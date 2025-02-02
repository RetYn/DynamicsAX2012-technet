---
title: SharePointTimerJobHelper.UnregisterSPService Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: UnregisterSPService Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTimerJobHelper.UnregisterSPService(Microsoft.SharePoint.Administration.SPFarm,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.sharepointtimerjobhelper.unregisterspservice(v=AX.60)
ms:contentKeyID: 62205269
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTimerJobHelper.UnregisterSPService
dev_langs:
- CSharp
- C++
- VB
---

# UnregisterSPService Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Unregisters a service from the farm.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub UnregisterSPService ( _
    farm As SPFarm, _
    serviceName As String _
)
'Usage
Dim farm As SPFarm
Dim serviceName As String

SharePointTimerJobHelper.UnregisterSPService(farm, serviceName)
```

``` csharp
public static void UnregisterSPService(
    SPFarm farm,
    string serviceName
)
```

``` c++
public:
static void UnregisterSPService(
    SPFarm^ farm, 
    String^ serviceName
)
```

#### Parameters

  - farm  
    Type: SPFarm  

<!-- end list -->

  - serviceName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## Exceptions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="https://technet.microsoft.com/library/27426hcy(v=ax.60)">ArgumentNullException</a></td>
<td><p>farm or serviceName</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[SharePointTimerJobHelper Class](sharepointtimerjobhelper-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

