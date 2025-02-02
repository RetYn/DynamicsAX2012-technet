---
title: ValidateShippingAddressServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ValidateShippingAddressServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressServiceResponse.#ctor(System.Boolean,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.Address})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.validateshippingaddressserviceresponse.validateshippingaddressserviceresponse(v=AX.60)
ms:contentKeyID: 49849796
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ValidateShippingAddressServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ValidateShippingAddressServiceResponse](validateshippingaddressserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    isAddressValid As Boolean, _
    recommendedAddresses As IEnumerable(Of Address) _
)
'Usage
Dim isAddressValid As Boolean
Dim recommendedAddresses As IEnumerable(Of Address)

Dim instance As New ValidateShippingAddressServiceResponse(isAddressValid, _
    recommendedAddresses)
```

``` csharp
public ValidateShippingAddressServiceResponse(
    bool isAddressValid,
    IEnumerable<Address> recommendedAddresses
)
```

``` c++
public:
ValidateShippingAddressServiceResponse(
    bool isAddressValid, 
    IEnumerable<Address^>^ recommendedAddresses
)
```

#### Parameters

  - isAddressValid  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - recommendedAddresses  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ValidateShippingAddressServiceResponse Class](validateshippingaddressserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

