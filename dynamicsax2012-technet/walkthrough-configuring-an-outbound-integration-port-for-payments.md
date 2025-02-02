---
title: 'Walkthrough: Configuring an outbound integration port for payments'
TOCTitle: 'Walkthrough: Configuring an outbound integration port for payments'
ms:assetid: b2a8b438-981d-49ec-ab1a-5dbbde686a57
ms:mtpsurl: https://technet.microsoft.com/library/Hh446522(v=AX.60)
ms:contentKeyID: 36956800
author: Khairunj
ms.date: 08/22/2014
mtps_version: v=AX.60
f1_keywords:
- payments
- vendor payment
---

# Walkthrough: Configuring an outbound integration port for payments 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX, you can use a service to create electronic payment files. Before you can use the service, you must configure an outbound integration port. This topic describes how to set up an outbound integration port for payments that use Application Integration Framework (AIF) and Single Euro Payments Area (SEPA) Credit Transfer. **SEPACreditTransfer** is one of the payment format XSL transforms that is available. This topic assumes that you are familiar with AIF in Microsoft Dynamics AX 2012. For background information about AIF, see [Services and Application Integration Framework (AIF)](https://go.microsoft.com/fwlink/?linkid=216851).

In this walkthrough, you will export an XML style sheet from the Application Object Tree (AOT), set up a batch job to generate XML files, and set up an outbound port for electronic payments. You can also add an outbound transform, if a special XML format is required by the bank that you are processing payments for. For this walkthrough, use the **SEPACreditTransfer** format.

## Options for electronic payment formats

The following options for electronic payment formats are available in Microsoft Dynamics AX: File input-output formats and AIF service formats. Electronic payments can be made by using AIF service formats starting in Microsoft Dynamics AX 2012. AIF services provide a flexible and extensible framework for payment generation. You can easily add and remove payment formats. You can also add more XSL or binary transforms to generate payment files. If changes are required for a payment format, you do not have to change Microsoft Dynamics AX. Instead, you can modify the XSLT file.

By default, the following payment format XSL transforms are available in Microsoft Dynamics AX 2012.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Country/region</p></th>
<th><p>Format</p></th>
<th><p>Customer payment or vendor payment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>All</p></td>
<td><p>SEPA CreditTransfer</p></td>
<td><p>Vendor payment</p></td>
</tr>
<tr class="even">
<td><p>All</p></td>
<td><p>SEPADirectDebit</p></td>
<td><p>Customer payment</p></td>
</tr>
<tr class="odd">
<td><p>Italy (IT)</p></td>
<td><p>Fornitori</p></td>
<td><p>Vendor payment</p></td>
</tr>
<tr class="even">
<td><p>Sweden (SE)</p></td>
<td><p>Bankgirot</p></td>
<td><p>Vendor payment</p></td>
</tr>
<tr class="odd">
<td><p>Switzerland (CH)</p></td>
<td><p>EZAG</p></td>
<td><p>Vendor payment</p></td>
</tr>
</tbody>
</table>


The file input-output payment formats are available in Microsoft Dynamics AX 2012 and in earlier releases of Microsoft Dynamics AX. For information about file input-output payment formats, see [Configuring customer payment formats](configuring-customer-payment-formats.md) and [Configuring vendor payment formats](configuring-vendor-payment-formats.md).

## Overview of payment generation by using AIF

The **CustPaymentsService** and **VendPaymentsService** services expose payment information for the AIF outbound processing service. These services are based on Microsoft Dynamics AX queries. The queries capture all the data that is required to generate electronic payment files for customers or vendors. Developers can modify the service, document, and data object classes by using the AIF document service wizard.

First, set up the AIF transforms by following the instructions in this topic. You can then export payment data that is defined by the queries. An XSL transform can be applied to this data to transform the AIF XML file to the payment file for a specified format.

For every payment format that you intend to generate by using AIF, you must have a corresponding XSLT file. This XSLT file is based on the format that is specified by the bank. Several XSLT files are provided with Microsoft Dynamics AX. However, you can create your own XSLT file by using a text editor or XML editor.

For payment files that are not in XML format, you must apply an outbound transform to convert the XML results to a flat file. Outbound transforms can be of any file type, such as binary or XSLT. When you apply the outbound transform to the XML file that is generated by AIF, the XML tags are removed and the payment file is created in the format that is required by the bank.

In addition to the master data, payment-specific data might be required for each file, depending on the requirements of the bank. This data can be associated with outbound ports, and can be defined in the **Payment processing data** form by the system administrator. Then, when users generate payments, the users can enter values in the fields.

The following illustration shows the steps that are required to configure and use payment formats by using AIF services. The instructions in this topic explain how to complete the steps that are performed by a system administrator.

![Process to configure and use AIF SEPA payments](images/Hh446522.AIF_SEPA_Payment_Process(AX.60).gif "Process to configure and use AIF SEPA payments")

## User roles

A system administrator configures the outbound integration ports for payments. This user must have access to the **Outbound ports for electronic payments** form. This form is used to create the outbound port and define the payment processing data for each payment format that is used. The administrator selects the outbound folder and XSLT file that are used for a specific format. For more information about this process, see the sections later in this topic.

A business user performs the periodic task to create and settle payments with invoices, and to generate the relevant electronic payment files for those payments. The user experience resembles the process of generating payments by using the file input-output payment formats. The user selects the payment format and the format-specific data that is required to generate the payments.

## Prerequisites

You must be a member of the System Administrator (-SYSADMIN-) role to configure outbound integration ports for payments.

Identify a file location where the system administrator and the users who will generate payments both have **Write** access. You will create a folder in this location.

## 1\. Export the XML style sheet for the payment format from the AOT

The XSLT files for the payment formats are stored in the **Resources** node of the Application Object Tree (AOT). The name of each payment format for customer payments starts with CustPayments\_, and the name of each payment format for vendor payments starts with VendPayments\_. For this walkthrough, export the VendPayments\_SEPACreditTransfer\_xslt file.

1.  Create the folder to export the XSLT file to. The administrator and all Microsoft Dynamics AX users who generate payment files must have **Write** access to this folder. For example, the folder might be named c:\\AX\\SEPA.

2.  Log on to Microsoft Dynamics AX as an administrator.

3.  Click the **Windows** icon button at the top of the screen, and then click **New Development Workspace**.

4.  Open the AOT, and then expand the **Resources** node.

5.  Right-click **VendPayments\_SEPACreditTransfer\_xslt**, and then click **Open**.

6.  Click **Export**.

7.  Select the folder that you created in step 1, and then click **Save**.

8.  Close the **Preview** form and the development workspace.

## 2\. Set up a batch job to generate XML payment files

A batch job runs periodically. You must set up a batch job that automatically processes documents that are created by the service that you will set up later in this topic.

1.  Log on to Microsoft Dynamics AX as an administrator.

2.  Switch to the legal entity that users will generate payments from.

3.  Click **System administration** \> **Inquiries** \> **Batch jobs** \> **Batch jobs**.

4.  Press CTRL+N to create a batch job.

5.  In the **Job description** field, enter a description. For example, you might enter Generate SEPA payments.

6.  Save the batch job.

7.  Click **View tasks**.

8.  Create the following tasks.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p><strong>Task description</strong></p></th>
    <th><p><strong>Company accounts</strong></p></th>
    <th><p>Class name</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>1</p></td>
    <td><p>Select the legal entity that users will generate payments from.</p></td>
    <td><p><strong>AIFGatewaySendService</strong></p></td>
    </tr>
    <tr class="even">
    <td><p>2</p></td>
    <td><p>Select the legal entity that users will generate payments from.</p></td>
    <td><p><strong>AIFOutboundProcessingService</strong></p></td>
    </tr>
    </tbody>
    </table>


9.  Close the **Batch tasks** form.

10. In the **Batch job** form, select the batch that you created in steps 4 and 5, and then click **Recurrence**.

11. In the **Recurring pattern** field group, select **Minutes**, and then enter the number of minutes in the **Count** field. For example, you might enter 1 to process payment files every one minute.

12. Click **OK** to close the **Recurrence** form.

13. In the **Batch job** form, select the batch that you created in steps 4 and 5, and then click **Functions** \> **Change status**.

14. Select **Waiting**.

15. Close the **Batch job** form.

## 3\. Set up outbound ports for electronic payment formats

The **SEPACreditTransfer** format is used by multiple countries/regions. Follow these steps to specify the country/region and other information that is required for this payment format. You can use the same forms to specify information for other payment formats. However, the fields that are available might differ for other payment formats.

1.  Log on to Microsoft Dynamics AX as an administrator.

2.  Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Electronic payment services** \> **Outbound ports for electronic payments**.

3.  In the **Payment format** field, select **SEPACreditTransfer**.

4.  In the **XSLT** field, select the XSLT file that you previously saved. For example, the location of the XSLT file might be c:\\AX\\SEPA\\SEPAVend.xsl.

5.  In the **Outbound folder** field, select the location where you want to save the payment files after they are transformed. For example, the location might be c:\\AX\\SEPA.
    

    > [!NOTE]
    > <P>Make sure that the Microsoft Dynamics AX users who will generate payments have <STRONG>Write</STRONG> access to this folder.</P>



6.  Click **Create ports**.

7.  Select the **SEPACreditTransfer** payment format, and then click **Payment processing data**.

8.  Enter the following information that is specific to the **SEPACreditTransfer** payment format.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Processing date</strong></p></td>
    <td><p>Enter the first date that payments will be processed. This date can be changed when users generate payments.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Format</strong></p></td>
    <td><p>Enter Strd.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Country</strong></p></td>
    <td><p>Enter the two-character International Organization for Standardization (ISO) abbreviation for the country/region. For example, for Germany, enter DE.</p>
    <ul>
    <li><p>Austria – AT</p></li>
    <li><p>Belgium – BE</p></li>
    <li><p>Finland – FI</p></li>
    <li><p>France – FR</p></li>
    <li><p>Germany – DE</p></li>
    <li><p>Italy – IT</p></li>
    <li><p>Netherlands – NL</p></li>
    <li><p>Spain – ES</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


9.  Close the **Payment processing data** and **Outbound ports for electronic payments** forms.

## 4\. Optional: Add an outbound transform

If the payment file requires additional modifications to meet the requirements of the bank, you can add an outbound transform.

1.  Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Outbound ports**.

2.  Select the port that you created in the previous section, and then click the **Processing options** FastTab.

3.  Select the **Transform all responses** check box, and then click **Outbound transforms**.

4.  Click **New**.

5.  Select the transform to apply after the first transform is applied. For example, you might add an XSLT file that removes the header information that the AIF process inserted. You can even include binary files as part of the outbound transform, to perform additional processing on the payment file.

6.  Close the **Outbound transforms** and **Outbound ports** forms.

## Next steps

Before an electronic payment can be generated for a customer or a vendor, a user must specify information for the customer’s bank or the vendor’s bank. For more information, see the following topics:

  - [Set up a bank account for a customer account](set-up-a-bank-account-for-a-customer-account.md)

  - [Specify when a vendor bank account is active](specify-when-a-vendor-bank-account-is-active.md)

  - [Customer bank accounts (form)](https://technet.microsoft.com/library/aa575695\(v=ax.60\))

  - [Vendor bank accounts (form)](https://technet.microsoft.com/library/aa589805\(v=ax.60\))

A user can enter a vendor invoice, and then enter and settle a payment with the invoice. Then, the user can generate the payment. For information about how to create vendor invoices, see [Key tasks: Vendor invoices](key-tasks-vendor-invoices.md).

## See also

[AIF outbound ports (form)](https://technet.microsoft.com/library/hh227495\(v=ax.60\))

[AIF outbound transforms (form)](https://technet.microsoft.com/library/hh208828\(v=ax.60\))

[Batch job (form)](https://technet.microsoft.com/library/aa585684\(v=ax.60\))

[Generate payments - customer (class form)](https://technet.microsoft.com/library/aa554105\(v=ax.60\))

[Generate payments - vendor (class form)](https://technet.microsoft.com/library/aa586980\(v=ax.60\))

[Outbound ports for electronic payments (form)](https://technet.microsoft.com/library/hh208616\(v=ax.60\))

[Payment processing data (form)](https://technet.microsoft.com/library/hh242773\(v=ax.60\))

[Recurrence (form)](https://technet.microsoft.com/library/aa616143\(v=ax.60\))

  


