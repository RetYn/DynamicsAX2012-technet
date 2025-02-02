---
title: IPricingDataManagerV2.GetMultipleBuyDiscountLinesByOfferIds Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetMultipleBuyDiscountLinesByOfferIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2.GetMultipleBuyDiscountLinesByOfferIds(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ipricingdatamanagerv2.getmultiplebuydiscountlinesbyofferids(v=AX.60)
ms:contentKeyID: 62212882
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2.GetMultipleBuyDiscountLinesByOfferIds
dev_langs:
- CSharp
- C++
- VB
---

# GetMultipleBuyDiscountLinesByOfferIds Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get all the multi buy discount lines associated with the given offers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetMultipleBuyDiscountLinesByOfferIds ( _
    offerIds As IEnumerable(Of String) _
) As ReadOnlyCollection(Of QuantityDiscountLevel)
'Usage
Dim instance As IPricingDataManagerV2
Dim offerIds As IEnumerable(Of String)
Dim returnValue As ReadOnlyCollection(Of QuantityDiscountLevel)

returnValue = instance.GetMultipleBuyDiscountLinesByOfferIds(offerIds)
```

``` csharp
ReadOnlyCollection<QuantityDiscountLevel> GetMultipleBuyDiscountLinesByOfferIds(
    IEnumerable<string> offerIds
)
```

``` c++
ReadOnlyCollection<QuantityDiscountLevel^>^ GetMultipleBuyDiscountLinesByOfferIds(
    IEnumerable<String^>^ offerIds
)
```

#### Parameters

  - offerIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[QuantityDiscountLevel](quantitydiscountlevel-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Collection of multi buy discount lines associated with the given offer Ids.  

## See Also

#### Reference

[IPricingDataManagerV2 Interface](ipricingdatamanagerv2-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

