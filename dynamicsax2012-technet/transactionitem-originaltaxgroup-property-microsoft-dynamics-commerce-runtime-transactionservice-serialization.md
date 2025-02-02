---
title: TransactionItem.OriginalTaxGroup Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: OriginalTaxGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.OriginalTaxGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.transactionitem.originaltaxgroup(v=AX.60)
ms:contentKeyID: 49819695
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.OriginalTaxGroup
dev_langs:
- CSharp
- C++
- VB
---

# OriginalTaxGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the original tax group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property OriginalTaxGroup As String
    Get
    Set
'Usage
Dim instance As TransactionItem
Dim value As String

value = instance.OriginalTaxGroup

instance.OriginalTaxGroup = value
```

``` csharp
public string OriginalTaxGroup { get; set; }
```

``` c++
public:
property String^ OriginalTaxGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The original tax group.  

## See Also

#### Reference

[TransactionItem Class](transactionitem-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)

