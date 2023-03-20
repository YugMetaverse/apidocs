[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / ListViewProps

# Interface: ListViewProps

[react-umg](../modules/react_umg.md).ListViewProps

## Hierarchy

- [`ListViewBaseProps`](react_umg.ListViewBaseProps.md)

  ↳ **`ListViewProps`**

  ↳↳ [`TileViewProps`](react_umg.TileViewProps.md)

  ↳↳ [`TreeViewProps`](react_umg.TreeViewProps.md)

## Table of contents

### Properties

- [AccessibleBehavior](react_umg.ListViewProps.md#accessiblebehavior)
- [AccessibleSummaryBehavior](react_umg.ListViewProps.md#accessiblesummarybehavior)
- [AccessibleSummaryText](react_umg.ListViewProps.md#accessiblesummarytext)
- [AccessibleSummaryTextDelegate](react_umg.ListViewProps.md#accessiblesummarytextdelegate)
- [AccessibleText](react_umg.ListViewProps.md#accessibletext)
- [AccessibleTextDelegate](react_umg.ListViewProps.md#accessibletextdelegate)
- [CategoryName](react_umg.ListViewProps.md#categoryname)
- [Clipping](react_umg.ListViewProps.md#clipping)
- [ConsumeMouseWheel](react_umg.ListViewProps.md#consumemousewheel)
- [Cursor](react_umg.ListViewProps.md#cursor)
- [DesignerFlags](react_umg.ListViewProps.md#designerflags)
- [DisplayLabel](react_umg.ListViewProps.md#displaylabel)
- [EntrySpacing](react_umg.ListViewProps.md#entryspacing)
- [EntryWidgetPool](react_umg.ListViewProps.md#entrywidgetpool)
- [FixedLineScrollOffset](react_umg.ListViewProps.md#fixedlinescrolloffset)
- [FlowDirectionPreference](react_umg.ListViewProps.md#flowdirectionpreference)
- [NumDesignerPreviewEntries](react_umg.ListViewProps.md#numdesignerpreviewentries)
- [Orientation](react_umg.ListViewProps.md#orientation)
- [RenderOpacity](react_umg.ListViewProps.md#renderopacity)
- [RenderTransform](react_umg.ListViewProps.md#rendertransform)
- [RenderTransformPivot](react_umg.ListViewProps.md#rendertransformpivot)
- [SelectionMode](react_umg.ListViewProps.md#selectionmode)
- [Slot](react_umg.ListViewProps.md#slot)
- [ToolTipText](react_umg.ListViewProps.md#tooltiptext)
- [ToolTipTextDelegate](react_umg.ListViewProps.md#tooltiptextdelegate)
- [Visibility](react_umg.ListViewProps.md#visibility)
- [VisibilityDelegate](react_umg.ListViewProps.md#visibilitydelegate)
- [WheelScrollMultiplier](react_umg.ListViewProps.md#wheelscrollmultiplier)
- [bCanChildrenBeAccessible](react_umg.ListViewProps.md#bcanchildrenbeaccessible)
- [bClearSelectionOnClick](react_umg.ListViewProps.md#bclearselectiononclick)
- [bCreatedByConstructionScript](react_umg.ListViewProps.md#bcreatedbyconstructionscript)
- [bEnableFixedLineOffset](react_umg.ListViewProps.md#benablefixedlineoffset)
- [bEnableScrollAnimation](react_umg.ListViewProps.md#benablescrollanimation)
- [bExpandedInDesigner](react_umg.ListViewProps.md#bexpandedindesigner)
- [bHiddenInDesigner](react_umg.ListViewProps.md#bhiddenindesigner)
- [bIsEnabled](react_umg.ListViewProps.md#bisenabled)
- [bIsEnabledDelegate](react_umg.ListViewProps.md#bisenableddelegate)
- [bIsFocusable](react_umg.ListViewProps.md#bisfocusable)
- [bIsVariable](react_umg.ListViewProps.md#bisvariable)
- [bIsVolatile](react_umg.ListViewProps.md#bisvolatile)
- [bLockedInDesigner](react_umg.ListViewProps.md#blockedindesigner)
- [bOverrideAccessibleDefaults](react_umg.ListViewProps.md#boverrideaccessibledefaults)
- [bOverride\_Cursor](react_umg.ListViewProps.md#boverride_cursor)
- [bReturnFocusToSelection](react_umg.ListViewProps.md#breturnfocustoselection)

## Properties

### AccessibleBehavior

• `Optional` **AccessibleBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[AccessibleBehavior](react_umg.ListViewBaseProps.md#accessiblebehavior)

#### Defined in

[react-umg/index.d.ts:145](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L145)

___

### AccessibleSummaryBehavior

• `Optional` **AccessibleSummaryBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[AccessibleSummaryBehavior](react_umg.ListViewBaseProps.md#accessiblesummarybehavior)

#### Defined in

[react-umg/index.d.ts:146](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L146)

___

### AccessibleSummaryText

• `Optional` **AccessibleSummaryText**: `string`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[AccessibleSummaryText](react_umg.ListViewBaseProps.md#accessiblesummarytext)

#### Defined in

[react-umg/index.d.ts:149](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L149)

___

### AccessibleSummaryTextDelegate

• `Optional` **AccessibleSummaryTextDelegate**: () => `string`

#### Type declaration

▸ (): `string`

##### Returns

`string`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[AccessibleSummaryTextDelegate](react_umg.ListViewBaseProps.md#accessiblesummarytextdelegate)

#### Defined in

[react-umg/index.d.ts:150](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L150)

___

### AccessibleText

• `Optional` **AccessibleText**: `string`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[AccessibleText](react_umg.ListViewBaseProps.md#accessibletext)

#### Defined in

[react-umg/index.d.ts:147](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L147)

___

### AccessibleTextDelegate

• `Optional` **AccessibleTextDelegate**: () => `string`

#### Type declaration

▸ (): `string`

##### Returns

`string`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[AccessibleTextDelegate](react_umg.ListViewBaseProps.md#accessibletextdelegate)

#### Defined in

[react-umg/index.d.ts:148](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L148)

___

### CategoryName

• `Optional` **CategoryName**: `string`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[CategoryName](react_umg.ListViewBaseProps.md#categoryname)

#### Defined in

[react-umg/index.d.ts:162](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L162)

___

### Clipping

• `Optional` **Clipping**: [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[Clipping](react_umg.ListViewBaseProps.md#clipping)

#### Defined in

[react-umg/index.d.ts:156](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L156)

___

### ConsumeMouseWheel

• `Optional` **ConsumeMouseWheel**: [`EConsumeMouseWheel`](../enums/ue_ue.EConsumeMouseWheel.md)

#### Defined in

[react-umg/index.d.ts:508](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L508)

___

### Cursor

• `Optional` **Cursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[Cursor](react_umg.ListViewBaseProps.md#cursor)

#### Defined in

[react-umg/index.d.ts:155](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L155)

___

### DesignerFlags

• `Optional` **DesignerFlags**: `number`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[DesignerFlags](react_umg.ListViewBaseProps.md#designerflags)

#### Defined in

[react-umg/index.d.ts:160](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L160)

___

### DisplayLabel

• `Optional` **DisplayLabel**: `string`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[DisplayLabel](react_umg.ListViewBaseProps.md#displaylabel)

#### Defined in

[react-umg/index.d.ts:161](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L161)

___

### EntrySpacing

• `Optional` **EntrySpacing**: `number`

#### Defined in

[react-umg/index.d.ts:511](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L511)

___

### EntryWidgetPool

• `Optional` **EntryWidgetPool**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`UserWidgetPool`](../classes/ue_ue.UserWidgetPool.md)\>

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[EntryWidgetPool](react_umg.ListViewBaseProps.md#entrywidgetpool)

#### Defined in

[react-umg/index.d.ts:498](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L498)

___

### FixedLineScrollOffset

• `Optional` **FixedLineScrollOffset**: `number`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[FixedLineScrollOffset](react_umg.ListViewBaseProps.md#fixedlinescrolloffset)

#### Defined in

[react-umg/index.d.ts:496](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L496)

___

### FlowDirectionPreference

• `Optional` **FlowDirectionPreference**: [`EFlowDirectionPreference`](../enums/ue_ue.EFlowDirectionPreference.md)

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[FlowDirectionPreference](react_umg.ListViewBaseProps.md#flowdirectionpreference)

#### Defined in

[react-umg/index.d.ts:159](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L159)

___

### NumDesignerPreviewEntries

• `Optional` **NumDesignerPreviewEntries**: `number`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[NumDesignerPreviewEntries](react_umg.ListViewBaseProps.md#numdesignerpreviewentries)

#### Defined in

[react-umg/index.d.ts:497](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L497)

___

### Orientation

• `Optional` **Orientation**: [`EOrientation`](../enums/ue_ue.EOrientation.md)

#### Defined in

[react-umg/index.d.ts:506](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L506)

___

### RenderOpacity

• `Optional` **RenderOpacity**: `number`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[RenderOpacity](react_umg.ListViewBaseProps.md#renderopacity)

#### Defined in

[react-umg/index.d.ts:158](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L158)

___

### RenderTransform

• `Optional` **RenderTransform**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`WidgetTransform`](../classes/ue_ue.WidgetTransform.md)\>

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[RenderTransform](react_umg.ListViewBaseProps.md#rendertransform)

#### Defined in

[react-umg/index.d.ts:137](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L137)

___

### RenderTransformPivot

• `Optional` **RenderTransformPivot**: [`RecursivePartial`](../modules/react_umg.md#recursivepartial)<[`Vector2D`](../classes/ue_ue_s.Vector2D.md)\>

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[RenderTransformPivot](react_umg.ListViewBaseProps.md#rendertransformpivot)

#### Defined in

[react-umg/index.d.ts:138](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L138)

___

### SelectionMode

• `Optional` **SelectionMode**: [`ESelectionMode`](../enums/ue_ue.ESelectionMode.md)

#### Defined in

[react-umg/index.d.ts:507](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L507)

___

### Slot

• `Optional` **Slot**: [`PanelSlot`](react_umg.PanelSlot.md)

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[Slot](react_umg.ListViewBaseProps.md#slot)

#### Defined in

[react-umg/index.d.ts:129](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L129)

___

### ToolTipText

• `Optional` **ToolTipText**: `string`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[ToolTipText](react_umg.ListViewBaseProps.md#tooltiptext)

#### Defined in

[react-umg/index.d.ts:134](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L134)

___

### ToolTipTextDelegate

• `Optional` **ToolTipTextDelegate**: () => `string`

#### Type declaration

▸ (): `string`

##### Returns

`string`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[ToolTipTextDelegate](react_umg.ListViewBaseProps.md#tooltiptextdelegate)

#### Defined in

[react-umg/index.d.ts:135](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L135)

___

### Visibility

• `Optional` **Visibility**: [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[Visibility](react_umg.ListViewBaseProps.md#visibility)

#### Defined in

[react-umg/index.d.ts:157](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L157)

___

### VisibilityDelegate

• `Optional` **VisibilityDelegate**: () => [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Type declaration

▸ (): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

##### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[VisibilityDelegate](react_umg.ListViewBaseProps.md#visibilitydelegate)

#### Defined in

[react-umg/index.d.ts:136](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L136)

___

### WheelScrollMultiplier

• `Optional` **WheelScrollMultiplier**: `number`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[WheelScrollMultiplier](react_umg.ListViewBaseProps.md#wheelscrollmultiplier)

#### Defined in

[react-umg/index.d.ts:493](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L493)

___

### bCanChildrenBeAccessible

• `Optional` **bCanChildrenBeAccessible**: `boolean`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[bCanChildrenBeAccessible](react_umg.ListViewBaseProps.md#bcanchildrenbeaccessible)

#### Defined in

[react-umg/index.d.ts:144](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L144)

___

### bClearSelectionOnClick

• `Optional` **bClearSelectionOnClick**: `boolean`

#### Defined in

[react-umg/index.d.ts:509](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L509)

___

### bCreatedByConstructionScript

• `Optional` **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[bCreatedByConstructionScript](react_umg.ListViewBaseProps.md#bcreatedbyconstructionscript)

#### Defined in

[react-umg/index.d.ts:140](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L140)

___

### bEnableFixedLineOffset

• `Optional` **bEnableFixedLineOffset**: `boolean`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[bEnableFixedLineOffset](react_umg.ListViewBaseProps.md#benablefixedlineoffset)

#### Defined in

[react-umg/index.d.ts:495](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L495)

___

### bEnableScrollAnimation

• `Optional` **bEnableScrollAnimation**: `boolean`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[bEnableScrollAnimation](react_umg.ListViewBaseProps.md#benablescrollanimation)

#### Defined in

[react-umg/index.d.ts:494](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L494)

___

### bExpandedInDesigner

• `Optional` **bExpandedInDesigner**: `boolean`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[bExpandedInDesigner](react_umg.ListViewBaseProps.md#bexpandedindesigner)

#### Defined in

[react-umg/index.d.ts:153](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L153)

___

### bHiddenInDesigner

• `Optional` **bHiddenInDesigner**: `boolean`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[bHiddenInDesigner](react_umg.ListViewBaseProps.md#bhiddenindesigner)

#### Defined in

[react-umg/index.d.ts:152](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L152)

___

### bIsEnabled

• `Optional` **bIsEnabled**: `boolean`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[bIsEnabled](react_umg.ListViewBaseProps.md#bisenabled)

#### Defined in

[react-umg/index.d.ts:141](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L141)

___

### bIsEnabledDelegate

• `Optional` **bIsEnabledDelegate**: () => `boolean`

#### Type declaration

▸ (): `boolean`

##### Returns

`boolean`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[bIsEnabledDelegate](react_umg.ListViewBaseProps.md#bisenableddelegate)

#### Defined in

[react-umg/index.d.ts:133](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L133)

___

### bIsFocusable

• `Optional` **bIsFocusable**: `boolean`

#### Defined in

[react-umg/index.d.ts:510](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L510)

___

### bIsVariable

• `Optional` **bIsVariable**: `boolean`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[bIsVariable](react_umg.ListViewBaseProps.md#bisvariable)

#### Defined in

[react-umg/index.d.ts:139](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L139)

___

### bIsVolatile

• `Optional` **bIsVolatile**: `boolean`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[bIsVolatile](react_umg.ListViewBaseProps.md#bisvolatile)

#### Defined in

[react-umg/index.d.ts:151](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L151)

___

### bLockedInDesigner

• `Optional` **bLockedInDesigner**: `boolean`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[bLockedInDesigner](react_umg.ListViewBaseProps.md#blockedindesigner)

#### Defined in

[react-umg/index.d.ts:154](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L154)

___

### bOverrideAccessibleDefaults

• `Optional` **bOverrideAccessibleDefaults**: `boolean`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[bOverrideAccessibleDefaults](react_umg.ListViewBaseProps.md#boverrideaccessibledefaults)

#### Defined in

[react-umg/index.d.ts:143](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L143)

___

### bOverride\_Cursor

• `Optional` **bOverride\_Cursor**: `boolean`

#### Inherited from

[ListViewBaseProps](react_umg.ListViewBaseProps.md).[bOverride_Cursor](react_umg.ListViewBaseProps.md#boverride_cursor)

#### Defined in

[react-umg/index.d.ts:142](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L142)

___

### bReturnFocusToSelection

• `Optional` **bReturnFocusToSelection**: `boolean`

#### Defined in

[react-umg/index.d.ts:512](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L512)
