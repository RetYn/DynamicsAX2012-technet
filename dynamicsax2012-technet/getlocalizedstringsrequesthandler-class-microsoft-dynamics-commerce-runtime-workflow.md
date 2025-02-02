---
title: GetLocalizedStringsRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetLocalizedStringsRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetLocalizedStringsRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getlocalizedstringsrequesthandler(v=AX.60)
ms:contentKeyID: 62214874
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetLocalizedStringsRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetLocalizedStringsRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to retrieve localized strings.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Class GetLocalizedStringsRequestHandler _
    Inherits WorkflowRequestHandler(Of GetLocalizedStringsRequest, GetLocalizedStringsResponse)
'Usage
Dim instance As GetLocalizedStringsRequestHandler
```

``` csharp
public class GetLocalizedStringsRequestHandler : WorkflowRequestHandler<GetLocalizedStringsRequest, GetLocalizedStringsResponse>
```

``` c++
public ref class GetLocalizedStringsRequestHandler : public WorkflowRequestHandler<GetLocalizedStringsRequest^, GetLocalizedStringsResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetLocalizedStringsRequest](getlocalizedstringsrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetLocalizedStringsResponse](getlocalizedstringsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetLocalizedStringsRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

