[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TileView

# Class: TileView

[ue/ue](../modules/ue_ue.md).TileView

## Hierarchy

- [`ListView`](ue_ue.ListView.md)

  ↳ **`TileView`**

## Table of contents

### Constructors

- [constructor](ue_ue.TileView.md#constructor)

### Properties

- [AccessibleBehavior](ue_ue.TileView.md#accessiblebehavior)
- [AccessibleSummaryBehavior](ue_ue.TileView.md#accessiblesummarybehavior)
- [AccessibleSummaryText](ue_ue.TileView.md#accessiblesummarytext)
- [AccessibleSummaryTextDelegate](ue_ue.TileView.md#accessiblesummarytextdelegate)
- [AccessibleText](ue_ue.TileView.md#accessibletext)
- [AccessibleTextDelegate](ue_ue.TileView.md#accessibletextdelegate)
- [AccessibleWidgetData](ue_ue.TileView.md#accessiblewidgetdata)
- [BP\_OnEntryGenerated](ue_ue.TileView.md#bp_onentrygenerated)
- [BP\_OnEntryInitialized](ue_ue.TileView.md#bp_onentryinitialized)
- [BP\_OnEntryReleased](ue_ue.TileView.md#bp_onentryreleased)
- [BP\_OnItemClicked](ue_ue.TileView.md#bp_onitemclicked)
- [BP\_OnItemDoubleClicked](ue_ue.TileView.md#bp_onitemdoubleclicked)
- [BP\_OnItemIsHoveredChanged](ue_ue.TileView.md#bp_onitemishoveredchanged)
- [BP\_OnItemScrolledIntoView](ue_ue.TileView.md#bp_onitemscrolledintoview)
- [BP\_OnItemSelectionChanged](ue_ue.TileView.md#bp_onitemselectionchanged)
- [CategoryName](ue_ue.TileView.md#categoryname)
- [Clipping](ue_ue.TileView.md#clipping)
- [ConsumeMouseWheel](ue_ue.TileView.md#consumemousewheel)
- [Cursor](ue_ue.TileView.md#cursor)
- [DesignerFlags](ue_ue.TileView.md#designerflags)
- [DisplayLabel](ue_ue.TileView.md#displaylabel)
- [EntryHeight](ue_ue.TileView.md#entryheight)
- [EntrySpacing](ue_ue.TileView.md#entryspacing)
- [EntryWidgetClass](ue_ue.TileView.md#entrywidgetclass)
- [EntryWidgetPool](ue_ue.TileView.md#entrywidgetpool)
- [EntryWidth](ue_ue.TileView.md#entrywidth)
- [FixedLineScrollOffset](ue_ue.TileView.md#fixedlinescrolloffset)
- [FlowDirectionPreference](ue_ue.TileView.md#flowdirectionpreference)
- [ListItems](ue_ue.TileView.md#listitems)
- [NativeBindings](ue_ue.TileView.md#nativebindings)
- [Navigation](ue_ue.TileView.md#navigation)
- [NumDesignerPreviewEntries](ue_ue.TileView.md#numdesignerpreviewentries)
- [Orientation](ue_ue.TileView.md#orientation)
- [RenderOpacity](ue_ue.TileView.md#renderopacity)
- [RenderTransform](ue_ue.TileView.md#rendertransform)
- [RenderTransformPivot](ue_ue.TileView.md#rendertransformpivot)
- [SelectionMode](ue_ue.TileView.md#selectionmode)
- [Slot](ue_ue.TileView.md#slot)
- [TileAlignment](ue_ue.TileView.md#tilealignment)
- [ToolTipText](ue_ue.TileView.md#tooltiptext)
- [ToolTipTextDelegate](ue_ue.TileView.md#tooltiptextdelegate)
- [ToolTipWidget](ue_ue.TileView.md#tooltipwidget)
- [ToolTipWidgetDelegate](ue_ue.TileView.md#tooltipwidgetdelegate)
- [Visibility](ue_ue.TileView.md#visibility)
- [VisibilityDelegate](ue_ue.TileView.md#visibilitydelegate)
- [WheelScrollMultiplier](ue_ue.TileView.md#wheelscrollmultiplier)
- [\_\_tid\_ListViewBase\_\_](ue_ue.TileView.md#__tid_listviewbase__)
- [\_\_tid\_ListView\_\_](ue_ue.TileView.md#__tid_listview__)
- [\_\_tid\_Object\_\_](ue_ue.TileView.md#__tid_object__)
- [\_\_tid\_TileView\_\_](ue_ue.TileView.md#__tid_tileview__)
- [\_\_tid\_Visual\_\_](ue_ue.TileView.md#__tid_visual__)
- [\_\_tid\_Widget\_\_](ue_ue.TileView.md#__tid_widget__)
- [bCanChildrenBeAccessible](ue_ue.TileView.md#bcanchildrenbeaccessible)
- [bClearSelectionOnClick](ue_ue.TileView.md#bclearselectiononclick)
- [bCreatedByConstructionScript](ue_ue.TileView.md#bcreatedbyconstructionscript)
- [bEnableFixedLineOffset](ue_ue.TileView.md#benablefixedlineoffset)
- [bEnableScrollAnimation](ue_ue.TileView.md#benablescrollanimation)
- [bExpandedInDesigner](ue_ue.TileView.md#bexpandedindesigner)
- [bHiddenInDesigner](ue_ue.TileView.md#bhiddenindesigner)
- [bIsEnabled](ue_ue.TileView.md#bisenabled)
- [bIsEnabledDelegate](ue_ue.TileView.md#bisenableddelegate)
- [bIsFocusable](ue_ue.TileView.md#bisfocusable)
- [bIsVariable](ue_ue.TileView.md#bisvariable)
- [bIsVolatile](ue_ue.TileView.md#bisvolatile)
- [bLockedInDesigner](ue_ue.TileView.md#blockedindesigner)
- [bOverrideAccessibleDefaults](ue_ue.TileView.md#boverrideaccessibledefaults)
- [bOverride\_Cursor](ue_ue.TileView.md#boverride_cursor)
- [bReturnFocusToSelection](ue_ue.TileView.md#breturnfocustoselection)
- [bWrapHorizontalNavigation](ue_ue.TileView.md#bwraphorizontalnavigation)

### Methods

- [AddItem](ue_ue.TileView.md#additem)
- [BP\_CancelScrollIntoView](ue_ue.TileView.md#bp_cancelscrollintoview)
- [BP\_ClearSelection](ue_ue.TileView.md#bp_clearselection)
- [BP\_GetNumItemsSelected](ue_ue.TileView.md#bp_getnumitemsselected)
- [BP\_GetSelectedItem](ue_ue.TileView.md#bp_getselecteditem)
- [BP\_GetSelectedItems](ue_ue.TileView.md#bp_getselecteditems)
- [BP\_IsItemVisible](ue_ue.TileView.md#bp_isitemvisible)
- [BP\_NavigateToItem](ue_ue.TileView.md#bp_navigatetoitem)
- [BP\_ScrollItemIntoView](ue_ue.TileView.md#bp_scrollitemintoview)
- [BP\_SetItemSelection](ue_ue.TileView.md#bp_setitemselection)
- [BP\_SetListItems](ue_ue.TileView.md#bp_setlistitems)
- [BP\_SetSelectedItem](ue_ue.TileView.md#bp_setselecteditem)
- [ClearListItems](ue_ue.TileView.md#clearlistitems)
- [CreateDefaultSubobject](ue_ue.TileView.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TileView.md#executeubergraph)
- [ForceLayoutPrepass](ue_ue.TileView.md#forcelayoutprepass)
- [ForceVolatile](ue_ue.TileView.md#forcevolatile)
- [GenerateWidgetForObject\_\_DelegateSignature](ue_ue.TileView.md#generatewidgetforobject__delegatesignature)
- [GenerateWidgetForString\_\_DelegateSignature](ue_ue.TileView.md#generatewidgetforstring__delegatesignature)
- [GetBool\_\_DelegateSignature](ue_ue.TileView.md#getbool__delegatesignature)
- [GetCachedGeometry](ue_ue.TileView.md#getcachedgeometry)
- [GetCheckBoxState\_\_DelegateSignature](ue_ue.TileView.md#getcheckboxstate__delegatesignature)
- [GetClass](ue_ue.TileView.md#getclass)
- [GetClipping](ue_ue.TileView.md#getclipping)
- [GetDesiredSize](ue_ue.TileView.md#getdesiredsize)
- [GetDisplayedEntryWidgets](ue_ue.TileView.md#getdisplayedentrywidgets)
- [GetFloat\_\_DelegateSignature](ue_ue.TileView.md#getfloat__delegatesignature)
- [GetGameInstance](ue_ue.TileView.md#getgameinstance)
- [GetIndexForItem](ue_ue.TileView.md#getindexforitem)
- [GetInt32\_\_DelegateSignature](ue_ue.TileView.md#getint32__delegatesignature)
- [GetIsEnabled](ue_ue.TileView.md#getisenabled)
- [GetItemAt](ue_ue.TileView.md#getitemat)
- [GetLinearColor\_\_DelegateSignature](ue_ue.TileView.md#getlinearcolor__delegatesignature)
- [GetListItems](ue_ue.TileView.md#getlistitems)
- [GetMouseCursor\_\_DelegateSignature](ue_ue.TileView.md#getmousecursor__delegatesignature)
- [GetName](ue_ue.TileView.md#getname)
- [GetNumItems](ue_ue.TileView.md#getnumitems)
- [GetOuter](ue_ue.TileView.md#getouter)
- [GetOwningLocalPlayer](ue_ue.TileView.md#getowninglocalplayer)
- [GetOwningPlayer](ue_ue.TileView.md#getowningplayer)
- [GetPaintSpaceGeometry](ue_ue.TileView.md#getpaintspacegeometry)
- [GetParent](ue_ue.TileView.md#getparent)
- [GetRenderOpacity](ue_ue.TileView.md#getrenderopacity)
- [GetRenderTransformAngle](ue_ue.TileView.md#getrendertransformangle)
- [GetSlateBrush\_\_DelegateSignature](ue_ue.TileView.md#getslatebrush__delegatesignature)
- [GetSlateColor\_\_DelegateSignature](ue_ue.TileView.md#getslatecolor__delegatesignature)
- [GetSlateVisibility\_\_DelegateSignature](ue_ue.TileView.md#getslatevisibility__delegatesignature)
- [GetText\_\_DelegateSignature](ue_ue.TileView.md#gettext__delegatesignature)
- [GetTickSpaceGeometry](ue_ue.TileView.md#gettickspacegeometry)
- [GetVisibility](ue_ue.TileView.md#getvisibility)
- [GetWidget\_\_DelegateSignature](ue_ue.TileView.md#getwidget__delegatesignature)
- [GetWorld](ue_ue.TileView.md#getworld)
- [HasAnyUserFocus](ue_ue.TileView.md#hasanyuserfocus)
- [HasFocusedDescendants](ue_ue.TileView.md#hasfocuseddescendants)
- [HasKeyboardFocus](ue_ue.TileView.md#haskeyboardfocus)
- [HasMouseCapture](ue_ue.TileView.md#hasmousecapture)
- [HasMouseCaptureByUser](ue_ue.TileView.md#hasmousecapturebyuser)
- [HasUserFocus](ue_ue.TileView.md#hasuserfocus)
- [HasUserFocusedDescendants](ue_ue.TileView.md#hasuserfocuseddescendants)
- [InvalidateLayoutAndVolatility](ue_ue.TileView.md#invalidatelayoutandvolatility)
- [IsHovered](ue_ue.TileView.md#ishovered)
- [IsRefreshPending](ue_ue.TileView.md#isrefreshpending)
- [IsVisible](ue_ue.TileView.md#isvisible)
- [NavigateToIndex](ue_ue.TileView.md#navigatetoindex)
- [OnPointerEvent\_\_DelegateSignature](ue_ue.TileView.md#onpointerevent__delegatesignature)
- [OnReply\_\_DelegateSignature](ue_ue.TileView.md#onreply__delegatesignature)
- [RegenerateAllEntries](ue_ue.TileView.md#regenerateallentries)
- [RemoveFromParent](ue_ue.TileView.md#removefromparent)
- [RemoveItem](ue_ue.TileView.md#removeitem)
- [RequestRefresh](ue_ue.TileView.md#requestrefresh)
- [ResetCursor](ue_ue.TileView.md#resetcursor)
- [ScrollIndexIntoView](ue_ue.TileView.md#scrollindexintoview)
- [ScrollToBottom](ue_ue.TileView.md#scrolltobottom)
- [ScrollToTop](ue_ue.TileView.md#scrolltotop)
- [SetAllNavigationRules](ue_ue.TileView.md#setallnavigationrules)
- [SetClipping](ue_ue.TileView.md#setclipping)
- [SetCursor](ue_ue.TileView.md#setcursor)
- [SetEntryHeight](ue_ue.TileView.md#setentryheight)
- [SetEntryWidth](ue_ue.TileView.md#setentrywidth)
- [SetFocus](ue_ue.TileView.md#setfocus)
- [SetIsEnabled](ue_ue.TileView.md#setisenabled)
- [SetKeyboardFocus](ue_ue.TileView.md#setkeyboardfocus)
- [SetNavigationRule](ue_ue.TileView.md#setnavigationrule)
- [SetNavigationRuleBase](ue_ue.TileView.md#setnavigationrulebase)
- [SetNavigationRuleCustom](ue_ue.TileView.md#setnavigationrulecustom)
- [SetNavigationRuleCustomBoundary](ue_ue.TileView.md#setnavigationrulecustomboundary)
- [SetNavigationRuleExplicit](ue_ue.TileView.md#setnavigationruleexplicit)
- [SetRenderOpacity](ue_ue.TileView.md#setrenderopacity)
- [SetRenderScale](ue_ue.TileView.md#setrenderscale)
- [SetRenderShear](ue_ue.TileView.md#setrendershear)
- [SetRenderTransform](ue_ue.TileView.md#setrendertransform)
- [SetRenderTransformAngle](ue_ue.TileView.md#setrendertransformangle)
- [SetRenderTransformPivot](ue_ue.TileView.md#setrendertransformpivot)
- [SetRenderTranslation](ue_ue.TileView.md#setrendertranslation)
- [SetScrollOffset](ue_ue.TileView.md#setscrolloffset)
- [SetScrollbarVisibility](ue_ue.TileView.md#setscrollbarvisibility)
- [SetSelectedIndex](ue_ue.TileView.md#setselectedindex)
- [SetSelectionMode](ue_ue.TileView.md#setselectionmode)
- [SetToolTip](ue_ue.TileView.md#settooltip)
- [SetToolTipText](ue_ue.TileView.md#settooltiptext)
- [SetUserFocus](ue_ue.TileView.md#setuserfocus)
- [SetVisibility](ue_ue.TileView.md#setvisibility)
- [SetWheelScrollMultiplier](ue_ue.TileView.md#setwheelscrollmultiplier)
- [Find](ue_ue.TileView.md#find)
- [Load](ue_ue.TileView.md#load)
- [StaticClass](ue_ue.TileView.md#staticclass)

## Constructors

### constructor

• **new TileView**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ListView](ue_ue.ListView.md).[constructor](ue_ue.ListView.md#constructor)

#### Defined in

[ue/ue.d.ts:63525](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63525)

## Properties

### AccessibleBehavior

• **AccessibleBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[AccessibleBehavior](ue_ue.ListView.md#accessiblebehavior)

#### Defined in

[ue/ue.d.ts:10940](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10940)

___

### AccessibleSummaryBehavior

• **AccessibleSummaryBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[AccessibleSummaryBehavior](ue_ue.ListView.md#accessiblesummarybehavior)

#### Defined in

[ue/ue.d.ts:10941](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10941)

___

### AccessibleSummaryText

• **AccessibleSummaryText**: `string`

#### Inherited from

[ListView](ue_ue.ListView.md).[AccessibleSummaryText](ue_ue.ListView.md#accessiblesummarytext)

#### Defined in

[ue/ue.d.ts:10944](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10944)

___

### AccessibleSummaryTextDelegate

• **AccessibleSummaryTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[AccessibleSummaryTextDelegate](ue_ue.ListView.md#accessiblesummarytextdelegate)

#### Defined in

[ue/ue.d.ts:10945](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10945)

___

### AccessibleText

• **AccessibleText**: `string`

#### Inherited from

[ListView](ue_ue.ListView.md).[AccessibleText](ue_ue.ListView.md#accessibletext)

#### Defined in

[ue/ue.d.ts:10942](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10942)

___

### AccessibleTextDelegate

• **AccessibleTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[AccessibleTextDelegate](ue_ue.ListView.md#accessibletextdelegate)

#### Defined in

[ue/ue.d.ts:10943](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10943)

___

### AccessibleWidgetData

• **AccessibleWidgetData**: [`SlateAccessibleWidgetData`](ue_ue.SlateAccessibleWidgetData.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[AccessibleWidgetData](ue_ue.ListView.md#accessiblewidgetdata)

#### Defined in

[ue/ue.d.ts:10946](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10946)

___

### BP\_OnEntryGenerated

• **BP\_OnEntryGenerated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Widget`: [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\>) => `void`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_OnEntryGenerated](ue_ue.ListView.md#bp_onentrygenerated)

#### Defined in

[ue/ue.d.ts:45654](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45654)

___

### BP\_OnEntryInitialized

• **BP\_OnEntryInitialized**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Item`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>, `Widget`: [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\>) => `void`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_OnEntryInitialized](ue_ue.ListView.md#bp_onentryinitialized)

#### Defined in

[ue/ue.d.ts:45683](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45683)

___

### BP\_OnEntryReleased

• **BP\_OnEntryReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Widget`: [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\>) => `void`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_OnEntryReleased](ue_ue.ListView.md#bp_onentryreleased)

#### Defined in

[ue/ue.d.ts:45655](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45655)

___

### BP\_OnItemClicked

• **BP\_OnItemClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Item`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>) => `void`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_OnItemClicked](ue_ue.ListView.md#bp_onitemclicked)

#### Defined in

[ue/ue.d.ts:45684](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45684)

___

### BP\_OnItemDoubleClicked

• **BP\_OnItemDoubleClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Item`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>) => `void`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_OnItemDoubleClicked](ue_ue.ListView.md#bp_onitemdoubleclicked)

#### Defined in

[ue/ue.d.ts:45685](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45685)

___

### BP\_OnItemIsHoveredChanged

• **BP\_OnItemIsHoveredChanged**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Item`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>, `bIsHovered`: `boolean`) => `void`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_OnItemIsHoveredChanged](ue_ue.ListView.md#bp_onitemishoveredchanged)

#### Defined in

[ue/ue.d.ts:45686](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45686)

___

### BP\_OnItemScrolledIntoView

• **BP\_OnItemScrolledIntoView**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Item`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>, `Widget`: [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\>) => `void`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_OnItemScrolledIntoView](ue_ue.ListView.md#bp_onitemscrolledintoview)

#### Defined in

[ue/ue.d.ts:45688](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45688)

___

### BP\_OnItemSelectionChanged

• **BP\_OnItemSelectionChanged**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Item`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>, `bIsSelected`: `boolean`) => `void`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_OnItemSelectionChanged](ue_ue.ListView.md#bp_onitemselectionchanged)

#### Defined in

[ue/ue.d.ts:45687](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45687)

___

### CategoryName

• **CategoryName**: `string`

#### Inherited from

[ListView](ue_ue.ListView.md).[CategoryName](ue_ue.ListView.md#categoryname)

#### Defined in

[ue/ue.d.ts:10960](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10960)

___

### Clipping

• **Clipping**: [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[Clipping](ue_ue.ListView.md#clipping)

#### Defined in

[ue/ue.d.ts:10952](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10952)

___

### ConsumeMouseWheel

• **ConsumeMouseWheel**: [`EConsumeMouseWheel`](../enums/ue_ue.EConsumeMouseWheel.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[ConsumeMouseWheel](ue_ue.ListView.md#consumemousewheel)

#### Defined in

[ue/ue.d.ts:45677](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45677)

___

### Cursor

• **Cursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[Cursor](ue_ue.ListView.md#cursor)

#### Defined in

[ue/ue.d.ts:10951](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10951)

___

### DesignerFlags

• **DesignerFlags**: `number`

#### Inherited from

[ListView](ue_ue.ListView.md).[DesignerFlags](ue_ue.ListView.md#designerflags)

#### Defined in

[ue/ue.d.ts:10958](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10958)

___

### DisplayLabel

• **DisplayLabel**: `string`

#### Inherited from

[ListView](ue_ue.ListView.md).[DisplayLabel](ue_ue.ListView.md#displaylabel)

#### Defined in

[ue/ue.d.ts:10959](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10959)

___

### EntryHeight

• **EntryHeight**: `number`

#### Defined in

[ue/ue.d.ts:63526](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63526)

___

### EntrySpacing

• **EntrySpacing**: `number`

#### Inherited from

[ListView](ue_ue.ListView.md).[EntrySpacing](ue_ue.ListView.md#entryspacing)

#### Defined in

[ue/ue.d.ts:45680](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45680)

___

### EntryWidgetClass

• **EntryWidgetClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[EntryWidgetClass](ue_ue.ListView.md#entrywidgetclass)

#### Defined in

[ue/ue.d.ts:45649](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45649)

___

### EntryWidgetPool

• **EntryWidgetPool**: [`UserWidgetPool`](ue_ue.UserWidgetPool.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[EntryWidgetPool](ue_ue.ListView.md#entrywidgetpool)

#### Defined in

[ue/ue.d.ts:45657](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45657)

___

### EntryWidth

• **EntryWidth**: `number`

#### Defined in

[ue/ue.d.ts:63527](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63527)

___

### FixedLineScrollOffset

• **FixedLineScrollOffset**: `number`

#### Inherited from

[ListView](ue_ue.ListView.md).[FixedLineScrollOffset](ue_ue.ListView.md#fixedlinescrolloffset)

#### Defined in

[ue/ue.d.ts:45653](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45653)

___

### FlowDirectionPreference

• **FlowDirectionPreference**: [`EFlowDirectionPreference`](../enums/ue_ue.EFlowDirectionPreference.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[FlowDirectionPreference](ue_ue.ListView.md#flowdirectionpreference)

#### Defined in

[ue/ue.d.ts:10956](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10956)

___

### ListItems

• **ListItems**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[ListView](ue_ue.ListView.md).[ListItems](ue_ue.ListView.md#listitems)

#### Defined in

[ue/ue.d.ts:45682](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45682)

___

### NativeBindings

• **NativeBindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyBinding`](ue_ue.PropertyBinding.md)\>

#### Inherited from

[ListView](ue_ue.ListView.md).[NativeBindings](ue_ue.ListView.md#nativebindings)

#### Defined in

[ue/ue.d.ts:10957](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10957)

___

### Navigation

• **Navigation**: [`WidgetNavigation`](ue_ue.WidgetNavigation.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[Navigation](ue_ue.ListView.md#navigation)

#### Defined in

[ue/ue.d.ts:10955](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10955)

___

### NumDesignerPreviewEntries

• **NumDesignerPreviewEntries**: `number`

#### Inherited from

[ListView](ue_ue.ListView.md).[NumDesignerPreviewEntries](ue_ue.ListView.md#numdesignerpreviewentries)

#### Defined in

[ue/ue.d.ts:45656](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45656)

___

### Orientation

• **Orientation**: [`EOrientation`](../enums/ue_ue.EOrientation.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[Orientation](ue_ue.ListView.md#orientation)

#### Defined in

[ue/ue.d.ts:45675](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45675)

___

### RenderOpacity

• **RenderOpacity**: `number`

#### Inherited from

[ListView](ue_ue.ListView.md).[RenderOpacity](ue_ue.ListView.md#renderopacity)

#### Defined in

[ue/ue.d.ts:10954](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10954)

___

### RenderTransform

• **RenderTransform**: [`WidgetTransform`](ue_ue.WidgetTransform.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[RenderTransform](ue_ue.ListView.md#rendertransform)

#### Defined in

[ue/ue.d.ts:10932](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10932)

___

### RenderTransformPivot

• **RenderTransformPivot**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[RenderTransformPivot](ue_ue.ListView.md#rendertransformpivot)

#### Defined in

[ue/ue.d.ts:10933](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10933)

___

### SelectionMode

• **SelectionMode**: [`ESelectionMode`](../enums/ue_ue.ESelectionMode.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[SelectionMode](ue_ue.ListView.md#selectionmode)

#### Defined in

[ue/ue.d.ts:45676](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45676)

___

### Slot

• **Slot**: [`PanelSlot`](ue_ue.PanelSlot.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[Slot](ue_ue.ListView.md#slot)

#### Defined in

[ue/ue.d.ts:10925](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10925)

___

### TileAlignment

• **TileAlignment**: [`EListItemAlignment`](../enums/ue_ue.EListItemAlignment.md)

#### Defined in

[ue/ue.d.ts:63528](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63528)

___

### ToolTipText

• **ToolTipText**: `string`

#### Inherited from

[ListView](ue_ue.ListView.md).[ToolTipText](ue_ue.ListView.md#tooltiptext)

#### Defined in

[ue/ue.d.ts:10927](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10927)

___

### ToolTipTextDelegate

• **ToolTipTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[ToolTipTextDelegate](ue_ue.ListView.md#tooltiptextdelegate)

#### Defined in

[ue/ue.d.ts:10928](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10928)

___

### ToolTipWidget

• **ToolTipWidget**: [`Widget`](ue_ue.Widget.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[ToolTipWidget](ue_ue.ListView.md#tooltipwidget)

#### Defined in

[ue/ue.d.ts:10929](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10929)

___

### ToolTipWidgetDelegate

• **ToolTipWidgetDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`Widget`](ue_ue.Widget.md)\>

#### Inherited from

[ListView](ue_ue.ListView.md).[ToolTipWidgetDelegate](ue_ue.ListView.md#tooltipwidgetdelegate)

#### Defined in

[ue/ue.d.ts:10930](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10930)

___

### Visibility

• **Visibility**: [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[Visibility](ue_ue.ListView.md#visibility)

#### Defined in

[ue/ue.d.ts:10953](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10953)

___

### VisibilityDelegate

• **VisibilityDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)\>

#### Inherited from

[ListView](ue_ue.ListView.md).[VisibilityDelegate](ue_ue.ListView.md#visibilitydelegate)

#### Defined in

[ue/ue.d.ts:10931](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10931)

___

### WheelScrollMultiplier

• **WheelScrollMultiplier**: `number`

#### Inherited from

[ListView](ue_ue.ListView.md).[WheelScrollMultiplier](ue_ue.ListView.md#wheelscrollmultiplier)

#### Defined in

[ue/ue.d.ts:45650](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45650)

___

### \_\_tid\_ListViewBase\_\_

• **\_\_tid\_ListViewBase\_\_**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[__tid_ListViewBase__](ue_ue.ListView.md#__tid_listviewbase__)

#### Defined in

[ue/ue.d.ts:45670](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45670)

___

### \_\_tid\_ListView\_\_

• **\_\_tid\_ListView\_\_**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[__tid_ListView__](ue_ue.ListView.md#__tid_listview__)

#### Defined in

[ue/ue.d.ts:45716](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45716)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[__tid_Object__](ue_ue.ListView.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_TileView\_\_

• **\_\_tid\_TileView\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:63536](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63536)

___

### \_\_tid\_Visual\_\_

• **\_\_tid\_Visual\_\_**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[__tid_Visual__](ue_ue.ListView.md#__tid_visual__)

#### Defined in

[ue/ue.d.ts:10673](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10673)

___

### \_\_tid\_Widget\_\_

• **\_\_tid\_Widget\_\_**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[__tid_Widget__](ue_ue.ListView.md#__tid_widget__)

#### Defined in

[ue/ue.d.ts:11029](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11029)

___

### bCanChildrenBeAccessible

• **bCanChildrenBeAccessible**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bCanChildrenBeAccessible](ue_ue.ListView.md#bcanchildrenbeaccessible)

#### Defined in

[ue/ue.d.ts:10939](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10939)

___

### bClearSelectionOnClick

• **bClearSelectionOnClick**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bClearSelectionOnClick](ue_ue.ListView.md#bclearselectiononclick)

#### Defined in

[ue/ue.d.ts:45678](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45678)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bCreatedByConstructionScript](ue_ue.ListView.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:10935](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10935)

___

### bEnableFixedLineOffset

• **bEnableFixedLineOffset**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bEnableFixedLineOffset](ue_ue.ListView.md#benablefixedlineoffset)

#### Defined in

[ue/ue.d.ts:45652](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45652)

___

### bEnableScrollAnimation

• **bEnableScrollAnimation**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bEnableScrollAnimation](ue_ue.ListView.md#benablescrollanimation)

#### Defined in

[ue/ue.d.ts:45651](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45651)

___

### bExpandedInDesigner

• **bExpandedInDesigner**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bExpandedInDesigner](ue_ue.ListView.md#bexpandedindesigner)

#### Defined in

[ue/ue.d.ts:10949](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10949)

___

### bHiddenInDesigner

• **bHiddenInDesigner**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bHiddenInDesigner](ue_ue.ListView.md#bhiddenindesigner)

#### Defined in

[ue/ue.d.ts:10948](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10948)

___

### bIsEnabled

• **bIsEnabled**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bIsEnabled](ue_ue.ListView.md#bisenabled)

#### Defined in

[ue/ue.d.ts:10936](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10936)

___

### bIsEnabledDelegate

• **bIsEnabledDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `boolean`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[bIsEnabledDelegate](ue_ue.ListView.md#bisenableddelegate)

#### Defined in

[ue/ue.d.ts:10926](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10926)

___

### bIsFocusable

• **bIsFocusable**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bIsFocusable](ue_ue.ListView.md#bisfocusable)

#### Defined in

[ue/ue.d.ts:45679](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45679)

___

### bIsVariable

• **bIsVariable**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bIsVariable](ue_ue.ListView.md#bisvariable)

#### Defined in

[ue/ue.d.ts:10934](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10934)

___

### bIsVolatile

• **bIsVolatile**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bIsVolatile](ue_ue.ListView.md#bisvolatile)

#### Defined in

[ue/ue.d.ts:10947](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10947)

___

### bLockedInDesigner

• **bLockedInDesigner**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bLockedInDesigner](ue_ue.ListView.md#blockedindesigner)

#### Defined in

[ue/ue.d.ts:10950](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10950)

___

### bOverrideAccessibleDefaults

• **bOverrideAccessibleDefaults**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bOverrideAccessibleDefaults](ue_ue.ListView.md#boverrideaccessibledefaults)

#### Defined in

[ue/ue.d.ts:10938](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10938)

___

### bOverride\_Cursor

• **bOverride\_Cursor**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bOverride_Cursor](ue_ue.ListView.md#boverride_cursor)

#### Defined in

[ue/ue.d.ts:10937](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10937)

___

### bReturnFocusToSelection

• **bReturnFocusToSelection**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bReturnFocusToSelection](ue_ue.ListView.md#breturnfocustoselection)

#### Defined in

[ue/ue.d.ts:45681](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45681)

___

### bWrapHorizontalNavigation

• **bWrapHorizontalNavigation**: `boolean`

#### Defined in

[ue/ue.d.ts:63529](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63529)

## Methods

### AddItem

▸ **AddItem**(`Item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[AddItem](ue_ue.ListView.md#additem)

#### Defined in

[ue/ue.d.ts:45689](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45689)

___

### BP\_CancelScrollIntoView

▸ **BP_CancelScrollIntoView**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_CancelScrollIntoView](ue_ue.ListView.md#bp_cancelscrollintoview)

#### Defined in

[ue/ue.d.ts:45690](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45690)

___

### BP\_ClearSelection

▸ **BP_ClearSelection**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_ClearSelection](ue_ue.ListView.md#bp_clearselection)

#### Defined in

[ue/ue.d.ts:45691](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45691)

___

### BP\_GetNumItemsSelected

▸ **BP_GetNumItemsSelected**(): `number`

#### Returns

`number`

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_GetNumItemsSelected](ue_ue.ListView.md#bp_getnumitemsselected)

#### Defined in

[ue/ue.d.ts:45692](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45692)

___

### BP\_GetSelectedItem

▸ **BP_GetSelectedItem**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_GetSelectedItem](ue_ue.ListView.md#bp_getselecteditem)

#### Defined in

[ue/ue.d.ts:45693](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45693)

___

### BP\_GetSelectedItems

▸ **BP_GetSelectedItems**(`Items`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Items` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>\> |

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_GetSelectedItems](ue_ue.ListView.md#bp_getselecteditems)

#### Defined in

[ue/ue.d.ts:45694](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45694)

___

### BP\_IsItemVisible

▸ **BP_IsItemVisible**(`Item`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_IsItemVisible](ue_ue.ListView.md#bp_isitemvisible)

#### Defined in

[ue/ue.d.ts:45695](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45695)

___

### BP\_NavigateToItem

▸ **BP_NavigateToItem**(`Item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_NavigateToItem](ue_ue.ListView.md#bp_navigatetoitem)

#### Defined in

[ue/ue.d.ts:45696](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45696)

___

### BP\_ScrollItemIntoView

▸ **BP_ScrollItemIntoView**(`Item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_ScrollItemIntoView](ue_ue.ListView.md#bp_scrollitemintoview)

#### Defined in

[ue/ue.d.ts:45697](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45697)

___

### BP\_SetItemSelection

▸ **BP_SetItemSelection**(`Item`, `bSelected`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `bSelected` | `boolean` |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_SetItemSelection](ue_ue.ListView.md#bp_setitemselection)

#### Defined in

[ue/ue.d.ts:45698](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45698)

___

### BP\_SetListItems

▸ **BP_SetListItems**(`InListItems`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InListItems` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_SetListItems](ue_ue.ListView.md#bp_setlistitems)

#### Defined in

[ue/ue.d.ts:45699](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45699)

___

### BP\_SetSelectedItem

▸ **BP_SetSelectedItem**(`Item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_SetSelectedItem](ue_ue.ListView.md#bp_setselecteditem)

#### Defined in

[ue/ue.d.ts:45700](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45700)

___

### ClearListItems

▸ **ClearListItems**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[ClearListItems](ue_ue.ListView.md#clearlistitems)

#### Defined in

[ue/ue.d.ts:45701](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45701)

___

### CreateDefaultSubobject

▸ **CreateDefaultSubobject**(`p0`, `p1`, `p2`, `p3`, `p4`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `string` |
| `p1` | [`Class`](ue_ue.Class.md) |
| `p2` | [`Class`](ue_ue.Class.md) |
| `p3` | `boolean` |
| `p4` | `boolean` |

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[CreateDefaultSubobject](ue_ue.ListView.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

___

### ExecuteUbergraph

▸ **ExecuteUbergraph**(`EntryPoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EntryPoint` | `number` |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[ExecuteUbergraph](ue_ue.ListView.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### ForceLayoutPrepass

▸ **ForceLayoutPrepass**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[ForceLayoutPrepass](ue_ue.ListView.md#forcelayoutprepass)

#### Defined in

[ue/ue.d.ts:10961](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10961)

___

### ForceVolatile

▸ **ForceVolatile**(`bForce`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bForce` | `boolean` |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[ForceVolatile](ue_ue.ListView.md#forcevolatile)

#### Defined in

[ue/ue.d.ts:10962](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10962)

___

### GenerateWidgetForObject\_\_DelegateSignature

▸ **GenerateWidgetForObject__DelegateSignature**(`Item`): [`Widget`](ue_ue.Widget.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`Widget`](ue_ue.Widget.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GenerateWidgetForObject__DelegateSignature](ue_ue.ListView.md#generatewidgetforobject__delegatesignature)

#### Defined in

[ue/ue.d.ts:10963](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10963)

___

### GenerateWidgetForString\_\_DelegateSignature

▸ **GenerateWidgetForString__DelegateSignature**(`Item`): [`Widget`](ue_ue.Widget.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | `string` |

#### Returns

[`Widget`](ue_ue.Widget.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GenerateWidgetForString__DelegateSignature](ue_ue.ListView.md#generatewidgetforstring__delegatesignature)

#### Defined in

[ue/ue.d.ts:10964](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10964)

___

### GetBool\_\_DelegateSignature

▸ **GetBool__DelegateSignature**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[GetBool__DelegateSignature](ue_ue.ListView.md#getbool__delegatesignature)

#### Defined in

[ue/ue.d.ts:10965](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10965)

___

### GetCachedGeometry

▸ **GetCachedGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetCachedGeometry](ue_ue.ListView.md#getcachedgeometry)

#### Defined in

[ue/ue.d.ts:10966](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10966)

___

### GetCheckBoxState\_\_DelegateSignature

▸ **GetCheckBoxState__DelegateSignature**(): [`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Returns

[`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetCheckBoxState__DelegateSignature](ue_ue.ListView.md#getcheckboxstate__delegatesignature)

#### Defined in

[ue/ue.d.ts:10967](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10967)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetClass](ue_ue.ListView.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetClipping

▸ **GetClipping**(): [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Returns

[`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetClipping](ue_ue.ListView.md#getclipping)

#### Defined in

[ue/ue.d.ts:10968](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10968)

___

### GetDesiredSize

▸ **GetDesiredSize**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetDesiredSize](ue_ue.ListView.md#getdesiredsize)

#### Defined in

[ue/ue.d.ts:10969](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10969)

___

### GetDisplayedEntryWidgets

▸ **GetDisplayedEntryWidgets**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UserWidget`](ue_ue.UserWidget.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`UserWidget`](ue_ue.UserWidget.md)\>

#### Inherited from

[ListView](ue_ue.ListView.md).[GetDisplayedEntryWidgets](ue_ue.ListView.md#getdisplayedentrywidgets)

#### Defined in

[ue/ue.d.ts:45658](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45658)

___

### GetFloat\_\_DelegateSignature

▸ **GetFloat__DelegateSignature**(): `number`

#### Returns

`number`

#### Inherited from

[ListView](ue_ue.ListView.md).[GetFloat__DelegateSignature](ue_ue.ListView.md#getfloat__delegatesignature)

#### Defined in

[ue/ue.d.ts:10970](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10970)

___

### GetGameInstance

▸ **GetGameInstance**(): [`GameInstance`](ue_ue.GameInstance.md)

#### Returns

[`GameInstance`](ue_ue.GameInstance.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetGameInstance](ue_ue.ListView.md#getgameinstance)

#### Defined in

[ue/ue.d.ts:10971](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10971)

___

### GetIndexForItem

▸ **GetIndexForItem**(`Item`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`number`

#### Inherited from

[ListView](ue_ue.ListView.md).[GetIndexForItem](ue_ue.ListView.md#getindexforitem)

#### Defined in

[ue/ue.d.ts:45702](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45702)

___

### GetInt32\_\_DelegateSignature

▸ **GetInt32__DelegateSignature**(): `number`

#### Returns

`number`

#### Inherited from

[ListView](ue_ue.ListView.md).[GetInt32__DelegateSignature](ue_ue.ListView.md#getint32__delegatesignature)

#### Defined in

[ue/ue.d.ts:10972](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10972)

___

### GetIsEnabled

▸ **GetIsEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[GetIsEnabled](ue_ue.ListView.md#getisenabled)

#### Defined in

[ue/ue.d.ts:10973](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10973)

___

### GetItemAt

▸ **GetItemAt**(`Index`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetItemAt](ue_ue.ListView.md#getitemat)

#### Defined in

[ue/ue.d.ts:45703](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45703)

___

### GetLinearColor\_\_DelegateSignature

▸ **GetLinearColor__DelegateSignature**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetLinearColor__DelegateSignature](ue_ue.ListView.md#getlinearcolor__delegatesignature)

#### Defined in

[ue/ue.d.ts:10974](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10974)

___

### GetListItems

▸ **GetListItems**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[ListView](ue_ue.ListView.md).[GetListItems](ue_ue.ListView.md#getlistitems)

#### Defined in

[ue/ue.d.ts:45704](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45704)

___

### GetMouseCursor\_\_DelegateSignature

▸ **GetMouseCursor__DelegateSignature**(): [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Returns

[`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetMouseCursor__DelegateSignature](ue_ue.ListView.md#getmousecursor__delegatesignature)

#### Defined in

[ue/ue.d.ts:10975](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10975)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ListView](ue_ue.ListView.md).[GetName](ue_ue.ListView.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetNumItems

▸ **GetNumItems**(): `number`

#### Returns

`number`

#### Inherited from

[ListView](ue_ue.ListView.md).[GetNumItems](ue_ue.ListView.md#getnumitems)

#### Defined in

[ue/ue.d.ts:45705](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45705)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetOuter](ue_ue.ListView.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetOwningLocalPlayer

▸ **GetOwningLocalPlayer**(): [`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Returns

[`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetOwningLocalPlayer](ue_ue.ListView.md#getowninglocalplayer)

#### Defined in

[ue/ue.d.ts:10976](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10976)

___

### GetOwningPlayer

▸ **GetOwningPlayer**(): [`PlayerController`](ue_ue.PlayerController.md)

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetOwningPlayer](ue_ue.ListView.md#getowningplayer)

#### Defined in

[ue/ue.d.ts:10977](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10977)

___

### GetPaintSpaceGeometry

▸ **GetPaintSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetPaintSpaceGeometry](ue_ue.ListView.md#getpaintspacegeometry)

#### Defined in

[ue/ue.d.ts:10978](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10978)

___

### GetParent

▸ **GetParent**(): [`PanelWidget`](ue_ue.PanelWidget.md)

#### Returns

[`PanelWidget`](ue_ue.PanelWidget.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetParent](ue_ue.ListView.md#getparent)

#### Defined in

[ue/ue.d.ts:10979](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10979)

___

### GetRenderOpacity

▸ **GetRenderOpacity**(): `number`

#### Returns

`number`

#### Inherited from

[ListView](ue_ue.ListView.md).[GetRenderOpacity](ue_ue.ListView.md#getrenderopacity)

#### Defined in

[ue/ue.d.ts:10980](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10980)

___

### GetRenderTransformAngle

▸ **GetRenderTransformAngle**(): `number`

#### Returns

`number`

#### Inherited from

[ListView](ue_ue.ListView.md).[GetRenderTransformAngle](ue_ue.ListView.md#getrendertransformangle)

#### Defined in

[ue/ue.d.ts:10981](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10981)

___

### GetSlateBrush\_\_DelegateSignature

▸ **GetSlateBrush__DelegateSignature**(): [`SlateBrush`](ue_ue.SlateBrush.md)

#### Returns

[`SlateBrush`](ue_ue.SlateBrush.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetSlateBrush__DelegateSignature](ue_ue.ListView.md#getslatebrush__delegatesignature)

#### Defined in

[ue/ue.d.ts:10982](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10982)

___

### GetSlateColor\_\_DelegateSignature

▸ **GetSlateColor__DelegateSignature**(): [`SlateColor`](ue_ue.SlateColor.md)

#### Returns

[`SlateColor`](ue_ue.SlateColor.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetSlateColor__DelegateSignature](ue_ue.ListView.md#getslatecolor__delegatesignature)

#### Defined in

[ue/ue.d.ts:10983](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10983)

___

### GetSlateVisibility\_\_DelegateSignature

▸ **GetSlateVisibility__DelegateSignature**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetSlateVisibility__DelegateSignature](ue_ue.ListView.md#getslatevisibility__delegatesignature)

#### Defined in

[ue/ue.d.ts:10984](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10984)

___

### GetText\_\_DelegateSignature

▸ **GetText__DelegateSignature**(): `string`

#### Returns

`string`

#### Inherited from

[ListView](ue_ue.ListView.md).[GetText__DelegateSignature](ue_ue.ListView.md#gettext__delegatesignature)

#### Defined in

[ue/ue.d.ts:10985](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10985)

___

### GetTickSpaceGeometry

▸ **GetTickSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetTickSpaceGeometry](ue_ue.ListView.md#gettickspacegeometry)

#### Defined in

[ue/ue.d.ts:10986](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10986)

___

### GetVisibility

▸ **GetVisibility**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetVisibility](ue_ue.ListView.md#getvisibility)

#### Defined in

[ue/ue.d.ts:10987](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10987)

___

### GetWidget\_\_DelegateSignature

▸ **GetWidget__DelegateSignature**(): [`Widget`](ue_ue.Widget.md)

#### Returns

[`Widget`](ue_ue.Widget.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetWidget__DelegateSignature](ue_ue.ListView.md#getwidget__delegatesignature)

#### Defined in

[ue/ue.d.ts:10988](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10988)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetWorld](ue_ue.ListView.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### HasAnyUserFocus

▸ **HasAnyUserFocus**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[HasAnyUserFocus](ue_ue.ListView.md#hasanyuserfocus)

#### Defined in

[ue/ue.d.ts:10989](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10989)

___

### HasFocusedDescendants

▸ **HasFocusedDescendants**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[HasFocusedDescendants](ue_ue.ListView.md#hasfocuseddescendants)

#### Defined in

[ue/ue.d.ts:10990](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10990)

___

### HasKeyboardFocus

▸ **HasKeyboardFocus**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[HasKeyboardFocus](ue_ue.ListView.md#haskeyboardfocus)

#### Defined in

[ue/ue.d.ts:10991](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10991)

___

### HasMouseCapture

▸ **HasMouseCapture**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[HasMouseCapture](ue_ue.ListView.md#hasmousecapture)

#### Defined in

[ue/ue.d.ts:10992](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10992)

___

### HasMouseCaptureByUser

▸ **HasMouseCaptureByUser**(`UserIndex`, `PointerIndex?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `UserIndex` | `number` |
| `PointerIndex?` | `number` |

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[HasMouseCaptureByUser](ue_ue.ListView.md#hasmousecapturebyuser)

#### Defined in

[ue/ue.d.ts:10993](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10993)

___

### HasUserFocus

▸ **HasUserFocus**(`PlayerController`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[HasUserFocus](ue_ue.ListView.md#hasuserfocus)

#### Defined in

[ue/ue.d.ts:10994](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10994)

___

### HasUserFocusedDescendants

▸ **HasUserFocusedDescendants**(`PlayerController`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[HasUserFocusedDescendants](ue_ue.ListView.md#hasuserfocuseddescendants)

#### Defined in

[ue/ue.d.ts:10995](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10995)

___

### InvalidateLayoutAndVolatility

▸ **InvalidateLayoutAndVolatility**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[InvalidateLayoutAndVolatility](ue_ue.ListView.md#invalidatelayoutandvolatility)

#### Defined in

[ue/ue.d.ts:10996](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10996)

___

### IsHovered

▸ **IsHovered**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[IsHovered](ue_ue.ListView.md#ishovered)

#### Defined in

[ue/ue.d.ts:10997](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10997)

___

### IsRefreshPending

▸ **IsRefreshPending**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[IsRefreshPending](ue_ue.ListView.md#isrefreshpending)

#### Defined in

[ue/ue.d.ts:45706](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45706)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[IsVisible](ue_ue.ListView.md#isvisible)

#### Defined in

[ue/ue.d.ts:10998](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10998)

___

### NavigateToIndex

▸ **NavigateToIndex**(`Index`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[NavigateToIndex](ue_ue.ListView.md#navigatetoindex)

#### Defined in

[ue/ue.d.ts:45707](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45707)

___

### OnPointerEvent\_\_DelegateSignature

▸ **OnPointerEvent__DelegateSignature**(`MyGeometry`, `MouseEvent`): [`EventReply`](ue_ue.EventReply.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `MouseEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[OnPointerEvent__DelegateSignature](ue_ue.ListView.md#onpointerevent__delegatesignature)

#### Defined in

[ue/ue.d.ts:10999](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10999)

___

### OnReply\_\_DelegateSignature

▸ **OnReply__DelegateSignature**(): [`EventReply`](ue_ue.EventReply.md)

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[OnReply__DelegateSignature](ue_ue.ListView.md#onreply__delegatesignature)

#### Defined in

[ue/ue.d.ts:11000](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11000)

___

### RegenerateAllEntries

▸ **RegenerateAllEntries**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[RegenerateAllEntries](ue_ue.ListView.md#regenerateallentries)

#### Defined in

[ue/ue.d.ts:45659](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45659)

___

### RemoveFromParent

▸ **RemoveFromParent**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[RemoveFromParent](ue_ue.ListView.md#removefromparent)

#### Defined in

[ue/ue.d.ts:11001](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11001)

___

### RemoveItem

▸ **RemoveItem**(`Item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[RemoveItem](ue_ue.ListView.md#removeitem)

#### Defined in

[ue/ue.d.ts:45708](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45708)

___

### RequestRefresh

▸ **RequestRefresh**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[RequestRefresh](ue_ue.ListView.md#requestrefresh)

#### Defined in

[ue/ue.d.ts:45660](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45660)

___

### ResetCursor

▸ **ResetCursor**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[ResetCursor](ue_ue.ListView.md#resetcursor)

#### Defined in

[ue/ue.d.ts:11002](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11002)

___

### ScrollIndexIntoView

▸ **ScrollIndexIntoView**(`Index`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[ScrollIndexIntoView](ue_ue.ListView.md#scrollindexintoview)

#### Defined in

[ue/ue.d.ts:45709](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45709)

___

### ScrollToBottom

▸ **ScrollToBottom**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[ScrollToBottom](ue_ue.ListView.md#scrolltobottom)

#### Defined in

[ue/ue.d.ts:45661](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45661)

___

### ScrollToTop

▸ **ScrollToTop**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[ScrollToTop](ue_ue.ListView.md#scrolltotop)

#### Defined in

[ue/ue.d.ts:45662](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45662)

___

### SetAllNavigationRules

▸ **SetAllNavigationRules**(`Rule`, `WidgetToFocus`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Rule` | [`EUINavigationRule`](../enums/ue_ue.EUINavigationRule.md) |
| `WidgetToFocus` | `string` |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetAllNavigationRules](ue_ue.ListView.md#setallnavigationrules)

#### Defined in

[ue/ue.d.ts:11003](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11003)

___

### SetClipping

▸ **SetClipping**(`InClipping`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InClipping` | [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md) |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetClipping](ue_ue.ListView.md#setclipping)

#### Defined in

[ue/ue.d.ts:11004](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11004)

___

### SetCursor

▸ **SetCursor**(`InCursor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InCursor` | [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md) |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetCursor](ue_ue.ListView.md#setcursor)

#### Defined in

[ue/ue.d.ts:11005](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11005)

___

### SetEntryHeight

▸ **SetEntryHeight**(`NewHeight`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewHeight` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63530](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63530)

___

### SetEntryWidth

▸ **SetEntryWidth**(`NewWidth`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewWidth` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63531](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63531)

___

### SetFocus

▸ **SetFocus**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetFocus](ue_ue.ListView.md#setfocus)

#### Defined in

[ue/ue.d.ts:11006](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11006)

___

### SetIsEnabled

▸ **SetIsEnabled**(`bInIsEnabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInIsEnabled` | `boolean` |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetIsEnabled](ue_ue.ListView.md#setisenabled)

#### Defined in

[ue/ue.d.ts:11007](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11007)

___

### SetKeyboardFocus

▸ **SetKeyboardFocus**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetKeyboardFocus](ue_ue.ListView.md#setkeyboardfocus)

#### Defined in

[ue/ue.d.ts:11008](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11008)

___

### SetNavigationRule

▸ **SetNavigationRule**(`Direction`, `Rule`, `WidgetToFocus`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Direction` | [`EUINavigation`](../enums/ue_ue.EUINavigation.md) |
| `Rule` | [`EUINavigationRule`](../enums/ue_ue.EUINavigationRule.md) |
| `WidgetToFocus` | `string` |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetNavigationRule](ue_ue.ListView.md#setnavigationrule)

#### Defined in

[ue/ue.d.ts:11009](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11009)

___

### SetNavigationRuleBase

▸ **SetNavigationRuleBase**(`Direction`, `Rule`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Direction` | [`EUINavigation`](../enums/ue_ue.EUINavigation.md) |
| `Rule` | [`EUINavigationRule`](../enums/ue_ue.EUINavigationRule.md) |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetNavigationRuleBase](ue_ue.ListView.md#setnavigationrulebase)

#### Defined in

[ue/ue.d.ts:11010](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11010)

___

### SetNavigationRuleCustom

▸ **SetNavigationRuleCustom**(`Direction`, `InCustomDelegate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Direction` | [`EUINavigation`](../enums/ue_ue.EUINavigation.md) |
| `InCustomDelegate` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`Navigation`: [`EUINavigation`](../enums/ue_ue.EUINavigation.md)) => [`Widget`](ue_ue.Widget.md)\> |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetNavigationRuleCustom](ue_ue.ListView.md#setnavigationrulecustom)

#### Defined in

[ue/ue.d.ts:11011](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11011)

___

### SetNavigationRuleCustomBoundary

▸ **SetNavigationRuleCustomBoundary**(`Direction`, `InCustomDelegate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Direction` | [`EUINavigation`](../enums/ue_ue.EUINavigation.md) |
| `InCustomDelegate` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`Navigation`: [`EUINavigation`](../enums/ue_ue.EUINavigation.md)) => [`Widget`](ue_ue.Widget.md)\> |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetNavigationRuleCustomBoundary](ue_ue.ListView.md#setnavigationrulecustomboundary)

#### Defined in

[ue/ue.d.ts:11012](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11012)

___

### SetNavigationRuleExplicit

▸ **SetNavigationRuleExplicit**(`Direction`, `InWidget`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Direction` | [`EUINavigation`](../enums/ue_ue.EUINavigation.md) |
| `InWidget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetNavigationRuleExplicit](ue_ue.ListView.md#setnavigationruleexplicit)

#### Defined in

[ue/ue.d.ts:11013](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11013)

___

### SetRenderOpacity

▸ **SetRenderOpacity**(`InOpacity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InOpacity` | `number` |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetRenderOpacity](ue_ue.ListView.md#setrenderopacity)

#### Defined in

[ue/ue.d.ts:11014](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11014)

___

### SetRenderScale

▸ **SetRenderScale**(`Scale`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetRenderScale](ue_ue.ListView.md#setrenderscale)

#### Defined in

[ue/ue.d.ts:11015](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11015)

___

### SetRenderShear

▸ **SetRenderShear**(`Shear`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Shear` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetRenderShear](ue_ue.ListView.md#setrendershear)

#### Defined in

[ue/ue.d.ts:11016](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11016)

___

### SetRenderTransform

▸ **SetRenderTransform**(`InTransform`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTransform` | [`WidgetTransform`](ue_ue.WidgetTransform.md) |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetRenderTransform](ue_ue.ListView.md#setrendertransform)

#### Defined in

[ue/ue.d.ts:11017](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11017)

___

### SetRenderTransformAngle

▸ **SetRenderTransformAngle**(`Angle`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Angle` | `number` |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetRenderTransformAngle](ue_ue.ListView.md#setrendertransformangle)

#### Defined in

[ue/ue.d.ts:11018](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11018)

___

### SetRenderTransformPivot

▸ **SetRenderTransformPivot**(`Pivot`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Pivot` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetRenderTransformPivot](ue_ue.ListView.md#setrendertransformpivot)

#### Defined in

[ue/ue.d.ts:11019](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11019)

___

### SetRenderTranslation

▸ **SetRenderTranslation**(`Translation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Translation` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetRenderTranslation](ue_ue.ListView.md#setrendertranslation)

#### Defined in

[ue/ue.d.ts:11020](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11020)

___

### SetScrollOffset

▸ **SetScrollOffset**(`InScrollOffset`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InScrollOffset` | `number` |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetScrollOffset](ue_ue.ListView.md#setscrolloffset)

#### Defined in

[ue/ue.d.ts:45664](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45664)

___

### SetScrollbarVisibility

▸ **SetScrollbarVisibility**(`InVisibility`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InVisibility` | [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md) |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetScrollbarVisibility](ue_ue.ListView.md#setscrollbarvisibility)

#### Defined in

[ue/ue.d.ts:45663](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45663)

___

### SetSelectedIndex

▸ **SetSelectedIndex**(`Index`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetSelectedIndex](ue_ue.ListView.md#setselectedindex)

#### Defined in

[ue/ue.d.ts:45710](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45710)

___

### SetSelectionMode

▸ **SetSelectionMode**(`SelectionMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SelectionMode` | [`ESelectionMode`](../enums/ue_ue.ESelectionMode.md) |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetSelectionMode](ue_ue.ListView.md#setselectionmode)

#### Defined in

[ue/ue.d.ts:45711](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45711)

___

### SetToolTip

▸ **SetToolTip**(`Widget`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetToolTip](ue_ue.ListView.md#settooltip)

#### Defined in

[ue/ue.d.ts:11021](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11021)

___

### SetToolTipText

▸ **SetToolTipText**(`InToolTipText`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InToolTipText` | `string` |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetToolTipText](ue_ue.ListView.md#settooltiptext)

#### Defined in

[ue/ue.d.ts:11022](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11022)

___

### SetUserFocus

▸ **SetUserFocus**(`PlayerController`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetUserFocus](ue_ue.ListView.md#setuserfocus)

#### Defined in

[ue/ue.d.ts:11023](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11023)

___

### SetVisibility

▸ **SetVisibility**(`InVisibility`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InVisibility` | [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md) |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetVisibility](ue_ue.ListView.md#setvisibility)

#### Defined in

[ue/ue.d.ts:11024](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11024)

___

### SetWheelScrollMultiplier

▸ **SetWheelScrollMultiplier**(`NewWheelScrollMultiplier`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewWheelScrollMultiplier` | `number` |

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetWheelScrollMultiplier](ue_ue.ListView.md#setwheelscrollmultiplier)

#### Defined in

[ue/ue.d.ts:45665](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45665)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TileView`](ue_ue.TileView.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TileView`](ue_ue.TileView.md)

#### Overrides

[ListView](ue_ue.ListView.md).[Find](ue_ue.ListView.md#find)

#### Defined in

[ue/ue.d.ts:63533](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63533)

___

### Load

▸ `Static` **Load**(`InName`): [`TileView`](ue_ue.TileView.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TileView`](ue_ue.TileView.md)

#### Overrides

[ListView](ue_ue.ListView.md).[Load](ue_ue.ListView.md#load)

#### Defined in

[ue/ue.d.ts:63534](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63534)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ListView](ue_ue.ListView.md).[StaticClass](ue_ue.ListView.md#staticclass)

#### Defined in

[ue/ue.d.ts:63532](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63532)
