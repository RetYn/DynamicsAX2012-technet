---
title: SalesLine.ReturnChannelId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReturnChannelId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ReturnChannelId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.returnchannelid(v=AX.60)
ms:contentKeyID: 62202835
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ReturnChannelId
dev_langs:
- CSharp
- C++
- VB
---

# ReturnChannelId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the return channel identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("RETURNCHANNELID")> _
<DataMemberAttribute> _
<ReadOnlyAttribute("RETURNCHANNELID")> _
Public Property ReturnChannelId As Long
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Long

value = instance.ReturnChannelId

instance.ReturnChannelId = value
```

``` csharp
[ColumnAttribute("RETURNCHANNELID")]
[DataMemberAttribute]
[ReadOnlyAttribute("RETURNCHANNELID")]
public long ReturnChannelId { get; set; }
```

``` c++
[ColumnAttribute(L"RETURNCHANNELID")]
[DataMemberAttribute]
[ReadOnlyAttribute(L"RETURNCHANNELID")]
public:
property long long ReturnChannelId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The channel identifier.  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

