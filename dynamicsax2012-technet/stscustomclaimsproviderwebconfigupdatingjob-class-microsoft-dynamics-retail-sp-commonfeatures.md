---
title: STSCustomClaimsProviderWebConfigUpdatingJob Class (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: STSCustomClaimsProviderWebConfigUpdatingJob Class
ms:assetid: T:Microsoft.Dynamics.Retail.SP.CommonFeatures.STSCustomClaimsProviderWebConfigUpdatingJob
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.stscustomclaimsproviderwebconfigupdatingjob(v=AX.60)
ms:contentKeyID: 62207501
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.STSCustomClaimsProviderWebConfigUpdatingJob
dev_langs:
- CSharp
- C++
- VB
---

# STSCustomClaimsProviderWebConfigUpdatingJob Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Job that makes web.config file changes in the STS. STS does not seem to be supported by the "normal" web.config-updating infrastructure, hence we do this directly via editing the xml.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public MustInherit Class STSCustomClaimsProviderWebConfigUpdatingJob _
    Inherits SPJobDefinition
'Usage
Dim instance As STSCustomClaimsProviderWebConfigUpdatingJob
```

``` csharp
public abstract class STSCustomClaimsProviderWebConfigUpdatingJob : SPJobDefinition
```

``` c++
public ref class STSCustomClaimsProviderWebConfigUpdatingJob abstract : public SPJobDefinition
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  SPAutoSerializingObject  
    SPPersistedObject  
      SPJobDefinition  
        Microsoft.Dynamics.Retail.SP.CommonFeatures.STSCustomClaimsProviderWebConfigUpdatingJob  
          [Microsoft.Dynamics.Retail.SP.CommonFeatures.STSCustomClaimsProviderWebConfigActivationJob](stscustomclaimsproviderwebconfigactivationjob-class-microsoft-dynamics-retail-sp-commonfeatures.md)  
          [Microsoft.Dynamics.Retail.SP.CommonFeatures.STSCustomClaimsProviderWebConfigDeactivationJob](stscustomclaimsproviderwebconfigdeactivationjob-class-microsoft-dynamics-retail-sp-commonfeatures.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

