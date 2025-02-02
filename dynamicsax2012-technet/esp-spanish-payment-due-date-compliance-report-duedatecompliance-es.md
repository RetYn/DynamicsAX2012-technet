---
title: (ESP) Spanish payment due date compliance report (DueDateCompliance_ES)
TOCTitle: (ESP) Spanish payment due date compliance report (DueDateCompliance_ES)
ms:assetid: b89f7b1f-9a50-49ef-a429-f73b4e34b07e
ms:mtpsurl: https://technet.microsoft.com/library/Dn584138(v=AX.60)
ms:contentKeyID: 60936834
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Spain
- SSRS_Reports.Reports.DueDateCompliance_ES
- ES - 00004
- payment due date compliance
- payments due date compliance
---

# (ESP) Spanish payment due date compliance report (DueDateCompliance\_ES) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Spanish payments due date compliance report** form to generate the Payments due date compliance report for a legal entity. You can generate the Payments due date compliance report for vendor transactions, such as invoices, payment journals, and promissory note journals. This report is generated by accountants.


> [!NOTE]
> <P>In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2: The report takes into account the payments that are made by using promissory notes that have a status of <STRONG>Drawn</STRONG>, <STRONG>Remitted</STRONG>, or <STRONG>Honored</STRONG>.</P>



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
<td><p><strong>From</strong> <br />
(In the <strong>Current period</strong> field group)</p></td>
<td><p>Enter the starting date of the current period, for which the report is to be generated.</p></td>
</tr>
<tr class="even">
<td><p><strong>To</strong> <br />
(In the <strong>Current period</strong> field group)</p></td>
<td><p>Enter the ending date of the current period, for which the report is to be generated.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From</strong> <br />
(In the <strong>Comparative period</strong> field group)</p></td>
<td><p>Enter the starting date of the comparative fiscal period, for which the report is to be generated.</p></td>
</tr>
<tr class="even">
<td><p><strong>To</strong> <br />
(In the <strong>Comparative period</strong> field group)</p></td>
<td><p>Enter the ending date of the comparative fiscal period, for which the report is to be generated.</p></td>
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
<td><p>DueDateCompliance_ES</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\DueDateCompliance_ES</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>DueDateCompliance_ES</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Spanish payments due date compliance report</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TmpDueDateCompliance\_ES
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the DueDateComplianceDP_ES.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(ESP) Generate the payment due date compliance report](esp-generate-the-payment-due-date-compliance-report.md)

  


