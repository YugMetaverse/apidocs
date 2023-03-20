[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / WorldComposition

# Class: WorldComposition

[ue/ue](../modules/ue_ue.md).WorldComposition

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`WorldComposition`**

## Table of contents

### Constructors

- [constructor](ue_ue.WorldComposition.md#constructor)

### Properties

- [RebaseOriginDistance](ue_ue.WorldComposition.md#rebaseorigindistance)
- [TilesStreaming](ue_ue.WorldComposition.md#tilesstreaming)
- [TilesStreamingTimeThreshold](ue_ue.WorldComposition.md#tilesstreamingtimethreshold)
- [\_\_tid\_Object\_\_](ue_ue.WorldComposition.md#__tid_object__)
- [\_\_tid\_WorldComposition\_\_](ue_ue.WorldComposition.md#__tid_worldcomposition__)
- [bLoadAllTilesDuringCinematic](ue_ue.WorldComposition.md#bloadalltilesduringcinematic)
- [bLockTilesLocation](ue_ue.WorldComposition.md#blocktileslocation)
- [bRebaseOriginIn3DSpace](ue_ue.WorldComposition.md#brebaseoriginin3dspace)

### Methods

- [CreateDefaultSubobject](ue_ue.WorldComposition.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.WorldComposition.md#executeubergraph)
- [GetClass](ue_ue.WorldComposition.md#getclass)
- [GetName](ue_ue.WorldComposition.md#getname)
- [GetOuter](ue_ue.WorldComposition.md#getouter)
- [GetWorld](ue_ue.WorldComposition.md#getworld)
- [Find](ue_ue.WorldComposition.md#find)
- [Load](ue_ue.WorldComposition.md#load)
- [StaticClass](ue_ue.WorldComposition.md#staticclass)

## Constructors

### constructor

• **new WorldComposition**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:10232](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10232)

## Properties

### RebaseOriginDistance

• **RebaseOriginDistance**: `number`

#### Defined in

[ue/ue.d.ts:10238](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10238)

___

### TilesStreaming

• **TilesStreaming**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LevelStreaming`](ue_ue.LevelStreaming.md)\>

#### Defined in

[ue/ue.d.ts:10233](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10233)

___

### TilesStreamingTimeThreshold

• **TilesStreamingTimeThreshold**: `number`

#### Defined in

[ue/ue.d.ts:10234](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10234)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_WorldComposition\_\_

• **\_\_tid\_WorldComposition\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:10243](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10243)

___

### bLoadAllTilesDuringCinematic

• **bLoadAllTilesDuringCinematic**: `boolean`

#### Defined in

[ue/ue.d.ts:10235](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10235)

___

### bLockTilesLocation

• **bLockTilesLocation**: `boolean`

#### Defined in

[ue/ue.d.ts:10237](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10237)

___

### bRebaseOriginIn3DSpace

• **bRebaseOriginIn3DSpace**: `boolean`

#### Defined in

[ue/ue.d.ts:10236](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10236)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`WorldComposition`](ue_ue.WorldComposition.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`WorldComposition`](ue_ue.WorldComposition.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:10240](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10240)

___

### Load

▸ `Static` **Load**(`InName`): [`WorldComposition`](ue_ue.WorldComposition.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`WorldComposition`](ue_ue.WorldComposition.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:10241](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10241)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:10239](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10239)
