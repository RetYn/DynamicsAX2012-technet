---
title: IItemV1.PropertyId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PropertyId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.PropertyId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iitemv1.propertyid(v=AX.60)
ms:contentKeyID: 49847825
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.PropertyId
dev_langs:
- CSharp
- C++
- VB
---

# PropertyId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the property id.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PropertyId As String
    Get
    Set
'Usage
Dim instance As IItemV1
Dim value As String

value = instance.PropertyId

instance.PropertyId = value
```

``` csharp
string PropertyId { get; set; }
```

``` c++
property String^ PropertyId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The property id.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

