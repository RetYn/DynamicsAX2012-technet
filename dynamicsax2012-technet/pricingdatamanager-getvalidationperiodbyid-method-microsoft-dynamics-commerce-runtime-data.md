---
title: PricingDataManager.GetValidationPeriodById Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetValidationPeriodById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.GetValidationPeriodById(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.pricingdatamanager.getvalidationperiodbyid(v=AX.60)
ms:contentKeyID: 49850748
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.GetValidationPeriodById
dev_langs:
- CSharp
- C++
- VB
---

# GetValidationPeriodById Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get the periodic discount validation period with specified identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetValidationPeriodById ( _
    periodId As String, _
    columns As ColumnSet _
) As ValidationPeriod
'Usage
Dim instance As PricingDataManager
Dim periodId As String
Dim columns As ColumnSet
Dim returnValue As ValidationPeriod

returnValue = instance.GetValidationPeriodById(periodId, _
    columns)
```

``` csharp
public ValidationPeriod GetValidationPeriodById(
    string periodId,
    ColumnSet columns
)
```

``` c++
public:
virtual ValidationPeriod^ GetValidationPeriodById(
    String^ periodId, 
    ColumnSet^ columns
) sealed
```

#### Parameters

  - periodId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod](validationperiod-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Periodic discount validation period matching given identifier. Null if none found.  

#### Implements

[IPricingDataManager.GetValidationPeriodById(String, ColumnSet)](ipricingdatamanager-getvalidationperiodbyid-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataManager Class](pricingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

