---
title: ItemAvailability.InventorySiteId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventorySiteId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability.InventorySiteId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemavailability.inventorysiteid(v=AX.60)
ms:contentKeyID: 49820187
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability.InventorySiteId
dev_langs:
- CSharp
- C++
- VB
---

# InventorySiteId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the inventory site identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVENTSITEID")> _
Public Property InventorySiteId As String
    Get
    Friend Set
'Usage
Dim instance As ItemAvailability
Dim value As String

value = instance.InventorySiteId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVENTSITEID")]
public string InventorySiteId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVENTSITEID")]
public:
property String^ InventorySiteId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ItemAvailability Class](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

