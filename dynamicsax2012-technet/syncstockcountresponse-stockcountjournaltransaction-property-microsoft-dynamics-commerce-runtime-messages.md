---
title: SyncStockCountResponse.StockCountJournalTransaction Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: StockCountJournalTransaction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SyncStockCountResponse.StockCountJournalTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.syncstockcountresponse.stockcountjournaltransaction(v=AX.60)
ms:contentKeyID: 62213457
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SyncStockCountResponse.StockCountJournalTransaction
dev_langs:
- CSharp
- C++
- VB
---

# StockCountJournalTransaction Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the StockCountJournal transaction collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StockCountJournalTransaction As ReadOnlyCollection(Of StockCountJournalTransaction)
    Get
    Private Set
'Usage
Dim instance As SyncStockCountResponse
Dim value As ReadOnlyCollection(Of StockCountJournalTransaction)

value = instance.StockCountJournalTransaction
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<StockCountJournalTransaction> StockCountJournalTransaction { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<StockCountJournalTransaction^>^ StockCountJournalTransaction {
    ReadOnlyCollection<StockCountJournalTransaction^>^ get ();
    private: void set (ReadOnlyCollection<StockCountJournalTransaction^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[SyncStockCountResponse Class](syncstockcountresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

