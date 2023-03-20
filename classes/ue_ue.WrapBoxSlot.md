[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / WrapBoxSlot

# Class: WrapBoxSlot

[ue/ue](../modules/ue_ue.md).WrapBoxSlot

## Hierarchy

- [`PanelSlot`](ue_ue.PanelSlot.md)

  ↳ **`WrapBoxSlot`**

## Table of contents

### Constructors

- [constructor](ue_ue.WrapBoxSlot.md#constructor)

### Properties

- [Content](ue_ue.WrapBoxSlot.md#content)
- [FillSpanWhenLessThan](ue_ue.WrapBoxSlot.md#fillspanwhenlessthan)
- [HorizontalAlignment](ue_ue.WrapBoxSlot.md#horizontalalignment)
- [Padding](ue_ue.WrapBoxSlot.md#padding)
- [Parent](ue_ue.WrapBoxSlot.md#parent)
- [VerticalAlignment](ue_ue.WrapBoxSlot.md#verticalalignment)
- [\_\_tid\_Object\_\_](ue_ue.WrapBoxSlot.md#__tid_object__)
- [\_\_tid\_PanelSlot\_\_](ue_ue.WrapBoxSlot.md#__tid_panelslot__)
- [\_\_tid\_Visual\_\_](ue_ue.WrapBoxSlot.md#__tid_visual__)
- [\_\_tid\_WrapBoxSlot\_\_](ue_ue.WrapBoxSlot.md#__tid_wrapboxslot__)
- [bFillEmptySpace](ue_ue.WrapBoxSlot.md#bfillemptyspace)

### Methods

- [CreateDefaultSubobject](ue_ue.WrapBoxSlot.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.WrapBoxSlot.md#executeubergraph)
- [GetClass](ue_ue.WrapBoxSlot.md#getclass)
- [GetName](ue_ue.WrapBoxSlot.md#getname)
- [GetOuter](ue_ue.WrapBoxSlot.md#getouter)
- [GetWorld](ue_ue.WrapBoxSlot.md#getworld)
- [SetFillEmptySpace](ue_ue.WrapBoxSlot.md#setfillemptyspace)
- [SetFillSpanWhenLessThan](ue_ue.WrapBoxSlot.md#setfillspanwhenlessthan)
- [SetHorizontalAlignment](ue_ue.WrapBoxSlot.md#sethorizontalalignment)
- [SetPadding](ue_ue.WrapBoxSlot.md#setpadding)
- [SetVerticalAlignment](ue_ue.WrapBoxSlot.md#setverticalalignment)
- [Find](ue_ue.WrapBoxSlot.md#find)
- [Load](ue_ue.WrapBoxSlot.md#load)
- [StaticClass](ue_ue.WrapBoxSlot.md#staticclass)

## Constructors

### constructor

• **new WrapBoxSlot**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PanelSlot](ue_ue.PanelSlot.md).[constructor](ue_ue.PanelSlot.md#constructor)

#### Defined in

[ue/ue.d.ts:66336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66336)

## Properties

### Content

• **Content**: [`Widget`](ue_ue.Widget.md)

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[Content](ue_ue.PanelSlot.md#content)

#### Defined in

[ue/ue.d.ts:10699](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10699)

___

### FillSpanWhenLessThan

• **FillSpanWhenLessThan**: `number`

#### Defined in

[ue/ue.d.ts:66339](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66339)

___

### HorizontalAlignment

• **HorizontalAlignment**: [`EHorizontalAlignment`](../enums/ue_ue.EHorizontalAlignment.md)

#### Defined in

[ue/ue.d.ts:66340](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66340)

___

### Padding

• **Padding**: [`Margin`](ue_ue.Margin.md)

#### Defined in

[ue/ue.d.ts:66337](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66337)

___

### Parent

• **Parent**: [`PanelWidget`](ue_ue.PanelWidget.md)

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[Parent](ue_ue.PanelSlot.md#parent)

#### Defined in

[ue/ue.d.ts:10698](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10698)

___

### VerticalAlignment

• **VerticalAlignment**: [`EVerticalAlignment`](../enums/ue_ue.EVerticalAlignment.md)

#### Defined in

[ue/ue.d.ts:66341](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66341)

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

___

### \_\_tid\_WrapBoxSlot\_\_

• **\_\_tid\_WrapBoxSlot\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:66351](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66351)

___

### bFillEmptySpace

• **bFillEmptySpace**: `boolean`

#### Defined in

[ue/ue.d.ts:66338](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66338)

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

### SetFillEmptySpace

▸ **SetFillEmptySpace**(`InbFillEmptySpace`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InbFillEmptySpace` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:66342](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66342)

___

### SetFillSpanWhenLessThan

▸ **SetFillSpanWhenLessThan**(`InFillSpanWhenLessThan`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFillSpanWhenLessThan` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:66343](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66343)

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

[ue/ue.d.ts:66344](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66344)

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

[ue/ue.d.ts:66345](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66345)

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

[ue/ue.d.ts:66346](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66346)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`WrapBoxSlot`](ue_ue.WrapBoxSlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`WrapBoxSlot`](ue_ue.WrapBoxSlot.md)

#### Overrides

[PanelSlot](ue_ue.PanelSlot.md).[Find](ue_ue.PanelSlot.md#find)

#### Defined in

[ue/ue.d.ts:66348](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66348)

___

### Load

▸ `Static` **Load**(`InName`): [`WrapBoxSlot`](ue_ue.WrapBoxSlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`WrapBoxSlot`](ue_ue.WrapBoxSlot.md)

#### Overrides

[PanelSlot](ue_ue.PanelSlot.md).[Load](ue_ue.PanelSlot.md#load)

#### Defined in

[ue/ue.d.ts:66349](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66349)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PanelSlot](ue_ue.PanelSlot.md).[StaticClass](ue_ue.PanelSlot.md#staticclass)

#### Defined in

[ue/ue.d.ts:66347](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66347)
