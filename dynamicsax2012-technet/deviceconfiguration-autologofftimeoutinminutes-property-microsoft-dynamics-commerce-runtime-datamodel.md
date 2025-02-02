---
title: DeviceConfiguration.AutoLogOffTimeoutInMinutes Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AutoLogOffTimeoutInMinutes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.AutoLogOffTimeoutInMinutes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.autologofftimeoutinminutes(v=AX.60)
ms:contentKeyID: 62210935
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.AutoLogOffTimeoutInMinutes
dev_langs:
- CSharp
- C++
- VB
---

# AutoLogOffTimeoutInMinutes Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the auto logoff timeout value in minutes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("AUTOLOGOFFTIMEOUT")> _
<DataMemberAttribute> _
Public Property AutoLogOffTimeoutInMinutes As Integer
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Integer

value = instance.AutoLogOffTimeoutInMinutes

instance.AutoLogOffTimeoutInMinutes = value
```

``` csharp
[ColumnAttribute("AUTOLOGOFFTIMEOUT")]
[DataMemberAttribute]
public int AutoLogOffTimeoutInMinutes { get; set; }
```

``` c++
[ColumnAttribute(L"AUTOLOGOFFTIMEOUT")]
[DataMemberAttribute]
public:
property int AutoLogOffTimeoutInMinutes {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The auto logoff timeout value.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

