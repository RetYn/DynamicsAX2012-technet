---
title: TenderLineBase.LoyaltyCardId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LoyaltyCardId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.LoyaltyCardId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinebase.loyaltycardid(v=AX.60)
ms:contentKeyID: 62213793
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.LoyaltyCardId
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCardId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets loyalty card identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LOYALTYCARDID")> _
Public Property LoyaltyCardId As String
    Get
    Set
'Usage
Dim instance As TenderLineBase
Dim value As String

value = instance.LoyaltyCardId

instance.LoyaltyCardId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LOYALTYCARDID")]
public string LoyaltyCardId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LOYALTYCARDID")]
public:
property String^ LoyaltyCardId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TenderLineBase Class](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

