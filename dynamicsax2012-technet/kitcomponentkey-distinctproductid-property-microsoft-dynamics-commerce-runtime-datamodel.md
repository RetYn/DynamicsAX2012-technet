---
title: KitComponentKey.DistinctProductId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DistinctProductId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponentKey.DistinctProductId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitcomponentkey.distinctproductid(v=AX.60)
ms:contentKeyID: 62214987
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponentKey.DistinctProductId
dev_langs:
- CSharp
- C++
- VB
---

# DistinctProductId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the distinct product id of the kit component.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DistinctProductId As Long
    Get
    Friend Set
'Usage
Dim instance As KitComponentKey
Dim value As Long

value = instance.DistinctProductId
```

``` csharp
[DataMemberAttribute]
public long DistinctProductId { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property long long DistinctProductId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[KitComponentKey Class](kitcomponentkey-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

