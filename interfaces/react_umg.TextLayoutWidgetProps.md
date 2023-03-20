[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / TextLayoutWidgetProps

# Interface: TextLayoutWidgetProps

[react-umg](../modules/react_umg.md).TextLayoutWidgetProps

## Hierarchy

- [`WidgetProps`](react_umg.WidgetProps.md)

  ↳ **`TextLayoutWidgetProps`**

  ↳↳ [`MultiLineEditableTextProps`](react_umg.MultiLineEditableTextProps.md)

  ↳↳ [`MultiLineEditableTextBoxProps`](react_umg.MultiLineEditableTextBoxProps.md)

  ↳↳ [`RichTextBlockProps`](react_umg.RichTextBlockProps.md)

  ↳↳ [`TextBlockProps`](react_umg.TextBlockProps.md)

## Table of contents

### Properties

- [AccessibleBehavior](react_umg.TextLayoutWidgetProps.md#accessiblebehavior)
- [AccessibleSummaryBehavior](react_umg.TextLayoutWidgetProps.md#accessiblesummarybehavior)
- [AccessibleSummaryText](react_umg.TextLayoutWidgetProps.md#accessiblesummarytext)
- [AccessibleSummaryTextDelegate](react_umg.TextLayoutWidgetProps.md#accessiblesummarytextdelegate)
- [AccessibleText](react_umg.TextLayoutWidgetProps.md#accessibletext)
- [AccessibleTextDelegate](react_umg.TextLayoutWidgetProps.md#accessibletextdelegate)
- [AutoWrapText](react_umg.TextLayoutWidgetProps.md#autowraptext)
- [CategoryName](react_umg.TextLayoutWidgetProps.md#categoryname)
- [Clipping](react_umg.TextLayoutWidgetProps.md#clipping)
- [Cursor](react_umg.TextLayoutWidgetProps.md#cursor)
- [DesignerFlags](react_umg.TextLayoutWidgetProps.md#designerflags)
- [DisplayLabel](react_umg.TextLayoutWidgetProps.md#displaylabel)
- [FlowDirectionPreference](react_umg.TextLayoutWidgetProps.md#flowdirectionpreference)
- [Justification](react_umg.TextLayoutWidgetProps.md#justification)
- [LineHeightPercentage](react_umg.TextLayoutWidgetProps.md#lineheightpercentage)
- [Margin](react_umg.TextLayoutWidgetProps.md#margin)
- [RenderOpacity](react_umg.TextLayoutWidgetProps.md#renderopacity)
- [RenderTransform](react_umg.TextLayoutWidgetProps.md#rendertransform)
- [RenderTransformPivot](react_umg.TextLayoutWidgetProps.md#rendertransformpivot)
- [ShapedTextOptions](react_umg.TextLayoutWidgetProps.md#shapedtextoptions)
- [Slot](react_umg.TextLayoutWidgetProps.md#slot)
- [ToolTipText](react_umg.TextLayoutWidgetProps.md#tooltiptext)
- [ToolTipTextDelegate](react_umg.TextLayoutWidgetProps.md#tooltiptextdelegate)
- [Visibility](react_umg.TextLayoutWidgetProps.md#visibility)
- [VisibilityDelegate](react_umg.TextLayoutWidgetProps.md#visibilitydelegate)
- [WrapTextAt](react_umg.TextLayoutWidgetProps.md#wraptextat)
- [WrappingPolicy](react_umg.TextLayoutWidgetProps.md#wrappingpolicy)
- [bCanChildrenBeAccessible](react_umg.TextLayoutWidgetProps.md#bcanchildrenbeaccessible)
- [bCreatedByConstructionScript](react_umg.TextLayoutWidgetProps.md#bcreatedbyconstructionscript)
- [bExpandedInDesigner](react_umg.TextLayoutWidgetProps.md#bexpandedindesigner)
- [bHiddenInDesigner](react_umg.TextLayoutWidgetProps.md#bhiddenindesigner)
- [bIsEnabled](react_umg.TextLayoutWidgetProps.md#bisenabled)
- [bIsEnabledDelegate](react_umg.TextLayoutWidgetProps.md#bisenableddelegate)
- [bIsVariable](react_umg.TextLayoutWidgetProps.md#bisvariable)
- [bIsVolatile](react_umg.TextLayoutWidgetProps.md#bisvolatile)
- [bLockedInDesigner](react_umg.TextLayoutWidgetProps.md#blockedindesigner)
- [bOverrideAccessibleDefaults](react_umg.TextLayoutWidgetProps.md#boverrideaccessibledefaults)
- [bOverride\_Cursor](react_umg.TextLayoutWidgetProps.md#boverride_cursor)

## Properties

### AccessibleBehavior

• `Optional` **AccessibleBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[AccessibleBehavior](react_umg.WidgetProps.md#accessiblebehavior)

___

### AccessibleSummaryBehavior

• `Optional` **AccessibleSummaryBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[AccessibleSummaryBehavior](react_umg.WidgetProps.md#accessiblesummarybehavior)

___

### AccessibleSummaryText

• `Optional` **AccessibleSummaryText**: `string`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[AccessibleSummaryText](react_umg.WidgetProps.md#accessiblesummarytext)

___

### AccessibleSummaryTextDelegate

• `Optional` **AccessibleSummaryTextDelegate**: () => `string`

#### Type declaration

▸ (): `string`

##### Returns

`string`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[AccessibleSummaryTextDelegate](react_umg.WidgetProps.md#accessiblesummarytextdelegate)

___

### AccessibleText

• `Optional` **AccessibleText**: `string`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[AccessibleText](react_umg.WidgetProps.md#accessibletext)

___

### AccessibleTextDelegate

• `Optional` **AccessibleTextDelegate**: () => `string`

#### Type declaration

▸ (): `string`

##### Returns

`string`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[AccessibleTextDelegate](react_umg.WidgetProps.md#accessibletextdelegate)

___

### AutoWrapText

• `Optional` **AutoWrapText**: `boolean`

___

### CategoryName

• `Optional` **CategoryName**: `string`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[CategoryName](react_umg.WidgetProps.md#categoryname)

___

### Clipping

• `Optional` **Clipping**: [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[Clipping](react_umg.WidgetProps.md#clipping)

___

### Cursor

• `Optional` **Cursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[Cursor](react_umg.WidgetProps.md#cursor)

___

### DesignerFlags

• `Optional` **DesignerFlags**: `number`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[DesignerFlags](react_umg.WidgetProps.md#designerflags)

___

### DisplayLabel

• `Optional` **DisplayLabel**: `string`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[DisplayLabel](react_umg.WidgetProps.md#displaylabel)

___

### FlowDirectionPreference

• `Optional` **FlowDirectionPreference**: [`EFlowDirectionPreference`](../enums/ue_ue.EFlowDirectionPreference.md)

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[FlowDirectionPreference](react_umg.WidgetProps.md#flowdirectionpreference)

___

### Justification

• `Optional` **Justification**: [`ETextJustify`](../enums/ue_ue.ETextJustify.md)

___

### LineHeightPercentage

• `Optional` **LineHeightPercentage**: `number`

___

### Margin

• `Optional` **Margin**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`Margin`](../classes/ue_ue.Margin.md)\>

___

### RenderOpacity

• `Optional` **RenderOpacity**: `number`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[RenderOpacity](react_umg.WidgetProps.md#renderopacity)

___

### RenderTransform

• `Optional` **RenderTransform**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`WidgetTransform`](../classes/ue_ue.WidgetTransform.md)\>

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[RenderTransform](react_umg.WidgetProps.md#rendertransform)

___

### RenderTransformPivot

• `Optional` **RenderTransformPivot**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`Vector2D`](../classes/ue_ue_s.Vector2D.md)\>

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[RenderTransformPivot](react_umg.WidgetProps.md#rendertransformpivot)

___

### ShapedTextOptions

• `Optional` **ShapedTextOptions**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`ShapedTextOptions`](../classes/ue_ue.ShapedTextOptions.md)\>

___

### Slot

• `Optional` **Slot**: [`PanelSlot`](react_umg.PanelSlot.md)

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[Slot](react_umg.WidgetProps.md#slot)

___

### ToolTipText

• `Optional` **ToolTipText**: `string`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[ToolTipText](react_umg.WidgetProps.md#tooltiptext)

___

### ToolTipTextDelegate

• `Optional` **ToolTipTextDelegate**: () => `string`

#### Type declaration

▸ (): `string`

##### Returns

`string`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[ToolTipTextDelegate](react_umg.WidgetProps.md#tooltiptextdelegate)

___

### Visibility

• `Optional` **Visibility**: [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[Visibility](react_umg.WidgetProps.md#visibility)

___

### VisibilityDelegate

• `Optional` **VisibilityDelegate**: () => [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Type declaration

▸ (): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

##### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[VisibilityDelegate](react_umg.WidgetProps.md#visibilitydelegate)

___

### WrapTextAt

• `Optional` **WrapTextAt**: `number`

___

### WrappingPolicy

• `Optional` **WrappingPolicy**: [`ETextWrappingPolicy`](../enums/ue_ue.ETextWrappingPolicy.md)

___

### bCanChildrenBeAccessible

• `Optional` **bCanChildrenBeAccessible**: `boolean`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[bCanChildrenBeAccessible](react_umg.WidgetProps.md#bcanchildrenbeaccessible)

___

### bCreatedByConstructionScript

• `Optional` **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[bCreatedByConstructionScript](react_umg.WidgetProps.md#bcreatedbyconstructionscript)

___

### bExpandedInDesigner

• `Optional` **bExpandedInDesigner**: `boolean`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[bExpandedInDesigner](react_umg.WidgetProps.md#bexpandedindesigner)

___

### bHiddenInDesigner

• `Optional` **bHiddenInDesigner**: `boolean`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[bHiddenInDesigner](react_umg.WidgetProps.md#bhiddenindesigner)

___

### bIsEnabled

• `Optional` **bIsEnabled**: `boolean`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[bIsEnabled](react_umg.WidgetProps.md#bisenabled)

___

### bIsEnabledDelegate

• `Optional` **bIsEnabledDelegate**: () => `boolean`

#### Type declaration

▸ (): `boolean`

##### Returns

`boolean`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[bIsEnabledDelegate](react_umg.WidgetProps.md#bisenableddelegate)

___

### bIsVariable

• `Optional` **bIsVariable**: `boolean`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[bIsVariable](react_umg.WidgetProps.md#bisvariable)

___

### bIsVolatile

• `Optional` **bIsVolatile**: `boolean`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[bIsVolatile](react_umg.WidgetProps.md#bisvolatile)

___

### bLockedInDesigner

• `Optional` **bLockedInDesigner**: `boolean`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[bLockedInDesigner](react_umg.WidgetProps.md#blockedindesigner)

___

### bOverrideAccessibleDefaults

• `Optional` **bOverrideAccessibleDefaults**: `boolean`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[bOverrideAccessibleDefaults](react_umg.WidgetProps.md#boverrideaccessibledefaults)

___

### bOverride\_Cursor

• `Optional` **bOverride\_Cursor**: `boolean`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[bOverride_Cursor](react_umg.WidgetProps.md#boverride_cursor)
