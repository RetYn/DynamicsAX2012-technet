---
title: StateProvinceInfo.StateId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StateId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.StateProvinceInfo.StateId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.stateprovinceinfo.stateid(v=AX.60)
ms:contentKeyID: 49847851
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.StateProvinceInfo.StateId
dev_langs:
- CSharp
- C++
- VB
---

# StateId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the state identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<KeyAttribute> _
<ColumnAttribute("STATEID")> _
Public Property StateId As String
    Get
    Set
'Usage
Dim instance As StateProvinceInfo
Dim value As String

value = instance.StateId

instance.StateId = value
```

``` csharp
[DataMemberAttribute]
[KeyAttribute]
[ColumnAttribute("STATEID")]
public string StateId { get; set; }
```

``` c++
[DataMemberAttribute]
[KeyAttribute]
[ColumnAttribute(L"STATEID")]
public:
property String^ StateId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[StateProvinceInfo Class](stateprovinceinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

