[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / ImageProps

# Interface: ImageProps

[react-umg](../modules/react_umg.md).ImageProps

## Hierarchy

- [`WidgetProps`](react_umg.WidgetProps.md)

  ↳ **`ImageProps`**

  ↳↳ [`TextureImageProps`](react_umg.TextureImageProps.md)

## Table of contents

### Properties

- [AccessibleBehavior](react_umg.ImageProps.md#accessiblebehavior)
- [AccessibleSummaryBehavior](react_umg.ImageProps.md#accessiblesummarybehavior)
- [AccessibleSummaryText](react_umg.ImageProps.md#accessiblesummarytext)
- [AccessibleSummaryTextDelegate](react_umg.ImageProps.md#accessiblesummarytextdelegate)
- [AccessibleText](react_umg.ImageProps.md#accessibletext)
- [AccessibleTextDelegate](react_umg.ImageProps.md#accessibletextdelegate)
- [Brush](react_umg.ImageProps.md#brush)
- [BrushDelegate](react_umg.ImageProps.md#brushdelegate)
- [CategoryName](react_umg.ImageProps.md#categoryname)
- [Clipping](react_umg.ImageProps.md#clipping)
- [ColorAndOpacity](react_umg.ImageProps.md#colorandopacity)
- [ColorAndOpacityDelegate](react_umg.ImageProps.md#colorandopacitydelegate)
- [Cursor](react_umg.ImageProps.md#cursor)
- [DesignerFlags](react_umg.ImageProps.md#designerflags)
- [DisplayLabel](react_umg.ImageProps.md#displaylabel)
- [FlowDirectionPreference](react_umg.ImageProps.md#flowdirectionpreference)
- [OnMouseButtonDownEvent](react_umg.ImageProps.md#onmousebuttondownevent)
- [RenderOpacity](react_umg.ImageProps.md#renderopacity)
- [RenderTransform](react_umg.ImageProps.md#rendertransform)
- [RenderTransformPivot](react_umg.ImageProps.md#rendertransformpivot)
- [Slot](react_umg.ImageProps.md#slot)
- [ToolTipText](react_umg.ImageProps.md#tooltiptext)
- [ToolTipTextDelegate](react_umg.ImageProps.md#tooltiptextdelegate)
- [Visibility](react_umg.ImageProps.md#visibility)
- [VisibilityDelegate](react_umg.ImageProps.md#visibilitydelegate)
- [bCanChildrenBeAccessible](react_umg.ImageProps.md#bcanchildrenbeaccessible)
- [bCreatedByConstructionScript](react_umg.ImageProps.md#bcreatedbyconstructionscript)
- [bExpandedInDesigner](react_umg.ImageProps.md#bexpandedindesigner)
- [bFlipForRightToLeftFlowDirection](react_umg.ImageProps.md#bflipforrighttoleftflowdirection)
- [bHiddenInDesigner](react_umg.ImageProps.md#bhiddenindesigner)
- [bIsEnabled](react_umg.ImageProps.md#bisenabled)
- [bIsEnabledDelegate](react_umg.ImageProps.md#bisenableddelegate)
- [bIsVariable](react_umg.ImageProps.md#bisvariable)
- [bIsVolatile](react_umg.ImageProps.md#bisvolatile)
- [bLockedInDesigner](react_umg.ImageProps.md#blockedindesigner)
- [bOverrideAccessibleDefaults](react_umg.ImageProps.md#boverrideaccessibledefaults)
- [bOverride\_Cursor](react_umg.ImageProps.md#boverride_cursor)

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

### Brush

• `Optional` **Brush**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`SlateBrush`](../classes/ue_ue.SlateBrush.md)\>

___

### BrushDelegate

• `Optional` **BrushDelegate**: () => [`SlateBrush`](../classes/ue_ue.SlateBrush.md)

#### Type declaration

▸ (): [`SlateBrush`](../classes/ue_ue.SlateBrush.md)

##### Returns

[`SlateBrush`](../classes/ue_ue.SlateBrush.md)

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

### OnMouseButtonDownEvent

• `Optional` **OnMouseButtonDownEvent**: (`MyGeometry`: [`Geometry`](../classes/ue_ue.Geometry.md), `MouseEvent`: [`PointerEvent`](../classes/ue_ue.PointerEvent.md)) => [`EventReply`](../classes/ue_ue.EventReply.md)

#### Type declaration

▸ (`MyGeometry`, `MouseEvent`): [`EventReply`](../classes/ue_ue.EventReply.md)

##### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](../classes/ue_ue.Geometry.md) |
| `MouseEvent` | [`PointerEvent`](../classes/ue_ue.PointerEvent.md) |

##### Returns

[`EventReply`](../classes/ue_ue.EventReply.md)

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

### bFlipForRightToLeftFlowDirection

• `Optional` **bFlipForRightToLeftFlowDirection**: `boolean`

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
