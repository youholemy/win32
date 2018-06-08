---
Description: Returns the number of animation sets currently registered in the animation controller.
ms.assetid: 1aacc84d-5025-4601-9a6c-84b3d9b06012
title: ID3DXAnimationController::GetNumAnimationSets method
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# ID3DXAnimationController::GetNumAnimationSets method

Returns the number of animation sets currently registered in the animation controller.

## Syntax


```C++
UINT GetNumAnimationSets();
```



## Parameters

This method has no parameters.

## Return value

Type: **[**UINT**](https://msdn.microsoft.com/4553cafc-450e-4493-a4d4-cb6e2f274d46)**

Number of animation sets.

## Remarks

The controller contains any number of animations sets and tracks. Animation sets can be registered with [**RegisterAnimationOutput**](id3dxanimationcontroller--registeranimationoutput.md). An animation controller created by a call to [**D3DXLoadMeshHierarchyFromX**](d3dxloadmeshhierarchyfromx.md) will automatically register loaded animation sets.

## Requirements



|                    |                                                                                        |
|--------------------|----------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>D3dx9anim.h</dt> </dl> |
| Library<br/> | <dl> <dt>D3dx9.lib</dt> </dl>   |



## See also

<dl> <dt>

[ID3DXAnimationController](id3dxanimationcontroller.md)
</dt> </dl>

 

 



