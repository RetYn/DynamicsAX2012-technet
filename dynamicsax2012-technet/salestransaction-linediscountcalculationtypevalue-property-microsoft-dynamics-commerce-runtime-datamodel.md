---
title: SalesTransaction.LineDiscountCalculationTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineDiscountCalculationTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.LineDiscountCalculationTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.linediscountcalculationtypevalue(v=AX.60)
ms:contentKeyID: 62211992
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.LineDiscountCalculationTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# LineDiscountCalculationTypeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of the LineDiscountCalculationType. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LineDiscountCalculationTypeValue As Integer
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Integer

value = instance.LineDiscountCalculationTypeValue

instance.LineDiscountCalculationTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int LineDiscountCalculationTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int LineDiscountCalculationTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

