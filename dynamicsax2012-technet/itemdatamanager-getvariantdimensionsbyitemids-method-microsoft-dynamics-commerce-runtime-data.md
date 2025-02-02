---
title: ItemDataManager.GetVariantDimensionsByItemIds Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetVariantDimensionsByItemIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ItemDataManager.GetVariantDimensionsByItemIds(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.itemdatamanager.getvariantdimensionsbyitemids(v=AX.60)
ms:contentKeyID: 62209115
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ItemDataManager.GetVariantDimensionsByItemIds
dev_langs:
- CSharp
- C++
- VB
---

# GetVariantDimensionsByItemIds Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get the variant dimensions populated for the given dimension Ids. This is lightweight and only returns the dimension Ids, not translations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetVariantDimensionsByItemIds ( _
    inventoryDimensionIds As IEnumerable(Of String) _
) As ReadOnlyCollection(Of ProductVariant)
'Usage
Dim instance As ItemDataManager
Dim inventoryDimensionIds As IEnumerable(Of String)
Dim returnValue As ReadOnlyCollection(Of ProductVariant)

returnValue = instance.GetVariantDimensionsByItemIds(inventoryDimensionIds)
```

``` csharp
public ReadOnlyCollection<ProductVariant> GetVariantDimensionsByItemIds(
    IEnumerable<string> inventoryDimensionIds
)
```

``` c++
public:
virtual ReadOnlyCollection<ProductVariant^>^ GetVariantDimensionsByItemIds(
    IEnumerable<String^>^ inventoryDimensionIds
) sealed
```

#### Parameters

  - inventoryDimensionIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Collection of dimension values.  

#### Implements

[IItemDataManager.GetVariantDimensionsByItemIds(IEnumerable\<String\>)](iitemdatamanager-getvariantdimensionsbyitemids-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ItemDataManager Class](itemdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

