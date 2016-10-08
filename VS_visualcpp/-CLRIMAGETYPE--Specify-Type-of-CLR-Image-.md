---
title: "-CLRIMAGETYPE (Specify Type of CLR Image)"
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
H1: /CLRIMAGETYPE (Specify Type of CLR Image)
ms.assetid: 04c60ee6-9dd7-4391-bc03-6926ad0fa116
caps.latest.revision: 14
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
# -CLRIMAGETYPE (Specify Type of CLR Image)
```  
/CLRIMAGETYPE:{IJW|PURE|SAFE|SAFE32BITPREFERRED}  
```  
  
## Remarks  
 The linker accepts native objects and also MSIL objects that are compiled by using [/clr](../VS_visualcpp/-clr--Common-Language-Runtime-Compilation-.md), /clr:pure, or /clr:safe. When mixed objects in the same build are passed, the verifiability of the resulting output file is, by default, equal to the lowest level of verifiability of the input modules. For example, if you pass both a safe and a pure module to the linker, the output file will be pure. If you pass a native image and a mixed mode image (compiled by using **/clr**), the resulting image will be a mixed mode image.  
  
 You can use /CLRIMAGETYPE to specify a lower level of verifiability, if that is what you need.  
  
 In .NET 4.5, /CLRIMAGETYPE supports a SAFE32BITPREFERRED option. This sets—in the PE header of the image—flags that indicate that the MSIL objects are safe and can be run on all platforms, but that 32-bit execution environments are preferred. This option enables an app to run on ARM platforms and also specifies that it should run under WOW64 on 64-bit operating systems instead of using the 64-bit execution environment.  
  
 When an .exe that was compiled by using **/clr** or **/clr:pure** is run on a 64-bit operating system, the application is run under WOW64, which enables a 32-bit application to run on a 64-bit operating system. By default, an .exe that's compiled by using **/clr:safe** is run under the operating system's 64-bit support. However, it is possible that your safe application loads a 32-bit component. In that case, a safe image running under the operating system's 64-bit support will fail when it loads the 32-bit application. To ensure that a safe image continues to run when it loads a 32-bit component on a 64-bit operating system, use the /CLRIMAGETYPE:SAFE32BITPREFERRED option. If your code does not have to run on ARM platforms, you can specify the /CLRIMAGETYPE:PURE option to change the metadata (.corflags), marking it to be run under WOW64 (and substituting your own entry symbol):  
  
 **cl /clr:safe t.cpp /link /clrimagetype:pure /entry:?main@@$$HYMHXZ /subsystem:console**  
  
 For information about how to determine the CLR image type of a file, see [/CLRHEADER](../VS_visualcpp/-CLRHEADER.md).  
  
### To set this linker option in the Visual Studio development environment  
  
1.  Open the project's **Property Pages** dialog box. For details, see [How to: Open Project Property Pages](../Topic/How%20to:%20Open%20Project%20Property%20Pages.md).  
  
2.  Expand the **Configuration Properties** node.  
  
3.  Expand the **Linker** node.  
  
4.  Select the **Advanced** property page.  
  
5.  Modify the **CLR Image Type** property.  
  
### To set this linker option programmatically  
  
1.  See <xref:Microsoft.VisualStudio.VCProjectEngine.VCLinkerTool.CLRImageType?qualifyHint=False>.  
  
## See Also  
 [Setting Linker Options](../VS_visualcpp/Setting-Linker-Options.md)   
 [Linker Options](../VS_visualcpp/Linker-Options.md)