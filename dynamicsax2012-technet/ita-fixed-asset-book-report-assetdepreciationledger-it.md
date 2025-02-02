---
title: (ITA) Fixed asset book report (AssetDepreciationLedger_IT)
TOCTitle: (ITA) Fixed asset book report (AssetDepreciationLedger_IT)
ms:assetid: 221ea0f6-177e-4ca4-97cb-009f16213804
ms:mtpsurl: https://technet.microsoft.com/library/Hh352240(v=AX.60)
ms:contentKeyID: 36687865
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.AssetDepreciationLedger_IT
- (ITA)
- Fixed asset book report
---

# (ITA) Fixed asset book report (AssetDepreciationLedger\_IT) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Italian fixed asset book** report displays information about Italian fixed asset books. You can select whether to include summarized information or detailed information about the books. This report is used to inquire into the status of fixed asset transactions and review the status of fixed asset processes. This report is typically used by accountants, accounting managers, accounting supervisors, accounts payable managers, chief executive officers, chief financial officers, compliance managers, financial controllers, and chief financial controllers.


> [!NOTE]
> <P>(ITA) This report is available only to legal entities whose primary address is in Italy.</P>



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
<td><p><strong>Closing date prior year</strong></p></td>
<td><p>Enter the closing date for the prior year.</p></td>
</tr>
<tr class="even">
<td><p><strong>Closing date this year</strong></p></td>
<td><p>Enter the closing date for this year.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Detailed print</strong></p></td>
<td><p>Select this check box to include detailed information about the asset books. By default, this check box is not selected.</p></td>
</tr>
<tr class="even">
<td><p><strong>Fixed asset group</strong></p></td>
<td><p>The identification of the fixed asset group.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Fixed asset number</strong></p></td>
<td><p>The fixed asset identification number.</p></td>
</tr>
<tr class="even">
<td><p><strong>Posting layer</strong></p></td>
<td><p>The posting layer code for current transactions, operating transactions, or fiscal transactions.</p></td>
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
<td><p>AssetDepreciationLedger_IT</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\AssetDepreciationLedger_IT</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>AssetDepreciationLedger_IT</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Fixed assets</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Italian fixed asset book</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TmpAssetFixedBook table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the AssetDepreciationLedgerDP_IT.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


