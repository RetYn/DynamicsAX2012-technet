---
title: Barcode.ZeroPriceValid Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ZeroPriceValid Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.ZeroPriceValid
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.zeropricevalid(v=AX.60)
ms:contentKeyID: 62206561
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.ZeroPriceValid
dev_langs:
- CSharp
- C++
- VB
---

# ZeroPriceValid Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ZeroPriceValid As Boolean
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As Boolean

value = instance.ZeroPriceValid

instance.ZeroPriceValid = value
```

``` csharp
[DataMemberAttribute]
public bool ZeroPriceValid { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool ZeroPriceValid {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[Barcode Class](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

