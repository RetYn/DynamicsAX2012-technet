---
title: ValidationPeriod.IsMondayTimeBounded Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsMondayTimeBounded Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsMondayTimeBounded
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.ismondaytimebounded(v=AX.60)
ms:contentKeyID: 49829187
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsMondayTimeBounded
dev_langs:
- CSharp
- C++
- VB
---

# IsMondayTimeBounded Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets whether valid time is inside or outside specified bounds for Mondays in this period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MONDAYTIMEWITHINBOUNDS")> _
<DataMemberAttribute> _
Public Property IsMondayTimeBounded As Integer
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As Integer

value = instance.IsMondayTimeBounded
```

``` csharp
[ColumnAttribute("MONDAYTIMEWITHINBOUNDS")]
[DataMemberAttribute]
public int IsMondayTimeBounded { get; internal set; }
```

``` c++
[ColumnAttribute(L"MONDAYTIMEWITHINBOUNDS")]
[DataMemberAttribute]
public:
property int IsMondayTimeBounded {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ValidationPeriod Class](validationperiod-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

