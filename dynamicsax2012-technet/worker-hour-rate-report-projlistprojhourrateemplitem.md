---
title: Worker hour rate report (ProjListProjHourRateEmplItem)
TOCTitle: Worker hour rate report (ProjListProjHourRateEmplItem)
ms:assetid: 614a83de-9d13-483b-8b11-b3820c0414dc
ms:mtpsurl: https://technet.microsoft.com/library/Aa584767(v=AX.60)
ms:contentKeyID: 37832006
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Worker hour rate report (ProjListProjHourRateEmplItem) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to analyze rate per hour, value-added rate per hour, cost per hour, and gross margin per hour by project.

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
<td><p><strong>Include project types</strong></p></td>
<td><p>Select the project types that you want to include on the report. You must select at least one project type.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include transaction types</strong></p></td>
<td><p>Select the transaction types that you want to include on the report. By default, hour transaction types are included on the report.</p></td>
</tr>
<tr class="odd">
<td><p>(<strong>Project date</strong>)</p>
<p><strong>From date</strong> / <strong>To date</strong></p></td>
<td><p>Specify a starting date and an ending date for hour transactions posted to projects to include on the report.</p></td>
</tr>
<tr class="even">
<td><p>(<strong>Ledger date</strong>)</p>
<p><strong>From date</strong> / <strong>To date</strong></p></td>
<td><p>Specify a starting date and an ending date for hour transactions posted to the general ledger to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Actual vs. budget</strong></p></td>
<td><p>Select <strong>Actual</strong> to display actual values on the report.</p>
<p>Select <strong>Budget</strong> to display budgeted values on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Forecast model</strong></p></td>
<td><p>Select the forecast model that you want the report to use.</p>
<div class="alert">

> [!NOTE]
> <P>If you are using project budget control, select the budget forecast model that is used by this project.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Skip blank ID</strong></p></td>
<td><p>Select whether to exclude transactions that are not assigned to a project.</p></td>
</tr>
<tr class="even">
<td><p><strong>Skip zero</strong></p></td>
<td><p>Select whether to exclude all rows on the report where the amounts are equal to zero.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Item number</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Worker hour rate</strong> form, in the <strong>Criteria</strong> field, select an item number to include on the report. To add more than one item, click <strong>Add</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Service subscription</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Worker hour rate</strong> form, in the <strong>Criteria</strong> field, select a service subscription to include on the report. To add more than one service subscription, click <strong>Add</strong>.</p></td>
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
<td><p>ProjHourRateEmpl</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjHourRateEmpl</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjListProjHourRateEmplItem</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Project statements</strong> &gt; <strong>Hour rate</strong> &gt; <strong>Worker hour rate</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjListProjHourRateEmplItemDP.processReport

  - DirPerson table

  - HcmWorker table

  - InventTable table

  - ProjListProjProfitLossTmp table

  - SMASubscriptionTable


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the ProjListProjHourRateEmplItemDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


