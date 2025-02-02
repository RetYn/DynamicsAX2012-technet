---
title: WishListLine.ImageUrl Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ImageUrl Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.WishListLine.ImageUrl
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.wishlistline.imageurl(v=AX.60)
ms:contentKeyID: 62206982
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.WishListLine.ImageUrl
dev_langs:
- CSharp
- C++
- VB
---

# ImageUrl Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the product image url.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ImageUrl As String
    Get
    Set
'Usage
Dim instance As WishListLine
Dim value As String

value = instance.ImageUrl

instance.ImageUrl = value
```

``` csharp
[DataMemberAttribute]
public string ImageUrl { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ImageUrl {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[WishListLine Class](wishlistline-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

