---
title: HardwareProfilePrinter.DeviceName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeviceName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.DeviceName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofileprinter.devicename(v=AX.60)
ms:contentKeyID: 62212483
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.DeviceName
dev_langs:
- CSharp
- C++
- VB
---

# DeviceName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the printer device name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PRINTERDEVICENAMEVALUE")> _
Public Property DeviceName As String
    Get
    Set
'Usage
Dim instance As HardwareProfilePrinter
Dim value As String

value = instance.DeviceName

instance.DeviceName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PRINTERDEVICENAMEVALUE")]
public string DeviceName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PRINTERDEVICENAMEVALUE")]
public:
property String^ DeviceName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The name string.  

## See Also

#### Reference

[HardwareProfilePrinter Class](hardwareprofileprinter-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

