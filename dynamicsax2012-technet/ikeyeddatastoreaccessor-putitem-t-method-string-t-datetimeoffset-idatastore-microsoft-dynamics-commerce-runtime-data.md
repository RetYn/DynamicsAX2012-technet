---
title: IKeyedDataStoreAccessor.PutItem(T) Method (String, T, DateTimeOffset, IDataStore) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutItem(T) Method (String, T, DateTimeOffset, IDataStore)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IKeyedDataStoreAccessor.PutItem``1(System.String,``0,System.DateTimeOffset,Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore)
ms:mtpsurl: https://technet.microsoft.com/library/Dn988905(v=AX.60)
ms:contentKeyID: 65318355
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PutItem(T) Method (String, T, DateTimeOffset, IDataStore)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Sub PutItem(Of T) ( _
    key As String, _
    item As T, _
    absoluteExpiration As DateTimeOffset, _
    currentStore As IDataStore _
)
'Usage
Dim instance As IKeyedDataStoreAccessor
Dim key As String
Dim item As T
Dim absoluteExpiration As DateTimeOffset
Dim currentStore As IDataStore

instance.PutItem(key, item, absoluteExpiration, _
    currentStore)
```

``` csharp
void PutItem<T>(
    string key,
    T item,
    DateTimeOffset absoluteExpiration,
    IDataStore currentStore
)
```

``` c++
generic<typename T>
void PutItem(
    String^ key, 
    T item, 
    DateTimeOffset absoluteExpiration, 
    IDataStore^ currentStore
)
```

#### Type Parameters

  - T

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - item  
    Type: T  

<!-- end list -->

  - absoluteExpiration  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

<!-- end list -->

  - currentStore  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[IKeyedDataStoreAccessor Interface](ikeyeddatastoreaccessor-interface-microsoft-dynamics-commerce-runtime-data.md)

[PutItem\<T\> Overload](ikeyeddatastoreaccessor-putitem-t-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

