---
title: LoyaltySchemeLineRedeem.FromRewardPointAmountQuantity Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FromRewardPointAmountQuantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.FromRewardPointAmountQuantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineredeem.fromrewardpointamountquantity(v=AX.60)
ms:contentKeyID: 62213871
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.FromRewardPointAmountQuantity
dev_langs:
- CSharp
- C++
- VB
---

# FromRewardPointAmountQuantity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the amount or the quantity of the reward point.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("FROMREWARDPOINTAMOUNTQTY")> _
Public Property FromRewardPointAmountQuantity As Decimal
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineRedeem
Dim value As Decimal

value = instance.FromRewardPointAmountQuantity
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("FROMREWARDPOINTAMOUNTQTY")]
public decimal FromRewardPointAmountQuantity { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"FROMREWARDPOINTAMOUNTQTY")]
public:
property Decimal FromRewardPointAmountQuantity {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltySchemeLineRedeem Class](loyaltyschemelineredeem-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

