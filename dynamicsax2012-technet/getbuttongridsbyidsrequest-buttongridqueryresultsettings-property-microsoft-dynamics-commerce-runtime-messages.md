---
title: GetButtonGridsByIdsRequest.ButtonGridQueryResultSettings Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ButtonGridQueryResultSettings Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetButtonGridsByIdsRequest.ButtonGridQueryResultSettings
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getbuttongridsbyidsrequest.buttongridqueryresultsettings(v=AX.60)
ms:contentKeyID: 62208300
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetButtonGridsByIdsRequest.ButtonGridQueryResultSettings
dev_langs:
- CSharp
- C++
- VB
---

# ButtonGridQueryResultSettings Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the buttongrids query result setting.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ButtonGridQueryResultSettings As QueryResultSettings
    Get
    Private Set
'Usage
Dim instance As GetButtonGridsByIdsRequest
Dim value As QueryResultSettings

value = instance.ButtonGridQueryResultSettings
```

``` csharp
[DataMemberAttribute]
public QueryResultSettings ButtonGridQueryResultSettings { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property QueryResultSettings^ ButtonGridQueryResultSettings {
    QueryResultSettings^ get ();
    private: void set (QueryResultSettings^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns QueryResultSettings.  

## See Also

#### Reference

[GetButtonGridsByIdsRequest Class](getbuttongridsbyidsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

