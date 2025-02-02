---
title: ITransactionTriggerV1 Methods (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: ITransactionTriggerV1 Methods
ms:assetid: Methods.T:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITransactionTriggerV1
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.itransactiontriggerv1_methods(v=AX.60)
ms:contentKeyID: 47129054
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ITransactionTriggerV1 Methods


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The [ITransactionTriggerV1](itransactiontriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md) type exposes the following members.

## Methods

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="itransactiontriggerv1-begintransaction-method-microsoft-dynamics-retail-pos-contracts-triggers.md">BeginTransaction</a></td>
<td>Called at the start of a new transaction, but after loading the transaction with initialization data, such as the store ID, the terminal number, and the date.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="itransactiontriggerv1-postendtransaction-method-microsoft-dynamics-retail-pos-contracts-triggers.md">PostEndTransaction</a></td>
<td>Called at the end of a transaction, after the transaction is saved and the receipts are printed.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="itransactiontriggerv1-postreturntransaction-method-microsoft-dynamics-retail-pos-contracts-triggers.md">PostReturnTransaction</a></td>
<td>Called after a return transaction is completed.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="itransactiontriggerv1-postvoidtransaction-method-microsoft-dynamics-retail-pos-contracts-triggers.md">PostVoidTransaction</a></td>
<td>Called after a transaction is voided.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="itransactiontriggerv1-preendtransaction-method-microsoft-dynamics-retail-pos-contracts-triggers.md">PreEndTransaction</a></td>
<td>Called at the end of a transaction, before the transaction is saved and the receipts are printed.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="itransactiontriggerv1-prereturntransaction-method-microsoft-dynamics-retail-pos-contracts-triggers.md">PreReturnTransaction</a></td>
<td>Called before a return transaction is completed.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="itransactiontriggerv1-prevoidtransaction-method-microsoft-dynamics-retail-pos-contracts-triggers.md">PreVoidTransaction</a></td>
<td>Called before a transaction is voided.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="itransactiontriggerv1-savetransaction-method-microsoft-dynamics-retail-pos-contracts-triggers.md">SaveTransaction</a></td>
<td>Called when a transaction is saved to the database.</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[ITransactionTriggerV1 Interface](itransactiontriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

