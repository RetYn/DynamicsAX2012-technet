---
title: GetDiscountCodesServiceResponse.DiscountCodes Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: DiscountCodes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDiscountCodesServiceResponse.DiscountCodes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getdiscountcodesserviceresponse.discountcodes(v=AX.60)
ms:contentKeyID: 62214177
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDiscountCodesServiceResponse.DiscountCodes
dev_langs:
- CSharp
- C++
- VB
---

# DiscountCodes Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the discount codes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DiscountCodes As ReadOnlyCollection(Of DiscountCode)
    Get
    Private Set
'Usage
Dim instance As GetDiscountCodesServiceResponse
Dim value As ReadOnlyCollection(Of DiscountCode)

value = instance.DiscountCodes
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<DiscountCode> DiscountCodes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<DiscountCode^>^ DiscountCodes {
    ReadOnlyCollection<DiscountCode^>^ get ();
    private: void set (ReadOnlyCollection<DiscountCode^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[DiscountCode](discountcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetDiscountCodesServiceResponse Class](getdiscountcodesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

