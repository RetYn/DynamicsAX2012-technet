---
title: GetPriceServiceResponse.Transaction Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Transaction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPriceServiceResponse.Transaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getpriceserviceresponse.transaction(v=AX.60)
ms:contentKeyID: 62214743
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPriceServiceResponse.Transaction
dev_langs:
- CSharp
- C++
- VB
---

# Transaction Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the transaction which has been updated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Transaction As SalesTransaction
    Get
    Private Set
'Usage
Dim instance As GetPriceServiceResponse
Dim value As SalesTransaction

value = instance.Transaction
```

``` csharp
[DataMemberAttribute]
public SalesTransaction Transaction { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property SalesTransaction^ Transaction {
    SalesTransaction^ get ();
    private: void set (SalesTransaction^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetPriceServiceResponse Class](getpriceserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

