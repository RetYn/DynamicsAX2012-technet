---
title: CreditMemoRealtimeRequestBase Constructor (String, String, String) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CreditMemoRealtimeRequestBase Constructor (String, String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreditMemoRealtimeRequestBase.#ctor(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.creditmemorealtimerequestbase.creditmemorealtimerequestbase(v=AX.60)
ms:contentKeyID: 65318881
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CreditMemoRealtimeRequestBase Constructor (String, String, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Protected Sub New ( _
    memoId As String, _
    storeId As String, _
    terminalId As String _
)
'Usage
Dim memoId As String
Dim storeId As String
Dim terminalId As String

Dim instance As New CreditMemoRealtimeRequestBase(memoId, _
    storeId, terminalId)
```

``` csharp
protected CreditMemoRealtimeRequestBase(
    string memoId,
    string storeId,
    string terminalId
)
```

``` c++
protected:
CreditMemoRealtimeRequestBase(
    String^ memoId, 
    String^ storeId, 
    String^ terminalId
)
```

#### Parameters

  - memoId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - storeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CreditMemoRealtimeRequestBase Class](creditmemorealtimerequestbase-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[CreditMemoRealtimeRequestBase Overload](creditmemorealtimerequestbase-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

