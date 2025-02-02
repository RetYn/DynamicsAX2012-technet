---
title: Shift.ClosedAtTerminalId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ClosedAtTerminalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.ClosedAtTerminalId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shift.closedatterminalid(v=AX.60)
ms:contentKeyID: 62212392
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.ClosedAtTerminalId
dev_langs:
- CSharp
- C++
- VB
---

# ClosedAtTerminalId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets Closed at terminal identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CLOSEDATTERMINAL")> _
Public Property ClosedAtTerminalId As String
    Get
    Set
'Usage
Dim instance As Shift
Dim value As String

value = instance.ClosedAtTerminalId

instance.ClosedAtTerminalId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CLOSEDATTERMINAL")]
public string ClosedAtTerminalId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CLOSEDATTERMINAL")]
public:
property String^ ClosedAtTerminalId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

