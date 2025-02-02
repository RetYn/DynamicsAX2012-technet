---
title: IItemTriggerV1.PostVoidItem Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PostVoidItem Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IItemTriggerV1.PostVoidItem(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.iitemtriggerv1.postvoiditem(v=AX.60)
ms:contentKeyID: 47128435
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IItemTriggerV1.PostVoidItem
dev_langs:
- CSharp
- C++
- VB
---

# PostVoidItem Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered after an item is voided.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostVoidItem ( _
    posTransaction As IPosTransaction, _
    lineId As Integer _
)
'Usage
Dim instance As IItemTriggerV1
Dim posTransaction As IPosTransaction
Dim lineId As Integer

instance.PostVoidItem(posTransaction, _
    lineId)
```

``` csharp
void PostVoidItem(
    IPosTransaction posTransaction,
    int lineId
)
```

``` c++
void PostVoidItem(
    IPosTransaction^ posTransaction, 
    int lineId
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - lineId  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[IItemTriggerV1 Interface](iitemtriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

