---
title: DataValidationException Constructor (String, String, Object ) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: DataValidationException Constructor (String, String, Object )
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataValidationException.#ctor(System.String,System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datavalidationexception.datavalidationexception(v=AX.60)
ms:contentKeyID: 49831038
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# DataValidationException Constructor (String, String, Object[])


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [DataValidationException](datavalidationexception-class-microsoft-dynamics-commerce-runtime.md) class.

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

Dim instance As New DataValidationException(errorResourceId, _
    message, args)
```

``` csharp
public DataValidationException(
    string errorResourceId,
    string message,
    params Object[] args
)
```

``` c++
public:
DataValidationException(
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

[DataValidationException Class](datavalidationexception-class-microsoft-dynamics-commerce-runtime.md)

[DataValidationException Overload](datavalidationexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

