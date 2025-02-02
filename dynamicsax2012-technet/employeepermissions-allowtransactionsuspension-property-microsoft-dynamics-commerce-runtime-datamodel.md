---
title: EmployeePermissions.AllowTransactionSuspension Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowTransactionSuspension Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowTransactionSuspension
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.allowtransactionsuspension(v=AX.60)
ms:contentKeyID: 62205333
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowTransactionSuspension
dev_langs:
- CSharp
- C++
- VB
---

# AllowTransactionSuspension Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether transaction suspension is allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<RequiredAttribute> _
<ColumnAttribute("ALLOWTRANSACTIONSUSPENSION")> _
Public Property AllowTransactionSuspension As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.AllowTransactionSuspension

instance.AllowTransactionSuspension = value
```

``` csharp
[IgnoreDataMemberAttribute]
[RequiredAttribute]
[ColumnAttribute("ALLOWTRANSACTIONSUSPENSION")]
public bool AllowTransactionSuspension { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[RequiredAttribute]
[ColumnAttribute(L"ALLOWTRANSACTIONSUSPENSION")]
public:
property bool AllowTransactionSuspension {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[EmployeePermissions Class](employeepermissions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

