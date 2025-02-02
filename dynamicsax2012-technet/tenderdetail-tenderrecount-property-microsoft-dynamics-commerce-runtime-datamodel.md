---
title: TenderDetail.TenderRecount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TenderRecount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDetail.TenderRecount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderdetail.tenderrecount(v=AX.60)
ms:contentKeyID: 65317073
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDetail.TenderRecount
dev_langs:
- CSharp
- C++
- VB
---

# TenderRecount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TenderRecount As Integer
    Get
    Set
'Usage
Dim instance As TenderDetail
Dim value As Integer

value = instance.TenderRecount

instance.TenderRecount = value
```

``` csharp
[DataMemberAttribute]
public int TenderRecount { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int TenderRecount {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[TenderDetail Class](tenderdetail-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

