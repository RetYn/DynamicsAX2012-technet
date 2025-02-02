---
title: TaxLineIndia.TerminalId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TerminalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.TerminalId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxlineindia.terminalid(v=AX.60)
ms:contentKeyID: 62215134
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.TerminalId
dev_langs:
- CSharp
- C++
- VB
---

# TerminalId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets terminal ID.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TERMINALID")> _
<DataMemberAttribute> _
Public Property TerminalId As String
    Get
    Set
'Usage
Dim instance As TaxLineIndia
Dim value As String

value = instance.TerminalId

instance.TerminalId = value
```

``` csharp
[ColumnAttribute("TERMINALID")]
[DataMemberAttribute]
public string TerminalId { get; set; }
```

``` c++
[ColumnAttribute(L"TERMINALID")]
[DataMemberAttribute]
public:
property String^ TerminalId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TaxLineIndia Class](taxlineindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

