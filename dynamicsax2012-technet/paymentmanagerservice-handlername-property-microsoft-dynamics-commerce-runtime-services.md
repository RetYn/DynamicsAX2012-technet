---
title: PaymentManagerService.HandlerName Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: HandlerName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PaymentManagerService.HandlerName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.paymentmanagerservice.handlername(v=AX.60)
ms:contentKeyID: 65319200
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PaymentManagerService.HandlerName
dev_langs:
- CSharp
- C++
- VB
---

# HandlerName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property HandlerName As String
    Get
'Usage
Dim instance As PaymentManagerService
Dim value As String

value = instance.HandlerName
```

``` csharp
public string HandlerName { get; }
```

``` c++
public:
virtual property String^ HandlerName {
    String^ get () sealed;
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Implements

[INamedRequestHandler.HandlerName](inamedrequesthandler-handlername-property-microsoft-dynamics-commerce-runtime-handlers.md)  

## See Also

#### Reference

[PaymentManagerService Class](paymentmanagerservice-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

