---
title: ProductAttributeSchemaEntry.KeyName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KeyName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAttributeSchemaEntry.KeyName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productattributeschemaentry.keyname(v=AX.60)
ms:contentKeyID: 65317095
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAttributeSchemaEntry.KeyName
dev_langs:
- CSharp
- C++
- VB
---

# KeyName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value representing the key name of the attribute.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("KEYNAME")> _
Public Property KeyName As String
    Get
    Set
'Usage
Dim instance As ProductAttributeSchemaEntry
Dim value As String

value = instance.KeyName

instance.KeyName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("KEYNAME")]
public string KeyName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"KEYNAME")]
public:
property String^ KeyName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductAttributeSchemaEntry Class](productattributeschemaentry-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

