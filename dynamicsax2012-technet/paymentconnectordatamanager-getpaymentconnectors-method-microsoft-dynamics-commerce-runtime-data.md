---
title: PaymentConnectorDataManager.GetPaymentConnectors Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetPaymentConnectors Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.PaymentConnectorDataManager.GetPaymentConnectors(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.paymentconnectordatamanager.getpaymentconnectors(v=AX.60)
ms:contentKeyID: 65321252
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PaymentConnectorDataManager.GetPaymentConnectors
dev_langs:
- CSharp
- C++
- VB
---

# GetPaymentConnectors Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetPaymentConnectors ( _
    channelId As Long, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of PaymentConnectorConfiguration)
'Usage
Dim instance As PaymentConnectorDataManager
Dim channelId As Long
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of PaymentConnectorConfiguration)

returnValue = instance.GetPaymentConnectors(channelId, _
    settings)
```

``` csharp
public ReadOnlyCollection<PaymentConnectorConfiguration> GetPaymentConnectors(
    long channelId,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<PaymentConnectorConfiguration^>^ GetPaymentConnectors(
    long long channelId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[PaymentConnectorConfiguration](paymentconnectorconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[PaymentConnectorDataManager Class](paymentconnectordatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

