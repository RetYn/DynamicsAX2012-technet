---
title: CartWorkflowHelper.LoadSalesTransactionForReturn Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: LoadSalesTransactionForReturn Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.LoadSalesTransactionForReturn(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.loadsalestransactionforreturn(v=AX.60)
ms:contentKeyID: 62211390
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.LoadSalesTransactionForReturn
dev_langs:
- CSharp
- C++
- VB
---

# LoadSalesTransactionForReturn Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Loads a returned sales transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function LoadSalesTransactionForReturn ( _
    context As RequestContext, _
    cart As Cart _
) As SalesTransaction
'Usage
Dim context As RequestContext
Dim cart As Cart
Dim returnValue As SalesTransaction

returnValue = CartWorkflowHelper.LoadSalesTransactionForReturn(context, _
    cart)
```

``` csharp
public static SalesTransaction LoadSalesTransactionForReturn(
    RequestContext context,
    Cart cart
)
```

``` c++
public:
static SalesTransaction^ LoadSalesTransactionForReturn(
    RequestContext^ context, 
    Cart^ cart
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - cart  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The loaded returned sales transaction.  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

