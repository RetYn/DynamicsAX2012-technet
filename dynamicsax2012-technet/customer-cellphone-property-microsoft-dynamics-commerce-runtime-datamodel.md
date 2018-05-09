﻿---
title: Customer.Cellphone Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Cellphone Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.Cellphone
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.customer.cellphone(v=AX.60)
ms:contentKeyID: 62208818
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.Cellphone
dev_langs:
- CSharp
- C++
- VB
---

# Cellphone Property

Gets or sets the phone number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CELLPHONE")> _
Public Property Cellphone As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.Cellphone

instance.Cellphone = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CELLPHONE")]
public string Cellphone { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CELLPHONE")]
public:
property String^ Cellphone {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
