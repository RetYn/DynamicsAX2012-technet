---
title: ICustomerV1.DistrictName Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: DistrictName Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.DistrictName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerv1.districtname(v=AX.60)
ms:contentKeyID: 47128662
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.DistrictName
dev_langs:
- CSharp
- C++
- VB
---

# DistrictName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the district name.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property DistrictName As String
    Get
    Set
'Usage
Dim instance As ICustomerV1
Dim value As String

value = instance.DistrictName

instance.DistrictName = value
```

``` csharp
string DistrictName { get; set; }
```

``` c++
property String^ DistrictName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## Remarks

This is a Brazil-specific address field.

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

