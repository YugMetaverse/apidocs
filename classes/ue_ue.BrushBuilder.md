[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BrushBuilder

# Class: BrushBuilder

[ue/ue](../modules/ue_ue.md).BrushBuilder

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`BrushBuilder`**

  ↳↳ [`EditorBrushBuilder`](ue_ue.EditorBrushBuilder.md)

## Table of contents

### Constructors

- [constructor](ue_ue.BrushBuilder.md#constructor)

### Properties

- [BitmapFilename](ue_ue.BrushBuilder.md#bitmapfilename)
- [Layer](ue_ue.BrushBuilder.md#layer)
- [MergeCoplanars](ue_ue.BrushBuilder.md#mergecoplanars)
- [NotifyBadParams](ue_ue.BrushBuilder.md#notifybadparams)
- [Polys](ue_ue.BrushBuilder.md#polys)
- [ToolTip](ue_ue.BrushBuilder.md#tooltip)
- [Vertices](ue_ue.BrushBuilder.md#vertices)
- [\_\_tid\_BrushBuilder\_\_](ue_ue.BrushBuilder.md#__tid_brushbuilder__)
- [\_\_tid\_Object\_\_](ue_ue.BrushBuilder.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.BrushBuilder.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BrushBuilder.md#executeubergraph)
- [GetClass](ue_ue.BrushBuilder.md#getclass)
- [GetName](ue_ue.BrushBuilder.md#getname)
- [GetOuter](ue_ue.BrushBuilder.md#getouter)
- [GetWorld](ue_ue.BrushBuilder.md#getworld)
- [Find](ue_ue.BrushBuilder.md#find)
- [Load](ue_ue.BrushBuilder.md#load)
- [StaticClass](ue_ue.BrushBuilder.md#staticclass)

## Constructors

### constructor

• **new BrushBuilder**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:12792](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12792)

## Properties

### BitmapFilename

• **BitmapFilename**: `string`

#### Defined in

[ue/ue.d.ts:12793](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12793)

___

### Layer

• **Layer**: `string`

#### Defined in

[ue/ue.d.ts:12798](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12798)

___

### MergeCoplanars

• **MergeCoplanars**: `boolean`

#### Defined in

[ue/ue.d.ts:12799](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12799)

___

### NotifyBadParams

• **NotifyBadParams**: `boolean`

#### Defined in

[ue/ue.d.ts:12795](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12795)

___

### Polys

• **Polys**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BuilderPoly`](ue_ue.BuilderPoly.md)\>

#### Defined in

[ue/ue.d.ts:12797](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12797)

___

### ToolTip

• **ToolTip**: `string`

#### Defined in

[ue/ue.d.ts:12794](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12794)

___

### Vertices

• **Vertices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Defined in

[ue/ue.d.ts:12796](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12796)

___

### \_\_tid\_BrushBuilder\_\_

• **\_\_tid\_BrushBuilder\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:12804](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12804)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BrushBuilder`](ue_ue.BrushBuilder.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BrushBuilder`](ue_ue.BrushBuilder.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:12801](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12801)

___

### Load

▸ `Static` **Load**(`InName`): [`BrushBuilder`](ue_ue.BrushBuilder.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BrushBuilder`](ue_ue.BrushBuilder.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:12802](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12802)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:12800](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12800)
