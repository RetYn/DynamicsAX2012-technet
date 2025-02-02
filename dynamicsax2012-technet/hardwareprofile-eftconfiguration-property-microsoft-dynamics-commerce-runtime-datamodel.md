---
title: HardwareProfile.EftConfiguration Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EftConfiguration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EFTConfiguration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.eftconfiguration(v=AX.60)
ms:contentKeyID: 62207704
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EftConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# EftConfiguration Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EFTCONFIGURATION")> _
<DataMemberAttribute> _
Public Property EftConfiguration As Integer
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As Integer

value = instance.EftConfiguration

instance.EftConfiguration = value
```

``` csharp
[ColumnAttribute("EFTCONFIGURATION")]
[DataMemberAttribute]
public int EftConfiguration { get; set; }
```

``` c++
[ColumnAttribute(L"EFTCONFIGURATION")]
[DataMemberAttribute]
public:
property int EftConfiguration {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

