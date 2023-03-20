[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / WidgetProps

# Interface: WidgetProps

[react-umg](../modules/react_umg.md).WidgetProps

## Hierarchy

- [`Props`](react_umg.Props.md)

  ↳ **`WidgetProps`**

  ↳↳ [`UserWidgetProps`](react_umg.UserWidgetProps.md)

  ↳↳ [`PanelWidgetProps`](react_umg.PanelWidgetProps.md)

  ↳↳ [`CircularThrobberProps`](react_umg.CircularThrobberProps.md)

  ↳↳ [`ComboBoxProps`](react_umg.ComboBoxProps.md)

  ↳↳ [`ComboBoxStringProps`](react_umg.ComboBoxStringProps.md)

  ↳↳ [`DynamicEntryBoxBaseProps`](react_umg.DynamicEntryBoxBaseProps.md)

  ↳↳ [`EditableTextProps`](react_umg.EditableTextProps.md)

  ↳↳ [`EditableTextBoxProps`](react_umg.EditableTextBoxProps.md)

  ↳↳ [`ExpandableAreaProps`](react_umg.ExpandableAreaProps.md)

  ↳↳ [`ImageProps`](react_umg.ImageProps.md)

  ↳↳ [`InputKeySelectorProps`](react_umg.InputKeySelectorProps.md)

  ↳↳ [`ListViewBaseProps`](react_umg.ListViewBaseProps.md)

  ↳↳ [`TextLayoutWidgetProps`](react_umg.TextLayoutWidgetProps.md)

  ↳↳ [`NativeWidgetHostProps`](react_umg.NativeWidgetHostProps.md)

  ↳↳ [`ProgressBarProps`](react_umg.ProgressBarProps.md)

  ↳↳ [`ScrollBarProps`](react_umg.ScrollBarProps.md)

  ↳↳ [`SliderProps`](react_umg.SliderProps.md)

  ↳↳ [`SpacerProps`](react_umg.SpacerProps.md)

  ↳↳ [`SpinBoxProps`](react_umg.SpinBoxProps.md)

  ↳↳ [`ThrobberProps`](react_umg.ThrobberProps.md)

  ↳↳ [`PropertyViewBaseProps`](react_umg.PropertyViewBaseProps.md)

## Table of contents

### Properties

- [AccessibleBehavior](react_umg.WidgetProps.md#accessiblebehavior)
- [AccessibleSummaryBehavior](react_umg.WidgetProps.md#accessiblesummarybehavior)
- [AccessibleSummaryText](react_umg.WidgetProps.md#accessiblesummarytext)
- [AccessibleSummaryTextDelegate](react_umg.WidgetProps.md#accessiblesummarytextdelegate)
- [AccessibleText](react_umg.WidgetProps.md#accessibletext)
- [AccessibleTextDelegate](react_umg.WidgetProps.md#accessibletextdelegate)
- [CategoryName](react_umg.WidgetProps.md#categoryname)
- [Clipping](react_umg.WidgetProps.md#clipping)
- [Cursor](react_umg.WidgetProps.md#cursor)
- [DesignerFlags](react_umg.WidgetProps.md#designerflags)
- [DisplayLabel](react_umg.WidgetProps.md#displaylabel)
- [FlowDirectionPreference](react_umg.WidgetProps.md#flowdirectionpreference)
- [RenderOpacity](react_umg.WidgetProps.md#renderopacity)
- [RenderTransform](react_umg.WidgetProps.md#rendertransform)
- [RenderTransformPivot](react_umg.WidgetProps.md#rendertransformpivot)
- [Slot](react_umg.WidgetProps.md#slot)
- [ToolTipText](react_umg.WidgetProps.md#tooltiptext)
- [ToolTipTextDelegate](react_umg.WidgetProps.md#tooltiptextdelegate)
- [Visibility](react_umg.WidgetProps.md#visibility)
- [VisibilityDelegate](react_umg.WidgetProps.md#visibilitydelegate)
- [bCanChildrenBeAccessible](react_umg.WidgetProps.md#bcanchildrenbeaccessible)
- [bCreatedByConstructionScript](react_umg.WidgetProps.md#bcreatedbyconstructionscript)
- [bExpandedInDesigner](react_umg.WidgetProps.md#bexpandedindesigner)
- [bHiddenInDesigner](react_umg.WidgetProps.md#bhiddenindesigner)
- [bIsEnabled](react_umg.WidgetProps.md#bisenabled)
- [bIsEnabledDelegate](react_umg.WidgetProps.md#bisenableddelegate)
- [bIsVariable](react_umg.WidgetProps.md#bisvariable)
- [bIsVolatile](react_umg.WidgetProps.md#bisvolatile)
- [bLockedInDesigner](react_umg.WidgetProps.md#blockedindesigner)
- [bOverrideAccessibleDefaults](react_umg.WidgetProps.md#boverrideaccessibledefaults)
- [bOverride\_Cursor](react_umg.WidgetProps.md#boverride_cursor)

## Properties

### AccessibleBehavior

• `Optional` **AccessibleBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Defined in

[react-umg/index.d.ts:145](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L145)

___

### AccessibleSummaryBehavior

• `Optional` **AccessibleSummaryBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Defined in

[react-umg/index.d.ts:146](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L146)

___

### AccessibleSummaryText

• `Optional` **AccessibleSummaryText**: `string`

#### Defined in

[react-umg/index.d.ts:149](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L149)

___

### AccessibleSummaryTextDelegate

• `Optional` **AccessibleSummaryTextDelegate**: () => `string`

#### Type declaration

▸ (): `string`

##### Returns

`string`

#### Defined in

[react-umg/index.d.ts:150](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L150)

___

### AccessibleText

• `Optional` **AccessibleText**: `string`

#### Defined in

[react-umg/index.d.ts:147](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L147)

___

### AccessibleTextDelegate

• `Optional` **AccessibleTextDelegate**: () => `string`

#### Type declaration

▸ (): `string`

##### Returns

`string`

#### Defined in

[react-umg/index.d.ts:148](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L148)

___

### CategoryName

• `Optional` **CategoryName**: `string`

#### Defined in

[react-umg/index.d.ts:162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L162)

___

### Clipping

• `Optional` **Clipping**: [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Defined in

[react-umg/index.d.ts:156](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L156)

___

### Cursor

• `Optional` **Cursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Defined in

[react-umg/index.d.ts:155](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L155)

___

### DesignerFlags

• `Optional` **DesignerFlags**: `number`

#### Defined in

[react-umg/index.d.ts:160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L160)

___

### DisplayLabel

• `Optional` **DisplayLabel**: `string`

#### Defined in

[react-umg/index.d.ts:161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L161)

___

### FlowDirectionPreference

• `Optional` **FlowDirectionPreference**: [`EFlowDirectionPreference`](../enums/ue_ue.EFlowDirectionPreference.md)

#### Defined in

[react-umg/index.d.ts:159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L159)

___

### RenderOpacity

• `Optional` **RenderOpacity**: `number`

#### Defined in

[react-umg/index.d.ts:158](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L158)

___

### RenderTransform

• `Optional` **RenderTransform**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`WidgetTransform`](../classes/ue_ue.WidgetTransform.md)\>

#### Defined in

[react-umg/index.d.ts:137](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L137)

___

### RenderTransformPivot

• `Optional` **RenderTransformPivot**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`Vector2D`](../classes/ue_ue_s.Vector2D.md)\>

#### Defined in

[react-umg/index.d.ts:138](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L138)

___

### Slot

• `Optional` **Slot**: [`PanelSlot`](react_umg.PanelSlot.md)

#### Inherited from

[Props](react_umg.Props.md).[Slot](react_umg.Props.md#slot)

#### Defined in

[react-umg/index.d.ts:129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L129)

___

### ToolTipText

• `Optional` **ToolTipText**: `string`

#### Defined in

[react-umg/index.d.ts:134](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L134)

___

### ToolTipTextDelegate

• `Optional` **ToolTipTextDelegate**: () => `string`

#### Type declaration

▸ (): `string`

##### Returns

`string`

#### Defined in

[react-umg/index.d.ts:135](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L135)

___

### Visibility

• `Optional` **Visibility**: [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Defined in

[react-umg/index.d.ts:157](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L157)

___

### VisibilityDelegate

• `Optional` **VisibilityDelegate**: () => [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Type declaration

▸ (): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

##### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Defined in

[react-umg/index.d.ts:136](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L136)

___

### bCanChildrenBeAccessible

• `Optional` **bCanChildrenBeAccessible**: `boolean`

#### Defined in

[react-umg/index.d.ts:144](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L144)

___

### bCreatedByConstructionScript

• `Optional` **bCreatedByConstructionScript**: `boolean`

#### Defined in

[react-umg/index.d.ts:140](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L140)

___

### bExpandedInDesigner

• `Optional` **bExpandedInDesigner**: `boolean`

#### Defined in

[react-umg/index.d.ts:153](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L153)

___

### bHiddenInDesigner

• `Optional` **bHiddenInDesigner**: `boolean`

#### Defined in

[react-umg/index.d.ts:152](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L152)

___

### bIsEnabled

• `Optional` **bIsEnabled**: `boolean`

#### Defined in

[react-umg/index.d.ts:141](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L141)

___

### bIsEnabledDelegate

• `Optional` **bIsEnabledDelegate**: () => `boolean`

#### Type declaration

▸ (): `boolean`

##### Returns

`boolean`

#### Defined in

[react-umg/index.d.ts:133](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L133)

___

### bIsVariable

• `Optional` **bIsVariable**: `boolean`

#### Defined in

[react-umg/index.d.ts:139](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L139)

___

### bIsVolatile

• `Optional` **bIsVolatile**: `boolean`

#### Defined in

[react-umg/index.d.ts:151](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L151)

___

### bLockedInDesigner

• `Optional` **bLockedInDesigner**: `boolean`

#### Defined in

[react-umg/index.d.ts:154](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L154)

___

### bOverrideAccessibleDefaults

• `Optional` **bOverrideAccessibleDefaults**: `boolean`

#### Defined in

[react-umg/index.d.ts:143](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L143)

___

### bOverride\_Cursor

• `Optional` **bOverride\_Cursor**: `boolean`

#### Defined in

[react-umg/index.d.ts:142](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L142)
