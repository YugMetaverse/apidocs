[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GeomComponentCacheParameters

# Class: GeomComponentCacheParameters

[ue/ue](../modules/ue_ue.md).GeomComponentCacheParameters

## Table of contents

### Constructors

- [constructor](ue_ue.GeomComponentCacheParameters.md#constructor)

### Properties

- [BreakingDataSizeMax](ue_ue.GeomComponentCacheParameters.md#breakingdatasizemax)
- [BreakingDataSpatialHashRadius](ue_ue.GeomComponentCacheParameters.md#breakingdataspatialhashradius)
- [CacheMode](ue_ue.GeomComponentCacheParameters.md#cachemode)
- [CollisionDataSizeMax](ue_ue.GeomComponentCacheParameters.md#collisiondatasizemax)
- [CollisionDataSpatialHashRadius](ue_ue.GeomComponentCacheParameters.md#collisiondataspatialhashradius)
- [DoBreakingDataSpatialHash](ue_ue.GeomComponentCacheParameters.md#dobreakingdataspatialhash)
- [DoCollisionDataSpatialHash](ue_ue.GeomComponentCacheParameters.md#docollisiondataspatialhash)
- [DoGenerateBreakingData](ue_ue.GeomComponentCacheParameters.md#dogeneratebreakingdata)
- [DoGenerateCollisionData](ue_ue.GeomComponentCacheParameters.md#dogeneratecollisiondata)
- [DoGenerateTrailingData](ue_ue.GeomComponentCacheParameters.md#dogeneratetrailingdata)
- [MaxBreakingPerCell](ue_ue.GeomComponentCacheParameters.md#maxbreakingpercell)
- [MaxCollisionPerCell](ue_ue.GeomComponentCacheParameters.md#maxcollisionpercell)
- [ReverseCacheBeginTime](ue_ue.GeomComponentCacheParameters.md#reversecachebegintime)
- [SaveBreakingData](ue_ue.GeomComponentCacheParameters.md#savebreakingdata)
- [SaveCollisionData](ue_ue.GeomComponentCacheParameters.md#savecollisiondata)
- [SaveTrailingData](ue_ue.GeomComponentCacheParameters.md#savetrailingdata)
- [TargetCache](ue_ue.GeomComponentCacheParameters.md#targetcache)
- [TrailingDataSizeMax](ue_ue.GeomComponentCacheParameters.md#trailingdatasizemax)
- [TrailingMinSpeedThreshold](ue_ue.GeomComponentCacheParameters.md#trailingminspeedthreshold)
- [TrailingMinVolumeThreshold](ue_ue.GeomComponentCacheParameters.md#trailingminvolumethreshold)
- [\_\_tid\_GeomComponentCacheParameters\_\_](ue_ue.GeomComponentCacheParameters.md#__tid_geomcomponentcacheparameters__)

### Methods

- [StaticClass](ue_ue.GeomComponentCacheParameters.md#staticclass)
- [StaticStruct](ue_ue.GeomComponentCacheParameters.md#staticstruct)

## Constructors

### constructor

• **new GeomComponentCacheParameters**()

#### Defined in

[ue/ue.d.ts:26718](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26718)

• **new GeomComponentCacheParameters**(`CacheMode`, `TargetCache`, `ReverseCacheBeginTime`, `SaveCollisionData`, `DoGenerateCollisionData`, `CollisionDataSizeMax`, `DoCollisionDataSpatialHash`, `CollisionDataSpatialHashRadius`, `MaxCollisionPerCell`, `SaveBreakingData`, `DoGenerateBreakingData`, `BreakingDataSizeMax`, `DoBreakingDataSpatialHash`, `BreakingDataSpatialHashRadius`, `MaxBreakingPerCell`, `SaveTrailingData`, `DoGenerateTrailingData`, `TrailingDataSizeMax`, `TrailingMinSpeedThreshold`, `TrailingMinVolumeThreshold`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `CacheMode` | [`EGeometryCollectionCacheType`](../enums/ue_ue.EGeometryCollectionCacheType.md) |
| `TargetCache` | [`GeometryCollectionCache`](ue_ue.GeometryCollectionCache.md) |
| `ReverseCacheBeginTime` | `number` |
| `SaveCollisionData` | `boolean` |
| `DoGenerateCollisionData` | `boolean` |
| `CollisionDataSizeMax` | `number` |
| `DoCollisionDataSpatialHash` | `boolean` |
| `CollisionDataSpatialHashRadius` | `number` |
| `MaxCollisionPerCell` | `number` |
| `SaveBreakingData` | `boolean` |
| `DoGenerateBreakingData` | `boolean` |
| `BreakingDataSizeMax` | `number` |
| `DoBreakingDataSpatialHash` | `boolean` |
| `BreakingDataSpatialHashRadius` | `number` |
| `MaxBreakingPerCell` | `number` |
| `SaveTrailingData` | `boolean` |
| `DoGenerateTrailingData` | `boolean` |
| `TrailingDataSizeMax` | `number` |
| `TrailingMinSpeedThreshold` | `number` |
| `TrailingMinVolumeThreshold` | `number` |

#### Defined in

[ue/ue.d.ts:26719](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26719)

## Properties

### BreakingDataSizeMax

• **BreakingDataSizeMax**: `number`

#### Defined in

[ue/ue.d.ts:26731](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26731)

___

### BreakingDataSpatialHashRadius

• **BreakingDataSpatialHashRadius**: `number`

#### Defined in

[ue/ue.d.ts:26733](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26733)

___

### CacheMode

• **CacheMode**: [`EGeometryCollectionCacheType`](../enums/ue_ue.EGeometryCollectionCacheType.md)

#### Defined in

[ue/ue.d.ts:26720](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26720)

___

### CollisionDataSizeMax

• **CollisionDataSizeMax**: `number`

#### Defined in

[ue/ue.d.ts:26725](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26725)

___

### CollisionDataSpatialHashRadius

• **CollisionDataSpatialHashRadius**: `number`

#### Defined in

[ue/ue.d.ts:26727](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26727)

___

### DoBreakingDataSpatialHash

• **DoBreakingDataSpatialHash**: `boolean`

#### Defined in

[ue/ue.d.ts:26732](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26732)

___

### DoCollisionDataSpatialHash

• **DoCollisionDataSpatialHash**: `boolean`

#### Defined in

[ue/ue.d.ts:26726](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26726)

___

### DoGenerateBreakingData

• **DoGenerateBreakingData**: `boolean`

#### Defined in

[ue/ue.d.ts:26730](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26730)

___

### DoGenerateCollisionData

• **DoGenerateCollisionData**: `boolean`

#### Defined in

[ue/ue.d.ts:26724](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26724)

___

### DoGenerateTrailingData

• **DoGenerateTrailingData**: `boolean`

#### Defined in

[ue/ue.d.ts:26736](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26736)

___

### MaxBreakingPerCell

• **MaxBreakingPerCell**: `number`

#### Defined in

[ue/ue.d.ts:26734](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26734)

___

### MaxCollisionPerCell

• **MaxCollisionPerCell**: `number`

#### Defined in

[ue/ue.d.ts:26728](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26728)

___

### ReverseCacheBeginTime

• **ReverseCacheBeginTime**: `number`

#### Defined in

[ue/ue.d.ts:26722](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26722)

___

### SaveBreakingData

• **SaveBreakingData**: `boolean`

#### Defined in

[ue/ue.d.ts:26729](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26729)

___

### SaveCollisionData

• **SaveCollisionData**: `boolean`

#### Defined in

[ue/ue.d.ts:26723](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26723)

___

### SaveTrailingData

• **SaveTrailingData**: `boolean`

#### Defined in

[ue/ue.d.ts:26735](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26735)

___

### TargetCache

• **TargetCache**: [`GeometryCollectionCache`](ue_ue.GeometryCollectionCache.md)

#### Defined in

[ue/ue.d.ts:26721](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26721)

___

### TrailingDataSizeMax

• **TrailingDataSizeMax**: `number`

#### Defined in

[ue/ue.d.ts:26737](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26737)

___

### TrailingMinSpeedThreshold

• **TrailingMinSpeedThreshold**: `number`

#### Defined in

[ue/ue.d.ts:26738](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26738)

___

### TrailingMinVolumeThreshold

• **TrailingMinVolumeThreshold**: `number`

#### Defined in

[ue/ue.d.ts:26739](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26739)

___

### \_\_tid\_GeomComponentCacheParameters\_\_

• `Private` **\_\_tid\_GeomComponentCacheParameters\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:26745](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26745)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:26743](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26743)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:26744](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26744)
