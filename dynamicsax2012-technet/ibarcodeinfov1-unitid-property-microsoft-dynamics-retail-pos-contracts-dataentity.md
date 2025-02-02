---
title: IBarcodeInfoV1.UnitId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: UnitId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.UnitId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibarcodeinfov1.unitid(v=AX.60)
ms:contentKeyID: 47129005
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.UnitId
dev_langs:
- CSharp
- C++
- VB
---

# UnitId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the unit ID for the barcode.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property UnitId As String
    Get
    Set
'Usage
Dim instance As IBarcodeInfoV1
Dim value As String

value = instance.UnitId

instance.UnitId = value
```

``` csharp
string UnitId { get; set; }
```

``` c++
property String^ UnitId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[IBarcodeInfoV1 Interface](ibarcodeinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

