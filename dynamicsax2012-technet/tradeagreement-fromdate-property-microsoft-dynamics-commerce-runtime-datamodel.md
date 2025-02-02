---
title: TradeAgreement.FromDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FromDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.FromDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.fromdate(v=AX.60)
ms:contentKeyID: 49835993
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.FromDate
dev_langs:
- CSharp
- C++
- VB
---

# FromDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the starting date when this rule becomes active.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("FROMDATE")> _
<DataMemberAttribute> _
Public Property FromDate As DateTimeOffset
    Get
    Friend Set
'Usage
Dim instance As TradeAgreement
Dim value As DateTimeOffset

value = instance.FromDate
```

``` csharp
[ColumnAttribute("FROMDATE")]
[DataMemberAttribute]
public DateTimeOffset FromDate { get; internal set; }
```

``` c++
[ColumnAttribute(L"FROMDATE")]
[DataMemberAttribute]
public:
property DateTimeOffset FromDate {
    DateTimeOffset get ();
    internal: void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[TradeAgreement Class](tradeagreement-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

