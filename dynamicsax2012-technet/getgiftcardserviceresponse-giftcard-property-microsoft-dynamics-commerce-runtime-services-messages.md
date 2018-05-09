﻿---
title: GetGiftCardServiceResponse.GiftCard Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GiftCard Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetGiftCardServiceResponse.GiftCard
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getgiftcardserviceresponse.giftcard(v=AX.60)
ms:contentKeyID: 62215107
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetGiftCardServiceResponse.GiftCard
dev_langs:
- CSharp
- C++
- VB
---

# GiftCard Property

Gets the gift card.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property GiftCard As GiftCard
    Get
    Private Set
'Usage
Dim instance As GetGiftCardServiceResponse
Dim value As GiftCard

value = instance.GiftCard
```

``` csharp
[DataMemberAttribute]
public GiftCard GiftCard { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property GiftCard^ GiftCard {
    GiftCard^ get ();
    private: void set (GiftCard^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.GiftCard](giftcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [GiftCard](giftcard-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetGiftCardServiceResponse Class](getgiftcardserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)
