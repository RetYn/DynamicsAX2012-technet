---
title: PeriodicDiscount.ConcurrencyMode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ConcurrencyMode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.ConcurrencyMode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.concurrencymode(v=AX.60)
ms:contentKeyID: 49825766
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.ConcurrencyMode
dev_langs:
- CSharp
- C++
- VB
---

# ConcurrencyMode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the concurrency mode for this discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CONCURRENCYMODE")> _
Public Property ConcurrencyMode As ConcurrencyMode
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As ConcurrencyMode

value = instance.ConcurrencyMode
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CONCURRENCYMODE")]
public ConcurrencyMode ConcurrencyMode { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CONCURRENCYMODE")]
public:
property ConcurrencyMode ConcurrencyMode {
    ConcurrencyMode get ();
    internal: void set (ConcurrencyMode value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ConcurrencyMode](concurrencymode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ConcurrencyMode](concurrencymode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[PeriodicDiscount Class](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

