---
title: CalculateRequiredReasonCodesServiceRequest Constructor (SalesTransaction, ReasonCodeSourceType) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CalculateRequiredReasonCodesServiceRequest Constructor (SalesTransaction, ReasonCodeSourceType)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateRequiredReasonCodesServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.calculaterequiredreasoncodesservicerequest.calculaterequiredreasoncodesservicerequest(v=AX.60)
ms:contentKeyID: 65323144
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CalculateRequiredReasonCodesServiceRequest Constructor (SalesTransaction, ReasonCodeSourceType)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesTransaction As SalesTransaction, _
    sourceType As ReasonCodeSourceType _
)
'Usage
Dim salesTransaction As SalesTransaction
Dim sourceType As ReasonCodeSourceType

Dim instance As New CalculateRequiredReasonCodesServiceRequest(salesTransaction, _
    sourceType)
```

``` csharp
public CalculateRequiredReasonCodesServiceRequest(
    SalesTransaction salesTransaction,
    ReasonCodeSourceType sourceType
)
```

``` c++
public:
CalculateRequiredReasonCodesServiceRequest(
    SalesTransaction^ salesTransaction, 
    ReasonCodeSourceType sourceType
)
```

#### Parameters

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - sourceType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType](reasoncodesourcetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CalculateRequiredReasonCodesServiceRequest Class](calculaterequiredreasoncodesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[CalculateRequiredReasonCodesServiceRequest Overload](calculaterequiredreasoncodesservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

