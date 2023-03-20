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

## Properties

### Column

• **Column**: `number`

___

### ColumnSpan

• **ColumnSpan**: `number`

___

### Content

• **Content**: [`Widget`](ue_ue.Widget.md)

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[Content](ue_ue.PanelSlot.md#content)

___

### HorizontalAlignment

• **HorizontalAlignment**: [`EHorizontalAlignment`](../enums/ue_ue.EHorizontalAlignment.md)

___

### Layer

• **Layer**: `number`

___

### Nudge

• **Nudge**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### Padding

• **Padding**: [`Margin`](ue_ue.Margin.md)

___

### Parent

• **Parent**: [`PanelWidget`](ue_ue.PanelWidget.md)

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[Parent](ue_ue.PanelSlot.md#parent)

___

### Row

• **Row**: `number`

___

### RowSpan

• **RowSpan**: `number`

___

### VerticalAlignment

• **VerticalAlignment**: [`EVerticalAlignment`](../enums/ue_ue.EVerticalAlignment.md)

___

### \_\_tid\_GridSlot\_\_

• **\_\_tid\_GridSlot\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[__tid_Object__](ue_ue.PanelSlot.md#__tid_object__)

___

### \_\_tid\_PanelSlot\_\_

• **\_\_tid\_PanelSlot\_\_**: `boolean`

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[__tid_PanelSlot__](ue_ue.PanelSlot.md#__tid_panelslot__)

___

### \_\_tid\_Visual\_\_

• **\_\_tid\_Visual\_\_**: `boolean`

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[__tid_Visual__](ue_ue.PanelSlot.md#__tid_visual__)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[GetClass](ue_ue.PanelSlot.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[GetName](ue_ue.PanelSlot.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[GetOuter](ue_ue.PanelSlot.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[GetWorld](ue_ue.PanelSlot.md#getworld)

___

### SetColumn

▸ **SetColumn**(`InColumn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InColumn` | `number` |

#### Returns

`void`

___

### SetColumnSpan

▸ **SetColumnSpan**(`InColumnSpan`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InColumnSpan` | `number` |

#### Returns

`void`

___

### SetHorizontalAlignment

▸ **SetHorizontalAlignment**(`InHorizontalAlignment`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InHorizontalAlignment` | [`EHorizontalAlignment`](../enums/ue_ue.EHorizontalAlignment.md) |

#### Returns

`void`

___

### SetLayer

▸ **SetLayer**(`InLayer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLayer` | `number` |

#### Returns

`void`

___

### SetNudge

▸ **SetNudge**(`InNudge`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InNudge` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

___

### SetPadding

▸ **SetPadding**(`InPadding`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPadding` | [`Margin`](ue_ue.Margin.md) |

#### Returns

`void`

___

### SetRow

▸ **SetRow**(`InRow`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRow` | `number` |

#### Returns

`void`

___

### SetRowSpan

▸ **SetRowSpan**(`InRowSpan`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRowSpan` | `number` |

#### Returns

`void`

___

### SetVerticalAlignment

▸ **SetVerticalAlignment**(`InVerticalAlignment`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InVerticalAlignment` | [`EVerticalAlignment`](../enums/ue_ue.EVerticalAlignment.md) |

#### Returns

`void`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PanelSlot](ue_ue.PanelSlot.md).[StaticClass](ue_ue.PanelSlot.md#staticclass)
