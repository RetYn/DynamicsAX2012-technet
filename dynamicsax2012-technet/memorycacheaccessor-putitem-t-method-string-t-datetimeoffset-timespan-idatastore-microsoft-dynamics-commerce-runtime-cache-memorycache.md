---
title: MemoryCacheAccessor.PutItem(T) Method (String, T, DateTimeOffset, TimeSpan, IDataStore) (Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache)
TOCTitle: PutItem(T) Method (String, T, DateTimeOffset, TimeSpan, IDataStore)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache.MemoryCacheAccessor.PutItem``1(System.String,``0,System.DateTimeOffset,System.TimeSpan,Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore)
ms:mtpsurl: https://technet.microsoft.com/library/Dn990053(v=AX.60)
ms:contentKeyID: 65320743
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PutItem(T) Method (String, T, DateTimeOffset, TimeSpan, IDataStore)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Puts an item in the cache under the specified key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache](microsoft-dynamics-commerce-runtime-cache-memorycache-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache (in Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache.dll)

## Syntax

``` vb
'Declaration
Public Sub PutItem(Of T) ( _
    key As String, _
    item As T, _
    absoluteExpiration As DateTimeOffset, _
    slidingExpiration As TimeSpan, _
    currentStore As IDataStore _
)
'Usage
Dim instance As MemoryCacheAccessor
Dim key As String
Dim item As T
Dim absoluteExpiration As DateTimeOffset
Dim slidingExpiration As TimeSpan
Dim currentStore As IDataStore

instance.PutItem(key, item, absoluteExpiration, _
    slidingExpiration, currentStore)
```

``` csharp
public void PutItem<T>(
    string key,
    T item,
    DateTimeOffset absoluteExpiration,
    TimeSpan slidingExpiration,
    IDataStore currentStore
)
```

``` c++
public:
generic<typename T>
virtual void PutItem(
    String^ key, 
    T item, 
    DateTimeOffset absoluteExpiration, 
    TimeSpan slidingExpiration, 
    IDataStore^ currentStore
) sealed
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

  - slidingExpiration  
    Type: [System.TimeSpan](https://technet.microsoft.com/library/269ew577\(v=ax.60\))  

<!-- end list -->

  - currentStore  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)  

#### Implements

[IKeyedDataStoreAccessor.PutItem\<T\>(String, T, DateTimeOffset, TimeSpan, IDataStore)](ikeyeddatastoreaccessor-putitem-t-method-string-t-datetimeoffset-timespan-idatastore-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[MemoryCacheAccessor Class](memorycacheaccessor-class-microsoft-dynamics-commerce-runtime-cache-memorycache.md)

[PutItem\<T\> Overload](memorycacheaccessor-putitem-t-method-microsoft-dynamics-commerce-runtime-cache-memorycache.md)

[Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache Namespace](microsoft-dynamics-commerce-runtime-cache-memorycache-namespace.md)

