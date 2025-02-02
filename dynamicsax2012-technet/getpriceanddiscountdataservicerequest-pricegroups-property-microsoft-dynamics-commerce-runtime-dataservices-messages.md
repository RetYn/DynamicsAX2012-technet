---
title: GetPriceAndDiscountDataServiceRequest.PriceGroups Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: PriceGroups Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.PriceGroups
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getpriceanddiscountdataservicerequest.pricegroups(v=AX.60)
ms:contentKeyID: 65322126
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.PriceGroups
dev_langs:
- CSharp
- C++
- VB
---

# PriceGroups Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the list of price groups.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PriceGroups As ISet(Of String)
    Get
    Protected Set
'Usage
Dim instance As GetPriceAndDiscountDataServiceRequest
Dim value As ISet(Of String)

value = instance.PriceGroups

instance.PriceGroups = value
```

``` csharp
[DataMemberAttribute]
public ISet<string> PriceGroups { get; protected set; }
```

``` c++
[DataMemberAttribute]
public:
property ISet<String^>^ PriceGroups {
    ISet<String^>^ get ();
    protected: void set (ISet<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [ISet\<T\>](https://technet.microsoft.com/library/dd412081\(v=ax.60\)).  

## See Also

#### Reference

[GetPriceAndDiscountDataServiceRequest Class](getpriceanddiscountdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

