---
title: Api.JetBeginTransaction2 method 
TOCTitle: 'JetBeginTransaction2 method '
ms:assetid: M:Microsoft.Isam.Esent.Interop.Api.JetBeginTransaction2(Microsoft.Isam.Esent.Interop.JET_SESID,Microsoft.Isam.Esent.Interop.BeginTransactionGrbit)
ms:mtpsurl: https://msdn.microsoft.com/library/microsoft.isam.esent.interop.api.jetbegintransaction2(v=EXCHG.10)
ms:contentKeyID: 55107226
ms.date: 07/30/2014
ms.topic: reference
f1_keywords:
- Microsoft.Isam.Esent.Interop.Api.JetBeginTransaction2
dev_langs:
- CSharp
- JScript
- VB
- other
api_name: 
- Microsoft.Isam.Esent.Interop.Api.JetBeginTransaction2
topic_type: 
- kbSyntax
- apiref
api_type: 
- Managed
api_location: 
- Microsoft.Isam.Esent.Interop.dll
ROBOTS: INDEX,FOLLOW

---

# Api.JetBeginTransaction2 method

Causes a session to enter a transaction or create a new save point in an existing transaction.

**Namespace:**  [Microsoft.Isam.Esent.Interop](hh596136\(v=exchg.10\).md)  
**Assembly:**  Microsoft.Isam.Esent.Interop (in Microsoft.Isam.Esent.Interop.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub JetBeginTransaction2 ( _
    sesid As JET_SESID, _
    grbit As BeginTransactionGrbit _
)
'Usage
Dim sesid As JET_SESID
Dim grbit As BeginTransactionGrbitApi.JetBeginTransaction2(sesid, _
    grbit)
```

``` csharp
public static void JetBeginTransaction2(
    JET_SESID sesid,
    BeginTransactionGrbit grbit
)
```

#### Parameters

  - sesid  
    Type: [Microsoft.Isam.Esent.Interop.JET_SESID](hh596745\(v=exchg.10\).md)  
    
    The session to begin the transaction for.

<!-- end list -->

  - grbit  
    Type: [Microsoft.Isam.Esent.Interop.BeginTransactionGrbit](hh558568\(v=exchg.10\).md)  
    
    Transaction options.

## See also

#### Reference

[Api class](dn292211\(v=exchg.10\).md)

[Api members](dn292213\(v=exchg.10\).md)

[Microsoft.Isam.Esent.Interop namespace](hh596136\(v=exchg.10\).md)

