[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / ReactWidgetProps

# Interface: ReactWidgetProps

[react-umg](../modules/react_umg.md).ReactWidgetProps

## Hierarchy

- [`UserWidgetProps`](react_umg.UserWidgetProps.md)

  ↳ **`ReactWidgetProps`**

## Table of contents

### Properties

- [AccessibleBehavior](react_umg.ReactWidgetProps.md#accessiblebehavior)
- [AccessibleSummaryBehavior](react_umg.ReactWidgetProps.md#accessiblesummarybehavior)
- [AccessibleSummaryText](react_umg.ReactWidgetProps.md#accessiblesummarytext)
- [AccessibleSummaryTextDelegate](react_umg.ReactWidgetProps.md#accessiblesummarytextdelegate)
- [AccessibleText](react_umg.ReactWidgetProps.md#accessibletext)
- [AccessibleTextDelegate](react_umg.ReactWidgetProps.md#accessibletextdelegate)
- [AnimationCallbacks](react_umg.ReactWidgetProps.md#animationcallbacks)
- [CategoryName](react_umg.ReactWidgetProps.md#categoryname)
- [Clipping](react_umg.ReactWidgetProps.md#clipping)
- [ColorAndOpacity](react_umg.ReactWidgetProps.md#colorandopacity)
- [ColorAndOpacityDelegate](react_umg.ReactWidgetProps.md#colorandopacitydelegate)
- [Cursor](react_umg.ReactWidgetProps.md#cursor)
- [DesignSizeMode](react_umg.ReactWidgetProps.md#designsizemode)
- [DesignTimeSize](react_umg.ReactWidgetProps.md#designtimesize)
- [DesignerFlags](react_umg.ReactWidgetProps.md#designerflags)
- [DisplayLabel](react_umg.ReactWidgetProps.md#displaylabel)
- [FlowDirectionPreference](react_umg.ReactWidgetProps.md#flowdirectionpreference)
- [ForegroundColor](react_umg.ReactWidgetProps.md#foregroundcolor)
- [ForegroundColorDelegate](react_umg.ReactWidgetProps.md#foregroundcolordelegate)
- [NamedSlotBindings](react_umg.ReactWidgetProps.md#namedslotbindings)
- [Padding](react_umg.ReactWidgetProps.md#padding)
- [PaletteCategory](react_umg.ReactWidgetProps.md#palettecategory)
- [Priority](react_umg.ReactWidgetProps.md#priority)
- [RenderOpacity](react_umg.ReactWidgetProps.md#renderopacity)
- [RenderTransform](react_umg.ReactWidgetProps.md#rendertransform)
- [RenderTransformPivot](react_umg.ReactWidgetProps.md#rendertransformpivot)
- [Slot](react_umg.ReactWidgetProps.md#slot)
- [TickFrequency](react_umg.ReactWidgetProps.md#tickfrequency)
- [ToolTipText](react_umg.ReactWidgetProps.md#tooltiptext)
- [ToolTipTextDelegate](react_umg.ReactWidgetProps.md#tooltiptextdelegate)
- [Visibility](react_umg.ReactWidgetProps.md#visibility)
- [VisibilityDelegate](react_umg.ReactWidgetProps.md#visibilitydelegate)
- [bCanChildrenBeAccessible](react_umg.ReactWidgetProps.md#bcanchildrenbeaccessible)
- [bCookedWidgetTree](react_umg.ReactWidgetProps.md#bcookedwidgettree)
- [bCreatedByConstructionScript](react_umg.ReactWidgetProps.md#bcreatedbyconstructionscript)
- [bExpandedInDesigner](react_umg.ReactWidgetProps.md#bexpandedindesigner)
- [bHasScriptImplementedPaint](react_umg.ReactWidgetProps.md#bhasscriptimplementedpaint)
- [bHasScriptImplementedTick](react_umg.ReactWidgetProps.md#bhasscriptimplementedtick)
- [bHiddenInDesigner](react_umg.ReactWidgetProps.md#bhiddenindesigner)
- [bIsEnabled](react_umg.ReactWidgetProps.md#bisenabled)
- [bIsEnabledDelegate](react_umg.ReactWidgetProps.md#bisenableddelegate)
- [bIsFocusable](react_umg.ReactWidgetProps.md#bisfocusable)
- [bIsVariable](react_umg.ReactWidgetProps.md#bisvariable)
- [bIsVolatile](react_umg.ReactWidgetProps.md#bisvolatile)
- [bLockedInDesigner](react_umg.ReactWidgetProps.md#blockedindesigner)
- [bOverrideAccessibleDefaults](react_umg.ReactWidgetProps.md#boverrideaccessibledefaults)
- [bOverride\_Cursor](react_umg.ReactWidgetProps.md#boverride_cursor)
- [bStopAction](react_umg.ReactWidgetProps.md#bstopaction)
- [bSupportsKeyboardFocus](react_umg.ReactWidgetProps.md#bsupportskeyboardfocus)

## Properties

### AccessibleBehavior

• `Optional` **AccessibleBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[AccessibleBehavior](react_umg.UserWidgetProps.md#accessiblebehavior)

___

### AccessibleSummaryBehavior

• `Optional` **AccessibleSummaryBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[AccessibleSummaryBehavior](react_umg.UserWidgetProps.md#accessiblesummarybehavior)

___

### AccessibleSummaryText

• `Optional` **AccessibleSummaryText**: `string`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[AccessibleSummaryText](react_umg.UserWidgetProps.md#accessiblesummarytext)

___

### AccessibleSummaryTextDelegate

• `Optional` **AccessibleSummaryTextDelegate**: () => `string`

#### Type declaration

▸ (): `string`

##### Returns

`string`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[AccessibleSummaryTextDelegate](react_umg.UserWidgetProps.md#accessiblesummarytextdelegate)

___

### AccessibleText

• `Optional` **AccessibleText**: `string`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[AccessibleText](react_umg.UserWidgetProps.md#accessibletext)

___

### AccessibleTextDelegate

• `Optional` **AccessibleTextDelegate**: () => `string`

#### Type declaration

▸ (): `string`

##### Returns

`string`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[AccessibleTextDelegate](react_umg.UserWidgetProps.md#accessibletextdelegate)

___

### AnimationCallbacks

• `Optional` **AnimationCallbacks**: [`TArray`](../modules/react_umg.md#tarray)<[`AnimationEventBinding`](../classes/ue_ue.AnimationEventBinding.md)\>

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[AnimationCallbacks](react_umg.UserWidgetProps.md#animationcallbacks)

___

### CategoryName

• `Optional` **CategoryName**: `string`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[CategoryName](react_umg.UserWidgetProps.md#categoryname)

___

### Clipping

• `Optional` **Clipping**: [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[Clipping](react_umg.UserWidgetProps.md#clipping)

___

### ColorAndOpacity

• `Optional` **ColorAndOpacity**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`LinearColor`](../classes/ue_ue_s.LinearColor.md)\>

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[ColorAndOpacity](react_umg.UserWidgetProps.md#colorandopacity)

___

### ColorAndOpacityDelegate

• `Optional` **ColorAndOpacityDelegate**: () => [`LinearColor`](../classes/ue_ue_s.LinearColor.md)

#### Type declaration

▸ (): [`LinearColor`](../classes/ue_ue_s.LinearColor.md)

##### Returns

[`LinearColor`](../classes/ue_ue_s.LinearColor.md)

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[ColorAndOpacityDelegate](react_umg.UserWidgetProps.md#colorandopacitydelegate)

___

### Cursor

• `Optional` **Cursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[Cursor](react_umg.UserWidgetProps.md#cursor)

___

### DesignSizeMode

• `Optional` **DesignSizeMode**: [`EDesignPreviewSizeMode`](../enums/ue_ue.EDesignPreviewSizeMode.md)

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[DesignSizeMode](react_umg.UserWidgetProps.md#designsizemode)

___

### DesignTimeSize

• `Optional` **DesignTimeSize**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`Vector2D`](../classes/ue_ue_s.Vector2D.md)\>

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[DesignTimeSize](react_umg.UserWidgetProps.md#designtimesize)

___

### DesignerFlags

• `Optional` **DesignerFlags**: `number`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[DesignerFlags](react_umg.UserWidgetProps.md#designerflags)

___

### DisplayLabel

• `Optional` **DisplayLabel**: `string`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[DisplayLabel](react_umg.UserWidgetProps.md#displaylabel)

___

### FlowDirectionPreference

• `Optional` **FlowDirectionPreference**: [`EFlowDirectionPreference`](../enums/ue_ue.EFlowDirectionPreference.md)

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[FlowDirectionPreference](react_umg.UserWidgetProps.md#flowdirectionpreference)

___

### ForegroundColor

• `Optional` **ForegroundColor**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`SlateColor`](../classes/ue_ue.SlateColor.md)\>

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[ForegroundColor](react_umg.UserWidgetProps.md#foregroundcolor)

___

### ForegroundColorDelegate

• `Optional` **ForegroundColorDelegate**: () => [`SlateColor`](../classes/ue_ue.SlateColor.md)

#### Type declaration

▸ (): [`SlateColor`](../classes/ue_ue.SlateColor.md)

##### Returns

[`SlateColor`](../classes/ue_ue.SlateColor.md)

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[ForegroundColorDelegate](react_umg.UserWidgetProps.md#foregroundcolordelegate)

___

### NamedSlotBindings

• `Optional` **NamedSlotBindings**: [`TArray`](../modules/react_umg.md#tarray)<[`NamedSlotBinding`](../classes/ue_ue.NamedSlotBinding.md)\>

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[NamedSlotBindings](react_umg.UserWidgetProps.md#namedslotbindings)

___

### Padding

• `Optional` **Padding**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`Margin`](../classes/ue_ue.Margin.md)\>

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[Padding](react_umg.UserWidgetProps.md#padding)

___

### PaletteCategory

• `Optional` **PaletteCategory**: `string`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[PaletteCategory](react_umg.UserWidgetProps.md#palettecategory)

___

### Priority

• `Optional` **Priority**: `number`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[Priority](react_umg.UserWidgetProps.md#priority)

___

### RenderOpacity

• `Optional` **RenderOpacity**: `number`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[RenderOpacity](react_umg.UserWidgetProps.md#renderopacity)

___

### RenderTransform

• `Optional` **RenderTransform**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`WidgetTransform`](../classes/ue_ue.WidgetTransform.md)\>

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[RenderTransform](react_umg.UserWidgetProps.md#rendertransform)

___

### RenderTransformPivot

• `Optional` **RenderTransformPivot**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`Vector2D`](../classes/ue_ue_s.Vector2D.md)\>

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[RenderTransformPivot](react_umg.UserWidgetProps.md#rendertransformpivot)

___

### Slot

• `Optional` **Slot**: [`PanelSlot`](react_umg.PanelSlot.md)

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[Slot](react_umg.UserWidgetProps.md#slot)

___

### TickFrequency

• `Optional` **TickFrequency**: [`EWidgetTickFrequency`](../enums/ue_ue.EWidgetTickFrequency.md)

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[TickFrequency](react_umg.UserWidgetProps.md#tickfrequency)

___

### ToolTipText

• `Optional` **ToolTipText**: `string`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[ToolTipText](react_umg.UserWidgetProps.md#tooltiptext)

___

### ToolTipTextDelegate

• `Optional` **ToolTipTextDelegate**: () => `string`

#### Type declaration

▸ (): `string`

##### Returns

`string`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[ToolTipTextDelegate](react_umg.UserWidgetProps.md#tooltiptextdelegate)

___

### Visibility

• `Optional` **Visibility**: [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[Visibility](react_umg.UserWidgetProps.md#visibility)

___

### VisibilityDelegate

• `Optional` **VisibilityDelegate**: () => [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Type declaration

▸ (): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

##### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[VisibilityDelegate](react_umg.UserWidgetProps.md#visibilitydelegate)

___

### bCanChildrenBeAccessible

• `Optional` **bCanChildrenBeAccessible**: `boolean`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[bCanChildrenBeAccessible](react_umg.UserWidgetProps.md#bcanchildrenbeaccessible)

___

### bCookedWidgetTree

• `Optional` **bCookedWidgetTree**: `boolean`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[bCookedWidgetTree](react_umg.UserWidgetProps.md#bcookedwidgettree)

___

### bCreatedByConstructionScript

• `Optional` **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[bCreatedByConstructionScript](react_umg.UserWidgetProps.md#bcreatedbyconstructionscript)

___

### bExpandedInDesigner

• `Optional` **bExpandedInDesigner**: `boolean`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[bExpandedInDesigner](react_umg.UserWidgetProps.md#bexpandedindesigner)

___

### bHasScriptImplementedPaint

• `Optional` **bHasScriptImplementedPaint**: `boolean`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[bHasScriptImplementedPaint](react_umg.UserWidgetProps.md#bhasscriptimplementedpaint)

___

### bHasScriptImplementedTick

• `Optional` **bHasScriptImplementedTick**: `boolean`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[bHasScriptImplementedTick](react_umg.UserWidgetProps.md#bhasscriptimplementedtick)

___

### bHiddenInDesigner

• `Optional` **bHiddenInDesigner**: `boolean`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[bHiddenInDesigner](react_umg.UserWidgetProps.md#bhiddenindesigner)

___

### bIsEnabled

• `Optional` **bIsEnabled**: `boolean`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[bIsEnabled](react_umg.UserWidgetProps.md#bisenabled)

___

### bIsEnabledDelegate

• `Optional` **bIsEnabledDelegate**: () => `boolean`

#### Type declaration

▸ (): `boolean`

##### Returns

`boolean`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[bIsEnabledDelegate](react_umg.UserWidgetProps.md#bisenableddelegate)

___

### bIsFocusable

• `Optional` **bIsFocusable**: `boolean`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[bIsFocusable](react_umg.UserWidgetProps.md#bisfocusable)

___

### bIsVariable

• `Optional` **bIsVariable**: `boolean`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[bIsVariable](react_umg.UserWidgetProps.md#bisvariable)

___

### bIsVolatile

• `Optional` **bIsVolatile**: `boolean`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[bIsVolatile](react_umg.UserWidgetProps.md#bisvolatile)

___

### bLockedInDesigner

• `Optional` **bLockedInDesigner**: `boolean`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[bLockedInDesigner](react_umg.UserWidgetProps.md#blockedindesigner)

___

### bOverrideAccessibleDefaults

• `Optional` **bOverrideAccessibleDefaults**: `boolean`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[bOverrideAccessibleDefaults](react_umg.UserWidgetProps.md#boverrideaccessibledefaults)

___

### bOverride\_Cursor

• `Optional` **bOverride\_Cursor**: `boolean`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[bOverride_Cursor](react_umg.UserWidgetProps.md#boverride_cursor)

___

### bStopAction

• `Optional` **bStopAction**: `boolean`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[bStopAction](react_umg.UserWidgetProps.md#bstopaction)

___

### bSupportsKeyboardFocus

• `Optional` **bSupportsKeyboardFocus**: `boolean`

#### Inherited from

[UserWidgetProps](react_umg.UserWidgetProps.md).[bSupportsKeyboardFocus](react_umg.UserWidgetProps.md#bsupportskeyboardfocus)
