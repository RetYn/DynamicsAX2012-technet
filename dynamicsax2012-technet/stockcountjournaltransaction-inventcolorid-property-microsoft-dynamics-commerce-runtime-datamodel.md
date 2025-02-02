---
title: StockCountJournalTransaction.InventColorId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventColorId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.InventColorId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.stockcountjournaltransaction.inventcolorid(v=AX.60)
ms:contentKeyID: 62213247
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.InventColorId
dev_langs:
- CSharp
- C++
- VB
---

# InventColorId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the inventory color identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVENTCOLORID")> _
<DataMemberAttribute> _
Public Property InventColorId As String
    Get
    Set
'Usage
Dim instance As StockCountJournalTransaction
Dim value As String

value = instance.InventColorId

instance.InventColorId = value
```

``` csharp
[ColumnAttribute("INVENTCOLORID")]
[DataMemberAttribute]
public string InventColorId { get; set; }
```

``` c++
[ColumnAttribute(L"INVENTCOLORID")]
[DataMemberAttribute]
public:
property String^ InventColorId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[StockCountJournalTransaction Class](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

