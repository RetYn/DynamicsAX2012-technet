---
title: CustomerController.SearchCustomersAndReturnCustomerId Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: SearchCustomersAndReturnCustomerId Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.SearchCustomersAndReturnCustomerId(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.customercontroller.searchcustomersandreturncustomerid(v=AX.60)
ms:contentKeyID: 65318334
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.SearchCustomersAndReturnCustomerId
dev_langs:
- CSharp
- C++
- VB
---

# SearchCustomersAndReturnCustomerId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function SearchCustomersAndReturnCustomerId ( _
    emailAddress As String _
) As String
'Usage
Dim instance As CustomerController
Dim emailAddress As String
Dim returnValue As String

returnValue = instance.SearchCustomersAndReturnCustomerId(emailAddress)
```

``` csharp
public virtual string SearchCustomersAndReturnCustomerId(
    string emailAddress
)
```

``` c++
public:
virtual String^ SearchCustomersAndReturnCustomerId(
    String^ emailAddress
)
```

#### Parameters

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CustomerController Class](customercontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

