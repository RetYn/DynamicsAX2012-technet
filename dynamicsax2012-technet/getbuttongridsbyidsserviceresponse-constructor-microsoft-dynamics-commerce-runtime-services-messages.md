---
title: GetButtonGridsByIdsServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetButtonGridsByIdsServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetButtonGridsByIdsServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGrid})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getbuttongridsbyidsserviceresponse.getbuttongridsbyidsserviceresponse(v=AX.60)
ms:contentKeyID: 62207260
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetButtonGridsByIdsServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetButtonGridsByIdsServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetButtonGridsByIdsServiceResponse](getbuttongridsbyidsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    buttonGrids As IEnumerable(Of ButtonGrid) _
)
'Usage
Dim buttonGrids As IEnumerable(Of ButtonGrid)

Dim instance As New GetButtonGridsByIdsServiceResponse(buttonGrids)
```

``` csharp
public GetButtonGridsByIdsServiceResponse(
    IEnumerable<ButtonGrid> buttonGrids
)
```

``` c++
public:
GetButtonGridsByIdsServiceResponse(
    IEnumerable<ButtonGrid^>^ buttonGrids
)
```

#### Parameters

  - buttonGrids  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ButtonGrid](buttongrid-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetButtonGridsByIdsServiceResponse Class](getbuttongridsbyidsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

