---
title: Posting example 2 - fixed-price project
TOCTitle: Posting example 2 - fixed-price project
ms:assetid: 80623878-e3ea-41de-984d-3ee7fe46b00d
ms:mtpsurl: https://technet.microsoft.com/library/Aa571545(v=AX.60)
ms:contentKeyID: 36058339
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- fixed-price
- project posting
audience: Application User
ms.search.region: Global
---

# Posting example 2 - fixed-price project 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following tables provide an example for posting a fixed-price project.

## Ledger posting examples

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Project group parameters</p></th>
<th><p>Revenue recognition accounting rule</p></th>
<th><p>Matching principle</p></th>
<th><p>On-account invoicing</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p></p></td>
<td><p>Completed contract</p></td>
<td><p>Sales value</p></td>
<td><p>Balance</p></td>
</tr>
</tbody>
</table>



> [!TIP]
> <P>These project group parameters are set up on the <STRONG>Estimate</STRONG> FastTab in the <STRONG>Project groups</STRONG> form. Click <STRONG>Project management and accounting</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Posting</STRONG> &gt; <STRONG>Project groups</STRONG>.</P>



## Statistics - before estimate posting

<table style="width:100%;">
<colgroup>
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Statement P&amp;L</p></th>
<th><p>Positive amount</p></th>
<th><p>Jul</p></th>
<th><p>Aug</p></th>
<th><p>Sept</p></th>
<th><p>Oct</p></th>
<th><p>Nov</p></th>
<th><p>Dec</p></th>
<th><p>Total</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Accrued revenue - sales value</p></td>
<td><p>Credit</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
</tr>
<tr class="even">
<td><p>Revenue</p></td>
<td><p></p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
</tr>
<tr class="odd">
<td><p>Cost</p></td>
<td><p>Debit</p></td>
<td><p>12,000</p></td>
<td><p>30,000</p></td>
<td><p>24,000</p></td>
<td><p>36,000</p></td>
<td><p>18,000</p></td>
<td><p>0</p></td>
<td><p>120,000</p></td>
</tr>
<tr class="even">
<td><p>Gross margin</p></td>
<td><p></p></td>
<td><p>-12,000</p></td>
<td><p>-30,000</p></td>
<td><p>-24,000</p></td>
<td><p>-36,000</p></td>
<td><p>-18,000</p></td>
<td><p>0</p></td>
<td><p>-120,000</p></td>
</tr>
</tbody>
</table>


<table style="width:100%;">
<colgroup>
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Statement WIP (balance)</p></th>
<th><p>Positive amount</p></th>
<th><p>Jul</p></th>
<th><p>Aug</p></th>
<th><p>Sept</p></th>
<th><p>Oct</p></th>
<th><p>Nov</p></th>
<th><p>Dec</p></th>
<th><p>Total</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>WIP - cost value and WIP - cost value - item</p></td>
<td><p>Debit</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
</tr>
<tr class="even">
<td><p>Gross WIP</p></td>
<td><p></p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
</tr>
<tr class="odd">
<td><p>WIP - invoiced - on account</p></td>
<td><p>Credit</p></td>
<td><p>-80,000</p></td>
<td><p>0</p></td>
<td><p>-50,000</p></td>
<td><p>0</p></td>
<td><p>-70,000</p></td>
<td><p>0</p></td>
<td><p>-200,000</p></td>
</tr>
<tr class="even">
<td><p>Net WIP</p></td>
<td><p></p></td>
<td><p>-80,0000</p></td>
<td><p>0</p></td>
<td><p>-50,000</p></td>
<td><p>0</p></td>
<td><p>-70,000</p></td>
<td><p>0</p></td>
<td><p>-200,000</p></td>
</tr>
</tbody>
</table>


## Posting of estimate

<table style="width:100%;">
<colgroup>
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Statement P&amp;L</p></th>
<th><p>Positive amount</p></th>
<th><p>Jul</p></th>
<th><p>Aug</p></th>
<th><p>Sept</p></th>
<th><p>Oct</p></th>
<th><p>Nov</p></th>
<th><p>Dec</p></th>
<th><p>Total</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Accrued revenue - sales value</p></td>
<td><p>Credit</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>200,000</p></td>
<td><p>0</p></td>
</tr>
<tr class="even">
<td><p>Cost</p></td>
<td><p>Debit</p></td>
<td><p>-12,000</p></td>
<td><p>-30,000</p></td>
<td><p>-24,000</p></td>
<td><p>-36,000</p></td>
<td><p>-18,000</p></td>
<td><p>120,000</p></td>
<td><p>0</p></td>
</tr>
</tbody>
</table>


<table style="width:100%;">
<colgroup>
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Statement WIP (balance)</p></th>
<th><p>Positive amount</p></th>
<th><p>Jul</p></th>
<th><p>Aug</p></th>
<th><p>Sept</p></th>
<th><p>Oct</p></th>
<th><p>Nov</p></th>
<th><p>Dec</p></th>
<th><p>Total</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>WIP - cost value and WIP - cost value - item</p></td>
<td><p>Debit</p></td>
<td><p>12,000</p></td>
<td><p>30,000</p></td>
<td><p>24,000</p></td>
<td><p>36,000</p></td>
<td><p>18,000</p></td>
<td><p>-120,000</p></td>
<td><p>0</p></td>
</tr>
<tr class="even">
<td><p>WIP - invoiced - on account</p></td>
<td><p>Credit</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>-200,000</p></td>
<td><p>-200,000</p></td>
</tr>
</tbody>
</table>


## Statistics - after estimate posting

<table style="width:100%;">
<colgroup>
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Statement P&amp;L</p></th>
<th><p>Positive amount</p></th>
<th><p>Jul</p></th>
<th><p>Aug</p></th>
<th><p>Sept</p></th>
<th><p>Oct</p></th>
<th><p>Nov</p></th>
<th><p>Dec</p></th>
<th><p>Total</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Accrued revenue - sales value</p></td>
<td><p>Credit</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>200,000</p></td>
<td><p>200,00</p></td>
</tr>
<tr class="even">
<td><p>Revenue</p></td>
<td><p></p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>200,000</p></td>
<td><p>200,000</p></td>
</tr>
<tr class="odd">
<td><p>Cost</p></td>
<td><p>Debit</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>120,000</p></td>
<td><p>120,000</p></td>
</tr>
<tr class="even">
<td><p>Gross margin</p></td>
<td><p></p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>80,000</p></td>
<td><p>80,000</p></td>
</tr>
</tbody>
</table>


<table style="width:100%;">
<colgroup>
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Statement WIP (balance)</p></th>
<th><p>Positive amount</p></th>
<th><p>Jul</p></th>
<th><p>Aug</p></th>
<th><p>Sept</p></th>
<th><p>Oct</p></th>
<th><p>Nov</p></th>
<th><p>Dec</p></th>
<th><p>Total</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>WIP - cost value and WIP - cost value - item</p></td>
<td><p>Debit</p></td>
<td><p>12,000</p></td>
<td><p>30,000</p></td>
<td><p>24,000</p></td>
<td><p>36,000</p></td>
<td><p>18,000</p></td>
<td><p>-120,000</p></td>
<td><p>0</p></td>
</tr>
<tr class="even">
<td><p>Gross WIP</p></td>
<td><p></p></td>
<td><p>12,000</p></td>
<td><p>30,000</p></td>
<td><p>24,000</p></td>
<td><p>36,000</p></td>
<td><p>18,000</p></td>
<td><p>-120,000</p></td>
<td><p>0</p></td>
</tr>
<tr class="odd">
<td><p>WIP - invoiced - on account</p></td>
<td><p>Credit</p></td>
<td><p>80,000</p></td>
<td><p>0</p></td>
<td><p>50,000</p></td>
<td><p>0</p></td>
<td><p>70,000</p></td>
<td><p>-200,000</p></td>
<td><p>0</p></td>
</tr>
<tr class="even">
<td><p>Net WIP</p></td>
<td><p></p></td>
<td><p>-68,000</p></td>
<td><p>30,000</p></td>
<td><p>-26,000</p></td>
<td><p>36,000</p></td>
<td><p>-52,000</p></td>
<td><p>80,000</p></td>
<td><p>0</p></td>
</tr>
</tbody>
</table>


## See also

[About the fixed-price project posting examples](about-the-fixed-price-project-posting-examples.md)

[About invoicing fixed-price projects](about-invoicing-fixed-price-projects.md)

[Create an invoice for a fixed-price project](create-an-invoice-for-a-fixed-price-project.md)

[Project groups (form)](https://technet.microsoft.com/library/aa590435\(v=ax.60\))

[Configuring project groups](configuring-project-groups.md)

  


