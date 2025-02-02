---
title: HardwareProfile.KeyLockDeviceName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KeyLockDeviceName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.KeyLockDeviceName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.keylockdevicename(v=AX.60)
ms:contentKeyID: 62209582
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.KeyLockDeviceName
dev_langs:
- CSharp
- C++
- VB
---

# KeyLockDeviceName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the keylock device name value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("KEYLOCKDEVICENAME")> _
Public Property KeyLockDeviceName As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.KeyLockDeviceName

instance.KeyLockDeviceName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("KEYLOCKDEVICENAME")]
public string KeyLockDeviceName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"KEYLOCKDEVICENAME")]
public:
property String^ KeyLockDeviceName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The device name string.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

