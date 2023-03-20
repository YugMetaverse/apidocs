[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / OverlaySlot

# Class: OverlaySlot

[ue/ue](../modules/ue_ue.md).OverlaySlot

## Hierarchy

- [`PanelSlot`](ue_ue.PanelSlot.md)

  ↳ **`OverlaySlot`**

## Table of contents

### Constructors

- [constructor](ue_ue.OverlaySlot.md#constructor)

### Properties

- [Content](ue_ue.OverlaySlot.md#content)
- [HorizontalAlignment](ue_ue.OverlaySlot.md#horizontalalignment)
- [Padding](ue_ue.OverlaySlot.md#padding)
- [Parent](ue_ue.OverlaySlot.md#parent)
- [VerticalAlignment](ue_ue.OverlaySlot.md#verticalalignment)
- [\_\_tid\_Object\_\_](ue_ue.OverlaySlot.md#__tid_object__)
- [\_\_tid\_OverlaySlot\_\_](ue_ue.OverlaySlot.md#__tid_overlayslot__)
- [\_\_tid\_PanelSlot\_\_](ue_ue.OverlaySlot.md#__tid_panelslot__)
- [\_\_tid\_Visual\_\_](ue_ue.OverlaySlot.md#__tid_visual__)

### Methods

- [CreateDefaultSubobject](ue_ue.OverlaySlot.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.OverlaySlot.md#executeubergraph)
- [GetClass](ue_ue.OverlaySlot.md#getclass)
- [GetName](ue_ue.OverlaySlot.md#getname)
- [GetOuter](ue_ue.OverlaySlot.md#getouter)
- [GetWorld](ue_ue.OverlaySlot.md#getworld)
- [SetHorizontalAlignment](ue_ue.OverlaySlot.md#sethorizontalalignment)
- [SetPadding](ue_ue.OverlaySlot.md#setpadding)
- [SetVerticalAlignment](ue_ue.OverlaySlot.md#setverticalalignment)
- [Find](ue_ue.OverlaySlot.md#find)
- [Load](ue_ue.OverlaySlot.md#load)
- [StaticClass](ue_ue.OverlaySlot.md#staticclass)

## Constructors

### constructor

• **new OverlaySlot**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PanelSlot](ue_ue.PanelSlot.md).[constructor](ue_ue.PanelSlot.md#constructor)

#### Defined in

[ue/ue.d.ts:54289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54289)

## Properties

### Content

• **Content**: [`Widget`](ue_ue.Widget.md)

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[Content](ue_ue.PanelSlot.md#content)

#### Defined in

[ue/ue.d.ts:10699](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10699)

___

### HorizontalAlignment

• **HorizontalAlignment**: [`EHorizontalAlignment`](../enums/ue_ue.EHorizontalAlignment.md)

#### Defined in

[ue/ue.d.ts:54291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54291)

___

### Padding

• **Padding**: [`Margin`](ue_ue.Margin.md)

#### Defined in

[ue/ue.d.ts:54290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54290)

___

### Parent

• **Parent**: [`PanelWidget`](ue_ue.PanelWidget.md)

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[Parent](ue_ue.PanelSlot.md#parent)

#### Defined in

[ue/ue.d.ts:10698](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10698)

___

### VerticalAlignment

• **VerticalAlignment**: [`EVerticalAlignment`](../enums/ue_ue.EVerticalAlignment.md)

#### Defined in

[ue/ue.d.ts:54292](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54292)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[__tid_Object__](ue_ue.PanelSlot.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_OverlaySlot\_\_

• **\_\_tid\_OverlaySlot\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:54300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54300)

___

### \_\_tid\_PanelSlot\_\_

• **\_\_tid\_PanelSlot\_\_**: `boolean`

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[__tid_PanelSlot__](ue_ue.PanelSlot.md#__tid_panelslot__)

#### Defined in

[ue/ue.d.ts:10704](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10704)

___

### \_\_tid\_Visual\_\_

• **\_\_tid\_Visual\_\_**: `boolean`

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[__tid_Visual__](ue_ue.PanelSlot.md#__tid_visual__)

#### Defined in

[ue/ue.d.ts:10673](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10673)

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

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[GetClass](ue_ue.PanelSlot.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[GetName](ue_ue.PanelSlot.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[GetOuter](ue_ue.PanelSlot.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PanelSlot](ue_ue.PanelSlot.md).[GetWorld](ue_ue.PanelSlot.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

[ue/ue.d.ts:54293](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54293)

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

[ue/ue.d.ts:54294](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54294)

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

[ue/ue.d.ts:54295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54295)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`OverlaySlot`](ue_ue.OverlaySlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`OverlaySlot`](ue_ue.OverlaySlot.md)

#### Overrides

[PanelSlot](ue_ue.PanelSlot.md).[Find](ue_ue.PanelSlot.md#find)

#### Defined in

[ue/ue.d.ts:54297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54297)

___

### Load

▸ `Static` **Load**(`InName`): [`OverlaySlot`](ue_ue.OverlaySlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`OverlaySlot`](ue_ue.OverlaySlot.md)

#### Overrides

[PanelSlot](ue_ue.PanelSlot.md).[Load](ue_ue.PanelSlot.md#load)

#### Defined in

[ue/ue.d.ts:54298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54298)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PanelSlot](ue_ue.PanelSlot.md).[StaticClass](ue_ue.PanelSlot.md#staticclass)

#### Defined in

[ue/ue.d.ts:54296](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54296)