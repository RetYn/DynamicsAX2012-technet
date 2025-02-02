---
title: UpsService.HandlerName Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: HandlerName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.UpsService.HandlerName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.upsservice.handlername(v=AX.60)
ms:contentKeyID: 65318910
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.UpsService.HandlerName
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
Dim instance As UpsService
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

[UpsService Class](upsservice-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

