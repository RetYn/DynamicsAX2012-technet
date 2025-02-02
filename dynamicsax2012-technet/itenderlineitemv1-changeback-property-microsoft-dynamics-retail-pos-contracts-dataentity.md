---
title: ITenderLineItemV1.ChangeBack Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ChangeBack Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderLineItemV1.ChangeBack
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itenderlineitemv1.changeback(v=AX.60)
ms:contentKeyID: 49835343
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderLineItemV1.ChangeBack
dev_langs:
- CSharp
- C++
- VB
---

# ChangeBack Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

If true then the tender item was created as a Change back tender item

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ChangeBack As Boolean
    Get
    Set
'Usage
Dim instance As ITenderLineItemV1
Dim value As Boolean

value = instance.ChangeBack

instance.ChangeBack = value
```

``` csharp
bool ChangeBack { get; set; }
```

``` c++
property bool ChangeBack {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ITenderLineItemV1 Interface](itenderlineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

