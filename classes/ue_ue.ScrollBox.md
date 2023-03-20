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

## Properties

### AccessibleBehavior

• **AccessibleBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[AccessibleBehavior](ue_ue.PanelWidget.md#accessiblebehavior)

___

### AccessibleSummaryBehavior

• **AccessibleSummaryBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[AccessibleSummaryBehavior](ue_ue.PanelWidget.md#accessiblesummarybehavior)

___

### AccessibleSummaryText

• **AccessibleSummaryText**: `string`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[AccessibleSummaryText](ue_ue.PanelWidget.md#accessiblesummarytext)

___

### AccessibleSummaryTextDelegate

• **AccessibleSummaryTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[AccessibleSummaryTextDelegate](ue_ue.PanelWidget.md#accessiblesummarytextdelegate)

___

### AccessibleText

• **AccessibleText**: `string`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[AccessibleText](ue_ue.PanelWidget.md#accessibletext)

___

### AccessibleTextDelegate

• **AccessibleTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[AccessibleTextDelegate](ue_ue.PanelWidget.md#accessibletextdelegate)

___

### AccessibleWidgetData

• **AccessibleWidgetData**: [`SlateAccessibleWidgetData`](ue_ue.SlateAccessibleWidgetData.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[AccessibleWidgetData](ue_ue.PanelWidget.md#accessiblewidgetdata)

___

### AllowOverscroll

• **AllowOverscroll**: `boolean`

___

### AlwaysShowScrollbar

• **AlwaysShowScrollbar**: `boolean`

___

### AlwaysShowScrollbarTrack

• **AlwaysShowScrollbarTrack**: `boolean`

___

### BarStyle

• **BarStyle**: [`SlateWidgetStyleAsset`](ue_ue.SlateWidgetStyleAsset.md)

___

### CategoryName

• **CategoryName**: `string`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[CategoryName](ue_ue.PanelWidget.md#categoryname)

___

### Clipping

• **Clipping**: [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[Clipping](ue_ue.PanelWidget.md#clipping)

___

### ConsumeMouseWheel

• **ConsumeMouseWheel**: [`EConsumeMouseWheel`](../enums/ue_ue.EConsumeMouseWheel.md)

___

### Cursor

• **Cursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[Cursor](ue_ue.PanelWidget.md#cursor)

___

### DesignerFlags

• **DesignerFlags**: `number`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[DesignerFlags](ue_ue.PanelWidget.md#designerflags)

___

### DisplayLabel

• **DisplayLabel**: `string`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[DisplayLabel](ue_ue.PanelWidget.md#displaylabel)

___

### FlowDirectionPreference

• **FlowDirectionPreference**: [`EFlowDirectionPreference`](../enums/ue_ue.EFlowDirectionPreference.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[FlowDirectionPreference](ue_ue.PanelWidget.md#flowdirectionpreference)

___

### NativeBindings

• **NativeBindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyBinding`](ue_ue.PropertyBinding.md)\>

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[NativeBindings](ue_ue.PanelWidget.md#nativebindings)

___

### Navigation

• **Navigation**: [`WidgetNavigation`](ue_ue.WidgetNavigation.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[Navigation](ue_ue.PanelWidget.md#navigation)

___

### NavigationDestination

• **NavigationDestination**: [`EDescendantScrollDestination`](../enums/ue_ue.EDescendantScrollDestination.md)

___

### NavigationScrollPadding

• **NavigationScrollPadding**: `number`

___

### OnUserScrolled

• **OnUserScrolled**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`CurrentOffset`: `number`) => `void`\>

___

### Orientation

• **Orientation**: [`EOrientation`](../enums/ue_ue.EOrientation.md)

___

### RenderOpacity

• **RenderOpacity**: `number`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[RenderOpacity](ue_ue.PanelWidget.md#renderopacity)

___

### RenderTransform

• **RenderTransform**: [`WidgetTransform`](ue_ue.WidgetTransform.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[RenderTransform](ue_ue.PanelWidget.md#rendertransform)

___

### RenderTransformPivot

• **RenderTransformPivot**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[RenderTransformPivot](ue_ue.PanelWidget.md#rendertransformpivot)

___

### ScrollBarVisibility

• **ScrollBarVisibility**: [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

___

### ScrollbarPadding

• **ScrollbarPadding**: [`Margin`](ue_ue.Margin.md)

___

### ScrollbarThickness

• **ScrollbarThickness**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### Slot

• **Slot**: [`PanelSlot`](ue_ue.PanelSlot.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[Slot](ue_ue.PanelWidget.md#slot)

___

### Slots

• **Slots**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PanelSlot`](ue_ue.PanelSlot.md)\>

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[Slots](ue_ue.PanelWidget.md#slots)

___

### Style

• **Style**: [`SlateWidgetStyleAsset`](ue_ue.SlateWidgetStyleAsset.md)

___

### ToolTipText

• **ToolTipText**: `string`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[ToolTipText](ue_ue.PanelWidget.md#tooltiptext)

___

### ToolTipTextDelegate

• **ToolTipTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[ToolTipTextDelegate](ue_ue.PanelWidget.md#tooltiptextdelegate)

___

### ToolTipWidget

• **ToolTipWidget**: [`Widget`](ue_ue.Widget.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[ToolTipWidget](ue_ue.PanelWidget.md#tooltipwidget)

___

### ToolTipWidgetDelegate

• **ToolTipWidgetDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`Widget`](ue_ue.Widget.md)\>

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[ToolTipWidgetDelegate](ue_ue.PanelWidget.md#tooltipwidgetdelegate)

___

### Visibility

• **Visibility**: [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[Visibility](ue_ue.PanelWidget.md#visibility)

___

### VisibilityDelegate

• **VisibilityDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)\>

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[VisibilityDelegate](ue_ue.PanelWidget.md#visibilitydelegate)

___

### WheelScrollMultiplier

• **WheelScrollMultiplier**: `number`

___

### WidgetBarStyle

• **WidgetBarStyle**: [`ScrollBarStyle`](ue_ue.ScrollBarStyle.md)

___

### WidgetStyle

• **WidgetStyle**: [`ScrollBoxStyle`](ue_ue.ScrollBoxStyle.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[__tid_Object__](ue_ue.PanelWidget.md#__tid_object__)

___

### \_\_tid\_PanelWidget\_\_

• **\_\_tid\_PanelWidget\_\_**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[__tid_PanelWidget__](ue_ue.PanelWidget.md#__tid_panelwidget__)

___

### \_\_tid\_ScrollBox\_\_

• **\_\_tid\_ScrollBox\_\_**: `boolean`

___

### \_\_tid\_Visual\_\_

• **\_\_tid\_Visual\_\_**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[__tid_Visual__](ue_ue.PanelWidget.md#__tid_visual__)

___

### \_\_tid\_Widget\_\_

• **\_\_tid\_Widget\_\_**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[__tid_Widget__](ue_ue.PanelWidget.md#__tid_widget__)

___

### bAllowRightClickDragScrolling

• **bAllowRightClickDragScrolling**: `boolean`

___

### bAnimateWheelScrolling

• **bAnimateWheelScrolling**: `boolean`

___

### bCanChildrenBeAccessible

• **bCanChildrenBeAccessible**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bCanChildrenBeAccessible](ue_ue.PanelWidget.md#bcanchildrenbeaccessible)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bCreatedByConstructionScript](ue_ue.PanelWidget.md#bcreatedbyconstructionscript)

___

### bExpandedInDesigner

• **bExpandedInDesigner**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bExpandedInDesigner](ue_ue.PanelWidget.md#bexpandedindesigner)

___

### bHiddenInDesigner

• **bHiddenInDesigner**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bHiddenInDesigner](ue_ue.PanelWidget.md#bhiddenindesigner)

___

### bIsEnabled

• **bIsEnabled**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bIsEnabled](ue_ue.PanelWidget.md#bisenabled)

___

### bIsEnabledDelegate

• **bIsEnabledDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `boolean`\>

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bIsEnabledDelegate](ue_ue.PanelWidget.md#bisenableddelegate)

___

### bIsVariable

• **bIsVariable**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bIsVariable](ue_ue.PanelWidget.md#bisvariable)

___

### bIsVolatile

• **bIsVolatile**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bIsVolatile](ue_ue.PanelWidget.md#bisvolatile)

___

### bLockedInDesigner

• **bLockedInDesigner**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bLockedInDesigner](ue_ue.PanelWidget.md#blockedindesigner)

___

### bOverrideAccessibleDefaults

• **bOverrideAccessibleDefaults**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bOverrideAccessibleDefaults](ue_ue.PanelWidget.md#boverrideaccessibledefaults)

___

### bOverride\_Cursor

• **bOverride\_Cursor**: `boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[bOverride_Cursor](ue_ue.PanelWidget.md#boverride_cursor)

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

___

### ClearChildren

▸ **ClearChildren**(): `void`

#### Returns

`void`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[ClearChildren](ue_ue.PanelWidget.md#clearchildren)

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

___

### EndInertialScrolling

▸ **EndInertialScrolling**(): `void`

#### Returns

`void`

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

___

### ForceLayoutPrepass

▸ **ForceLayoutPrepass**(): `void`

#### Returns

`void`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[ForceLayoutPrepass](ue_ue.PanelWidget.md#forcelayoutprepass)

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

___

### GetAllChildren

▸ **GetAllChildren**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Widget`](ue_ue.Widget.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Widget`](ue_ue.Widget.md)\>

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetAllChildren](ue_ue.PanelWidget.md#getallchildren)

___

### GetBool\_\_DelegateSignature

▸ **GetBool__DelegateSignature**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetBool__DelegateSignature](ue_ue.PanelWidget.md#getbool__delegatesignature)

___

### GetCachedGeometry

▸ **GetCachedGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetCachedGeometry](ue_ue.PanelWidget.md#getcachedgeometry)

___

### GetCheckBoxState\_\_DelegateSignature

▸ **GetCheckBoxState__DelegateSignature**(): [`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Returns

[`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetCheckBoxState__DelegateSignature](ue_ue.PanelWidget.md#getcheckboxstate__delegatesignature)

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

___

### GetChildrenCount

▸ **GetChildrenCount**(): `number`

#### Returns

`number`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetChildrenCount](ue_ue.PanelWidget.md#getchildrencount)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetClass](ue_ue.PanelWidget.md#getclass)

___

### GetClipping

▸ **GetClipping**(): [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Returns

[`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetClipping](ue_ue.PanelWidget.md#getclipping)

___

### GetDesiredSize

▸ **GetDesiredSize**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetDesiredSize](ue_ue.PanelWidget.md#getdesiredsize)

___

### GetFloat\_\_DelegateSignature

▸ **GetFloat__DelegateSignature**(): `number`

#### Returns

`number`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetFloat__DelegateSignature](ue_ue.PanelWidget.md#getfloat__delegatesignature)

___

### GetGameInstance

▸ **GetGameInstance**(): [`GameInstance`](ue_ue.GameInstance.md)

#### Returns

[`GameInstance`](ue_ue.GameInstance.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetGameInstance](ue_ue.PanelWidget.md#getgameinstance)

___

### GetInt32\_\_DelegateSignature

▸ **GetInt32__DelegateSignature**(): `number`

#### Returns

`number`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetInt32__DelegateSignature](ue_ue.PanelWidget.md#getint32__delegatesignature)

___

### GetIsEnabled

▸ **GetIsEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetIsEnabled](ue_ue.PanelWidget.md#getisenabled)

___

### GetLinearColor\_\_DelegateSignature

▸ **GetLinearColor__DelegateSignature**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetLinearColor__DelegateSignature](ue_ue.PanelWidget.md#getlinearcolor__delegatesignature)

___

### GetMouseCursor\_\_DelegateSignature

▸ **GetMouseCursor__DelegateSignature**(): [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Returns

[`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetMouseCursor__DelegateSignature](ue_ue.PanelWidget.md#getmousecursor__delegatesignature)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetName](ue_ue.PanelWidget.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetOuter](ue_ue.PanelWidget.md#getouter)

___

### GetOwningLocalPlayer

▸ **GetOwningLocalPlayer**(): [`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Returns

[`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetOwningLocalPlayer](ue_ue.PanelWidget.md#getowninglocalplayer)

___

### GetOwningPlayer

▸ **GetOwningPlayer**(): [`PlayerController`](ue_ue.PlayerController.md)

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetOwningPlayer](ue_ue.PanelWidget.md#getowningplayer)

___

### GetPaintSpaceGeometry

▸ **GetPaintSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetPaintSpaceGeometry](ue_ue.PanelWidget.md#getpaintspacegeometry)

___

### GetParent

▸ **GetParent**(): [`PanelWidget`](ue_ue.PanelWidget.md)

#### Returns

[`PanelWidget`](ue_ue.PanelWidget.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetParent](ue_ue.PanelWidget.md#getparent)

___

### GetRenderOpacity

▸ **GetRenderOpacity**(): `number`

#### Returns

`number`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetRenderOpacity](ue_ue.PanelWidget.md#getrenderopacity)

___

### GetRenderTransformAngle

▸ **GetRenderTransformAngle**(): `number`

#### Returns

`number`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetRenderTransformAngle](ue_ue.PanelWidget.md#getrendertransformangle)

___

### GetScrollOffset

▸ **GetScrollOffset**(): `number`

#### Returns

`number`

___

### GetScrollOffsetOfEnd

▸ **GetScrollOffsetOfEnd**(): `number`

#### Returns

`number`

___

### GetSlateBrush\_\_DelegateSignature

▸ **GetSlateBrush__DelegateSignature**(): [`SlateBrush`](ue_ue.SlateBrush.md)

#### Returns

[`SlateBrush`](ue_ue.SlateBrush.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetSlateBrush__DelegateSignature](ue_ue.PanelWidget.md#getslatebrush__delegatesignature)

___

### GetSlateColor\_\_DelegateSignature

▸ **GetSlateColor__DelegateSignature**(): [`SlateColor`](ue_ue.SlateColor.md)

#### Returns

[`SlateColor`](ue_ue.SlateColor.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetSlateColor__DelegateSignature](ue_ue.PanelWidget.md#getslatecolor__delegatesignature)

___

### GetSlateVisibility\_\_DelegateSignature

▸ **GetSlateVisibility__DelegateSignature**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetSlateVisibility__DelegateSignature](ue_ue.PanelWidget.md#getslatevisibility__delegatesignature)

___

### GetText\_\_DelegateSignature

▸ **GetText__DelegateSignature**(): `string`

#### Returns

`string`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetText__DelegateSignature](ue_ue.PanelWidget.md#gettext__delegatesignature)

___

### GetTickSpaceGeometry

▸ **GetTickSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetTickSpaceGeometry](ue_ue.PanelWidget.md#gettickspacegeometry)

___

### GetViewOffsetFraction

▸ **GetViewOffsetFraction**(): `number`

#### Returns

`number`

___

### GetVisibility

▸ **GetVisibility**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetVisibility](ue_ue.PanelWidget.md#getvisibility)

___

### GetWidget\_\_DelegateSignature

▸ **GetWidget__DelegateSignature**(): [`Widget`](ue_ue.Widget.md)

#### Returns

[`Widget`](ue_ue.Widget.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetWidget__DelegateSignature](ue_ue.PanelWidget.md#getwidget__delegatesignature)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[GetWorld](ue_ue.PanelWidget.md#getworld)

___

### HasAnyChildren

▸ **HasAnyChildren**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[HasAnyChildren](ue_ue.PanelWidget.md#hasanychildren)

___

### HasAnyUserFocus

▸ **HasAnyUserFocus**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[HasAnyUserFocus](ue_ue.PanelWidget.md#hasanyuserfocus)

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

___

### HasFocusedDescendants

▸ **HasFocusedDescendants**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[HasFocusedDescendants](ue_ue.PanelWidget.md#hasfocuseddescendants)

___

### HasKeyboardFocus

▸ **HasKeyboardFocus**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[HasKeyboardFocus](ue_ue.PanelWidget.md#haskeyboardfocus)

___

### HasMouseCapture

▸ **HasMouseCapture**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[HasMouseCapture](ue_ue.PanelWidget.md#hasmousecapture)

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

___

### InvalidateLayoutAndVolatility

▸ **InvalidateLayoutAndVolatility**(): `void`

#### Returns

`void`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[InvalidateLayoutAndVolatility](ue_ue.PanelWidget.md#invalidatelayoutandvolatility)

___

### IsHovered

▸ **IsHovered**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[IsHovered](ue_ue.PanelWidget.md#ishovered)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[IsVisible](ue_ue.PanelWidget.md#isvisible)

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

___

### OnReply\_\_DelegateSignature

▸ **OnReply__DelegateSignature**(): [`EventReply`](ue_ue.EventReply.md)

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[OnReply__DelegateSignature](ue_ue.PanelWidget.md#onreply__delegatesignature)

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

___

### RemoveFromParent

▸ **RemoveFromParent**(): `void`

#### Returns

`void`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[RemoveFromParent](ue_ue.PanelWidget.md#removefromparent)

___

### ResetCursor

▸ **ResetCursor**(): `void`

#### Returns

`void`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[ResetCursor](ue_ue.PanelWidget.md#resetcursor)

___

### ScrollToEnd

▸ **ScrollToEnd**(): `void`

#### Returns

`void`

___

### ScrollToStart

▸ **ScrollToStart**(): `void`

#### Returns

`void`

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

___

### SetAllowOverscroll

▸ **SetAllowOverscroll**(`NewAllowOverscroll`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewAllowOverscroll` | `boolean` |

#### Returns

`void`

___

### SetAlwaysShowScrollbar

▸ **SetAlwaysShowScrollbar**(`NewAlwaysShowScrollbar`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewAlwaysShowScrollbar` | `boolean` |

#### Returns

`void`

___

### SetAnimateWheelScrolling

▸ **SetAnimateWheelScrolling**(`bShouldAnimateWheelScrolling`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bShouldAnimateWheelScrolling` | `boolean` |

#### Returns

`void`

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

___

### SetConsumeMouseWheel

▸ **SetConsumeMouseWheel**(`NewConsumeMouseWheel`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewConsumeMouseWheel` | [`EConsumeMouseWheel`](../enums/ue_ue.EConsumeMouseWheel.md) |

#### Returns

`void`

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

___

### SetFocus

▸ **SetFocus**(): `void`

#### Returns

`void`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[SetFocus](ue_ue.PanelWidget.md#setfocus)

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

___

### SetKeyboardFocus

▸ **SetKeyboardFocus**(): `void`

#### Returns

`void`

#### Inherited from

[PanelWidget](ue_ue.PanelWidget.md).[SetKeyboardFocus](ue_ue.PanelWidget.md#setkeyboardfocus)

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

___

### SetOrientation

▸ **SetOrientation**(`NewOrientation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewOrientation` | [`EOrientation`](../enums/ue_ue.EOrientation.md) |

#### Returns

`void`

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

___

### SetScrollBarVisibility

▸ **SetScrollBarVisibility**(`NewScrollBarVisibility`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScrollBarVisibility` | [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md) |

#### Returns

`void`

___

### SetScrollOffset

▸ **SetScrollOffset**(`NewScrollOffset`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScrollOffset` | `number` |

#### Returns

`void`

___

### SetScrollbarPadding

▸ **SetScrollbarPadding**(`NewScrollbarPadding`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScrollbarPadding` | [`Margin`](ue_ue.Margin.md) |

#### Returns

`void`

___

### SetScrollbarThickness

▸ **SetScrollbarThickness**(`NewScrollbarThickness`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScrollbarThickness` | [`Vector2D`](ue_ue_s.Vector2D.md) |

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

[PanelWidget](ue_ue.PanelWidget.md).[SetToolTip](ue_ue.PanelWidget.md#settooltip)

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

___

### SetWheelScrollMultiplier

▸ **SetWheelScrollMultiplier**(`NewWheelScrollMultiplier`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewWheelScrollMultiplier` | `number` |

#### Returns

`void`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PanelWidget](ue_ue.PanelWidget.md).[StaticClass](ue_ue.PanelWidget.md#staticclass)
