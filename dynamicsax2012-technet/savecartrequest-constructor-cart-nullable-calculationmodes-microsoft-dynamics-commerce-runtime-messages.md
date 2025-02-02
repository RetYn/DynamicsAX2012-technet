---
title: SaveCartRequest Constructor (Cart, Nullable(CalculationModes)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SaveCartRequest Constructor (Cart, Nullable(CalculationModes))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCartRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart,System.Nullable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savecartrequest.savecartrequest(v=AX.60)
ms:contentKeyID: 62202661
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SaveCartRequest Constructor (Cart, Nullable(CalculationModes))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [SaveCartRequest](savecartrequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    cart As Cart, _
    calculationModes As Nullable(Of CalculationModes) _
)
'Usage
Dim cart As Cart
Dim calculationModes As Nullable(Of CalculationModes)

Dim instance As New SaveCartRequest(cart, calculationModes)
```

``` csharp
public SaveCartRequest(
    Cart cart,
    Nullable<CalculationModes> calculationModes
)
```

``` c++
public:
SaveCartRequest(
    Cart^ cart, 
    Nullable<CalculationModes> calculationModes
)
```

#### Parameters

  - cart  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - calculationModes  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[CalculationModes](calculationmodes-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[SaveCartRequest Class](savecartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[SaveCartRequest Overload](savecartrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

