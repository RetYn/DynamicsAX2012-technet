---
title: SalesLine.IsLoyaltyDiscountApplied Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsLoyaltyDiscountApplied Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.IsLoyaltyDiscountApplied
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.isloyaltydiscountapplied(v=AX.60)
ms:contentKeyID: 62205368
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.IsLoyaltyDiscountApplied
dev_langs:
- CSharp
- C++
- VB
---

# IsLoyaltyDiscountApplied Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the loyalty discount was applied to this line or not.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsLoyaltyDiscountApplied As Boolean
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Boolean

value = instance.IsLoyaltyDiscountApplied

instance.IsLoyaltyDiscountApplied = value
```

``` csharp
[DataMemberAttribute]
public bool IsLoyaltyDiscountApplied { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsLoyaltyDiscountApplied {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

