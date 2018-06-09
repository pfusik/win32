---
title: STYLE statement
description: Defines the window style of the dialog box. The window style specifies whether the box is a pop-up or a child window.
ms.assetid: 5dc74bab-e385-457c-80c4-5e04eed589b5
keywords:
- STYLE statement Menus and Other Resources
topic_type:
- apiref
api_name:
- STYLE
api_type:
- NA
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# STYLE statement

Defines the window style of the dialog box. The window style specifies whether the box is a pop-up or a child window.

``` syntax
STYLE style
```

<dl> <dt>

<span id="style"></span><span id="STYLE"></span>*style*
</dt> <dd>

The window style. This parameter can be an integer value or a combination of window style values (such as **WS\_CAPTION** and **WS\_SYSMENU**) and dialog box style values (such as **DS\_CENTER**).

</dd> </dl>

For a list of window styles, see [Window Styles](https://msdn.microsoft.com/library/windows/desktop/ms632600). For a list of dialog box styles, see [Dialog Box Template Styles](https://msdn.microsoft.com/windows/desktop/51960c28-a178-4ad3-b45e-426fec42a945). If you use the window or dialog box style values, you must include Windows.h.

 

 



