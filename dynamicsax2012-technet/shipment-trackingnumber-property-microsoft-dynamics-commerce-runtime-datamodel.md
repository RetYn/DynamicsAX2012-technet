---
title: Shipment.TrackingNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TrackingNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shipment.TrackingNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shipment.trackingnumber(v=AX.60)
ms:contentKeyID: 49833429
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shipment.TrackingNumber
dev_langs:
- CSharp
- C++
- VB
---

# TrackingNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tracking number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TRACKINGNUMBER")> _
<DataMemberAttribute> _
Public Property TrackingNumber As String
    Get
    Set
'Usage
Dim instance As Shipment
Dim value As String

value = instance.TrackingNumber

instance.TrackingNumber = value
```

``` csharp
[ColumnAttribute("TRACKINGNUMBER")]
[DataMemberAttribute]
public string TrackingNumber { get; set; }
```

``` c++
[ColumnAttribute(L"TRACKINGNUMBER")]
[DataMemberAttribute]
public:
property String^ TrackingNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The tracking number.  

## See Also

#### Reference

[Shipment Class](shipment-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

