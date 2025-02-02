---
title: CalculatePaymentAmountServiceRequest Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CalculatePaymentAmountServiceRequest Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculatePaymentAmountServiceRequest
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.calculatepaymentamountservicerequest(v=AX.60)
ms:contentKeyID: 62204168
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculatePaymentAmountServiceRequest
dev_langs:
- CSharp
- C++
- VB
---

# CalculatePaymentAmountServiceRequest Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Request object to calculate amount to be authorized.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public NotInheritable Class CalculatePaymentAmountServiceRequest _
    Inherits PaymentServiceRequestBase
'Usage
Dim instance As CalculatePaymentAmountServiceRequest
```

``` csharp
[DataContractAttribute]
public sealed class CalculatePaymentAmountServiceRequest : PaymentServiceRequestBase
```

``` c++
[DataContractAttribute]
public ref class CalculatePaymentAmountServiceRequest sealed : public PaymentServiceRequestBase
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ServiceRequest](servicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PaymentServiceRequestBase](paymentservicerequestbase-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
        Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculatePaymentAmountServiceRequest  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

