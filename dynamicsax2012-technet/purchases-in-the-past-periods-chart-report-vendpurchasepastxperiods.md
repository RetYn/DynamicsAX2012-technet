---
title: Purchases in the past periods chart report (VendPurchasePastXPeriods)
TOCTitle: Purchases in the past periods chart report (VendPurchasePastXPeriods)
ms:assetid: fe54ba8d-1ce1-425f-ab67-687518cf6b60
ms:mtpsurl: https://technet.microsoft.com/library/Hh538469(v=AX.60)
ms:contentKeyID: 39508900
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendPurchasePastXPeriods
---

# Purchases in the past periods chart report (VendPurchasePastXPeriods) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Purchases in the past periods** chart report to view the total purchases by a selected legal entity for the selected periods, in graphical form.

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
<td><p><strong>Company:</strong></p></td>
<td><p>Select the legal entity to print the total purchases for.</p></td>
</tr>
<tr class="even">
<td><p><strong>Year:</strong></p></td>
<td><p>Select the fiscal year to print information for.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Period:</strong></p></td>
<td><p>Select the last period to print information for.</p></td>
</tr>
<tr class="even">
<td><p><strong>Number of periods:</strong></p></td>
<td><p>Select the number of periods to print information for. The report will display information for the selected number of periods, with the period that you selected in the <strong>Period:</strong> field being the last period.</p></td>
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
<td><p>VendPurchasePastXPeriods</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\VendPurchasePastXPeriods</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendPurchasesPastXPeriods</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistics</strong> &gt; <strong>Vendor</strong> &gt; <strong>Purchases in the past periods</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DynamicsAXOLAP cube

  - BASEENUM\_FiscalQuarter table

  - BICOMPANYVIEW table

  - LEDGERPERIODDATEDIMENSIONVIEW table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


