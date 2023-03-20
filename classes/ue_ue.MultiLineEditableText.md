[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MultiLineEditableText

# Class: MultiLineEditableText

[ue/ue](../modules/ue_ue.md).MultiLineEditableText

## Hierarchy

- [`TextLayoutWidget`](ue_ue.TextLayoutWidget.md)

  ↳ **`MultiLineEditableText`**

## Table of contents

### Constructors

- [constructor](ue_ue.MultiLineEditableText.md#constructor)

### Properties

- [AccessibleBehavior](ue_ue.MultiLineEditableText.md#accessiblebehavior)
- [AccessibleSummaryBehavior](ue_ue.MultiLineEditableText.md#accessiblesummarybehavior)
- [AccessibleSummaryText](ue_ue.MultiLineEditableText.md#accessiblesummarytext)
- [AccessibleSummaryTextDelegate](ue_ue.MultiLineEditableText.md#accessiblesummarytextdelegate)
- [AccessibleText](ue_ue.MultiLineEditableText.md#accessibletext)
- [AccessibleTextDelegate](ue_ue.MultiLineEditableText.md#accessibletextdelegate)
- [AccessibleWidgetData](ue_ue.MultiLineEditableText.md#accessiblewidgetdata)
- [AllowContextMenu](ue_ue.MultiLineEditableText.md#allowcontextmenu)
- [AutoWrapText](ue_ue.MultiLineEditableText.md#autowraptext)
- [CategoryName](ue_ue.MultiLineEditableText.md#categoryname)
- [ClearKeyboardFocusOnCommit](ue_ue.MultiLineEditableText.md#clearkeyboardfocusoncommit)
- [ClearTextSelectionOnFocusLoss](ue_ue.MultiLineEditableText.md#cleartextselectiononfocusloss)
- [Clipping](ue_ue.MultiLineEditableText.md#clipping)
- [Cursor](ue_ue.MultiLineEditableText.md#cursor)
- [DesignerFlags](ue_ue.MultiLineEditableText.md#designerflags)
- [DisplayLabel](ue_ue.MultiLineEditableText.md#displaylabel)
- [FlowDirectionPreference](ue_ue.MultiLineEditableText.md#flowdirectionpreference)
- [Font](ue_ue.MultiLineEditableText.md#font)
- [HintText](ue_ue.MultiLineEditableText.md#hinttext)
- [HintTextDelegate](ue_ue.MultiLineEditableText.md#hinttextdelegate)
- [Justification](ue_ue.MultiLineEditableText.md#justification)
- [LineHeightPercentage](ue_ue.MultiLineEditableText.md#lineheightpercentage)
- [Margin](ue_ue.MultiLineEditableText.md#margin)
- [NativeBindings](ue_ue.MultiLineEditableText.md#nativebindings)
- [Navigation](ue_ue.MultiLineEditableText.md#navigation)
- [OnTextChanged](ue_ue.MultiLineEditableText.md#ontextchanged)
- [OnTextCommitted](ue_ue.MultiLineEditableText.md#ontextcommitted)
- [RenderOpacity](ue_ue.MultiLineEditableText.md#renderopacity)
- [RenderTransform](ue_ue.MultiLineEditableText.md#rendertransform)
- [RenderTransformPivot](ue_ue.MultiLineEditableText.md#rendertransformpivot)
- [RevertTextOnEscape](ue_ue.MultiLineEditableText.md#reverttextonescape)
- [SelectAllTextWhenFocused](ue_ue.MultiLineEditableText.md#selectalltextwhenfocused)
- [ShapedTextOptions](ue_ue.MultiLineEditableText.md#shapedtextoptions)
- [Slot](ue_ue.MultiLineEditableText.md#slot)
- [Text](ue_ue.MultiLineEditableText.md#text)
- [ToolTipText](ue_ue.MultiLineEditableText.md#tooltiptext)
- [ToolTipTextDelegate](ue_ue.MultiLineEditableText.md#tooltiptextdelegate)
- [ToolTipWidget](ue_ue.MultiLineEditableText.md#tooltipwidget)
- [ToolTipWidgetDelegate](ue_ue.MultiLineEditableText.md#tooltipwidgetdelegate)
- [VirtualKeyboardDismissAction](ue_ue.MultiLineEditableText.md#virtualkeyboarddismissaction)
- [VirtualKeyboardOptions](ue_ue.MultiLineEditableText.md#virtualkeyboardoptions)
- [Visibility](ue_ue.MultiLineEditableText.md#visibility)
- [VisibilityDelegate](ue_ue.MultiLineEditableText.md#visibilitydelegate)
- [WidgetStyle](ue_ue.MultiLineEditableText.md#widgetstyle)
- [WrapTextAt](ue_ue.MultiLineEditableText.md#wraptextat)
- [WrappingPolicy](ue_ue.MultiLineEditableText.md#wrappingpolicy)
- [\_\_tid\_MultiLineEditableText\_\_](ue_ue.MultiLineEditableText.md#__tid_multilineeditabletext__)
- [\_\_tid\_Object\_\_](ue_ue.MultiLineEditableText.md#__tid_object__)
- [\_\_tid\_TextLayoutWidget\_\_](ue_ue.MultiLineEditableText.md#__tid_textlayoutwidget__)
- [\_\_tid\_Visual\_\_](ue_ue.MultiLineEditableText.md#__tid_visual__)
- [\_\_tid\_Widget\_\_](ue_ue.MultiLineEditableText.md#__tid_widget__)
- [bCanChildrenBeAccessible](ue_ue.MultiLineEditableText.md#bcanchildrenbeaccessible)
- [bCreatedByConstructionScript](ue_ue.MultiLineEditableText.md#bcreatedbyconstructionscript)
- [bExpandedInDesigner](ue_ue.MultiLineEditableText.md#bexpandedindesigner)
- [bHiddenInDesigner](ue_ue.MultiLineEditableText.md#bhiddenindesigner)
- [bIsEnabled](ue_ue.MultiLineEditableText.md#bisenabled)
- [bIsEnabledDelegate](ue_ue.MultiLineEditableText.md#bisenableddelegate)
- [bIsReadOnly](ue_ue.MultiLineEditableText.md#bisreadonly)
- [bIsVariable](ue_ue.MultiLineEditableText.md#bisvariable)
- [bIsVolatile](ue_ue.MultiLineEditableText.md#bisvolatile)
- [bLockedInDesigner](ue_ue.MultiLineEditableText.md#blockedindesigner)
- [bOverrideAccessibleDefaults](ue_ue.MultiLineEditableText.md#boverrideaccessibledefaults)
- [bOverride\_Cursor](ue_ue.MultiLineEditableText.md#boverride_cursor)

### Methods

- [CreateDefaultSubobject](ue_ue.MultiLineEditableText.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MultiLineEditableText.md#executeubergraph)
- [ForceLayoutPrepass](ue_ue.MultiLineEditableText.md#forcelayoutprepass)
- [ForceVolatile](ue_ue.MultiLineEditableText.md#forcevolatile)
- [GenerateWidgetForObject\_\_DelegateSignature](ue_ue.MultiLineEditableText.md#generatewidgetforobject__delegatesignature)
- [GenerateWidgetForString\_\_DelegateSignature](ue_ue.MultiLineEditableText.md#generatewidgetforstring__delegatesignature)
- [GetBool\_\_DelegateSignature](ue_ue.MultiLineEditableText.md#getbool__delegatesignature)
- [GetCachedGeometry](ue_ue.MultiLineEditableText.md#getcachedgeometry)
- [GetCheckBoxState\_\_DelegateSignature](ue_ue.MultiLineEditableText.md#getcheckboxstate__delegatesignature)
- [GetClass](ue_ue.MultiLineEditableText.md#getclass)
- [GetClipping](ue_ue.MultiLineEditableText.md#getclipping)
- [GetDesiredSize](ue_ue.MultiLineEditableText.md#getdesiredsize)
- [GetFloat\_\_DelegateSignature](ue_ue.MultiLineEditableText.md#getfloat__delegatesignature)
- [GetGameInstance](ue_ue.MultiLineEditableText.md#getgameinstance)
- [GetHintText](ue_ue.MultiLineEditableText.md#gethinttext)
- [GetInt32\_\_DelegateSignature](ue_ue.MultiLineEditableText.md#getint32__delegatesignature)
- [GetIsEnabled](ue_ue.MultiLineEditableText.md#getisenabled)
- [GetLinearColor\_\_DelegateSignature](ue_ue.MultiLineEditableText.md#getlinearcolor__delegatesignature)
- [GetMouseCursor\_\_DelegateSignature](ue_ue.MultiLineEditableText.md#getmousecursor__delegatesignature)
- [GetName](ue_ue.MultiLineEditableText.md#getname)
- [GetOuter](ue_ue.MultiLineEditableText.md#getouter)
- [GetOwningLocalPlayer](ue_ue.MultiLineEditableText.md#getowninglocalplayer)
- [GetOwningPlayer](ue_ue.MultiLineEditableText.md#getowningplayer)
- [GetPaintSpaceGeometry](ue_ue.MultiLineEditableText.md#getpaintspacegeometry)
- [GetParent](ue_ue.MultiLineEditableText.md#getparent)
- [GetRenderOpacity](ue_ue.MultiLineEditableText.md#getrenderopacity)
- [GetRenderTransformAngle](ue_ue.MultiLineEditableText.md#getrendertransformangle)
- [GetSlateBrush\_\_DelegateSignature](ue_ue.MultiLineEditableText.md#getslatebrush__delegatesignature)
- [GetSlateColor\_\_DelegateSignature](ue_ue.MultiLineEditableText.md#getslatecolor__delegatesignature)
- [GetSlateVisibility\_\_DelegateSignature](ue_ue.MultiLineEditableText.md#getslatevisibility__delegatesignature)
- [GetText](ue_ue.MultiLineEditableText.md#gettext)
- [GetText\_\_DelegateSignature](ue_ue.MultiLineEditableText.md#gettext__delegatesignature)
- [GetTickSpaceGeometry](ue_ue.MultiLineEditableText.md#gettickspacegeometry)
- [GetVisibility](ue_ue.MultiLineEditableText.md#getvisibility)
- [GetWidget\_\_DelegateSignature](ue_ue.MultiLineEditableText.md#getwidget__delegatesignature)
- [GetWorld](ue_ue.MultiLineEditableText.md#getworld)
- [HasAnyUserFocus](ue_ue.MultiLineEditableText.md#hasanyuserfocus)
- [HasFocusedDescendants](ue_ue.MultiLineEditableText.md#hasfocuseddescendants)
- [HasKeyboardFocus](ue_ue.MultiLineEditableText.md#haskeyboardfocus)
- [HasMouseCapture](ue_ue.MultiLineEditableText.md#hasmousecapture)
- [HasMouseCaptureByUser](ue_ue.MultiLineEditableText.md#hasmousecapturebyuser)
- [HasUserFocus](ue_ue.MultiLineEditableText.md#hasuserfocus)
- [HasUserFocusedDescendants](ue_ue.MultiLineEditableText.md#hasuserfocuseddescendants)
- [InvalidateLayoutAndVolatility](ue_ue.MultiLineEditableText.md#invalidatelayoutandvolatility)
- [IsHovered](ue_ue.MultiLineEditableText.md#ishovered)
- [IsVisible](ue_ue.MultiLineEditableText.md#isvisible)
- [OnMultiLineEditableTextChangedEvent\_\_DelegateSignature](ue_ue.MultiLineEditableText.md#onmultilineeditabletextchangedevent__delegatesignature)
- [OnMultiLineEditableTextCommittedEvent\_\_DelegateSignature](ue_ue.MultiLineEditableText.md#onmultilineeditabletextcommittedevent__delegatesignature)
- [OnPointerEvent\_\_DelegateSignature](ue_ue.MultiLineEditableText.md#onpointerevent__delegatesignature)
- [OnReply\_\_DelegateSignature](ue_ue.MultiLineEditableText.md#onreply__delegatesignature)
- [RemoveFromParent](ue_ue.MultiLineEditableText.md#removefromparent)
- [ResetCursor](ue_ue.MultiLineEditableText.md#resetcursor)
- [SetAllNavigationRules](ue_ue.MultiLineEditableText.md#setallnavigationrules)
- [SetClipping](ue_ue.MultiLineEditableText.md#setclipping)
- [SetCursor](ue_ue.MultiLineEditableText.md#setcursor)
- [SetFocus](ue_ue.MultiLineEditableText.md#setfocus)
- [SetHintText](ue_ue.MultiLineEditableText.md#sethinttext)
- [SetIsEnabled](ue_ue.MultiLineEditableText.md#setisenabled)
- [SetIsReadOnly](ue_ue.MultiLineEditableText.md#setisreadonly)
- [SetJustification](ue_ue.MultiLineEditableText.md#setjustification)
- [SetKeyboardFocus](ue_ue.MultiLineEditableText.md#setkeyboardfocus)
- [SetNavigationRule](ue_ue.MultiLineEditableText.md#setnavigationrule)
- [SetNavigationRuleBase](ue_ue.MultiLineEditableText.md#setnavigationrulebase)
- [SetNavigationRuleCustom](ue_ue.MultiLineEditableText.md#setnavigationrulecustom)
- [SetNavigationRuleCustomBoundary](ue_ue.MultiLineEditableText.md#setnavigationrulecustomboundary)
- [SetNavigationRuleExplicit](ue_ue.MultiLineEditableText.md#setnavigationruleexplicit)
- [SetRenderOpacity](ue_ue.MultiLineEditableText.md#setrenderopacity)
- [SetRenderScale](ue_ue.MultiLineEditableText.md#setrenderscale)
- [SetRenderShear](ue_ue.MultiLineEditableText.md#setrendershear)
- [SetRenderTransform](ue_ue.MultiLineEditableText.md#setrendertransform)
- [SetRenderTransformAngle](ue_ue.MultiLineEditableText.md#setrendertransformangle)
- [SetRenderTransformPivot](ue_ue.MultiLineEditableText.md#setrendertransformpivot)
- [SetRenderTranslation](ue_ue.MultiLineEditableText.md#setrendertranslation)
- [SetText](ue_ue.MultiLineEditableText.md#settext)
- [SetToolTip](ue_ue.MultiLineEditableText.md#settooltip)
- [SetToolTipText](ue_ue.MultiLineEditableText.md#settooltiptext)
- [SetUserFocus](ue_ue.MultiLineEditableText.md#setuserfocus)
- [SetVisibility](ue_ue.MultiLineEditableText.md#setvisibility)
- [SetWidgetStyle](ue_ue.MultiLineEditableText.md#setwidgetstyle)
- [Find](ue_ue.MultiLineEditableText.md#find)
- [Load](ue_ue.MultiLineEditableText.md#load)
- [StaticClass](ue_ue.MultiLineEditableText.md#staticclass)

## Constructors

### constructor

• **new MultiLineEditableText**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[constructor](ue_ue.TextLayoutWidget.md#constructor)

## Properties

### AccessibleBehavior

• **AccessibleBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[AccessibleBehavior](ue_ue.TextLayoutWidget.md#accessiblebehavior)

___

### AccessibleSummaryBehavior

• **AccessibleSummaryBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[AccessibleSummaryBehavior](ue_ue.TextLayoutWidget.md#accessiblesummarybehavior)

___

### AccessibleSummaryText

• **AccessibleSummaryText**: `string`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[AccessibleSummaryText](ue_ue.TextLayoutWidget.md#accessiblesummarytext)

___

### AccessibleSummaryTextDelegate

• **AccessibleSummaryTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[AccessibleSummaryTextDelegate](ue_ue.TextLayoutWidget.md#accessiblesummarytextdelegate)

___

### AccessibleText

• **AccessibleText**: `string`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[AccessibleText](ue_ue.TextLayoutWidget.md#accessibletext)

___

### AccessibleTextDelegate

• **AccessibleTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[AccessibleTextDelegate](ue_ue.TextLayoutWidget.md#accessibletextdelegate)

___

### AccessibleWidgetData

• **AccessibleWidgetData**: [`SlateAccessibleWidgetData`](ue_ue.SlateAccessibleWidgetData.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[AccessibleWidgetData](ue_ue.TextLayoutWidget.md#accessiblewidgetdata)

___

### AllowContextMenu

• **AllowContextMenu**: `boolean`

___

### AutoWrapText

• **AutoWrapText**: `boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[AutoWrapText](ue_ue.TextLayoutWidget.md#autowraptext)

___

### CategoryName

• **CategoryName**: `string`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[CategoryName](ue_ue.TextLayoutWidget.md#categoryname)

___

### ClearKeyboardFocusOnCommit

• **ClearKeyboardFocusOnCommit**: `boolean`

___

### ClearTextSelectionOnFocusLoss

• **ClearTextSelectionOnFocusLoss**: `boolean`

___

### Clipping

• **Clipping**: [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[Clipping](ue_ue.TextLayoutWidget.md#clipping)

___

### Cursor

• **Cursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[Cursor](ue_ue.TextLayoutWidget.md#cursor)

___

### DesignerFlags

• **DesignerFlags**: `number`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[DesignerFlags](ue_ue.TextLayoutWidget.md#designerflags)

___

### DisplayLabel

• **DisplayLabel**: `string`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[DisplayLabel](ue_ue.TextLayoutWidget.md#displaylabel)

___

### FlowDirectionPreference

• **FlowDirectionPreference**: [`EFlowDirectionPreference`](../enums/ue_ue.EFlowDirectionPreference.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[FlowDirectionPreference](ue_ue.TextLayoutWidget.md#flowdirectionpreference)

___

### Font

• **Font**: [`SlateFontInfo`](ue_ue.SlateFontInfo.md)

___

### HintText

• **HintText**: `string`

___

### HintTextDelegate

• **HintTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

___

### Justification

• **Justification**: [`ETextJustify`](../enums/ue_ue.ETextJustify.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[Justification](ue_ue.TextLayoutWidget.md#justification)

___

### LineHeightPercentage

• **LineHeightPercentage**: `number`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[LineHeightPercentage](ue_ue.TextLayoutWidget.md#lineheightpercentage)

___

### Margin

• **Margin**: [`Margin`](ue_ue.Margin.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[Margin](ue_ue.TextLayoutWidget.md#margin)

___

### NativeBindings

• **NativeBindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyBinding`](ue_ue.PropertyBinding.md)\>

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[NativeBindings](ue_ue.TextLayoutWidget.md#nativebindings)

___

### Navigation

• **Navigation**: [`WidgetNavigation`](ue_ue.WidgetNavigation.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[Navigation](ue_ue.TextLayoutWidget.md#navigation)

___

### OnTextChanged

• **OnTextChanged**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Text`: `string`) => `void`\>

___

### OnTextCommitted

• **OnTextCommitted**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Text`: `string`, `CommitMethod`: [`ETextCommit`](../enums/ue_ue.ETextCommit.md)) => `void`\>

___

### RenderOpacity

• **RenderOpacity**: `number`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[RenderOpacity](ue_ue.TextLayoutWidget.md#renderopacity)

___

### RenderTransform

• **RenderTransform**: [`WidgetTransform`](ue_ue.WidgetTransform.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[RenderTransform](ue_ue.TextLayoutWidget.md#rendertransform)

___

### RenderTransformPivot

• **RenderTransformPivot**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[RenderTransformPivot](ue_ue.TextLayoutWidget.md#rendertransformpivot)

___

### RevertTextOnEscape

• **RevertTextOnEscape**: `boolean`

___

### SelectAllTextWhenFocused

• **SelectAllTextWhenFocused**: `boolean`

___

### ShapedTextOptions

• **ShapedTextOptions**: [`ShapedTextOptions`](ue_ue.ShapedTextOptions.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[ShapedTextOptions](ue_ue.TextLayoutWidget.md#shapedtextoptions)

___

### Slot

• **Slot**: [`PanelSlot`](ue_ue.PanelSlot.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[Slot](ue_ue.TextLayoutWidget.md#slot)

___

### Text

• **Text**: `string`

___

### ToolTipText

• **ToolTipText**: `string`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[ToolTipText](ue_ue.TextLayoutWidget.md#tooltiptext)

___

### ToolTipTextDelegate

• **ToolTipTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[ToolTipTextDelegate](ue_ue.TextLayoutWidget.md#tooltiptextdelegate)

___

### ToolTipWidget

• **ToolTipWidget**: [`Widget`](ue_ue.Widget.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[ToolTipWidget](ue_ue.TextLayoutWidget.md#tooltipwidget)

___

### ToolTipWidgetDelegate

• **ToolTipWidgetDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`Widget`](ue_ue.Widget.md)\>

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[ToolTipWidgetDelegate](ue_ue.TextLayoutWidget.md#tooltipwidgetdelegate)

___

### VirtualKeyboardDismissAction

• **VirtualKeyboardDismissAction**: [`EVirtualKeyboardDismissAction`](../enums/ue_ue.EVirtualKeyboardDismissAction.md)

___

### VirtualKeyboardOptions

• **VirtualKeyboardOptions**: [`VirtualKeyboardOptions`](ue_ue.VirtualKeyboardOptions.md)

___

### Visibility

• **Visibility**: [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[Visibility](ue_ue.TextLayoutWidget.md#visibility)

___

### VisibilityDelegate

• **VisibilityDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)\>

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[VisibilityDelegate](ue_ue.TextLayoutWidget.md#visibilitydelegate)

___

### WidgetStyle

• **WidgetStyle**: [`TextBlockStyle`](ue_ue.TextBlockStyle.md)

___

### WrapTextAt

• **WrapTextAt**: `number`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[WrapTextAt](ue_ue.TextLayoutWidget.md#wraptextat)

___

### WrappingPolicy

• **WrappingPolicy**: [`ETextWrappingPolicy`](../enums/ue_ue.ETextWrappingPolicy.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[WrappingPolicy](ue_ue.TextLayoutWidget.md#wrappingpolicy)

___

### \_\_tid\_MultiLineEditableText\_\_

• **\_\_tid\_MultiLineEditableText\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[__tid_Object__](ue_ue.TextLayoutWidget.md#__tid_object__)

___

### \_\_tid\_TextLayoutWidget\_\_

• **\_\_tid\_TextLayoutWidget\_\_**: `boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[__tid_TextLayoutWidget__](ue_ue.TextLayoutWidget.md#__tid_textlayoutwidget__)

___

### \_\_tid\_Visual\_\_

• **\_\_tid\_Visual\_\_**: `boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[__tid_Visual__](ue_ue.TextLayoutWidget.md#__tid_visual__)

___

### \_\_tid\_Widget\_\_

• **\_\_tid\_Widget\_\_**: `boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[__tid_Widget__](ue_ue.TextLayoutWidget.md#__tid_widget__)

___

### bCanChildrenBeAccessible

• **bCanChildrenBeAccessible**: `boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[bCanChildrenBeAccessible](ue_ue.TextLayoutWidget.md#bcanchildrenbeaccessible)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[bCreatedByConstructionScript](ue_ue.TextLayoutWidget.md#bcreatedbyconstructionscript)

___

### bExpandedInDesigner

• **bExpandedInDesigner**: `boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[bExpandedInDesigner](ue_ue.TextLayoutWidget.md#bexpandedindesigner)

___

### bHiddenInDesigner

• **bHiddenInDesigner**: `boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[bHiddenInDesigner](ue_ue.TextLayoutWidget.md#bhiddenindesigner)

___

### bIsEnabled

• **bIsEnabled**: `boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[bIsEnabled](ue_ue.TextLayoutWidget.md#bisenabled)

___

### bIsEnabledDelegate

• **bIsEnabledDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `boolean`\>

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[bIsEnabledDelegate](ue_ue.TextLayoutWidget.md#bisenableddelegate)

___

### bIsReadOnly

• **bIsReadOnly**: `boolean`

___

### bIsVariable

• **bIsVariable**: `boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[bIsVariable](ue_ue.TextLayoutWidget.md#bisvariable)

___

### bIsVolatile

• **bIsVolatile**: `boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[bIsVolatile](ue_ue.TextLayoutWidget.md#bisvolatile)

___

### bLockedInDesigner

• **bLockedInDesigner**: `boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[bLockedInDesigner](ue_ue.TextLayoutWidget.md#blockedindesigner)

___

### bOverrideAccessibleDefaults

• **bOverrideAccessibleDefaults**: `boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[bOverrideAccessibleDefaults](ue_ue.TextLayoutWidget.md#boverrideaccessibledefaults)

___

### bOverride\_Cursor

• **bOverride\_Cursor**: `boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[bOverride_Cursor](ue_ue.TextLayoutWidget.md#boverride_cursor)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[CreateDefaultSubobject](ue_ue.TextLayoutWidget.md#createdefaultsubobject)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[ExecuteUbergraph](ue_ue.TextLayoutWidget.md#executeubergraph)

___

### ForceLayoutPrepass

▸ **ForceLayoutPrepass**(): `void`

#### Returns

`void`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[ForceLayoutPrepass](ue_ue.TextLayoutWidget.md#forcelayoutprepass)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[ForceVolatile](ue_ue.TextLayoutWidget.md#forcevolatile)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GenerateWidgetForObject__DelegateSignature](ue_ue.TextLayoutWidget.md#generatewidgetforobject__delegatesignature)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GenerateWidgetForString__DelegateSignature](ue_ue.TextLayoutWidget.md#generatewidgetforstring__delegatesignature)

___

### GetBool\_\_DelegateSignature

▸ **GetBool__DelegateSignature**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetBool__DelegateSignature](ue_ue.TextLayoutWidget.md#getbool__delegatesignature)

___

### GetCachedGeometry

▸ **GetCachedGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetCachedGeometry](ue_ue.TextLayoutWidget.md#getcachedgeometry)

___

### GetCheckBoxState\_\_DelegateSignature

▸ **GetCheckBoxState__DelegateSignature**(): [`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Returns

[`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetCheckBoxState__DelegateSignature](ue_ue.TextLayoutWidget.md#getcheckboxstate__delegatesignature)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetClass](ue_ue.TextLayoutWidget.md#getclass)

___

### GetClipping

▸ **GetClipping**(): [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Returns

[`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetClipping](ue_ue.TextLayoutWidget.md#getclipping)

___

### GetDesiredSize

▸ **GetDesiredSize**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetDesiredSize](ue_ue.TextLayoutWidget.md#getdesiredsize)

___

### GetFloat\_\_DelegateSignature

▸ **GetFloat__DelegateSignature**(): `number`

#### Returns

`number`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetFloat__DelegateSignature](ue_ue.TextLayoutWidget.md#getfloat__delegatesignature)

___

### GetGameInstance

▸ **GetGameInstance**(): [`GameInstance`](ue_ue.GameInstance.md)

#### Returns

[`GameInstance`](ue_ue.GameInstance.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetGameInstance](ue_ue.TextLayoutWidget.md#getgameinstance)

___

### GetHintText

▸ **GetHintText**(): `string`

#### Returns

`string`

___

### GetInt32\_\_DelegateSignature

▸ **GetInt32__DelegateSignature**(): `number`

#### Returns

`number`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetInt32__DelegateSignature](ue_ue.TextLayoutWidget.md#getint32__delegatesignature)

___

### GetIsEnabled

▸ **GetIsEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetIsEnabled](ue_ue.TextLayoutWidget.md#getisenabled)

___

### GetLinearColor\_\_DelegateSignature

▸ **GetLinearColor__DelegateSignature**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetLinearColor__DelegateSignature](ue_ue.TextLayoutWidget.md#getlinearcolor__delegatesignature)

___

### GetMouseCursor\_\_DelegateSignature

▸ **GetMouseCursor__DelegateSignature**(): [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Returns

[`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetMouseCursor__DelegateSignature](ue_ue.TextLayoutWidget.md#getmousecursor__delegatesignature)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetName](ue_ue.TextLayoutWidget.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetOuter](ue_ue.TextLayoutWidget.md#getouter)

___

### GetOwningLocalPlayer

▸ **GetOwningLocalPlayer**(): [`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Returns

[`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetOwningLocalPlayer](ue_ue.TextLayoutWidget.md#getowninglocalplayer)

___

### GetOwningPlayer

▸ **GetOwningPlayer**(): [`PlayerController`](ue_ue.PlayerController.md)

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetOwningPlayer](ue_ue.TextLayoutWidget.md#getowningplayer)

___

### GetPaintSpaceGeometry

▸ **GetPaintSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetPaintSpaceGeometry](ue_ue.TextLayoutWidget.md#getpaintspacegeometry)

___

### GetParent

▸ **GetParent**(): [`PanelWidget`](ue_ue.PanelWidget.md)

#### Returns

[`PanelWidget`](ue_ue.PanelWidget.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetParent](ue_ue.TextLayoutWidget.md#getparent)

___

### GetRenderOpacity

▸ **GetRenderOpacity**(): `number`

#### Returns

`number`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetRenderOpacity](ue_ue.TextLayoutWidget.md#getrenderopacity)

___

### GetRenderTransformAngle

▸ **GetRenderTransformAngle**(): `number`

#### Returns

`number`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetRenderTransformAngle](ue_ue.TextLayoutWidget.md#getrendertransformangle)

___

### GetSlateBrush\_\_DelegateSignature

▸ **GetSlateBrush__DelegateSignature**(): [`SlateBrush`](ue_ue.SlateBrush.md)

#### Returns

[`SlateBrush`](ue_ue.SlateBrush.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetSlateBrush__DelegateSignature](ue_ue.TextLayoutWidget.md#getslatebrush__delegatesignature)

___

### GetSlateColor\_\_DelegateSignature

▸ **GetSlateColor__DelegateSignature**(): [`SlateColor`](ue_ue.SlateColor.md)

#### Returns

[`SlateColor`](ue_ue.SlateColor.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetSlateColor__DelegateSignature](ue_ue.TextLayoutWidget.md#getslatecolor__delegatesignature)

___

### GetSlateVisibility\_\_DelegateSignature

▸ **GetSlateVisibility__DelegateSignature**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetSlateVisibility__DelegateSignature](ue_ue.TextLayoutWidget.md#getslatevisibility__delegatesignature)

___

### GetText

▸ **GetText**(): `string`

#### Returns

`string`

___

### GetText\_\_DelegateSignature

▸ **GetText__DelegateSignature**(): `string`

#### Returns

`string`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetText__DelegateSignature](ue_ue.TextLayoutWidget.md#gettext__delegatesignature)

___

### GetTickSpaceGeometry

▸ **GetTickSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetTickSpaceGeometry](ue_ue.TextLayoutWidget.md#gettickspacegeometry)

___

### GetVisibility

▸ **GetVisibility**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetVisibility](ue_ue.TextLayoutWidget.md#getvisibility)

___

### GetWidget\_\_DelegateSignature

▸ **GetWidget__DelegateSignature**(): [`Widget`](ue_ue.Widget.md)

#### Returns

[`Widget`](ue_ue.Widget.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetWidget__DelegateSignature](ue_ue.TextLayoutWidget.md#getwidget__delegatesignature)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[GetWorld](ue_ue.TextLayoutWidget.md#getworld)

___

### HasAnyUserFocus

▸ **HasAnyUserFocus**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[HasAnyUserFocus](ue_ue.TextLayoutWidget.md#hasanyuserfocus)

___

### HasFocusedDescendants

▸ **HasFocusedDescendants**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[HasFocusedDescendants](ue_ue.TextLayoutWidget.md#hasfocuseddescendants)

___

### HasKeyboardFocus

▸ **HasKeyboardFocus**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[HasKeyboardFocus](ue_ue.TextLayoutWidget.md#haskeyboardfocus)

___

### HasMouseCapture

▸ **HasMouseCapture**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[HasMouseCapture](ue_ue.TextLayoutWidget.md#hasmousecapture)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[HasMouseCaptureByUser](ue_ue.TextLayoutWidget.md#hasmousecapturebyuser)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[HasUserFocus](ue_ue.TextLayoutWidget.md#hasuserfocus)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[HasUserFocusedDescendants](ue_ue.TextLayoutWidget.md#hasuserfocuseddescendants)

___

### InvalidateLayoutAndVolatility

▸ **InvalidateLayoutAndVolatility**(): `void`

#### Returns

`void`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[InvalidateLayoutAndVolatility](ue_ue.TextLayoutWidget.md#invalidatelayoutandvolatility)

___

### IsHovered

▸ **IsHovered**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[IsHovered](ue_ue.TextLayoutWidget.md#ishovered)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[IsVisible](ue_ue.TextLayoutWidget.md#isvisible)

___

### OnMultiLineEditableTextChangedEvent\_\_DelegateSignature

▸ **OnMultiLineEditableTextChangedEvent__DelegateSignature**(`Text`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Text` | `string` |

#### Returns

`void`

___

### OnMultiLineEditableTextCommittedEvent\_\_DelegateSignature

▸ **OnMultiLineEditableTextCommittedEvent__DelegateSignature**(`Text`, `CommitMethod`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Text` | `string` |
| `CommitMethod` | [`ETextCommit`](../enums/ue_ue.ETextCommit.md) |

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[OnPointerEvent__DelegateSignature](ue_ue.TextLayoutWidget.md#onpointerevent__delegatesignature)

___

### OnReply\_\_DelegateSignature

▸ **OnReply__DelegateSignature**(): [`EventReply`](ue_ue.EventReply.md)

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[OnReply__DelegateSignature](ue_ue.TextLayoutWidget.md#onreply__delegatesignature)

___

### RemoveFromParent

▸ **RemoveFromParent**(): `void`

#### Returns

`void`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[RemoveFromParent](ue_ue.TextLayoutWidget.md#removefromparent)

___

### ResetCursor

▸ **ResetCursor**(): `void`

#### Returns

`void`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[ResetCursor](ue_ue.TextLayoutWidget.md#resetcursor)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetAllNavigationRules](ue_ue.TextLayoutWidget.md#setallnavigationrules)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetClipping](ue_ue.TextLayoutWidget.md#setclipping)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetCursor](ue_ue.TextLayoutWidget.md#setcursor)

___

### SetFocus

▸ **SetFocus**(): `void`

#### Returns

`void`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetFocus](ue_ue.TextLayoutWidget.md#setfocus)

___

### SetHintText

▸ **SetHintText**(`InHintText`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InHintText` | `string` |

#### Returns

`void`

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetIsEnabled](ue_ue.TextLayoutWidget.md#setisenabled)

___

### SetIsReadOnly

▸ **SetIsReadOnly**(`bReadOnly`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bReadOnly` | `boolean` |

#### Returns

`void`

___

### SetJustification

▸ **SetJustification**(`InJustification`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InJustification` | [`ETextJustify`](../enums/ue_ue.ETextJustify.md) |

#### Returns

`void`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetJustification](ue_ue.TextLayoutWidget.md#setjustification)

___

### SetKeyboardFocus

▸ **SetKeyboardFocus**(): `void`

#### Returns

`void`

#### Inherited from

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetKeyboardFocus](ue_ue.TextLayoutWidget.md#setkeyboardfocus)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetNavigationRule](ue_ue.TextLayoutWidget.md#setnavigationrule)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetNavigationRuleBase](ue_ue.TextLayoutWidget.md#setnavigationrulebase)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetNavigationRuleCustom](ue_ue.TextLayoutWidget.md#setnavigationrulecustom)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetNavigationRuleCustomBoundary](ue_ue.TextLayoutWidget.md#setnavigationrulecustomboundary)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetNavigationRuleExplicit](ue_ue.TextLayoutWidget.md#setnavigationruleexplicit)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetRenderOpacity](ue_ue.TextLayoutWidget.md#setrenderopacity)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetRenderScale](ue_ue.TextLayoutWidget.md#setrenderscale)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetRenderShear](ue_ue.TextLayoutWidget.md#setrendershear)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetRenderTransform](ue_ue.TextLayoutWidget.md#setrendertransform)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetRenderTransformAngle](ue_ue.TextLayoutWidget.md#setrendertransformangle)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetRenderTransformPivot](ue_ue.TextLayoutWidget.md#setrendertransformpivot)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetRenderTranslation](ue_ue.TextLayoutWidget.md#setrendertranslation)

___

### SetText

▸ **SetText**(`InText`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InText` | `string` |

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetToolTip](ue_ue.TextLayoutWidget.md#settooltip)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetToolTipText](ue_ue.TextLayoutWidget.md#settooltiptext)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetUserFocus](ue_ue.TextLayoutWidget.md#setuserfocus)

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

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[SetVisibility](ue_ue.TextLayoutWidget.md#setvisibility)

___

### SetWidgetStyle

▸ **SetWidgetStyle**(`InWidgetStyle`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InWidgetStyle` | [`TextBlockStyle`](ue_ue.TextBlockStyle.md) |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MultiLineEditableText`](ue_ue.MultiLineEditableText.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MultiLineEditableText`](ue_ue.MultiLineEditableText.md)

#### Overrides

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[Find](ue_ue.TextLayoutWidget.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MultiLineEditableText`](ue_ue.MultiLineEditableText.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MultiLineEditableText`](ue_ue.MultiLineEditableText.md)

#### Overrides

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[Load](ue_ue.TextLayoutWidget.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[TextLayoutWidget](ue_ue.TextLayoutWidget.md).[StaticClass](ue_ue.TextLayoutWidget.md#staticclass)
