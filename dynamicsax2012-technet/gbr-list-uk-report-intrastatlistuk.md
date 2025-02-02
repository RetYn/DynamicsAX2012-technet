---
title: (GBR) List UK report (IntrastatListUK)
TOCTitle: (GBR) List UK report (IntrastatListUK)
ms:assetid: 40eaba78-fbc7-44e2-aea8-e54d357abcd6
ms:mtpsurl: https://technet.microsoft.com/library/Hh433490(v=AX.60)
ms:contentKeyID: 36941251
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Intrastat
- SSRS_Reports.Reports.IntrastatListUK
- GBR
---

# (GBR) List UK report (IntrastatListUK) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **List UK** report lists all the Intrastat transactions with other European Union (EU) member states. This report is typically used by accounting managers, accountants, and accounting supervisors to inquire into the status of the Intrastat transactions.


> [!NOTE]
> <P>(GBR) This report is available only to legal entities whose primary address is in the United Kingdom.</P>



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
<td><p>Select or enter the starting date of the reporting period.</p></td>
</tr>
<tr class="even">
<td><p><strong>To</strong></p></td>
<td><p>Select or enter the ending date of the reporting period.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Direction</strong></p></td>
<td><p>Select the type of transactions to be included in the report from the following options:</p>
<ul>
<li><p><strong>Arrivals</strong> – Include details of purchases or arrivals from EU member states.</p></li>
<li><p><strong>Dispatches</strong> – Include details of sales or dispatches to EU member states.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Only corrections</strong></p></td>
<td><p>Select this check box to report only corrections to already-reported Intrastat transactions.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Shipment batch</strong></p></td>
<td><p>The shipment batch number of the Intrastat transactions.</p></td>
</tr>
<tr class="even">
<td><p><strong>Sequence number</strong></p></td>
<td><p>The sequence number for the Intrastat transactions in the shipment batch.</p></td>
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
<td><p>IntrastatListUK</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\IntrastatListUK</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>IntrastatListUK</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Organization administration</strong> &gt; <strong>Periodic</strong> &gt; <strong>Foreign trade</strong> &gt; <strong>Intrastat</strong>. Click <strong>Output</strong> &gt; <strong>List UK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - IntrastatListTmpUK table


> [!NOTE]
> <P>To find out where the data in the temp table comes from, view the cross-references for the IntrastatListDPUK.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


