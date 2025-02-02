---
title: (DEU) DTAUS report (VendOutAttendingNoteDE_DTAUS)
TOCTitle: (DEU) DTAUS report (VendOutAttendingNoteDE_DTAUS)
ms:assetid: 5412f5c5-962f-496c-88e4-3e712be9487c
ms:mtpsurl: https://technet.microsoft.com/library/Hh335148(v=AX.60)
ms:contentKeyID: 36687359
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendOutAttendingNoteDE_DTAUS
- note
- attending note
- DTAUS
---

# (DEU) DTAUS report (VendOutAttendingNoteDE\_DTAUS) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **DTAUS (DE)** report prints the payment advice for electronic vendor payments. This report is typically used by credit managers and collections managers.

Before you print this report, you must set up a payment method with **DTAUS (DE)** as the export format in the **Methods of payment - vendors** form.


> [!NOTE]
> <P>(DEU) This report is available only to legal entities whose primary address is in Germany.</P>



## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Bank account</strong></p></td>
<td><p>The bank account number that is selected in the <strong>Generate payments</strong> form.</p></td>
</tr>
<tr class="even">
<td><p><strong>Currency</strong></p></td>
<td><p>Select the currency code used in the vendor payment transaction.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Processing date</strong></p></td>
<td><p>Enter the processing date of the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Covering letter from quantity of invoices</strong></p></td>
<td><p>Enter the minimum quantity of invoices required to print a cover letter. You can enter a value between 1 and 14.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Disk number</strong></p></td>
<td><p>Enter the disk number.</p></td>
</tr>
<tr class="even">
<td><p><strong>Transmute umlauts</strong></p></td>
<td><p>Select this check box to translate umlauts from German to English. For example, Ä is displayed as Ae.</p></td>
</tr>
<tr class="odd">
<td><p><strong>File name</strong></p></td>
<td><p>Enter the file name and path of the file to which the payment details are exported.</p></td>
</tr>
<tr class="even">
<td><p><strong>Control report</strong></p></td>
<td><p>Select this check box to print the control report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Attending note</strong></p></td>
<td><p>Select this check box to print the attending note.</p></td>
</tr>
</tbody>
</table>


## How to work with reports

The following topics explain how to print a report and how to filter and sort the data on a report.

  - [Print or email a report](print-or-email-a-report.md)

  - [Filter the data on a report](filter-the-data-on-a-report.md)

  - [Sort the data on a report](sort-the-data-on-a-report.md)

## Details of this report

The following table explains where to find the report in the Application Object Tree (AOT) and how to navigate to the report in the Microsoft Dynamics AX client.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Detail</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Name of report in the AOT</p></td>
<td><p>VendOutAttendingNoteDE_DTAUS</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendOutAttendingNoteDE_DTAUS</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendOutAttendingNote_DEDTAUS</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Select a journal name, and then click <strong>Lines</strong>. Click <strong>Functions</strong> &gt; <strong>Generate payments</strong>. In the <strong>Export format</strong> field, select <strong>DTAUS (DE)</strong>. In the <strong>Bank account</strong> field, select a bank account, and then click <strong>Dialog</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendOutAttendingNoteTmpDE\_DTAUS table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the VendOutAttendingNoteDEDP_DTAUS.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


