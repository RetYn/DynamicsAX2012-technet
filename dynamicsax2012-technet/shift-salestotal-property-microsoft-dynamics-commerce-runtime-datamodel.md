---
title: Shift.SalesTotal Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesTotal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.SalesTotal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shift.salestotal(v=AX.60)
ms:contentKeyID: 62206873
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.SalesTotal
dev_langs:
- CSharp
- C++
- VB
---

# SalesTotal Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets total of sales.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SALESTOTAL")> _
Public Property SalesTotal As Decimal
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Decimal

value = instance.SalesTotal

instance.SalesTotal = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SALESTOTAL")]
public decimal SalesTotal { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SALESTOTAL")]
public:
property Decimal SalesTotal {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

