---
title: IssueGiftCardServiceRequest.CurrencyCode Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CurrencyCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueGiftCardServiceRequest.CurrencyCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.issuegiftcardservicerequest.currencycode(v=AX.60)
ms:contentKeyID: 62204777
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueGiftCardServiceRequest.CurrencyCode
dev_langs:
- CSharp
- C++
- VB
---

# CurrencyCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the gift card currency code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CurrencyCode As String
    Get
    Private Set
'Usage
Dim instance As IssueGiftCardServiceRequest
Dim value As String

value = instance.CurrencyCode
```

``` csharp
[DataMemberAttribute]
public string CurrencyCode { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CurrencyCode {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IssueGiftCardServiceRequest Class](issuegiftcardservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

