[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GridSlot

# Class: GridSlot

[ue/ue](../modules/ue_ue.md).GridSlot

## Hierarchy

- [`PanelSlot`](ue_ue.PanelSlot.md)

  ↳ **`GridSlot`**

## Table of contents

### Constructors

- [constructor](ue_ue.GridSlot.md#constructor)

### Properties

- [Column](ue_ue.GridSlot.md#column)
- [ColumnSpan](ue_ue.GridSlot.md#columnspan)
- [Content](ue_ue.GridSlot.md#content)
- [HorizontalAlignment](ue_ue.GridSlot.md#horizontalalignment)
- [Layer](ue_ue.GridSlot.md#layer)
- [Nudge](ue_ue.GridSlot.md#nudge)
- [Padding](ue_ue.GridSlot.md#padding)
- [Parent](ue_ue.GridSlot.md#parent)
- [Row](ue_ue.GridSlot.md#row)
- [RowSpan](ue_ue.GridSlot.md#rowspan)
- [VerticalAlignment](ue_ue.GridSlot.md#verticalalignment)
- [\_\_tid\_GridSlot\_\_](ue_ue.GridSlot.md#__tid_gridslot__)
- [\_\_tid\_Object\_\_](ue_ue.GridSlot.md#__tid_object__)
- [\_\_tid\_PanelSlot\_\_](ue_ue.GridSlot.md#__tid_panelslot__)
- [\_\_tid\_Visual\_\_](ue_ue.GridSlot.md#__tid_visual__)

### Methods

- [CreateDefaultSubobject](ue_ue.GridSlot.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GridSlot.md#executeubergraph)
- [GetClass](ue_ue.GridSlot.md#getclass)
- [GetName](ue_ue.GridSlot.md#getname)
- [GetOuter](ue_ue.GridSlot.md#getouter)
- [GetWorld](ue_ue.GridSlot.md#getworld)
- [SetColumn](ue_ue.GridSlot.md#setcolumn)
- [SetColumnSpan](ue_ue.GridSlot.md#setcolumnspan)
- [SetHorizontalAlignment](ue_ue.GridSlot.md#sethorizontalalignment)
- [SetLayer](ue_ue.GridSlot.md#setlayer)
- [SetNudge](ue_ue.GridSlot.md#setnudge)
- [SetPadding](ue_ue.GridSlot.md#setpadding)
- [SetRow](ue_ue.GridSlot.md#setrow)
- [SetRowSpan](ue_ue.GridSlot.md#setrowspan)
- [SetVerticalAlignment](ue_ue.GridSlot.md#setverticalalignment)
- [Find](ue_ue.GridSlot.md#find)
- [Load](ue_ue.GridSlot.md#load)
- [StaticClass](ue_ue.GridSlot.md#staticclass)

## Constructors

### constructor

• **new GridSlot**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PanelSlot](ue_ue.PanelSlot.md).[constructor](ue_ue.PanelSlot.md#constructor)

#### Defined in

[ue/ue.d.ts:38347](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38347)

## Properties

### Column

• **Column**: `number`

#### Defined in

[ue/ue.d.ts:38353](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38353)

___

### ColumnSpan

• **ColumnSpan**: `number`

#### Defined in

[ue/ue.d.ts:38354](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38354)

___

### Content

• **Content**: [`Widget`](ue_ue.Widget.md)

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[Content](ue_ue.PanelSlot.md#content)

#### Defined in

[ue/ue.d.ts:10699](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10699)

___

### HorizontalAlignment

• **HorizontalAlignment**: [`EHorizontalAlignment`](../enums/ue_ue.EHorizontalAlignment.md)

#### Defined in

[ue/ue.d.ts:38349](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38349)

___

### Layer

• **Layer**: `number`

#### Defined in

[ue/ue.d.ts:38355](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38355)

___

### Nudge

• **Nudge**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:38356](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38356)

___

### Padding

• **Padding**: [`Margin`](ue_ue.Margin.md)

#### Defined in

[ue/ue.d.ts:38348](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38348)

___

### Parent

• **Parent**: [`PanelWidget`](ue_ue.PanelWidget.md)

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[Parent](ue_ue.PanelSlot.md#parent)

#### Defined in

[ue/ue.d.ts:10698](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10698)

___

### Row

• **Row**: `number`

#### Defined in

[ue/ue.d.ts:38351](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38351)

___

### RowSpan

• **RowSpan**: `number`

#### Defined in

[ue/ue.d.ts:38352](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38352)

___

### VerticalAlignment

• **VerticalAlignment**: [`EVerticalAlignment`](../enums/ue_ue.EVerticalAlignment.md)

#### Defined in

[ue/ue.d.ts:38350](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38350)

___

### \_\_tid\_GridSlot\_\_

• **\_\_tid\_GridSlot\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:38370](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38370)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[__tid_Object__](ue_ue.PanelSlot.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_PanelSlot\_\_

• **\_\_tid\_PanelSlot\_\_**: `boolean`

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[__tid_PanelSlot__](ue_ue.PanelSlot.md#__tid_panelslot__)

#### Defined in

[ue/ue.d.ts:10704](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10704)

___

### \_\_tid\_Visual\_\_

• **\_\_tid\_Visual\_\_**: `boolean`

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[__tid_Visual__](ue_ue.PanelSlot.md#__tid_visual__)

#### Defined in

[ue/ue.d.ts:10673](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10673)

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

[PanelSlot](ue_ue.PanelSlot.md).[CreateDefaultSubobject](ue_ue.PanelSlot.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

[PanelSlot](ue_ue.PanelSlot.md).[ExecuteUbergraph](ue_ue.PanelSlot.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[GetClass](ue_ue.PanelSlot.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[GetName](ue_ue.PanelSlot.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[GetOuter](ue_ue.PanelSlot.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[GetWorld](ue_ue.PanelSlot.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### SetColumn

▸ **SetColumn**(`InColumn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InColumn` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38357](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38357)

___

### SetColumnSpan

▸ **SetColumnSpan**(`InColumnSpan`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InColumnSpan` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38358](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38358)

___

### SetHorizontalAlignment

▸ **SetHorizontalAlignment**(`InHorizontalAlignment`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InHorizontalAlignment` | [`EHorizontalAlignment`](../enums/ue_ue.EHorizontalAlignment.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38359](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38359)

___

### SetLayer

▸ **SetLayer**(`InLayer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLayer` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38360](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38360)

___

### SetNudge

▸ **SetNudge**(`InNudge`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InNudge` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38361](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38361)

___

### SetPadding

▸ **SetPadding**(`InPadding`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPadding` | [`Margin`](ue_ue.Margin.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38362](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38362)

___

### SetRow

▸ **SetRow**(`InRow`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRow` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38363](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38363)

___

### SetRowSpan

▸ **SetRowSpan**(`InRowSpan`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRowSpan` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38364](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38364)

___

### SetVerticalAlignment

▸ **SetVerticalAlignment**(`InVerticalAlignment`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InVerticalAlignment` | [`EVerticalAlignment`](../enums/ue_ue.EVerticalAlignment.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38365](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38365)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GridSlot`](ue_ue.GridSlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GridSlot`](ue_ue.GridSlot.md)

#### Overrides

[PanelSlot](ue_ue.PanelSlot.md).[Find](ue_ue.PanelSlot.md#find)

#### Defined in

[ue/ue.d.ts:38367](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38367)

___

### Load

▸ `Static` **Load**(`InName`): [`GridSlot`](ue_ue.GridSlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GridSlot`](ue_ue.GridSlot.md)

#### Overrides

[PanelSlot](ue_ue.PanelSlot.md).[Load](ue_ue.PanelSlot.md#load)

#### Defined in

[ue/ue.d.ts:38368](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38368)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PanelSlot](ue_ue.PanelSlot.md).[StaticClass](ue_ue.PanelSlot.md#staticclass)

#### Defined in

[ue/ue.d.ts:38366](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38366)
