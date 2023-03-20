[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ScrollBox

# Class: ScrollBox

[ue/ue](../modules/ue_ue.md).ScrollBox

## Hierarchy

- [`PanelWidget`](ue_ue.PanelWidget.md)

  ↳ **`ScrollBox`**

## Table of contents

### Constructors

- [constructor](ue_ue.ScrollBox.md#constructor)

### Properties

- [AccessibleBehavior](ue_ue.ScrollBox.md#accessiblebehavior)
- [AccessibleSummaryBehavior](ue_ue.ScrollBox.md#accessiblesummarybehavior)
- [AccessibleSummaryText](ue_ue.ScrollBox.md#accessiblesummarytext)
- [AccessibleSummaryTextDelegate](ue_ue.ScrollBox.md#accessiblesummarytextdelegate)
- [AccessibleText](ue_ue.ScrollBox.md#accessibletext)
- [AccessibleTextDelegate](ue_ue.ScrollBox.md#accessibletextdelegate)
- [AccessibleWidgetData](ue_ue.ScrollBox.md#accessiblewidgetdata)
- [AllowOverscroll](ue_ue.ScrollBox.md#allowoverscroll)
- [AlwaysShowScrollbar](ue_ue.ScrollBox.md#alwaysshowscrollbar)
- [AlwaysShowScrollbarTrack](ue_ue.ScrollBox.md#alwaysshowscrollbartrack)
- [BarStyle](ue_ue.ScrollBox.md#barstyle)
- [CategoryName](ue_ue.ScrollBox.md#categoryname)
- [Clipping](ue_ue.ScrollBox.md#clipping)
- [ConsumeMouseWheel](ue_ue.ScrollBox.md#consumemousewheel)
- [Cursor](ue_ue.ScrollBox.md#cursor)
- [DesignerFlags](ue_ue.ScrollBox.md#designerflags)
- [DisplayLabel](ue_ue.ScrollBox.md#displaylabel)
- [FlowDirectionPreference](ue_ue.ScrollBox.md#flowdirectionpreference)
- [NativeBindings](ue_ue.ScrollBox.md#nativebindings)
- [Navigation](ue_ue.ScrollBox.md#navigation)
- [NavigationDestination](ue_ue.ScrollBox.md#navigationdestination)
- [NavigationScrollPadding](ue_ue.ScrollBox.md#navigationscrollpadding)
- [OnUserScrolled](ue_ue.ScrollBox.md#onuserscrolled)
- [Orientation](ue_ue.ScrollBox.md#orientation)
- [RenderOpacity](ue_ue.ScrollBox.md#renderopacity)
- [RenderTransform](ue_ue.ScrollBox.md#rendertransform)
- [RenderTransformPivot](ue_ue.ScrollBox.md#rendertransformpivot)
- [ScrollBarVisibility](ue_ue.ScrollBox.md#scrollbarvisibility)
- [ScrollbarPadding](ue_ue.ScrollBox.md#scrollbarpadding)
- [ScrollbarThickness](ue_ue.ScrollBox.md#scrollbarthickness)
- [Slot](ue_ue.ScrollBox.md#slot)
- [Slots](ue_ue.ScrollBox.md#slots)
- [Style](ue_ue.ScrollBox.md#style)
- [ToolTipText](ue_ue.ScrollBox.md#tooltiptext)
- [ToolTipTextDelegate](ue_ue.ScrollBox.md#tooltiptextdelegate)
- [ToolTipWidget](ue_ue.ScrollBox.md#tooltipwidget)
- [ToolTipWidgetDelegate](ue_ue.ScrollBox.md#tooltipwidgetdelegate)
- [Visibility](ue_ue.ScrollBox.md#visibility)
- [VisibilityDelegate](ue_ue.ScrollBox.md#visibilitydelegate)
- [WheelScrollMultiplier](ue_ue.ScrollBox.md#wheelscrollmultiplier)
- [WidgetBarStyle](ue_ue.ScrollBox.md#widgetbarstyle)
- [WidgetStyle](ue_ue.ScrollBox.md#widgetstyle)
- [\_\_tid\_Object\_\_](ue_ue.ScrollBox.md#__tid_object__)
- [\_\_tid\_PanelWidget\_\_](ue_ue.ScrollBox.md#__tid_panelwidget__)
- [\_\_tid\_ScrollBox\_\_](ue_ue.ScrollBox.md#__tid_scrollbox__)
- [\_\_tid\_Visual\_\_](ue_ue.ScrollBox.md#__tid_visual__)
- [\_\_tid\_Widget\_\_](ue_ue.ScrollBox.md#__tid_widget__)
- [bAllowRightClickDragScrolling](ue_ue.ScrollBox.md#ballowrightclickdragscrolling)
- [bAnimateWheelScrolling](ue_ue.ScrollBox.md#banimatewheelscrolling)
- [bCanChildrenBeAccessible](ue_ue.ScrollBox.md#bcanchildrenbeaccessible)
- [bCreatedByConstructionScript](ue_ue.ScrollBox.md#bcreatedbyconstructionscript)
- [bExpandedInDesigner](ue_ue.ScrollBox.md#bexpandedindesigner)
- [bHiddenInDesigner](ue_ue.ScrollBox.md#bhiddenindesigner)
- [bIsEnabled](ue_ue.ScrollBox.md#bisenabled)
- [bIsEnabledDelegate](ue_ue.ScrollBox.md#bisenableddelegate)
- [bIsVariable](ue_ue.ScrollBox.md#bisvariable)
- [bIsVolatile](ue_ue.ScrollBox.md#bisvolatile)
- [bLockedInDesigner](ue_ue.ScrollBox.md#blockedindesigner)
- [bOverrideAccessibleDefaults](ue_ue.ScrollBox.md#boverrideaccessibledefaults)
- [bOverride\_Cursor](ue_ue.ScrollBox.md#boverride_cursor)

### Methods

- [AddChild](ue_ue.ScrollBox.md#addchild)
- [ClearChildren](ue_ue.ScrollBox.md#clearchildren)
- [CreateDefaultSubobject](ue_ue.ScrollBox.md#createdefaultsubobject)
- [EndInertialScrolling](ue_ue.ScrollBox.md#endinertialscrolling)
- [ExecuteUbergraph](ue_ue.ScrollBox.md#executeubergraph)
- [ForceLayoutPrepass](ue_ue.ScrollBox.md#forcelayoutprepass)
- [ForceVolatile](ue_ue.ScrollBox.md#forcevolatile)
- [GenerateWidgetForObject\_\_DelegateSignature](ue_ue.ScrollBox.md#generatewidgetforobject__delegatesignature)
- [GenerateWidgetForString\_\_DelegateSignature](ue_ue.ScrollBox.md#generatewidgetforstring__delegatesignature)
- [GetAllChildren](ue_ue.ScrollBox.md#getallchildren)
- [GetBool\_\_DelegateSignature](ue_ue.ScrollBox.md#getbool__delegatesignature)
- [GetCachedGeometry](ue_ue.ScrollBox.md#getcachedgeometry)
- [GetCheckBoxState\_\_DelegateSignature](ue_ue.ScrollBox.md#getcheckboxstate__delegatesignature)
- [GetChildAt](ue_ue.ScrollBox.md#getchildat)
- [GetChildIndex](ue_ue.ScrollBox.md#getchildindex)
- [GetChildrenCount](ue_ue.ScrollBox.md#getchildrencount)
- [GetClass](ue_ue.ScrollBox.md#getclass)
- [GetClipping](ue_ue.ScrollBox.md#getclipping)
- [GetDesiredSize](ue_ue.ScrollBox.md#getdesiredsize)
- [GetFloat\_\_DelegateSignature](ue_ue.ScrollBox.md#getfloat__delegatesignature)
- [GetGameInstance](ue_ue.ScrollBox.md#getgameinstance)
- [GetInt32\_\_DelegateSignature](ue_ue.ScrollBox.md#getint32__delegatesignature)
- [GetIsEnabled](ue_ue.ScrollBox.md#getisenabled)
- [GetLinearColor\_\_DelegateSignature](ue_ue.ScrollBox.md#getlinearcolor__delegatesignature)
- [GetMouseCursor\_\_DelegateSignature](ue_ue.ScrollBox.md#getmousecursor__delegatesignature)
- [GetName](ue_ue.ScrollBox.md#getname)
- [GetOuter](ue_ue.ScrollBox.md#getouter)
- [GetOwningLocalPlayer](ue_ue.ScrollBox.md#getowninglocalplayer)
- [GetOwningPlayer](ue_ue.ScrollBox.md#getowningplayer)
- [GetPaintSpaceGeometry](ue_ue.ScrollBox.md#getpaintspacegeometry)
- [GetParent](ue_ue.ScrollBox.md#getparent)
- [GetRenderOpacity](ue_ue.ScrollBox.md#getrenderopacity)
- [GetRenderTransformAngle](ue_ue.ScrollBox.md#getrendertransformangle)
- [GetScrollOffset](ue_ue.ScrollBox.md#getscrolloffset)
- [GetScrollOffsetOfEnd](ue_ue.ScrollBox.md#getscrolloffsetofend)
- [GetSlateBrush\_\_DelegateSignature](ue_ue.ScrollBox.md#getslatebrush__delegatesignature)
- [GetSlateColor\_\_DelegateSignature](ue_ue.ScrollBox.md#getslatecolor__delegatesignature)
- [GetSlateVisibility\_\_DelegateSignature](ue_ue.ScrollBox.md#getslatevisibility__delegatesignature)
- [GetText\_\_DelegateSignature](ue_ue.ScrollBox.md#gettext__delegatesignature)
- [GetTickSpaceGeometry](ue_ue.ScrollBox.md#gettickspacegeometry)
- [GetViewOffsetFraction](ue_ue.ScrollBox.md#getviewoffsetfraction)
- [GetVisibility](ue_ue.ScrollBox.md#getvisibility)
- [GetWidget\_\_DelegateSignature](ue_ue.ScrollBox.md#getwidget__delegatesignature)
- [GetWorld](ue_ue.ScrollBox.md#getworld)
- [HasAnyChildren](ue_ue.ScrollBox.md#hasanychildren)
- [HasAnyUserFocus](ue_ue.ScrollBox.md#hasanyuserfocus)
- [HasChild](ue_ue.ScrollBox.md#haschild)
- [HasFocusedDescendants](ue_ue.ScrollBox.md#hasfocuseddescendants)
- [HasKeyboardFocus](ue_ue.ScrollBox.md#haskeyboardfocus)
- [HasMouseCapture](ue_ue.ScrollBox.md#hasmousecapture)
- [HasMouseCaptureByUser](ue_ue.ScrollBox.md#hasmousecapturebyuser)
- [HasUserFocus](ue_ue.ScrollBox.md#hasuserfocus)
- [HasUserFocusedDescendants](ue_ue.ScrollBox.md#hasuserfocuseddescendants)
- [InvalidateLayoutAndVolatility](ue_ue.ScrollBox.md#invalidatelayoutandvolatility)
- [IsHovered](ue_ue.ScrollBox.md#ishovered)
- [IsVisible](ue_ue.ScrollBox.md#isvisible)
- [OnPointerEvent\_\_DelegateSignature](ue_ue.ScrollBox.md#onpointerevent__delegatesignature)
- [OnReply\_\_DelegateSignature](ue_ue.ScrollBox.md#onreply__delegatesignature)
- [RemoveChild](ue_ue.ScrollBox.md#removechild)
- [RemoveChildAt](ue_ue.ScrollBox.md#removechildat)
- [RemoveFromParent](ue_ue.ScrollBox.md#removefromparent)
- [ResetCursor](ue_ue.ScrollBox.md#resetcursor)
- [ScrollToEnd](ue_ue.ScrollBox.md#scrolltoend)
- [ScrollToStart](ue_ue.ScrollBox.md#scrolltostart)
- [ScrollWidgetIntoView](ue_ue.ScrollBox.md#scrollwidgetintoview)
- [SetAllNavigationRules](ue_ue.ScrollBox.md#setallnavigationrules)
- [SetAllowOverscroll](ue_ue.ScrollBox.md#setallowoverscroll)
- [SetAlwaysShowScrollbar](ue_ue.ScrollBox.md#setalwaysshowscrollbar)
- [SetAnimateWheelScrolling](ue_ue.ScrollBox.md#setanimatewheelscrolling)
- [SetClipping](ue_ue.ScrollBox.md#setclipping)
- [SetConsumeMouseWheel](ue_ue.ScrollBox.md#setconsumemousewheel)
- [SetCursor](ue_ue.ScrollBox.md#setcursor)
- [SetFocus](ue_ue.ScrollBox.md#setfocus)
- [SetIsEnabled](ue_ue.ScrollBox.md#setisenabled)
- [SetKeyboardFocus](ue_ue.ScrollBox.md#setkeyboardfocus)
- [SetNavigationRule](ue_ue.ScrollBox.md#setnavigationrule)
- [SetNavigationRuleBase](ue_ue.ScrollBox.md#setnavigationrulebase)
- [SetNavigationRuleCustom](ue_ue.ScrollBox.md#setnavigationrulecustom)
- [SetNavigationRuleCustomBoundary](ue_ue.ScrollBox.md#setnavigationrulecustomboundary)
- [SetNavigationRuleExplicit](ue_ue.ScrollBox.md#setnavigationruleexplicit)
- [SetOrientation](ue_ue.ScrollBox.md#setorientation)
- [SetRenderOpacity](ue_ue.ScrollBox.md#setrenderopacity)
- [SetRenderScale](ue_ue.ScrollBox.md#setrenderscale)
- [SetRenderShear](ue_ue.ScrollBox.md#setrendershear)
- [SetRenderTransform](ue_ue.ScrollBox.md#setrendertransform)
- [SetRenderTransformAngle](ue_ue.ScrollBox.md#setrendertransformangle)
- [SetRenderTransformPivot](ue_ue.ScrollBox.md#setrendertransformpivot)
- [SetRenderTranslation](ue_ue.ScrollBox.md#setrendertranslation)
- [SetScrollBarVisibility](ue_ue.ScrollBox.md#setscrollbarvisibility)
- [SetScrollOffset](ue_ue.ScrollBox.md#setscrolloffset)
- [SetScrollbarPadding](ue_ue.ScrollBox.md#setscrollbarpadding)
- [SetScrollbarThickness](ue_ue.ScrollBox.md#setscrollbarthickness)
- [SetToolTip](ue_ue.ScrollBox.md#settooltip)
- [SetToolTipText](ue_ue.ScrollBox.md#settooltiptext)
- [SetUserFocus](ue_ue.ScrollBox.md#setuserfocus)
- [SetVisibility](ue_ue.ScrollBox.md#setvisibility)
- [SetWheelScrollMultiplier](ue_ue.ScrollBox.md#setwheelscrollmultiplier)
- [Find](ue_ue.ScrollBox.md#find)
- [Load](ue_ue.ScrollBox.md#load)
- [StaticClass](ue_ue.ScrollBox.md#staticclass)

## Constructors

### constructor

• **new ScrollBox**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PanelWidget](ue_ue.PanelWidget.md).[constructor](ue_ue.PanelWidget.md#constructor)

#### Defined in

[ue/ue.d.ts:59993](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59993)

## Properties

### AccessibleBehavior

• **AccessibleBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[AccessibleBehavior](ue_ue.PanelWidget.md#accessiblebehavior)

#### Defined in

[ue/ue.d.ts:10940](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10940)

___

### AccessibleSummaryBehavior

• **AccessibleSummaryBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[AccessibleSummaryBehavior](ue_ue.PanelWidget.md#accessiblesummarybehavior)

#### Defined in

[ue/ue.d.ts:10941](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10941)

___

### AccessibleSummaryText

• **AccessibleSummaryText**: `string`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[AccessibleSummaryText](ue_ue.PanelWidget.md#accessiblesummarytext)

#### Defined in

[ue/ue.d.ts:10944](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10944)

___

### AccessibleSummaryTextDelegate

• **AccessibleSummaryTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[AccessibleSummaryTextDelegate](ue_ue.PanelWidget.md#accessiblesummarytextdelegate)

#### Defined in

[ue/ue.d.ts:10945](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10945)

___

### AccessibleText

• **AccessibleText**: `string`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[AccessibleText](ue_ue.PanelWidget.md#accessibletext)

#### Defined in

[ue/ue.d.ts:10942](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10942)

___

### AccessibleTextDelegate

• **AccessibleTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[AccessibleTextDelegate](ue_ue.PanelWidget.md#accessibletextdelegate)

#### Defined in

[ue/ue.d.ts:10943](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10943)

___

### AccessibleWidgetData

• **AccessibleWidgetData**: [`SlateAccessibleWidgetData`](ue_ue.SlateAccessibleWidgetData.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[AccessibleWidgetData](ue_ue.PanelWidget.md#accessiblewidgetdata)

#### Defined in

[ue/ue.d.ts:10946](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10946)

___

### AllowOverscroll

• **AllowOverscroll**: `boolean`

#### Defined in

[ue/ue.d.ts:60005](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60005)

___

### AlwaysShowScrollbar

• **AlwaysShowScrollbar**: `boolean`

#### Defined in

[ue/ue.d.ts:60003](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60003)

___

### AlwaysShowScrollbarTrack

• **AlwaysShowScrollbarTrack**: `boolean`

#### Defined in

[ue/ue.d.ts:60004](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60004)

___

### BarStyle

• **BarStyle**: [`SlateWidgetStyleAsset`](ue_ue.SlateWidgetStyleAsset.md)

#### Defined in

[ue/ue.d.ts:59997](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59997)

___

### CategoryName

• **CategoryName**: `string`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[CategoryName](ue_ue.PanelWidget.md#categoryname)

#### Defined in

[ue/ue.d.ts:10960](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10960)

___

### Clipping

• **Clipping**: [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[Clipping](ue_ue.PanelWidget.md#clipping)

#### Defined in

[ue/ue.d.ts:10952](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10952)

___

### ConsumeMouseWheel

• **ConsumeMouseWheel**: [`EConsumeMouseWheel`](../enums/ue_ue.EConsumeMouseWheel.md)

#### Defined in

[ue/ue.d.ts:60000](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60000)

___

### Cursor

• **Cursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[Cursor](ue_ue.PanelWidget.md#cursor)

#### Defined in

[ue/ue.d.ts:10951](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10951)

___

### DesignerFlags

• **DesignerFlags**: `number`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[DesignerFlags](ue_ue.PanelWidget.md#designerflags)

#### Defined in

[ue/ue.d.ts:10958](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10958)

___

### DisplayLabel

• **DisplayLabel**: `string`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[DisplayLabel](ue_ue.PanelWidget.md#displaylabel)

#### Defined in

[ue/ue.d.ts:10959](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10959)

___

### FlowDirectionPreference

• **FlowDirectionPreference**: [`EFlowDirectionPreference`](../enums/ue_ue.EFlowDirectionPreference.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[FlowDirectionPreference](ue_ue.PanelWidget.md#flowdirectionpreference)

#### Defined in

[ue/ue.d.ts:10956](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10956)

___

### NativeBindings

• **NativeBindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyBinding`](ue_ue.PropertyBinding.md)\>

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[NativeBindings](ue_ue.PanelWidget.md#nativebindings)

#### Defined in

[ue/ue.d.ts:10957](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10957)

___

### Navigation

• **Navigation**: [`WidgetNavigation`](ue_ue.WidgetNavigation.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[Navigation](ue_ue.PanelWidget.md#navigation)

#### Defined in

[ue/ue.d.ts:10955](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10955)

___

### NavigationDestination

• **NavigationDestination**: [`EDescendantScrollDestination`](../enums/ue_ue.EDescendantScrollDestination.md)

#### Defined in

[ue/ue.d.ts:60007](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60007)

___

### NavigationScrollPadding

• **NavigationScrollPadding**: `number`

#### Defined in

[ue/ue.d.ts:60008](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60008)

___

### OnUserScrolled

• **OnUserScrolled**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`CurrentOffset`: `number`) => `void`\>

#### Defined in

[ue/ue.d.ts:60011](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60011)

___

### Orientation

• **Orientation**: [`EOrientation`](../enums/ue_ue.EOrientation.md)

#### Defined in

[ue/ue.d.ts:59998](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59998)

___

### RenderOpacity

• **RenderOpacity**: `number`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[RenderOpacity](ue_ue.PanelWidget.md#renderopacity)

#### Defined in

[ue/ue.d.ts:10954](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10954)

___

### RenderTransform

• **RenderTransform**: [`WidgetTransform`](ue_ue.WidgetTransform.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[RenderTransform](ue_ue.PanelWidget.md#rendertransform)

#### Defined in

[ue/ue.d.ts:10932](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10932)

___

### RenderTransformPivot

• **RenderTransformPivot**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[RenderTransformPivot](ue_ue.PanelWidget.md#rendertransformpivot)

#### Defined in

[ue/ue.d.ts:10933](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10933)

___

### ScrollBarVisibility

• **ScrollBarVisibility**: [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Defined in

[ue/ue.d.ts:59999](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59999)

___

### ScrollbarPadding

• **ScrollbarPadding**: [`Margin`](ue_ue.Margin.md)

#### Defined in

[ue/ue.d.ts:60002](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60002)

___

### ScrollbarThickness

• **ScrollbarThickness**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:60001](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60001)

___

### Slot

• **Slot**: [`PanelSlot`](ue_ue.PanelSlot.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[Slot](ue_ue.PanelWidget.md#slot)

#### Defined in

[ue/ue.d.ts:10925](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10925)

___

### Slots

• **Slots**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PanelSlot`](ue_ue.PanelSlot.md)\>

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[Slots](ue_ue.PanelWidget.md#slots)

#### Defined in

[ue/ue.d.ts:10678](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10678)

___

### Style

• **Style**: [`SlateWidgetStyleAsset`](ue_ue.SlateWidgetStyleAsset.md)

#### Defined in

[ue/ue.d.ts:59996](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59996)

___

### ToolTipText

• **ToolTipText**: `string`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[ToolTipText](ue_ue.PanelWidget.md#tooltiptext)

#### Defined in

[ue/ue.d.ts:10927](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10927)

___

### ToolTipTextDelegate

• **ToolTipTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[ToolTipTextDelegate](ue_ue.PanelWidget.md#tooltiptextdelegate)

#### Defined in

[ue/ue.d.ts:10928](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10928)

___

### ToolTipWidget

• **ToolTipWidget**: [`Widget`](ue_ue.Widget.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[ToolTipWidget](ue_ue.PanelWidget.md#tooltipwidget)

#### Defined in

[ue/ue.d.ts:10929](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10929)

___

### ToolTipWidgetDelegate

• **ToolTipWidgetDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`Widget`](ue_ue.Widget.md)\>

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[ToolTipWidgetDelegate](ue_ue.PanelWidget.md#tooltipwidgetdelegate)

#### Defined in

[ue/ue.d.ts:10930](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10930)

___

### Visibility

• **Visibility**: [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[Visibility](ue_ue.PanelWidget.md#visibility)

#### Defined in

[ue/ue.d.ts:10953](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10953)

___

### VisibilityDelegate

• **VisibilityDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)\>

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[VisibilityDelegate](ue_ue.PanelWidget.md#visibilitydelegate)

#### Defined in

[ue/ue.d.ts:10931](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10931)

___

### WheelScrollMultiplier

• **WheelScrollMultiplier**: `number`

#### Defined in

[ue/ue.d.ts:60010](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60010)

___

### WidgetBarStyle

• **WidgetBarStyle**: [`ScrollBarStyle`](ue_ue.ScrollBarStyle.md)

#### Defined in

[ue/ue.d.ts:59995](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59995)

___

### WidgetStyle

• **WidgetStyle**: [`ScrollBoxStyle`](ue_ue.ScrollBoxStyle.md)

#### Defined in

[ue/ue.d.ts:59994](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59994)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[__tid_Object__](ue_ue.PanelWidget.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PanelWidget\_\_

• **\_\_tid\_PanelWidget\_\_**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[__tid_PanelWidget__](ue_ue.PanelWidget.md#__tid_panelwidget__)

#### Defined in

[ue/ue.d.ts:10693](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10693)

___

### \_\_tid\_ScrollBox\_\_

• **\_\_tid\_ScrollBox\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:60033](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60033)

___

### \_\_tid\_Visual\_\_

• **\_\_tid\_Visual\_\_**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[__tid_Visual__](ue_ue.PanelWidget.md#__tid_visual__)

#### Defined in

[ue/ue.d.ts:10673](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10673)

___

### \_\_tid\_Widget\_\_

• **\_\_tid\_Widget\_\_**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[__tid_Widget__](ue_ue.PanelWidget.md#__tid_widget__)

#### Defined in

[ue/ue.d.ts:11029](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11029)

___

### bAllowRightClickDragScrolling

• **bAllowRightClickDragScrolling**: `boolean`

#### Defined in

[ue/ue.d.ts:60009](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60009)

___

### bAnimateWheelScrolling

• **bAnimateWheelScrolling**: `boolean`

#### Defined in

[ue/ue.d.ts:60006](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60006)

___

### bCanChildrenBeAccessible

• **bCanChildrenBeAccessible**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bCanChildrenBeAccessible](ue_ue.PanelWidget.md#bcanchildrenbeaccessible)

#### Defined in

[ue/ue.d.ts:10939](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10939)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bCreatedByConstructionScript](ue_ue.PanelWidget.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:10935](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10935)

___

### bExpandedInDesigner

• **bExpandedInDesigner**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bExpandedInDesigner](ue_ue.PanelWidget.md#bexpandedindesigner)

#### Defined in

[ue/ue.d.ts:10949](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10949)

___

### bHiddenInDesigner

• **bHiddenInDesigner**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bHiddenInDesigner](ue_ue.PanelWidget.md#bhiddenindesigner)

#### Defined in

[ue/ue.d.ts:10948](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10948)

___

### bIsEnabled

• **bIsEnabled**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bIsEnabled](ue_ue.PanelWidget.md#bisenabled)

#### Defined in

[ue/ue.d.ts:10936](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10936)

___

### bIsEnabledDelegate

• **bIsEnabledDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `boolean`\>

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bIsEnabledDelegate](ue_ue.PanelWidget.md#bisenableddelegate)

#### Defined in

[ue/ue.d.ts:10926](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10926)

___

### bIsVariable

• **bIsVariable**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bIsVariable](ue_ue.PanelWidget.md#bisvariable)

#### Defined in

[ue/ue.d.ts:10934](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10934)

___

### bIsVolatile

• **bIsVolatile**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bIsVolatile](ue_ue.PanelWidget.md#bisvolatile)

#### Defined in

[ue/ue.d.ts:10947](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10947)

___

### bLockedInDesigner

• **bLockedInDesigner**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bLockedInDesigner](ue_ue.PanelWidget.md#blockedindesigner)

#### Defined in

[ue/ue.d.ts:10950](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10950)

___

### bOverrideAccessibleDefaults

• **bOverrideAccessibleDefaults**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bOverrideAccessibleDefaults](ue_ue.PanelWidget.md#boverrideaccessibledefaults)

#### Defined in

[ue/ue.d.ts:10938](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10938)

___

### bOverride\_Cursor

• **bOverride\_Cursor**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bOverride_Cursor](ue_ue.PanelWidget.md#boverride_cursor)

#### Defined in

[ue/ue.d.ts:10937](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10937)

## Methods

### AddChild

▸ **AddChild**(`Content`): [`PanelSlot`](ue_ue.PanelSlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Content` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

[`PanelSlot`](ue_ue.PanelSlot.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[AddChild](ue_ue.PanelWidget.md#addchild)

#### Defined in

[ue/ue.d.ts:10679](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10679)

___

### ClearChildren

▸ **ClearChildren**(): `void`

#### Returns

`void`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[ClearChildren](ue_ue.PanelWidget.md#clearchildren)

#### Defined in

[ue/ue.d.ts:10680](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10680)

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

[PanelWidget](ue_ue.PanelWidget.md).[CreateDefaultSubobject](ue_ue.PanelWidget.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

___

### EndInertialScrolling

▸ **EndInertialScrolling**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60012](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60012)

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

[PanelWidget](ue_ue.PanelWidget.md).[ExecuteUbergraph](ue_ue.PanelWidget.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### ForceLayoutPrepass

▸ **ForceLayoutPrepass**(): `void`

#### Returns

`void`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[ForceLayoutPrepass](ue_ue.PanelWidget.md#forcelayoutprepass)

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

[PanelWidget](ue_ue.PanelWidget.md).[ForceVolatile](ue_ue.PanelWidget.md#forcevolatile)

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

[PanelWidget](ue_ue.PanelWidget.md).[GenerateWidgetForObject__DelegateSignature](ue_ue.PanelWidget.md#generatewidgetforobject__delegatesignature)

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

[PanelWidget](ue_ue.PanelWidget.md).[GenerateWidgetForString__DelegateSignature](ue_ue.PanelWidget.md#generatewidgetforstring__delegatesignature)

#### Defined in

[ue/ue.d.ts:10964](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10964)

___

### GetAllChildren

▸ **GetAllChildren**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Widget`](ue_ue.Widget.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Widget`](ue_ue.Widget.md)\>

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetAllChildren](ue_ue.PanelWidget.md#getallchildren)

#### Defined in

[ue/ue.d.ts:10681](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10681)

___

### GetBool\_\_DelegateSignature

▸ **GetBool__DelegateSignature**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetBool__DelegateSignature](ue_ue.PanelWidget.md#getbool__delegatesignature)

#### Defined in

[ue/ue.d.ts:10965](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10965)

___

### GetCachedGeometry

▸ **GetCachedGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetCachedGeometry](ue_ue.PanelWidget.md#getcachedgeometry)

#### Defined in

[ue/ue.d.ts:10966](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10966)

___

### GetCheckBoxState\_\_DelegateSignature

▸ **GetCheckBoxState__DelegateSignature**(): [`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Returns

[`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetCheckBoxState__DelegateSignature](ue_ue.PanelWidget.md#getcheckboxstate__delegatesignature)

#### Defined in

[ue/ue.d.ts:10967](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10967)

___

### GetChildAt

▸ **GetChildAt**(`Index`): [`Widget`](ue_ue.Widget.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

[`Widget`](ue_ue.Widget.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetChildAt](ue_ue.PanelWidget.md#getchildat)

#### Defined in

[ue/ue.d.ts:10682](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10682)

___

### GetChildIndex

▸ **GetChildIndex**(`Content`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Content` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

`number`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetChildIndex](ue_ue.PanelWidget.md#getchildindex)

#### Defined in

[ue/ue.d.ts:10683](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10683)

___

### GetChildrenCount

▸ **GetChildrenCount**(): `number`

#### Returns

`number`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetChildrenCount](ue_ue.PanelWidget.md#getchildrencount)

#### Defined in

[ue/ue.d.ts:10684](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10684)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetClass](ue_ue.PanelWidget.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetClipping

▸ **GetClipping**(): [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Returns

[`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetClipping](ue_ue.PanelWidget.md#getclipping)

#### Defined in

[ue/ue.d.ts:10968](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10968)

___

### GetDesiredSize

▸ **GetDesiredSize**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetDesiredSize](ue_ue.PanelWidget.md#getdesiredsize)

#### Defined in

[ue/ue.d.ts:10969](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10969)

___

### GetFloat\_\_DelegateSignature

▸ **GetFloat__DelegateSignature**(): `number`

#### Returns

`number`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetFloat__DelegateSignature](ue_ue.PanelWidget.md#getfloat__delegatesignature)

#### Defined in

[ue/ue.d.ts:10970](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10970)

___

### GetGameInstance

▸ **GetGameInstance**(): [`GameInstance`](ue_ue.GameInstance.md)

#### Returns

[`GameInstance`](ue_ue.GameInstance.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetGameInstance](ue_ue.PanelWidget.md#getgameinstance)

#### Defined in

[ue/ue.d.ts:10971](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10971)

___

### GetInt32\_\_DelegateSignature

▸ **GetInt32__DelegateSignature**(): `number`

#### Returns

`number`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetInt32__DelegateSignature](ue_ue.PanelWidget.md#getint32__delegatesignature)

#### Defined in

[ue/ue.d.ts:10972](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10972)

___

### GetIsEnabled

▸ **GetIsEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetIsEnabled](ue_ue.PanelWidget.md#getisenabled)

#### Defined in

[ue/ue.d.ts:10973](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10973)

___

### GetLinearColor\_\_DelegateSignature

▸ **GetLinearColor__DelegateSignature**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetLinearColor__DelegateSignature](ue_ue.PanelWidget.md#getlinearcolor__delegatesignature)

#### Defined in

[ue/ue.d.ts:10974](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10974)

___

### GetMouseCursor\_\_DelegateSignature

▸ **GetMouseCursor__DelegateSignature**(): [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Returns

[`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetMouseCursor__DelegateSignature](ue_ue.PanelWidget.md#getmousecursor__delegatesignature)

#### Defined in

[ue/ue.d.ts:10975](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10975)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetName](ue_ue.PanelWidget.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetOuter](ue_ue.PanelWidget.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetOwningLocalPlayer

▸ **GetOwningLocalPlayer**(): [`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Returns

[`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetOwningLocalPlayer](ue_ue.PanelWidget.md#getowninglocalplayer)

#### Defined in

[ue/ue.d.ts:10976](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10976)

___

### GetOwningPlayer

▸ **GetOwningPlayer**(): [`PlayerController`](ue_ue.PlayerController.md)

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetOwningPlayer](ue_ue.PanelWidget.md#getowningplayer)

#### Defined in

[ue/ue.d.ts:10977](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10977)

___

### GetPaintSpaceGeometry

▸ **GetPaintSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetPaintSpaceGeometry](ue_ue.PanelWidget.md#getpaintspacegeometry)

#### Defined in

[ue/ue.d.ts:10978](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10978)

___

### GetParent

▸ **GetParent**(): [`PanelWidget`](ue_ue.PanelWidget.md)

#### Returns

[`PanelWidget`](ue_ue.PanelWidget.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetParent](ue_ue.PanelWidget.md#getparent)

#### Defined in

[ue/ue.d.ts:10979](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10979)

___

### GetRenderOpacity

▸ **GetRenderOpacity**(): `number`

#### Returns

`number`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetRenderOpacity](ue_ue.PanelWidget.md#getrenderopacity)

#### Defined in

[ue/ue.d.ts:10980](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10980)

___

### GetRenderTransformAngle

▸ **GetRenderTransformAngle**(): `number`

#### Returns

`number`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetRenderTransformAngle](ue_ue.PanelWidget.md#getrendertransformangle)

#### Defined in

[ue/ue.d.ts:10981](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10981)

___

### GetScrollOffset

▸ **GetScrollOffset**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:60013](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60013)

___

### GetScrollOffsetOfEnd

▸ **GetScrollOffsetOfEnd**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:60014](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60014)

___

### GetSlateBrush\_\_DelegateSignature

▸ **GetSlateBrush__DelegateSignature**(): [`SlateBrush`](ue_ue.SlateBrush.md)

#### Returns

[`SlateBrush`](ue_ue.SlateBrush.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetSlateBrush__DelegateSignature](ue_ue.PanelWidget.md#getslatebrush__delegatesignature)

#### Defined in

[ue/ue.d.ts:10982](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10982)

___

### GetSlateColor\_\_DelegateSignature

▸ **GetSlateColor__DelegateSignature**(): [`SlateColor`](ue_ue.SlateColor.md)

#### Returns

[`SlateColor`](ue_ue.SlateColor.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetSlateColor__DelegateSignature](ue_ue.PanelWidget.md#getslatecolor__delegatesignature)

#### Defined in

[ue/ue.d.ts:10983](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10983)

___

### GetSlateVisibility\_\_DelegateSignature

▸ **GetSlateVisibility__DelegateSignature**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetSlateVisibility__DelegateSignature](ue_ue.PanelWidget.md#getslatevisibility__delegatesignature)

#### Defined in

[ue/ue.d.ts:10984](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10984)

___

### GetText\_\_DelegateSignature

▸ **GetText__DelegateSignature**(): `string`

#### Returns

`string`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetText__DelegateSignature](ue_ue.PanelWidget.md#gettext__delegatesignature)

#### Defined in

[ue/ue.d.ts:10985](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10985)

___

### GetTickSpaceGeometry

▸ **GetTickSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetTickSpaceGeometry](ue_ue.PanelWidget.md#gettickspacegeometry)

#### Defined in

[ue/ue.d.ts:10986](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10986)

___

### GetViewOffsetFraction

▸ **GetViewOffsetFraction**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:60015](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60015)

___

### GetVisibility

▸ **GetVisibility**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetVisibility](ue_ue.PanelWidget.md#getvisibility)

#### Defined in

[ue/ue.d.ts:10987](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10987)

___

### GetWidget\_\_DelegateSignature

▸ **GetWidget__DelegateSignature**(): [`Widget`](ue_ue.Widget.md)

#### Returns

[`Widget`](ue_ue.Widget.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetWidget__DelegateSignature](ue_ue.PanelWidget.md#getwidget__delegatesignature)

#### Defined in

[ue/ue.d.ts:10988](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10988)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetWorld](ue_ue.PanelWidget.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### HasAnyChildren

▸ **HasAnyChildren**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[HasAnyChildren](ue_ue.PanelWidget.md#hasanychildren)

#### Defined in

[ue/ue.d.ts:10685](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10685)

___

### HasAnyUserFocus

▸ **HasAnyUserFocus**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[HasAnyUserFocus](ue_ue.PanelWidget.md#hasanyuserfocus)

#### Defined in

[ue/ue.d.ts:10989](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10989)

___

### HasChild

▸ **HasChild**(`Content`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Content` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

`boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[HasChild](ue_ue.PanelWidget.md#haschild)

#### Defined in

[ue/ue.d.ts:10686](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10686)

___

### HasFocusedDescendants

▸ **HasFocusedDescendants**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[HasFocusedDescendants](ue_ue.PanelWidget.md#hasfocuseddescendants)

#### Defined in

[ue/ue.d.ts:10990](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10990)

___

### HasKeyboardFocus

▸ **HasKeyboardFocus**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[HasKeyboardFocus](ue_ue.PanelWidget.md#haskeyboardfocus)

#### Defined in

[ue/ue.d.ts:10991](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10991)

___

### HasMouseCapture

▸ **HasMouseCapture**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[HasMouseCapture](ue_ue.PanelWidget.md#hasmousecapture)

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

[PanelWidget](ue_ue.PanelWidget.md).[HasMouseCaptureByUser](ue_ue.PanelWidget.md#hasmousecapturebyuser)

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

[PanelWidget](ue_ue.PanelWidget.md).[HasUserFocus](ue_ue.PanelWidget.md#hasuserfocus)

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

[PanelWidget](ue_ue.PanelWidget.md).[HasUserFocusedDescendants](ue_ue.PanelWidget.md#hasuserfocuseddescendants)

#### Defined in

[ue/ue.d.ts:10995](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10995)

___

### InvalidateLayoutAndVolatility

▸ **InvalidateLayoutAndVolatility**(): `void`

#### Returns

`void`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[InvalidateLayoutAndVolatility](ue_ue.PanelWidget.md#invalidatelayoutandvolatility)

#### Defined in

[ue/ue.d.ts:10996](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10996)

___

### IsHovered

▸ **IsHovered**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[IsHovered](ue_ue.PanelWidget.md#ishovered)

#### Defined in

[ue/ue.d.ts:10997](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10997)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[IsVisible](ue_ue.PanelWidget.md#isvisible)

#### Defined in

[ue/ue.d.ts:10998](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10998)

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

[PanelWidget](ue_ue.PanelWidget.md).[OnPointerEvent__DelegateSignature](ue_ue.PanelWidget.md#onpointerevent__delegatesignature)

#### Defined in

[ue/ue.d.ts:10999](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10999)

___

### OnReply\_\_DelegateSignature

▸ **OnReply__DelegateSignature**(): [`EventReply`](ue_ue.EventReply.md)

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[OnReply__DelegateSignature](ue_ue.PanelWidget.md#onreply__delegatesignature)

#### Defined in

[ue/ue.d.ts:11000](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11000)

___

### RemoveChild

▸ **RemoveChild**(`Content`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Content` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

`boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[RemoveChild](ue_ue.PanelWidget.md#removechild)

#### Defined in

[ue/ue.d.ts:10687](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10687)

___

### RemoveChildAt

▸ **RemoveChildAt**(`Index`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

`boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[RemoveChildAt](ue_ue.PanelWidget.md#removechildat)

#### Defined in

[ue/ue.d.ts:10688](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10688)

___

### RemoveFromParent

▸ **RemoveFromParent**(): `void`

#### Returns

`void`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[RemoveFromParent](ue_ue.PanelWidget.md#removefromparent)

#### Defined in

[ue/ue.d.ts:11001](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11001)

___

### ResetCursor

▸ **ResetCursor**(): `void`

#### Returns

`void`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[ResetCursor](ue_ue.PanelWidget.md#resetcursor)

#### Defined in

[ue/ue.d.ts:11002](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11002)

___

### ScrollToEnd

▸ **ScrollToEnd**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60016](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60016)

___

### ScrollToStart

▸ **ScrollToStart**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60017](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60017)

___

### ScrollWidgetIntoView

▸ **ScrollWidgetIntoView**(`WidgetToFind`, `AnimateScroll?`, `ScrollDestination?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WidgetToFind` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |
| `AnimateScroll?` | `boolean` |
| `ScrollDestination?` | [`EDescendantScrollDestination`](../enums/ue_ue.EDescendantScrollDestination.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60018](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60018)

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

[PanelWidget](ue_ue.PanelWidget.md).[SetAllNavigationRules](ue_ue.PanelWidget.md#setallnavigationrules)

#### Defined in

[ue/ue.d.ts:11003](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11003)

___

### SetAllowOverscroll

▸ **SetAllowOverscroll**(`NewAllowOverscroll`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewAllowOverscroll` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60019](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60019)

___

### SetAlwaysShowScrollbar

▸ **SetAlwaysShowScrollbar**(`NewAlwaysShowScrollbar`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewAlwaysShowScrollbar` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60020](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60020)

___

### SetAnimateWheelScrolling

▸ **SetAnimateWheelScrolling**(`bShouldAnimateWheelScrolling`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bShouldAnimateWheelScrolling` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60021](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60021)

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

[PanelWidget](ue_ue.PanelWidget.md).[SetClipping](ue_ue.PanelWidget.md#setclipping)

#### Defined in

[ue/ue.d.ts:11004](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11004)

___

### SetConsumeMouseWheel

▸ **SetConsumeMouseWheel**(`NewConsumeMouseWheel`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewConsumeMouseWheel` | [`EConsumeMouseWheel`](../enums/ue_ue.EConsumeMouseWheel.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60022](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60022)

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

[PanelWidget](ue_ue.PanelWidget.md).[SetCursor](ue_ue.PanelWidget.md#setcursor)

#### Defined in

[ue/ue.d.ts:11005](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11005)

___

### SetFocus

▸ **SetFocus**(): `void`

#### Returns

`void`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[SetFocus](ue_ue.PanelWidget.md#setfocus)

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

[PanelWidget](ue_ue.PanelWidget.md).[SetIsEnabled](ue_ue.PanelWidget.md#setisenabled)

#### Defined in

[ue/ue.d.ts:11007](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11007)

___

### SetKeyboardFocus

▸ **SetKeyboardFocus**(): `void`

#### Returns

`void`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[SetKeyboardFocus](ue_ue.PanelWidget.md#setkeyboardfocus)

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

[PanelWidget](ue_ue.PanelWidget.md).[SetNavigationRule](ue_ue.PanelWidget.md#setnavigationrule)

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

[PanelWidget](ue_ue.PanelWidget.md).[SetNavigationRuleBase](ue_ue.PanelWidget.md#setnavigationrulebase)

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

[PanelWidget](ue_ue.PanelWidget.md).[SetNavigationRuleCustom](ue_ue.PanelWidget.md#setnavigationrulecustom)

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

[PanelWidget](ue_ue.PanelWidget.md).[SetNavigationRuleCustomBoundary](ue_ue.PanelWidget.md#setnavigationrulecustomboundary)

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

[PanelWidget](ue_ue.PanelWidget.md).[SetNavigationRuleExplicit](ue_ue.PanelWidget.md#setnavigationruleexplicit)

#### Defined in

[ue/ue.d.ts:11013](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11013)

___

### SetOrientation

▸ **SetOrientation**(`NewOrientation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewOrientation` | [`EOrientation`](../enums/ue_ue.EOrientation.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60023](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60023)

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

[PanelWidget](ue_ue.PanelWidget.md).[SetRenderOpacity](ue_ue.PanelWidget.md#setrenderopacity)

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

[PanelWidget](ue_ue.PanelWidget.md).[SetRenderScale](ue_ue.PanelWidget.md#setrenderscale)

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

[PanelWidget](ue_ue.PanelWidget.md).[SetRenderShear](ue_ue.PanelWidget.md#setrendershear)

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

[PanelWidget](ue_ue.PanelWidget.md).[SetRenderTransform](ue_ue.PanelWidget.md#setrendertransform)

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

[PanelWidget](ue_ue.PanelWidget.md).[SetRenderTransformAngle](ue_ue.PanelWidget.md#setrendertransformangle)

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

[PanelWidget](ue_ue.PanelWidget.md).[SetRenderTransformPivot](ue_ue.PanelWidget.md#setrendertransformpivot)

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

[PanelWidget](ue_ue.PanelWidget.md).[SetRenderTranslation](ue_ue.PanelWidget.md#setrendertranslation)

#### Defined in

[ue/ue.d.ts:11020](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11020)

___

### SetScrollBarVisibility

▸ **SetScrollBarVisibility**(`NewScrollBarVisibility`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScrollBarVisibility` | [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60026](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60026)

___

### SetScrollOffset

▸ **SetScrollOffset**(`NewScrollOffset`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScrollOffset` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60027](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60027)

___

### SetScrollbarPadding

▸ **SetScrollbarPadding**(`NewScrollbarPadding`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScrollbarPadding` | [`Margin`](ue_ue.Margin.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60024](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60024)

___

### SetScrollbarThickness

▸ **SetScrollbarThickness**(`NewScrollbarThickness`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScrollbarThickness` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60025](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60025)

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

[PanelWidget](ue_ue.PanelWidget.md).[SetToolTip](ue_ue.PanelWidget.md#settooltip)

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

[PanelWidget](ue_ue.PanelWidget.md).[SetToolTipText](ue_ue.PanelWidget.md#settooltiptext)

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

[PanelWidget](ue_ue.PanelWidget.md).[SetUserFocus](ue_ue.PanelWidget.md#setuserfocus)

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

[PanelWidget](ue_ue.PanelWidget.md).[SetVisibility](ue_ue.PanelWidget.md#setvisibility)

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

#### Defined in

[ue/ue.d.ts:60028](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60028)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ScrollBox`](ue_ue.ScrollBox.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ScrollBox`](ue_ue.ScrollBox.md)

#### Overrides

[PanelWidget](ue_ue.PanelWidget.md).[Find](ue_ue.PanelWidget.md#find)

#### Defined in

[ue/ue.d.ts:60030](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60030)

___

### Load

▸ `Static` **Load**(`InName`): [`ScrollBox`](ue_ue.ScrollBox.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ScrollBox`](ue_ue.ScrollBox.md)

#### Overrides

[PanelWidget](ue_ue.PanelWidget.md).[Load](ue_ue.PanelWidget.md#load)

#### Defined in

[ue/ue.d.ts:60031](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60031)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PanelWidget](ue_ue.PanelWidget.md).[StaticClass](ue_ue.PanelWidget.md#staticclass)

#### Defined in

[ue/ue.d.ts:60029](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60029)
