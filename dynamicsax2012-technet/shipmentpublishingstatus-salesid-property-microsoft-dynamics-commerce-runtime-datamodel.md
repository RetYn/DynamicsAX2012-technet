---
title: ShipmentPublishingStatus.SalesId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentPublishingStatus.SalesId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shipmentpublishingstatus.salesid(v=AX.60)
ms:contentKeyID: 62211106
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentPublishingStatus.SalesId
dev_langs:
- CSharp
- C++
- VB
---

# SalesId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sales id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SALESID")> _
Public Property SalesId As String
    Get
    Set
'Usage
Dim instance As ShipmentPublishingStatus
Dim value As String

value = instance.SalesId

instance.SalesId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SALESID")]
public string SalesId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SALESID")]
public:
property String^ SalesId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ShipmentPublishingStatus Class](shipmentpublishingstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

