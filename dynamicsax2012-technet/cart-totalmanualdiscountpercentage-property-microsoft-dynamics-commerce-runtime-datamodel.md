---
title: Cart.TotalManualDiscountPercentage Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TotalManualDiscountPercentage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.TotalManualDiscountPercentage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.totalmanualdiscountpercentage(v=AX.60)
ms:contentKeyID: 62213121
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.TotalManualDiscountPercentage
dev_langs:
- CSharp
- C++
- VB
---

# TotalManualDiscountPercentage Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the manual total percent off value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TOTALMANUALDISCOUNTPERCENTAGE")> _
<DataMemberAttribute> _
Public Property TotalManualDiscountPercentage As Decimal
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Decimal

value = instance.TotalManualDiscountPercentage

instance.TotalManualDiscountPercentage = value
```

``` csharp
[ColumnAttribute("TOTALMANUALDISCOUNTPERCENTAGE")]
[DataMemberAttribute]
public decimal TotalManualDiscountPercentage { get; set; }
```

``` c++
[ColumnAttribute(L"TOTALMANUALDISCOUNTPERCENTAGE")]
[DataMemberAttribute]
public:
property Decimal TotalManualDiscountPercentage {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

