---
title: ListingPrice.AdjustedPrice Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: AdjustedPrice Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ListingPrice.AdjustedPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.listingprice.adjustedprice(v=AX.60)
ms:contentKeyID: 65317099
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ListingPrice.AdjustedPrice
dev_langs:
- CSharp
- C++
- VB
---

# AdjustedPrice Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AdjustedPrice As Decimal
    Get
    Set
'Usage
Dim instance As ListingPrice
Dim value As Decimal

value = instance.AdjustedPrice

instance.AdjustedPrice = value
```

``` csharp
[DataMemberAttribute]
public decimal AdjustedPrice { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal AdjustedPrice {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[ListingPrice Class](listingprice-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

