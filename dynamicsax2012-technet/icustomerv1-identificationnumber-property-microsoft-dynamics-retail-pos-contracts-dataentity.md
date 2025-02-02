---
title: ICustomerV1.IdentificationNumber Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IdentificationNumber Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.IdentificationNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerv1.identificationnumber(v=AX.60)
ms:contentKeyID: 47128121
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.IdentificationNumber
dev_langs:
- CSharp
- C++
- VB
---

# IdentificationNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer's identification number.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property IdentificationNumber As String
    Get
    Set
'Usage
Dim instance As ICustomerV1
Dim value As String

value = instance.IdentificationNumber

instance.IdentificationNumber = value
```

``` csharp
string IdentificationNumber { get; set; }
```

``` c++
property String^ IdentificationNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## Remarks

When Microsoft Dynamics AX is enabled for Israel, this field is called National ID.

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

