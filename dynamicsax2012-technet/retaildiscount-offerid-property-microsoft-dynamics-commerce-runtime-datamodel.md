---
title: RetailDiscount.OfferId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OfferId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.OfferId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscount.offerid(v=AX.60)
ms:contentKeyID: 62207794
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.OfferId
dev_langs:
- CSharp
- C++
- VB
---

# OfferId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the offer identifier of the discount this rule is part of.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("OFFERID")> _
Public Property OfferId As String
    Get
    Set
'Usage
Dim instance As RetailDiscount
Dim value As String

value = instance.OfferId

instance.OfferId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("OFFERID")]
public string OfferId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"OFFERID")]
public:
property String^ OfferId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscount Class](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

