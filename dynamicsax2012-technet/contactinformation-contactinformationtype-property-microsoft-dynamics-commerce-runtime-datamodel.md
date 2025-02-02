---
title: ContactInformation.ContactInformationType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ContactInformationType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInformation.ContactInformationType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.contactinformation.contactinformationtype(v=AX.60)
ms:contentKeyID: 49833426
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInformation.ContactInformationType
dev_langs:
- CSharp
- C++
- VB
---

# ContactInformationType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the contact information type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TYPE")> _
Public Property ContactInformationType As ContactInformationType
    Get
    Set
'Usage
Dim instance As ContactInformation
Dim value As ContactInformationType

value = instance.ContactInformationType

instance.ContactInformationType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TYPE")]
public ContactInformationType ContactInformationType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TYPE")]
public:
property ContactInformationType ContactInformationType {
    ContactInformationType get ();
    void set (ContactInformationType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInformationType](contactinformationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ContactInformationType](contactinformationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ContactInformation Class](contactinformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

