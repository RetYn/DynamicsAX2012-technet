---
title: Payment control report (CustOutPaymControl)
TOCTitle: Payment control report (CustOutPaymControl)
ms:assetid: a099829c-a01b-4762-8917-8b87e5dee3fc
ms:mtpsurl: https://technet.microsoft.com/library/Hh538457(v=AX.60)
ms:contentKeyID: 39508885
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustOutPaymControl
---

# Payment control report (CustOutPaymControl) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Payment control** report to view a list of payments that are generated. The report includes customer account information, bank account numbers, and payment amounts in both the transaction currency and the accounting currency.

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
<td><p>CustOutPaymControl</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustOutPaymControl</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustOutPaymControl</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Create or select a payment journal, and then click <strong>Lines</strong>. Enter a line, and then click <strong>Functions</strong> &gt; <strong>Generate payments</strong>. Select the <strong>Export format</strong> option, and then select the <strong>cust Format 1 (Test)</strong> export format. Select a bank account, select the <strong>Show format dialog</strong> check box, and then click <strong>OK</strong>. In the <strong>cust Format 1 (Test)</strong> dialog box, select the <strong>Control report</strong> check box, and then click <strong>OK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustVendOutTmp table

  - TmpAccountSum table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the CustOutPaymControlDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


