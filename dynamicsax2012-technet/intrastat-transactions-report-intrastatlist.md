---
title: Intrastat transactions report (IntrastatList)
TOCTitle: Intrastat transactions report (IntrastatList)
ms:assetid: 4c3cea89-3999-4daa-80fa-56782acdea3e
ms:mtpsurl: https://technet.microsoft.com/library/Aa576461(v=AX.60)
ms:contentKeyID: 37831999
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.IntrastatList
- SSRS_Reports.Reports.IntrastatListES
- SSRS_Reports.Reports.IntrastatListFI
- SSRS_Reports.Reports.IntrastatListNL
- SSRS_Reports.Reports.IntrastatListUK
---

# Intrastat transactions report (IntrastatList) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to print a list of Intrastat records.

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
<td><p><strong>From</strong></p></td>
<td><p>Enter the first date in the range of dates to include Intrastat transactions for on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To</strong></p></td>
<td><p>Enter the last date in the range of dates to include Intrastat transactions for on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Both</strong></p></td>
<td><p>Select this check box to include transactions for both arrivals and dispatches.</p>
<p>Clear this check box to enable the <strong>Direction</strong> field, where you can select either <strong>Arrivals</strong> or <strong>Dispatches</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Direction</strong></p></td>
<td><p>Select the type of Intrastat transaction to include on the report:</p>
<ul>
<li><p><strong>Arrivals</strong> – Include only transactions that record the arrival of products from other countries/regions.</p></li>
<li><p><strong>Dispatches</strong> – Include only transactions that record the shipment of products to other countries/regions.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Only corrections</strong></p></td>
<td><p>Select this check box to include only transactions that have the <strong>Correction</strong> check box selected in the <strong>Intrastat</strong> form.</p></td>
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
<td><p>IntrastatList</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\IntrastatList</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>IntrastatListAT</p>
<p>IntrastatListDE</p>
<p>IntrastatListDK</p>
<p>IntrastatListSE</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Organization administration</strong> &gt; <strong>Periodic</strong> &gt; <strong>Foreign trade</strong> &gt; <strong>Intrastat</strong>. Click <strong>Output</strong> &gt; <strong>List AT</strong>.</p>
<p>Click <strong>Organization administration</strong> &gt; <strong>Periodic</strong> &gt; <strong>Foreign trade</strong> &gt; <strong>Intrastat</strong>. Click <strong>Output</strong> &gt; <strong>List DE</strong>.</p>
<p>Click <strong>Organization administration</strong> &gt; <strong>Periodic</strong> &gt; <strong>Foreign trade</strong> &gt; <strong>Intrastat</strong>. Click <strong>Output</strong> &gt; <strong>List DK</strong>.</p>
<p>Click <strong>Organization administration</strong> &gt; <strong>Periodic</strong> &gt; <strong>Foreign trade</strong> &gt; <strong>Intrastat</strong>. Click <strong>Output</strong> &gt; <strong>List SE</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - IntrastatFormLetterListTmp table

To find out where the data in the temp table comes from, view the cross-references for the IntrastatListDP.processReport class.

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


