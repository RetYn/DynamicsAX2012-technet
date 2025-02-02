---
title: (FRA) Print bill of exchange report (BankBillOfExchange_FR)
TOCTitle: (FRA) Print bill of exchange report (BankBillOfExchange_FR)
ms:assetid: d80a26a2-d473-4c29-bf90-97fde51aa592
ms:mtpsurl: https://technet.microsoft.com/library/Hh335169(v=AX.60)
ms:contentKeyID: 36687383
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- bill of exchange
- SSRS_Reports.Reports.BankBillofExchange_FR
- (FRA)
- bill of exchange report
- Print bill of exchange
---

# (FRA) Print bill of exchange report (BankBillOfExchange\_FR) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Print bill of exchange** report prints a list of bills of exchange together with their details for legal entities operating in France. This report is typically used by accounting clerks and bookkeepers.

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
<td><p>BankBillOfExchange_FR</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BankBillOfExchange_FR</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BankBillOfExchange_FR</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Bill of exchange</strong> &gt; <strong>Draw bill of exchange journal</strong>. Click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, click <strong>Functions</strong> &gt; <strong>Generate payments</strong>. In the <strong>Generate payments</strong> form, in the <strong>Export format</strong> field, select <strong>French bill of exchange</strong>, and then click <strong>Dialog</strong>. In the <strong>French bill of exchange</strong> form, in the <strong>City</strong> field, enter the city of the legal entity, and then click <strong>OK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BankBillOfExchangeTmp\_FR table


> [!NOTE]
> <P>To find out where the data in the temp table comes from, view the cross-references for the BankBillOfExchangeDP_FR.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


