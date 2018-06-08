---
title: UInt8Type Simple Type
description: Defines an unsigned byte type.
ms.assetid: bda12d06-683f-4183-a84b-2bc3159c4eff
keywords:
- UInt8Type simple type EventLog
topic_type:
- apiref
api_name:
- UInt8Type
api_type:
- Schema
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# UInt8Type Simple Type

Defines an unsigned byte type. The value can be specified as a 1-byte integer or hexadecimal value in the range from 0 through 255.

``` syntax
<xs:simpleType name="UInt8Type">
    <xs:union
        memberValues="unsignedByte HexInt8Type"
     />
</xs:simpleType>
```

## Requirements



|                                     |                                                      |
|-------------------------------------|------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista \[desktop apps only\]<br/>       |
| Minimum supported server<br/> | Windows Server 2008 \[desktop apps only\]<br/> |



 

 




