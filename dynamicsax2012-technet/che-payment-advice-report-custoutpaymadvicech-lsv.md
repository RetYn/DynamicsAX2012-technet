---
title: (CHE) Payment advice report (CustOutPaymAdviceCH_LSV)
TOCTitle: (CHE) Payment advice report (CustOutPaymAdviceCH_LSV)
ms:assetid: 0d258003-4edb-4fd5-bf8a-e7826bfdacda
ms:mtpsurl: https://technet.microsoft.com/library/Hh404032(v=AX.60)
ms:contentKeyID: 36956683
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustOutPaymAdviceCH_LSV
---

# (CHE) Payment advice report (CustOutPaymAdviceCH\_LSV) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Payment advice** report prints payment advice for customer payments that are made by using the **LSV (CH)** export format. You must select **LSV (CH)** in the **Export format** field in the **Generate payments** form. This report is typically used by accounts receivable payments clerks to maintain customer payments.


> [!NOTE]
> <P>(CHE) This report is available only to legal entities whose primary address is in Switzerland.</P>



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
<td><p>CustOutPaymAdviceCH_LSV</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustOutPaymAdviceCH_LSV</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustOutPaymAdviceReportCH_LSV</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, click <strong>Functions</strong> &gt; <strong>Generate payments</strong>. In the <strong>Export format</strong> field, select <strong>LSV (CH)</strong>. Enter the required details, and then click <strong>OK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustVendOutTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the CustOutPaymAdviceDP_CHLSV.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Generate payments - customer (class form)](https://technet.microsoft.com/library/aa554105\(v=ax.60\))

  


