---
title: (CHN) Summarized general ledger (report)
TOCTitle: (CHN) Summarized general ledger (report)
ms:assetid: 1a0d887b-112a-4364-bccd-9aba5bdecc80
ms:mtpsurl: https://technet.microsoft.com/library/JJ874404(v=AX.60)
ms:contentKeyID: 50619721
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CHN) Summarized general ledger (report) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Generate a report that displays a summary of selected ledger accounts during a specified time period.

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
<td><p><strong>From account</strong></p></td>
<td><p>Select the first account in the list of accounts to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To account</strong></p></td>
<td><p>Select the last account in the list of accounts to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Fiscal year</strong></p></td>
<td><p>Select the fiscal year for the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Period name</strong></p></td>
<td><p>Select the period within the selected fiscal year to use for calculating the report.</p></td>
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
<td><p>LedgerSummarizedGL_CN</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>Forms\LedgerSummarizedGL_CN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerSummarizedGL_CN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Inquiries</strong> &gt; <strong>Summarized general ledger</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TmpSummarizeGL\_CN

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


