---
title: HardwareProfile.MsrModel Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MsrModel Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.MSRModel
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.msrmodel(v=AX.60)
ms:contentKeyID: 62211933
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.MsrModel
dev_langs:
- CSharp
- C++
- VB
---

# MsrModel Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MSRMODEL")> _
<DataMemberAttribute> _
Public Property MsrModel As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.MsrModel

instance.MsrModel = value
```

``` csharp
[ColumnAttribute("MSRMODEL")]
[DataMemberAttribute]
public string MsrModel { get; set; }
```

``` c++
[ColumnAttribute(L"MSRMODEL")]
[DataMemberAttribute]
public:
property String^ MsrModel {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

