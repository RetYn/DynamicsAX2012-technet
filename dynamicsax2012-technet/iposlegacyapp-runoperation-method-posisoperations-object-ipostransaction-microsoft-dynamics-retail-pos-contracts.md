---
title: IPosLegacyApp.RunOperation Method (PosisOperations, Object, IPosTransaction) (Microsoft.Dynamics.Retail.Pos.Contracts)
TOCTitle: RunOperation Method (PosisOperations, Object, IPosTransaction)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.IPosLegacyApp.RunOperation(Microsoft.Dynamics.Retail.Pos.Contracts.PosisOperations,System.Object,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.iposlegacyapp.runoperation(v=AX.60)
ms:contentKeyID: 47128104
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# RunOperation Method (PosisOperations, Object, IPosTransaction)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Runs a POS operation.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts](microsoft-dynamics-retail-pos-contracts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function RunOperation ( _
    operationID As PosisOperations, _
    extraInfo As Object, _
    transaction As IPosTransaction _
) As IPosTransaction
'Usage
Dim instance As IPosLegacyApp
Dim operationID As PosisOperations
Dim extraInfo As Object
Dim transaction As IPosTransaction
Dim returnValue As IPosTransaction

returnValue = instance.RunOperation(operationID, _
    extraInfo, transaction)
```

``` csharp
IPosTransaction RunOperation(
    PosisOperations operationID,
    Object extraInfo,
    IPosTransaction transaction
)
```

``` c++
IPosTransaction^ RunOperation(
    PosisOperations operationID, 
    Object^ extraInfo, 
    IPosTransaction^ transaction
)
```

#### Parameters

  - operationID  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.PosisOperations](posisoperations-enumeration-microsoft-dynamics-retail-pos-contracts.md)  

<!-- end list -->

  - extraInfo  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

<!-- end list -->

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The POS transaction object  

## See Also

#### Reference

[IPosLegacyApp Interface](iposlegacyapp-interface-microsoft-dynamics-retail-pos-contracts.md)

[RunOperation Overload](iposlegacyapp-runoperation-method-microsoft-dynamics-retail-pos-contracts.md)

[Microsoft.Dynamics.Retail.Pos.Contracts Namespace](microsoft-dynamics-retail-pos-contracts-namespace.md)

