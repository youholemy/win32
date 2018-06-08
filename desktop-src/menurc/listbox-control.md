---
title: LISTBOX control
description: Defines commonly used controls for a dialog box or window. The control is a rectangle containing a list of strings (such as filenames) from which the user can select.
ms.assetid: 78f6d36e-5079-4f04-87e4-ca55a1161a51
keywords:
- LISTBOX control Menus and Other Resources
topic_type:
- apiref
api_name:
- LISTBOX
api_type:
- NA
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# LISTBOX control

Defines commonly used controls for a dialog box or window. The control is a rectangle containing a list of strings (such as filenames) from which the user can select.

The **LISTBOX** statement, which can only be used in a [**DIALOGEX**](dialogex-resource.md) or **WINDOW** statement, defines the identifier, dimensions, and attributes of a control window.

``` syntax
LISTBOX id, x, y, width, height [, style [, extended-style]]
```

<dl> <dt>

<span id="style"></span><span id="STYLE"></span>*style*
</dt> <dd>

Control styles. This value can be a combination of the list-box class styles and any of the following styles: **WS\_BORDER** and **WS\_VSCROLL**.

If you do not specify a style, the default style is `LBS_NOTIFY | WS_BORDER`.

</dd> </dl>

For more information about the general syntax of a control statement, see [Common Control Parameters](common-control-parameters.md).

## Examples

This example defines a list-box control whose identifier is 101:

``` syntax
LISTBOX 101, 10, 10, 100, 100
```

## See also

<dl> <dt>

[**COMBOBOX**](combobox-control.md)
</dt> <dt>

[List Boxes](359bb363-5b97-4e0c-bdc4-bfa6a6504a76)
</dt> </dl>

 

 



