[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / BorderProps

# Interface: BorderProps

[react-umg](../modules/react_umg.md).BorderProps

## Hierarchy

- [`ContentWidgetProps`](react_umg.ContentWidgetProps.md)

  ↳ **`BorderProps`**

## Table of contents

### Properties

- [AccessibleBehavior](react_umg.BorderProps.md#accessiblebehavior)
- [AccessibleSummaryBehavior](react_umg.BorderProps.md#accessiblesummarybehavior)
- [AccessibleSummaryText](react_umg.BorderProps.md#accessiblesummarytext)
- [AccessibleSummaryTextDelegate](react_umg.BorderProps.md#accessiblesummarytextdelegate)
- [AccessibleText](react_umg.BorderProps.md#accessibletext)
- [AccessibleTextDelegate](react_umg.BorderProps.md#accessibletextdelegate)
- [Background](react_umg.BorderProps.md#background)
- [BackgroundDelegate](react_umg.BorderProps.md#backgrounddelegate)
- [BrushColor](react_umg.BorderProps.md#brushcolor)
- [BrushColorDelegate](react_umg.BorderProps.md#brushcolordelegate)
- [CategoryName](react_umg.BorderProps.md#categoryname)
- [Clipping](react_umg.BorderProps.md#clipping)
- [ContentColorAndOpacity](react_umg.BorderProps.md#contentcolorandopacity)
- [ContentColorAndOpacityDelegate](react_umg.BorderProps.md#contentcolorandopacitydelegate)
- [Cursor](react_umg.BorderProps.md#cursor)
- [DesignerFlags](react_umg.BorderProps.md#designerflags)
- [DesiredSizeScale](react_umg.BorderProps.md#desiredsizescale)
- [DisplayLabel](react_umg.BorderProps.md#displaylabel)
- [FlowDirectionPreference](react_umg.BorderProps.md#flowdirectionpreference)
- [HorizontalAlignment](react_umg.BorderProps.md#horizontalalignment)
- [OnMouseButtonDownEvent](react_umg.BorderProps.md#onmousebuttondownevent)
- [OnMouseButtonUpEvent](react_umg.BorderProps.md#onmousebuttonupevent)
- [OnMouseDoubleClickEvent](react_umg.BorderProps.md#onmousedoubleclickevent)
- [OnMouseMoveEvent](react_umg.BorderProps.md#onmousemoveevent)
- [Padding](react_umg.BorderProps.md#padding)
- [RenderOpacity](react_umg.BorderProps.md#renderopacity)
- [RenderTransform](react_umg.BorderProps.md#rendertransform)
- [RenderTransformPivot](react_umg.BorderProps.md#rendertransformpivot)
- [Slot](react_umg.BorderProps.md#slot)
- [ToolTipText](react_umg.BorderProps.md#tooltiptext)
- [ToolTipTextDelegate](react_umg.BorderProps.md#tooltiptextdelegate)
- [VerticalAlignment](react_umg.BorderProps.md#verticalalignment)
- [Visibility](react_umg.BorderProps.md#visibility)
- [VisibilityDelegate](react_umg.BorderProps.md#visibilitydelegate)
- [bCanChildrenBeAccessible](react_umg.BorderProps.md#bcanchildrenbeaccessible)
- [bCreatedByConstructionScript](react_umg.BorderProps.md#bcreatedbyconstructionscript)
- [bExpandedInDesigner](react_umg.BorderProps.md#bexpandedindesigner)
- [bFlipForRightToLeftFlowDirection](react_umg.BorderProps.md#bflipforrighttoleftflowdirection)
- [bHiddenInDesigner](react_umg.BorderProps.md#bhiddenindesigner)
- [bIsEnabled](react_umg.BorderProps.md#bisenabled)
- [bIsEnabledDelegate](react_umg.BorderProps.md#bisenableddelegate)
- [bIsVariable](react_umg.BorderProps.md#bisvariable)
- [bIsVolatile](react_umg.BorderProps.md#bisvolatile)
- [bLockedInDesigner](react_umg.BorderProps.md#blockedindesigner)
- [bOverrideAccessibleDefaults](react_umg.BorderProps.md#boverrideaccessibledefaults)
- [bOverride\_Cursor](react_umg.BorderProps.md#boverride_cursor)
- [bShowEffectWhenDisabled](react_umg.BorderProps.md#bshoweffectwhendisabled)

## Properties

### AccessibleBehavior

• `Optional` **AccessibleBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[AccessibleBehavior](react_umg.ContentWidgetProps.md#accessiblebehavior)

___

### AccessibleSummaryBehavior

• `Optional` **AccessibleSummaryBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[AccessibleSummaryBehavior](react_umg.ContentWidgetProps.md#accessiblesummarybehavior)

___

### AccessibleSummaryText

• `Optional` **AccessibleSummaryText**: `string`

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[AccessibleSummaryText](react_umg.ContentWidgetProps.md#accessiblesummarytext)

___

### AccessibleSummaryTextDelegate

• `Optional` **AccessibleSummaryTextDelegate**: () => `string`

#### Type declaration

▸ (): `string`

##### Returns

`string`

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[AccessibleSummaryTextDelegate](react_umg.ContentWidgetProps.md#accessiblesummarytextdelegate)

___

### AccessibleText

• `Optional` **AccessibleText**: `string`

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[AccessibleText](react_umg.ContentWidgetProps.md#accessibletext)

___

### AccessibleTextDelegate

• `Optional` **AccessibleTextDelegate**: () => `string`

#### Type declaration

▸ (): `string`

##### Returns

`string`

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[AccessibleTextDelegate](react_umg.ContentWidgetProps.md#accessibletextdelegate)

___

### Background

• `Optional` **Background**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`SlateBrush`](../classes/ue_ue.SlateBrush.md)\>

___

### BackgroundDelegate

• `Optional` **BackgroundDelegate**: () => [`SlateBrush`](../classes/ue_ue.SlateBrush.md)

#### Type declaration

▸ (): [`SlateBrush`](../classes/ue_ue.SlateBrush.md)

##### Returns

[`SlateBrush`](../classes/ue_ue.SlateBrush.md)

___

### BrushColor

• `Optional` **BrushColor**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`LinearColor`](../classes/ue_ue_s.LinearColor.md)\>

___

### BrushColorDelegate

• `Optional` **BrushColorDelegate**: () => [`LinearColor`](../classes/ue_ue_s.LinearColor.md)

#### Type declaration

▸ (): [`LinearColor`](../classes/ue_ue_s.LinearColor.md)

##### Returns

[`LinearColor`](../classes/ue_ue_s.LinearColor.md)

___

### CategoryName

• `Optional` **CategoryName**: `string`

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[CategoryName](react_umg.ContentWidgetProps.md#categoryname)

___

### Clipping

• `Optional` **Clipping**: [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[Clipping](react_umg.ContentWidgetProps.md#clipping)

___

### ContentColorAndOpacity

• `Optional` **ContentColorAndOpacity**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`LinearColor`](../classes/ue_ue_s.LinearColor.md)\>

___

### ContentColorAndOpacityDelegate

• `Optional` **ContentColorAndOpacityDelegate**: () => [`LinearColor`](../classes/ue_ue_s.LinearColor.md)

#### Type declaration

▸ (): [`LinearColor`](../classes/ue_ue_s.LinearColor.md)

##### Returns

[`LinearColor`](../classes/ue_ue_s.LinearColor.md)

___

### Cursor

• `Optional` **Cursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[Cursor](react_umg.ContentWidgetProps.md#cursor)

___

### DesignerFlags

• `Optional` **DesignerFlags**: `number`

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[DesignerFlags](react_umg.ContentWidgetProps.md#designerflags)

___

### DesiredSizeScale

• `Optional` **DesiredSizeScale**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`Vector2D`](../classes/ue_ue_s.Vector2D.md)\>

___

### DisplayLabel

• `Optional` **DisplayLabel**: `string`

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[DisplayLabel](react_umg.ContentWidgetProps.md#displaylabel)

___

### FlowDirectionPreference

• `Optional` **FlowDirectionPreference**: [`EFlowDirectionPreference`](../enums/ue_ue.EFlowDirectionPreference.md)

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[FlowDirectionPreference](react_umg.ContentWidgetProps.md#flowdirectionpreference)

___

### HorizontalAlignment

• `Optional` **HorizontalAlignment**: [`EHorizontalAlignment`](../enums/ue_ue.EHorizontalAlignment.md)

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

### OnMouseButtonUpEvent

• `Optional` **OnMouseButtonUpEvent**: (`MyGeometry`: [`Geometry`](../classes/ue_ue.Geometry.md), `MouseEvent`: [`PointerEvent`](../classes/ue_ue.PointerEvent.md)) => [`EventReply`](../classes/ue_ue.EventReply.md)

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

### OnMouseDoubleClickEvent

• `Optional` **OnMouseDoubleClickEvent**: (`MyGeometry`: [`Geometry`](../classes/ue_ue.Geometry.md), `MouseEvent`: [`PointerEvent`](../classes/ue_ue.PointerEvent.md)) => [`EventReply`](../classes/ue_ue.EventReply.md)

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

### OnMouseMoveEvent

• `Optional` **OnMouseMoveEvent**: (`MyGeometry`: [`Geometry`](../classes/ue_ue.Geometry.md), `MouseEvent`: [`PointerEvent`](../classes/ue_ue.PointerEvent.md)) => [`EventReply`](../classes/ue_ue.EventReply.md)

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

### Padding

• `Optional` **Padding**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`Margin`](../classes/ue_ue.Margin.md)\>

___

### RenderOpacity

• `Optional` **RenderOpacity**: `number`

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[RenderOpacity](react_umg.ContentWidgetProps.md#renderopacity)

___

### RenderTransform

• `Optional` **RenderTransform**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`WidgetTransform`](../classes/ue_ue.WidgetTransform.md)\>

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[RenderTransform](react_umg.ContentWidgetProps.md#rendertransform)

___

### RenderTransformPivot

• `Optional` **RenderTransformPivot**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`Vector2D`](../classes/ue_ue_s.Vector2D.md)\>

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[RenderTransformPivot](react_umg.ContentWidgetProps.md#rendertransformpivot)

___

### Slot

• `Optional` **Slot**: [`PanelSlot`](react_umg.PanelSlot.md)

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[Slot](react_umg.ContentWidgetProps.md#slot)

___

### ToolTipText

• `Optional` **ToolTipText**: `string`

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[ToolTipText](react_umg.ContentWidgetProps.md#tooltiptext)

___

### ToolTipTextDelegate

• `Optional` **ToolTipTextDelegate**: () => `string`

#### Type declaration

▸ (): `string`

##### Returns

`string`

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[ToolTipTextDelegate](react_umg.ContentWidgetProps.md#tooltiptextdelegate)

___

### VerticalAlignment

• `Optional` **VerticalAlignment**: [`EVerticalAlignment`](../enums/ue_ue.EVerticalAlignment.md)

___

### Visibility

• `Optional` **Visibility**: [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[Visibility](react_umg.ContentWidgetProps.md#visibility)

___

### VisibilityDelegate

• `Optional` **VisibilityDelegate**: () => [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Type declaration

▸ (): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

##### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[VisibilityDelegate](react_umg.ContentWidgetProps.md#visibilitydelegate)

___

### bCanChildrenBeAccessible

• `Optional` **bCanChildrenBeAccessible**: `boolean`

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[bCanChildrenBeAccessible](react_umg.ContentWidgetProps.md#bcanchildrenbeaccessible)

___

### bCreatedByConstructionScript

• `Optional` **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[bCreatedByConstructionScript](react_umg.ContentWidgetProps.md#bcreatedbyconstructionscript)

___

### bExpandedInDesigner

• `Optional` **bExpandedInDesigner**: `boolean`

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[bExpandedInDesigner](react_umg.ContentWidgetProps.md#bexpandedindesigner)

___

### bFlipForRightToLeftFlowDirection

• `Optional` **bFlipForRightToLeftFlowDirection**: `boolean`

___

### bHiddenInDesigner

• `Optional` **bHiddenInDesigner**: `boolean`

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[bHiddenInDesigner](react_umg.ContentWidgetProps.md#bhiddenindesigner)

___

### bIsEnabled

• `Optional` **bIsEnabled**: `boolean`

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[bIsEnabled](react_umg.ContentWidgetProps.md#bisenabled)

___

### bIsEnabledDelegate

• `Optional` **bIsEnabledDelegate**: () => `boolean`

#### Type declaration

▸ (): `boolean`

##### Returns

`boolean`

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[bIsEnabledDelegate](react_umg.ContentWidgetProps.md#bisenableddelegate)

___

### bIsVariable

• `Optional` **bIsVariable**: `boolean`

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[bIsVariable](react_umg.ContentWidgetProps.md#bisvariable)

___

### bIsVolatile

• `Optional` **bIsVolatile**: `boolean`

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[bIsVolatile](react_umg.ContentWidgetProps.md#bisvolatile)

___

### bLockedInDesigner

• `Optional` **bLockedInDesigner**: `boolean`

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[bLockedInDesigner](react_umg.ContentWidgetProps.md#blockedindesigner)

___

### bOverrideAccessibleDefaults

• `Optional` **bOverrideAccessibleDefaults**: `boolean`

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[bOverrideAccessibleDefaults](react_umg.ContentWidgetProps.md#boverrideaccessibledefaults)

___

### bOverride\_Cursor

• `Optional` **bOverride\_Cursor**: `boolean`

#### Inherited from

[ContentWidgetProps](react_umg.ContentWidgetProps.md).[bOverride_Cursor](react_umg.ContentWidgetProps.md#boverride_cursor)

___

### bShowEffectWhenDisabled

• `Optional` **bShowEffectWhenDisabled**: `boolean`
