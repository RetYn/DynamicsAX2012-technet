---
title: IRetailTransactionV1.KeyItemGroupPercent Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: KeyItemGroupPercent Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.KeyItemGroupPercent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.keyitemgrouppercent(v=AX.60)
ms:contentKeyID: 49840421
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.KeyItemGroupPercent
dev_langs:
- CSharp
- C++
- VB
---

# KeyItemGroupPercent Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The percentage of items that where sold as an item group.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property KeyItemGroupPercent As Decimal
    Get
    Set
'Usage
Dim instance As IRetailTransactionV1
Dim value As Decimal

value = instance.KeyItemGroupPercent

instance.KeyItemGroupPercent = value
```

``` csharp
decimal KeyItemGroupPercent { get; set; }
```

``` c++
property Decimal KeyItemGroupPercent {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

