---
title: IItemV1.ItemBuyerGroupId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ItemBuyerGroupId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.ItemBuyerGroupId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iitemv1.itembuyergroupid(v=AX.60)
ms:contentKeyID: 49824317
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.ItemBuyerGroupId
dev_langs:
- CSharp
- C++
- VB
---

# ItemBuyerGroupId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the item buyer group id.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ItemBuyerGroupId As String
    Get
    Set
'Usage
Dim instance As IItemV1
Dim value As String

value = instance.ItemBuyerGroupId

instance.ItemBuyerGroupId = value
```

``` csharp
string ItemBuyerGroupId { get; set; }
```

``` c++
property String^ ItemBuyerGroupId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The item buyer group id.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

