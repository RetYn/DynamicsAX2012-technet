---
title: IndiaTaxDatabaseAccessor.GetTaxComponentIndia Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTaxComponentIndia Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IndiaTaxDatabaseAccessor.GetTaxComponentIndia(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.indiataxdatabaseaccessor.gettaxcomponentindia(v=AX.60)
ms:contentKeyID: 62204348
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IndiaTaxDatabaseAccessor.GetTaxComponentIndia
dev_langs:
- CSharp
- C++
- VB
---

# GetTaxComponentIndia Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets Tax component.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTaxComponentIndia ( _
    taxCode As String _
) As TaxComponentIndia
'Usage
Dim instance As IndiaTaxDatabaseAccessor
Dim taxCode As String
Dim returnValue As TaxComponentIndia

returnValue = instance.GetTaxComponentIndia(taxCode)
```

``` csharp
public TaxComponentIndia GetTaxComponentIndia(
    string taxCode
)
```

``` c++
public:
TaxComponentIndia^ GetTaxComponentIndia(
    String^ taxCode
)
```

#### Parameters

  - taxCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxComponentIndia](taxcomponentindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Tax component.  

## See Also

#### Reference

[IndiaTaxDatabaseAccessor Class](indiataxdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

