---
title: ITaxableItem.ItemGroupId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ItemGroupId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.ItemGroupId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxableitem.itemgroupid(v=AX.60)
ms:contentKeyID: 47129168
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.ItemGroupId
dev_langs:
- CSharp
- C++
- VB
---

# ItemGroupId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Note: This API is now obsolete.**

The retail group of the item.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<ObsoleteAttribute("Value is no longer used")> _
Property ItemGroupId As String
    Get
    Set
'Usage
Dim instance As ITaxableItem
Dim value As String

value = instance.ItemGroupId

instance.ItemGroupId = value
```

``` csharp
[ObsoleteAttribute("Value is no longer used")]
string ItemGroupId { get; set; }
```

``` c++
[ObsoleteAttribute(L"Value is no longer used")]
property String^ ItemGroupId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[ITaxableItem Interface](itaxableitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

