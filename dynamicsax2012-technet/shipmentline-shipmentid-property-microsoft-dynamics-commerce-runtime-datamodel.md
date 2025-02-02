---
title: ShipmentLine.ShipmentId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShipmentId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentLine.ShipmentId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shipmentline.shipmentid(v=AX.60)
ms:contentKeyID: 65321518
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentLine.ShipmentId
dev_langs:
- CSharp
- C++
- VB
---

# ShipmentId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PACKINGSLIPID")> _
Public Property ShipmentId As String
    Get
    Set
'Usage
Dim instance As ShipmentLine
Dim value As String

value = instance.ShipmentId

instance.ShipmentId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PACKINGSLIPID")]
public string ShipmentId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PACKINGSLIPID")]
public:
property String^ ShipmentId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ShipmentLine Class](shipmentline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

