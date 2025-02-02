---
title: Workflow participants performance report (WorkflowParticipantPerformanceReport)
TOCTitle: Workflow participants performance report (WorkflowParticipantPerformanceReport)
ms:assetid: f4e765e0-6125-416d-88f7-0ea152fb943c
ms:mtpsurl: https://technet.microsoft.com/library/Hh334506(v=AX.60)
ms:contentKeyID: 36676496
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.WorkflowParticipantPerformanceReport
---

# Workflow participants performance report (WorkflowParticipantPerformanceReport) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Workflow participants performance** report shows information about specific workflow participants. For example, the report shows the average time it took for a specific participant to complete a work item. The report also shows the number of work items that the participant completed, approved, and rejected.

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
<td><p><strong>Element type</strong></p></td>
<td><p>Select a workflow element. For more information about workflow elements, see <a href="workflow-elements.md">Workflow elements</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>End date</strong></p></td>
<td><p>Select an end date.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Participant</strong></p></td>
<td><p>Enter the name of a workflow participant.</p></td>
</tr>
<tr class="even">
<td><p><strong>Start date</strong></p></td>
<td><p>Select a start date.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Workflow name</strong></p></td>
<td><p>Enter the name of a workflow.</p></td>
</tr>
<tr class="even">
<td><p><strong>Participant type</strong></p></td>
<td><p>Enter the type of participant.</p></td>
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
<td><p>WorkflowParticipantPerformanceReport</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\WorkflowParticipantPerformanceReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>WorkflowParticipantReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Organization administration</strong> &gt; <strong>Reports</strong> &gt; <strong>Workflow</strong> &gt; <strong>Workflow participants performance</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - Workflow cube

  - BIDATEDIM\_DATE table

  - WORKFLOWCUBEELEMENTLOOKUP table

  - WORKFLOWCUBELOOKUP table

  - WORKFLOWCUBETRANSACTION table

  - WORKFLOWCUBETRANSACTION\_DIM table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


