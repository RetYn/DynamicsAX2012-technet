---
title: About action messages
TOCTitle: About action messages
ms:assetid: 4f08ad7e-ac31-4e26-9651-172d4b274368
ms:mtpsurl: https://technet.microsoft.com/library/Aa497126(v=AX.60)
ms:contentKeyID: 36057071
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- action messages
- about action messages
audience: Application User
ms.search.region: Global
---

# About action messages 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

An action message is a system-generated suggestion to change an existing planned order. Action messages are generated by the master scheduling calculation in response to changed requirements. For example, the due date or quantity may have changed because an order was firmed. You decide whether to make the changes that are suggested.

You can configure how action messages are calculated for a coverage group that you attach to an item. For more information, see [Coverage groups (form)](https://technet.microsoft.com/library/aa552922\(v=ax.60\)).

## Selecting action messages

In the **Coverage groups** form, you can select the action messages that you want the system to generate, and the coverage groups or items that the messages apply to. You can select the following action messages.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Message</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Advance</strong></p></td>
<td><p>One or more planned orders should be moved forward in time. If you select this message, in the <strong>Advance margin</strong> field, you can also specify the maximum number of days between orders that are advanced.</p></td>
</tr>
<tr class="even">
<td><p><strong>Postpone</strong></p></td>
<td><p>One or more planned orders should be postponed. If you select this message, in the <strong>Postpone margin</strong> field, you can also specify the maximum number of days that are permitted between orders that are postponed.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Decrease</strong></p></td>
<td><p>Production orders, purchase orders, and other receipt transactions should be decreased to prevent excess inventory levels.</p></td>
</tr>
<tr class="even">
<td><p><strong>Increase</strong></p></td>
<td><p>Production orders, purchase orders, and other receipt transactions should be increased to prevent shortages in inventory.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Derived actions</strong></p></td>
<td><p>Actions that are derived from requirements can be transferred to component items.</p></td>
</tr>
</tbody>
</table>


## See also

[Maintain planned orders](maintain-planned-orders.md)

  


