---
title: ChannelConfiguration.GiftCardItemId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GiftCardItemId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.GiftCardItemId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.giftcarditemid(v=AX.60)
ms:contentKeyID: 62213064
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.GiftCardItemId
dev_langs:
- CSharp
- C++
- VB
---

# GiftCardItemId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the GiftCard ItemId.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("GIFTCARDITEM")> _
<DataMemberAttribute> _
Public Property GiftCardItemId As String
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As String

value = instance.GiftCardItemId
```

``` csharp
[ColumnAttribute("GIFTCARDITEM")]
[DataMemberAttribute]
public string GiftCardItemId { get; internal set; }
```

``` c++
[ColumnAttribute(L"GIFTCARDITEM")]
[DataMemberAttribute]
public:
property String^ GiftCardItemId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

