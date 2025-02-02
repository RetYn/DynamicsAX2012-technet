---
title: DeviceConfiguration.LogOnBackgroundPictureAsBase64 Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LogOnBackgroundPictureAsBase64 Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.LogOnBackgroundPictureAsBase64
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.logonbackgroundpictureasbase64(v=AX.60)
ms:contentKeyID: 62213726
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.LogOnBackgroundPictureAsBase64
dev_langs:
- CSharp
- C++
- VB
---

# LogOnBackgroundPictureAsBase64 Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the log on background picture as base64.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LogOnBackgroundPictureAsBase64 As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.LogOnBackgroundPictureAsBase64

instance.LogOnBackgroundPictureAsBase64 = value
```

``` csharp
[DataMemberAttribute]
public string LogOnBackgroundPictureAsBase64 { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ LogOnBackgroundPictureAsBase64 {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

