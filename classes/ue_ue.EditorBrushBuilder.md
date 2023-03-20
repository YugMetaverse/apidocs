[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorBrushBuilder

# Class: EditorBrushBuilder

[ue/ue](../modules/ue_ue.md).EditorBrushBuilder

## Hierarchy

- [`BrushBuilder`](ue_ue.BrushBuilder.md)

  ↳ **`EditorBrushBuilder`**

  ↳↳ [`ConeBuilder`](ue_ue.ConeBuilder.md)

  ↳↳ [`CubeBuilder`](ue_ue.CubeBuilder.md)

  ↳↳ [`CurvedStairBuilder`](ue_ue.CurvedStairBuilder.md)

  ↳↳ [`CylinderBuilder`](ue_ue.CylinderBuilder.md)

  ↳↳ [`LinearStairBuilder`](ue_ue.LinearStairBuilder.md)

  ↳↳ [`SheetBuilder`](ue_ue.SheetBuilder.md)

  ↳↳ [`SpiralStairBuilder`](ue_ue.SpiralStairBuilder.md)

  ↳↳ [`TetrahedronBuilder`](ue_ue.TetrahedronBuilder.md)

  ↳↳ [`VolumetricBuilder`](ue_ue.VolumetricBuilder.md)

## Table of contents

### Constructors

- [constructor](ue_ue.EditorBrushBuilder.md#constructor)

### Properties

- [BitmapFilename](ue_ue.EditorBrushBuilder.md#bitmapfilename)
- [Layer](ue_ue.EditorBrushBuilder.md#layer)
- [MergeCoplanars](ue_ue.EditorBrushBuilder.md#mergecoplanars)
- [NotifyBadParams](ue_ue.EditorBrushBuilder.md#notifybadparams)
- [Polys](ue_ue.EditorBrushBuilder.md#polys)
- [ToolTip](ue_ue.EditorBrushBuilder.md#tooltip)
- [Vertices](ue_ue.EditorBrushBuilder.md#vertices)
- [\_\_tid\_BrushBuilder\_\_](ue_ue.EditorBrushBuilder.md#__tid_brushbuilder__)
- [\_\_tid\_EditorBrushBuilder\_\_](ue_ue.EditorBrushBuilder.md#__tid_editorbrushbuilder__)
- [\_\_tid\_Object\_\_](ue_ue.EditorBrushBuilder.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.EditorBrushBuilder.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditorBrushBuilder.md#executeubergraph)
- [GetClass](ue_ue.EditorBrushBuilder.md#getclass)
- [GetName](ue_ue.EditorBrushBuilder.md#getname)
- [GetOuter](ue_ue.EditorBrushBuilder.md#getouter)
- [GetWorld](ue_ue.EditorBrushBuilder.md#getworld)
- [Find](ue_ue.EditorBrushBuilder.md#find)
- [Load](ue_ue.EditorBrushBuilder.md#load)
- [StaticClass](ue_ue.EditorBrushBuilder.md#staticclass)

## Constructors

### constructor

• **new EditorBrushBuilder**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BrushBuilder](ue_ue.BrushBuilder.md).[constructor](ue_ue.BrushBuilder.md#constructor)

#### Defined in

[ue/ue.d.ts:28540](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28540)

## Properties

### BitmapFilename

• **BitmapFilename**: `string`

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[BitmapFilename](ue_ue.BrushBuilder.md#bitmapfilename)

#### Defined in

[ue/ue.d.ts:12793](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12793)

___

### Layer

• **Layer**: `string`

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[Layer](ue_ue.BrushBuilder.md#layer)

#### Defined in

[ue/ue.d.ts:12798](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12798)

___

### MergeCoplanars

• **MergeCoplanars**: `boolean`

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[MergeCoplanars](ue_ue.BrushBuilder.md#mergecoplanars)

#### Defined in

[ue/ue.d.ts:12799](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12799)

___

### NotifyBadParams

• **NotifyBadParams**: `boolean`

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[NotifyBadParams](ue_ue.BrushBuilder.md#notifybadparams)

#### Defined in

[ue/ue.d.ts:12795](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12795)

___

### Polys

• **Polys**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BuilderPoly`](ue_ue.BuilderPoly.md)\>

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[Polys](ue_ue.BrushBuilder.md#polys)

#### Defined in

[ue/ue.d.ts:12797](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12797)

___

### ToolTip

• **ToolTip**: `string`

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[ToolTip](ue_ue.BrushBuilder.md#tooltip)

#### Defined in

[ue/ue.d.ts:12794](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12794)

___

### Vertices

• **Vertices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[Vertices](ue_ue.BrushBuilder.md#vertices)

#### Defined in

[ue/ue.d.ts:12796](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12796)

___

### \_\_tid\_BrushBuilder\_\_

• **\_\_tid\_BrushBuilder\_\_**: `boolean`

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[__tid_BrushBuilder__](ue_ue.BrushBuilder.md#__tid_brushbuilder__)

#### Defined in

[ue/ue.d.ts:12804](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12804)

___

### \_\_tid\_EditorBrushBuilder\_\_

• **\_\_tid\_EditorBrushBuilder\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:28545](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28545)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[__tid_Object__](ue_ue.BrushBuilder.md#__tid_object__)

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

[BrushBuilder](ue_ue.BrushBuilder.md).[CreateDefaultSubobject](ue_ue.BrushBuilder.md#createdefaultsubobject)

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

[BrushBuilder](ue_ue.BrushBuilder.md).[ExecuteUbergraph](ue_ue.BrushBuilder.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[GetClass](ue_ue.BrushBuilder.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[GetName](ue_ue.BrushBuilder.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[GetOuter](ue_ue.BrushBuilder.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[GetWorld](ue_ue.BrushBuilder.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorBrushBuilder`](ue_ue.EditorBrushBuilder.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorBrushBuilder`](ue_ue.EditorBrushBuilder.md)

#### Overrides

[BrushBuilder](ue_ue.BrushBuilder.md).[Find](ue_ue.BrushBuilder.md#find)

#### Defined in

[ue/ue.d.ts:28542](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28542)

___

### Load

▸ `Static` **Load**(`InName`): [`EditorBrushBuilder`](ue_ue.EditorBrushBuilder.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorBrushBuilder`](ue_ue.EditorBrushBuilder.md)

#### Overrides

[BrushBuilder](ue_ue.BrushBuilder.md).[Load](ue_ue.BrushBuilder.md#load)

#### Defined in

[ue/ue.d.ts:28543](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28543)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BrushBuilder](ue_ue.BrushBuilder.md).[StaticClass](ue_ue.BrushBuilder.md#staticclass)

#### Defined in

[ue/ue.d.ts:28541](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28541)
