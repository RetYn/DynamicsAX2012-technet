---
title: ShoppingCartItem.ProductDetailsJson Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ProductDetailsJson Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartItem.ProductDetailsJson
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.shoppingcartitem.productdetailsjson(v=AX.60)
ms:contentKeyID: 62205627
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartItem.ProductDetailsJson
dev_langs:
- CSharp
- C++
- VB
---

# ProductDetailsJson Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the product details json.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProductDetailsJson As String
    Get
    Set
'Usage
Dim instance As ShoppingCartItem
Dim value As String

value = instance.ProductDetailsJson

instance.ProductDetailsJson = value
```

``` csharp
[DataMemberAttribute]
public string ProductDetailsJson { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ProductDetailsJson {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ShoppingCartItem Class](shoppingcartitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

