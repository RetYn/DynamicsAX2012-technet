---
title: TransactionServiceClient.RetailServerStaffLogOn Method (String, Int64, Int64, String) (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: RetailServerStaffLogOn Method (String, Int64, Int64, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.RetailServerStaffLogOn(System.String,System.Int64,System.Int64,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.retailserverstafflogon(v=AX.60)
ms:contentKeyID: 62208005
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# RetailServerStaffLogOn Method (String, Int64, Int64, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Logs the specified user on.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function RetailServerStaffLogOn ( _
    staffId As String, _
    storeRecordId As Long, _
    terminalRecordId As Long, _
    password As String _
) As Employee
'Usage
Dim instance As TransactionServiceClient
Dim staffId As String
Dim storeRecordId As Long
Dim terminalRecordId As Long
Dim password As String
Dim returnValue As Employee

returnValue = instance.RetailServerStaffLogOn(staffId, _
    storeRecordId, terminalRecordId, _
    password)
```

``` csharp
public Employee RetailServerStaffLogOn(
    string staffId,
    long storeRecordId,
    long terminalRecordId,
    string password
)
```

``` c++
public:
Employee^ RetailServerStaffLogOn(
    String^ staffId, 
    long long storeRecordId, 
    long long terminalRecordId, 
    String^ password
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - storeRecordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - terminalRecordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - password  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The employee information.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[RetailServerStaffLogOn Overload](transactionserviceclient-retailserverstafflogon-method-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

