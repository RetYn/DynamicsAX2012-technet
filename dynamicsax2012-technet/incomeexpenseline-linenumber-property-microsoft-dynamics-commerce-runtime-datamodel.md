﻿---
title: IncomeExpenseLine.LineNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseLine.LineNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.incomeexpenseline.linenumber(v=AX.60)
ms:contentKeyID: 65320216
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseLine.LineNumber
dev_langs:
- CSharp
- C++
- VB
---

# LineNumber Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LINENUM")> _
<IgnoreDataMemberAttribute> _
Public Property LineNumber As Decimal
    Get
    Set
'Usage
Dim instance As IncomeExpenseLine
Dim value As Decimal

value = instance.LineNumber

instance.LineNumber = value
```

``` csharp
[ColumnAttribute("LINENUM")]
[IgnoreDataMemberAttribute]
public decimal LineNumber { get; set; }
```

``` c++
[ColumnAttribute(L"LINENUM")]
[IgnoreDataMemberAttribute]
public:
property Decimal LineNumber {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[IncomeExpenseLine Class](incomeexpenseline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
