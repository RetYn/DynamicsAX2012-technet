---
title: TransactionServiceProfile.PasswordEncryptionType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PasswordEncryptionType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.PasswordEncryptionType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transactionserviceprofile.passwordencryptiontype(v=AX.60)
ms:contentKeyID: 62210367
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.PasswordEncryptionType
dev_langs:
- CSharp
- C++
- VB
---

# PasswordEncryptionType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the transaction service password encryption type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TSPASSWORDENCRYPTION")> _
Public ReadOnly Property PasswordEncryptionType As String
    Get
'Usage
Dim instance As TransactionServiceProfile
Dim value As String

value = instance.PasswordEncryptionType
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TSPASSWORDENCRYPTION")]
public string PasswordEncryptionType { get; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TSPASSWORDENCRYPTION")]
public:
property String^ PasswordEncryptionType {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TransactionServiceProfile Class](transactionserviceprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

