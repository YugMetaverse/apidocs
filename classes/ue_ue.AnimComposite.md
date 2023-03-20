[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimComposite

# Class: AnimComposite

[ue/ue](../modules/ue_ue.md).AnimComposite

## Hierarchy

- [`AnimCompositeBase`](ue_ue.AnimCompositeBase.md)

  ↳ **`AnimComposite`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimComposite.md#constructor)

### Properties

- [AnimNotifyTracks](ue_ue.AnimComposite.md#animnotifytracks)
- [AnimationTrack](ue_ue.AnimComposite.md#animationtrack)
- [AssetMappingTable](ue_ue.AnimComposite.md#assetmappingtable)
- [AssetUserData](ue_ue.AnimComposite.md#assetuserdata)
- [ChildrenAssets](ue_ue.AnimComposite.md#childrenassets)
- [MetaData](ue_ue.AnimComposite.md#metadata)
- [Notifies](ue_ue.AnimComposite.md#notifies)
- [ParentAsset](ue_ue.AnimComposite.md#parentasset)
- [PreviewBasePose](ue_ue.AnimComposite.md#previewbasepose)
- [PreviewPoseAsset](ue_ue.AnimComposite.md#previewposeasset)
- [PreviewSkeletalMesh](ue_ue.AnimComposite.md#previewskeletalmesh)
- [RateScale](ue_ue.AnimComposite.md#ratescale)
- [RawCurveData](ue_ue.AnimComposite.md#rawcurvedata)
- [SequenceLength](ue_ue.AnimComposite.md#sequencelength)
- [Skeleton](ue_ue.AnimComposite.md#skeleton)
- [ThumbnailInfo](ue_ue.AnimComposite.md#thumbnailinfo)
- [\_\_tid\_AnimCompositeBase\_\_](ue_ue.AnimComposite.md#__tid_animcompositebase__)
- [\_\_tid\_AnimComposite\_\_](ue_ue.AnimComposite.md#__tid_animcomposite__)
- [\_\_tid\_AnimSequenceBase\_\_](ue_ue.AnimComposite.md#__tid_animsequencebase__)
- [\_\_tid\_AnimationAsset\_\_](ue_ue.AnimComposite.md#__tid_animationasset__)
- [\_\_tid\_Object\_\_](ue_ue.AnimComposite.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimComposite.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimComposite.md#executeubergraph)
- [GetClass](ue_ue.AnimComposite.md#getclass)
- [GetName](ue_ue.AnimComposite.md#getname)
- [GetOuter](ue_ue.AnimComposite.md#getouter)
- [GetPlayLength](ue_ue.AnimComposite.md#getplaylength)
- [GetWorld](ue_ue.AnimComposite.md#getworld)
- [Find](ue_ue.AnimComposite.md#find)
- [Load](ue_ue.AnimComposite.md#load)
- [StaticClass](ue_ue.AnimComposite.md#staticclass)

## Constructors

### constructor

• **new AnimComposite**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[constructor](ue_ue.AnimCompositeBase.md#constructor)

## Properties

### AnimNotifyTracks

• **AnimNotifyTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyTrack`](ue_ue.AnimNotifyTrack.md)\>

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[AnimNotifyTracks](ue_ue.AnimCompositeBase.md#animnotifytracks)

___

### AnimationTrack

• **AnimationTrack**: [`AnimTrack`](ue_ue.AnimTrack.md)

___

### AssetMappingTable

• **AssetMappingTable**: [`AssetMappingTable`](ue_ue.AssetMappingTable.md)

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[AssetMappingTable](ue_ue.AnimCompositeBase.md#assetmappingtable)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[AssetUserData](ue_ue.AnimCompositeBase.md#assetuserdata)

___

### ChildrenAssets

• **ChildrenAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationAsset`](ue_ue.AnimationAsset.md)\>

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[ChildrenAssets](ue_ue.AnimCompositeBase.md#childrenassets)

___

### MetaData

• **MetaData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimMetaData`](ue_ue.AnimMetaData.md)\>

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[MetaData](ue_ue.AnimCompositeBase.md#metadata)

___

### Notifies

• **Notifies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)\>

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[Notifies](ue_ue.AnimCompositeBase.md#notifies)

___

### ParentAsset

• **ParentAsset**: [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[ParentAsset](ue_ue.AnimCompositeBase.md#parentasset)

___

### PreviewBasePose

• **PreviewBasePose**: [`AnimSequence`](ue_ue.AnimSequence.md)

___

### PreviewPoseAsset

• **PreviewPoseAsset**: [`PoseAsset`](ue_ue.PoseAsset.md)

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[PreviewPoseAsset](ue_ue.AnimCompositeBase.md#previewposeasset)

___

### PreviewSkeletalMesh

• **PreviewSkeletalMesh**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`SkeletalMesh`](ue_ue.SkeletalMesh.md)\>

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[PreviewSkeletalMesh](ue_ue.AnimCompositeBase.md#previewskeletalmesh)

___

### RateScale

• **RateScale**: `number`

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[RateScale](ue_ue.AnimCompositeBase.md#ratescale)

___

### RawCurveData

• **RawCurveData**: [`RawCurveTracks`](ue_ue.RawCurveTracks.md)

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[RawCurveData](ue_ue.AnimCompositeBase.md#rawcurvedata)

___

### SequenceLength

• **SequenceLength**: `number`

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[SequenceLength](ue_ue.AnimCompositeBase.md#sequencelength)

___

### Skeleton

• **Skeleton**: [`Skeleton`](ue_ue.Skeleton.md)

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[Skeleton](ue_ue.AnimCompositeBase.md#skeleton)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[ThumbnailInfo](ue_ue.AnimCompositeBase.md#thumbnailinfo)

___

### \_\_tid\_AnimCompositeBase\_\_

• **\_\_tid\_AnimCompositeBase\_\_**: `boolean`

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[__tid_AnimCompositeBase__](ue_ue.AnimCompositeBase.md#__tid_animcompositebase__)

___

### \_\_tid\_AnimComposite\_\_

• **\_\_tid\_AnimComposite\_\_**: `boolean`

___

### \_\_tid\_AnimSequenceBase\_\_

• **\_\_tid\_AnimSequenceBase\_\_**: `boolean`

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[__tid_AnimSequenceBase__](ue_ue.AnimCompositeBase.md#__tid_animsequencebase__)

___

### \_\_tid\_AnimationAsset\_\_

• **\_\_tid\_AnimationAsset\_\_**: `boolean`

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[__tid_AnimationAsset__](ue_ue.AnimCompositeBase.md#__tid_animationasset__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[__tid_Object__](ue_ue.AnimCompositeBase.md#__tid_object__)

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

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[CreateDefaultSubobject](ue_ue.AnimCompositeBase.md#createdefaultsubobject)

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

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[ExecuteUbergraph](ue_ue.AnimCompositeBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[GetClass](ue_ue.AnimCompositeBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[GetName](ue_ue.AnimCompositeBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[GetOuter](ue_ue.AnimCompositeBase.md#getouter)

___

### GetPlayLength

▸ **GetPlayLength**(): `number`

#### Returns

`number`

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[GetPlayLength](ue_ue.AnimCompositeBase.md#getplaylength)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[GetWorld](ue_ue.AnimCompositeBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimComposite`](ue_ue.AnimComposite.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimComposite`](ue_ue.AnimComposite.md)

#### Overrides

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[Find](ue_ue.AnimCompositeBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimComposite`](ue_ue.AnimComposite.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimComposite`](ue_ue.AnimComposite.md)

#### Overrides

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[Load](ue_ue.AnimCompositeBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[StaticClass](ue_ue.AnimCompositeBase.md#staticclass)
