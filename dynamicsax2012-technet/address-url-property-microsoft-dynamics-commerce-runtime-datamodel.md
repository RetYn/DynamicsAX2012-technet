---
title: Address.Url Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Url Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.Url
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.url(v=AX.60)
ms:contentKeyID: 49836431
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.Url
dev_langs:
- CSharp
- C++
- VB
---

# Url Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the Url.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("URL")> _
Public Property Url As String
    Get
    Set
'Usage
Dim instance As Address
Dim value As String

value = instance.Url

instance.Url = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("URL")]
public string Url { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"URL")]
public:
property String^ Url {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

