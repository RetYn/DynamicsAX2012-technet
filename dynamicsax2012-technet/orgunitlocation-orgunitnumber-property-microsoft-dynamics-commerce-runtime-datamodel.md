---
title: OrgUnitLocation.OrgUnitNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OrgUnitNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.OrgUnitNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitlocation.orgunitnumber(v=AX.60)
ms:contentKeyID: 62206554
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.OrgUnitNumber
dev_langs:
- CSharp
- C++
- VB
---

# OrgUnitNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the organization unit number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STORENUMBER")> _
<DataMemberAttribute> _
Public Property OrgUnitNumber As String
    Get
    Set
'Usage
Dim instance As OrgUnitLocation
Dim value As String

value = instance.OrgUnitNumber

instance.OrgUnitNumber = value
```

``` csharp
[ColumnAttribute("STORENUMBER")]
[DataMemberAttribute]
public string OrgUnitNumber { get; set; }
```

``` c++
[ColumnAttribute(L"STORENUMBER")]
[DataMemberAttribute]
public:
property String^ OrgUnitNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[OrgUnitLocation Class](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

