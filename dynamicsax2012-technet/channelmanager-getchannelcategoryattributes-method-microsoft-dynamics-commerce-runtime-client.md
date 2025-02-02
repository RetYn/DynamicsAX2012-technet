---
title: ChannelManager.GetChannelCategoryAttributes Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetChannelCategoryAttributes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetChannelCategoryAttributes(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getchannelcategoryattributes(v=AX.60)
ms:contentKeyID: 65318122
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetChannelCategoryAttributes
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelCategoryAttributes Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetChannelCategoryAttributes ( _
    settings As QueryResultSettings, _
    categoryId As Long _
) As ReadOnlyCollection(Of AttributeCategory)
'Usage
Dim instance As ChannelManager
Dim settings As QueryResultSettings
Dim categoryId As Long
Dim returnValue As ReadOnlyCollection(Of AttributeCategory)

returnValue = instance.GetChannelCategoryAttributes(settings, _
    categoryId)
```

``` csharp
public ReadOnlyCollection<AttributeCategory> GetChannelCategoryAttributes(
    QueryResultSettings settings,
    long categoryId
)
```

``` c++
public:
ReadOnlyCollection<AttributeCategory^>^ GetChannelCategoryAttributes(
    QueryResultSettings^ settings, 
    long long categoryId
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - categoryId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[AttributeCategory](attributecategory-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

