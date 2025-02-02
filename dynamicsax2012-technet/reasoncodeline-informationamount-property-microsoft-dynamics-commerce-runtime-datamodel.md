---
title: ReasonCodeLine.InformationAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InformationAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.InformationAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodeline.informationamount(v=AX.60)
ms:contentKeyID: 62203428
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.InformationAmount
dev_langs:
- CSharp
- C++
- VB
---

# InformationAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the information amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INFOAMOUNT")> _
Public Property InformationAmount As Decimal
    Get
    Set
'Usage
Dim instance As ReasonCodeLine
Dim value As Decimal

value = instance.InformationAmount

instance.InformationAmount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INFOAMOUNT")]
public decimal InformationAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INFOAMOUNT")]
public:
property Decimal InformationAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The information amount.  

## See Also

#### Reference

[ReasonCodeLine Class](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

