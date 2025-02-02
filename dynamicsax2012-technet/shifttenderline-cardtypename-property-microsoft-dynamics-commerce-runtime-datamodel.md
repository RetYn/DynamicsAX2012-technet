---
title: ShiftTenderLine.CardTypeName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CardTypeName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.CardTypeName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.cardtypename(v=AX.60)
ms:contentKeyID: 62202429
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.CardTypeName
dev_langs:
- CSharp
- C++
- VB
---

# CardTypeName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets card name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CARDTYPENAME")> _
<DataMemberAttribute> _
Public Property CardTypeName As String
    Get
    Friend Set
'Usage
Dim instance As ShiftTenderLine
Dim value As String

value = instance.CardTypeName
```

``` csharp
[ColumnAttribute("CARDTYPENAME")]
[DataMemberAttribute]
public string CardTypeName { get; internal set; }
```

``` c++
[ColumnAttribute(L"CARDTYPENAME")]
[DataMemberAttribute]
public:
property String^ CardTypeName {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ShiftTenderLine Class](shifttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

