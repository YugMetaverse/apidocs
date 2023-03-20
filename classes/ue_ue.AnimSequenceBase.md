[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimSequenceBase

# Class: AnimSequenceBase

[ue/ue](../modules/ue_ue.md).AnimSequenceBase

## Hierarchy

- [`AnimationAsset`](ue_ue.AnimationAsset.md)

  ↳ **`AnimSequenceBase`**

  ↳↳ [`AnimCompositeBase`](ue_ue.AnimCompositeBase.md)

  ↳↳ [`AnimSequence`](ue_ue.AnimSequence.md)

  ↳↳ [`AnimStreamable`](ue_ue.AnimStreamable.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimSequenceBase.md#constructor)

### Properties

- [AnimNotifyTracks](ue_ue.AnimSequenceBase.md#animnotifytracks)
- [AssetMappingTable](ue_ue.AnimSequenceBase.md#assetmappingtable)
- [AssetUserData](ue_ue.AnimSequenceBase.md#assetuserdata)
- [ChildrenAssets](ue_ue.AnimSequenceBase.md#childrenassets)
- [MetaData](ue_ue.AnimSequenceBase.md#metadata)
- [Notifies](ue_ue.AnimSequenceBase.md#notifies)
- [ParentAsset](ue_ue.AnimSequenceBase.md#parentasset)
- [PreviewPoseAsset](ue_ue.AnimSequenceBase.md#previewposeasset)
- [PreviewSkeletalMesh](ue_ue.AnimSequenceBase.md#previewskeletalmesh)
- [RateScale](ue_ue.AnimSequenceBase.md#ratescale)
- [RawCurveData](ue_ue.AnimSequenceBase.md#rawcurvedata)
- [SequenceLength](ue_ue.AnimSequenceBase.md#sequencelength)
- [Skeleton](ue_ue.AnimSequenceBase.md#skeleton)
- [ThumbnailInfo](ue_ue.AnimSequenceBase.md#thumbnailinfo)
- [\_\_tid\_AnimSequenceBase\_\_](ue_ue.AnimSequenceBase.md#__tid_animsequencebase__)
- [\_\_tid\_AnimationAsset\_\_](ue_ue.AnimSequenceBase.md#__tid_animationasset__)
- [\_\_tid\_Object\_\_](ue_ue.AnimSequenceBase.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimSequenceBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimSequenceBase.md#executeubergraph)
- [GetClass](ue_ue.AnimSequenceBase.md#getclass)
- [GetName](ue_ue.AnimSequenceBase.md#getname)
- [GetOuter](ue_ue.AnimSequenceBase.md#getouter)
- [GetPlayLength](ue_ue.AnimSequenceBase.md#getplaylength)
- [GetWorld](ue_ue.AnimSequenceBase.md#getworld)
- [Find](ue_ue.AnimSequenceBase.md#find)
- [Load](ue_ue.AnimSequenceBase.md#load)
- [StaticClass](ue_ue.AnimSequenceBase.md#staticclass)

## Constructors

### constructor

• **new AnimSequenceBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimationAsset](ue_ue.AnimationAsset.md).[constructor](ue_ue.AnimationAsset.md#constructor)

## Properties

### AnimNotifyTracks

• **AnimNotifyTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyTrack`](ue_ue.AnimNotifyTrack.md)\>

___

### AssetMappingTable

• **AssetMappingTable**: [`AssetMappingTable`](ue_ue.AssetMappingTable.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[AssetMappingTable](ue_ue.AnimationAsset.md#assetmappingtable)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[AssetUserData](ue_ue.AnimationAsset.md#assetuserdata)

___

### ChildrenAssets

• **ChildrenAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationAsset`](ue_ue.AnimationAsset.md)\>

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[ChildrenAssets](ue_ue.AnimationAsset.md#childrenassets)

___

### MetaData

• **MetaData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimMetaData`](ue_ue.AnimMetaData.md)\>

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[MetaData](ue_ue.AnimationAsset.md#metadata)

___

### Notifies

• **Notifies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)\>

___

### ParentAsset

• **ParentAsset**: [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[ParentAsset](ue_ue.AnimationAsset.md#parentasset)

___

### PreviewPoseAsset

• **PreviewPoseAsset**: [`PoseAsset`](ue_ue.PoseAsset.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[PreviewPoseAsset](ue_ue.AnimationAsset.md#previewposeasset)

___

### PreviewSkeletalMesh

• **PreviewSkeletalMesh**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`SkeletalMesh`](ue_ue.SkeletalMesh.md)\>

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[PreviewSkeletalMesh](ue_ue.AnimationAsset.md#previewskeletalmesh)

___

### RateScale

• **RateScale**: `number`

___

### RawCurveData

• **RawCurveData**: [`RawCurveTracks`](ue_ue.RawCurveTracks.md)

___

### SequenceLength

• **SequenceLength**: `number`

___

### Skeleton

• **Skeleton**: [`Skeleton`](ue_ue.Skeleton.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[Skeleton](ue_ue.AnimationAsset.md#skeleton)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[ThumbnailInfo](ue_ue.AnimationAsset.md#thumbnailinfo)

___

### \_\_tid\_AnimSequenceBase\_\_

• **\_\_tid\_AnimSequenceBase\_\_**: `boolean`

___

### \_\_tid\_AnimationAsset\_\_

• **\_\_tid\_AnimationAsset\_\_**: `boolean`

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[__tid_AnimationAsset__](ue_ue.AnimationAsset.md#__tid_animationasset__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[__tid_Object__](ue_ue.AnimationAsset.md#__tid_object__)

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

[AnimationAsset](ue_ue.AnimationAsset.md).[CreateDefaultSubobject](ue_ue.AnimationAsset.md#createdefaultsubobject)

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

[AnimationAsset](ue_ue.AnimationAsset.md).[ExecuteUbergraph](ue_ue.AnimationAsset.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[GetClass](ue_ue.AnimationAsset.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[GetName](ue_ue.AnimationAsset.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[GetOuter](ue_ue.AnimationAsset.md#getouter)

___

### GetPlayLength

▸ **GetPlayLength**(): `number`

#### Returns

`number`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[GetWorld](ue_ue.AnimationAsset.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)

#### Overrides

[AnimationAsset](ue_ue.AnimationAsset.md).[Find](ue_ue.AnimationAsset.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)

#### Overrides

[AnimationAsset](ue_ue.AnimationAsset.md).[Load](ue_ue.AnimationAsset.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimationAsset](ue_ue.AnimationAsset.md).[StaticClass](ue_ue.AnimationAsset.md#staticclass)
