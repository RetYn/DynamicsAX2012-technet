---
title: SecurityException Constructor (String, String, Object ) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: SecurityException Constructor (String, String, Object )
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.SecurityException.#ctor(System.String,System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.securityexception.securityexception(v=AX.60)
ms:contentKeyID: 49829751
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SecurityException Constructor (String, String, Object[])


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [SecurityException](securityexception-class-microsoft-dynamics-commerce-runtime.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    errorResourceId As String, _
    message As String, _
    ParamArray args As Object() _
)
'Usage
Dim errorResourceId As String
Dim message As String
Dim args As Object()

Dim instance As New SecurityException(errorResourceId, _
    message, args)
```

``` csharp
public SecurityException(
    string errorResourceId,
    string message,
    params Object[] args
)
```

``` c++
public:
SecurityException(
    String^ errorResourceId, 
    String^ message, 
    ... array<Object^>^ args
)
```

#### Parameters

  - errorResourceId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - message  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - args  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\[\]  

## See Also

#### Reference

[SecurityException Class](securityexception-class-microsoft-dynamics-commerce-runtime.md)

[SecurityException Overload](securityexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

