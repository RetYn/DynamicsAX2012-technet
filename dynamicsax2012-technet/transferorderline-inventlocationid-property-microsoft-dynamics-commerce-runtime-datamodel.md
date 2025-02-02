---
title: TransferOrderLine.InventLocationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventLocationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.InventLocationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transferorderline.inventlocationid(v=AX.60)
ms:contentKeyID: 62204911
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.InventLocationId
dev_langs:
- CSharp
- C++
- VB
---

# InventLocationId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the inventory location identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVENTLOCATIONID")> _
<DataMemberAttribute> _
Public Property InventLocationId As String
    Get
    Set
'Usage
Dim instance As TransferOrderLine
Dim value As String

value = instance.InventLocationId

instance.InventLocationId = value
```

``` csharp
[ColumnAttribute("INVENTLOCATIONID")]
[DataMemberAttribute]
public string InventLocationId { get; set; }
```

``` c++
[ColumnAttribute(L"INVENTLOCATIONID")]
[DataMemberAttribute]
public:
property String^ InventLocationId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TransferOrderLine Class](transferorderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

