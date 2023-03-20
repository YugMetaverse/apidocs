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

#### Defined in

[ue/ue.d.ts:10924](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10924)

## Properties

### AccessibleBehavior

• **AccessibleBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Defined in

[ue/ue.d.ts:10940](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10940)

___

### AccessibleSummaryBehavior

• **AccessibleSummaryBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Defined in

[ue/ue.d.ts:10941](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10941)

___

### AccessibleSummaryText

• **AccessibleSummaryText**: `string`

#### Defined in

[ue/ue.d.ts:10944](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10944)

___

### AccessibleSummaryTextDelegate

• **AccessibleSummaryTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Defined in

[ue/ue.d.ts:10945](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10945)

___

### AccessibleText

• **AccessibleText**: `string`

#### Defined in

[ue/ue.d.ts:10942](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10942)

___

### AccessibleTextDelegate

• **AccessibleTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Defined in

[ue/ue.d.ts:10943](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10943)

___

### AccessibleWidgetData

• **AccessibleWidgetData**: [`SlateAccessibleWidgetData`](ue_ue.SlateAccessibleWidgetData.md)

#### Defined in

[ue/ue.d.ts:10946](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10946)

___

### CategoryName

• **CategoryName**: `string`

#### Defined in

[ue/ue.d.ts:10960](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10960)

___

### Clipping

• **Clipping**: [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Defined in

[ue/ue.d.ts:10952](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10952)

___

### Cursor

• **Cursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Defined in

[ue/ue.d.ts:10951](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10951)

___

### DesignerFlags

• **DesignerFlags**: `number`

#### Defined in

[ue/ue.d.ts:10958](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10958)

___

### DisplayLabel

• **DisplayLabel**: `string`

#### Defined in

[ue/ue.d.ts:10959](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10959)

___

### FlowDirectionPreference

• **FlowDirectionPreference**: [`EFlowDirectionPreference`](../enums/ue_ue.EFlowDirectionPreference.md)

#### Defined in

[ue/ue.d.ts:10956](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10956)

___

### NativeBindings

• **NativeBindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyBinding`](ue_ue.PropertyBinding.md)\>

#### Defined in

[ue/ue.d.ts:10957](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10957)

___

### Navigation

• **Navigation**: [`WidgetNavigation`](ue_ue.WidgetNavigation.md)

#### Defined in

[ue/ue.d.ts:10955](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10955)

___

### RenderOpacity

• **RenderOpacity**: `number`

#### Defined in

[ue/ue.d.ts:10954](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10954)

___

### RenderTransform

• **RenderTransform**: [`WidgetTransform`](ue_ue.WidgetTransform.md)

#### Defined in

[ue/ue.d.ts:10932](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10932)

___

### RenderTransformPivot

• **RenderTransformPivot**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:10933](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10933)

___

### Slot

• **Slot**: [`PanelSlot`](ue_ue.PanelSlot.md)

#### Defined in

[ue/ue.d.ts:10925](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10925)

___

### ToolTipText

• **ToolTipText**: `string`

#### Defined in

[ue/ue.d.ts:10927](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10927)

___

### ToolTipTextDelegate

• **ToolTipTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Defined in

[ue/ue.d.ts:10928](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10928)

___

### ToolTipWidget

• **ToolTipWidget**: [`Widget`](ue_ue.Widget.md)

#### Defined in

[ue/ue.d.ts:10929](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10929)

___

### ToolTipWidgetDelegate

• **ToolTipWidgetDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`Widget`](ue_ue.Widget.md)\>

#### Defined in

[ue/ue.d.ts:10930](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10930)

___

### Visibility

• **Visibility**: [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Defined in

[ue/ue.d.ts:10953](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10953)

___

### VisibilityDelegate

• **VisibilityDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)\>

#### Defined in

[ue/ue.d.ts:10931](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10931)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Visual](ue_ue.Visual.md).[__tid_Object__](ue_ue.Visual.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_Visual\_\_

• **\_\_tid\_Visual\_\_**: `boolean`

#### Inherited from

[Visual](ue_ue.Visual.md).[__tid_Visual__](ue_ue.Visual.md#__tid_visual__)

#### Defined in

[ue/ue.d.ts:10673](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10673)

___

### \_\_tid\_Widget\_\_

• **\_\_tid\_Widget\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:11029](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11029)

___

### bCanChildrenBeAccessible

• **bCanChildrenBeAccessible**: `boolean`

#### Defined in

[ue/ue.d.ts:10939](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10939)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Defined in

[ue/ue.d.ts:10935](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10935)

___

### bExpandedInDesigner

• **bExpandedInDesigner**: `boolean`

#### Defined in

[ue/ue.d.ts:10949](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10949)

___

### bHiddenInDesigner

• **bHiddenInDesigner**: `boolean`

#### Defined in

[ue/ue.d.ts:10948](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10948)

___

### bIsEnabled

• **bIsEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:10936](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10936)

___

### bIsEnabledDelegate

• **bIsEnabledDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `boolean`\>

#### Defined in

[ue/ue.d.ts:10926](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10926)

___

### bIsVariable

• **bIsVariable**: `boolean`

#### Defined in

[ue/ue.d.ts:10934](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10934)

___

### bIsVolatile

• **bIsVolatile**: `boolean`

#### Defined in

[ue/ue.d.ts:10947](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10947)

___

### bLockedInDesigner

• **bLockedInDesigner**: `boolean`

#### Defined in

[ue/ue.d.ts:10950](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10950)

___

### bOverrideAccessibleDefaults

• **bOverrideAccessibleDefaults**: `boolean`

#### Defined in

[ue/ue.d.ts:10938](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10938)

___

### bOverride\_Cursor

• **bOverride\_Cursor**: `boolean`

#### Defined in

[ue/ue.d.ts:10937](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10937)

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

[Visual](ue_ue.Visual.md).[ExecuteUbergraph](ue_ue.Visual.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### ForceLayoutPrepass

▸ **ForceLayoutPrepass**(): `void`

#### Returns

`void`

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

#### Defined in

[ue/ue.d.ts:10964](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10964)

___

### GetBool\_\_DelegateSignature

▸ **GetBool__DelegateSignature**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:10965](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10965)

___

### GetCachedGeometry

▸ **GetCachedGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Defined in

[ue/ue.d.ts:10966](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10966)

___

### GetCheckBoxState\_\_DelegateSignature

▸ **GetCheckBoxState__DelegateSignature**(): [`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Returns

[`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Defined in

[ue/ue.d.ts:10967](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10967)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Visual](ue_ue.Visual.md).[GetClass](ue_ue.Visual.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetClipping

▸ **GetClipping**(): [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Returns

[`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Defined in

[ue/ue.d.ts:10968](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10968)

___

### GetDesiredSize

▸ **GetDesiredSize**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:10969](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10969)

___

### GetFloat\_\_DelegateSignature

▸ **GetFloat__DelegateSignature**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:10970](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10970)

___

### GetGameInstance

▸ **GetGameInstance**(): [`GameInstance`](ue_ue.GameInstance.md)

#### Returns

[`GameInstance`](ue_ue.GameInstance.md)

#### Defined in

[ue/ue.d.ts:10971](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10971)

___

### GetInt32\_\_DelegateSignature

▸ **GetInt32__DelegateSignature**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:10972](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10972)

___

### GetIsEnabled

▸ **GetIsEnabled**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:10973](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10973)

___

### GetLinearColor\_\_DelegateSignature

▸ **GetLinearColor__DelegateSignature**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:10974](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10974)

___

### GetMouseCursor\_\_DelegateSignature

▸ **GetMouseCursor__DelegateSignature**(): [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Returns

[`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Defined in

[ue/ue.d.ts:10975](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10975)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Visual](ue_ue.Visual.md).[GetName](ue_ue.Visual.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Visual](ue_ue.Visual.md).[GetOuter](ue_ue.Visual.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetOwningLocalPlayer

▸ **GetOwningLocalPlayer**(): [`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Returns

[`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Defined in

[ue/ue.d.ts:10976](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10976)

___

### GetOwningPlayer

▸ **GetOwningPlayer**(): [`PlayerController`](ue_ue.PlayerController.md)

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Defined in

[ue/ue.d.ts:10977](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10977)

___

### GetPaintSpaceGeometry

▸ **GetPaintSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Defined in

[ue/ue.d.ts:10978](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10978)

___

### GetParent

▸ **GetParent**(): [`PanelWidget`](ue_ue.PanelWidget.md)

#### Returns

[`PanelWidget`](ue_ue.PanelWidget.md)

#### Defined in

[ue/ue.d.ts:10979](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10979)

___

### GetRenderOpacity

▸ **GetRenderOpacity**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:10980](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10980)

___

### GetRenderTransformAngle

▸ **GetRenderTransformAngle**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:10981](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10981)

___

### GetSlateBrush\_\_DelegateSignature

▸ **GetSlateBrush__DelegateSignature**(): [`SlateBrush`](ue_ue.SlateBrush.md)

#### Returns

[`SlateBrush`](ue_ue.SlateBrush.md)

#### Defined in

[ue/ue.d.ts:10982](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10982)

___

### GetSlateColor\_\_DelegateSignature

▸ **GetSlateColor__DelegateSignature**(): [`SlateColor`](ue_ue.SlateColor.md)

#### Returns

[`SlateColor`](ue_ue.SlateColor.md)

#### Defined in

[ue/ue.d.ts:10983](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10983)

___

### GetSlateVisibility\_\_DelegateSignature

▸ **GetSlateVisibility__DelegateSignature**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Defined in

[ue/ue.d.ts:10984](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10984)

___

### GetText\_\_DelegateSignature

▸ **GetText__DelegateSignature**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:10985](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10985)

___

### GetTickSpaceGeometry

▸ **GetTickSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Defined in

[ue/ue.d.ts:10986](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10986)

___

### GetVisibility

▸ **GetVisibility**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Defined in

[ue/ue.d.ts:10987](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10987)

___

### GetWidget\_\_DelegateSignature

▸ **GetWidget__DelegateSignature**(): [`Widget`](ue_ue.Widget.md)

#### Returns

[`Widget`](ue_ue.Widget.md)

#### Defined in

[ue/ue.d.ts:10988](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10988)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Visual](ue_ue.Visual.md).[GetWorld](ue_ue.Visual.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### HasAnyUserFocus

▸ **HasAnyUserFocus**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:10989](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10989)

___

### HasFocusedDescendants

▸ **HasFocusedDescendants**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:10990](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10990)

___

### HasKeyboardFocus

▸ **HasKeyboardFocus**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:10991](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10991)

___

### HasMouseCapture

▸ **HasMouseCapture**(): `boolean`

#### Returns

`boolean`

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

#### Defined in

[ue/ue.d.ts:10995](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10995)

___

### InvalidateLayoutAndVolatility

▸ **InvalidateLayoutAndVolatility**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:10996](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10996)

___

### IsHovered

▸ **IsHovered**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:10997](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10997)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

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

#### Defined in

[ue/ue.d.ts:10999](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10999)

___

### OnReply\_\_DelegateSignature

▸ **OnReply__DelegateSignature**(): [`EventReply`](ue_ue.EventReply.md)

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Defined in

[ue/ue.d.ts:11000](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11000)

___

### RemoveFromParent

▸ **RemoveFromParent**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:11001](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11001)

___

### ResetCursor

▸ **ResetCursor**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:11002](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11002)

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

#### Defined in

[ue/ue.d.ts:11005](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11005)

___

### SetFocus

▸ **SetFocus**(): `void`

#### Returns

`void`

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

#### Defined in

[ue/ue.d.ts:11007](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11007)

___

### SetKeyboardFocus

▸ **SetKeyboardFocus**(): `void`

#### Returns

`void`

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

#### Defined in

[ue/ue.d.ts:11020](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11020)

___

### SetToolTip

▸ **SetToolTip**(`Widget`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

`void`

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

#### Defined in

[ue/ue.d.ts:11024](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11024)

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

#### Defined in

[ue/ue.d.ts:11026](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11026)

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

#### Defined in

[ue/ue.d.ts:11027](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11027)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Visual](ue_ue.Visual.md).[StaticClass](ue_ue.Visual.md#staticclass)

#### Defined in

[ue/ue.d.ts:11025](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11025)
