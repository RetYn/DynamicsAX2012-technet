---
title: ProductVariant.PropertiesAsList Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PropertiesAsList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.PropertiesAsList
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariant.propertiesaslist(v=AX.60)
ms:contentKeyID: 62211873
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.PropertiesAsList
dev_langs:
- CSharp
- C++
- VB
---

# PropertiesAsList Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the properties of a variant as a flat list.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PropertiesAsList As ICollection(Of ProductPropertyTranslation)
    Get
    Set
'Usage
Dim instance As ProductVariant
Dim value As ICollection(Of ProductPropertyTranslation)

value = instance.PropertiesAsList

instance.PropertiesAsList = value
```

``` csharp
[DataMemberAttribute]
public ICollection<ProductPropertyTranslation> PropertiesAsList { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<ProductPropertyTranslation^>^ PropertiesAsList {
    ICollection<ProductPropertyTranslation^>^ get ();
    void set (ICollection<ProductPropertyTranslation^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ProductPropertyTranslation](productpropertytranslation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[ProductVariant Class](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

