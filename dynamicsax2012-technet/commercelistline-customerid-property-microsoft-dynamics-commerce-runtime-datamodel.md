---
title: CommerceListLine.CustomerId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListLine.CustomerId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commercelistline.customerid(v=AX.60)
ms:contentKeyID: 62214284
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListLine.CustomerId
dev_langs:
- CSharp
- C++
- VB
---

# CustomerId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the commerce list line customer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomerId As String
    Get
    Set
'Usage
Dim instance As CommerceListLine
Dim value As String

value = instance.CustomerId

instance.CustomerId = value
```

``` csharp
[DataMemberAttribute]
public string CustomerId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CustomerId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CommerceListLine Class](commercelistline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

