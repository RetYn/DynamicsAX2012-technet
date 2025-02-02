---
title: InventoryInfo.InventoryAvailable Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: InventoryAvailable Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.InventoryInfo.InventoryAvailable
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.inventoryinfo.inventoryavailable(v=AX.60)
ms:contentKeyID: 49848169
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.InventoryInfo.InventoryAvailable
dev_langs:
- CSharp
- C++
- VB
---

# InventoryAvailable Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the inventory available.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property InventoryAvailable As String
    Get
    Set
'Usage
Dim instance As InventoryInfo
Dim value As String

value = instance.InventoryAvailable

instance.InventoryAvailable = value
```

``` csharp
public string InventoryAvailable { get; set; }
```

``` c++
public:
property String^ InventoryAvailable {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The inventory available.  

## See Also

#### Reference

[InventoryInfo Class](inventoryinfo-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)

