---
title: ItemDatabaseAccessor.GetVariantByVariantId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetVariantByVariantId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ItemDatabaseAccessor.GetVariantByVariantId(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.itemdatabaseaccessor.getvariantbyvariantid(v=AX.60)
ms:contentKeyID: 62214029
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ItemDatabaseAccessor.GetVariantByVariantId
dev_langs:
- CSharp
- C++
- VB
---

# GetVariantByVariantId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the variant using the specified variant identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetVariantByVariantId ( _
    variantId As String, _
    columnSet As ColumnSet _
) As ProductVariant
'Usage
Dim instance As ItemDatabaseAccessor
Dim variantId As String
Dim columnSet As ColumnSet
Dim returnValue As ProductVariant

returnValue = instance.GetVariantByVariantId(variantId, _
    columnSet)
```

``` csharp
public ProductVariant GetVariantByVariantId(
    string variantId,
    ColumnSet columnSet
)
```

``` c++
public:
virtual ProductVariant^ GetVariantByVariantId(
    String^ variantId, 
    ColumnSet^ columnSet
) sealed
```

#### Parameters

  - variantId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The variant if it exists; otherwise, NULL.  

#### Implements

[IItemDataManager.GetVariantByVariantId(String, ColumnSet)](iitemdatamanager-getvariantbyvariantid-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ItemDatabaseAccessor Class](itemdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

