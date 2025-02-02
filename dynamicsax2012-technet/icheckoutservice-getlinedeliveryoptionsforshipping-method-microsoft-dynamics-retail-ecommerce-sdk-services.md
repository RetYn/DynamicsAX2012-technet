---
title: ICheckoutService.GetLineDeliveryOptionsForShipping Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetLineDeliveryOptionsForShipping Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICheckoutService.GetLineDeliveryOptionsForShipping(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SelectedLineShippingInfo})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.icheckoutservice.getlinedeliveryoptionsforshipping(v=AX.60)
ms:contentKeyID: 65318461
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICheckoutService.GetLineDeliveryOptionsForShipping
dev_langs:
- CSharp
- C++
- VB
---

# GetLineDeliveryOptionsForShipping Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetLineDeliveryOptionsForShipping ( _
    selectedLineShippingInfo As IEnumerable(Of SelectedLineShippingInfo) _
) As DeliveryOptionsResponse
'Usage
Dim instance As ICheckoutService
Dim selectedLineShippingInfo As IEnumerable(Of SelectedLineShippingInfo)
Dim returnValue As DeliveryOptionsResponse

returnValue = instance.GetLineDeliveryOptionsForShipping(selectedLineShippingInfo)
```

``` csharp
[OperationContractAttribute]
DeliveryOptionsResponse GetLineDeliveryOptionsForShipping(
    IEnumerable<SelectedLineShippingInfo> selectedLineShippingInfo
)
```

``` c++
[OperationContractAttribute]
DeliveryOptionsResponse^ GetLineDeliveryOptionsForShipping(
    IEnumerable<SelectedLineShippingInfo^>^ selectedLineShippingInfo
)
```

#### Parameters

  - selectedLineShippingInfo  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SelectedLineShippingInfo](selectedlineshippinginfo-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.DeliveryOptionsResponse](deliveryoptionsresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[ICheckoutService Interface](icheckoutservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

