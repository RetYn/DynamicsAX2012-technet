---
title: (MEX) Inflation adjustment report (InfAdjInventory_MX)
TOCTitle: (MEX) Inflation adjustment report (InfAdjInventory_MX)
ms:assetid: 0add9852-cb0f-498d-82d9-715edcccee8b
ms:mtpsurl: https://technet.microsoft.com/library/Hh416706(v=AX.60)
ms:contentKeyID: 36931893
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Adjustment
- SSRS_Reports.Reports.InfAdjInventory_MX
- MEX
- Inflation
---

# (MEX) Inflation adjustment report (InfAdjInventory\_MX) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Inflation adjustment** report prints the adjustment inflation data in the financial statements for inventory accounts. This report is used to report the financial transactions that are generated when the inflation adjustment process is run. This report is typically used by accountants, accounting managers, accounting supervisors, accounts payable clerks, accounts payable managers, accounts receivable managers, chief executive officers, chief financial officers, compliance mangers, and financial controllers.


> [!NOTE]
> <P>(MEX) This report is available only to legal entities whose primary address is in Mexico.</P>



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
<td><p><strong>Adjustment method</strong></p></td>
<td><p>Select the adjustment method that is used to filter the transactions from the following options:</p>
<ul>
<li><p><strong>None</strong> – The inflation is not adjusted.</p></li>
<li><p><strong>Transaction date</strong> - The adjustment method is based on the transaction date. The account type can be <strong>Equity</strong>, <strong>Asset</strong>, <strong>Liability</strong>, or <strong>Balance sheet</strong>.</p></li>
<li><p><strong>Opening balance</strong> - The adjustment method is based on the opening account balance. The account type can be <strong>Asset</strong>, <strong>Liability</strong>, or <strong>Balance sheet</strong>.</p></li>
<li><p><strong>Monthly balance</strong> - The adjustment method is based on the monthly account balance. The account type can be <strong>Profit and loss</strong>, <strong>Expense</strong>, or <strong>Revenue</strong>.</p></li>
<li><p><strong>Balance</strong> - The adjustment method is based on the account balance.</p></li>
</ul></td>
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
<td><p>InfAdjInventory_MX</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\InfAdjInventory_MX</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>InfAdjInventory_MX</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Periodic</strong> &gt; <strong>Inflation adjustment B-10</strong>. Select an inflation adjustment record, and then click <strong>Print report</strong> &gt; <strong>Inventory</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - InvAdjustmentReportTmp\_MX table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the InfAdjReportsDP_MX.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


