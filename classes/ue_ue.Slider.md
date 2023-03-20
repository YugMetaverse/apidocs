[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Slider

# Class: Slider

[ue/ue](../modules/ue_ue.md).Slider

## Hierarchy

- [`Widget`](ue_ue.Widget.md)

  ↳ **`Slider`**

## Table of contents

### Constructors

- [constructor](ue_ue.Slider.md#constructor)

### Properties

- [AccessibleBehavior](ue_ue.Slider.md#accessiblebehavior)
- [AccessibleSummaryBehavior](ue_ue.Slider.md#accessiblesummarybehavior)
- [AccessibleSummaryText](ue_ue.Slider.md#accessiblesummarytext)
- [AccessibleSummaryTextDelegate](ue_ue.Slider.md#accessiblesummarytextdelegate)
- [AccessibleText](ue_ue.Slider.md#accessibletext)
- [AccessibleTextDelegate](ue_ue.Slider.md#accessibletextdelegate)
- [AccessibleWidgetData](ue_ue.Slider.md#accessiblewidgetdata)
- [CategoryName](ue_ue.Slider.md#categoryname)
- [Clipping](ue_ue.Slider.md#clipping)
- [Cursor](ue_ue.Slider.md#cursor)
- [DesignerFlags](ue_ue.Slider.md#designerflags)
- [DisplayLabel](ue_ue.Slider.md#displaylabel)
- [FlowDirectionPreference](ue_ue.Slider.md#flowdirectionpreference)
- [IndentHandle](ue_ue.Slider.md#indenthandle)
- [IsFocusable](ue_ue.Slider.md#isfocusable)
- [Locked](ue_ue.Slider.md#locked)
- [MaxValue](ue_ue.Slider.md#maxvalue)
- [MinValue](ue_ue.Slider.md#minvalue)
- [MouseUsesStep](ue_ue.Slider.md#mouseusesstep)
- [NativeBindings](ue_ue.Slider.md#nativebindings)
- [Navigation](ue_ue.Slider.md#navigation)
- [OnControllerCaptureBegin](ue_ue.Slider.md#oncontrollercapturebegin)
- [OnControllerCaptureEnd](ue_ue.Slider.md#oncontrollercaptureend)
- [OnMouseCaptureBegin](ue_ue.Slider.md#onmousecapturebegin)
- [OnMouseCaptureEnd](ue_ue.Slider.md#onmousecaptureend)
- [OnValueChanged](ue_ue.Slider.md#onvaluechanged)
- [Orientation](ue_ue.Slider.md#orientation)
- [RenderOpacity](ue_ue.Slider.md#renderopacity)
- [RenderTransform](ue_ue.Slider.md#rendertransform)
- [RenderTransformPivot](ue_ue.Slider.md#rendertransformpivot)
- [RequiresControllerLock](ue_ue.Slider.md#requirescontrollerlock)
- [SliderBarColor](ue_ue.Slider.md#sliderbarcolor)
- [SliderHandleColor](ue_ue.Slider.md#sliderhandlecolor)
- [Slot](ue_ue.Slider.md#slot)
- [StepSize](ue_ue.Slider.md#stepsize)
- [ToolTipText](ue_ue.Slider.md#tooltiptext)
- [ToolTipTextDelegate](ue_ue.Slider.md#tooltiptextdelegate)
- [ToolTipWidget](ue_ue.Slider.md#tooltipwidget)
- [ToolTipWidgetDelegate](ue_ue.Slider.md#tooltipwidgetdelegate)
- [Value](ue_ue.Slider.md#value)
- [ValueDelegate](ue_ue.Slider.md#valuedelegate)
- [Visibility](ue_ue.Slider.md#visibility)
- [VisibilityDelegate](ue_ue.Slider.md#visibilitydelegate)
- [WidgetStyle](ue_ue.Slider.md#widgetstyle)
- [\_\_tid\_Object\_\_](ue_ue.Slider.md#__tid_object__)
- [\_\_tid\_Slider\_\_](ue_ue.Slider.md#__tid_slider__)
- [\_\_tid\_Visual\_\_](ue_ue.Slider.md#__tid_visual__)
- [\_\_tid\_Widget\_\_](ue_ue.Slider.md#__tid_widget__)
- [bCanChildrenBeAccessible](ue_ue.Slider.md#bcanchildrenbeaccessible)
- [bCreatedByConstructionScript](ue_ue.Slider.md#bcreatedbyconstructionscript)
- [bExpandedInDesigner](ue_ue.Slider.md#bexpandedindesigner)
- [bHiddenInDesigner](ue_ue.Slider.md#bhiddenindesigner)
- [bIsEnabled](ue_ue.Slider.md#bisenabled)
- [bIsEnabledDelegate](ue_ue.Slider.md#bisenableddelegate)
- [bIsVariable](ue_ue.Slider.md#bisvariable)
- [bIsVolatile](ue_ue.Slider.md#bisvolatile)
- [bLockedInDesigner](ue_ue.Slider.md#blockedindesigner)
- [bOverrideAccessibleDefaults](ue_ue.Slider.md#boverrideaccessibledefaults)
- [bOverride\_Cursor](ue_ue.Slider.md#boverride_cursor)

### Methods

- [CreateDefaultSubobject](ue_ue.Slider.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Slider.md#executeubergraph)
- [ForceLayoutPrepass](ue_ue.Slider.md#forcelayoutprepass)
- [ForceVolatile](ue_ue.Slider.md#forcevolatile)
- [GenerateWidgetForObject\_\_DelegateSignature](ue_ue.Slider.md#generatewidgetforobject__delegatesignature)
- [GenerateWidgetForString\_\_DelegateSignature](ue_ue.Slider.md#generatewidgetforstring__delegatesignature)
- [GetBool\_\_DelegateSignature](ue_ue.Slider.md#getbool__delegatesignature)
- [GetCachedGeometry](ue_ue.Slider.md#getcachedgeometry)
- [GetCheckBoxState\_\_DelegateSignature](ue_ue.Slider.md#getcheckboxstate__delegatesignature)
- [GetClass](ue_ue.Slider.md#getclass)
- [GetClipping](ue_ue.Slider.md#getclipping)
- [GetDesiredSize](ue_ue.Slider.md#getdesiredsize)
- [GetFloat\_\_DelegateSignature](ue_ue.Slider.md#getfloat__delegatesignature)
- [GetGameInstance](ue_ue.Slider.md#getgameinstance)
- [GetInt32\_\_DelegateSignature](ue_ue.Slider.md#getint32__delegatesignature)
- [GetIsEnabled](ue_ue.Slider.md#getisenabled)
- [GetLinearColor\_\_DelegateSignature](ue_ue.Slider.md#getlinearcolor__delegatesignature)
- [GetMouseCursor\_\_DelegateSignature](ue_ue.Slider.md#getmousecursor__delegatesignature)
- [GetName](ue_ue.Slider.md#getname)
- [GetNormalizedValue](ue_ue.Slider.md#getnormalizedvalue)
- [GetOuter](ue_ue.Slider.md#getouter)
- [GetOwningLocalPlayer](ue_ue.Slider.md#getowninglocalplayer)
- [GetOwningPlayer](ue_ue.Slider.md#getowningplayer)
- [GetPaintSpaceGeometry](ue_ue.Slider.md#getpaintspacegeometry)
- [GetParent](ue_ue.Slider.md#getparent)
- [GetRenderOpacity](ue_ue.Slider.md#getrenderopacity)
- [GetRenderTransformAngle](ue_ue.Slider.md#getrendertransformangle)
- [GetSlateBrush\_\_DelegateSignature](ue_ue.Slider.md#getslatebrush__delegatesignature)
- [GetSlateColor\_\_DelegateSignature](ue_ue.Slider.md#getslatecolor__delegatesignature)
- [GetSlateVisibility\_\_DelegateSignature](ue_ue.Slider.md#getslatevisibility__delegatesignature)
- [GetText\_\_DelegateSignature](ue_ue.Slider.md#gettext__delegatesignature)
- [GetTickSpaceGeometry](ue_ue.Slider.md#gettickspacegeometry)
- [GetValue](ue_ue.Slider.md#getvalue)
- [GetVisibility](ue_ue.Slider.md#getvisibility)
- [GetWidget\_\_DelegateSignature](ue_ue.Slider.md#getwidget__delegatesignature)
- [GetWorld](ue_ue.Slider.md#getworld)
- [HasAnyUserFocus](ue_ue.Slider.md#hasanyuserfocus)
- [HasFocusedDescendants](ue_ue.Slider.md#hasfocuseddescendants)
- [HasKeyboardFocus](ue_ue.Slider.md#haskeyboardfocus)
- [HasMouseCapture](ue_ue.Slider.md#hasmousecapture)
- [HasMouseCaptureByUser](ue_ue.Slider.md#hasmousecapturebyuser)
- [HasUserFocus](ue_ue.Slider.md#hasuserfocus)
- [HasUserFocusedDescendants](ue_ue.Slider.md#hasuserfocuseddescendants)
- [InvalidateLayoutAndVolatility](ue_ue.Slider.md#invalidatelayoutandvolatility)
- [IsHovered](ue_ue.Slider.md#ishovered)
- [IsVisible](ue_ue.Slider.md#isvisible)
- [OnPointerEvent\_\_DelegateSignature](ue_ue.Slider.md#onpointerevent__delegatesignature)
- [OnReply\_\_DelegateSignature](ue_ue.Slider.md#onreply__delegatesignature)
- [RemoveFromParent](ue_ue.Slider.md#removefromparent)
- [ResetCursor](ue_ue.Slider.md#resetcursor)
- [SetAllNavigationRules](ue_ue.Slider.md#setallnavigationrules)
- [SetClipping](ue_ue.Slider.md#setclipping)
- [SetCursor](ue_ue.Slider.md#setcursor)
- [SetFocus](ue_ue.Slider.md#setfocus)
- [SetIndentHandle](ue_ue.Slider.md#setindenthandle)
- [SetIsEnabled](ue_ue.Slider.md#setisenabled)
- [SetKeyboardFocus](ue_ue.Slider.md#setkeyboardfocus)
- [SetLocked](ue_ue.Slider.md#setlocked)
- [SetMaxValue](ue_ue.Slider.md#setmaxvalue)
- [SetMinValue](ue_ue.Slider.md#setminvalue)
- [SetNavigationRule](ue_ue.Slider.md#setnavigationrule)
- [SetNavigationRuleBase](ue_ue.Slider.md#setnavigationrulebase)
- [SetNavigationRuleCustom](ue_ue.Slider.md#setnavigationrulecustom)
- [SetNavigationRuleCustomBoundary](ue_ue.Slider.md#setnavigationrulecustomboundary)
- [SetNavigationRuleExplicit](ue_ue.Slider.md#setnavigationruleexplicit)
- [SetRenderOpacity](ue_ue.Slider.md#setrenderopacity)
- [SetRenderScale](ue_ue.Slider.md#setrenderscale)
- [SetRenderShear](ue_ue.Slider.md#setrendershear)
- [SetRenderTransform](ue_ue.Slider.md#setrendertransform)
- [SetRenderTransformAngle](ue_ue.Slider.md#setrendertransformangle)
- [SetRenderTransformPivot](ue_ue.Slider.md#setrendertransformpivot)
- [SetRenderTranslation](ue_ue.Slider.md#setrendertranslation)
- [SetSliderBarColor](ue_ue.Slider.md#setsliderbarcolor)
- [SetSliderHandleColor](ue_ue.Slider.md#setsliderhandlecolor)
- [SetStepSize](ue_ue.Slider.md#setstepsize)
- [SetToolTip](ue_ue.Slider.md#settooltip)
- [SetToolTipText](ue_ue.Slider.md#settooltiptext)
- [SetUserFocus](ue_ue.Slider.md#setuserfocus)
- [SetValue](ue_ue.Slider.md#setvalue)
- [SetVisibility](ue_ue.Slider.md#setvisibility)
- [Find](ue_ue.Slider.md#find)
- [Load](ue_ue.Slider.md#load)
- [StaticClass](ue_ue.Slider.md#staticclass)

## Constructors

### constructor

• **new Slider**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Widget](ue_ue.Widget.md).[constructor](ue_ue.Widget.md#constructor)

#### Defined in

[ue/ue.d.ts:61028](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61028)

## Properties

### AccessibleBehavior

• **AccessibleBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[AccessibleBehavior](ue_ue.Widget.md#accessiblebehavior)

#### Defined in

[ue/ue.d.ts:10940](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10940)

___

### AccessibleSummaryBehavior

• **AccessibleSummaryBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[AccessibleSummaryBehavior](ue_ue.Widget.md#accessiblesummarybehavior)

#### Defined in

[ue/ue.d.ts:10941](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10941)

___

### AccessibleSummaryText

• **AccessibleSummaryText**: `string`

#### Inherited from

[Widget](ue_ue.Widget.md).[AccessibleSummaryText](ue_ue.Widget.md#accessiblesummarytext)

#### Defined in

[ue/ue.d.ts:10944](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10944)

___

### AccessibleSummaryTextDelegate

• **AccessibleSummaryTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[Widget](ue_ue.Widget.md).[AccessibleSummaryTextDelegate](ue_ue.Widget.md#accessiblesummarytextdelegate)

#### Defined in

[ue/ue.d.ts:10945](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10945)

___

### AccessibleText

• **AccessibleText**: `string`

#### Inherited from

[Widget](ue_ue.Widget.md).[AccessibleText](ue_ue.Widget.md#accessibletext)

#### Defined in

[ue/ue.d.ts:10942](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10942)

___

### AccessibleTextDelegate

• **AccessibleTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[Widget](ue_ue.Widget.md).[AccessibleTextDelegate](ue_ue.Widget.md#accessibletextdelegate)

#### Defined in

[ue/ue.d.ts:10943](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10943)

___

### AccessibleWidgetData

• **AccessibleWidgetData**: [`SlateAccessibleWidgetData`](ue_ue.SlateAccessibleWidgetData.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[AccessibleWidgetData](ue_ue.Widget.md#accessiblewidgetdata)

#### Defined in

[ue/ue.d.ts:10946](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10946)

___

### CategoryName

• **CategoryName**: `string`

#### Inherited from

[Widget](ue_ue.Widget.md).[CategoryName](ue_ue.Widget.md#categoryname)

#### Defined in

[ue/ue.d.ts:10960](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10960)

___

### Clipping

• **Clipping**: [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[Clipping](ue_ue.Widget.md#clipping)

#### Defined in

[ue/ue.d.ts:10952](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10952)

___

### Cursor

• **Cursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[Cursor](ue_ue.Widget.md#cursor)

#### Defined in

[ue/ue.d.ts:10951](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10951)

___

### DesignerFlags

• **DesignerFlags**: `number`

#### Inherited from

[Widget](ue_ue.Widget.md).[DesignerFlags](ue_ue.Widget.md#designerflags)

#### Defined in

[ue/ue.d.ts:10958](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10958)

___

### DisplayLabel

• **DisplayLabel**: `string`

#### Inherited from

[Widget](ue_ue.Widget.md).[DisplayLabel](ue_ue.Widget.md#displaylabel)

#### Defined in

[ue/ue.d.ts:10959](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10959)

___

### FlowDirectionPreference

• **FlowDirectionPreference**: [`EFlowDirectionPreference`](../enums/ue_ue.EFlowDirectionPreference.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[FlowDirectionPreference](ue_ue.Widget.md#flowdirectionpreference)

#### Defined in

[ue/ue.d.ts:10956](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10956)

___

### IndentHandle

• **IndentHandle**: `boolean`

#### Defined in

[ue/ue.d.ts:61037](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61037)

___

### IsFocusable

• **IsFocusable**: `boolean`

#### Defined in

[ue/ue.d.ts:61042](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61042)

___

### Locked

• **Locked**: `boolean`

#### Defined in

[ue/ue.d.ts:61038](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61038)

___

### MaxValue

• **MaxValue**: `number`

#### Defined in

[ue/ue.d.ts:61032](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61032)

___

### MinValue

• **MinValue**: `number`

#### Defined in

[ue/ue.d.ts:61031](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61031)

___

### MouseUsesStep

• **MouseUsesStep**: `boolean`

#### Defined in

[ue/ue.d.ts:61039](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61039)

___

### NativeBindings

• **NativeBindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyBinding`](ue_ue.PropertyBinding.md)\>

#### Inherited from

[Widget](ue_ue.Widget.md).[NativeBindings](ue_ue.Widget.md#nativebindings)

#### Defined in

[ue/ue.d.ts:10957](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10957)

___

### Navigation

• **Navigation**: [`WidgetNavigation`](ue_ue.WidgetNavigation.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[Navigation](ue_ue.Widget.md#navigation)

#### Defined in

[ue/ue.d.ts:10955](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10955)

___

### OnControllerCaptureBegin

• **OnControllerCaptureBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:61045](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61045)

___

### OnControllerCaptureEnd

• **OnControllerCaptureEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:61046](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61046)

___

### OnMouseCaptureBegin

• **OnMouseCaptureBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:61043](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61043)

___

### OnMouseCaptureEnd

• **OnMouseCaptureEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:61044](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61044)

___

### OnValueChanged

• **OnValueChanged**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Value`: `number`) => `void`\>

#### Defined in

[ue/ue.d.ts:61047](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61047)

___

### Orientation

• **Orientation**: [`EOrientation`](../enums/ue_ue.EOrientation.md)

#### Defined in

[ue/ue.d.ts:61034](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61034)

___

### RenderOpacity

• **RenderOpacity**: `number`

#### Inherited from

[Widget](ue_ue.Widget.md).[RenderOpacity](ue_ue.Widget.md#renderopacity)

#### Defined in

[ue/ue.d.ts:10954](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10954)

___

### RenderTransform

• **RenderTransform**: [`WidgetTransform`](ue_ue.WidgetTransform.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[RenderTransform](ue_ue.Widget.md#rendertransform)

#### Defined in

[ue/ue.d.ts:10932](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10932)

___

### RenderTransformPivot

• **RenderTransformPivot**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[RenderTransformPivot](ue_ue.Widget.md#rendertransformpivot)

#### Defined in

[ue/ue.d.ts:10933](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10933)

___

### RequiresControllerLock

• **RequiresControllerLock**: `boolean`

#### Defined in

[ue/ue.d.ts:61040](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61040)

___

### SliderBarColor

• **SliderBarColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:61035](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61035)

___

### SliderHandleColor

• **SliderHandleColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:61036](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61036)

___

### Slot

• **Slot**: [`PanelSlot`](ue_ue.PanelSlot.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[Slot](ue_ue.Widget.md#slot)

#### Defined in

[ue/ue.d.ts:10925](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10925)

___

### StepSize

• **StepSize**: `number`

#### Defined in

[ue/ue.d.ts:61041](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61041)

___

### ToolTipText

• **ToolTipText**: `string`

#### Inherited from

[Widget](ue_ue.Widget.md).[ToolTipText](ue_ue.Widget.md#tooltiptext)

#### Defined in

[ue/ue.d.ts:10927](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10927)

___

### ToolTipTextDelegate

• **ToolTipTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[Widget](ue_ue.Widget.md).[ToolTipTextDelegate](ue_ue.Widget.md#tooltiptextdelegate)

#### Defined in

[ue/ue.d.ts:10928](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10928)

___

### ToolTipWidget

• **ToolTipWidget**: [`Widget`](ue_ue.Widget.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[ToolTipWidget](ue_ue.Widget.md#tooltipwidget)

#### Defined in

[ue/ue.d.ts:10929](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10929)

___

### ToolTipWidgetDelegate

• **ToolTipWidgetDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`Widget`](ue_ue.Widget.md)\>

#### Inherited from

[Widget](ue_ue.Widget.md).[ToolTipWidgetDelegate](ue_ue.Widget.md#tooltipwidgetdelegate)

#### Defined in

[ue/ue.d.ts:10930](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10930)

___

### Value

• **Value**: `number`

#### Defined in

[ue/ue.d.ts:61029](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61029)

___

### ValueDelegate

• **ValueDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `number`\>

#### Defined in

[ue/ue.d.ts:61030](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61030)

___

### Visibility

• **Visibility**: [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[Visibility](ue_ue.Widget.md#visibility)

#### Defined in

[ue/ue.d.ts:10953](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10953)

___

### VisibilityDelegate

• **VisibilityDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)\>

#### Inherited from

[Widget](ue_ue.Widget.md).[VisibilityDelegate](ue_ue.Widget.md#visibilitydelegate)

#### Defined in

[ue/ue.d.ts:10931](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10931)

___

### WidgetStyle

• **WidgetStyle**: [`SliderStyle`](ue_ue.SliderStyle.md)

#### Defined in

[ue/ue.d.ts:61033](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61033)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[__tid_Object__](ue_ue.Widget.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_Slider\_\_

• **\_\_tid\_Slider\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:61062](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61062)

___

### \_\_tid\_Visual\_\_

• **\_\_tid\_Visual\_\_**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[__tid_Visual__](ue_ue.Widget.md#__tid_visual__)

#### Defined in

[ue/ue.d.ts:10673](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10673)

___

### \_\_tid\_Widget\_\_

• **\_\_tid\_Widget\_\_**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[__tid_Widget__](ue_ue.Widget.md#__tid_widget__)

#### Defined in

[ue/ue.d.ts:11029](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11029)

___

### bCanChildrenBeAccessible

• **bCanChildrenBeAccessible**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[bCanChildrenBeAccessible](ue_ue.Widget.md#bcanchildrenbeaccessible)

#### Defined in

[ue/ue.d.ts:10939](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10939)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[bCreatedByConstructionScript](ue_ue.Widget.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:10935](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10935)

___

### bExpandedInDesigner

• **bExpandedInDesigner**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[bExpandedInDesigner](ue_ue.Widget.md#bexpandedindesigner)

#### Defined in

[ue/ue.d.ts:10949](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10949)

___

### bHiddenInDesigner

• **bHiddenInDesigner**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[bHiddenInDesigner](ue_ue.Widget.md#bhiddenindesigner)

#### Defined in

[ue/ue.d.ts:10948](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10948)

___

### bIsEnabled

• **bIsEnabled**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[bIsEnabled](ue_ue.Widget.md#bisenabled)

#### Defined in

[ue/ue.d.ts:10936](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10936)

___

### bIsEnabledDelegate

• **bIsEnabledDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `boolean`\>

#### Inherited from

[Widget](ue_ue.Widget.md).[bIsEnabledDelegate](ue_ue.Widget.md#bisenableddelegate)

#### Defined in

[ue/ue.d.ts:10926](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10926)

___

### bIsVariable

• **bIsVariable**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[bIsVariable](ue_ue.Widget.md#bisvariable)

#### Defined in

[ue/ue.d.ts:10934](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10934)

___

### bIsVolatile

• **bIsVolatile**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[bIsVolatile](ue_ue.Widget.md#bisvolatile)

#### Defined in

[ue/ue.d.ts:10947](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10947)

___

### bLockedInDesigner

• **bLockedInDesigner**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[bLockedInDesigner](ue_ue.Widget.md#blockedindesigner)

#### Defined in

[ue/ue.d.ts:10950](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10950)

___

### bOverrideAccessibleDefaults

• **bOverrideAccessibleDefaults**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[bOverrideAccessibleDefaults](ue_ue.Widget.md#boverrideaccessibledefaults)

#### Defined in

[ue/ue.d.ts:10938](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10938)

___

### bOverride\_Cursor

• **bOverride\_Cursor**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[bOverride_Cursor](ue_ue.Widget.md#boverride_cursor)

#### Defined in

[ue/ue.d.ts:10937](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10937)

## Methods

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

[Widget](ue_ue.Widget.md).[CreateDefaultSubobject](ue_ue.Widget.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

[Widget](ue_ue.Widget.md).[ExecuteUbergraph](ue_ue.Widget.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### ForceLayoutPrepass

▸ **ForceLayoutPrepass**(): `void`

#### Returns

`void`

#### Inherited from

[Widget](ue_ue.Widget.md).[ForceLayoutPrepass](ue_ue.Widget.md#forcelayoutprepass)

#### Defined in

[ue/ue.d.ts:10961](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10961)

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

[Widget](ue_ue.Widget.md).[ForceVolatile](ue_ue.Widget.md#forcevolatile)

#### Defined in

[ue/ue.d.ts:10962](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10962)

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

[Widget](ue_ue.Widget.md).[GenerateWidgetForObject__DelegateSignature](ue_ue.Widget.md#generatewidgetforobject__delegatesignature)

#### Defined in

[ue/ue.d.ts:10963](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10963)

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

[Widget](ue_ue.Widget.md).[GenerateWidgetForString__DelegateSignature](ue_ue.Widget.md#generatewidgetforstring__delegatesignature)

#### Defined in

[ue/ue.d.ts:10964](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10964)

___

### GetBool\_\_DelegateSignature

▸ **GetBool__DelegateSignature**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[GetBool__DelegateSignature](ue_ue.Widget.md#getbool__delegatesignature)

#### Defined in

[ue/ue.d.ts:10965](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10965)

___

### GetCachedGeometry

▸ **GetCachedGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetCachedGeometry](ue_ue.Widget.md#getcachedgeometry)

#### Defined in

[ue/ue.d.ts:10966](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10966)

___

### GetCheckBoxState\_\_DelegateSignature

▸ **GetCheckBoxState__DelegateSignature**(): [`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Returns

[`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetCheckBoxState__DelegateSignature](ue_ue.Widget.md#getcheckboxstate__delegatesignature)

#### Defined in

[ue/ue.d.ts:10967](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10967)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetClass](ue_ue.Widget.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetClipping

▸ **GetClipping**(): [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Returns

[`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetClipping](ue_ue.Widget.md#getclipping)

#### Defined in

[ue/ue.d.ts:10968](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10968)

___

### GetDesiredSize

▸ **GetDesiredSize**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetDesiredSize](ue_ue.Widget.md#getdesiredsize)

#### Defined in

[ue/ue.d.ts:10969](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10969)

___

### GetFloat\_\_DelegateSignature

▸ **GetFloat__DelegateSignature**(): `number`

#### Returns

`number`

#### Inherited from

[Widget](ue_ue.Widget.md).[GetFloat__DelegateSignature](ue_ue.Widget.md#getfloat__delegatesignature)

#### Defined in

[ue/ue.d.ts:10970](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10970)

___

### GetGameInstance

▸ **GetGameInstance**(): [`GameInstance`](ue_ue.GameInstance.md)

#### Returns

[`GameInstance`](ue_ue.GameInstance.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetGameInstance](ue_ue.Widget.md#getgameinstance)

#### Defined in

[ue/ue.d.ts:10971](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10971)

___

### GetInt32\_\_DelegateSignature

▸ **GetInt32__DelegateSignature**(): `number`

#### Returns

`number`

#### Inherited from

[Widget](ue_ue.Widget.md).[GetInt32__DelegateSignature](ue_ue.Widget.md#getint32__delegatesignature)

#### Defined in

[ue/ue.d.ts:10972](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10972)

___

### GetIsEnabled

▸ **GetIsEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[GetIsEnabled](ue_ue.Widget.md#getisenabled)

#### Defined in

[ue/ue.d.ts:10973](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10973)

___

### GetLinearColor\_\_DelegateSignature

▸ **GetLinearColor__DelegateSignature**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetLinearColor__DelegateSignature](ue_ue.Widget.md#getlinearcolor__delegatesignature)

#### Defined in

[ue/ue.d.ts:10974](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10974)

___

### GetMouseCursor\_\_DelegateSignature

▸ **GetMouseCursor__DelegateSignature**(): [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Returns

[`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetMouseCursor__DelegateSignature](ue_ue.Widget.md#getmousecursor__delegatesignature)

#### Defined in

[ue/ue.d.ts:10975](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10975)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Widget](ue_ue.Widget.md).[GetName](ue_ue.Widget.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetNormalizedValue

▸ **GetNormalizedValue**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:61048](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61048)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetOuter](ue_ue.Widget.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetOwningLocalPlayer

▸ **GetOwningLocalPlayer**(): [`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Returns

[`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetOwningLocalPlayer](ue_ue.Widget.md#getowninglocalplayer)

#### Defined in

[ue/ue.d.ts:10976](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10976)

___

### GetOwningPlayer

▸ **GetOwningPlayer**(): [`PlayerController`](ue_ue.PlayerController.md)

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetOwningPlayer](ue_ue.Widget.md#getowningplayer)

#### Defined in

[ue/ue.d.ts:10977](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10977)

___

### GetPaintSpaceGeometry

▸ **GetPaintSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetPaintSpaceGeometry](ue_ue.Widget.md#getpaintspacegeometry)

#### Defined in

[ue/ue.d.ts:10978](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10978)

___

### GetParent

▸ **GetParent**(): [`PanelWidget`](ue_ue.PanelWidget.md)

#### Returns

[`PanelWidget`](ue_ue.PanelWidget.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetParent](ue_ue.Widget.md#getparent)

#### Defined in

[ue/ue.d.ts:10979](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10979)

___

### GetRenderOpacity

▸ **GetRenderOpacity**(): `number`

#### Returns

`number`

#### Inherited from

[Widget](ue_ue.Widget.md).[GetRenderOpacity](ue_ue.Widget.md#getrenderopacity)

#### Defined in

[ue/ue.d.ts:10980](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10980)

___

### GetRenderTransformAngle

▸ **GetRenderTransformAngle**(): `number`

#### Returns

`number`

#### Inherited from

[Widget](ue_ue.Widget.md).[GetRenderTransformAngle](ue_ue.Widget.md#getrendertransformangle)

#### Defined in

[ue/ue.d.ts:10981](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10981)

___

### GetSlateBrush\_\_DelegateSignature

▸ **GetSlateBrush__DelegateSignature**(): [`SlateBrush`](ue_ue.SlateBrush.md)

#### Returns

[`SlateBrush`](ue_ue.SlateBrush.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetSlateBrush__DelegateSignature](ue_ue.Widget.md#getslatebrush__delegatesignature)

#### Defined in

[ue/ue.d.ts:10982](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10982)

___

### GetSlateColor\_\_DelegateSignature

▸ **GetSlateColor__DelegateSignature**(): [`SlateColor`](ue_ue.SlateColor.md)

#### Returns

[`SlateColor`](ue_ue.SlateColor.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetSlateColor__DelegateSignature](ue_ue.Widget.md#getslatecolor__delegatesignature)

#### Defined in

[ue/ue.d.ts:10983](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10983)

___

### GetSlateVisibility\_\_DelegateSignature

▸ **GetSlateVisibility__DelegateSignature**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetSlateVisibility__DelegateSignature](ue_ue.Widget.md#getslatevisibility__delegatesignature)

#### Defined in

[ue/ue.d.ts:10984](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10984)

___

### GetText\_\_DelegateSignature

▸ **GetText__DelegateSignature**(): `string`

#### Returns

`string`

#### Inherited from

[Widget](ue_ue.Widget.md).[GetText__DelegateSignature](ue_ue.Widget.md#gettext__delegatesignature)

#### Defined in

[ue/ue.d.ts:10985](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10985)

___

### GetTickSpaceGeometry

▸ **GetTickSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetTickSpaceGeometry](ue_ue.Widget.md#gettickspacegeometry)

#### Defined in

[ue/ue.d.ts:10986](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10986)

___

### GetValue

▸ **GetValue**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:61049](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61049)

___

### GetVisibility

▸ **GetVisibility**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetVisibility](ue_ue.Widget.md#getvisibility)

#### Defined in

[ue/ue.d.ts:10987](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10987)

___

### GetWidget\_\_DelegateSignature

▸ **GetWidget__DelegateSignature**(): [`Widget`](ue_ue.Widget.md)

#### Returns

[`Widget`](ue_ue.Widget.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetWidget__DelegateSignature](ue_ue.Widget.md#getwidget__delegatesignature)

#### Defined in

[ue/ue.d.ts:10988](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10988)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetWorld](ue_ue.Widget.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### HasAnyUserFocus

▸ **HasAnyUserFocus**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[HasAnyUserFocus](ue_ue.Widget.md#hasanyuserfocus)

#### Defined in

[ue/ue.d.ts:10989](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10989)

___

### HasFocusedDescendants

▸ **HasFocusedDescendants**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[HasFocusedDescendants](ue_ue.Widget.md#hasfocuseddescendants)

#### Defined in

[ue/ue.d.ts:10990](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10990)

___

### HasKeyboardFocus

▸ **HasKeyboardFocus**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[HasKeyboardFocus](ue_ue.Widget.md#haskeyboardfocus)

#### Defined in

[ue/ue.d.ts:10991](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10991)

___

### HasMouseCapture

▸ **HasMouseCapture**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[HasMouseCapture](ue_ue.Widget.md#hasmousecapture)

#### Defined in

[ue/ue.d.ts:10992](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10992)

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

[Widget](ue_ue.Widget.md).[HasMouseCaptureByUser](ue_ue.Widget.md#hasmousecapturebyuser)

#### Defined in

[ue/ue.d.ts:10993](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10993)

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

[Widget](ue_ue.Widget.md).[HasUserFocus](ue_ue.Widget.md#hasuserfocus)

#### Defined in

[ue/ue.d.ts:10994](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10994)

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

[Widget](ue_ue.Widget.md).[HasUserFocusedDescendants](ue_ue.Widget.md#hasuserfocuseddescendants)

#### Defined in

[ue/ue.d.ts:10995](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10995)

___

### InvalidateLayoutAndVolatility

▸ **InvalidateLayoutAndVolatility**(): `void`

#### Returns

`void`

#### Inherited from

[Widget](ue_ue.Widget.md).[InvalidateLayoutAndVolatility](ue_ue.Widget.md#invalidatelayoutandvolatility)

#### Defined in

[ue/ue.d.ts:10996](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10996)

___

### IsHovered

▸ **IsHovered**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[IsHovered](ue_ue.Widget.md#ishovered)

#### Defined in

[ue/ue.d.ts:10997](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10997)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[IsVisible](ue_ue.Widget.md#isvisible)

#### Defined in

[ue/ue.d.ts:10998](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10998)

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

[Widget](ue_ue.Widget.md).[OnPointerEvent__DelegateSignature](ue_ue.Widget.md#onpointerevent__delegatesignature)

#### Defined in

[ue/ue.d.ts:10999](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10999)

___

### OnReply\_\_DelegateSignature

▸ **OnReply__DelegateSignature**(): [`EventReply`](ue_ue.EventReply.md)

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[OnReply__DelegateSignature](ue_ue.Widget.md#onreply__delegatesignature)

#### Defined in

[ue/ue.d.ts:11000](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11000)

___

### RemoveFromParent

▸ **RemoveFromParent**(): `void`

#### Returns

`void`

#### Inherited from

[Widget](ue_ue.Widget.md).[RemoveFromParent](ue_ue.Widget.md#removefromparent)

#### Defined in

[ue/ue.d.ts:11001](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11001)

___

### ResetCursor

▸ **ResetCursor**(): `void`

#### Returns

`void`

#### Inherited from

[Widget](ue_ue.Widget.md).[ResetCursor](ue_ue.Widget.md#resetcursor)

#### Defined in

[ue/ue.d.ts:11002](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11002)

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

[Widget](ue_ue.Widget.md).[SetAllNavigationRules](ue_ue.Widget.md#setallnavigationrules)

#### Defined in

[ue/ue.d.ts:11003](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11003)

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

[Widget](ue_ue.Widget.md).[SetClipping](ue_ue.Widget.md#setclipping)

#### Defined in

[ue/ue.d.ts:11004](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11004)

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

[Widget](ue_ue.Widget.md).[SetCursor](ue_ue.Widget.md#setcursor)

#### Defined in

[ue/ue.d.ts:11005](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11005)

___

### SetFocus

▸ **SetFocus**(): `void`

#### Returns

`void`

#### Inherited from

[Widget](ue_ue.Widget.md).[SetFocus](ue_ue.Widget.md#setfocus)

#### Defined in

[ue/ue.d.ts:11006](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11006)

___

### SetIndentHandle

▸ **SetIndentHandle**(`InValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InValue` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:61050](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61050)

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

[Widget](ue_ue.Widget.md).[SetIsEnabled](ue_ue.Widget.md#setisenabled)

#### Defined in

[ue/ue.d.ts:11007](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11007)

___

### SetKeyboardFocus

▸ **SetKeyboardFocus**(): `void`

#### Returns

`void`

#### Inherited from

[Widget](ue_ue.Widget.md).[SetKeyboardFocus](ue_ue.Widget.md#setkeyboardfocus)

#### Defined in

[ue/ue.d.ts:11008](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11008)

___

### SetLocked

▸ **SetLocked**(`InValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InValue` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:61051](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61051)

___

### SetMaxValue

▸ **SetMaxValue**(`InValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InValue` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:61052](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61052)

___

### SetMinValue

▸ **SetMinValue**(`InValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InValue` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:61053](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61053)

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

[Widget](ue_ue.Widget.md).[SetNavigationRule](ue_ue.Widget.md#setnavigationrule)

#### Defined in

[ue/ue.d.ts:11009](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11009)

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

[Widget](ue_ue.Widget.md).[SetNavigationRuleBase](ue_ue.Widget.md#setnavigationrulebase)

#### Defined in

[ue/ue.d.ts:11010](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11010)

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

[Widget](ue_ue.Widget.md).[SetNavigationRuleCustom](ue_ue.Widget.md#setnavigationrulecustom)

#### Defined in

[ue/ue.d.ts:11011](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11011)

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

[Widget](ue_ue.Widget.md).[SetNavigationRuleCustomBoundary](ue_ue.Widget.md#setnavigationrulecustomboundary)

#### Defined in

[ue/ue.d.ts:11012](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11012)

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

[Widget](ue_ue.Widget.md).[SetNavigationRuleExplicit](ue_ue.Widget.md#setnavigationruleexplicit)

#### Defined in

[ue/ue.d.ts:11013](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11013)

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

[Widget](ue_ue.Widget.md).[SetRenderOpacity](ue_ue.Widget.md#setrenderopacity)

#### Defined in

[ue/ue.d.ts:11014](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11014)

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

[Widget](ue_ue.Widget.md).[SetRenderScale](ue_ue.Widget.md#setrenderscale)

#### Defined in

[ue/ue.d.ts:11015](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11015)

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

[Widget](ue_ue.Widget.md).[SetRenderShear](ue_ue.Widget.md#setrendershear)

#### Defined in

[ue/ue.d.ts:11016](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11016)

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

[Widget](ue_ue.Widget.md).[SetRenderTransform](ue_ue.Widget.md#setrendertransform)

#### Defined in

[ue/ue.d.ts:11017](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11017)

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

[Widget](ue_ue.Widget.md).[SetRenderTransformAngle](ue_ue.Widget.md#setrendertransformangle)

#### Defined in

[ue/ue.d.ts:11018](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11018)

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

[Widget](ue_ue.Widget.md).[SetRenderTransformPivot](ue_ue.Widget.md#setrendertransformpivot)

#### Defined in

[ue/ue.d.ts:11019](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11019)

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

[Widget](ue_ue.Widget.md).[SetRenderTranslation](ue_ue.Widget.md#setrendertranslation)

#### Defined in

[ue/ue.d.ts:11020](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11020)

___

### SetSliderBarColor

▸ **SetSliderBarColor**(`InValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InValue` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:61054](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61054)

___

### SetSliderHandleColor

▸ **SetSliderHandleColor**(`InValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InValue` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:61055](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61055)

___

### SetStepSize

▸ **SetStepSize**(`InValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InValue` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:61056](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61056)

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

[Widget](ue_ue.Widget.md).[SetToolTip](ue_ue.Widget.md#settooltip)

#### Defined in

[ue/ue.d.ts:11021](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11021)

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

[Widget](ue_ue.Widget.md).[SetToolTipText](ue_ue.Widget.md#settooltiptext)

#### Defined in

[ue/ue.d.ts:11022](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11022)

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

[Widget](ue_ue.Widget.md).[SetUserFocus](ue_ue.Widget.md#setuserfocus)

#### Defined in

[ue/ue.d.ts:11023](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11023)

___

### SetValue

▸ **SetValue**(`InValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InValue` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:61057](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61057)

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

[Widget](ue_ue.Widget.md).[SetVisibility](ue_ue.Widget.md#setvisibility)

#### Defined in

[ue/ue.d.ts:11024](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11024)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Slider`](ue_ue.Slider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Slider`](ue_ue.Slider.md)

#### Overrides

[Widget](ue_ue.Widget.md).[Find](ue_ue.Widget.md#find)

#### Defined in

[ue/ue.d.ts:61059](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61059)

___

### Load

▸ `Static` **Load**(`InName`): [`Slider`](ue_ue.Slider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Slider`](ue_ue.Slider.md)

#### Overrides

[Widget](ue_ue.Widget.md).[Load](ue_ue.Widget.md#load)

#### Defined in

[ue/ue.d.ts:61060](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61060)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Widget](ue_ue.Widget.md).[StaticClass](ue_ue.Widget.md#staticclass)

#### Defined in

[ue/ue.d.ts:61058](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61058)
