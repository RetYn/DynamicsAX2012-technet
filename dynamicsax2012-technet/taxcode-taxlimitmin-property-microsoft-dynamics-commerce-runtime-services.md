---
title: TaxCode.TaxLimitMin Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: TaxLimitMin Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxLimitMin
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcode.taxlimitmin(v=AX.60)
ms:contentKeyID: 49847464
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxLimitMin
dev_langs:
- CSharp
- C++
- VB
---

# TaxLimitMin Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Minimum amount required to calculate this tax.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property TaxLimitMin As Decimal
    Get
    Private Set
'Usage
Dim instance As TaxCode
Dim value As Decimal

value = instance.TaxLimitMin
```

``` csharp
public decimal TaxLimitMin { get; private set; }
```

``` c++
public:
property Decimal TaxLimitMin {
    Decimal get ();
    private: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## Remarks

REMOVE in favor of TaxIntervals collection. If the price is less than this, then the tax will not be calculated

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

