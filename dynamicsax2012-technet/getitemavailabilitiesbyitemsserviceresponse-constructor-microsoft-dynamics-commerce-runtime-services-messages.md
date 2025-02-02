---
title: GetItemAvailabilitiesByItemsServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetItemAvailabilitiesByItemsServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemsServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability},System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getitemavailabilitiesbyitemsserviceresponse.getitemavailabilitiesbyitemsserviceresponse(v=AX.60)
ms:contentKeyID: 62212296
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemsServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetItemAvailabilitiesByItemsServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetItemAvailabilitiesByItemsServiceResponse](getitemavailabilitiesbyitemsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemAvailabilities As IEnumerable(Of ItemAvailability), _
    totalNumberOfRecords As Integer _
)
'Usage
Dim itemAvailabilities As IEnumerable(Of ItemAvailability)
Dim totalNumberOfRecords As Integer

Dim instance As New GetItemAvailabilitiesByItemsServiceResponse(itemAvailabilities, _
    totalNumberOfRecords)
```

``` csharp
public GetItemAvailabilitiesByItemsServiceResponse(
    IEnumerable<ItemAvailability> itemAvailabilities,
    int totalNumberOfRecords
)
```

``` c++
public:
GetItemAvailabilitiesByItemsServiceResponse(
    IEnumerable<ItemAvailability^>^ itemAvailabilities, 
    int totalNumberOfRecords
)
```

#### Parameters

  - itemAvailabilities  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemAvailability](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - totalNumberOfRecords  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[GetItemAvailabilitiesByItemsServiceResponse Class](getitemavailabilitiesbyitemsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

