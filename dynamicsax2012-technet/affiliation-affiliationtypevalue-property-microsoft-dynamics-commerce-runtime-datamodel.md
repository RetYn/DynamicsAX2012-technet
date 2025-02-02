---
title: Affiliation.AffiliationTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AffiliationTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Affiliation.AffiliationTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.affiliation.affiliationtypevalue(v=AX.60)
ms:contentKeyID: 62213051
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Affiliation.AffiliationTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# AffiliationTypeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of the affiliation enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AffiliationTypeValue As Integer
    Get
    Set
'Usage
Dim instance As Affiliation
Dim value As Integer

value = instance.AffiliationTypeValue

instance.AffiliationTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int AffiliationTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int AffiliationTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[Affiliation Class](affiliation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

