---
title: CartLine.GiftCardOperation Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GiftCardOperation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.GiftCardOperation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.giftcardoperation(v=AX.60)
ms:contentKeyID: 62210988
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.GiftCardOperation
dev_langs:
- CSharp
- C++
- VB
---

# GiftCardOperation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating the type of gift card operation(Issue or AddTo).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property GiftCardOperation As GiftCardOperationType
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As GiftCardOperationType

value = instance.GiftCardOperation

instance.GiftCardOperation = value
```

``` csharp
[IgnoreDataMemberAttribute]
public GiftCardOperationType GiftCardOperation { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property GiftCardOperationType GiftCardOperation {
    GiftCardOperationType get ();
    void set (GiftCardOperationType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.GiftCardOperationType](giftcardoperationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [GiftCardOperationType](giftcardoperationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

