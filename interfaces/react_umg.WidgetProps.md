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

___

### AccessibleSummaryBehavior

• `Optional` **AccessibleSummaryBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

___

### AccessibleSummaryText

• `Optional` **AccessibleSummaryText**: `string`

___

### AccessibleSummaryTextDelegate

• `Optional` **AccessibleSummaryTextDelegate**: () => `string`

#### Type declaration

▸ (): `string`

##### Returns

`string`

___

### AccessibleText

• `Optional` **AccessibleText**: `string`

___

### AccessibleTextDelegate

• `Optional` **AccessibleTextDelegate**: () => `string`

#### Type declaration

▸ (): `string`

##### Returns

`string`

___

### CategoryName

• `Optional` **CategoryName**: `string`

___

### Clipping

• `Optional` **Clipping**: [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

___

### Cursor

• `Optional` **Cursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

___

### DesignerFlags

• `Optional` **DesignerFlags**: `number`

___

### DisplayLabel

• `Optional` **DisplayLabel**: `string`

___

### FlowDirectionPreference

• `Optional` **FlowDirectionPreference**: [`EFlowDirectionPreference`](../enums/ue_ue.EFlowDirectionPreference.md)

___

### RenderOpacity

• `Optional` **RenderOpacity**: `number`

___

### RenderTransform

• `Optional` **RenderTransform**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`WidgetTransform`](../classes/ue_ue.WidgetTransform.md)\>

___

### RenderTransformPivot

• `Optional` **RenderTransformPivot**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`Vector2D`](../classes/ue_ue_s.Vector2D.md)\>

___

### Slot

• `Optional` **Slot**: [`PanelSlot`](react_umg.PanelSlot.md)

#### Inherited from

[Props](react_umg.Props.md).[Slot](react_umg.Props.md#slot)

___

### ToolTipText

• `Optional` **ToolTipText**: `string`

___

### ToolTipTextDelegate

• `Optional` **ToolTipTextDelegate**: () => `string`

#### Type declaration

▸ (): `string`

##### Returns

`string`

___

### Visibility

• `Optional` **Visibility**: [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

___

### VisibilityDelegate

• `Optional` **VisibilityDelegate**: () => [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Type declaration

▸ (): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

##### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

___

### bCanChildrenBeAccessible

• `Optional` **bCanChildrenBeAccessible**: `boolean`

___

### bCreatedByConstructionScript

• `Optional` **bCreatedByConstructionScript**: `boolean`

___

### bExpandedInDesigner

• `Optional` **bExpandedInDesigner**: `boolean`

___

### bHiddenInDesigner

• `Optional` **bHiddenInDesigner**: `boolean`

___

### bIsEnabled

• `Optional` **bIsEnabled**: `boolean`

___

### bIsEnabledDelegate

• `Optional` **bIsEnabledDelegate**: () => `boolean`

#### Type declaration

▸ (): `boolean`

##### Returns

`boolean`

___

### bIsVariable

• `Optional` **bIsVariable**: `boolean`

___

### bIsVolatile

• `Optional` **bIsVolatile**: `boolean`

___

### bLockedInDesigner

• `Optional` **bLockedInDesigner**: `boolean`

___

### bOverrideAccessibleDefaults

• `Optional` **bOverrideAccessibleDefaults**: `boolean`

___

### bOverride\_Cursor

• `Optional` **bOverride\_Cursor**: `boolean`
