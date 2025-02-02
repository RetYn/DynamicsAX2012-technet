---
title: IDiscountV1.AddLineDiscountAmount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AddLineDiscountAmount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.AddLineDiscountAmount(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILineDiscountItem)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idiscountv1.addlinediscountamount(v=AX.60)
ms:contentKeyID: 47344064
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.AddLineDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# AddLineDiscountAmount Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Applies a discount amount to a specific line item in a transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub AddLineDiscountAmount ( _
    lineItem As ISaleLineItem, _
    discountItem As ILineDiscountItem _
)
'Usage
Dim instance As IDiscountV1
Dim lineItem As ISaleLineItem
Dim discountItem As ILineDiscountItem

instance.AddLineDiscountAmount(lineItem, _
    discountItem)
```

``` csharp
void AddLineDiscountAmount(
    ISaleLineItem lineItem,
    ILineDiscountItem discountItem
)
```

``` c++
void AddLineDiscountAmount(
    ISaleLineItem^ lineItem, 
    ILineDiscountItem^ discountItem
)
```

#### Parameters

  - lineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - discountItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILineDiscountItem](ilinediscountitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## Remarks

This method is invoked by the line discount amount operation.

## See Also

#### Reference

[IDiscountV1 Interface](idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

