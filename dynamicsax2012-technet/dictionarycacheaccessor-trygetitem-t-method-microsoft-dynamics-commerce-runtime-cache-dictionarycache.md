---
title: DictionaryCacheAccessor.TryGetItem(T) Method  (Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache)
TOCTitle: TryGetItem(T) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache.DictionaryCacheAccessor.TryGetItem``1(System.String,``0@,Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore)
ms:mtpsurl: https://technet.microsoft.com/library/Dn969241(v=AX.60)
ms:contentKeyID: 65322855
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache.DictionaryCacheAccessor.TryGetItem``1
dev_langs:
- CSharp
- C++
- VB
---

# TryGetItem(T) Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Attempts to extract the item stored in the cache under the specified key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache](microsoft-dynamics-commerce-runtime-cache-dictionarycache-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache (in Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache.dll)

## Syntax

``` vb
'Declaration
Public Function TryGetItem(Of T) ( _
    key As String, _
    <OutAttribute> ByRef item As T, _
    currentStore As IDataStore _
) As Boolean
'Usage
Dim instance As DictionaryCacheAccessor
Dim key As String
Dim item As T
Dim currentStore As IDataStore
Dim returnValue As Boolean

returnValue = instance.TryGetItem(key, _
    item, currentStore)
```

``` csharp
public bool TryGetItem<T>(
    string key,
    out T item,
    IDataStore currentStore
)
```

``` c++
public:
generic<typename T>
virtual bool TryGetItem(
    String^ key, 
    [OutAttribute] T% item, 
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

  - currentStore  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if the key exists in the memory cache.  

#### Implements

[IKeyedDataStoreAccessor.TryGetItem\<T\>(String, T, IDataStore)](ikeyeddatastoreaccessor-trygetitem-t-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[DictionaryCacheAccessor Class](dictionarycacheaccessor-class-microsoft-dynamics-commerce-runtime-cache-dictionarycache.md)

[Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache Namespace](microsoft-dynamics-commerce-runtime-cache-dictionarycache-namespace.md)

