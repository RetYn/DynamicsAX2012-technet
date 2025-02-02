---
title: OrgUnit.UseDestinationBasedTax Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UseDestinationBasedTax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.UseDestinationBasedTax
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunit.usedestinationbasedtax(v=AX.60)
ms:contentKeyID: 62209489
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.UseDestinationBasedTax
dev_langs:
- CSharp
- C++
- VB
---

# UseDestinationBasedTax Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether destination based tax is used.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("USEDESTINATIONBASEDTAX")> _
<DataMemberAttribute> _
Public Property UseDestinationBasedTax As Boolean
    Get
    Set
'Usage
Dim instance As OrgUnit
Dim value As Boolean

value = instance.UseDestinationBasedTax

instance.UseDestinationBasedTax = value
```

``` csharp
[ColumnAttribute("USEDESTINATIONBASEDTAX")]
[DataMemberAttribute]
public bool UseDestinationBasedTax { get; set; }
```

``` c++
[ColumnAttribute(L"USEDESTINATIONBASEDTAX")]
[DataMemberAttribute]
public:
property bool UseDestinationBasedTax {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[OrgUnit Class](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

