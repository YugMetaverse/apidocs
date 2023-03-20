[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ListView

# Class: ListView

[ue/ue](../modules/ue_ue.md).ListView

## Hierarchy

- [`ListViewBase`](ue_ue.ListViewBase.md)

  ↳ **`ListView`**

  ↳↳ [`TileView`](ue_ue.TileView.md)

  ↳↳ [`TreeView`](ue_ue.TreeView.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ListView.md#constructor)

### Properties

- [AccessibleBehavior](ue_ue.ListView.md#accessiblebehavior)
- [AccessibleSummaryBehavior](ue_ue.ListView.md#accessiblesummarybehavior)
- [AccessibleSummaryText](ue_ue.ListView.md#accessiblesummarytext)
- [AccessibleSummaryTextDelegate](ue_ue.ListView.md#accessiblesummarytextdelegate)
- [AccessibleText](ue_ue.ListView.md#accessibletext)
- [AccessibleTextDelegate](ue_ue.ListView.md#accessibletextdelegate)
- [AccessibleWidgetData](ue_ue.ListView.md#accessiblewidgetdata)
- [BP\_OnEntryGenerated](ue_ue.ListView.md#bp_onentrygenerated)
- [BP\_OnEntryInitialized](ue_ue.ListView.md#bp_onentryinitialized)
- [BP\_OnEntryReleased](ue_ue.ListView.md#bp_onentryreleased)
- [BP\_OnItemClicked](ue_ue.ListView.md#bp_onitemclicked)
- [BP\_OnItemDoubleClicked](ue_ue.ListView.md#bp_onitemdoubleclicked)
- [BP\_OnItemIsHoveredChanged](ue_ue.ListView.md#bp_onitemishoveredchanged)
- [BP\_OnItemScrolledIntoView](ue_ue.ListView.md#bp_onitemscrolledintoview)
- [BP\_OnItemSelectionChanged](ue_ue.ListView.md#bp_onitemselectionchanged)
- [CategoryName](ue_ue.ListView.md#categoryname)
- [Clipping](ue_ue.ListView.md#clipping)
- [ConsumeMouseWheel](ue_ue.ListView.md#consumemousewheel)
- [Cursor](ue_ue.ListView.md#cursor)
- [DesignerFlags](ue_ue.ListView.md#designerflags)
- [DisplayLabel](ue_ue.ListView.md#displaylabel)
- [EntrySpacing](ue_ue.ListView.md#entryspacing)
- [EntryWidgetClass](ue_ue.ListView.md#entrywidgetclass)
- [EntryWidgetPool](ue_ue.ListView.md#entrywidgetpool)
- [FixedLineScrollOffset](ue_ue.ListView.md#fixedlinescrolloffset)
- [FlowDirectionPreference](ue_ue.ListView.md#flowdirectionpreference)
- [ListItems](ue_ue.ListView.md#listitems)
- [NativeBindings](ue_ue.ListView.md#nativebindings)
- [Navigation](ue_ue.ListView.md#navigation)
- [NumDesignerPreviewEntries](ue_ue.ListView.md#numdesignerpreviewentries)
- [Orientation](ue_ue.ListView.md#orientation)
- [RenderOpacity](ue_ue.ListView.md#renderopacity)
- [RenderTransform](ue_ue.ListView.md#rendertransform)
- [RenderTransformPivot](ue_ue.ListView.md#rendertransformpivot)
- [SelectionMode](ue_ue.ListView.md#selectionmode)
- [Slot](ue_ue.ListView.md#slot)
- [ToolTipText](ue_ue.ListView.md#tooltiptext)
- [ToolTipTextDelegate](ue_ue.ListView.md#tooltiptextdelegate)
- [ToolTipWidget](ue_ue.ListView.md#tooltipwidget)
- [ToolTipWidgetDelegate](ue_ue.ListView.md#tooltipwidgetdelegate)
- [Visibility](ue_ue.ListView.md#visibility)
- [VisibilityDelegate](ue_ue.ListView.md#visibilitydelegate)
- [WheelScrollMultiplier](ue_ue.ListView.md#wheelscrollmultiplier)
- [\_\_tid\_ListViewBase\_\_](ue_ue.ListView.md#__tid_listviewbase__)
- [\_\_tid\_ListView\_\_](ue_ue.ListView.md#__tid_listview__)
- [\_\_tid\_Object\_\_](ue_ue.ListView.md#__tid_object__)
- [\_\_tid\_Visual\_\_](ue_ue.ListView.md#__tid_visual__)
- [\_\_tid\_Widget\_\_](ue_ue.ListView.md#__tid_widget__)
- [bCanChildrenBeAccessible](ue_ue.ListView.md#bcanchildrenbeaccessible)
- [bClearSelectionOnClick](ue_ue.ListView.md#bclearselectiononclick)
- [bCreatedByConstructionScript](ue_ue.ListView.md#bcreatedbyconstructionscript)
- [bEnableFixedLineOffset](ue_ue.ListView.md#benablefixedlineoffset)
- [bEnableScrollAnimation](ue_ue.ListView.md#benablescrollanimation)
- [bExpandedInDesigner](ue_ue.ListView.md#bexpandedindesigner)
- [bHiddenInDesigner](ue_ue.ListView.md#bhiddenindesigner)
- [bIsEnabled](ue_ue.ListView.md#bisenabled)
- [bIsEnabledDelegate](ue_ue.ListView.md#bisenableddelegate)
- [bIsFocusable](ue_ue.ListView.md#bisfocusable)
- [bIsVariable](ue_ue.ListView.md#bisvariable)
- [bIsVolatile](ue_ue.ListView.md#bisvolatile)
- [bLockedInDesigner](ue_ue.ListView.md#blockedindesigner)
- [bOverrideAccessibleDefaults](ue_ue.ListView.md#boverrideaccessibledefaults)
- [bOverride\_Cursor](ue_ue.ListView.md#boverride_cursor)
- [bReturnFocusToSelection](ue_ue.ListView.md#breturnfocustoselection)

### Methods

- [AddItem](ue_ue.ListView.md#additem)
- [BP\_CancelScrollIntoView](ue_ue.ListView.md#bp_cancelscrollintoview)
- [BP\_ClearSelection](ue_ue.ListView.md#bp_clearselection)
- [BP\_GetNumItemsSelected](ue_ue.ListView.md#bp_getnumitemsselected)
- [BP\_GetSelectedItem](ue_ue.ListView.md#bp_getselecteditem)
- [BP\_GetSelectedItems](ue_ue.ListView.md#bp_getselecteditems)
- [BP\_IsItemVisible](ue_ue.ListView.md#bp_isitemvisible)
- [BP\_NavigateToItem](ue_ue.ListView.md#bp_navigatetoitem)
- [BP\_ScrollItemIntoView](ue_ue.ListView.md#bp_scrollitemintoview)
- [BP\_SetItemSelection](ue_ue.ListView.md#bp_setitemselection)
- [BP\_SetListItems](ue_ue.ListView.md#bp_setlistitems)
- [BP\_SetSelectedItem](ue_ue.ListView.md#bp_setselecteditem)
- [ClearListItems](ue_ue.ListView.md#clearlistitems)
- [CreateDefaultSubobject](ue_ue.ListView.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ListView.md#executeubergraph)
- [ForceLayoutPrepass](ue_ue.ListView.md#forcelayoutprepass)
- [ForceVolatile](ue_ue.ListView.md#forcevolatile)
- [GenerateWidgetForObject\_\_DelegateSignature](ue_ue.ListView.md#generatewidgetforobject__delegatesignature)
- [GenerateWidgetForString\_\_DelegateSignature](ue_ue.ListView.md#generatewidgetforstring__delegatesignature)
- [GetBool\_\_DelegateSignature](ue_ue.ListView.md#getbool__delegatesignature)
- [GetCachedGeometry](ue_ue.ListView.md#getcachedgeometry)
- [GetCheckBoxState\_\_DelegateSignature](ue_ue.ListView.md#getcheckboxstate__delegatesignature)
- [GetClass](ue_ue.ListView.md#getclass)
- [GetClipping](ue_ue.ListView.md#getclipping)
- [GetDesiredSize](ue_ue.ListView.md#getdesiredsize)
- [GetDisplayedEntryWidgets](ue_ue.ListView.md#getdisplayedentrywidgets)
- [GetFloat\_\_DelegateSignature](ue_ue.ListView.md#getfloat__delegatesignature)
- [GetGameInstance](ue_ue.ListView.md#getgameinstance)
- [GetIndexForItem](ue_ue.ListView.md#getindexforitem)
- [GetInt32\_\_DelegateSignature](ue_ue.ListView.md#getint32__delegatesignature)
- [GetIsEnabled](ue_ue.ListView.md#getisenabled)
- [GetItemAt](ue_ue.ListView.md#getitemat)
- [GetLinearColor\_\_DelegateSignature](ue_ue.ListView.md#getlinearcolor__delegatesignature)
- [GetListItems](ue_ue.ListView.md#getlistitems)
- [GetMouseCursor\_\_DelegateSignature](ue_ue.ListView.md#getmousecursor__delegatesignature)
- [GetName](ue_ue.ListView.md#getname)
- [GetNumItems](ue_ue.ListView.md#getnumitems)
- [GetOuter](ue_ue.ListView.md#getouter)
- [GetOwningLocalPlayer](ue_ue.ListView.md#getowninglocalplayer)
- [GetOwningPlayer](ue_ue.ListView.md#getowningplayer)
- [GetPaintSpaceGeometry](ue_ue.ListView.md#getpaintspacegeometry)
- [GetParent](ue_ue.ListView.md#getparent)
- [GetRenderOpacity](ue_ue.ListView.md#getrenderopacity)
- [GetRenderTransformAngle](ue_ue.ListView.md#getrendertransformangle)
- [GetSlateBrush\_\_DelegateSignature](ue_ue.ListView.md#getslatebrush__delegatesignature)
- [GetSlateColor\_\_DelegateSignature](ue_ue.ListView.md#getslatecolor__delegatesignature)
- [GetSlateVisibility\_\_DelegateSignature](ue_ue.ListView.md#getslatevisibility__delegatesignature)
- [GetText\_\_DelegateSignature](ue_ue.ListView.md#gettext__delegatesignature)
- [GetTickSpaceGeometry](ue_ue.ListView.md#gettickspacegeometry)
- [GetVisibility](ue_ue.ListView.md#getvisibility)
- [GetWidget\_\_DelegateSignature](ue_ue.ListView.md#getwidget__delegatesignature)
- [GetWorld](ue_ue.ListView.md#getworld)
- [HasAnyUserFocus](ue_ue.ListView.md#hasanyuserfocus)
- [HasFocusedDescendants](ue_ue.ListView.md#hasfocuseddescendants)
- [HasKeyboardFocus](ue_ue.ListView.md#haskeyboardfocus)
- [HasMouseCapture](ue_ue.ListView.md#hasmousecapture)
- [HasMouseCaptureByUser](ue_ue.ListView.md#hasmousecapturebyuser)
- [HasUserFocus](ue_ue.ListView.md#hasuserfocus)
- [HasUserFocusedDescendants](ue_ue.ListView.md#hasuserfocuseddescendants)
- [InvalidateLayoutAndVolatility](ue_ue.ListView.md#invalidatelayoutandvolatility)
- [IsHovered](ue_ue.ListView.md#ishovered)
- [IsRefreshPending](ue_ue.ListView.md#isrefreshpending)
- [IsVisible](ue_ue.ListView.md#isvisible)
- [NavigateToIndex](ue_ue.ListView.md#navigatetoindex)
- [OnPointerEvent\_\_DelegateSignature](ue_ue.ListView.md#onpointerevent__delegatesignature)
- [OnReply\_\_DelegateSignature](ue_ue.ListView.md#onreply__delegatesignature)
- [RegenerateAllEntries](ue_ue.ListView.md#regenerateallentries)
- [RemoveFromParent](ue_ue.ListView.md#removefromparent)
- [RemoveItem](ue_ue.ListView.md#removeitem)
- [RequestRefresh](ue_ue.ListView.md#requestrefresh)
- [ResetCursor](ue_ue.ListView.md#resetcursor)
- [ScrollIndexIntoView](ue_ue.ListView.md#scrollindexintoview)
- [ScrollToBottom](ue_ue.ListView.md#scrolltobottom)
- [ScrollToTop](ue_ue.ListView.md#scrolltotop)
- [SetAllNavigationRules](ue_ue.ListView.md#setallnavigationrules)
- [SetClipping](ue_ue.ListView.md#setclipping)
- [SetCursor](ue_ue.ListView.md#setcursor)
- [SetFocus](ue_ue.ListView.md#setfocus)
- [SetIsEnabled](ue_ue.ListView.md#setisenabled)
- [SetKeyboardFocus](ue_ue.ListView.md#setkeyboardfocus)
- [SetNavigationRule](ue_ue.ListView.md#setnavigationrule)
- [SetNavigationRuleBase](ue_ue.ListView.md#setnavigationrulebase)
- [SetNavigationRuleCustom](ue_ue.ListView.md#setnavigationrulecustom)
- [SetNavigationRuleCustomBoundary](ue_ue.ListView.md#setnavigationrulecustomboundary)
- [SetNavigationRuleExplicit](ue_ue.ListView.md#setnavigationruleexplicit)
- [SetRenderOpacity](ue_ue.ListView.md#setrenderopacity)
- [SetRenderScale](ue_ue.ListView.md#setrenderscale)
- [SetRenderShear](ue_ue.ListView.md#setrendershear)
- [SetRenderTransform](ue_ue.ListView.md#setrendertransform)
- [SetRenderTransformAngle](ue_ue.ListView.md#setrendertransformangle)
- [SetRenderTransformPivot](ue_ue.ListView.md#setrendertransformpivot)
- [SetRenderTranslation](ue_ue.ListView.md#setrendertranslation)
- [SetScrollOffset](ue_ue.ListView.md#setscrolloffset)
- [SetScrollbarVisibility](ue_ue.ListView.md#setscrollbarvisibility)
- [SetSelectedIndex](ue_ue.ListView.md#setselectedindex)
- [SetSelectionMode](ue_ue.ListView.md#setselectionmode)
- [SetToolTip](ue_ue.ListView.md#settooltip)
- [SetToolTipText](ue_ue.ListView.md#settooltiptext)
- [SetUserFocus](ue_ue.ListView.md#setuserfocus)
- [SetVisibility](ue_ue.ListView.md#setvisibility)
- [SetWheelScrollMultiplier](ue_ue.ListView.md#setwheelscrollmultiplier)
- [Find](ue_ue.ListView.md#find)
- [Load](ue_ue.ListView.md#load)
- [StaticClass](ue_ue.ListView.md#staticclass)

## Constructors

### constructor

• **new ListView**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ListViewBase](ue_ue.ListViewBase.md).[constructor](ue_ue.ListViewBase.md#constructor)

## Properties

### AccessibleBehavior

• **AccessibleBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[AccessibleBehavior](ue_ue.ListViewBase.md#accessiblebehavior)

___

### AccessibleSummaryBehavior

• **AccessibleSummaryBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[AccessibleSummaryBehavior](ue_ue.ListViewBase.md#accessiblesummarybehavior)

___

### AccessibleSummaryText

• **AccessibleSummaryText**: `string`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[AccessibleSummaryText](ue_ue.ListViewBase.md#accessiblesummarytext)

___

### AccessibleSummaryTextDelegate

• **AccessibleSummaryTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[AccessibleSummaryTextDelegate](ue_ue.ListViewBase.md#accessiblesummarytextdelegate)

___

### AccessibleText

• **AccessibleText**: `string`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[AccessibleText](ue_ue.ListViewBase.md#accessibletext)

___

### AccessibleTextDelegate

• **AccessibleTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[AccessibleTextDelegate](ue_ue.ListViewBase.md#accessibletextdelegate)

___

### AccessibleWidgetData

• **AccessibleWidgetData**: [`SlateAccessibleWidgetData`](ue_ue.SlateAccessibleWidgetData.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[AccessibleWidgetData](ue_ue.ListViewBase.md#accessiblewidgetdata)

___

### BP\_OnEntryGenerated

• **BP\_OnEntryGenerated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Widget`: [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\>) => `void`\>

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[BP_OnEntryGenerated](ue_ue.ListViewBase.md#bp_onentrygenerated)

___

### BP\_OnEntryInitialized

• **BP\_OnEntryInitialized**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Item`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>, `Widget`: [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\>) => `void`\>

___

### BP\_OnEntryReleased

• **BP\_OnEntryReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Widget`: [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\>) => `void`\>

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[BP_OnEntryReleased](ue_ue.ListViewBase.md#bp_onentryreleased)

___

### BP\_OnItemClicked

• **BP\_OnItemClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Item`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>) => `void`\>

___

### BP\_OnItemDoubleClicked

• **BP\_OnItemDoubleClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Item`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>) => `void`\>

___

### BP\_OnItemIsHoveredChanged

• **BP\_OnItemIsHoveredChanged**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Item`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>, `bIsHovered`: `boolean`) => `void`\>

___

### BP\_OnItemScrolledIntoView

• **BP\_OnItemScrolledIntoView**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Item`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>, `Widget`: [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\>) => `void`\>

___

### BP\_OnItemSelectionChanged

• **BP\_OnItemSelectionChanged**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Item`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>, `bIsSelected`: `boolean`) => `void`\>

___

### CategoryName

• **CategoryName**: `string`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[CategoryName](ue_ue.ListViewBase.md#categoryname)

___

### Clipping

• **Clipping**: [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[Clipping](ue_ue.ListViewBase.md#clipping)

___

### ConsumeMouseWheel

• **ConsumeMouseWheel**: [`EConsumeMouseWheel`](../enums/ue_ue.EConsumeMouseWheel.md)

___

### Cursor

• **Cursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[Cursor](ue_ue.ListViewBase.md#cursor)

___

### DesignerFlags

• **DesignerFlags**: `number`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[DesignerFlags](ue_ue.ListViewBase.md#designerflags)

___

### DisplayLabel

• **DisplayLabel**: `string`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[DisplayLabel](ue_ue.ListViewBase.md#displaylabel)

___

### EntrySpacing

• **EntrySpacing**: `number`

___

### EntryWidgetClass

• **EntryWidgetClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[EntryWidgetClass](ue_ue.ListViewBase.md#entrywidgetclass)

___

### EntryWidgetPool

• **EntryWidgetPool**: [`UserWidgetPool`](ue_ue.UserWidgetPool.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[EntryWidgetPool](ue_ue.ListViewBase.md#entrywidgetpool)

___

### FixedLineScrollOffset

• **FixedLineScrollOffset**: `number`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[FixedLineScrollOffset](ue_ue.ListViewBase.md#fixedlinescrolloffset)

___

### FlowDirectionPreference

• **FlowDirectionPreference**: [`EFlowDirectionPreference`](../enums/ue_ue.EFlowDirectionPreference.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[FlowDirectionPreference](ue_ue.ListViewBase.md#flowdirectionpreference)

___

### ListItems

• **ListItems**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

___

### NativeBindings

• **NativeBindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyBinding`](ue_ue.PropertyBinding.md)\>

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[NativeBindings](ue_ue.ListViewBase.md#nativebindings)

___

### Navigation

• **Navigation**: [`WidgetNavigation`](ue_ue.WidgetNavigation.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[Navigation](ue_ue.ListViewBase.md#navigation)

___

### NumDesignerPreviewEntries

• **NumDesignerPreviewEntries**: `number`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[NumDesignerPreviewEntries](ue_ue.ListViewBase.md#numdesignerpreviewentries)

___

### Orientation

• **Orientation**: [`EOrientation`](../enums/ue_ue.EOrientation.md)

___

### RenderOpacity

• **RenderOpacity**: `number`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[RenderOpacity](ue_ue.ListViewBase.md#renderopacity)

___

### RenderTransform

• **RenderTransform**: [`WidgetTransform`](ue_ue.WidgetTransform.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[RenderTransform](ue_ue.ListViewBase.md#rendertransform)

___

### RenderTransformPivot

• **RenderTransformPivot**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[RenderTransformPivot](ue_ue.ListViewBase.md#rendertransformpivot)

___

### SelectionMode

• **SelectionMode**: [`ESelectionMode`](../enums/ue_ue.ESelectionMode.md)

___

### Slot

• **Slot**: [`PanelSlot`](ue_ue.PanelSlot.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[Slot](ue_ue.ListViewBase.md#slot)

___

### ToolTipText

• **ToolTipText**: `string`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[ToolTipText](ue_ue.ListViewBase.md#tooltiptext)

___

### ToolTipTextDelegate

• **ToolTipTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[ToolTipTextDelegate](ue_ue.ListViewBase.md#tooltiptextdelegate)

___

### ToolTipWidget

• **ToolTipWidget**: [`Widget`](ue_ue.Widget.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[ToolTipWidget](ue_ue.ListViewBase.md#tooltipwidget)

___

### ToolTipWidgetDelegate

• **ToolTipWidgetDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`Widget`](ue_ue.Widget.md)\>

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[ToolTipWidgetDelegate](ue_ue.ListViewBase.md#tooltipwidgetdelegate)

___

### Visibility

• **Visibility**: [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[Visibility](ue_ue.ListViewBase.md#visibility)

___

### VisibilityDelegate

• **VisibilityDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)\>

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[VisibilityDelegate](ue_ue.ListViewBase.md#visibilitydelegate)

___

### WheelScrollMultiplier

• **WheelScrollMultiplier**: `number`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[WheelScrollMultiplier](ue_ue.ListViewBase.md#wheelscrollmultiplier)

___

### \_\_tid\_ListViewBase\_\_

• **\_\_tid\_ListViewBase\_\_**: `boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[__tid_ListViewBase__](ue_ue.ListViewBase.md#__tid_listviewbase__)

___

### \_\_tid\_ListView\_\_

• **\_\_tid\_ListView\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[__tid_Object__](ue_ue.ListViewBase.md#__tid_object__)

___

### \_\_tid\_Visual\_\_

• **\_\_tid\_Visual\_\_**: `boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[__tid_Visual__](ue_ue.ListViewBase.md#__tid_visual__)

___

### \_\_tid\_Widget\_\_

• **\_\_tid\_Widget\_\_**: `boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[__tid_Widget__](ue_ue.ListViewBase.md#__tid_widget__)

___

### bCanChildrenBeAccessible

• **bCanChildrenBeAccessible**: `boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[bCanChildrenBeAccessible](ue_ue.ListViewBase.md#bcanchildrenbeaccessible)

___

### bClearSelectionOnClick

• **bClearSelectionOnClick**: `boolean`

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[bCreatedByConstructionScript](ue_ue.ListViewBase.md#bcreatedbyconstructionscript)

___

### bEnableFixedLineOffset

• **bEnableFixedLineOffset**: `boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[bEnableFixedLineOffset](ue_ue.ListViewBase.md#benablefixedlineoffset)

___

### bEnableScrollAnimation

• **bEnableScrollAnimation**: `boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[bEnableScrollAnimation](ue_ue.ListViewBase.md#benablescrollanimation)

___

### bExpandedInDesigner

• **bExpandedInDesigner**: `boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[bExpandedInDesigner](ue_ue.ListViewBase.md#bexpandedindesigner)

___

### bHiddenInDesigner

• **bHiddenInDesigner**: `boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[bHiddenInDesigner](ue_ue.ListViewBase.md#bhiddenindesigner)

___

### bIsEnabled

• **bIsEnabled**: `boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[bIsEnabled](ue_ue.ListViewBase.md#bisenabled)

___

### bIsEnabledDelegate

• **bIsEnabledDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `boolean`\>

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[bIsEnabledDelegate](ue_ue.ListViewBase.md#bisenableddelegate)

___

### bIsFocusable

• **bIsFocusable**: `boolean`

___

### bIsVariable

• **bIsVariable**: `boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[bIsVariable](ue_ue.ListViewBase.md#bisvariable)

___

### bIsVolatile

• **bIsVolatile**: `boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[bIsVolatile](ue_ue.ListViewBase.md#bisvolatile)

___

### bLockedInDesigner

• **bLockedInDesigner**: `boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[bLockedInDesigner](ue_ue.ListViewBase.md#blockedindesigner)

___

### bOverrideAccessibleDefaults

• **bOverrideAccessibleDefaults**: `boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[bOverrideAccessibleDefaults](ue_ue.ListViewBase.md#boverrideaccessibledefaults)

___

### bOverride\_Cursor

• **bOverride\_Cursor**: `boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[bOverride_Cursor](ue_ue.ListViewBase.md#boverride_cursor)

___

### bReturnFocusToSelection

• **bReturnFocusToSelection**: `boolean`

## Methods

### AddItem

▸ **AddItem**(`Item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

___

### BP\_CancelScrollIntoView

▸ **BP_CancelScrollIntoView**(): `void`

#### Returns

`void`

___

### BP\_ClearSelection

▸ **BP_ClearSelection**(): `void`

#### Returns

`void`

___

### BP\_GetNumItemsSelected

▸ **BP_GetNumItemsSelected**(): `number`

#### Returns

`number`

___

### BP\_GetSelectedItem

▸ **BP_GetSelectedItem**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

___

### BP\_GetSelectedItems

▸ **BP_GetSelectedItems**(`Items`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Items` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>\> |

#### Returns

`boolean`

___

### BP\_IsItemVisible

▸ **BP_IsItemVisible**(`Item`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`boolean`

___

### BP\_NavigateToItem

▸ **BP_NavigateToItem**(`Item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

___

### BP\_ScrollItemIntoView

▸ **BP_ScrollItemIntoView**(`Item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

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

___

### BP\_SetListItems

▸ **BP_SetListItems**(`InListItems`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InListItems` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

___

### BP\_SetSelectedItem

▸ **BP_SetSelectedItem**(`Item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

___

### ClearListItems

▸ **ClearListItems**(): `void`

#### Returns

`void`

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

[ListViewBase](ue_ue.ListViewBase.md).[CreateDefaultSubobject](ue_ue.ListViewBase.md#createdefaultsubobject)

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

[ListViewBase](ue_ue.ListViewBase.md).[ExecuteUbergraph](ue_ue.ListViewBase.md#executeubergraph)

___

### ForceLayoutPrepass

▸ **ForceLayoutPrepass**(): `void`

#### Returns

`void`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[ForceLayoutPrepass](ue_ue.ListViewBase.md#forcelayoutprepass)

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

[ListViewBase](ue_ue.ListViewBase.md).[ForceVolatile](ue_ue.ListViewBase.md#forcevolatile)

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

[ListViewBase](ue_ue.ListViewBase.md).[GenerateWidgetForObject__DelegateSignature](ue_ue.ListViewBase.md#generatewidgetforobject__delegatesignature)

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

[ListViewBase](ue_ue.ListViewBase.md).[GenerateWidgetForString__DelegateSignature](ue_ue.ListViewBase.md#generatewidgetforstring__delegatesignature)

___

### GetBool\_\_DelegateSignature

▸ **GetBool__DelegateSignature**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetBool__DelegateSignature](ue_ue.ListViewBase.md#getbool__delegatesignature)

___

### GetCachedGeometry

▸ **GetCachedGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetCachedGeometry](ue_ue.ListViewBase.md#getcachedgeometry)

___

### GetCheckBoxState\_\_DelegateSignature

▸ **GetCheckBoxState__DelegateSignature**(): [`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Returns

[`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetCheckBoxState__DelegateSignature](ue_ue.ListViewBase.md#getcheckboxstate__delegatesignature)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetClass](ue_ue.ListViewBase.md#getclass)

___

### GetClipping

▸ **GetClipping**(): [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Returns

[`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetClipping](ue_ue.ListViewBase.md#getclipping)

___

### GetDesiredSize

▸ **GetDesiredSize**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetDesiredSize](ue_ue.ListViewBase.md#getdesiredsize)

___

### GetDisplayedEntryWidgets

▸ **GetDisplayedEntryWidgets**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UserWidget`](ue_ue.UserWidget.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`UserWidget`](ue_ue.UserWidget.md)\>

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetDisplayedEntryWidgets](ue_ue.ListViewBase.md#getdisplayedentrywidgets)

___

### GetFloat\_\_DelegateSignature

▸ **GetFloat__DelegateSignature**(): `number`

#### Returns

`number`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetFloat__DelegateSignature](ue_ue.ListViewBase.md#getfloat__delegatesignature)

___

### GetGameInstance

▸ **GetGameInstance**(): [`GameInstance`](ue_ue.GameInstance.md)

#### Returns

[`GameInstance`](ue_ue.GameInstance.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetGameInstance](ue_ue.ListViewBase.md#getgameinstance)

___

### GetIndexForItem

▸ **GetIndexForItem**(`Item`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`number`

___

### GetInt32\_\_DelegateSignature

▸ **GetInt32__DelegateSignature**(): `number`

#### Returns

`number`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetInt32__DelegateSignature](ue_ue.ListViewBase.md#getint32__delegatesignature)

___

### GetIsEnabled

▸ **GetIsEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetIsEnabled](ue_ue.ListViewBase.md#getisenabled)

___

### GetItemAt

▸ **GetItemAt**(`Index`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

[`Object`](ue_ue.Object.md)

___

### GetLinearColor\_\_DelegateSignature

▸ **GetLinearColor__DelegateSignature**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetLinearColor__DelegateSignature](ue_ue.ListViewBase.md#getlinearcolor__delegatesignature)

___

### GetListItems

▸ **GetListItems**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

___

### GetMouseCursor\_\_DelegateSignature

▸ **GetMouseCursor__DelegateSignature**(): [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Returns

[`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetMouseCursor__DelegateSignature](ue_ue.ListViewBase.md#getmousecursor__delegatesignature)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetName](ue_ue.ListViewBase.md#getname)

___

### GetNumItems

▸ **GetNumItems**(): `number`

#### Returns

`number`

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetOuter](ue_ue.ListViewBase.md#getouter)

___

### GetOwningLocalPlayer

▸ **GetOwningLocalPlayer**(): [`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Returns

[`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetOwningLocalPlayer](ue_ue.ListViewBase.md#getowninglocalplayer)

___

### GetOwningPlayer

▸ **GetOwningPlayer**(): [`PlayerController`](ue_ue.PlayerController.md)

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetOwningPlayer](ue_ue.ListViewBase.md#getowningplayer)

___

### GetPaintSpaceGeometry

▸ **GetPaintSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetPaintSpaceGeometry](ue_ue.ListViewBase.md#getpaintspacegeometry)

___

### GetParent

▸ **GetParent**(): [`PanelWidget`](ue_ue.PanelWidget.md)

#### Returns

[`PanelWidget`](ue_ue.PanelWidget.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetParent](ue_ue.ListViewBase.md#getparent)

___

### GetRenderOpacity

▸ **GetRenderOpacity**(): `number`

#### Returns

`number`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetRenderOpacity](ue_ue.ListViewBase.md#getrenderopacity)

___

### GetRenderTransformAngle

▸ **GetRenderTransformAngle**(): `number`

#### Returns

`number`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetRenderTransformAngle](ue_ue.ListViewBase.md#getrendertransformangle)

___

### GetSlateBrush\_\_DelegateSignature

▸ **GetSlateBrush__DelegateSignature**(): [`SlateBrush`](ue_ue.SlateBrush.md)

#### Returns

[`SlateBrush`](ue_ue.SlateBrush.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetSlateBrush__DelegateSignature](ue_ue.ListViewBase.md#getslatebrush__delegatesignature)

___

### GetSlateColor\_\_DelegateSignature

▸ **GetSlateColor__DelegateSignature**(): [`SlateColor`](ue_ue.SlateColor.md)

#### Returns

[`SlateColor`](ue_ue.SlateColor.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetSlateColor__DelegateSignature](ue_ue.ListViewBase.md#getslatecolor__delegatesignature)

___

### GetSlateVisibility\_\_DelegateSignature

▸ **GetSlateVisibility__DelegateSignature**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetSlateVisibility__DelegateSignature](ue_ue.ListViewBase.md#getslatevisibility__delegatesignature)

___

### GetText\_\_DelegateSignature

▸ **GetText__DelegateSignature**(): `string`

#### Returns

`string`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetText__DelegateSignature](ue_ue.ListViewBase.md#gettext__delegatesignature)

___

### GetTickSpaceGeometry

▸ **GetTickSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetTickSpaceGeometry](ue_ue.ListViewBase.md#gettickspacegeometry)

___

### GetVisibility

▸ **GetVisibility**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetVisibility](ue_ue.ListViewBase.md#getvisibility)

___

### GetWidget\_\_DelegateSignature

▸ **GetWidget__DelegateSignature**(): [`Widget`](ue_ue.Widget.md)

#### Returns

[`Widget`](ue_ue.Widget.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetWidget__DelegateSignature](ue_ue.ListViewBase.md#getwidget__delegatesignature)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[GetWorld](ue_ue.ListViewBase.md#getworld)

___

### HasAnyUserFocus

▸ **HasAnyUserFocus**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[HasAnyUserFocus](ue_ue.ListViewBase.md#hasanyuserfocus)

___

### HasFocusedDescendants

▸ **HasFocusedDescendants**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[HasFocusedDescendants](ue_ue.ListViewBase.md#hasfocuseddescendants)

___

### HasKeyboardFocus

▸ **HasKeyboardFocus**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[HasKeyboardFocus](ue_ue.ListViewBase.md#haskeyboardfocus)

___

### HasMouseCapture

▸ **HasMouseCapture**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[HasMouseCapture](ue_ue.ListViewBase.md#hasmousecapture)

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

[ListViewBase](ue_ue.ListViewBase.md).[HasMouseCaptureByUser](ue_ue.ListViewBase.md#hasmousecapturebyuser)

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

[ListViewBase](ue_ue.ListViewBase.md).[HasUserFocus](ue_ue.ListViewBase.md#hasuserfocus)

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

[ListViewBase](ue_ue.ListViewBase.md).[HasUserFocusedDescendants](ue_ue.ListViewBase.md#hasuserfocuseddescendants)

___

### InvalidateLayoutAndVolatility

▸ **InvalidateLayoutAndVolatility**(): `void`

#### Returns

`void`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[InvalidateLayoutAndVolatility](ue_ue.ListViewBase.md#invalidatelayoutandvolatility)

___

### IsHovered

▸ **IsHovered**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[IsHovered](ue_ue.ListViewBase.md#ishovered)

___

### IsRefreshPending

▸ **IsRefreshPending**(): `boolean`

#### Returns

`boolean`

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[IsVisible](ue_ue.ListViewBase.md#isvisible)

___

### NavigateToIndex

▸ **NavigateToIndex**(`Index`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

`void`

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

[ListViewBase](ue_ue.ListViewBase.md).[OnPointerEvent__DelegateSignature](ue_ue.ListViewBase.md#onpointerevent__delegatesignature)

___

### OnReply\_\_DelegateSignature

▸ **OnReply__DelegateSignature**(): [`EventReply`](ue_ue.EventReply.md)

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[OnReply__DelegateSignature](ue_ue.ListViewBase.md#onreply__delegatesignature)

___

### RegenerateAllEntries

▸ **RegenerateAllEntries**(): `void`

#### Returns

`void`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[RegenerateAllEntries](ue_ue.ListViewBase.md#regenerateallentries)

___

### RemoveFromParent

▸ **RemoveFromParent**(): `void`

#### Returns

`void`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[RemoveFromParent](ue_ue.ListViewBase.md#removefromparent)

___

### RemoveItem

▸ **RemoveItem**(`Item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

___

### RequestRefresh

▸ **RequestRefresh**(): `void`

#### Returns

`void`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[RequestRefresh](ue_ue.ListViewBase.md#requestrefresh)

___

### ResetCursor

▸ **ResetCursor**(): `void`

#### Returns

`void`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[ResetCursor](ue_ue.ListViewBase.md#resetcursor)

___

### ScrollIndexIntoView

▸ **ScrollIndexIntoView**(`Index`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

`void`

___

### ScrollToBottom

▸ **ScrollToBottom**(): `void`

#### Returns

`void`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[ScrollToBottom](ue_ue.ListViewBase.md#scrolltobottom)

___

### ScrollToTop

▸ **ScrollToTop**(): `void`

#### Returns

`void`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[ScrollToTop](ue_ue.ListViewBase.md#scrolltotop)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetAllNavigationRules](ue_ue.ListViewBase.md#setallnavigationrules)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetClipping](ue_ue.ListViewBase.md#setclipping)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetCursor](ue_ue.ListViewBase.md#setcursor)

___

### SetFocus

▸ **SetFocus**(): `void`

#### Returns

`void`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[SetFocus](ue_ue.ListViewBase.md#setfocus)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetIsEnabled](ue_ue.ListViewBase.md#setisenabled)

___

### SetKeyboardFocus

▸ **SetKeyboardFocus**(): `void`

#### Returns

`void`

#### Inherited from

[ListViewBase](ue_ue.ListViewBase.md).[SetKeyboardFocus](ue_ue.ListViewBase.md#setkeyboardfocus)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetNavigationRule](ue_ue.ListViewBase.md#setnavigationrule)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetNavigationRuleBase](ue_ue.ListViewBase.md#setnavigationrulebase)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetNavigationRuleCustom](ue_ue.ListViewBase.md#setnavigationrulecustom)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetNavigationRuleCustomBoundary](ue_ue.ListViewBase.md#setnavigationrulecustomboundary)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetNavigationRuleExplicit](ue_ue.ListViewBase.md#setnavigationruleexplicit)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetRenderOpacity](ue_ue.ListViewBase.md#setrenderopacity)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetRenderScale](ue_ue.ListViewBase.md#setrenderscale)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetRenderShear](ue_ue.ListViewBase.md#setrendershear)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetRenderTransform](ue_ue.ListViewBase.md#setrendertransform)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetRenderTransformAngle](ue_ue.ListViewBase.md#setrendertransformangle)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetRenderTransformPivot](ue_ue.ListViewBase.md#setrendertransformpivot)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetRenderTranslation](ue_ue.ListViewBase.md#setrendertranslation)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetScrollOffset](ue_ue.ListViewBase.md#setscrolloffset)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetScrollbarVisibility](ue_ue.ListViewBase.md#setscrollbarvisibility)

___

### SetSelectedIndex

▸ **SetSelectedIndex**(`Index`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

`void`

___

### SetSelectionMode

▸ **SetSelectionMode**(`SelectionMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SelectionMode` | [`ESelectionMode`](../enums/ue_ue.ESelectionMode.md) |

#### Returns

`void`

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

[ListViewBase](ue_ue.ListViewBase.md).[SetToolTip](ue_ue.ListViewBase.md#settooltip)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetToolTipText](ue_ue.ListViewBase.md#settooltiptext)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetUserFocus](ue_ue.ListViewBase.md#setuserfocus)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetVisibility](ue_ue.ListViewBase.md#setvisibility)

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

[ListViewBase](ue_ue.ListViewBase.md).[SetWheelScrollMultiplier](ue_ue.ListViewBase.md#setwheelscrollmultiplier)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ListView`](ue_ue.ListView.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ListView`](ue_ue.ListView.md)

#### Overrides

[ListViewBase](ue_ue.ListViewBase.md).[Find](ue_ue.ListViewBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ListView`](ue_ue.ListView.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ListView`](ue_ue.ListView.md)

#### Overrides

[ListViewBase](ue_ue.ListViewBase.md).[Load](ue_ue.ListViewBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ListViewBase](ue_ue.ListViewBase.md).[StaticClass](ue_ue.ListViewBase.md#staticclass)
