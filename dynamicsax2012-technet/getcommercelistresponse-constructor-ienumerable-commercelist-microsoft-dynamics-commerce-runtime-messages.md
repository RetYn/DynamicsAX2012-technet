---
title: GetCommerceListResponse Constructor (IEnumerable(CommerceList)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetCommerceListResponse Constructor (IEnumerable(CommerceList))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCommerceListResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getcommercelistresponse.getcommercelistresponse(v=AX.60)
ms:contentKeyID: 62208482
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCommerceListResponse Constructor (IEnumerable(CommerceList))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetCommerceListResponse](getcommercelistresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    clists As IEnumerable(Of CommerceList) _
)
'Usage
Dim clists As IEnumerable(Of CommerceList)

Dim instance As New GetCommerceListResponse(clists)
```

``` csharp
public GetCommerceListResponse(
    IEnumerable<CommerceList> clists
)
```

``` c++
public:
GetCommerceListResponse(
    IEnumerable<CommerceList^>^ clists
)
```

#### Parameters

  - clists  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetCommerceListResponse Class](getcommercelistresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetCommerceListResponse Overload](getcommercelistresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

