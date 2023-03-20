[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Widget

# Class: Widget

[ue/ue](../modules/ue_ue.md).Widget

## Hierarchy

- [`Visual`](ue_ue.Visual.md)

  ↳ **`Widget`**

  ↳↳ [`PanelWidget`](ue_ue.PanelWidget.md)

  ↳↳ [`UserWidget`](ue_ue.UserWidget.md)

  ↳↳ [`CircularThrobber`](ue_ue.CircularThrobber.md)

  ↳↳ [`ComboBox`](ue_ue.ComboBox.md)

  ↳↳ [`ComboBoxString`](ue_ue.ComboBoxString.md)

  ↳↳ [`PropertyViewBase`](ue_ue.PropertyViewBase.md)

  ↳↳ [`DynamicEntryBoxBase`](ue_ue.DynamicEntryBoxBase.md)

  ↳↳ [`EditableText`](ue_ue.EditableText.md)

  ↳↳ [`EditableTextBox`](ue_ue.EditableTextBox.md)

  ↳↳ [`ExpandableArea`](ue_ue.ExpandableArea.md)

  ↳↳ [`Image`](ue_ue.Image.md)

  ↳↳ [`InputKeySelector`](ue_ue.InputKeySelector.md)

  ↳↳ [`ListViewBase`](ue_ue.ListViewBase.md)

  ↳↳ [`TextLayoutWidget`](ue_ue.TextLayoutWidget.md)

  ↳↳ [`NativeWidgetHost`](ue_ue.NativeWidgetHost.md)

  ↳↳ [`ProgressBar`](ue_ue.ProgressBar.md)

  ↳↳ [`ScrollBar`](ue_ue.ScrollBar.md)

  ↳↳ [`Slider`](ue_ue.Slider.md)

  ↳↳ [`Spacer`](ue_ue.Spacer.md)

  ↳↳ [`SpinBox`](ue_ue.SpinBox.md)

  ↳↳ [`Throbber`](ue_ue.Throbber.md)

## Table of contents

### Constructors

- [constructor](ue_ue.Widget.md#constructor)

### Properties

- [AccessibleBehavior](ue_ue.Widget.md#accessiblebehavior)
- [AccessibleSummaryBehavior](ue_ue.Widget.md#accessiblesummarybehavior)
- [AccessibleSummaryText](ue_ue.Widget.md#accessiblesummarytext)
- [AccessibleSummaryTextDelegate](ue_ue.Widget.md#accessiblesummarytextdelegate)
- [AccessibleText](ue_ue.Widget.md#accessibletext)
- [AccessibleTextDelegate](ue_ue.Widget.md#accessibletextdelegate)
- [AccessibleWidgetData](ue_ue.Widget.md#accessiblewidgetdata)
- [CategoryName](ue_ue.Widget.md#categoryname)
- [Clipping](ue_ue.Widget.md#clipping)
- [Cursor](ue_ue.Widget.md#cursor)
- [DesignerFlags](ue_ue.Widget.md#designerflags)
- [DisplayLabel](ue_ue.Widget.md#displaylabel)
- [FlowDirectionPreference](ue_ue.Widget.md#flowdirectionpreference)
- [NativeBindings](ue_ue.Widget.md#nativebindings)
- [Navigation](ue_ue.Widget.md#navigation)
- [RenderOpacity](ue_ue.Widget.md#renderopacity)
- [RenderTransform](ue_ue.Widget.md#rendertransform)
- [RenderTransformPivot](ue_ue.Widget.md#rendertransformpivot)
- [Slot](ue_ue.Widget.md#slot)
- [ToolTipText](ue_ue.Widget.md#tooltiptext)
- [ToolTipTextDelegate](ue_ue.Widget.md#tooltiptextdelegate)
- [ToolTipWidget](ue_ue.Widget.md#tooltipwidget)
- [ToolTipWidgetDelegate](ue_ue.Widget.md#tooltipwidgetdelegate)
- [Visibility](ue_ue.Widget.md#visibility)
- [VisibilityDelegate](ue_ue.Widget.md#visibilitydelegate)
- [\_\_tid\_Object\_\_](ue_ue.Widget.md#__tid_object__)
- [\_\_tid\_Visual\_\_](ue_ue.Widget.md#__tid_visual__)
- [\_\_tid\_Widget\_\_](ue_ue.Widget.md#__tid_widget__)
- [bCanChildrenBeAccessible](ue_ue.Widget.md#bcanchildrenbeaccessible)
- [bCreatedByConstructionScript](ue_ue.Widget.md#bcreatedbyconstructionscript)
- [bExpandedInDesigner](ue_ue.Widget.md#bexpandedindesigner)
- [bHiddenInDesigner](ue_ue.Widget.md#bhiddenindesigner)
- [bIsEnabled](ue_ue.Widget.md#bisenabled)
- [bIsEnabledDelegate](ue_ue.Widget.md#bisenableddelegate)
- [bIsVariable](ue_ue.Widget.md#bisvariable)
- [bIsVolatile](ue_ue.Widget.md#bisvolatile)
- [bLockedInDesigner](ue_ue.Widget.md#blockedindesigner)
- [bOverrideAccessibleDefaults](ue_ue.Widget.md#boverrideaccessibledefaults)
- [bOverride\_Cursor](ue_ue.Widget.md#boverride_cursor)

### Methods

- [CreateDefaultSubobject](ue_ue.Widget.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Widget.md#executeubergraph)
- [ForceLayoutPrepass](ue_ue.Widget.md#forcelayoutprepass)
- [ForceVolatile](ue_ue.Widget.md#forcevolatile)
- [GenerateWidgetForObject\_\_DelegateSignature](ue_ue.Widget.md#generatewidgetforobject__delegatesignature)
- [GenerateWidgetForString\_\_DelegateSignature](ue_ue.Widget.md#generatewidgetforstring__delegatesignature)
- [GetBool\_\_DelegateSignature](ue_ue.Widget.md#getbool__delegatesignature)
- [GetCachedGeometry](ue_ue.Widget.md#getcachedgeometry)
- [GetCheckBoxState\_\_DelegateSignature](ue_ue.Widget.md#getcheckboxstate__delegatesignature)
- [GetClass](ue_ue.Widget.md#getclass)
- [GetClipping](ue_ue.Widget.md#getclipping)
- [GetDesiredSize](ue_ue.Widget.md#getdesiredsize)
- [GetFloat\_\_DelegateSignature](ue_ue.Widget.md#getfloat__delegatesignature)
- [GetGameInstance](ue_ue.Widget.md#getgameinstance)
- [GetInt32\_\_DelegateSignature](ue_ue.Widget.md#getint32__delegatesignature)
- [GetIsEnabled](ue_ue.Widget.md#getisenabled)
- [GetLinearColor\_\_DelegateSignature](ue_ue.Widget.md#getlinearcolor__delegatesignature)
- [GetMouseCursor\_\_DelegateSignature](ue_ue.Widget.md#getmousecursor__delegatesignature)
- [GetName](ue_ue.Widget.md#getname)
- [GetOuter](ue_ue.Widget.md#getouter)
- [GetOwningLocalPlayer](ue_ue.Widget.md#getowninglocalplayer)
- [GetOwningPlayer](ue_ue.Widget.md#getowningplayer)
- [GetPaintSpaceGeometry](ue_ue.Widget.md#getpaintspacegeometry)
- [GetParent](ue_ue.Widget.md#getparent)
- [GetRenderOpacity](ue_ue.Widget.md#getrenderopacity)
- [GetRenderTransformAngle](ue_ue.Widget.md#getrendertransformangle)
- [GetSlateBrush\_\_DelegateSignature](ue_ue.Widget.md#getslatebrush__delegatesignature)
- [GetSlateColor\_\_DelegateSignature](ue_ue.Widget.md#getslatecolor__delegatesignature)
- [GetSlateVisibility\_\_DelegateSignature](ue_ue.Widget.md#getslatevisibility__delegatesignature)
- [GetText\_\_DelegateSignature](ue_ue.Widget.md#gettext__delegatesignature)
- [GetTickSpaceGeometry](ue_ue.Widget.md#gettickspacegeometry)
- [GetVisibility](ue_ue.Widget.md#getvisibility)
- [GetWidget\_\_DelegateSignature](ue_ue.Widget.md#getwidget__delegatesignature)
- [GetWorld](ue_ue.Widget.md#getworld)
- [HasAnyUserFocus](ue_ue.Widget.md#hasanyuserfocus)
- [HasFocusedDescendants](ue_ue.Widget.md#hasfocuseddescendants)
- [HasKeyboardFocus](ue_ue.Widget.md#haskeyboardfocus)
- [HasMouseCapture](ue_ue.Widget.md#hasmousecapture)
- [HasMouseCaptureByUser](ue_ue.Widget.md#hasmousecapturebyuser)
- [HasUserFocus](ue_ue.Widget.md#hasuserfocus)
- [HasUserFocusedDescendants](ue_ue.Widget.md#hasuserfocuseddescendants)
- [InvalidateLayoutAndVolatility](ue_ue.Widget.md#invalidatelayoutandvolatility)
- [IsHovered](ue_ue.Widget.md#ishovered)
- [IsVisible](ue_ue.Widget.md#isvisible)
- [OnPointerEvent\_\_DelegateSignature](ue_ue.Widget.md#onpointerevent__delegatesignature)
- [OnReply\_\_DelegateSignature](ue_ue.Widget.md#onreply__delegatesignature)
- [RemoveFromParent](ue_ue.Widget.md#removefromparent)
- [ResetCursor](ue_ue.Widget.md#resetcursor)
- [SetAllNavigationRules](ue_ue.Widget.md#setallnavigationrules)
- [SetClipping](ue_ue.Widget.md#setclipping)
- [SetCursor](ue_ue.Widget.md#setcursor)
- [SetFocus](ue_ue.Widget.md#setfocus)
- [SetIsEnabled](ue_ue.Widget.md#setisenabled)
- [SetKeyboardFocus](ue_ue.Widget.md#setkeyboardfocus)
- [SetNavigationRule](ue_ue.Widget.md#setnavigationrule)
- [SetNavigationRuleBase](ue_ue.Widget.md#setnavigationrulebase)
- [SetNavigationRuleCustom](ue_ue.Widget.md#setnavigationrulecustom)
- [SetNavigationRuleCustomBoundary](ue_ue.Widget.md#setnavigationrulecustomboundary)
- [SetNavigationRuleExplicit](ue_ue.Widget.md#setnavigationruleexplicit)
- [SetRenderOpacity](ue_ue.Widget.md#setrenderopacity)
- [SetRenderScale](ue_ue.Widget.md#setrenderscale)
- [SetRenderShear](ue_ue.Widget.md#setrendershear)
- [SetRenderTransform](ue_ue.Widget.md#setrendertransform)
- [SetRenderTransformAngle](ue_ue.Widget.md#setrendertransformangle)
- [SetRenderTransformPivot](ue_ue.Widget.md#setrendertransformpivot)
- [SetRenderTranslation](ue_ue.Widget.md#setrendertranslation)
- [SetToolTip](ue_ue.Widget.md#settooltip)
- [SetToolTipText](ue_ue.Widget.md#settooltiptext)
- [SetUserFocus](ue_ue.Widget.md#setuserfocus)
- [SetVisibility](ue_ue.Widget.md#setvisibility)
- [Find](ue_ue.Widget.md#find)
- [Load](ue_ue.Widget.md#load)
- [StaticClass](ue_ue.Widget.md#staticclass)

## Constructors

### constructor

• **new Widget**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Visual](ue_ue.Visual.md).[constructor](ue_ue.Visual.md#constructor)

## Properties

### AccessibleBehavior

• **AccessibleBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

___

### AccessibleSummaryBehavior

• **AccessibleSummaryBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

___

### AccessibleSummaryText

• **AccessibleSummaryText**: `string`

___

### AccessibleSummaryTextDelegate

• **AccessibleSummaryTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

___

### AccessibleText

• **AccessibleText**: `string`

___

### AccessibleTextDelegate

• **AccessibleTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

___

### AccessibleWidgetData

• **AccessibleWidgetData**: [`SlateAccessibleWidgetData`](ue_ue.SlateAccessibleWidgetData.md)

___

### CategoryName

• **CategoryName**: `string`

___

### Clipping

• **Clipping**: [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

___

### Cursor

• **Cursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

___

### DesignerFlags

• **DesignerFlags**: `number`

___

### DisplayLabel

• **DisplayLabel**: `string`

___

### FlowDirectionPreference

• **FlowDirectionPreference**: [`EFlowDirectionPreference`](../enums/ue_ue.EFlowDirectionPreference.md)

___

### NativeBindings

• **NativeBindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyBinding`](ue_ue.PropertyBinding.md)\>

___

### Navigation

• **Navigation**: [`WidgetNavigation`](ue_ue.WidgetNavigation.md)

___

### RenderOpacity

• **RenderOpacity**: `number`

___

### RenderTransform

• **RenderTransform**: [`WidgetTransform`](ue_ue.WidgetTransform.md)

___

### RenderTransformPivot

• **RenderTransformPivot**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### Slot

• **Slot**: [`PanelSlot`](ue_ue.PanelSlot.md)

___

### ToolTipText

• **ToolTipText**: `string`

___

### ToolTipTextDelegate

• **ToolTipTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

___

### ToolTipWidget

• **ToolTipWidget**: [`Widget`](ue_ue.Widget.md)

___

### ToolTipWidgetDelegate

• **ToolTipWidgetDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`Widget`](ue_ue.Widget.md)\>

___

### Visibility

• **Visibility**: [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

___

### VisibilityDelegate

• **VisibilityDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)\>

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Visual](ue_ue.Visual.md).[__tid_Object__](ue_ue.Visual.md#__tid_object__)

___

### \_\_tid\_Visual\_\_

• **\_\_tid\_Visual\_\_**: `boolean`

#### Inherited from

[Visual](ue_ue.Visual.md).[__tid_Visual__](ue_ue.Visual.md#__tid_visual__)

___

### \_\_tid\_Widget\_\_

• **\_\_tid\_Widget\_\_**: `boolean`

___

### bCanChildrenBeAccessible

• **bCanChildrenBeAccessible**: `boolean`

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

___

### bExpandedInDesigner

• **bExpandedInDesigner**: `boolean`

___

### bHiddenInDesigner

• **bHiddenInDesigner**: `boolean`

___

### bIsEnabled

• **bIsEnabled**: `boolean`

___

### bIsEnabledDelegate

• **bIsEnabledDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `boolean`\>

___

### bIsVariable

• **bIsVariable**: `boolean`

___

### bIsVolatile

• **bIsVolatile**: `boolean`

___

### bLockedInDesigner

• **bLockedInDesigner**: `boolean`

___

### bOverrideAccessibleDefaults

• **bOverrideAccessibleDefaults**: `boolean`

___

### bOverride\_Cursor

• **bOverride\_Cursor**: `boolean`

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

[Visual](ue_ue.Visual.md).[CreateDefaultSubobject](ue_ue.Visual.md#createdefaultsubobject)

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

[Visual](ue_ue.Visual.md).[ExecuteUbergraph](ue_ue.Visual.md#executeubergraph)

___

### ForceLayoutPrepass

▸ **ForceLayoutPrepass**(): `void`

#### Returns

`void`

___

### ForceVolatile

▸ **ForceVolatile**(`bForce`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bForce` | `boolean` |

#### Returns

`void`

___

### GenerateWidgetForObject\_\_DelegateSignature

▸ **GenerateWidgetForObject__DelegateSignature**(`Item`): [`Widget`](ue_ue.Widget.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`Widget`](ue_ue.Widget.md)

___

### GenerateWidgetForString\_\_DelegateSignature

▸ **GenerateWidgetForString__DelegateSignature**(`Item`): [`Widget`](ue_ue.Widget.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | `string` |

#### Returns

[`Widget`](ue_ue.Widget.md)

___

### GetBool\_\_DelegateSignature

▸ **GetBool__DelegateSignature**(): `boolean`

#### Returns

`boolean`

___

### GetCachedGeometry

▸ **GetCachedGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

___

### GetCheckBoxState\_\_DelegateSignature

▸ **GetCheckBoxState__DelegateSignature**(): [`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Returns

[`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Visual](ue_ue.Visual.md).[GetClass](ue_ue.Visual.md#getclass)

___

### GetClipping

▸ **GetClipping**(): [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Returns

[`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

___

### GetDesiredSize

▸ **GetDesiredSize**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### GetFloat\_\_DelegateSignature

▸ **GetFloat__DelegateSignature**(): `number`

#### Returns

`number`

___

### GetGameInstance

▸ **GetGameInstance**(): [`GameInstance`](ue_ue.GameInstance.md)

#### Returns

[`GameInstance`](ue_ue.GameInstance.md)

___

### GetInt32\_\_DelegateSignature

▸ **GetInt32__DelegateSignature**(): `number`

#### Returns

`number`

___

### GetIsEnabled

▸ **GetIsEnabled**(): `boolean`

#### Returns

`boolean`

___

### GetLinearColor\_\_DelegateSignature

▸ **GetLinearColor__DelegateSignature**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

___

### GetMouseCursor\_\_DelegateSignature

▸ **GetMouseCursor__DelegateSignature**(): [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Returns

[`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Visual](ue_ue.Visual.md).[GetName](ue_ue.Visual.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Visual](ue_ue.Visual.md).[GetOuter](ue_ue.Visual.md#getouter)

___

### GetOwningLocalPlayer

▸ **GetOwningLocalPlayer**(): [`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Returns

[`LocalPlayer`](ue_ue.LocalPlayer.md)

___

### GetOwningPlayer

▸ **GetOwningPlayer**(): [`PlayerController`](ue_ue.PlayerController.md)

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

___

### GetPaintSpaceGeometry

▸ **GetPaintSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

___

### GetParent

▸ **GetParent**(): [`PanelWidget`](ue_ue.PanelWidget.md)

#### Returns

[`PanelWidget`](ue_ue.PanelWidget.md)

___

### GetRenderOpacity

▸ **GetRenderOpacity**(): `number`

#### Returns

`number`

___

### GetRenderTransformAngle

▸ **GetRenderTransformAngle**(): `number`

#### Returns

`number`

___

### GetSlateBrush\_\_DelegateSignature

▸ **GetSlateBrush__DelegateSignature**(): [`SlateBrush`](ue_ue.SlateBrush.md)

#### Returns

[`SlateBrush`](ue_ue.SlateBrush.md)

___

### GetSlateColor\_\_DelegateSignature

▸ **GetSlateColor__DelegateSignature**(): [`SlateColor`](ue_ue.SlateColor.md)

#### Returns

[`SlateColor`](ue_ue.SlateColor.md)

___

### GetSlateVisibility\_\_DelegateSignature

▸ **GetSlateVisibility__DelegateSignature**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

___

### GetText\_\_DelegateSignature

▸ **GetText__DelegateSignature**(): `string`

#### Returns

`string`

___

### GetTickSpaceGeometry

▸ **GetTickSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

___

### GetVisibility

▸ **GetVisibility**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

___

### GetWidget\_\_DelegateSignature

▸ **GetWidget__DelegateSignature**(): [`Widget`](ue_ue.Widget.md)

#### Returns

[`Widget`](ue_ue.Widget.md)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Visual](ue_ue.Visual.md).[GetWorld](ue_ue.Visual.md#getworld)

___

### HasAnyUserFocus

▸ **HasAnyUserFocus**(): `boolean`

#### Returns

`boolean`

___

### HasFocusedDescendants

▸ **HasFocusedDescendants**(): `boolean`

#### Returns

`boolean`

___

### HasKeyboardFocus

▸ **HasKeyboardFocus**(): `boolean`

#### Returns

`boolean`

___

### HasMouseCapture

▸ **HasMouseCapture**(): `boolean`

#### Returns

`boolean`

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

___

### HasUserFocus

▸ **HasUserFocus**(`PlayerController`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`boolean`

___

### HasUserFocusedDescendants

▸ **HasUserFocusedDescendants**(`PlayerController`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`boolean`

___

### InvalidateLayoutAndVolatility

▸ **InvalidateLayoutAndVolatility**(): `void`

#### Returns

`void`

___

### IsHovered

▸ **IsHovered**(): `boolean`

#### Returns

`boolean`

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

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

___

### OnReply\_\_DelegateSignature

▸ **OnReply__DelegateSignature**(): [`EventReply`](ue_ue.EventReply.md)

#### Returns

[`EventReply`](ue_ue.EventReply.md)

___

### RemoveFromParent

▸ **RemoveFromParent**(): `void`

#### Returns

`void`

___

### ResetCursor

▸ **ResetCursor**(): `void`

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

___

### SetClipping

▸ **SetClipping**(`InClipping`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InClipping` | [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md) |

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

___

### SetFocus

▸ **SetFocus**(): `void`

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

___

### SetKeyboardFocus

▸ **SetKeyboardFocus**(): `void`

#### Returns

`void`

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

___

### SetRenderOpacity

▸ **SetRenderOpacity**(`InOpacity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InOpacity` | `number` |

#### Returns

`void`

___

### SetRenderScale

▸ **SetRenderScale**(`Scale`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

___

### SetRenderShear

▸ **SetRenderShear**(`Shear`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Shear` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

___

### SetRenderTransform

▸ **SetRenderTransform**(`InTransform`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTransform` | [`WidgetTransform`](ue_ue.WidgetTransform.md) |

#### Returns

`void`

___

### SetRenderTransformAngle

▸ **SetRenderTransformAngle**(`Angle`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Angle` | `number` |

#### Returns

`void`

___

### SetRenderTransformPivot

▸ **SetRenderTransformPivot**(`Pivot`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Pivot` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

___

### SetRenderTranslation

▸ **SetRenderTranslation**(`Translation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Translation` | [`Vector2D`](ue_ue_s.Vector2D.md) |

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

___

### SetToolTipText

▸ **SetToolTipText**(`InToolTipText`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InToolTipText` | `string` |

#### Returns

`void`

___

### SetUserFocus

▸ **SetUserFocus**(`PlayerController`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`void`

___

### SetVisibility

▸ **SetVisibility**(`InVisibility`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InVisibility` | [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md) |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Widget`](ue_ue.Widget.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Widget`](ue_ue.Widget.md)

#### Overrides

[Visual](ue_ue.Visual.md).[Find](ue_ue.Visual.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`Widget`](ue_ue.Widget.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Widget`](ue_ue.Widget.md)

#### Overrides

[Visual](ue_ue.Visual.md).[Load](ue_ue.Visual.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Visual](ue_ue.Visual.md).[StaticClass](ue_ue.Visual.md#staticclass)
