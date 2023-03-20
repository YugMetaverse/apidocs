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

## Properties

### RebaseOriginDistance

• **RebaseOriginDistance**: `number`

___

### TilesStreaming

• **TilesStreaming**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LevelStreaming`](ue_ue.LevelStreaming.md)\>

___

### TilesStreamingTimeThreshold

• **TilesStreamingTimeThreshold**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_WorldComposition\_\_

• **\_\_tid\_WorldComposition\_\_**: `boolean`

___

### bLoadAllTilesDuringCinematic

• **bLoadAllTilesDuringCinematic**: `boolean`

___

### bLockTilesLocation

• **bLockTilesLocation**: `boolean`

___

### bRebaseOriginIn3DSpace

• **bRebaseOriginIn3DSpace**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
