---
title: GetPriceAndDiscountDataServiceRequest.UnitId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: UnitId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.UnitId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getpriceanddiscountdataservicerequest.unitid(v=AX.60)
ms:contentKeyID: 65322712
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.UnitId
dev_langs:
- CSharp
- C++
- VB
---

# UnitId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the product unit identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property UnitId As String
    Get
    Protected Set
'Usage
Dim instance As GetPriceAndDiscountDataServiceRequest
Dim value As String

value = instance.UnitId

instance.UnitId = value
```

``` csharp
[DataMemberAttribute]
public string UnitId { get; protected set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ UnitId {
    String^ get ();
    protected: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetPriceAndDiscountDataServiceRequest Class](getpriceanddiscountdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

