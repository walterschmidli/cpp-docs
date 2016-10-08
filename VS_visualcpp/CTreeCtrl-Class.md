---
title: "CTreeCtrl Class"
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
ms.topic: reference
ms.assetid: 96e20031-6161-4143-8c12-8d1816c66d90
caps.latest.revision: 19
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
# CTreeCtrl Class
Provides the functionality of the Windows common tree view control.  
  
## Syntax  
  
```  
class CTreeCtrl : public CWnd  
```  
  
## Members  
  
### Public Constructors  
  
|Name|Description|  
|----------|-----------------|  
|[CTreeCtrl::CTreeCtrl](#ctreectrl__ctreectrl)|Constructs a `CTreeCtrl` object.|  
  
### Public Methods  
  
|Name|Description|  
|----------|-----------------|  
|[CTreeCtrl::Create](#ctreectrl__create)|Creates a tree view control and attaches it to a `CTreeCtrl` object.|  
|[CTreeCtrl::CreateDragImage](#ctreectrl__createdragimage)|Creates a dragging bitmap for the specified tree view item.|  
|[CTreeCtrl::CreateEx](#ctreectrl__createex)|Creates a tree control with the specified Windows extended styles and attaches it to a `CTreeCtrl` object.|  
|[CTreeCtrl::DeleteAllItems](#ctreectrl__deleteallitems)|Deletes all items in a tree view control.|  
|[CTreeCtrl::DeleteItem](#ctreectrl__deleteitem)|Deletes a new item in a tree view control.|  
|[CTreeCtrl::EditLabel](#ctreectrl__editlabel)|Edits a specified tree view item in-place.|  
|[CTreeCtrl::EndEditLabelNow](#ctreectrl__endeditlabelnow)|Cancels the edit operation on the label of a tree-view item in the current tree-view control.|  
|[CTreeCtrl::EnsureVisible](#ctreectrl__ensurevisible)|Ensures that a tree view item is visible in its tree view control.|  
|[CTreeCtrl::Expand](#ctreectrl__expand)|Expands, or collapses, the child items of the specified tree view item.|  
|[CTreeCtrl::GetBkColor](#ctreectrl__getbkcolor)|Retrieves the current background color of the control.|  
|[CTreeCtrl::GetCheck](#ctreectrl__getcheck)|Retrieves the check state of a tree control item.|  
|[CTreeCtrl::GetChildItem](#ctreectrl__getchilditem)|Retrieves the child of a specified tree view item.|  
|[CTreeCtrl::GetCount](#ctreectrl__getcount)|Retrieves the number of tree items associated with a tree view control.|  
|[CTreeCtrl::GetDropHilightItem](#ctreectrl__getdrophilightitem)|Retrieves the target of a drag-and-drop operation.|  
|[CTreeCtrl::GetEditControl](#ctreectrl__geteditcontrol)|Retrieves the handle of the edit control used to edit the specified tree view item.|  
|[CTreeCtrl::GetExtendedStyle](#ctreectrl__getextendedstyle)|Retrieves the extended styles that the current tree-view control is using.|  
|[CTreeCtrl::GetFirstVisibleItem](#ctreectrl__getfirstvisibleitem)|Retrieves the first visible item of the specified tree view item.|  
|[CTreeCtrl::GetImageList](#ctreectrl__getimagelist)|Retrieves the handle of the image list associated with a tree view control.|  
|[CTreeCtrl::GetIndent](#ctreectrl__getindent)|Retrieves the offset (in pixels) of a tree view item from its parent.|  
|[CTreeCtrl::GetInsertMarkColor](#ctreectrl__getinsertmarkcolor)|Retrieves the color used to draw the insertion mark for the tree view.|  
|[CTreeCtrl::GetItem](#ctreectrl__getitem)|Retrieves the attributes of a specified tree view item.|  
|[CTreeCtrl::GetItemData](#ctreectrl__getitemdata)|Returns the 32-bit application-specific value associated with an item.|  
|[CTreeCtrl::GetItemExpandedImageIndex](#ctreectrl__getitemexpandedimageindex)|Retrieves the index of the image to display when the specified item of the current tree-view control is in the expanded state.|  
|[CTreeCtrl::GetItemHeight](#ctreectrl__getitemheight)|Retrieves the current height of the tree view items.|  
|[CTreeCtrl::GetItemImage](#ctreectrl__getitemimage)|Retrieves the images associated with an item.|  
|[CTreeCtrl::GetItemPartRect](#ctreectrl__getitempartrect)|Retrieves the bounding rectangle for a specified part of a specified item in the current tree-view control.|  
|[CTreeCtrl::GetItemRect](#ctreectrl__getitemrect)|Retrieves the bounding rectangle of a tree view item.|  
|[CTreeCtrl::GetItemState](#ctreectrl__getitemstate)|Returns the state of an item.|  
|[CTreeCtrl::GetItemStateEx](#ctreectrl__getitemstateex)|Retrieves the extended state of the specified item in the current tree-view control.|  
|[CTreeCtrl::GetItemText](#ctreectrl__getitemtext)|Returns the text of an item.|  
|[CTreeCtrl::GetLastVisibleItem](#ctreectrl__getlastvisibleitem)|Retrieves the last expanded item in the current tree-view control.|  
|[CTreeCtrl::GetLineColor](#ctreectrl__getlinecolor)|Retrieves the current line color for the tree view control.|  
|[CTreeCtrl::GetNextItem](#ctreectrl__getnextitem)|Retrieves the next tree view item that matches a specified relationship.|  
|[CTreeCtrl::GetNextSiblingItem](#ctreectrl__getnextsiblingitem)|Retrieves the next sibling of the specified tree view item.|  
|[CTreeCtrl::GetNextVisibleItem](#ctreectrl__getnextvisibleitem)|Retrieves the next visible item of the specified tree view item.|  
|[CTreeCtrl::GetParentItem](#ctreectrl__getparentitem)|Retrieves the parent of the specified tree view item.|  
|[CTreeCtrl::GetPrevSiblingItem](#ctreectrl__getprevsiblingitem)|Retrieves the previous sibling of the specified tree view item.|  
|[CTreeCtrl::GetPrevVisibleItem](#ctreectrl__getprevvisibleitem)|Retrieves the previous visible item of the specified tree view item.|  
|[CTreeCtrl::GetRootItem](#ctreectrl__getrootitem)|Retrieves the root of the specified tree view item.|  
|[CTreeCtrl::GetScrollTime](#ctreectrl__getscrolltime)|Retrieves the maximum scroll time for the tree view control.|  
|[CTreeCtrl::GetSelectedCount](#ctreectrl__getselectedcount)|Retrieves the number of selected items in the current tree-view control.|  
|[CTreeCtrl::GetSelectedItem](#ctreectrl__getselecteditem)|Retrieves the currently selected tree view item.|  
|[CTreeCtrl::GetTextColor](#ctreectrl__gettextcolor)|Retrieves the current text color of the control.|  
|[CTreeCtrl::GetToolTips](#ctreectrl__gettooltips)|Retrieves the handle to the child ToolTip control used by a tree view control.|  
|[CTreeCtrl::GetVisibleCount](#ctreectrl__getvisiblecount)|Retrieves the number of visible tree items associated with a tree view control.|  
|[CTreeCtrl::HitTest](#ctreectrl__hittest)|Returns the current position of the cursor related to the `CTreeCtrl` object.|  
|[CTreeCtrl::InsertItem](#ctreectrl__insertitem)|Inserts a new item in a tree view control.|  
|[CTreeCtrl::ItemHasChildren](#ctreectrl__itemhaschildren)|Returns nonzero if the specified item has child items.|  
|[CTreeCtrl::MapAccIdToItem](#ctreectrl__mapaccidtoitem)|Maps the specified accessibility identifier to the handle to a tree-view item in the current tree-view control.|  
|[CTreeCtrl::MapItemToAccID](#ctreectrl__mapitemtoaccid)|Maps the specified handle to a tree-view item in the current tree-view control to an accessibility identifier.|  
|[CTreeCtrl::Select](#ctreectrl__select)|Selects, scrolls into view, or redraws a specified tree view item.|  
|[CTreeCtrl::SelectDropTarget](#ctreectrl__selectdroptarget)|Redraws the tree item as the target of a drag-and-drop operation.|  
|[CTreeCtrl::SelectItem](#ctreectrl__selectitem)|Selects a specified tree view item.|  
|[CTreeCtrl::SelectSetFirstVisible](#ctreectrl__selectsetfirstvisible)|Selects a specified tree view item as the first visible item.|  
|[CTreeCtrl::SetAutoscrollInfo](#ctreectrl__setautoscrollinfo)|Sets the autoscroll rate of the current tree-view control.|  
|[CTreeCtrl::SetBkColor](#ctreectrl__setbkcolor)|Sets the background color of the control.|  
|[CTreeCtrl::SetCheck](#ctreectrl__setcheck)|Sets the check state of a tree control item.|  
|[CTreeCtrl::SetExtendedStyle](#ctreectrl__setextendedstyle)|Sets the extended styles for the current tree-view control.|  
|[CTreeCtrl::SetImageList](#ctreectrl__setimagelist)|Sets the handle of the image list associated with a tree view control.|  
|[CTreeCtrl::SetIndent](#ctreectrl__setindent)|Sets the offset (in pixels) of a tree view item from its parent.|  
|[CTreeCtrl::SetInsertMark](#ctreectrl__setinsertmark)|Sets the insertion mark in a tree view control.|  
|[CTreeCtrl::SetInsertMarkColor](#ctreectrl__setinsertmarkcolor)|Sets the color used to draw the insertion mark for the tree view.|  
|[CTreeCtrl::SetItem](#ctreectrl__setitem)|Sets the attributes of a specified tree view item.|  
|[CTreeCtrl::SetItemData](#ctreectrl__setitemdata)|Sets the 32-bit application-specific value associated with an item.|  
|[CTreeCtrl::SetItemExpandedImageIndex](#ctreectrl__setitemexpandedimageindex)|Sets the index of the image to display when the specified item of the current tree-view control is in the expanded state.|  
|[CTreeCtrl::SetItemHeight](#ctreectrl__setitemheight)|Sets the height of the tree view items.|  
|[CTreeCtrl::SetItemImage](#ctreectrl__setitemimage)|Associates images with an item.|  
|[CTreeCtrl::SetItemState](#ctreectrl__setitemstate)|Sets the state of an item.|  
|[CTreeCtrl::SetItemStateEx](#ctreectrl__setitemstateex)|Sets the extended state of the specified item in the current tree-view control.|  
|[CTreeCtrl::SetItemText](#ctreectrl__setitemtext)|Sets the text of an item.|  
|[CTreeCtrl::SetLineColor](#ctreectrl__setlinecolor)|Sets the current line color for the tree view control.|  
|[CTreeCtrl::SetScrollTime](#ctreectrl__setscrolltime)|Sets the maximum scroll time for the tree view control.|  
|[CTreeCtrl::SetTextColor](#ctreectrl__settextcolor)|Sets the text color of the control.|  
|[CTreeCtrl::SetToolTips](#ctreectrl__settooltips)|Sets a tree view control's child ToolTip control.|  
|[CTreeCtrl::ShowInfoTip](#ctreectrl__showinfotip)|Displays the infotip for the specified item in the current tree-view control.|  
|[CTreeCtrl::SortChildren](#ctreectrl__sortchildren)|Sorts the children of a given parent item.|  
|[CTreeCtrl::SortChildrenCB](#ctreectrl__sortchildrencb)|Sorts the children of a given parent item using an application-defined sort function.|  
  
## Remarks  
 A "tree view control" is a window that displays a hierarchical list of items, such as the headings in a document, the entries in an index, or the files and directories on a disk. Each item consists of a label and an optional bitmapped image, and each item can have a list of subitems associated with it. By clicking an item, the user can expand and collapse the associated list of subitems.  
  
 This control (and therefore the `CTreeCtrl` class) is available only to programs running under Windows 98 and Windows NT version 4 and later.  
  
 For more information on using `CTreeCtrl`, see:  
  
-   [Controls](../VS_visualcpp/Controls--MFC-.md)  
  
-   [Using CTreeCtrl](../VS_visualcpp/Using-CTreeCtrl.md)  
  
-   [Tree View Control Reference](http://msdn.microsoft.com/library/windows/desktop/bb759988) in the Windows SDK.  
  
-   Knowledge Base article Q222905: HOWTO: Display a Context Menu for CTreeCtrl  
  
## Inheritance Hierarchy  
 [CObject](../VS_visualcpp/CObject-Class.md)  
  
 [CCmdTarget](../VS_visualcpp/CCmdTarget-Class.md)  
  
 [CWnd](../VS_visualcpp/CWnd-Class.md)  
  
 `CTreeCtrl`  
  
## Requirements  
 **Header:** afxcmn.h  
  
##  <a name="ctreectrl__create"></a>  CTreeCtrl::Create  
 If you specify the tree control in a dialog box template, or if you are using [CTreeView](../VS_visualcpp/CTreeView-Class.md), your tree control is created automatically when the dialog box or view is created.  
  
```  
virtual BOOL Create(  
    DWORD dwStyle,  
    const RECT& rect,  
    CWnd* pParentWnd,  
    UINT nID );  
```  
  
### Parameters  
 `dwStyle`  
 Specifies the tree view control's style. Apply window styles, described in                                 [CreateWindow](http://msdn.microsoft.com/library/windows/desktop/ms632679), and any combination of                                 [tree view control styles](http://msdn.microsoft.com/library/windows/desktop/bb760013) as described in the Windows SDK.  
  
 `rect`  
 Specifies the tree view control's size and position. It can be either a [CRect](../VS_visualcpp/CRect-Class.md) object or a                                 [RECT](http://msdn.microsoft.com/library/windows/desktop/dd162897) structure.  
  
 `pParentWnd`  
 Specifies the tree view control's parent window, usually a `CDialog`. It must not be **NULL**.  
  
 `nID`  
 Specifies the tree view control's ID.  
  
### Return Value  
 Nonzero if initialization was successful; otherwise 0.  
  
### Remarks  
 If you want to create the tree control as a child window of some other window, use the **Create** member function. If you create the tree control using **Create**, you must pass it **WS_VISIBLE**, in addition to other tree view styles.  
  
 You construct a `CTreeCtrl` in two steps. First call the constructor, then call **Create**, which creates the tree view control and attaches it to the `CTreeCtrl` object.  
  
 To create a tree control with extended window styles, call [CreateEx](#ctreectrl__createex) instead of **Create**.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#1](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#1)]  
  
##  <a name="ctreectrl__createex"></a>  CTreeCtrl::CreateEx  
 Call this function to create a control (a child window) and associate it with the `CTreeCtrl` object.  
  
```  
virtual BOOL CreateEx(  
    DWORD dwExStyle,  
    DWORD dwStyle,  
    const RECT& rect,  
    CWnd* pParentWnd,  
    UINT nID );  
```  
  
### Parameters  
 `dwExStyle`  
 Specifies the extended style of the control being created. For a list of extended Windows styles, see the `dwExStyle` parameter for                                 [CreateWindowEx](http://msdn.microsoft.com/library/windows/desktop/ms632680) in the Windows SDK.  
  
 `dwStyle`  
 Specifies the tree view control's style. Apply window styles, described in                                 [CreateWindow](http://msdn.microsoft.com/library/windows/desktop/ms632679), and any combination of                                 [tree view control styles](http://msdn.microsoft.com/library/windows/desktop/bb760013) as described in the Windows SDK.  
  
 `rect`  
 A reference to a                                 [RECT](http://msdn.microsoft.com/library/windows/desktop/dd162897) structure describing the size and position of the window to be created, in client coordinates of `pParentWnd`.  
  
 `pParentWnd`  
 A pointer to the window that is the control's parent.  
  
 `nID`  
 The control's child-window ID.  
  
### Return Value  
 Nonzero if successful otherwise 0.  
  
### Remarks  
 Use `CreateEx` instead of [Create](#ctreectrl__create) to apply extended Windows styles, specified by the Windows extended style preface **WS_EX_**.  
  
##  <a name="ctreectrl__createdragimage"></a>  CTreeCtrl::CreateDragImage  
 Call this function to create a dragging bitmap for the given item in a tree view control, create an image list for the bitmap, and add the bitmap to the image list.  
  
```  
CImageList* CreateDragImage( HTREEITEM hItem );  
```  
  
### Parameters  
 `hItem`  
 Handle of the tree item to be dragged.  
  
### Return Value  
 Pointer to the image list to which the dragging bitmap was added, if successful; otherwise **NULL**.  
  
### Remarks  
 An application uses the image-list functions to display the image when the item is being dragged.  
  
 The `CImageList` object is permanent, and you must delete it when finished. For example:  
  
 [!CODE [NVC_MFC_CTreeCtrl#2](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#2)]  
  
##  <a name="ctreectrl__ctreectrl"></a>  CTreeCtrl::CTreeCtrl  
 Constructs a `CTreeCtrl` object.  
  
```  
CTreeCtrl();  
```  
  
##  <a name="ctreectrl__deleteallitems"></a>  CTreeCtrl::DeleteAllItems  
 Call this function to delete all items from the tree view control.  
  
```  
BOOL DeleteAllItems();  
```  
  
### Return Value  
 Nonzero if successful; otherwise 0.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#3](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#3)]  
  
##  <a name="ctreectrl__deleteitem"></a>  CTreeCtrl::DeleteItem  
 Call this function to delete an item from the tree view control.  
  
```  
BOOL DeleteItem( HTREEITEM hItem );  
```  
  
### Parameters  
 `hItem`  
 Handle of the tree item to be deleted. If                                 *hitem* has the **TVI_ROOT** value, all items are deleted from the tree view control.  
  
### Return Value  
 Nonzero if successful; otherwise 0.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#4](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#4)]  
  
##  <a name="ctreectrl__editlabel"></a>  CTreeCtrl::EditLabel  
 Call this function to begin in-place editing of the specified item's text.  
  
```  
CEdit* EditLabel( HTREEITEM hItem );  
```  
  
### Parameters  
 `hItem`  
 Handle of the tree item to be edited.  
  
### Return Value  
 If successful, a pointer to the `CEdit` object that is used to edit the item text; otherwise **NULL**.  
  
### Remarks  
 The editing is accomplished by replacing the text of the item with a single-line edit control containing the text.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#5](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#5)]  
  
##  <a name="ctreectrl__endeditlabelnow"></a>  CTreeCtrl::EndEditLabelNow  
 Concludes the edit operation on the label of a tree-view item in the current tree-view control.  
  
```  
BOOL EndEditLabelNow( BOOL fCancelWithoutSave );  
```  
  
### Parameters  
  
|Parameter|Description|  
|---------------|-----------------|  
|[in] `fCancelWithoutSave`|`true` to discard changes to the tree-view item before concluding the edit operation, or `false` to save changes to the tree-view item before concluding the operation.|  
  
### Return Value  
 `true` if this method is successful; otherwise, `false`.  
  
### Remarks  
 This method sends the                         [TVM_ENDEDITLABELNOW](http://msdn.microsoft.com/library/windows/desktop/bb773564) message, which is described in the Windows SDK.  
  
##  <a name="ctreectrl__ensurevisible"></a>  CTreeCtrl::EnsureVisible  
 Call this function to ensure that a tree view item is visible.  
  
```  
BOOL EnsureVisible( HTREEITEM hItem );  
```  
  
### Parameters  
 `hItem`  
 Handle of the tree item being made visible.  
  
### Return Value  
 Returns **TRUE** if the system scrolled the items in the tree-view control to ensure that the specified item is visible. Otherwise, the return value is **FALSE**.  
  
### Remarks  
 If necessary, the function expands the parent item or scrolls the tree view control so that the item is visible.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#6](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#6)]  
  
##  <a name="ctreectrl__expand"></a>  CTreeCtrl::Expand  
 Call this function to expand or collapse the list of child items, if any, associated with the given parent item.  
  
```  
BOOL Expand(  
    HTREEITEM hItem,  
    UINT nCode );  
```  
  
### Parameters  
 `hItem`  
 Handle of the tree item being expanded.  
  
 `nCode`  
 A flag indicating the type of action to be taken. This flag can have one of the following values:  
  
-   `TVE_COLLAPSE` Collapses the list.  
  
-   `TVE_COLLAPSERESET` Collapses the list and removes the child items. The **TVIS_EXPANDEDONCE** state flag is reset. This flag must be used with the `TVE_COLLAPSE` flag.  
  
-   `TVE_EXPAND` Expands the list.  
  
-   `TVE_TOGGLE` Collapses the list if it is currently expanded or expands it if it is currently collapsed.  
  
### Return Value  
 Nonzero if successful; otherwise 0.  
  
### Example  
  See the example for [CTreeCtrl::EnsureVisible](#ctreectrl__ensurevisible).  
  
##  <a name="ctreectrl__getbkcolor"></a>  CTreeCtrl::GetBkColor  
 This member function implements the behavior of the Win32 message                 [TVM_GETBKCOLOR](http://msdn.microsoft.com/library/windows/desktop/bb773570), as described in the Windows SDK.  
  
```  
COLORREF GetBkColor() const;  
```  
  
### Return Value  
 A **COLORREF** value that represents the current window background color for the control. If this value is -1, the control is using the system window color. In this case, you can use `::GetSysColor(COLOR_WINDOW)` to get the current system color that the control is using.  
  
### Example  
  See the example for [CTreeCtrl::SetTextColor](#ctreectrl__settextcolor).  
  
##  <a name="ctreectrl__getcheck"></a>  CTreeCtrl::GetCheck  
 Call this member function to retrieve an item's check state.  
  
```  
BOOL GetCheck( HTREEITEM hItem ) const;  
```  
  
### Parameters  
 `hItem`  
 The **HTREEITEM** about which to receive the state information.  
  
### Return Value  
 Nonzero if the tree control item is checked; otherwise 0.  
  
### Example  
  See the example for [CTreeCtrl::SetCheck](#ctreectrl__setcheck).  
  
##  <a name="ctreectrl__getchilditem"></a>  CTreeCtrl::GetChildItem  
 Call this function to retrieve the tree view item that is the child of the item specified by `hItem`.  
  
```  
HTREEITEM GetChildItem( HTREEITEM hItem ) const;  
```  
  
### Parameters  
 `hItem`  
 Handle of a tree item.  
  
### Return Value  
 The handle of the child item if successful; otherwise **NULL**.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#7](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#7)]  
  
##  <a name="ctreectrl__getcount"></a>  CTreeCtrl::GetCount  
 Call this function to retrieve a count of the items in a tree view control.  
  
```  
UINT GetCount() const;  
```  
  
### Return Value  
 The number of items in the tree view control.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#8](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#8)]  
  
##  <a name="ctreectrl__getdrophilightitem"></a>  CTreeCtrl::GetDropHilightItem  
 Call this function to retrieve the item that is the target of a drag-and-drop operation.  
  
```  
HTREEITEM GetDropHilightItem() const;  
```  
  
### Return Value  
 The handle of the item dropped if successful; otherwise **NULL**.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#9](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#9)]  
  
##  <a name="ctreectrl__geteditcontrol"></a>  CTreeCtrl::GetEditControl  
 Call this function to retrieve the handle of the edit control being used to edit a tree view item's text.  
  
```  
CEdit* GetEditControl() const;  
```  
  
### Return Value  
 A pointer to the edit control used to edit the item text, if successful; otherwise **NULL**.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#10](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#10)]  
  
##  <a name="ctreectrl__getextendedstyle"></a>  CTreeCtrl::GetExtendedStyle  
 Retrieves the extended styles that the current tree-view control is using.  
  
```  
DWORD GetExtendedStyle() const;  
```  
  
### Return Value  
 A value that contains a bitwise combination (OR) of the current tree-view control's extended styles. For more information, see                         [Tree-View Control Extended Styles](http://msdn.microsoft.com/library/windows/desktop/bb759981).  
  
### Remarks  
 This method sends the                         [TVM_GETEXTENDEDSTYLE](http://msdn.microsoft.com/library/windows/desktop/bb773580) message, which is described in the Windows SDK.  
  
##  <a name="ctreectrl__getfirstvisibleitem"></a>  CTreeCtrl::GetFirstVisibleItem  
 Call this function to retrieve the first visible item of the tree view control.  
  
```  
HTREEITEM GetFirstVisibleItem() const;  
```  
  
### Return Value  
 The handle of the first visible item; otherwise **NULL**.  
  
### Example  
  See the example for [CTreeCtrl::SetCheck](#ctreectrl__setcheck).  
  
##  <a name="ctreectrl__getimagelist"></a>  CTreeCtrl::GetImageList  
 Call this function to retrieve the handle of the normal or state image list associated with the tree view control.  
  
```  
CImageList* GetImageList( UINT nImageList ) const;  
```  
  
### Parameters  
 `nImageList`  
 Type of image list to retrieve. The image list can be one of the following values:  
  
-   `TVSIL_NORMAL` Retrieves the normal image list, which contains the selected and nonselected images for the tree view item.  
  
-   `TVSIL_STATE` Retrieves the state image list, which contains the images for tree view items that are in a user-defined state.  
  
### Return Value  
 Pointer to the control's image list if successful; otherwise **NULL**.  
  
### Remarks  
 Each item in a tree view control can have a pair of bitmapped images associated with it. One image is displayed when the item is selected, and the other is displayed when the item is not selected. For example, an item might display an open folder when it is selected and a closed folder when it is not selected.  
  
 For more information on image lists, see the [CImageList](../VS_visualcpp/CImageList-Class.md) class.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#11](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#11)]  
  
##  <a name="ctreectrl__getindent"></a>  CTreeCtrl::GetIndent  
 Call this function to retrieve the amount, in pixels, that child items are indented relative to their parent items.  
  
```  
UINT GetIndent() const;  
```  
  
### Return Value  
 The amount of indentation measured in pixels.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#12](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#12)]  
  
##  <a name="ctreectrl__getinsertmarkcolor"></a>  CTreeCtrl::GetInsertMarkColor  
 This member function implements the behavior of the Win32 message                 [TVM_GETINSERTMARKCOLOR](http://msdn.microsoft.com/library/windows/desktop/bb773590), as described in the Windows SDK.  
  
```  
COLORREF GetInsertMarkColor() const;  
```  
  
### Return Value  
 A **COLORREF** value that contains the current insertion mark color.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#13](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#13)]  
  
##  <a name="ctreectrl__getitem"></a>  CTreeCtrl::GetItem  
 Call this function to retrieve the attributes of the specified tree view item.  
  
```  
BOOL GetItem( TVITEM* pItem ) const;  
```  
  
### Parameters  
 `pItem`  
 A pointer to a                                 [TVITEM](http://msdn.microsoft.com/library/windows/desktop/bb773456) structure, as described in the Windows SDK.  
  
### Return Value  
 Nonzero if successful; otherwise 0.  
  
### Example  
  See the example for [CTreeCtrl::DeleteItem](#ctreectrl__deleteitem).  
  
##  <a name="ctreectrl__getitemdata"></a>  CTreeCtrl::GetItemData  
 Call this function to retrieve the 32-bit application-specific value associated with the specified item.  
  
```  
DWORD_PTR GetItemData( HTREEITEM hItem ) const;  
```  
  
### Parameters  
 `hItem`  
 Handle of the item whose data is to be retrieved.  
  
### Return Value  
 A 32-bit application-specific value associated with the item specified by `hItem`.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#14](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#14)]  
  
##  <a name="ctreectrl__getitemexpandedimageindex"></a>  CTreeCtrl::GetItemExpandedImageIndex  
 Retrieves the index of the image to display when the specified item of the current tree-view control is in the expanded state.  
  
```  
int GetItemExpandedImageIndex( HTREEITEM hItem )const;  
```  
  
### Parameters  
  
|Parameter|Description|  
|---------------|-----------------|  
|[in] `hItem`|Handle to a tree-view control item.|  
  
### Return Value  
 The index of the image to display when the specified item is in the expanded state.  
  
### Remarks  
 This method sends the                         [TVM_GETITEM](http://msdn.microsoft.com/library/windows/desktop/bb773596) message, which is described in the Windows SDK. That message returns the                         [TVITEMEX](http://msdn.microsoft.com/library/windows/desktop/bb773459) structure that describes the tree-view control item, and then this method retrieves the `iExpandedImage` member from that structure.  
  
##  <a name="ctreectrl__getitemheight"></a>  CTreeCtrl::GetItemHeight  
 This member function implements the behavior of the Win32 message                 [TVM_GETITEMHEIGHT](http://msdn.microsoft.com/library/windows/desktop/bb773599), as described in the Windows SDK.  
  
```  
SHORT GetItemHeight() const;  
```  
  
### Return Value  
 The height of the item, in pixels.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#15](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#15)]  
  
##  <a name="ctreectrl__getitemimage"></a>  CTreeCtrl::GetItemImage  
 Each item in a tree view control can have a pair of bitmapped images associated with it.  
  
```  
BOOL GetItemImage(  
    HTREEITEM hItem,  
    int& nImage,  
    int& nSelectedImage ) const;  
```  
  
### Parameters  
 `hItem`  
 The handle of the item whose image is to be retrieved.  
  
 `nImage`  
 An integer that receives the index of the item's image within the tree view control's image list.  
  
 `nSelectedImage`  
 An integer that receives the index of the item's selected image within the tree view control's image list.  
  
### Return Value  
 Nonzero if successful; otherwise 0.  
  
### Remarks  
 The images appear on the left side of an item's label. One image is displayed when the item is selected, and the other is displayed when the item is not selected. For example, an item might display an open folder when it is selected and a closed folder when it is not selected.  
  
 Call this function to retrieve the index of the item's image and its selected image within the tree view control's image list.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#16](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#16)]  
  
##  <a name="ctreectrl__getitempartrect"></a>  CTreeCtrl::GetItemPartRect  
 Retrieves the bounding rectangle for a specified part of a specified item in the current tree-view control.  
  
```  
BOOL GetItemPartRect(  
     HTREEITEM hItem,   
     int nPart,   
     LPRECT lpRect )const;  
```  
  
### Parameters  
  
|Parameter|Description|  
|---------------|-----------------|  
|[in] `hItem`|Handle to a tree-view control item.|  
|[in] `nPart`|Identifier for the part. Must be set to `TVGIPR_BUTTON`.|  
|[out] `lpRect`|Pointer to a                                         [RECT](http://msdn.microsoft.com/library/windows/desktop/dd162897) structure. If this method is successful, the structure receives the rectangle coordinates of the part specified by `hItem` and `nPart`.|  
  
### Return Value  
 `true` if this method is successful; otherwise, `false`.  
  
### Remarks  
 Each tree control item is bounded by a graphics rectangle. Whenever a point in that rectangle is clicked, the item is said to be *hit*. This method returns the largest rectangle such that when a point in the rectangle is clicked, the item identified by the `hItem` parameter is hit.  
  
 This method sends the `TVM_GETITEMPARTRECT` message, which is described in the Windows SDK. For more information, see the                         [TreeView_GetItemPartRect](http://msdn.microsoft.com/library/windows/desktop/bb773847) macro.  
  
### Example  
 The following code example defines a variable, `m_treeCtrl`, that is used to access the current tree-view control. The code example also defines an unsigned integer and several HTREEITEM variables. These variables are used in the next example.  
  
 [!CODE [NVC_MFC_CTreeCtrl_s1#1](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl_s1#1)]  
  
### Example  
 The following code example uses an accessibility identifier and the [CTreeCtrl::MapAccIdToItem](#ctreectrl__mapaccidtoitem) method to retrieve a handle to the root tree-view item. Then the example uses the handle and the [CTreeCtrl::GetItemPartRect](#ctreectrl__getitempartrect) method to draw a 3D rectangle around that item. In an earlier section of the code example, which is not shown, we created a tree-view that consists of a root country/region node for the United States, subnodes for the states of Pennsylvania and Washington, and tree items for cities in those states. We used the [CTreeCtrl::MapItemToAccID](#ctreectrl__mapitemtoaccid) method to associate the root tree-view item with an accessibility identifier.  
  
 [!CODE [NVC_MFC_CTreeCtrl_s1#5](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl_s1#5)]  
  
##  <a name="ctreectrl__getitemrect"></a>  CTreeCtrl::GetItemRect  
 Call this function to retrieve the bounding rectangle for `hItem` and determine whether it is visible or not.  
  
```  
BOOL GetItemRect(  
    HTREEITEM hItem,  
    LPRECT lpRect,  
    BOOL bTextOnly ) const;  
```  
  
### Parameters  
 `hItem`  
 The handle of a tree view control item.  
  
 `lpRect`  
 Pointer to a                                 [RECT](http://msdn.microsoft.com/library/windows/desktop/dd162897) structure that receives the bounding rectangle. The coordinates are relative to the upper-left corner of the tree view control.  
  
 *bTextOnly*  
 If this parameter is nonzero, the bounding rectangle includes only the text of the item. Otherwise it includes the entire line that the item occupies in the tree view control.  
  
### Return Value  
 Nonzero if the item is visible, with the bounding rectangle contained in `lpRect`. Otherwise, 0 with `lpRect` uninitialized.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#17](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#17)]  
  
##  <a name="ctreectrl__getitemstate"></a>  CTreeCtrl::GetItemState  
 Returns the state of the item specified by `hItem`.  
  
```  
UINT GetItemState(  
    HTREEITEM hItem,  
    UINT nStateMask ) const;  
```  
  
### Parameters  
 `hItem`  
 Handle of the item whose state is to be retrieved.  
  
 `nStateMask`  
 Mask indicating one or more states to be retrieved. For more information on possible values for `nStateMask`, see the discussion of the **state** and **stateMask** members of the                                 [TVITEM](http://msdn.microsoft.com/library/windows/desktop/bb773456) structure in the Windows SDK.  
  
### Return Value  
 A **UINT** that holds the bitwise OR of the values specified by nStateMask. For information on possible values, see [CTreeCtrl::GetItem](#ctreectrl__getitem). To find the value for a specific state, perform a bitwise AND operation of the state value and the return value, as shown in the following example.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#18](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#18)]  
  
##  <a name="ctreectrl__getitemstateex"></a>  CTreeCtrl::GetItemStateEx  
 Retrieves the extended state of the specified item in the current tree-view control.  
  
```  
UINT GetItemStateEx( HTREEITEM hItem ) const;  
```  
  
### Parameters  
  
|Parameter|Description|  
|---------------|-----------------|  
|[in] `hItem`|Handle to a tree-view control item.|  
  
### Return Value  
 The extended state of the item. For more information, see the `uStateEx` member of the                         [TVITEMEX](http://msdn.microsoft.com/library/windows/desktop/bb773459) structure.  
  
### Remarks  
 This method sends the                         [TVM_GETITEM](http://msdn.microsoft.com/library/windows/desktop/bb773596) message, which is described in the Windows SDK. That message returns the                         [TVITEMEX](http://msdn.microsoft.com/library/windows/desktop/bb773459) structure that describes the tree-view control item, and this method retrieves the `uStateEx` member from that structure.  
  
##  <a name="ctreectrl__getitemtext"></a>  CTreeCtrl::GetItemText  
 Returns the text of the item specified by `hItem`.  
  
```  
CString GetItemText( HTREEITEM hItem ) const;  
```  
  
### Parameters  
 `hItem`  
 Handle of the item whose text is to be retrieved.  
  
### Return Value  
 A `CString` object containing the item's text.  
  
### Example  
  See the example for [CTreeCtrl::GetNextItem](#ctreectrl__getnextitem).  
  
##  <a name="ctreectrl__getlastvisibleitem"></a>  CTreeCtrl::GetLastVisibleItem  
 Retrieves the last unexpanded node item in the current tree-view control.  
  
```  
HTREEITEM GetLastVisibleItem() const;  
```  
  
### Return Value  
 The handle to the last unexpanded node item if the method is successful; otherwise, `NULL`.  
  
### Remarks  
 This method sends the                         [TVM_GETNEXTITEM](http://msdn.microsoft.com/library/windows/desktop/bb773622) message, which is described in the Windows SDK. For more information, see the `TVGN_LASTVISIBLE` flag in the `flag` parameter of that message.  
  
### Example  
 The following code example defines a variable, `m_treeCtrl`, that is used to access the current tree-view control. The code example also defines an unsigned integer and several HTREEITEM variables. One or more of these variables are used in the next example.  
  
 [!CODE [NVC_MFC_CTreeCtrl_s1#1](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl_s1#1)]  
  
### Example  
 The following code example retrieves a handle to the last unexpanded tree-view node item, and then draws a 3D rectangle around that item. In an earlier section of the code example, which is not shown, we created a tree-view that consists of a root country/region node for the United States, subnodes for the states of Pennsylvania and Washington, and tree items for cities in those states.  
  
 [!CODE [NVC_MFC_CTreeCtrl_s1#6](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl_s1#6)]  
  
##  <a name="ctreectrl__getlinecolor"></a>  CTreeCtrl::GetLineColor  
 This member function implements the behavior of the win32 message                 [TVM_GETLINECOLOR](http://msdn.microsoft.com/library/windows/desktop/bb773619), as described in the Windows SDK.  
  
```  
COLORREF GetLineColor() const;  
```  
  
### Return Value  
 The current line color.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#19](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#19)]  
  
##  <a name="ctreectrl__getnextitem"></a>  CTreeCtrl::GetNextItem  
 Call this function to retrieve the tree view item that has the specified relationship, indicated by the `nCode` parameter, to `hItem`.  
  
```  
HTREEITEM GetNextItem(  
    HTREEITEM hItem,  
    UINT nCode ) const;  
```  
  
### Parameters  
 `hItem`  
 Handle of a tree item.  
  
 `nCode`  
 A flag indicating the type of relation to `hItem`. This flag can be one of the following values:  
  
-   `TVGN_CARET` Retrieves the currently selected item.  
  
-   `TVGN_CHILD` Retrieves the first child item of the item specified by the `hItem` parameter.  
  
-   `TVGN_DROPHILITE` Retrieves the item that is the target of a drag-and-drop operation.  
  
-   `TVGN_FIRSTVISIBLE` Retrieves the first visible item.  
  
-   `TVGN_LASTVISIBLE` Retrieves the last expanded item in the tree. This does not retrieve the last item visible in the tree-view window.  
  
-   `TVGN_NEXT` Retrieves the next sibling item.  
  
-   `TVGN_NEXTVISIBLE` Retrieves the next visible item that follows the specified item.  
  
-   `TVGN_PARENT` Retrieves the parent of the specified item.  
  
-   `TVGN_PREVIOUS` Retrieves the previous sibling item.  
  
-   `TVGN_PREVIOUSVISIBLE` Retrieves the first visible item that precedes the specified item.  
  
-   `TVGN_ROOT` Retrieves the first child item of the root item of which the specified item is a part.  
  
### Return Value  
 The handle of the next item if successful; otherwise **NULL**.  
  
### Remarks  
 This function will return **NULL** if the item being retrieved is the root node of the tree. For example, if you use this message with the `TVGN_PARENT` flag on a first-level child of the tree view's root node, the message will return **NULL**.  
  
### Example  
 For an example of using `GetNextItem` in a loop, see [CTreeCtrl::DeleteItem](#ctreectrl__deleteitem).  
  
 [!CODE [NVC_MFC_CTreeCtrl#20](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#20)]  
  
##  <a name="ctreectrl__getnextsiblingitem"></a>  CTreeCtrl::GetNextSiblingItem  
 Call this function to retrieve the next sibling of `hItem`.  
  
```  
HTREEITEM GetNextSiblingItem( HTREEITEM hItem ) const;  
```  
  
### Parameters  
 `hItem`  
 Handle of a tree item.  
  
### Return Value  
 The handle of the next sibling item; otherwise **NULL**.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#21](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#21)]  
  
##  <a name="ctreectrl__getnextvisibleitem"></a>  CTreeCtrl::GetNextVisibleItem  
 Call this function to retrieve the next visible item of `hItem`.  
  
```  
HTREEITEM GetNextVisibleItem( HTREEITEM hItem ) const;  
```  
  
### Parameters  
 `hItem`  
 Handle of a tree item.  
  
### Return Value  
 The handle of the next visible item; otherwise **NULL**.  
  
### Example  
  See the example for [CTreeCtrl::SetCheck](#ctreectrl__setcheck).  
  
##  <a name="ctreectrl__getparentitem"></a>  CTreeCtrl::GetParentItem  
 Call this function to retrieve the parent of `hItem`.  
  
```  
HTREEITEM GetParentItem( HTREEITEM hItem ) const;  
```  
  
### Parameters  
 `hItem`  
 Handle of a tree item.  
  
### Return Value  
 The handle of the parent item; otherwise **NULL**.  
  
### Remarks  
 This function will return **NULL** if the parent of the specified item is the root node of the tree.  
  
### Example  
  See the example for [CTreeCtrl::EnsureVisible](#ctreectrl__ensurevisible).  
  
##  <a name="ctreectrl__getprevsiblingitem"></a>  CTreeCtrl::GetPrevSiblingItem  
 Call this function to retrieve the previous sibling of `hItem`.  
  
```  
HTREEITEM GetPrevSiblingItem( HTREEITEM hItem ) const;  
```  
  
### Parameters  
 `hItem`  
 Handle of a tree item.  
  
### Return Value  
 The handle of the previous sibling; otherwise **NULL**.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#22](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#22)]  
  
##  <a name="ctreectrl__getprevvisibleitem"></a>  CTreeCtrl::GetPrevVisibleItem  
 Call this function to retrieve the previous visible item of `hItem`.  
  
```  
HTREEITEM GetPrevVisibleItem( HTREEITEM hItem ) const;  
```  
  
### Parameters  
 `hItem`  
 Handle of a tree item.  
  
### Return Value  
 The handle of the previous visible item; otherwise **NULL**.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#23](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#23)]  
  
##  <a name="ctreectrl__getrootitem"></a>  CTreeCtrl::GetRootItem  
 Call this function to retrieve the root item of the tree view control.  
  
```  
HTREEITEM GetRootItem() const;  
```  
  
### Return Value  
 The handle of the root item; otherwise **NULL**.  
  
### Example  
  See the example for [CTreeCtrl::EditLabel](#ctreectrl__editlabel).  
  
##  <a name="ctreectrl__getscrolltime"></a>  CTreeCtrl::GetScrollTime  
 Call this member function to retrieve the maximum scroll time for the tree view control.  
  
```  
UINT GetScrollTime() const;  
```  
  
### Return Value  
 The maximum scroll time, in milliseconds.  
  
### Remarks  
 This member function implements the behavior of the win32 message                         [TVM_GETSCROLLTIME](http://msdn.microsoft.com/library/windows/desktop/bb773625), as described in the Windows SDK.  
  
##  <a name="ctreectrl__getselectedcount"></a>  CTreeCtrl::GetSelectedCount  
 Retrieves the number of selected items in the current tree-view control.  
  
```  
UINT GetSelectedCount();  
```  
  
### Return Value  
 The number of selected items.  
  
### Remarks  
 This method sends the                         [TVM_GETSELECTEDCOUNT](http://msdn.microsoft.com/library/windows/desktop/bb773629) message, which is described in the Windows SDK.  
  
##  <a name="ctreectrl__getselecteditem"></a>  CTreeCtrl::GetSelectedItem  
 Call this function to retrieve the currently selected item of the tree view control.  
  
```  
HTREEITEM GetSelectedItem() const;  
```  
  
### Return Value  
 The handle of the selected item; otherwise **NULL**.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#24](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#24)]  
  
##  <a name="ctreectrl__gettextcolor"></a>  CTreeCtrl::GetTextColor  
 This member function implements the behavior of the Win32 message                 [TVM_GETTEXTCOLOR](http://msdn.microsoft.com/library/windows/desktop/bb773633), as described in the Windows SDK.  
  
```  
COLORREF GetTextColor() const;  
```  
  
### Return Value  
 A **COLORREF** value that represents the current text color. If this value is -1, the control is using the system color for the text color.  
  
### Example  
  See the example for [CTreeCtrl::SetTextColor](#ctreectrl__settextcolor).  
  
##  <a name="ctreectrl__gettooltips"></a>  CTreeCtrl::GetToolTips  
 This member function implements the behavior of the Win32 message                 [TVM_GETTOOLTIPS](http://msdn.microsoft.com/library/windows/desktop/bb773729), as described in the Windows SDK.  
  
```  
CToolTipCtrl* GetToolTips() const;  
```  
  
### Return Value  
 A pointer to a [CToolTipCtrl](../VS_visualcpp/CToolTipCtrl-Class.md) object to be used by the tree control. If the [Create](#ctreectrl__create) member function uses the style **TVS_NOTOOLTIPS**, no tooltips are used, and **NULL** is returned.  
  
### Remarks  
 The MFC implementation of `GetToolTips` returns a `CToolTipCtrl` object, which is used by the tree control, rather than a handle to a tooltip control.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#25](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#25)]  
  
##  <a name="ctreectrl__getvisiblecount"></a>  CTreeCtrl::GetVisibleCount  
 Call this function to retrieve a count of the visible items in a tree view control.  
  
```  
UINT GetVisibleCount() const;  
```  
  
### Return Value  
 The number of visible items in the tree view control; otherwise – 1.  
  
### Example  
  See the example for [CTreeCtrl::SetCheck](#ctreectrl__setcheck).  
  
##  <a name="ctreectrl__hittest"></a>  CTreeCtrl::HitTest  
 Call this function to determine the location of the specified point relative to the client area of a tree view control.  
  
```  
HTREEITEM HitTest(  
    CPoint pt,  
    UINT* pFlags = NULL ) const;  
  
HTREEITEM HitTest(  
    TVHITTESTINFO* pHitTestInfo ) const;  
```  
  
### Parameters  
 `pt`  
 Client coordinates of the point to test.  
  
 `pFlags`  
 Pointer to an integer that receives information about the results of the hit test. It can be one or more of the values listed under the **flags** member in the Remarks section.  
  
 `pHitTestInfo`  
 Address of a                                 [TVHITTESTINFO](http://msdn.microsoft.com/library/windows/desktop/bb773448) structure that contains the position to hit test and that receives information about the results of the hit test.  
  
### Return Value  
 The handle of the tree view item that occupies the specified point or **NULL** if no item occupies the point.  
  
### Remarks  
 When this function is called, the `pt` parameter specifies the coordinates of the point to test. The function returns the handle of the item at the specified point or **NULL** if no item occupies the point. In addition, the `pFlags` parameter contains a value that indicates the location of the specified point. Possible values are:  
  
|||  
|-|-|  
|Value|Meaning|  
|TVHT_ABOVE|Above the client area.|  
|TVHT_BELOW|Below the client area.|  
|TVHT_NOWHERE|In the client area, but below the last item.|  
|TVHT_ONITEM|On the bitmap or label associated with an item.|  
|TVHT_ONITEMBUTTON|On the button associated with an item.|  
|TVHT_ONITEMICON|On the bitmap associated with an item.|  
|TVHT_ONITEMINDENT|In the indentation associated with an item.|  
|TVHT_ONITEMLABEL|On the label (string) associated with an item.|  
|TVHT_ONITEMRIGHT|In the area to the right of an item.|  
|TVHT_ONITEMSTATEICON|On the state icon for a tree-view item that is in a user-defined state.|  
|TVHT_TOLEFT|To the left of the client area.|  
|TVHT_TORIGHT|To the right of the client area.|  
|||  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#26](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#26)]  
  
##  <a name="ctreectrl__insertitem"></a>  CTreeCtrl::InsertItem  
 Call this function to insert a new item in a tree view control.  
  
```  
HTREEITEM InsertItem(  
    LPTVINSERTSTRUCT lpInsertStruct );  
  
HTREEITEM InsertItem(  
    UINT nMask,  
    LPCTSTR lpszItem,  
    int nImage,  
    int nSelectedImage,  
    UINT nState,  
    UINT nStateMask,  
    LPARAM lParam,  
    HTREEITEM hParent,  
    HTREEITEM hInsertAfter );  
  
HTREEITEM InsertItem(  
    LPCTSTR lpszItem,  
    HTREEITEM hParent = TVI_ROOT,  
    HTREEITEM hInsertAfter = TVI_LAST  );  
  
HTREEITEM InsertItem(  
    LPCTSTR lpszItem,  
    int nImage,  
    int nSelectedImage,  
    HTREEITEM hParent = TVI_ROOT,  
    HTREEITEM hInsertAfter = TVI_LAST );  
```  
  
### Parameters  
 *lpInsertStruct*  
 A pointer to a `TVINSERTSTRUCT` that specifies the attributes of the tree view item to be inserted.  
  
 `nMask`  
 Integer specifying which attributes to set. See the `TVITEM` structure in the Windows SDK.  
  
 `lpszItem`  
 Address of a string containing the item's text.  
  
 `nImage`  
 Index of the item's image in the tree view control's image list.  
  
 `nSelectedImage`  
 Index of the item's selected image in the tree view control's image list.  
  
 `nState`  
 Specifies values for the item's states. See Tree View Control Item States in the Windows SDK for a list of appropriate states.  
  
 `nStateMask`  
 Specifies which states are to be set. See the `TVITEM` structure in the Windows SDK.  
  
 `lParam`  
 A 32-bit application-specific value associated with the item.  
  
 `hParent`  
 Handle of the inserted item's parent.  
  
 *hInsertAfter*  
 Handle of the item after which the new item is to be inserted.  
  
### Return Value  
 Handle of the new item if successful; otherwise **NULL**.  
  
### Remarks  
 The example shows situations in which you might want to use each version of the function when inserting a tree control item.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#27](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#27)]  
  
##  <a name="ctreectrl__itemhaschildren"></a>  CTreeCtrl::ItemHasChildren  
 Use this function to determine whether the tree item specified by `hItem` has child items.  
  
```  
BOOL ItemHasChildren( HTREEITEM hItem ) const;  
```  
  
### Parameters  
 `hItem`  
 Handle of a tree item.  
  
### Return Value  
 Nonzero if the tree item specified by `hItem` has child items; 0 if it does not.  
  
### Remarks  
 If so, you can then use [CTreeCtrl::GetChildItem](#ctreectrl__getchilditem) to retrieve those child items.  
  
### Example  
  See the example for [CTreeCtrl::GetSelectedItem](#ctreectrl__getselecteditem).  
  
##  <a name="ctreectrl__mapaccidtoitem"></a>  CTreeCtrl::MapAccIdToItem  
 Maps the specified accessibility identifier to the handle of a tree-view item in the current tree-view control.  
  
```  
HTREEITEM MapAccIdToItem( UINT uAccId ) const;  
```  
  
### Parameters  
  
|Parameter|Description|  
|---------------|-----------------|  
|[in] `uAccId`|An accessibility identifier for an element in the tree-view item.|  
  
### Return Value  
 The handle to a tree-view item ( `HTREEITEM`) that corresponds to the `uAccId` parameter. For more information, see the `hItem` member of the                         [TVITEMEX](http://msdn.microsoft.com/library/windows/desktop/bb773459) structure.  
  
### Remarks  
 Accessibility aids are applications that help people with disabilities use computers. An accessibility identifier is used by the `IAccessible` interface to uniquely specify an element in a window. For more information about accessibility identifiers, search for the "About Active Accessibility Support" topic at                         [Microsoft Developer Network](http://go.microsoft.com/fwlink/?LinkId=56322).  
  
 This method sends the                         [TVM_MAPACCIDTOHTREEITEM](http://msdn.microsoft.com/library/windows/desktop/bb773734) message, which is described in the Windows SDK.  
  
### Example  
 The following code example defines a variable, `m_treeCtrl`, that is used to access the current tree-view control. The code example also defines an unsigned integer and several HTREEITEM variables. These variables are used in the next example.  
  
 [!CODE [NVC_MFC_CTreeCtrl_s1#1](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl_s1#1)]  
  
### Example  
 The following code example uses an accessibility identifier and the [CTreeCtrl::MapAccIdToItem](#ctreectrl__mapaccidtoitem) method to retrieve a handle to the root tree-view item. The example uses the handle and the [CTreeCtrl::GetItemPartRect](#ctreectrl__getitempartrect) method to draw a 3D rectangle around that item. In an earlier section of the code example, which is not shown, we created a tree-view that consists of a root country/region node for the United States, subnodes for the states of Pennsylvania and Washington, and tree items for cities in those states. We used the [CTreeCtrl::MapItemToAccID](#ctreectrl__mapitemtoaccid) method to associate the root tree-view item with an accessibility identifier.  
  
 [!CODE [NVC_MFC_CTreeCtrl_s1#5](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl_s1#5)]  
  
##  <a name="ctreectrl__mapitemtoaccid"></a>  CTreeCtrl::MapItemToAccID  
 Maps the specified handle of a tree-view item in the current tree-view control to an accessibility identifier.  
  
```  
UINT MapItemToAccID( HTREEITEM hItem ) const;  
```  
  
### Parameters  
  
|Parameter|Description|  
|---------------|-----------------|  
|[in] `hItem`|A handle of a tree-view item in the control. For more information, see the `hItem` member of the                                         [TVITEMEX](http://msdn.microsoft.com/library/windows/desktop/bb773459) structure.|  
  
### Return Value  
 The accessibility identifier that corresponds to the `hItem` parameter.  
  
### Remarks  
 Accessibility aids are applications that help people with disabilities use computers. An accessibility identifier is used by the `IAccessible` interface to uniquely specify an element in a window. For more information about accessibility identifiers, search for the "About Active Accessibility Support" topic at                         [Microsoft Developer Network](http://go.microsoft.com/fwlink/?LinkId=56322).  
  
 This method sends the                         [TVM_MAPHTREEITEMTOACCID](http://msdn.microsoft.com/library/windows/desktop/bb773735) message, which is described in the Windows SDK.  
  
### Example  
 The following code example defines a variable, `m_treeCtrl`, that is used to access the current tree-view control. The code example also defines an unsigned integer and several HTREEITEM variables. These variables are used in the next example.  
  
 [!CODE [NVC_MFC_CTreeCtrl_s1#1](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl_s1#1)]  
  
### Example  
 The following code example obtains an identification number for a tree-view control item. In an earlier section of the code example, which is not shown, we created a tree-view that consists of a root country/region node for the United States, subnodes for the states of Pennsylvania and Washington, and tree items for cities in those states. This code example obtains a unique identification number for the root country/region node.  
  
 [!CODE [NVC_MFC_CTreeCtrl_s1#2](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl_s1#2)]  
  
##  <a name="ctreectrl__select"></a>  CTreeCtrl::Select  
 Call this function to select the given tree view item, scroll the item into view, or redraw the item in the style used to indicate the target of a drag-and-drop operation.  
  
```  
BOOL Select(  
    HTREEITEM hItem,  
    UINT nCode );  
```  
  
### Parameters  
 `hItem`  
 Handle of a tree item.  
  
 `nCode`  
 The type of action to take. This parameter can be one of the following values:  
  
-   `TVGN_CARET` Sets the selection to the given item.  
  
-   `TVGN_DROPHILITE` Redraws the given item in the style used to indicate the target of a drag-and-drop operation.  
  
-   `TVGN_FIRSTVISIBLE` Scrolls the tree view vertically so that the given item is the first visible item.  
  
### Return Value  
 Nonzero if successful; otherwise 0.  
  
### Remarks  
 If `nCode` contains the value `TVGN_CARET`, the parent window receives the **TVN_SELCHANGING** and **TVN_SELCHANGED** notification messages. In addition, if the specified item is the child of a collapsed parent item, the parent's list of child items is expanded to reveal the specified item. In this case, the parent window receives the **TVN_ITEMEXPANDING** and **TVN_ITEMEXPANDED** notification messages.  
  
### Example  
  See the example for [CTreeCtrl::HitTest](#ctreectrl__hittest).  
  
##  <a name="ctreectrl__selectdroptarget"></a>  CTreeCtrl::SelectDropTarget  
 Call this function to redraw the item in the style used to indicate the target of a drag-and-drop operation.  
  
```  
BOOL SelectDropTarget( HTREEITEM hItem );  
```  
  
### Parameters  
 `hItem`  
 Handle of a tree item.  
  
### Return Value  
 Nonzero if successful; otherwise 0.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#9](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#9)]  
  
##  <a name="ctreectrl__selectitem"></a>  CTreeCtrl::SelectItem  
 Call this function to select the given tree view item.  
  
```  
BOOL SelectItem( HTREEITEM hItem );  
```  
  
### Parameters  
 `hItem`  
 Handle of a tree item.  
  
### Return Value  
 Nonzero if successful; otherwise 0.  
  
### Remarks  
 If `hItem` is **NULL**, then this function selects no item.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#26](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#26)]  
  
##  <a name="ctreectrl__selectsetfirstvisible"></a>  CTreeCtrl::SelectSetFirstVisible  
 Call this function to scroll the tree view vertically so that the given item is the first visible item.  
  
```  
BOOL SelectSetFirstVisible( HTREEITEM hItem );  
```  
  
### Parameters  
 `hItem`  
 Handle of the tree item to be set as the first visible item.  
  
### Return Value  
 Nonzero if successful; otherwise 0.  
  
### Remarks  
 The function sends a message to the window with the `TVM_SELECTITEM` and `TVGN_FIRSTVISIBLE` message parameters.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#28](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#28)]  
  
##  <a name="ctreectrl__setautoscrollinfo"></a>  CTreeCtrl::SetAutoscrollInfo  
 Sets the autoscroll rate of the current tree-view control.  
  
```  
BOOL SetAutoscrollInfo(  
     UINT uPixelsPerSec,   
     UINT uUpdateTime );  
```  
  
### Parameters  
  
|Parameter|Description|  
|---------------|-----------------|  
|[in] `uPixelsPerSec`|The number of pixels per second to scroll.|  
|[in] `uUpdateTime`|The time interval between updates of the control.|  
  
### Return Value  
 Always returns `true`.  
  
### Remarks  
 The autoscroll parameters are used to scroll into view an item that is currently not visible. The tree-view control must have the `TVS_EX_AUTOHSCROLL` extended style, which is described in                         [Tree-View Control Extended Styles](http://msdn.microsoft.com/library/windows/desktop/bb759981).  
  
 This method sends the                         [TVM_SETAUTOSCROLLINFO](http://msdn.microsoft.com/library/windows/desktop/bb773738) message, which is described in the Windows SDK.  
  
### Example  
 The following code example defines a variable, `m_treeCtrl`, that is used to access the current tree-view control. The code example also defines an unsigned integer and several HTREEITEM variables. These variables are used in the next example.  
  
 [!CODE [NVC_MFC_CTreeCtrl_s1#1](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl_s1#1)]  
  
### Example  
 The following code example sets the autoscroll behavior of the current tree-view control. In an earlier section of the code example, which is not shown, we created a tree-view that consists of a root country/region node for the United States, subnodes for the states of Pennsylvania and Washington, and tree items for cities in those states. We intentionally made the tree-view control narrow so that it must automatically scroll to display the tree item that has the focus. The code example sets the tree-view control to automatically scroll 30 pixels per second every 5 seconds until the tree item is in view.  
  
 [!CODE [NVC_MFC_CTreeCtrl_s1#4](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl_s1#4)]  
  
##  <a name="ctreectrl__setbkcolor"></a>  CTreeCtrl::SetBkColor  
 This member function implements the behavior of the Win32 message                 [TVM_SETBKCOLOR](http://msdn.microsoft.com/library/windows/desktop/bb773741), as described in the Windows SDK.  
  
```  
COLORREF SetBkColor( COLORREF clr );  
```  
  
### Parameters  
 `clr`  
 A **COLORREF** value that contains the new background color. If this value is -1, the control will revert to using the system color for the background color.  
  
### Return Value  
 A **COLORREF** value that represents the current text color. If this value is -1, the control is using the system color for the text color.  
  
### Example  
  See the example for [CTreeCtrl::SetTextColor](#ctreectrl__settextcolor).  
  
##  <a name="ctreectrl__setcheck"></a>  CTreeCtrl::SetCheck  
 Call this member function to set the check state for a tree control item.  
  
```  
BOOL SetCheck(  
    HTREEITEM hItem,  
    BOOL fCheck = TRUE  );  
```  
  
### Parameters  
 `hItem`  
 The **HTREEITEM** to receive the check state change.  
  
 `fCheck`  
 Indicates whether the tree control item is to be checked or unchecked. By default, `SetCheck` sets the item to be checked.  
  
### Return Value  
 Nonzero if successful; otherwise 0.  
  
### Remarks  
 When the tree control item is checked ( `fCheck` set to **TRUE**), the item appears with an adjacent checkmark.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#29](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#29)]  
  
### Example  
 To use checkboxes, set TVS_CHECKBOXES before populating the tree control.  
  
 [!CODE [NVC_MFC_CTreeCtrl#30](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#30)]  
  
##  <a name="ctreectrl__setextendedstyle"></a>  CTreeCtrl::SetExtendedStyle  
 Sets the extended styles for the current tree-view control.  
  
```  
DWORD SetExtendedStyle(  
      DWORD dwExMask,   
      DWORD dwExStyles );  
```  
  
### Parameters  
  
|Parameter|Description|  
|---------------|-----------------|  
|[in] `dwExMask`|A bitmask that specifies which styles in the current tree-view control are affected by this method. If this parameter is zero, it is ignored and the value of the `dwExStyles` parameter is assigned to the tree-view control.<br /><br /> Specify zero or a bitwise combination (OR) of styles described in                                         [Tree-View Control Extended Styles](http://msdn.microsoft.com/library/windows/desktop/bb759981).|  
|[in] `dwExStyles`|A bitmask that specifies which styles in the current tree-view control to set or clear.<br /><br /> To set a combination of styles, specify a bitwise combination (OR) of styles described in                                         [Tree-View Control Extended Styles](http://msdn.microsoft.com/library/windows/desktop/bb759981). To clear a set of styles, specify zero.|  
  
### Return Value  
 A value that contains the previous extended control styles.  
  
### Remarks  
 This method clears the styles specified in the `dwExMask` parameter, then sets the styles specified in the `dwExStyles` parameter. Only the extended styles that correspond to the bits in `dwExMask` change.  
  
 This method sends the                         [TVM_SETEXTENDEDSTYLE](http://msdn.microsoft.com/library/windows/desktop/bb773744) message, which is described in the Windows SDK.  
  
### Example  
 The following code example defines a variable, `m_treeCtrl`, that is used to access the current tree-view control. The code example also defines an unsigned integer and several HTREEITEM variables. These variables are used in the next example.  
  
 [!CODE [NVC_MFC_CTreeCtrl_s1#1](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl_s1#1)]  
  
### Example  
 The following code example adds the `TVS_EX_AUTOHSCROLL` extended style to the current tree-view control. In an earlier section of the code example, which is not shown, we created a tree-view that consists of a root country/region node for the United States, subnodes for the states of Pennsylvania and Washington, and tree items for cities in those states. We intentionally made the tree-view control narrow so that it must automatically scroll to display the tree item that has the focus.  
  
 [!CODE [NVC_MFC_CTreeCtrl_s1#3](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl_s1#3)]  
  
##  <a name="ctreectrl__setimagelist"></a>  CTreeCtrl::SetImageList  
 Call this function to set the normal or state image list for a tree view control and redraw the control using the new images.  
  
```  
CImageList* SetImageList(  
    CImageList * pImageList,  
    int nImageListType );  
```  
  
### Parameters  
 `pImageList`  
 Pointer to the image list to assign. If `pImageList` is **NULL**, all images are removed from the tree view control.  
  
 `nImageListType`  
 Type of image list to set. The image list can be one of the following values:  
  
-   `TVSIL_NORMAL` Sets the normal image list, which contains the selected and nonselected images for the tree view item. You must use this state for overlay images.  
  
-   `TVSIL_STATE` Sets the state image list, which contains the images for tree view items that are in a user-defined state.  
  
### Return Value  
 Pointer to the previous image list, if any; otherwise **NULL**.  
  
### Example  
  See the example for [CTreeCtrl::GetImageList](#ctreectrl__getimagelist).  
  
##  <a name="ctreectrl__setindent"></a>  CTreeCtrl::SetIndent  
 Call this function to set the width of indentation for a tree view control and redraw the control to reflect the new width.  
  
```  
void SetIndent( UINT nIndent );  
```  
  
### Parameters  
 `nIndent`  
 Width, in pixels, of the indentation. If `nIndent` is less than the system-defined minimum width, the new width is set to the system-defined minimum.  
  
### Example  
  See the example for [CTreeCtrl::GetIndent](#ctreectrl__getindent).  
  
##  <a name="ctreectrl__setinsertmark"></a>  CTreeCtrl::SetInsertMark  
 This member function implements the behavior of the Win32 message                 [TVM_SETINSERTMARK](http://msdn.microsoft.com/library/windows/desktop/bb773753), as described in the Windows SDK.  
  
```  
BOOL SetInsertMark(  
    HTREEITEM hItem,  
    BOOL fAfter = TRUE  );  
```  
  
### Parameters  
 `hItem`  
 **HTREEITEM** that specifies at which item the insertion mark will be placed. If this argument is **NULL**, the insertion mark is removed.  
  
 *fAfter*  
 **BOOL** value that specifies if the insertion mark is placed before or after the specified item. If this argument is nonzero, the insertion mark will be placed after the item. If this argument is zero, the insertion mark will be placed before the item.  
  
### Return Value  
 Nonzero if successful; otherwise 0.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#31](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#31)]  
  
##  <a name="ctreectrl__setinsertmarkcolor"></a>  CTreeCtrl::SetInsertMarkColor  
 This member function implements the behavior of the Win32 message                 [TVM_SETINSERTMARKCOLOR](http://msdn.microsoft.com/library/windows/desktop/bb773755), as described in the Windows SDK.  
  
```  
COLORREF SetInsertMarkColor( COLORREF clrNew );  
```  
  
### Parameters  
 `clrNew`  
 A **COLORREF** value that contains the new insertion mark color.  
  
### Return Value  
 A **COLORREF** value that contains the previous insertion mark color.  
  
### Example  
  See the example for [CTreeCtrl::GetInsertMarkColor](#ctreectrl__getinsertmarkcolor).  
  
##  <a name="ctreectrl__setitem"></a>  CTreeCtrl::SetItem  
 Call this function to set the attributes of the specified tree view item.  
  
```  
BOOL SetItem(  
    TVITEM* pItem );  
  
BOOL SetItem(  
    HTREEITEM hItem,  
    UINT nMask,  
    LPCTSTR lpszItem,  
    int nImage,  
    int nSelectedImage,  
    UINT nState,  
    UINT nStateMask,  
    LPARAM lParam );  
```  
  
### Parameters  
 `pItem`  
 A pointer to a                                 [TVITEM](http://msdn.microsoft.com/library/windows/desktop/bb773456) structure that contains the new item attributes, as described in the Windows SDK.  
  
 `hItem`  
 Handle of the item whose attributes are to be set. See the **hItem** member of the `TVITEM` structure in the Windows SDK.  
  
 `nMask`  
 Integer specifying which attributes to set. See the **mask** member of the `TVITEM` structure.  
  
 `lpszItem`  
 Address of a string containing the item's text.  
  
 `nImage`  
 Index of the item's image in the tree view control's image list. See the `iImage` member of the `TVITEM` structure.  
  
 `nSelectedImage`  
 Index of the item's selected image in the tree view control's image list. See the **iSelectedImage** member of the `TVITEM` structure.  
  
 `nState`  
 Specifies values for the item's states. See the **State** member of the `TVITEM` structure.  
  
 `nStateMask`  
 Specifies which states are to be set. See the **stateMask** member of the `TVITEM` structure.  
  
 `lParam`  
 A 32-bit application-specific value associated with the item.  
  
### Return Value  
 Nonzero if successful; otherwise 0.  
  
### Remarks  
 In the `TVITEM` structure, the **hItem** member identifies the item, and the **mask** member specifies which attributes to set.  
  
 If the **mask** member or the `nMask` parameter specifies the `TVIF_TEXT` value, the **pszText** member or the `lpszItem` is the address of a null-terminated string and the **cchTextMax** member is ignored. If **mask** (or `nMask`) specifies the `TVIF_STATE` value, the **stateMask** member or the `nStateMask` parameter specifies which item states to change and the **state** member or `nState` parameter contains the values for those states.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#32](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#32)]  
  
##  <a name="ctreectrl__setitemdata"></a>  CTreeCtrl::SetItemData  
 Call this function to set the 32-bit application-specific value associated with the specified item.  
  
```  
BOOL SetItemData(  
    HTREEITEM hItem,  
    DWORD_PTR dwData );  
```  
  
### Parameters  
 `hItem`  
 Handle of the item whose data is to be retrieved.  
  
 `dwData`  
 A 32-bit application-specific value associated with the item specified by `hItem`.  
  
### Return Value  
 Nonzero if successful; otherwise 0.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#33](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#33)]  
  
##  <a name="ctreectrl__setitemexpandedimageindex"></a>  CTreeCtrl::SetItemExpandedImageIndex  
 Sets the index of the image to display when the specified item of the current tree-view control is in the expanded state.  
  
```  
BOOL SetItemExpandedImageIndex(  
     HTREEITEM hItem,   
     int iExpandedImage );  
```  
  
### Parameters  
  
|Parameter|Description|  
|---------------|-----------------|  
|[in] `hItem`|Handle to a tree-view control item.|  
|[in] `iExpandedImage`|The index of the image to display when the specified item is in the expanded state.|  
  
### Return Value  
 `true` if this method is successful; otherwise, `false`.  
  
### Remarks  
 This method sends the                         [TVM_SETITEM](http://msdn.microsoft.com/library/windows/desktop/bb773758) message, which is described in the Windows SDK. This method assigns the `iExpandedImage` parameter to the `iExpandedImage` member of a                         [TVITEMEX](http://msdn.microsoft.com/library/windows/desktop/bb773459) structure, and then uses that structure in the message.  
  
### Example  
 The following code example defines a variable, `m_treeCtrl`, that is used to access the current tree-view control. The code example also defines an unsigned integer and several HTREEITEM variables. These variables are used in the next example.  
  
 [!CODE [NVC_MFC_CTreeCtrl_s1#1](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl_s1#1)]  
  
### Example  
 The following code example is a trivial test to determine whether the [CTreeCtrl::GetItemExpandedImageIndex](#ctreectrl__getitemexpandedimageindex) method returns the value set by the [CTreeCtrl::SetItemExpandedImageIndex](#ctreectrl__setitemexpandedimageindex) method. In an earlier section of the code example, which is not shown, we created a tree-view that consists of a root country/region node for the United States, subnodes for the states of Pennsylvania and Washington, and tree items for cities in those states.  
  
 [!CODE [NVC_MFC_CTreeCtrl_s1#8](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl_s1#8)]  
  
##  <a name="ctreectrl__setitemheight"></a>  CTreeCtrl::SetItemHeight  
 This member function implements the behavior of the Win32 message                 [TVM_SETITEMHEIGHT](http://msdn.microsoft.com/library/windows/desktop/bb773761), as described in the Windows SDK.  
  
```  
SHORT SetItemHeight( SHORT cyHeight );  
```  
  
### Parameters  
 `cyHeight`  
 Specifies the new height of every item in the tree view, in pixels. If this argument is less than the height of the images, then it will be set to the height of the images. If this argument is not even, it will be rounded down to the nearest even value. If this argument is -1, the control will revert to using its default item height.  
  
### Return Value  
 The previous height of the items, in pixels.  
  
### Example  
  See the example for [CTreeCtrl::GetItemHeight](#ctreectrl__getitemheight).  
  
##  <a name="ctreectrl__setitemimage"></a>  CTreeCtrl::SetItemImage  
 Associates images with an item.  
  
```  
BOOL SetItemImage(  
    HTREEITEM hItem,  
    int nImage,  
    int nSelectedImage );  
```  
  
### Parameters  
 `hItem`  
 Handle of the item whose image is to be set.  
  
 `nImage`  
 Index of the item's image in the tree view control's image list.  
  
 `nSelectedImage`  
 Index of the item's selected image in the tree view control's image list.  
  
### Return Value  
 Nonzero if successful; otherwise 0.  
  
### Remarks  
 Each item in a tree view control can have a pair of bitmapped images associated with it. The images appear on the left side of an item's label. One image is displayed when the item is selected, and the other is displayed when the item is not selected. For example, an item might display an open folder when it is selected and a closed folder when it is not selected.  
  
 Call this function to set the index of the item's image and its selected image within the tree view control's image list.  
  
 For more information on images, see [CImageList](../VS_visualcpp/CImageList-Class.md).  
  
### Example  
  See the example for [CTreeCtrl::GetItemImage](#ctreectrl__getitemimage).  
  
##  <a name="ctreectrl__setitemstate"></a>  CTreeCtrl::SetItemState  
 Sets the state of the item specified by `hItem`.  
  
```  
BOOL SetItemState(  
    HTREEITEM hItem,  
    UINT nState,  
    UINT nStateMask );  
```  
  
### Parameters  
 `hItem`  
 Handle of the item whose state is to be set.  
  
 `nState`  
 Specifies new states for the item.  
  
 `nStateMask`  
 Specifies which states are to be changed.  
  
### Return Value  
 Nonzero if successful; otherwise 0.  
  
### Remarks  
 For information on states, see [CTreeCtrl::GetItem](#ctreectrl__getitem).  
  
### Example  
  See the example for [CTreeCtrl::GetItemState](#ctreectrl__getitemstate).  
  
##  <a name="ctreectrl__setitemstateex"></a>  CTreeCtrl::SetItemStateEx  
 Sets the extended state of the specified item in the current tree-view control.  
  
```  
BOOL SetItemStateEx(  
     HTREEITEM hItem,   
     UINT uStateEx );  
```  
  
### Parameters  
  
|Parameter|Description|  
|---------------|-----------------|  
|[in] `hItem`|Handle to a tree-view control item.|  
|[in] `uStateEx`|The extended state of the item. For more information, see the `uStateEx` member of the                                         [TVITEMEX](http://msdn.microsoft.com/library/windows/desktop/bb773459) structure.|  
  
### Return Value  
 `true` if this method is successful; otherwise, `false`.  
  
### Remarks  
 This method sends the                         [TVM_SETITEM](http://msdn.microsoft.com/library/windows/desktop/bb773758) message, which is described in the Windows SDK. This method assigns the `uStateEx` parameter to the `uStateEx` member of a                         [TVITEMEX](http://msdn.microsoft.com/library/windows/desktop/bb773459) structure, and then uses that structure in the message.  
  
### Example  
 The following code example defines a variable, `m_treeCtrl`, that is used to access the current tree-view control. The code example also defines an unsigned integer and several HTREEITEM variables. These variables are used in the next example.  
  
 [!CODE [NVC_MFC_CTreeCtrl_s1#1](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl_s1#1)]  
  
### Example  
 The following code example sets a tree-view item to disabled state. In an earlier section of the code example, which is not shown, we created a tree-view that consists of a root country/region node for the United States, subnodes for the states of Pennsylvania and Washington, and tree items for cities in those states. This code example sets the Pennsylvania node to disabled state.  
  
 [!CODE [NVC_MFC_CTreeCtrl_s1#7](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl_s1#7)]  
  
##  <a name="ctreectrl__setitemtext"></a>  CTreeCtrl::SetItemText  
 Sets the text of the item specified by `hItem`.  
  
```  
BOOL SetItemText(  
    HTREEITEM hItem,  
    LPCTSTR lpszItem );  
```  
  
### Parameters  
 `hItem`  
 Handle of the item whose text is to be set.  
  
 `lpszItem`  
 Address of a string containing the new text for the item  
  
### Return Value  
 Nonzero if successful; otherwise 0.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#34](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#34)]  
  
##  <a name="ctreectrl__setlinecolor"></a>  CTreeCtrl::SetLineColor  
 Call this member function to set the current line color for the tree view control.  
  
```  
COLORREF SetLineColor( COLORREF clrNew = CLR_DEFAULT  );  
```  
  
### Parameters  
 `clrNew`  
 The new line color.  
  
### Return Value  
 The previous line color.  
  
### Remarks  
 This member function implements the behavior of the win32 message                         [TVM_SETLINECOLOR](http://msdn.microsoft.com/library/windows/desktop/bb773764), as described in the Windows SDK.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#35](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#35)]  
  
##  <a name="ctreectrl__setscrolltime"></a>  CTreeCtrl::SetScrollTime  
 Call this member function to set the maximum scroll time for the tree view control.  
  
```  
UINT SetScrollTime( UINT uScrollTime );  
```  
  
### Parameters  
 *uScrollTime*  
 The new maximum scroll time, in milliseconds. If this value is less than 100, it will be rounded up to 100.  
  
### Return Value  
 The previous maximum scroll time, in milliseconds.  
  
### Remarks  
 This member function implements the behavior of the win32 message                         [TVM_SETSCROLLTIME](http://msdn.microsoft.com/library/windows/desktop/bb773767), as described in the Windows SDK.  
  
##  <a name="ctreectrl__settextcolor"></a>  CTreeCtrl::SetTextColor  
 This member function implements the behavior of the Win32 message                 [TVM_SETTEXTCOLOR](http://msdn.microsoft.com/library/windows/desktop/bb773769), as described in the Windows SDK.  
  
```  
COLORREF SetTextColor( COLORREF clr );  
```  
  
### Parameters  
 `clr`  
 A **COLORREF** value that contains the new text color. If this argument is -1, the control will revert to using the system color for the text color.  
  
### Return Value  
 A **COLORREF** value that represents the previous text color. If this value is -1, the control was using the system color for the text color.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#36](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#36)]  
  
##  <a name="ctreectrl__settooltips"></a>  CTreeCtrl::SetToolTips  
 This member function implements the behavior of the Win32 message                 [TVM_SETTOOLTIPS](http://msdn.microsoft.com/library/windows/desktop/bb773772), as described in the Windows SDK.  
  
```  
CToolTipCtrl* SetToolTips( CToolTipCtrl* pWndTip );  
```  
  
### Parameters  
 `pWndTip`  
 A pointer to a [CToolTipCtrl](../VS_visualcpp/CToolTipCtrl-Class.md) object that the tree control will use.  
  
### Return Value  
 A pointer to a [CToolTipCtrl](../VS_visualcpp/CToolTipCtrl-Class.md) object containing the tooltip previously used by the control, or **NULL** if no tooltips were used previously.  
  
### Remarks  
 To use tooltips, indicate the **TVS_NOTOOLTIPS** style when you create the `CTreeCtrl` object.  
  
### Example  
  See the example for [CTreeCtrl::GetToolTips](#ctreectrl__gettooltips).  
  
##  <a name="ctreectrl__showinfotip"></a>  CTreeCtrl::ShowInfoTip  
 Displays the infotip for the specified item in the current tree-view control.  
  
```  
void ShowInfoTip( HTREEITEM hItem );  
```  
  
### Parameters  
  
|Parameter|Description|  
|---------------|-----------------|  
|[in] `hItem`|A handle to a tree-view item in the control. For more information, see the `hItem` member of the                                         [TVITEMEX](http://msdn.microsoft.com/library/windows/desktop/bb773459) structure.|  
  
### Remarks  
 For more information about the difference between tooltips and infotips, search for the "Tooltips and Infotips" topic at                         [Microsoft Developer Network](http://go.microsoft.com/fwlink/?LinkId=56322).  
  
 This method sends the                         [TVM_SHOWINFOTIP](http://msdn.microsoft.com/library/windows/desktop/bb773779) message, which is described in the Windows SDK.  
  
##  <a name="ctreectrl__sortchildren"></a>  CTreeCtrl::SortChildren  
 Call this function to alphabetically sort the child items of the given parent item in a tree view control.  
  
```  
BOOL SortChildren( HTREEITEM hItem );  
```  
  
### Parameters  
 `hItem`  
 Handle of the parent item whose child items are to be sorted. If `hItem` is **NULL**, sorting will proceed from the root of the tree.  
  
### Return Value  
 Nonzero if successful; otherwise 0.  
  
### Remarks  
 `SortChildren` will not recurse through the tree; only the immediate children of `hItem` will be sorted.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#37](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#37)]  
  
##  <a name="ctreectrl__sortchildrencb"></a>  CTreeCtrl::SortChildrenCB  
 Call this function to sort tree view items using an application-defined callback function that compares the items.  
  
```  
BOOL SortChildrenCB( LPTVSORTCB pSort );  
```  
  
### Parameters  
 *pSort*  
 Pointer to a                                 [TVSORTCB](http://msdn.microsoft.com/library/windows/desktop/bb773462) structure.  
  
### Return Value  
 Nonzero if successful; otherwise 0.  
  
### Remarks  
 The structure's comparison function, **lpfnCompare**, must return a negative value if the first item should precede the second, a positive value if the first item should follow the second, or zero if the two items are equivalent.  
  
 The `lParam1` and `lParam2` parameters correspond to the **lParam** member of the                         [TVITEM](http://msdn.microsoft.com/library/windows/desktop/bb773456) structure for the two items being compared. The `lParamSort` parameter corresponds to the **lParam** member of the `TV_SORTCB` structure.  
  
### Example  
 [!CODE [NVC_MFC_CTreeCtrl#38](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#38)]  
  
 [!CODE [NVC_MFC_CTreeCtrl#39](../CodeSnippet/VS_Snippets_Cpp/NVC_MFC_CTreeCtrl#39)]  
  
## See Also  
 [MFC Sample CMNCTRL1](../VS_visualcpp/Visual-C---Samples.md)   
 [CWnd Class](../VS_visualcpp/CWnd-Class.md)   
 [Hierarchy Chart](../VS_visualcpp/Hierarchy-Chart.md)   
 [CImageList Class](../VS_visualcpp/CImageList-Class.md)