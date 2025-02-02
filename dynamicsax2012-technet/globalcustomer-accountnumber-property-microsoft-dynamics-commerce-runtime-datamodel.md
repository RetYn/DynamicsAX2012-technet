---
title: GlobalCustomer.AccountNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AccountNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.GlobalCustomer.AccountNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.globalcustomer.accountnumber(v=AX.60)
ms:contentKeyID: 62214152
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.GlobalCustomer.AccountNumber
dev_langs:
- CSharp
- C++
- VB
---

# AccountNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the account number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ACCOUNTNUMBER")> _
Public Property AccountNumber As String
    Get
    Set
'Usage
Dim instance As GlobalCustomer
Dim value As String

value = instance.AccountNumber

instance.AccountNumber = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ACCOUNTNUMBER")]
public string AccountNumber { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ACCOUNTNUMBER")]
public:
property String^ AccountNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The account number.  

## See Also

#### Reference

[GlobalCustomer Class](globalcustomer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

