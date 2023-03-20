[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TreeView

# Class: TreeView

[ue/ue](../modules/ue_ue.md).TreeView

## Hierarchy

- [`ListView`](ue_ue.ListView.md)

  ↳ **`TreeView`**

## Table of contents

### Constructors

- [constructor](ue_ue.TreeView.md#constructor)

### Properties

- [AccessibleBehavior](ue_ue.TreeView.md#accessiblebehavior)
- [AccessibleSummaryBehavior](ue_ue.TreeView.md#accessiblesummarybehavior)
- [AccessibleSummaryText](ue_ue.TreeView.md#accessiblesummarytext)
- [AccessibleSummaryTextDelegate](ue_ue.TreeView.md#accessiblesummarytextdelegate)
- [AccessibleText](ue_ue.TreeView.md#accessibletext)
- [AccessibleTextDelegate](ue_ue.TreeView.md#accessibletextdelegate)
- [AccessibleWidgetData](ue_ue.TreeView.md#accessiblewidgetdata)
- [BP\_OnEntryGenerated](ue_ue.TreeView.md#bp_onentrygenerated)
- [BP\_OnEntryInitialized](ue_ue.TreeView.md#bp_onentryinitialized)
- [BP\_OnEntryReleased](ue_ue.TreeView.md#bp_onentryreleased)
- [BP\_OnGetItemChildren](ue_ue.TreeView.md#bp_ongetitemchildren)
- [BP\_OnItemClicked](ue_ue.TreeView.md#bp_onitemclicked)
- [BP\_OnItemDoubleClicked](ue_ue.TreeView.md#bp_onitemdoubleclicked)
- [BP\_OnItemExpansionChanged](ue_ue.TreeView.md#bp_onitemexpansionchanged)
- [BP\_OnItemIsHoveredChanged](ue_ue.TreeView.md#bp_onitemishoveredchanged)
- [BP\_OnItemScrolledIntoView](ue_ue.TreeView.md#bp_onitemscrolledintoview)
- [BP\_OnItemSelectionChanged](ue_ue.TreeView.md#bp_onitemselectionchanged)
- [CategoryName](ue_ue.TreeView.md#categoryname)
- [Clipping](ue_ue.TreeView.md#clipping)
- [ConsumeMouseWheel](ue_ue.TreeView.md#consumemousewheel)
- [Cursor](ue_ue.TreeView.md#cursor)
- [DesignerFlags](ue_ue.TreeView.md#designerflags)
- [DisplayLabel](ue_ue.TreeView.md#displaylabel)
- [EntrySpacing](ue_ue.TreeView.md#entryspacing)
- [EntryWidgetClass](ue_ue.TreeView.md#entrywidgetclass)
- [EntryWidgetPool](ue_ue.TreeView.md#entrywidgetpool)
- [FixedLineScrollOffset](ue_ue.TreeView.md#fixedlinescrolloffset)
- [FlowDirectionPreference](ue_ue.TreeView.md#flowdirectionpreference)
- [ListItems](ue_ue.TreeView.md#listitems)
- [NativeBindings](ue_ue.TreeView.md#nativebindings)
- [Navigation](ue_ue.TreeView.md#navigation)
- [NumDesignerPreviewEntries](ue_ue.TreeView.md#numdesignerpreviewentries)
- [Orientation](ue_ue.TreeView.md#orientation)
- [RenderOpacity](ue_ue.TreeView.md#renderopacity)
- [RenderTransform](ue_ue.TreeView.md#rendertransform)
- [RenderTransformPivot](ue_ue.TreeView.md#rendertransformpivot)
- [SelectionMode](ue_ue.TreeView.md#selectionmode)
- [Slot](ue_ue.TreeView.md#slot)
- [ToolTipText](ue_ue.TreeView.md#tooltiptext)
- [ToolTipTextDelegate](ue_ue.TreeView.md#tooltiptextdelegate)
- [ToolTipWidget](ue_ue.TreeView.md#tooltipwidget)
- [ToolTipWidgetDelegate](ue_ue.TreeView.md#tooltipwidgetdelegate)
- [Visibility](ue_ue.TreeView.md#visibility)
- [VisibilityDelegate](ue_ue.TreeView.md#visibilitydelegate)
- [WheelScrollMultiplier](ue_ue.TreeView.md#wheelscrollmultiplier)
- [\_\_tid\_ListViewBase\_\_](ue_ue.TreeView.md#__tid_listviewbase__)
- [\_\_tid\_ListView\_\_](ue_ue.TreeView.md#__tid_listview__)
- [\_\_tid\_Object\_\_](ue_ue.TreeView.md#__tid_object__)
- [\_\_tid\_TreeView\_\_](ue_ue.TreeView.md#__tid_treeview__)
- [\_\_tid\_Visual\_\_](ue_ue.TreeView.md#__tid_visual__)
- [\_\_tid\_Widget\_\_](ue_ue.TreeView.md#__tid_widget__)
- [bCanChildrenBeAccessible](ue_ue.TreeView.md#bcanchildrenbeaccessible)
- [bClearSelectionOnClick](ue_ue.TreeView.md#bclearselectiononclick)
- [bCreatedByConstructionScript](ue_ue.TreeView.md#bcreatedbyconstructionscript)
- [bEnableFixedLineOffset](ue_ue.TreeView.md#benablefixedlineoffset)
- [bEnableScrollAnimation](ue_ue.TreeView.md#benablescrollanimation)
- [bExpandedInDesigner](ue_ue.TreeView.md#bexpandedindesigner)
- [bHiddenInDesigner](ue_ue.TreeView.md#bhiddenindesigner)
- [bIsEnabled](ue_ue.TreeView.md#bisenabled)
- [bIsEnabledDelegate](ue_ue.TreeView.md#bisenableddelegate)
- [bIsFocusable](ue_ue.TreeView.md#bisfocusable)
- [bIsVariable](ue_ue.TreeView.md#bisvariable)
- [bIsVolatile](ue_ue.TreeView.md#bisvolatile)
- [bLockedInDesigner](ue_ue.TreeView.md#blockedindesigner)
- [bOverrideAccessibleDefaults](ue_ue.TreeView.md#boverrideaccessibledefaults)
- [bOverride\_Cursor](ue_ue.TreeView.md#boverride_cursor)
- [bReturnFocusToSelection](ue_ue.TreeView.md#breturnfocustoselection)

### Methods

- [AddItem](ue_ue.TreeView.md#additem)
- [BP\_CancelScrollIntoView](ue_ue.TreeView.md#bp_cancelscrollintoview)
- [BP\_ClearSelection](ue_ue.TreeView.md#bp_clearselection)
- [BP\_GetNumItemsSelected](ue_ue.TreeView.md#bp_getnumitemsselected)
- [BP\_GetSelectedItem](ue_ue.TreeView.md#bp_getselecteditem)
- [BP\_GetSelectedItems](ue_ue.TreeView.md#bp_getselecteditems)
- [BP\_IsItemVisible](ue_ue.TreeView.md#bp_isitemvisible)
- [BP\_NavigateToItem](ue_ue.TreeView.md#bp_navigatetoitem)
- [BP\_ScrollItemIntoView](ue_ue.TreeView.md#bp_scrollitemintoview)
- [BP\_SetItemSelection](ue_ue.TreeView.md#bp_setitemselection)
- [BP\_SetListItems](ue_ue.TreeView.md#bp_setlistitems)
- [BP\_SetSelectedItem](ue_ue.TreeView.md#bp_setselecteditem)
- [ClearListItems](ue_ue.TreeView.md#clearlistitems)
- [CollapseAll](ue_ue.TreeView.md#collapseall)
- [CreateDefaultSubobject](ue_ue.TreeView.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TreeView.md#executeubergraph)
- [ExpandAll](ue_ue.TreeView.md#expandall)
- [ForceLayoutPrepass](ue_ue.TreeView.md#forcelayoutprepass)
- [ForceVolatile](ue_ue.TreeView.md#forcevolatile)
- [GenerateWidgetForObject\_\_DelegateSignature](ue_ue.TreeView.md#generatewidgetforobject__delegatesignature)
- [GenerateWidgetForString\_\_DelegateSignature](ue_ue.TreeView.md#generatewidgetforstring__delegatesignature)
- [GetBool\_\_DelegateSignature](ue_ue.TreeView.md#getbool__delegatesignature)
- [GetCachedGeometry](ue_ue.TreeView.md#getcachedgeometry)
- [GetCheckBoxState\_\_DelegateSignature](ue_ue.TreeView.md#getcheckboxstate__delegatesignature)
- [GetClass](ue_ue.TreeView.md#getclass)
- [GetClipping](ue_ue.TreeView.md#getclipping)
- [GetDesiredSize](ue_ue.TreeView.md#getdesiredsize)
- [GetDisplayedEntryWidgets](ue_ue.TreeView.md#getdisplayedentrywidgets)
- [GetFloat\_\_DelegateSignature](ue_ue.TreeView.md#getfloat__delegatesignature)
- [GetGameInstance](ue_ue.TreeView.md#getgameinstance)
- [GetIndexForItem](ue_ue.TreeView.md#getindexforitem)
- [GetInt32\_\_DelegateSignature](ue_ue.TreeView.md#getint32__delegatesignature)
- [GetIsEnabled](ue_ue.TreeView.md#getisenabled)
- [GetItemAt](ue_ue.TreeView.md#getitemat)
- [GetLinearColor\_\_DelegateSignature](ue_ue.TreeView.md#getlinearcolor__delegatesignature)
- [GetListItems](ue_ue.TreeView.md#getlistitems)
- [GetMouseCursor\_\_DelegateSignature](ue_ue.TreeView.md#getmousecursor__delegatesignature)
- [GetName](ue_ue.TreeView.md#getname)
- [GetNumItems](ue_ue.TreeView.md#getnumitems)
- [GetOuter](ue_ue.TreeView.md#getouter)
- [GetOwningLocalPlayer](ue_ue.TreeView.md#getowninglocalplayer)
- [GetOwningPlayer](ue_ue.TreeView.md#getowningplayer)
- [GetPaintSpaceGeometry](ue_ue.TreeView.md#getpaintspacegeometry)
- [GetParent](ue_ue.TreeView.md#getparent)
- [GetRenderOpacity](ue_ue.TreeView.md#getrenderopacity)
- [GetRenderTransformAngle](ue_ue.TreeView.md#getrendertransformangle)
- [GetSlateBrush\_\_DelegateSignature](ue_ue.TreeView.md#getslatebrush__delegatesignature)
- [GetSlateColor\_\_DelegateSignature](ue_ue.TreeView.md#getslatecolor__delegatesignature)
- [GetSlateVisibility\_\_DelegateSignature](ue_ue.TreeView.md#getslatevisibility__delegatesignature)
- [GetText\_\_DelegateSignature](ue_ue.TreeView.md#gettext__delegatesignature)
- [GetTickSpaceGeometry](ue_ue.TreeView.md#gettickspacegeometry)
- [GetVisibility](ue_ue.TreeView.md#getvisibility)
- [GetWidget\_\_DelegateSignature](ue_ue.TreeView.md#getwidget__delegatesignature)
- [GetWorld](ue_ue.TreeView.md#getworld)
- [HasAnyUserFocus](ue_ue.TreeView.md#hasanyuserfocus)
- [HasFocusedDescendants](ue_ue.TreeView.md#hasfocuseddescendants)
- [HasKeyboardFocus](ue_ue.TreeView.md#haskeyboardfocus)
- [HasMouseCapture](ue_ue.TreeView.md#hasmousecapture)
- [HasMouseCaptureByUser](ue_ue.TreeView.md#hasmousecapturebyuser)
- [HasUserFocus](ue_ue.TreeView.md#hasuserfocus)
- [HasUserFocusedDescendants](ue_ue.TreeView.md#hasuserfocuseddescendants)
- [InvalidateLayoutAndVolatility](ue_ue.TreeView.md#invalidatelayoutandvolatility)
- [IsHovered](ue_ue.TreeView.md#ishovered)
- [IsRefreshPending](ue_ue.TreeView.md#isrefreshpending)
- [IsVisible](ue_ue.TreeView.md#isvisible)
- [NavigateToIndex](ue_ue.TreeView.md#navigatetoindex)
- [OnPointerEvent\_\_DelegateSignature](ue_ue.TreeView.md#onpointerevent__delegatesignature)
- [OnReply\_\_DelegateSignature](ue_ue.TreeView.md#onreply__delegatesignature)
- [RegenerateAllEntries](ue_ue.TreeView.md#regenerateallentries)
- [RemoveFromParent](ue_ue.TreeView.md#removefromparent)
- [RemoveItem](ue_ue.TreeView.md#removeitem)
- [RequestRefresh](ue_ue.TreeView.md#requestrefresh)
- [ResetCursor](ue_ue.TreeView.md#resetcursor)
- [ScrollIndexIntoView](ue_ue.TreeView.md#scrollindexintoview)
- [ScrollToBottom](ue_ue.TreeView.md#scrolltobottom)
- [ScrollToTop](ue_ue.TreeView.md#scrolltotop)
- [SetAllNavigationRules](ue_ue.TreeView.md#setallnavigationrules)
- [SetClipping](ue_ue.TreeView.md#setclipping)
- [SetCursor](ue_ue.TreeView.md#setcursor)
- [SetFocus](ue_ue.TreeView.md#setfocus)
- [SetIsEnabled](ue_ue.TreeView.md#setisenabled)
- [SetItemExpansion](ue_ue.TreeView.md#setitemexpansion)
- [SetKeyboardFocus](ue_ue.TreeView.md#setkeyboardfocus)
- [SetNavigationRule](ue_ue.TreeView.md#setnavigationrule)
- [SetNavigationRuleBase](ue_ue.TreeView.md#setnavigationrulebase)
- [SetNavigationRuleCustom](ue_ue.TreeView.md#setnavigationrulecustom)
- [SetNavigationRuleCustomBoundary](ue_ue.TreeView.md#setnavigationrulecustomboundary)
- [SetNavigationRuleExplicit](ue_ue.TreeView.md#setnavigationruleexplicit)
- [SetRenderOpacity](ue_ue.TreeView.md#setrenderopacity)
- [SetRenderScale](ue_ue.TreeView.md#setrenderscale)
- [SetRenderShear](ue_ue.TreeView.md#setrendershear)
- [SetRenderTransform](ue_ue.TreeView.md#setrendertransform)
- [SetRenderTransformAngle](ue_ue.TreeView.md#setrendertransformangle)
- [SetRenderTransformPivot](ue_ue.TreeView.md#setrendertransformpivot)
- [SetRenderTranslation](ue_ue.TreeView.md#setrendertranslation)
- [SetScrollOffset](ue_ue.TreeView.md#setscrolloffset)
- [SetScrollbarVisibility](ue_ue.TreeView.md#setscrollbarvisibility)
- [SetSelectedIndex](ue_ue.TreeView.md#setselectedindex)
- [SetSelectionMode](ue_ue.TreeView.md#setselectionmode)
- [SetToolTip](ue_ue.TreeView.md#settooltip)
- [SetToolTipText](ue_ue.TreeView.md#settooltiptext)
- [SetUserFocus](ue_ue.TreeView.md#setuserfocus)
- [SetVisibility](ue_ue.TreeView.md#setvisibility)
- [SetWheelScrollMultiplier](ue_ue.TreeView.md#setwheelscrollmultiplier)
- [Find](ue_ue.TreeView.md#find)
- [Load](ue_ue.TreeView.md#load)
- [StaticClass](ue_ue.TreeView.md#staticclass)

## Constructors

### constructor

• **new TreeView**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ListView](ue_ue.ListView.md).[constructor](ue_ue.ListView.md#constructor)

## Properties

### AccessibleBehavior

• **AccessibleBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[AccessibleBehavior](ue_ue.ListView.md#accessiblebehavior)

___

### AccessibleSummaryBehavior

• **AccessibleSummaryBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[AccessibleSummaryBehavior](ue_ue.ListView.md#accessiblesummarybehavior)

___

### AccessibleSummaryText

• **AccessibleSummaryText**: `string`

#### Inherited from

[ListView](ue_ue.ListView.md).[AccessibleSummaryText](ue_ue.ListView.md#accessiblesummarytext)

___

### AccessibleSummaryTextDelegate

• **AccessibleSummaryTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[AccessibleSummaryTextDelegate](ue_ue.ListView.md#accessiblesummarytextdelegate)

___

### AccessibleText

• **AccessibleText**: `string`

#### Inherited from

[ListView](ue_ue.ListView.md).[AccessibleText](ue_ue.ListView.md#accessibletext)

___

### AccessibleTextDelegate

• **AccessibleTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[AccessibleTextDelegate](ue_ue.ListView.md#accessibletextdelegate)

___

### AccessibleWidgetData

• **AccessibleWidgetData**: [`SlateAccessibleWidgetData`](ue_ue.SlateAccessibleWidgetData.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[AccessibleWidgetData](ue_ue.ListView.md#accessiblewidgetdata)

___

### BP\_OnEntryGenerated

• **BP\_OnEntryGenerated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Widget`: [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\>) => `void`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_OnEntryGenerated](ue_ue.ListView.md#bp_onentrygenerated)

___

### BP\_OnEntryInitialized

• **BP\_OnEntryInitialized**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Item`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>, `Widget`: [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\>) => `void`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_OnEntryInitialized](ue_ue.ListView.md#bp_onentryinitialized)

___

### BP\_OnEntryReleased

• **BP\_OnEntryReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Widget`: [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\>) => `void`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_OnEntryReleased](ue_ue.ListView.md#bp_onentryreleased)

___

### BP\_OnGetItemChildren

• **BP\_OnGetItemChildren**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`Item`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>, `Children`: [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>\>) => `void`\>

___

### BP\_OnItemClicked

• **BP\_OnItemClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Item`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>) => `void`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_OnItemClicked](ue_ue.ListView.md#bp_onitemclicked)

___

### BP\_OnItemDoubleClicked

• **BP\_OnItemDoubleClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Item`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>) => `void`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_OnItemDoubleClicked](ue_ue.ListView.md#bp_onitemdoubleclicked)

___

### BP\_OnItemExpansionChanged

• **BP\_OnItemExpansionChanged**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Item`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>, `bIsExpanded`: `boolean`) => `void`\>

___

### BP\_OnItemIsHoveredChanged

• **BP\_OnItemIsHoveredChanged**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Item`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>, `bIsHovered`: `boolean`) => `void`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_OnItemIsHoveredChanged](ue_ue.ListView.md#bp_onitemishoveredchanged)

___

### BP\_OnItemScrolledIntoView

• **BP\_OnItemScrolledIntoView**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Item`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>, `Widget`: [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\>) => `void`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_OnItemScrolledIntoView](ue_ue.ListView.md#bp_onitemscrolledintoview)

___

### BP\_OnItemSelectionChanged

• **BP\_OnItemSelectionChanged**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Item`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>, `bIsSelected`: `boolean`) => `void`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_OnItemSelectionChanged](ue_ue.ListView.md#bp_onitemselectionchanged)

___

### CategoryName

• **CategoryName**: `string`

#### Inherited from

[ListView](ue_ue.ListView.md).[CategoryName](ue_ue.ListView.md#categoryname)

___

### Clipping

• **Clipping**: [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[Clipping](ue_ue.ListView.md#clipping)

___

### ConsumeMouseWheel

• **ConsumeMouseWheel**: [`EConsumeMouseWheel`](../enums/ue_ue.EConsumeMouseWheel.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[ConsumeMouseWheel](ue_ue.ListView.md#consumemousewheel)

___

### Cursor

• **Cursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[Cursor](ue_ue.ListView.md#cursor)

___

### DesignerFlags

• **DesignerFlags**: `number`

#### Inherited from

[ListView](ue_ue.ListView.md).[DesignerFlags](ue_ue.ListView.md#designerflags)

___

### DisplayLabel

• **DisplayLabel**: `string`

#### Inherited from

[ListView](ue_ue.ListView.md).[DisplayLabel](ue_ue.ListView.md#displaylabel)

___

### EntrySpacing

• **EntrySpacing**: `number`

#### Inherited from

[ListView](ue_ue.ListView.md).[EntrySpacing](ue_ue.ListView.md#entryspacing)

___

### EntryWidgetClass

• **EntryWidgetClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[EntryWidgetClass](ue_ue.ListView.md#entrywidgetclass)

___

### EntryWidgetPool

• **EntryWidgetPool**: [`UserWidgetPool`](ue_ue.UserWidgetPool.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[EntryWidgetPool](ue_ue.ListView.md#entrywidgetpool)

___

### FixedLineScrollOffset

• **FixedLineScrollOffset**: `number`

#### Inherited from

[ListView](ue_ue.ListView.md).[FixedLineScrollOffset](ue_ue.ListView.md#fixedlinescrolloffset)

___

### FlowDirectionPreference

• **FlowDirectionPreference**: [`EFlowDirectionPreference`](../enums/ue_ue.EFlowDirectionPreference.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[FlowDirectionPreference](ue_ue.ListView.md#flowdirectionpreference)

___

### ListItems

• **ListItems**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[ListView](ue_ue.ListView.md).[ListItems](ue_ue.ListView.md#listitems)

___

### NativeBindings

• **NativeBindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyBinding`](ue_ue.PropertyBinding.md)\>

#### Inherited from

[ListView](ue_ue.ListView.md).[NativeBindings](ue_ue.ListView.md#nativebindings)

___

### Navigation

• **Navigation**: [`WidgetNavigation`](ue_ue.WidgetNavigation.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[Navigation](ue_ue.ListView.md#navigation)

___

### NumDesignerPreviewEntries

• **NumDesignerPreviewEntries**: `number`

#### Inherited from

[ListView](ue_ue.ListView.md).[NumDesignerPreviewEntries](ue_ue.ListView.md#numdesignerpreviewentries)

___

### Orientation

• **Orientation**: [`EOrientation`](../enums/ue_ue.EOrientation.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[Orientation](ue_ue.ListView.md#orientation)

___

### RenderOpacity

• **RenderOpacity**: `number`

#### Inherited from

[ListView](ue_ue.ListView.md).[RenderOpacity](ue_ue.ListView.md#renderopacity)

___

### RenderTransform

• **RenderTransform**: [`WidgetTransform`](ue_ue.WidgetTransform.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[RenderTransform](ue_ue.ListView.md#rendertransform)

___

### RenderTransformPivot

• **RenderTransformPivot**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[RenderTransformPivot](ue_ue.ListView.md#rendertransformpivot)

___

### SelectionMode

• **SelectionMode**: [`ESelectionMode`](../enums/ue_ue.ESelectionMode.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[SelectionMode](ue_ue.ListView.md#selectionmode)

___

### Slot

• **Slot**: [`PanelSlot`](ue_ue.PanelSlot.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[Slot](ue_ue.ListView.md#slot)

___

### ToolTipText

• **ToolTipText**: `string`

#### Inherited from

[ListView](ue_ue.ListView.md).[ToolTipText](ue_ue.ListView.md#tooltiptext)

___

### ToolTipTextDelegate

• **ToolTipTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[ToolTipTextDelegate](ue_ue.ListView.md#tooltiptextdelegate)

___

### ToolTipWidget

• **ToolTipWidget**: [`Widget`](ue_ue.Widget.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[ToolTipWidget](ue_ue.ListView.md#tooltipwidget)

___

### ToolTipWidgetDelegate

• **ToolTipWidgetDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`Widget`](ue_ue.Widget.md)\>

#### Inherited from

[ListView](ue_ue.ListView.md).[ToolTipWidgetDelegate](ue_ue.ListView.md#tooltipwidgetdelegate)

___

### Visibility

• **Visibility**: [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[Visibility](ue_ue.ListView.md#visibility)

___

### VisibilityDelegate

• **VisibilityDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)\>

#### Inherited from

[ListView](ue_ue.ListView.md).[VisibilityDelegate](ue_ue.ListView.md#visibilitydelegate)

___

### WheelScrollMultiplier

• **WheelScrollMultiplier**: `number`

#### Inherited from

[ListView](ue_ue.ListView.md).[WheelScrollMultiplier](ue_ue.ListView.md#wheelscrollmultiplier)

___

### \_\_tid\_ListViewBase\_\_

• **\_\_tid\_ListViewBase\_\_**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[__tid_ListViewBase__](ue_ue.ListView.md#__tid_listviewbase__)

___

### \_\_tid\_ListView\_\_

• **\_\_tid\_ListView\_\_**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[__tid_ListView__](ue_ue.ListView.md#__tid_listview__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[__tid_Object__](ue_ue.ListView.md#__tid_object__)

___

### \_\_tid\_TreeView\_\_

• **\_\_tid\_TreeView\_\_**: `boolean`

___

### \_\_tid\_Visual\_\_

• **\_\_tid\_Visual\_\_**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[__tid_Visual__](ue_ue.ListView.md#__tid_visual__)

___

### \_\_tid\_Widget\_\_

• **\_\_tid\_Widget\_\_**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[__tid_Widget__](ue_ue.ListView.md#__tid_widget__)

___

### bCanChildrenBeAccessible

• **bCanChildrenBeAccessible**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bCanChildrenBeAccessible](ue_ue.ListView.md#bcanchildrenbeaccessible)

___

### bClearSelectionOnClick

• **bClearSelectionOnClick**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bClearSelectionOnClick](ue_ue.ListView.md#bclearselectiononclick)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bCreatedByConstructionScript](ue_ue.ListView.md#bcreatedbyconstructionscript)

___

### bEnableFixedLineOffset

• **bEnableFixedLineOffset**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bEnableFixedLineOffset](ue_ue.ListView.md#benablefixedlineoffset)

___

### bEnableScrollAnimation

• **bEnableScrollAnimation**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bEnableScrollAnimation](ue_ue.ListView.md#benablescrollanimation)

___

### bExpandedInDesigner

• **bExpandedInDesigner**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bExpandedInDesigner](ue_ue.ListView.md#bexpandedindesigner)

___

### bHiddenInDesigner

• **bHiddenInDesigner**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bHiddenInDesigner](ue_ue.ListView.md#bhiddenindesigner)

___

### bIsEnabled

• **bIsEnabled**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bIsEnabled](ue_ue.ListView.md#bisenabled)

___

### bIsEnabledDelegate

• **bIsEnabledDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `boolean`\>

#### Inherited from

[ListView](ue_ue.ListView.md).[bIsEnabledDelegate](ue_ue.ListView.md#bisenableddelegate)

___

### bIsFocusable

• **bIsFocusable**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bIsFocusable](ue_ue.ListView.md#bisfocusable)

___

### bIsVariable

• **bIsVariable**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bIsVariable](ue_ue.ListView.md#bisvariable)

___

### bIsVolatile

• **bIsVolatile**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bIsVolatile](ue_ue.ListView.md#bisvolatile)

___

### bLockedInDesigner

• **bLockedInDesigner**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bLockedInDesigner](ue_ue.ListView.md#blockedindesigner)

___

### bOverrideAccessibleDefaults

• **bOverrideAccessibleDefaults**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bOverrideAccessibleDefaults](ue_ue.ListView.md#boverrideaccessibledefaults)

___

### bOverride\_Cursor

• **bOverride\_Cursor**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bOverride_Cursor](ue_ue.ListView.md#boverride_cursor)

___

### bReturnFocusToSelection

• **bReturnFocusToSelection**: `boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[bReturnFocusToSelection](ue_ue.ListView.md#breturnfocustoselection)

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

___

### BP\_CancelScrollIntoView

▸ **BP_CancelScrollIntoView**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_CancelScrollIntoView](ue_ue.ListView.md#bp_cancelscrollintoview)

___

### BP\_ClearSelection

▸ **BP_ClearSelection**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_ClearSelection](ue_ue.ListView.md#bp_clearselection)

___

### BP\_GetNumItemsSelected

▸ **BP_GetNumItemsSelected**(): `number`

#### Returns

`number`

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_GetNumItemsSelected](ue_ue.ListView.md#bp_getnumitemsselected)

___

### BP\_GetSelectedItem

▸ **BP_GetSelectedItem**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[BP_GetSelectedItem](ue_ue.ListView.md#bp_getselecteditem)

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

___

### ClearListItems

▸ **ClearListItems**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[ClearListItems](ue_ue.ListView.md#clearlistitems)

___

### CollapseAll

▸ **CollapseAll**(): `void`

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

[ListView](ue_ue.ListView.md).[CreateDefaultSubobject](ue_ue.ListView.md#createdefaultsubobject)

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

___

### ExpandAll

▸ **ExpandAll**(): `void`

#### Returns

`void`

___

### ForceLayoutPrepass

▸ **ForceLayoutPrepass**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[ForceLayoutPrepass](ue_ue.ListView.md#forcelayoutprepass)

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

___

### GetBool\_\_DelegateSignature

▸ **GetBool__DelegateSignature**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[GetBool__DelegateSignature](ue_ue.ListView.md#getbool__delegatesignature)

___

### GetCachedGeometry

▸ **GetCachedGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetCachedGeometry](ue_ue.ListView.md#getcachedgeometry)

___

### GetCheckBoxState\_\_DelegateSignature

▸ **GetCheckBoxState__DelegateSignature**(): [`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Returns

[`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetCheckBoxState__DelegateSignature](ue_ue.ListView.md#getcheckboxstate__delegatesignature)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetClass](ue_ue.ListView.md#getclass)

___

### GetClipping

▸ **GetClipping**(): [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Returns

[`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetClipping](ue_ue.ListView.md#getclipping)

___

### GetDesiredSize

▸ **GetDesiredSize**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetDesiredSize](ue_ue.ListView.md#getdesiredsize)

___

### GetDisplayedEntryWidgets

▸ **GetDisplayedEntryWidgets**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UserWidget`](ue_ue.UserWidget.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`UserWidget`](ue_ue.UserWidget.md)\>

#### Inherited from

[ListView](ue_ue.ListView.md).[GetDisplayedEntryWidgets](ue_ue.ListView.md#getdisplayedentrywidgets)

___

### GetFloat\_\_DelegateSignature

▸ **GetFloat__DelegateSignature**(): `number`

#### Returns

`number`

#### Inherited from

[ListView](ue_ue.ListView.md).[GetFloat__DelegateSignature](ue_ue.ListView.md#getfloat__delegatesignature)

___

### GetGameInstance

▸ **GetGameInstance**(): [`GameInstance`](ue_ue.GameInstance.md)

#### Returns

[`GameInstance`](ue_ue.GameInstance.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetGameInstance](ue_ue.ListView.md#getgameinstance)

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

___

### GetInt32\_\_DelegateSignature

▸ **GetInt32__DelegateSignature**(): `number`

#### Returns

`number`

#### Inherited from

[ListView](ue_ue.ListView.md).[GetInt32__DelegateSignature](ue_ue.ListView.md#getint32__delegatesignature)

___

### GetIsEnabled

▸ **GetIsEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[GetIsEnabled](ue_ue.ListView.md#getisenabled)

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

___

### GetLinearColor\_\_DelegateSignature

▸ **GetLinearColor__DelegateSignature**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetLinearColor__DelegateSignature](ue_ue.ListView.md#getlinearcolor__delegatesignature)

___

### GetListItems

▸ **GetListItems**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[ListView](ue_ue.ListView.md).[GetListItems](ue_ue.ListView.md#getlistitems)

___

### GetMouseCursor\_\_DelegateSignature

▸ **GetMouseCursor__DelegateSignature**(): [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Returns

[`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetMouseCursor__DelegateSignature](ue_ue.ListView.md#getmousecursor__delegatesignature)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ListView](ue_ue.ListView.md).[GetName](ue_ue.ListView.md#getname)

___

### GetNumItems

▸ **GetNumItems**(): `number`

#### Returns

`number`

#### Inherited from

[ListView](ue_ue.ListView.md).[GetNumItems](ue_ue.ListView.md#getnumitems)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetOuter](ue_ue.ListView.md#getouter)

___

### GetOwningLocalPlayer

▸ **GetOwningLocalPlayer**(): [`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Returns

[`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetOwningLocalPlayer](ue_ue.ListView.md#getowninglocalplayer)

___

### GetOwningPlayer

▸ **GetOwningPlayer**(): [`PlayerController`](ue_ue.PlayerController.md)

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetOwningPlayer](ue_ue.ListView.md#getowningplayer)

___

### GetPaintSpaceGeometry

▸ **GetPaintSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetPaintSpaceGeometry](ue_ue.ListView.md#getpaintspacegeometry)

___

### GetParent

▸ **GetParent**(): [`PanelWidget`](ue_ue.PanelWidget.md)

#### Returns

[`PanelWidget`](ue_ue.PanelWidget.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetParent](ue_ue.ListView.md#getparent)

___

### GetRenderOpacity

▸ **GetRenderOpacity**(): `number`

#### Returns

`number`

#### Inherited from

[ListView](ue_ue.ListView.md).[GetRenderOpacity](ue_ue.ListView.md#getrenderopacity)

___

### GetRenderTransformAngle

▸ **GetRenderTransformAngle**(): `number`

#### Returns

`number`

#### Inherited from

[ListView](ue_ue.ListView.md).[GetRenderTransformAngle](ue_ue.ListView.md#getrendertransformangle)

___

### GetSlateBrush\_\_DelegateSignature

▸ **GetSlateBrush__DelegateSignature**(): [`SlateBrush`](ue_ue.SlateBrush.md)

#### Returns

[`SlateBrush`](ue_ue.SlateBrush.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetSlateBrush__DelegateSignature](ue_ue.ListView.md#getslatebrush__delegatesignature)

___

### GetSlateColor\_\_DelegateSignature

▸ **GetSlateColor__DelegateSignature**(): [`SlateColor`](ue_ue.SlateColor.md)

#### Returns

[`SlateColor`](ue_ue.SlateColor.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetSlateColor__DelegateSignature](ue_ue.ListView.md#getslatecolor__delegatesignature)

___

### GetSlateVisibility\_\_DelegateSignature

▸ **GetSlateVisibility__DelegateSignature**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetSlateVisibility__DelegateSignature](ue_ue.ListView.md#getslatevisibility__delegatesignature)

___

### GetText\_\_DelegateSignature

▸ **GetText__DelegateSignature**(): `string`

#### Returns

`string`

#### Inherited from

[ListView](ue_ue.ListView.md).[GetText__DelegateSignature](ue_ue.ListView.md#gettext__delegatesignature)

___

### GetTickSpaceGeometry

▸ **GetTickSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetTickSpaceGeometry](ue_ue.ListView.md#gettickspacegeometry)

___

### GetVisibility

▸ **GetVisibility**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetVisibility](ue_ue.ListView.md#getvisibility)

___

### GetWidget\_\_DelegateSignature

▸ **GetWidget__DelegateSignature**(): [`Widget`](ue_ue.Widget.md)

#### Returns

[`Widget`](ue_ue.Widget.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetWidget__DelegateSignature](ue_ue.ListView.md#getwidget__delegatesignature)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[GetWorld](ue_ue.ListView.md#getworld)

___

### HasAnyUserFocus

▸ **HasAnyUserFocus**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[HasAnyUserFocus](ue_ue.ListView.md#hasanyuserfocus)

___

### HasFocusedDescendants

▸ **HasFocusedDescendants**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[HasFocusedDescendants](ue_ue.ListView.md#hasfocuseddescendants)

___

### HasKeyboardFocus

▸ **HasKeyboardFocus**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[HasKeyboardFocus](ue_ue.ListView.md#haskeyboardfocus)

___

### HasMouseCapture

▸ **HasMouseCapture**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[HasMouseCapture](ue_ue.ListView.md#hasmousecapture)

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

___

### InvalidateLayoutAndVolatility

▸ **InvalidateLayoutAndVolatility**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[InvalidateLayoutAndVolatility](ue_ue.ListView.md#invalidatelayoutandvolatility)

___

### IsHovered

▸ **IsHovered**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[IsHovered](ue_ue.ListView.md#ishovered)

___

### IsRefreshPending

▸ **IsRefreshPending**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[IsRefreshPending](ue_ue.ListView.md#isrefreshpending)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ListView](ue_ue.ListView.md).[IsVisible](ue_ue.ListView.md#isvisible)

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

___

### OnReply\_\_DelegateSignature

▸ **OnReply__DelegateSignature**(): [`EventReply`](ue_ue.EventReply.md)

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[ListView](ue_ue.ListView.md).[OnReply__DelegateSignature](ue_ue.ListView.md#onreply__delegatesignature)

___

### RegenerateAllEntries

▸ **RegenerateAllEntries**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[RegenerateAllEntries](ue_ue.ListView.md#regenerateallentries)

___

### RemoveFromParent

▸ **RemoveFromParent**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[RemoveFromParent](ue_ue.ListView.md#removefromparent)

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

___

### RequestRefresh

▸ **RequestRefresh**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[RequestRefresh](ue_ue.ListView.md#requestrefresh)

___

### ResetCursor

▸ **ResetCursor**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[ResetCursor](ue_ue.ListView.md#resetcursor)

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

___

### ScrollToBottom

▸ **ScrollToBottom**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[ScrollToBottom](ue_ue.ListView.md#scrolltobottom)

___

### ScrollToTop

▸ **ScrollToTop**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[ScrollToTop](ue_ue.ListView.md#scrolltotop)

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

___

### SetFocus

▸ **SetFocus**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetFocus](ue_ue.ListView.md#setfocus)

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

___

### SetItemExpansion

▸ **SetItemExpansion**(`Item`, `bExpandItem`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `bExpandItem` | `boolean` |

#### Returns

`void`

___

### SetKeyboardFocus

▸ **SetKeyboardFocus**(): `void`

#### Returns

`void`

#### Inherited from

[ListView](ue_ue.ListView.md).[SetKeyboardFocus](ue_ue.ListView.md#setkeyboardfocus)

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

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TreeView`](ue_ue.TreeView.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TreeView`](ue_ue.TreeView.md)

#### Overrides

[ListView](ue_ue.ListView.md).[Find](ue_ue.ListView.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TreeView`](ue_ue.TreeView.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TreeView`](ue_ue.TreeView.md)

#### Overrides

[ListView](ue_ue.ListView.md).[Load](ue_ue.ListView.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ListView](ue_ue.ListView.md).[StaticClass](ue_ue.ListView.md#staticclass)
