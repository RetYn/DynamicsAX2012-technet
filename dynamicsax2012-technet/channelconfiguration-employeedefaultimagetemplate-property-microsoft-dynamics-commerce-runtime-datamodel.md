---
title: ChannelConfiguration.EmployeeDefaultImageTemplate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EmployeeDefaultImageTemplate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.EmployeeDefaultImageTemplate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.employeedefaultimagetemplate(v=AX.60)
ms:contentKeyID: 62203485
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.EmployeeDefaultImageTemplate
dev_langs:
- CSharp
- C++
- VB
---

# EmployeeDefaultImageTemplate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the default employee image template.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EMPLOYEEDEFAULTIMAGETEMPLATE")> _
<DataMemberAttribute> _
Public Property EmployeeDefaultImageTemplate As String
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As String

value = instance.EmployeeDefaultImageTemplate
```

``` csharp
[ColumnAttribute("EMPLOYEEDEFAULTIMAGETEMPLATE")]
[DataMemberAttribute]
public string EmployeeDefaultImageTemplate { get; internal set; }
```

``` c++
[ColumnAttribute(L"EMPLOYEEDEFAULTIMAGETEMPLATE")]
[DataMemberAttribute]
public:
property String^ EmployeeDefaultImageTemplate {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

