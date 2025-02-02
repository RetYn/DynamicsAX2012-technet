---
title: ICheckoutService.CreateOrder Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: CreateOrder Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICheckoutService.CreateOrder(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TenderDataLine},System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.icheckoutservice.createorder(v=AX.60)
ms:contentKeyID: 65315869
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICheckoutService.CreateOrder
dev_langs:
- CSharp
- C++
- VB
---

# CreateOrder Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function CreateOrder ( _
    tenderDataLine As IEnumerable(Of TenderDataLine), _
    emailAddress As String _
) As CreateSalesOrderResponse
'Usage
Dim instance As ICheckoutService
Dim tenderDataLine As IEnumerable(Of TenderDataLine)
Dim emailAddress As String
Dim returnValue As CreateSalesOrderResponse

returnValue = instance.CreateOrder(tenderDataLine, _
    emailAddress)
```

``` csharp
[OperationContractAttribute]
CreateSalesOrderResponse CreateOrder(
    IEnumerable<TenderDataLine> tenderDataLine,
    string emailAddress
)
```

``` c++
[OperationContractAttribute]
CreateSalesOrderResponse^ CreateOrder(
    IEnumerable<TenderDataLine^>^ tenderDataLine, 
    String^ emailAddress
)
```

#### Parameters

  - tenderDataLine  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[TenderDataLine](tenderdataline-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

<!-- end list -->

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CreateSalesOrderResponse](createsalesorderresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[ICheckoutService Interface](icheckoutservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

