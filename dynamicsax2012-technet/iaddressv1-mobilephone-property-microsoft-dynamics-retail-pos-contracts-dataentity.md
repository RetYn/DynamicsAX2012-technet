---
title: IAddressV1.MobilePhone Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: MobilePhone Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressV1.MobilePhone
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iaddressv1.mobilephone(v=AX.60)
ms:contentKeyID: 47128231
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressV1.MobilePhone
dev_langs:
- CSharp
- C++
- VB
---

# MobilePhone Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the mobile number.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property MobilePhone As String
    Get
    Set
'Usage
Dim instance As IAddressV1
Dim value As String

value = instance.MobilePhone

instance.MobilePhone = value
```

``` csharp
string MobilePhone { get; set; }
```

``` c++
property String^ MobilePhone {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[IAddressV1 Interface](iaddressv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

