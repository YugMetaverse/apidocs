[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimStreamable

# Class: AnimStreamable

[ue/ue](../modules/ue_ue.md).AnimStreamable

## Hierarchy

- [`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)

  ↳ **`AnimStreamable`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimStreamable.md#constructor)

### Properties

- [AnimNotifyTracks](ue_ue.AnimStreamable.md#animnotifytracks)
- [AnimationTrackNames](ue_ue.AnimStreamable.md#animationtracknames)
- [AssetMappingTable](ue_ue.AnimStreamable.md#assetmappingtable)
- [AssetUserData](ue_ue.AnimStreamable.md#assetuserdata)
- [ChildrenAssets](ue_ue.AnimStreamable.md#childrenassets)
- [CompressionScheme](ue_ue.AnimStreamable.md#compressionscheme)
- [CurveCompressionSettings](ue_ue.AnimStreamable.md#curvecompressionsettings)
- [Interpolation](ue_ue.AnimStreamable.md#interpolation)
- [MetaData](ue_ue.AnimStreamable.md#metadata)
- [Notifies](ue_ue.AnimStreamable.md#notifies)
- [NumFrames](ue_ue.AnimStreamable.md#numframes)
- [ParentAsset](ue_ue.AnimStreamable.md#parentasset)
- [PreviewPoseAsset](ue_ue.AnimStreamable.md#previewposeasset)
- [PreviewSkeletalMesh](ue_ue.AnimStreamable.md#previewskeletalmesh)
- [RateScale](ue_ue.AnimStreamable.md#ratescale)
- [RawAnimationData](ue_ue.AnimStreamable.md#rawanimationdata)
- [RawCurveData](ue_ue.AnimStreamable.md#rawcurvedata)
- [RawDataGuid](ue_ue.AnimStreamable.md#rawdataguid)
- [RetargetSource](ue_ue.AnimStreamable.md#retargetsource)
- [RootMotionRootLock](ue_ue.AnimStreamable.md#rootmotionrootlock)
- [SequenceLength](ue_ue.AnimStreamable.md#sequencelength)
- [Skeleton](ue_ue.AnimStreamable.md#skeleton)
- [SourceSequence](ue_ue.AnimStreamable.md#sourcesequence)
- [ThumbnailInfo](ue_ue.AnimStreamable.md#thumbnailinfo)
- [TrackToSkeletonMapTable](ue_ue.AnimStreamable.md#tracktoskeletonmaptable)
- [\_\_tid\_AnimSequenceBase\_\_](ue_ue.AnimStreamable.md#__tid_animsequencebase__)
- [\_\_tid\_AnimStreamable\_\_](ue_ue.AnimStreamable.md#__tid_animstreamable__)
- [\_\_tid\_AnimationAsset\_\_](ue_ue.AnimStreamable.md#__tid_animationasset__)
- [\_\_tid\_Object\_\_](ue_ue.AnimStreamable.md#__tid_object__)
- [bEnableRootMotion](ue_ue.AnimStreamable.md#benablerootmotion)
- [bForceRootLock](ue_ue.AnimStreamable.md#bforcerootlock)
- [bUseNormalizedRootMotionScale](ue_ue.AnimStreamable.md#busenormalizedrootmotionscale)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimStreamable.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimStreamable.md#executeubergraph)
- [GetClass](ue_ue.AnimStreamable.md#getclass)
- [GetName](ue_ue.AnimStreamable.md#getname)
- [GetOuter](ue_ue.AnimStreamable.md#getouter)
- [GetPlayLength](ue_ue.AnimStreamable.md#getplaylength)
- [GetWorld](ue_ue.AnimStreamable.md#getworld)
- [Find](ue_ue.AnimStreamable.md#find)
- [Load](ue_ue.AnimStreamable.md#load)
- [StaticClass](ue_ue.AnimStreamable.md#staticclass)

## Constructors

### constructor

• **new AnimStreamable**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[constructor](ue_ue.AnimSequenceBase.md#constructor)

#### Defined in

[ue/ue.d.ts:20551](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20551)

## Properties

### AnimNotifyTracks

• **AnimNotifyTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyTrack`](ue_ue.AnimNotifyTrack.md)\>

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[AnimNotifyTracks](ue_ue.AnimSequenceBase.md#animnotifytracks)

#### Defined in

[ue/ue.d.ts:3134](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3134)

___

### AnimationTrackNames

• **AnimationTrackNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:20560](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20560)

___

### AssetMappingTable

• **AssetMappingTable**: [`AssetMappingTable`](ue_ue.AssetMappingTable.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[AssetMappingTable](ue_ue.AnimSequenceBase.md#assetmappingtable)

#### Defined in

[ue/ue.d.ts:2766](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2766)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[AssetUserData](ue_ue.AnimSequenceBase.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:2767](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2767)

___

### ChildrenAssets

• **ChildrenAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationAsset`](ue_ue.AnimationAsset.md)\>

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[ChildrenAssets](ue_ue.AnimSequenceBase.md#childrenassets)

#### Defined in

[ue/ue.d.ts:2765](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2765)

___

### CompressionScheme

• **CompressionScheme**: [`AnimCompress`](ue_ue.AnimCompress.md)

#### Defined in

[ue/ue.d.ts:20556](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20556)

___

### CurveCompressionSettings

• **CurveCompressionSettings**: [`AnimCurveCompressionSettings`](ue_ue.AnimCurveCompressionSettings.md)

#### Defined in

[ue/ue.d.ts:20561](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20561)

___

### Interpolation

• **Interpolation**: [`EAnimInterpolationType`](../enums/ue_ue.EAnimInterpolationType.md)

#### Defined in

[ue/ue.d.ts:20553](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20553)

___

### MetaData

• **MetaData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimMetaData`](ue_ue.AnimMetaData.md)\>

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[MetaData](ue_ue.AnimSequenceBase.md#metadata)

#### Defined in

[ue/ue.d.ts:2763](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2763)

___

### Notifies

• **Notifies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)\>

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[Notifies](ue_ue.AnimSequenceBase.md#notifies)

#### Defined in

[ue/ue.d.ts:3130](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3130)

___

### NumFrames

• **NumFrames**: `number`

#### Defined in

[ue/ue.d.ts:20552](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20552)

___

### ParentAsset

• **ParentAsset**: [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[ParentAsset](ue_ue.AnimSequenceBase.md#parentasset)

#### Defined in

[ue/ue.d.ts:2764](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2764)

___

### PreviewPoseAsset

• **PreviewPoseAsset**: [`PoseAsset`](ue_ue.PoseAsset.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[PreviewPoseAsset](ue_ue.AnimSequenceBase.md#previewposeasset)

#### Defined in

[ue/ue.d.ts:2769](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2769)

___

### PreviewSkeletalMesh

• **PreviewSkeletalMesh**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`SkeletalMesh`](ue_ue.SkeletalMesh.md)\>

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[PreviewSkeletalMesh](ue_ue.AnimSequenceBase.md#previewskeletalmesh)

#### Defined in

[ue/ue.d.ts:2770](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2770)

___

### RateScale

• **RateScale**: `number`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[RateScale](ue_ue.AnimSequenceBase.md#ratescale)

#### Defined in

[ue/ue.d.ts:3132](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3132)

___

### RawAnimationData

• **RawAnimationData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RawAnimSequenceTrack`](ue_ue.RawAnimSequenceTrack.md)\>

#### Defined in

[ue/ue.d.ts:20558](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20558)

___

### RawCurveData

• **RawCurveData**: [`RawCurveTracks`](ue_ue.RawCurveTracks.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[RawCurveData](ue_ue.AnimSequenceBase.md#rawcurvedata)

#### Defined in

[ue/ue.d.ts:3133](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3133)

___

### RawDataGuid

• **RawDataGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:20557](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20557)

___

### RetargetSource

• **RetargetSource**: `string`

#### Defined in

[ue/ue.d.ts:20554](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20554)

___

### RootMotionRootLock

• **RootMotionRootLock**: [`ERootMotionRootLock`](../enums/ue_ue.ERootMotionRootLock.md)

#### Defined in

[ue/ue.d.ts:20563](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20563)

___

### SequenceLength

• **SequenceLength**: `number`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[SequenceLength](ue_ue.AnimSequenceBase.md#sequencelength)

#### Defined in

[ue/ue.d.ts:3131](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3131)

___

### Skeleton

• **Skeleton**: [`Skeleton`](ue_ue.Skeleton.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[Skeleton](ue_ue.AnimSequenceBase.md#skeleton)

#### Defined in

[ue/ue.d.ts:2762](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2762)

___

### SourceSequence

• **SourceSequence**: [`AnimSequence`](ue_ue.AnimSequence.md)

#### Defined in

[ue/ue.d.ts:20555](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20555)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[ThumbnailInfo](ue_ue.AnimSequenceBase.md#thumbnailinfo)

#### Defined in

[ue/ue.d.ts:2768](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2768)

___

### TrackToSkeletonMapTable

• **TrackToSkeletonMapTable**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TrackToSkeletonMap`](ue_ue.TrackToSkeletonMap.md)\>

#### Defined in

[ue/ue.d.ts:20559](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20559)

___

### \_\_tid\_AnimSequenceBase\_\_

• **\_\_tid\_AnimSequenceBase\_\_**: `boolean`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[__tid_AnimSequenceBase__](ue_ue.AnimSequenceBase.md#__tid_animsequencebase__)

#### Defined in

[ue/ue.d.ts:3140](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3140)

___

### \_\_tid\_AnimStreamable\_\_

• **\_\_tid\_AnimStreamable\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:20570](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20570)

___

### \_\_tid\_AnimationAsset\_\_

• **\_\_tid\_AnimationAsset\_\_**: `boolean`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[__tid_AnimationAsset__](ue_ue.AnimSequenceBase.md#__tid_animationasset__)

#### Defined in

[ue/ue.d.ts:2775](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2775)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[__tid_Object__](ue_ue.AnimSequenceBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bEnableRootMotion

• **bEnableRootMotion**: `boolean`

#### Defined in

[ue/ue.d.ts:20562](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20562)

___

### bForceRootLock

• **bForceRootLock**: `boolean`

#### Defined in

[ue/ue.d.ts:20564](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20564)

___

### bUseNormalizedRootMotionScale

• **bUseNormalizedRootMotionScale**: `boolean`

#### Defined in

[ue/ue.d.ts:20565](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20565)

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

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[ExecuteUbergraph](ue_ue.AnimSequenceBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[GetClass](ue_ue.AnimSequenceBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[GetName](ue_ue.AnimSequenceBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[GetOuter](ue_ue.AnimSequenceBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetPlayLength

▸ **GetPlayLength**(): `number`

#### Returns

`number`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[GetPlayLength](ue_ue.AnimSequenceBase.md#getplaylength)

#### Defined in

[ue/ue.d.ts:3135](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3135)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[GetWorld](ue_ue.AnimSequenceBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimStreamable`](ue_ue.AnimStreamable.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimStreamable`](ue_ue.AnimStreamable.md)

#### Overrides

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[Find](ue_ue.AnimSequenceBase.md#find)

#### Defined in

[ue/ue.d.ts:20567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20567)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimStreamable`](ue_ue.AnimStreamable.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimStreamable`](ue_ue.AnimStreamable.md)

#### Overrides

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[Load](ue_ue.AnimSequenceBase.md#load)

#### Defined in

[ue/ue.d.ts:20568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20568)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[StaticClass](ue_ue.AnimSequenceBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:20566](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20566)
