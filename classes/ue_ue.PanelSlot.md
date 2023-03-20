[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PanelSlot

# Class: PanelSlot

[ue/ue](../modules/ue_ue.md).PanelSlot

## Hierarchy

- [`Visual`](ue_ue.Visual.md)

  ↳ **`PanelSlot`**

  ↳↳ [`BackgroundBlurSlot`](ue_ue.BackgroundBlurSlot.md)

  ↳↳ [`BorderSlot`](ue_ue.BorderSlot.md)

  ↳↳ [`ButtonSlot`](ue_ue.ButtonSlot.md)

  ↳↳ [`CanvasPanelSlot`](ue_ue.CanvasPanelSlot.md)

  ↳↳ [`GridSlot`](ue_ue.GridSlot.md)

  ↳↳ [`HorizontalBoxSlot`](ue_ue.HorizontalBoxSlot.md)

  ↳↳ [`OverlaySlot`](ue_ue.OverlaySlot.md)

  ↳↳ [`SafeZoneSlot`](ue_ue.SafeZoneSlot.md)

  ↳↳ [`ScaleBoxSlot`](ue_ue.ScaleBoxSlot.md)

  ↳↳ [`ScrollBoxSlot`](ue_ue.ScrollBoxSlot.md)

  ↳↳ [`SizeBoxSlot`](ue_ue.SizeBoxSlot.md)

  ↳↳ [`UniformGridSlot`](ue_ue.UniformGridSlot.md)

  ↳↳ [`VerticalBoxSlot`](ue_ue.VerticalBoxSlot.md)

  ↳↳ [`WrapBoxSlot`](ue_ue.WrapBoxSlot.md)

  ↳↳ [`WidgetSwitcherSlot`](ue_ue.WidgetSwitcherSlot.md)

  ↳↳ [`WindowTitleBarAreaSlot`](ue_ue.WindowTitleBarAreaSlot.md)

## Table of contents

### Constructors

- [constructor](ue_ue.PanelSlot.md#constructor)

### Properties

- [Content](ue_ue.PanelSlot.md#content)
- [Parent](ue_ue.PanelSlot.md#parent)
- [\_\_tid\_Object\_\_](ue_ue.PanelSlot.md#__tid_object__)
- [\_\_tid\_PanelSlot\_\_](ue_ue.PanelSlot.md#__tid_panelslot__)
- [\_\_tid\_Visual\_\_](ue_ue.PanelSlot.md#__tid_visual__)

### Methods

- [CreateDefaultSubobject](ue_ue.PanelSlot.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PanelSlot.md#executeubergraph)
- [GetClass](ue_ue.PanelSlot.md#getclass)
- [GetName](ue_ue.PanelSlot.md#getname)
- [GetOuter](ue_ue.PanelSlot.md#getouter)
- [GetWorld](ue_ue.PanelSlot.md#getworld)
- [Find](ue_ue.PanelSlot.md#find)
- [Load](ue_ue.PanelSlot.md#load)
- [StaticClass](ue_ue.PanelSlot.md#staticclass)

## Constructors

### constructor

• **new PanelSlot**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Visual](ue_ue.Visual.md).[constructor](ue_ue.Visual.md#constructor)

#### Defined in

[ue/ue.d.ts:10697](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10697)

## Properties

### Content

• **Content**: [`Widget`](ue_ue.Widget.md)

#### Defined in

[ue/ue.d.ts:10699](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10699)

___

### Parent

• **Parent**: [`PanelWidget`](ue_ue.PanelWidget.md)

#### Defined in

[ue/ue.d.ts:10698](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10698)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Visual](ue_ue.Visual.md).[__tid_Object__](ue_ue.Visual.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PanelSlot\_\_

• **\_\_tid\_PanelSlot\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:10704](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10704)

___

### \_\_tid\_Visual\_\_

• **\_\_tid\_Visual\_\_**: `boolean`

#### Inherited from

[Visual](ue_ue.Visual.md).[__tid_Visual__](ue_ue.Visual.md#__tid_visual__)

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

[Visual](ue_ue.Visual.md).[CreateDefaultSubobject](ue_ue.Visual.md#createdefaultsubobject)

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

[Visual](ue_ue.Visual.md).[ExecuteUbergraph](ue_ue.Visual.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Visual](ue_ue.Visual.md).[GetClass](ue_ue.Visual.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Visual](ue_ue.Visual.md).[GetName](ue_ue.Visual.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Visual](ue_ue.Visual.md).[GetOuter](ue_ue.Visual.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Visual](ue_ue.Visual.md).[GetWorld](ue_ue.Visual.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PanelSlot`](ue_ue.PanelSlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PanelSlot`](ue_ue.PanelSlot.md)

#### Overrides

[Visual](ue_ue.Visual.md).[Find](ue_ue.Visual.md#find)

#### Defined in

[ue/ue.d.ts:10701](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10701)

___

### Load

▸ `Static` **Load**(`InName`): [`PanelSlot`](ue_ue.PanelSlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PanelSlot`](ue_ue.PanelSlot.md)

#### Overrides

[Visual](ue_ue.Visual.md).[Load](ue_ue.Visual.md#load)

#### Defined in

[ue/ue.d.ts:10702](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10702)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Visual](ue_ue.Visual.md).[StaticClass](ue_ue.Visual.md#staticclass)

#### Defined in

[ue/ue.d.ts:10700](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10700)
