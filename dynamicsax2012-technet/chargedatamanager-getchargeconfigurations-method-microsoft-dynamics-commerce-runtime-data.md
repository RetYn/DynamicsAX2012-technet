---
title: ChargeDataManager.GetChargeConfigurations Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChargeConfigurations Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChargeDataManager.GetChargeConfigurations(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.chargedatamanager.getchargeconfigurations(v=AX.60)
ms:contentKeyID: 65319823
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChargeDataManager.GetChargeConfigurations
dev_langs:
- CSharp
- C++
- VB
---

# GetChargeConfigurations Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetChargeConfigurations ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of ChargeConfiguration)
'Usage
Dim instance As ChargeDataManager
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of ChargeConfiguration)

returnValue = instance.GetChargeConfigurations(settings)
```

``` csharp
public ReadOnlyCollection<ChargeConfiguration> GetChargeConfigurations(
    QueryResultSettings settings
)
```

``` c++
public:
virtual ReadOnlyCollection<ChargeConfiguration^>^ GetChargeConfigurations(
    QueryResultSettings^ settings
) sealed
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ChargeConfiguration](chargeconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[IChargeDataManager.GetChargeConfigurations(QueryResultSettings)](ichargedatamanager-getchargeconfigurations-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ChargeDataManager Class](chargedatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

