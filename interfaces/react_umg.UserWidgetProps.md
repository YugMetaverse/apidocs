[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / UserWidgetProps

# Interface: UserWidgetProps

[react-umg](../modules/react_umg.md).UserWidgetProps

## Hierarchy

- [`WidgetProps`](react_umg.WidgetProps.md)

  ↳ **`UserWidgetProps`**

  ↳↳ [`VREditorBaseUserWidgetProps`](react_umg.VREditorBaseUserWidgetProps.md)

  ↳↳ [`LevelSequenceBurnInProps`](react_umg.LevelSequenceBurnInProps.md)

  ↳↳ [`EditorUtilityWidgetProps`](react_umg.EditorUtilityWidgetProps.md)

  ↳↳ [`ReactWidgetProps`](react_umg.ReactWidgetProps.md)

  ↳↳ [`TestWidgetBlueprint_CProps`](react_umg.TestWidgetBlueprint_CProps.md)

## Table of contents

### Properties

- [AccessibleBehavior](react_umg.UserWidgetProps.md#accessiblebehavior)
- [AccessibleSummaryBehavior](react_umg.UserWidgetProps.md#accessiblesummarybehavior)
- [AccessibleSummaryText](react_umg.UserWidgetProps.md#accessiblesummarytext)
- [AccessibleSummaryTextDelegate](react_umg.UserWidgetProps.md#accessiblesummarytextdelegate)
- [AccessibleText](react_umg.UserWidgetProps.md#accessibletext)
- [AccessibleTextDelegate](react_umg.UserWidgetProps.md#accessibletextdelegate)
- [AnimationCallbacks](react_umg.UserWidgetProps.md#animationcallbacks)
- [CategoryName](react_umg.UserWidgetProps.md#categoryname)
- [Clipping](react_umg.UserWidgetProps.md#clipping)
- [ColorAndOpacity](react_umg.UserWidgetProps.md#colorandopacity)
- [ColorAndOpacityDelegate](react_umg.UserWidgetProps.md#colorandopacitydelegate)
- [Cursor](react_umg.UserWidgetProps.md#cursor)
- [DesignSizeMode](react_umg.UserWidgetProps.md#designsizemode)
- [DesignTimeSize](react_umg.UserWidgetProps.md#designtimesize)
- [DesignerFlags](react_umg.UserWidgetProps.md#designerflags)
- [DisplayLabel](react_umg.UserWidgetProps.md#displaylabel)
- [FlowDirectionPreference](react_umg.UserWidgetProps.md#flowdirectionpreference)
- [ForegroundColor](react_umg.UserWidgetProps.md#foregroundcolor)
- [ForegroundColorDelegate](react_umg.UserWidgetProps.md#foregroundcolordelegate)
- [NamedSlotBindings](react_umg.UserWidgetProps.md#namedslotbindings)
- [Padding](react_umg.UserWidgetProps.md#padding)
- [PaletteCategory](react_umg.UserWidgetProps.md#palettecategory)
- [Priority](react_umg.UserWidgetProps.md#priority)
- [RenderOpacity](react_umg.UserWidgetProps.md#renderopacity)
- [RenderTransform](react_umg.UserWidgetProps.md#rendertransform)
- [RenderTransformPivot](react_umg.UserWidgetProps.md#rendertransformpivot)
- [Slot](react_umg.UserWidgetProps.md#slot)
- [TickFrequency](react_umg.UserWidgetProps.md#tickfrequency)
- [ToolTipText](react_umg.UserWidgetProps.md#tooltiptext)
- [ToolTipTextDelegate](react_umg.UserWidgetProps.md#tooltiptextdelegate)
- [Visibility](react_umg.UserWidgetProps.md#visibility)
- [VisibilityDelegate](react_umg.UserWidgetProps.md#visibilitydelegate)
- [bCanChildrenBeAccessible](react_umg.UserWidgetProps.md#bcanchildrenbeaccessible)
- [bCookedWidgetTree](react_umg.UserWidgetProps.md#bcookedwidgettree)
- [bCreatedByConstructionScript](react_umg.UserWidgetProps.md#bcreatedbyconstructionscript)
- [bExpandedInDesigner](react_umg.UserWidgetProps.md#bexpandedindesigner)
- [bHasScriptImplementedPaint](react_umg.UserWidgetProps.md#bhasscriptimplementedpaint)
- [bHasScriptImplementedTick](react_umg.UserWidgetProps.md#bhasscriptimplementedtick)
- [bHiddenInDesigner](react_umg.UserWidgetProps.md#bhiddenindesigner)
- [bIsEnabled](react_umg.UserWidgetProps.md#bisenabled)
- [bIsEnabledDelegate](react_umg.UserWidgetProps.md#bisenableddelegate)
- [bIsFocusable](react_umg.UserWidgetProps.md#bisfocusable)
- [bIsVariable](react_umg.UserWidgetProps.md#bisvariable)
- [bIsVolatile](react_umg.UserWidgetProps.md#bisvolatile)
- [bLockedInDesigner](react_umg.UserWidgetProps.md#blockedindesigner)
- [bOverrideAccessibleDefaults](react_umg.UserWidgetProps.md#boverrideaccessibledefaults)
- [bOverride\_Cursor](react_umg.UserWidgetProps.md#boverride_cursor)
- [bStopAction](react_umg.UserWidgetProps.md#bstopaction)
- [bSupportsKeyboardFocus](react_umg.UserWidgetProps.md#bsupportskeyboardfocus)

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

### AnimationCallbacks

• `Optional` **AnimationCallbacks**: [`TArray`](../modules/react_umg.md#tarray)<[`AnimationEventBinding`](../classes/ue_ue.AnimationEventBinding.md)\>

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

### ColorAndOpacity

• `Optional` **ColorAndOpacity**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`LinearColor`](../classes/ue_ue_s.LinearColor.md)\>

___

### ColorAndOpacityDelegate

• `Optional` **ColorAndOpacityDelegate**: () => [`LinearColor`](../classes/ue_ue_s.LinearColor.md)

#### Type declaration

▸ (): [`LinearColor`](../classes/ue_ue_s.LinearColor.md)

##### Returns

[`LinearColor`](../classes/ue_ue_s.LinearColor.md)

___

### Cursor

• `Optional` **Cursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[Cursor](react_umg.WidgetProps.md#cursor)

___

### DesignSizeMode

• `Optional` **DesignSizeMode**: [`EDesignPreviewSizeMode`](../enums/ue_ue.EDesignPreviewSizeMode.md)

___

### DesignTimeSize

• `Optional` **DesignTimeSize**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`Vector2D`](../classes/ue_ue_s.Vector2D.md)\>

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

### ForegroundColor

• `Optional` **ForegroundColor**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`SlateColor`](../classes/ue_ue.SlateColor.md)\>

___

### ForegroundColorDelegate

• `Optional` **ForegroundColorDelegate**: () => [`SlateColor`](../classes/ue_ue.SlateColor.md)

#### Type declaration

▸ (): [`SlateColor`](../classes/ue_ue.SlateColor.md)

##### Returns

[`SlateColor`](../classes/ue_ue.SlateColor.md)

___

### NamedSlotBindings

• `Optional` **NamedSlotBindings**: [`TArray`](../modules/react_umg.md#tarray)<[`NamedSlotBinding`](../classes/ue_ue.NamedSlotBinding.md)\>

___

### Padding

• `Optional` **Padding**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`Margin`](../classes/ue_ue.Margin.md)\>

___

### PaletteCategory

• `Optional` **PaletteCategory**: `string`

___

### Priority

• `Optional` **Priority**: `number`

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

### Slot

• `Optional` **Slot**: [`PanelSlot`](react_umg.PanelSlot.md)

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[Slot](react_umg.WidgetProps.md#slot)

___

### TickFrequency

• `Optional` **TickFrequency**: [`EWidgetTickFrequency`](../enums/ue_ue.EWidgetTickFrequency.md)

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

### bCanChildrenBeAccessible

• `Optional` **bCanChildrenBeAccessible**: `boolean`

#### Inherited from

[WidgetProps](react_umg.WidgetProps.md).[bCanChildrenBeAccessible](react_umg.WidgetProps.md#bcanchildrenbeaccessible)

___

### bCookedWidgetTree

• `Optional` **bCookedWidgetTree**: `boolean`

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

### bHasScriptImplementedPaint

• `Optional` **bHasScriptImplementedPaint**: `boolean`

___

### bHasScriptImplementedTick

• `Optional` **bHasScriptImplementedTick**: `boolean`

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

### bIsFocusable

• `Optional` **bIsFocusable**: `boolean`

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

___

### bStopAction

• `Optional` **bStopAction**: `boolean`

___

### bSupportsKeyboardFocus

• `Optional` **bSupportsKeyboardFocus**: `boolean`
