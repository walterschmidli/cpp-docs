---
title: "Filename Macros"
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
ms.assetid: 20afd6b3-5b6c-4e33-9d01-309ce98ef9db
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
# Filename Macros
Filename macros are predefined as filenames specified in the dependency (not full filename specifications on disk). These macros do not need to be enclosed in parentheses when invoked; specify only a $ as shown.  
  
|Macro|Meaning|  
|-----------|-------------|  
|**$@**|Current target's full name (path, base name, extension), as currently specified.|  
|**$$@**|Current target's full name (path, base name, extension), as currently specified. Valid only as a dependent in a dependency.|  
|**$\***|Current target's path and base name minus file extension.|  
|**$\*\***|All dependents of the current target.|  
|**$?**|All dependents with a later timestamp than the current target.|  
|**$<**|Dependent file with a later timestamp than the current target. Valid only in commands in inference rules.|  
  
 To specify part of a predefined filename macro, append a macro modifier and enclose the modified macro in parentheses.  
  
|Modifier|Resulting filename part|  
|--------------|-----------------------------|  
|**D**|Drive plus directory|  
|**B**|Base name|  
|**F**|Base name plus extension|  
|**R**|Drive plus directory plus base name|  
  
## See Also  
 [Special NMAKE Macros](../VS_visualcpp/Special-NMAKE-Macros.md)