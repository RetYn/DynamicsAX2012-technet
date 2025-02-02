---
title: Worker/category validation report (ProjValEmplCategory)
TOCTitle: Worker/category validation report (ProjValEmplCategory)
ms:assetid: 2b9177aa-2067-4c03-9f4c-74949f7d116b
ms:mtpsurl: https://technet.microsoft.com/library/Aa552275(v=AX.60)
ms:contentKeyID: 37831986
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjValEmplCategory
---

# Worker/category validation report (ProjValEmplCategory) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To control how project transactions are recorded, you can limit the values that are available in journals and timesheets for workers, projects, and categories. You can also set up rules to prevent posting of transactions that violate the validation rules. Use this report to view a list of the workers and categories for which validation is enabled.

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
<td><p><strong>Include transaction types</strong></p></td>
<td><p>Select the transaction types that you want to include on the report. You must select at least one transaction type.</p></td>
</tr>
<tr class="even">
<td><p><strong>Validation</strong></p></td>
<td><p>Select how you want to display the first column of the report from the following options:</p>
<ul>
<li><p><strong>Worker</strong> – Display workers in the selected validation groups.</p></li>
<li><p><strong>Category</strong> – Display categories in the selected validation groups.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Worker/category</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>ProjValEmplCategory</strong> form, in the <strong>Criteria</strong> field, select a worker/category to include on the report. To add more than one worker/category, click <strong>Add</strong>.</p></td>
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
<td><p>ProjValEmplCategory</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjValEmplCategory</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjListValEmplCategory</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Base data</strong> &gt; <strong>Validation</strong> &gt; <strong>Worker/category validation</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - ProjValEmplCategoryDP.processReport

  - ProjValEmplCategorySetUp table

  - ProjValEmplCategoryTable


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the ProjValEmplCategoryDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


