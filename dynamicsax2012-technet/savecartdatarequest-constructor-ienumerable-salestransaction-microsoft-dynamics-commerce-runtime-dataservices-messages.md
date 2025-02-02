---
title: SaveCartDataRequest Constructor (IEnumerable(SalesTransaction)) (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: SaveCartDataRequest Constructor (IEnumerable(SalesTransaction))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveCartDataRequest.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.savecartdatarequest.savecartdatarequest(v=AX.60)
ms:contentKeyID: 65322989
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SaveCartDataRequest Constructor (IEnumerable(SalesTransaction))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [SaveCartDataRequest](savecartdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesTransactions As IEnumerable(Of SalesTransaction) _
)
'Usage
Dim salesTransactions As IEnumerable(Of SalesTransaction)

Dim instance As New SaveCartDataRequest(salesTransactions)
```

``` csharp
public SaveCartDataRequest(
    IEnumerable<SalesTransaction> salesTransactions
)
```

``` c++
public:
SaveCartDataRequest(
    IEnumerable<SalesTransaction^>^ salesTransactions
)
```

#### Parameters

  - salesTransactions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[SaveCartDataRequest Class](savecartdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[SaveCartDataRequest Overload](savecartdatarequest-constructor-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

