---
title: DiscountInvalidatedNotification.InventDimId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventDimId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountInvalidatedNotification.InventDimId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountinvalidatednotification.inventdimid(v=AX.60)
ms:contentKeyID: 65322237
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountInvalidatedNotification.InventDimId
dev_langs:
- CSharp
- C++
- VB
---

# InventDimId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the inventory dimension identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InventDimId As String
    Get
    Private Set
'Usage
Dim instance As DiscountInvalidatedNotification
Dim value As String

value = instance.InventDimId
```

``` csharp
[DataMemberAttribute]
public string InventDimId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ InventDimId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DiscountInvalidatedNotification Class](discountinvalidatednotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

