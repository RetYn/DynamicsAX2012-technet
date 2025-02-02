---
title: (CHN) Inventory status report
TOCTitle: (CHN) Inventory status report
ms:assetid: 8eaf7bba-ef8b-4925-b089-be7d0d774a40
ms:mtpsurl: https://technet.microsoft.com/library/Dn169463(v=AX.60)
ms:contentKeyID: 53865955
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CHN) Inventory status report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Generate and print a report that displays a summary of the starting and ending balance of your organization’s inventory during a specified time.

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
<td><p><strong>Start date</strong></p></td>
<td><p>Select the start date.</p></td>
</tr>
<tr class="even">
<td><p><strong>End date</strong></p></td>
<td><p>Select the end date.</p></td>
</tr>
<tr class="odd">
<td><p><strong>View</strong></p></td>
<td><p>Select the check boxes in the <strong>View</strong> group to include inventory dimensions on the report.</p></td>
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
<td><p>InventStatus_CN</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\InventStatus_CN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>InventStatusInPeriod_CN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Inventory management</strong> &gt; <strong>Reports</strong> &gt; <strong>Reports (China)</strong> &gt; <strong>Inventory status report</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - InventPhysQtySumTmp\_CN

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


