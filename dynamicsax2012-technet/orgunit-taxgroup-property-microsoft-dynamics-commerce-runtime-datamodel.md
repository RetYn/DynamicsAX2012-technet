---
title: OrgUnit.TaxGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.TaxGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunit.taxgroup(v=AX.60)
ms:contentKeyID: 62204948
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.TaxGroup
dev_langs:
- CSharp
- C++
- VB
---

# TaxGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tax group for this customer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXGROUP")> _
Public Property TaxGroup As String
    Get
    Set
'Usage
Dim instance As OrgUnit
Dim value As String

value = instance.TaxGroup

instance.TaxGroup = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXGROUP")]
public string TaxGroup { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXGROUP")]
public:
property String^ TaxGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[OrgUnit Class](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

