---
title: IItemDataManager.GetItems Method (IEnumerable(String), ColumnSet) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetItems Method (IEnumerable(String), ColumnSet)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IItemDataManager.GetItems(System.Collections.Generic.IEnumerable{System.String},Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.iitemdatamanager.getitems(v=AX.60)
ms:contentKeyID: 62206479
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetItems Method (IEnumerable(String), ColumnSet)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the items using the specified item identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetItems ( _
    itemIds As IEnumerable(Of String), _
    columnSet As ColumnSet _
) As ReadOnlyCollection(Of Item)
'Usage
Dim instance As IItemDataManager
Dim itemIds As IEnumerable(Of String)
Dim columnSet As ColumnSet
Dim returnValue As ReadOnlyCollection(Of Item)

returnValue = instance.GetItems(itemIds, _
    columnSet)
```

``` csharp
ReadOnlyCollection<Item> GetItems(
    IEnumerable<string> itemIds,
    ColumnSet columnSet
)
```

``` c++
ReadOnlyCollection<Item^>^ GetItems(
    IEnumerable<String^>^ itemIds, 
    ColumnSet^ columnSet
)
```

#### Parameters

  - itemIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Item](item-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of items.  

## See Also

#### Reference

[IItemDataManager Interface](iitemdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[GetItems Overload](iitemdatamanager-getitems-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

