---
title: Transaction.TotalAmountWithCurrency Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: TotalAmountWithCurrency Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Transaction.TotalAmountWithCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.transaction.totalamountwithcurrency(v=AX.60)
ms:contentKeyID: 65317498
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Transaction.TotalAmountWithCurrency
dev_langs:
- CSharp
- C++
- VB
---

# TotalAmountWithCurrency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TotalAmountWithCurrency As String
    Get
    Set
'Usage
Dim instance As Transaction
Dim value As String

value = instance.TotalAmountWithCurrency

instance.TotalAmountWithCurrency = value
```

``` csharp
[DataMemberAttribute]
public string TotalAmountWithCurrency { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ TotalAmountWithCurrency {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Transaction Class](transaction-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

