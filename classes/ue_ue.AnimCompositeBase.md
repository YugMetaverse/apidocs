[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimCompositeBase

# Class: AnimCompositeBase

[ue/ue](../modules/ue_ue.md).AnimCompositeBase

## Hierarchy

- [`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)

  ↳ **`AnimCompositeBase`**

  ↳↳ [`AnimMontage`](ue_ue.AnimMontage.md)

  ↳↳ [`AnimComposite`](ue_ue.AnimComposite.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimCompositeBase.md#constructor)

### Properties

- [AnimNotifyTracks](ue_ue.AnimCompositeBase.md#animnotifytracks)
- [AssetMappingTable](ue_ue.AnimCompositeBase.md#assetmappingtable)
- [AssetUserData](ue_ue.AnimCompositeBase.md#assetuserdata)
- [ChildrenAssets](ue_ue.AnimCompositeBase.md#childrenassets)
- [MetaData](ue_ue.AnimCompositeBase.md#metadata)
- [Notifies](ue_ue.AnimCompositeBase.md#notifies)
- [ParentAsset](ue_ue.AnimCompositeBase.md#parentasset)
- [PreviewPoseAsset](ue_ue.AnimCompositeBase.md#previewposeasset)
- [PreviewSkeletalMesh](ue_ue.AnimCompositeBase.md#previewskeletalmesh)
- [RateScale](ue_ue.AnimCompositeBase.md#ratescale)
- [RawCurveData](ue_ue.AnimCompositeBase.md#rawcurvedata)
- [SequenceLength](ue_ue.AnimCompositeBase.md#sequencelength)
- [Skeleton](ue_ue.AnimCompositeBase.md#skeleton)
- [ThumbnailInfo](ue_ue.AnimCompositeBase.md#thumbnailinfo)
- [\_\_tid\_AnimCompositeBase\_\_](ue_ue.AnimCompositeBase.md#__tid_animcompositebase__)
- [\_\_tid\_AnimSequenceBase\_\_](ue_ue.AnimCompositeBase.md#__tid_animsequencebase__)
- [\_\_tid\_AnimationAsset\_\_](ue_ue.AnimCompositeBase.md#__tid_animationasset__)
- [\_\_tid\_Object\_\_](ue_ue.AnimCompositeBase.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimCompositeBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimCompositeBase.md#executeubergraph)
- [GetClass](ue_ue.AnimCompositeBase.md#getclass)
- [GetName](ue_ue.AnimCompositeBase.md#getname)
- [GetOuter](ue_ue.AnimCompositeBase.md#getouter)
- [GetPlayLength](ue_ue.AnimCompositeBase.md#getplaylength)
- [GetWorld](ue_ue.AnimCompositeBase.md#getworld)
- [Find](ue_ue.AnimCompositeBase.md#find)
- [Load](ue_ue.AnimCompositeBase.md#load)
- [StaticClass](ue_ue.AnimCompositeBase.md#staticclass)

## Constructors

### constructor

• **new AnimCompositeBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[constructor](ue_ue.AnimSequenceBase.md#constructor)

## Properties

### AnimNotifyTracks

• **AnimNotifyTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyTrack`](ue_ue.AnimNotifyTrack.md)\>

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[AnimNotifyTracks](ue_ue.AnimSequenceBase.md#animnotifytracks)

___

### AssetMappingTable

• **AssetMappingTable**: [`AssetMappingTable`](ue_ue.AssetMappingTable.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[AssetMappingTable](ue_ue.AnimSequenceBase.md#assetmappingtable)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[AssetUserData](ue_ue.AnimSequenceBase.md#assetuserdata)

___

### ChildrenAssets

• **ChildrenAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationAsset`](ue_ue.AnimationAsset.md)\>

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[ChildrenAssets](ue_ue.AnimSequenceBase.md#childrenassets)

___

### MetaData

• **MetaData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimMetaData`](ue_ue.AnimMetaData.md)\>

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[MetaData](ue_ue.AnimSequenceBase.md#metadata)

___

### Notifies

• **Notifies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)\>

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[Notifies](ue_ue.AnimSequenceBase.md#notifies)

___

### ParentAsset

• **ParentAsset**: [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[ParentAsset](ue_ue.AnimSequenceBase.md#parentasset)

___

### PreviewPoseAsset

• **PreviewPoseAsset**: [`PoseAsset`](ue_ue.PoseAsset.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[PreviewPoseAsset](ue_ue.AnimSequenceBase.md#previewposeasset)

___

### PreviewSkeletalMesh

• **PreviewSkeletalMesh**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`SkeletalMesh`](ue_ue.SkeletalMesh.md)\>

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[PreviewSkeletalMesh](ue_ue.AnimSequenceBase.md#previewskeletalmesh)

___

### RateScale

• **RateScale**: `number`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[RateScale](ue_ue.AnimSequenceBase.md#ratescale)

___

### RawCurveData

• **RawCurveData**: [`RawCurveTracks`](ue_ue.RawCurveTracks.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[RawCurveData](ue_ue.AnimSequenceBase.md#rawcurvedata)

___

### SequenceLength

• **SequenceLength**: `number`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[SequenceLength](ue_ue.AnimSequenceBase.md#sequencelength)

___

### Skeleton

• **Skeleton**: [`Skeleton`](ue_ue.Skeleton.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[Skeleton](ue_ue.AnimSequenceBase.md#skeleton)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[ThumbnailInfo](ue_ue.AnimSequenceBase.md#thumbnailinfo)

___

### \_\_tid\_AnimCompositeBase\_\_

• **\_\_tid\_AnimCompositeBase\_\_**: `boolean`

___

### \_\_tid\_AnimSequenceBase\_\_

• **\_\_tid\_AnimSequenceBase\_\_**: `boolean`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[__tid_AnimSequenceBase__](ue_ue.AnimSequenceBase.md#__tid_animsequencebase__)

___

### \_\_tid\_AnimationAsset\_\_

• **\_\_tid\_AnimationAsset\_\_**: `boolean`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[__tid_AnimationAsset__](ue_ue.AnimSequenceBase.md#__tid_animationasset__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[__tid_Object__](ue_ue.AnimSequenceBase.md#__tid_object__)

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

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[CreateDefaultSubobject](ue_ue.AnimSequenceBase.md#createdefaultsubobject)

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

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[ExecuteUbergraph](ue_ue.AnimSequenceBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[GetClass](ue_ue.AnimSequenceBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[GetName](ue_ue.AnimSequenceBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[GetOuter](ue_ue.AnimSequenceBase.md#getouter)

___

### GetPlayLength

▸ **GetPlayLength**(): `number`

#### Returns

`number`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[GetPlayLength](ue_ue.AnimSequenceBase.md#getplaylength)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[GetWorld](ue_ue.AnimSequenceBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimCompositeBase`](ue_ue.AnimCompositeBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimCompositeBase`](ue_ue.AnimCompositeBase.md)

#### Overrides

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[Find](ue_ue.AnimSequenceBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimCompositeBase`](ue_ue.AnimCompositeBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimCompositeBase`](ue_ue.AnimCompositeBase.md)

#### Overrides

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[Load](ue_ue.AnimSequenceBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[StaticClass](ue_ue.AnimSequenceBase.md#staticclass)
