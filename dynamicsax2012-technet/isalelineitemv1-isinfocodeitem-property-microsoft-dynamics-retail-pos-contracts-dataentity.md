---
title: ISaleLineItemV1.IsInfoCodeItem Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IsInfoCodeItem Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.IsInfoCodeItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.isinfocodeitem(v=AX.60)
ms:contentKeyID: 49830747
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.IsInfoCodeItem
dev_langs:
- CSharp
- C++
- VB
---

# IsInfoCodeItem Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Is set to true if item is a linked item

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property IsInfoCodeItem As Boolean
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As Boolean

value = instance.IsInfoCodeItem

instance.IsInfoCodeItem = value
```

``` csharp
bool IsInfoCodeItem { get; set; }
```

``` c++
property bool IsInfoCodeItem {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

