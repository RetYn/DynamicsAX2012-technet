---
title: IWishListService.RemoveItemFromWishList Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: RemoveItemFromWishList Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IWishListService.RemoveItemFromWishList(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.iwishlistservice.removeitemfromwishlist(v=AX.60)
ms:contentKeyID: 62202332
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IWishListService.RemoveItemFromWishList
dev_langs:
- CSharp
- C++
- VB
---

# RemoveItemFromWishList Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Remove item from wish list.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function RemoveItemFromWishList ( _
    wishListId As String, _
    listingId As String _
) As NullResponse
'Usage
Dim instance As IWishListService
Dim wishListId As String
Dim listingId As String
Dim returnValue As NullResponse

returnValue = instance.RemoveItemFromWishList(wishListId, _
    listingId)
```

``` csharp
[OperationContractAttribute]
NullResponse RemoveItemFromWishList(
    string wishListId,
    string listingId
)
```

``` c++
[OperationContractAttribute]
NullResponse^ RemoveItemFromWishList(
    String^ wishListId, 
    String^ listingId
)
```

#### Parameters

  - wishListId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - listingId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.NullResponse](nullresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [NullResponse](nullresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[IWishListService Interface](iwishlistservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

