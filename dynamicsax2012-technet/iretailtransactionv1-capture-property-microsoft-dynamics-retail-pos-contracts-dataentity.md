---
title: IRetailTransactionV1.Capture Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Capture Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.Capture
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.capture(v=AX.60)
ms:contentKeyID: 49820784
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.Capture
dev_langs:
- CSharp
- C++
- VB
---

# Capture Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Conclude transaction capture state.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Capture As Boolean
    Get
    Set
'Usage
Dim instance As IRetailTransactionV1
Dim value As Boolean

value = instance.Capture

instance.Capture = value
```

``` csharp
bool Capture { get; set; }
```

``` c++
property bool Capture {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

