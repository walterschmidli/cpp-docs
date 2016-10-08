---
title: "Managing Menus, Control Bars, and Accelerators"
ms.custom: na
ms.date: 10/03/2016
ms.devlang: 
  - C++
ms.prod: visual-studio-dev14
ms.reviewer: na
ms.suite: na
ms.technology: 
  - devlang-cpp
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 97ca1997-06df-4373-b023-4f7ecd81047b
caps.latest.revision: 7
manager: ghogen
translation.priority.ht: 
  - cs-cz
  - de-de
  - es-es
  - fr-fr
  - it-it
  - ja-jp
  - ko-kr
  - pl-pl
  - pt-br
  - ru-ru
  - tr-tr
  - zh-cn
  - zh-tw
---
# Managing Menus, Control Bars, and Accelerators
The frame window manages updating user-interface objects, including menus, toolbar buttons, the status bar, and accelerators. It also manages sharing the menu bar in MDI applications.  
  
## Managing Menus  
 The frame window participates in updating user-interface items using the `ON_UPDATE_COMMAND_UI` mechanism described in [How to Update User-Interface Objects](../VS_visualcpp/How-to--Update-User-Interface-Objects.md). Buttons on toolbars and other control bars are updated during the idle loop. Menu items in drop-down menus on the menu bar are updated just before the menu drops down.  
  
 For MDI applications, the MDI frame window manages the menu bar and caption. An MDI frame window owns one default menu that is used as the menu bar when there are no active MDI child windows. When there are active children, the MDI frame window's menu bar is taken over by the menu for the active MDI child window. If an MDI application supports multiple document types, such as chart and worksheet documents, each type puts its own menus into the menu bar and changes the main frame window's caption.  
  
 [CMDIFrameWnd](../VS_visualcpp/CMDIFrameWnd-Class.md) provides default implementations for the standard commands on the Window menu that appears for MDI applications. In particular, the New Window command (**ID_WINDOW_NEW**) is implemented to create a new frame window and view on the current document. You need to override these implementations only if you need advanced customization.  
  
 Multiple MDI child windows of the same document type share menu resources. If several MDI child windows are created by the same document template, they can all use the same menu resource, saving on system resources in Windows.  
  
## Managing the Status Bar  
 The frame window also positions the status bar within its client area and manages the status bar's indicators. The frame window clears and updates the message area in the status bar as needed and displays prompt strings as the user selects menu items or toolbar buttons, as described in [How to Display Command Information in the Status Bar](../VS_visualcpp/How-to--Display-Command-Information-in-the-Status-Bar.md).  
  
## Managing Accelerators  
 Each frame window maintains an optional accelerator table that does keyboard accelerator translation for you automatically. This mechanism makes it easy to define accelerator keys (also called shortcut keys) that invoke menu commands.  
  
## See Also  
 [Using Frame Windows](../VS_visualcpp/Using-Frame-Windows.md)