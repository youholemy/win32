---
Description: Contains format information for smart recompression.
ms.assetid: 471a7b4a-e639-443b-a30e-870b747e072c
title: SCompFmt0 structure
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: structure
ms.date: 05/31/2018
---

# SCompFmt0 structure

> [!Note]  
> \[Deprecated. This API may be removed from future releases of Windows.\]

 

Contains format information for smart recompression.

## Syntax


```C++
typedef struct _SCompFmt0 {
  long          nFormatId;
  AM_MEDIA_TYPE MediaType;
} SCompFmt0;
```



## Members

<dl> <dt>

**nFormatId**
</dt> <dd>

Reserved; must be zero.

</dd> <dt>

**MediaType**
</dt> <dd>

[**AM\_MEDIA\_TYPE**](/windows/desktop/api/strmif/ns-strmif-_ammediatype) structure that describes the compression format.

</dd> </dl>

## Requirements



|                   |                                                                                    |
|-------------------|------------------------------------------------------------------------------------|
| Header<br/> | <dl> <dt>Qedit.h</dt> </dl> |



## See also

<dl> <dt>

[**IAMTimelineGroup::GetSmartRecompressFormat**](iamtimelinegroup-getsmartrecompressformat.md)
</dt> <dt>

[**IAMTimelineGroup::SetSmartRecompressFormat**](iamtimelinegroup-setsmartrecompressformat.md)
</dt> </dl>

 

 



