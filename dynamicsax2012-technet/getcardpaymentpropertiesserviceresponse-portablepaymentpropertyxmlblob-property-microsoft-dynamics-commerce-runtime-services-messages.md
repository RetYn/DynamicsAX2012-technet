---
title: GetCardPaymentPropertiesServiceResponse.PortablePaymentPropertyXmlBlob Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: PortablePaymentPropertyXmlBlob Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCardPaymentPropertiesServiceResponse.PortablePaymentPropertyXmlBlob
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcardpaymentpropertiesserviceresponse.portablepaymentpropertyxmlblob(v=AX.60)
ms:contentKeyID: 65320210
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCardPaymentPropertiesServiceResponse.PortablePaymentPropertyXmlBlob
dev_langs:
- CSharp
- C++
- VB
---

# PortablePaymentPropertyXmlBlob Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PortablePaymentPropertyXmlBlob As String
    Get
    Private Set
'Usage
Dim instance As GetCardPaymentPropertiesServiceResponse
Dim value As String

value = instance.PortablePaymentPropertyXmlBlob
```

``` csharp
[DataMemberAttribute]
public string PortablePaymentPropertyXmlBlob { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ PortablePaymentPropertyXmlBlob {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetCardPaymentPropertiesServiceResponse Class](getcardpaymentpropertiesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

