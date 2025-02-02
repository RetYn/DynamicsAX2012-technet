---
title: GetRoundedStringServiceResponse.RoundedValue Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: RoundedValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundedStringServiceResponse.RoundedValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getroundedstringserviceresponse.roundedvalue(v=AX.60)
ms:contentKeyID: 62207901
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundedStringServiceResponse.RoundedValue
dev_langs:
- CSharp
- C++
- VB
---

# RoundedValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the rounded value which was calculated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RoundedValue As String
    Get
    Private Set
'Usage
Dim instance As GetRoundedStringServiceResponse
Dim value As String

value = instance.RoundedValue
```

``` csharp
[DataMemberAttribute]
public string RoundedValue { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ RoundedValue {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetRoundedStringServiceResponse Class](getroundedstringserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

