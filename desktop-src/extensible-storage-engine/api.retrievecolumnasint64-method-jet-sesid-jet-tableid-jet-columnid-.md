---
description: "Learn more about: Api.RetrieveColumnAsInt64 method (JET_SESID, JET_TABLEID, JET_COLUMNID)"
title: Api.RetrieveColumnAsInt64 method (JET_SESID, JET_TABLEID, JET_COLUMNID)
TOCTitle: RetrieveColumnAsInt64 method (JET_SESID, JET_TABLEID, JET_COLUMNID)
ms:assetid: M:Microsoft.Isam.Esent.Interop.Api.RetrieveColumnAsInt64(Microsoft.Isam.Esent.Interop.JET_SESID,Microsoft.Isam.Esent.Interop.JET_TABLEID,Microsoft.Isam.Esent.Interop.JET_COLUMNID)
ms:mtpsurl: https://msdn.microsoft.com/library/microsoft.isam.esent.interop.api.retrievecolumnasint64(v=EXCHG.10)
ms:contentKeyID: 55100858
ms.date: 07/30/2014
ms.topic: reference
dev_langs:
- vb
- csharp
api_name: 
- Microsoft.Isam.Esent.Interop.Api.RetrieveColumnAsInt64
topic_type: 
- apiref
- kbSyntax
api_type: 
- Managed
api_location: 
- Microsoft.Isam.Esent.Interop.dll
ROBOTS: INDEX,FOLLOW

---

# Api.RetrieveColumnAsInt64 method (JET_SESID, JET_TABLEID, JET_COLUMNID)

Retrieves a single column value from the current record. The record is that record associated with the index entry at the current position of the cursor.

**Namespace:**  [Microsoft.Isam.Esent.Interop](./microsoft.isam.esent.interop-namespace.md)  
**Assembly:**  Microsoft.Isam.Esent.Interop (in Microsoft.Isam.Esent.Interop.dll)

## Syntax

``` vb
'Declaration
Public Shared Function RetrieveColumnAsInt64 ( _
    sesid As JET_SESID, _
    tableid As JET_TABLEID, _
    columnid As JET_COLUMNID _
) As Nullable(Of Long)
'Usage
Dim sesid As JET_SESID
Dim tableid As JET_TABLEID
Dim columnid As JET_COLUMNID
Dim returnValue As Nullable(Of Long)

returnValue = Api.RetrieveColumnAsInt64(sesid, _
    tableid, columnid)
```

``` csharp
public static Nullable<long> RetrieveColumnAsInt64(
    JET_SESID sesid,
    JET_TABLEID tableid,
    JET_COLUMNID columnid
)
```

#### Parameters

  - sesid  
    Type: [Microsoft.Isam.Esent.Interop.JET_SESID](./jet-sesid-structure.md)  
    
    The session to use.

<!-- end list -->

  - tableid  
    Type: [Microsoft.Isam.Esent.Interop.JET_TABLEID](./jet-tableid-structure.md)  
    
    The cursor to retrieve the column from.

<!-- end list -->

  - columnid  
    Type: [Microsoft.Isam.Esent.Interop.JET_COLUMNID](./jet-columnid-structure.md)  
    
    The columnid to retrieve.

#### Return value

Type: [System.Nullable](/dotnet/api/system.nullable-1)\<[Int64](/dotnet/api/system.int64)\>  
The data retrieved from the column as a long. Null if the column is null.  

## See also

#### Reference

[Api class](./api-class.md)

[Api members](./api-members.md)

[RetrieveColumnAsInt64 overload](./api.retrievecolumnasint64-method.md)

[Microsoft.Isam.Esent.Interop namespace](./microsoft.isam.esent.interop-namespace.md)
