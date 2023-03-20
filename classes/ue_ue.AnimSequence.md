[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimSequence

# Class: AnimSequence

[ue/ue](../modules/ue_ue.md).AnimSequence

## Hierarchy

- [`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)

  ↳ **`AnimSequence`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimSequence.md#constructor)

### Properties

- [AdditiveAnimType](ue_ue.AnimSequence.md#additiveanimtype)
- [AnimNotifyTracks](ue_ue.AnimSequence.md#animnotifytracks)
- [AnimationTrackNames](ue_ue.AnimSequence.md#animationtracknames)
- [AssetImportData](ue_ue.AnimSequence.md#assetimportdata)
- [AssetMappingTable](ue_ue.AnimSequence.md#assetmappingtable)
- [AssetUserData](ue_ue.AnimSequence.md#assetuserdata)
- [AuthoredSyncMarkers](ue_ue.AnimSequence.md#authoredsyncmarkers)
- [ChildrenAssets](ue_ue.AnimSequence.md#childrenassets)
- [CompressCommandletVersion](ue_ue.AnimSequence.md#compresscommandletversion)
- [CompressionErrorThresholdScale](ue_ue.AnimSequence.md#compressionerrorthresholdscale)
- [CompressionScheme](ue_ue.AnimSequence.md#compressionscheme)
- [CurveCompressionSettings](ue_ue.AnimSequence.md#curvecompressionsettings)
- [ImportFileFramerate](ue_ue.AnimSequence.md#importfileframerate)
- [ImportResampleFramerate](ue_ue.AnimSequence.md#importresampleframerate)
- [Interpolation](ue_ue.AnimSequence.md#interpolation)
- [MetaData](ue_ue.AnimSequence.md#metadata)
- [Notifies](ue_ue.AnimSequence.md#notifies)
- [NumFrames](ue_ue.AnimSequence.md#numframes)
- [ParentAsset](ue_ue.AnimSequence.md#parentasset)
- [PreviewPoseAsset](ue_ue.AnimSequence.md#previewposeasset)
- [PreviewSkeletalMesh](ue_ue.AnimSequence.md#previewskeletalmesh)
- [RateScale](ue_ue.AnimSequence.md#ratescale)
- [RawCurveData](ue_ue.AnimSequence.md#rawcurvedata)
- [RawDataGuid](ue_ue.AnimSequence.md#rawdataguid)
- [RefFrameIndex](ue_ue.AnimSequence.md#refframeindex)
- [RefPoseSeq](ue_ue.AnimSequence.md#refposeseq)
- [RefPoseType](ue_ue.AnimSequence.md#refposetype)
- [RetargetSource](ue_ue.AnimSequence.md#retargetsource)
- [RootMotionRootLock](ue_ue.AnimSequence.md#rootmotionrootlock)
- [SequenceLength](ue_ue.AnimSequence.md#sequencelength)
- [Skeleton](ue_ue.AnimSequence.md#skeleton)
- [SourceFilePath](ue_ue.AnimSequence.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.AnimSequence.md#sourcefiletimestamp)
- [ThumbnailInfo](ue_ue.AnimSequence.md#thumbnailinfo)
- [TrackToSkeletonMapTable](ue_ue.AnimSequence.md#tracktoskeletonmaptable)
- [\_\_tid\_AnimSequenceBase\_\_](ue_ue.AnimSequence.md#__tid_animsequencebase__)
- [\_\_tid\_AnimSequence\_\_](ue_ue.AnimSequence.md#__tid_animsequence__)
- [\_\_tid\_AnimationAsset\_\_](ue_ue.AnimSequence.md#__tid_animationasset__)
- [\_\_tid\_Object\_\_](ue_ue.AnimSequence.md#__tid_object__)
- [bAllowFrameStripping](ue_ue.AnimSequence.md#ballowframestripping)
- [bDoNotOverrideCompression](ue_ue.AnimSequence.md#bdonotoverridecompression)
- [bEnableRootMotion](ue_ue.AnimSequence.md#benablerootmotion)
- [bForceRootLock](ue_ue.AnimSequence.md#bforcerootlock)
- [bNeedsRebake](ue_ue.AnimSequence.md#bneedsrebake)
- [bRootMotionSettingsCopiedFromMontage](ue_ue.AnimSequence.md#brootmotionsettingscopiedfrommontage)
- [bUseNormalizedRootMotionScale](ue_ue.AnimSequence.md#busenormalizedrootmotionscale)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimSequence.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimSequence.md#executeubergraph)
- [GetClass](ue_ue.AnimSequence.md#getclass)
- [GetName](ue_ue.AnimSequence.md#getname)
- [GetOuter](ue_ue.AnimSequence.md#getouter)
- [GetPlayLength](ue_ue.AnimSequence.md#getplaylength)
- [GetWorld](ue_ue.AnimSequence.md#getworld)
- [Find](ue_ue.AnimSequence.md#find)
- [Load](ue_ue.AnimSequence.md#load)
- [StaticClass](ue_ue.AnimSequence.md#staticclass)

## Constructors

### constructor

• **new AnimSequence**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[constructor](ue_ue.AnimSequenceBase.md#constructor)

#### Defined in

[ue/ue.d.ts:3197](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3197)

## Properties

### AdditiveAnimType

• **AdditiveAnimType**: [`EAdditiveAnimationType`](../enums/ue_ue.EAdditiveAnimationType.md)

#### Defined in

[ue/ue.d.ts:3208](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3208)

___

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

[ue/ue.d.ts:3203](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3203)

___

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Defined in

[ue/ue.d.ts:3221](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3221)

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

### AuthoredSyncMarkers

• **AuthoredSyncMarkers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimSyncMarker`](ue_ue.AnimSyncMarker.md)\>

#### Defined in

[ue/ue.d.ts:3225](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3225)

___

### ChildrenAssets

• **ChildrenAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationAsset`](ue_ue.AnimationAsset.md)\>

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[ChildrenAssets](ue_ue.AnimSequenceBase.md#childrenassets)

#### Defined in

[ue/ue.d.ts:2765](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2765)

___

### CompressCommandletVersion

• **CompressCommandletVersion**: `number`

#### Defined in

[ue/ue.d.ts:3219](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3219)

___

### CompressionErrorThresholdScale

• **CompressionErrorThresholdScale**: `number`

#### Defined in

[ue/ue.d.ts:3206](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3206)

___

### CompressionScheme

• **CompressionScheme**: [`AnimCompress`](ue_ue.AnimCompress.md)

#### Defined in

[ue/ue.d.ts:3204](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3204)

___

### CurveCompressionSettings

• **CurveCompressionSettings**: [`AnimCurveCompressionSettings`](ue_ue.AnimCurveCompressionSettings.md)

#### Defined in

[ue/ue.d.ts:3207](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3207)

___

### ImportFileFramerate

• **ImportFileFramerate**: `number`

#### Defined in

[ue/ue.d.ts:3198](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3198)

___

### ImportResampleFramerate

• **ImportResampleFramerate**: `number`

#### Defined in

[ue/ue.d.ts:3199](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3199)

___

### Interpolation

• **Interpolation**: [`EAnimInterpolationType`](../enums/ue_ue.EAnimInterpolationType.md)

#### Defined in

[ue/ue.d.ts:3213](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3213)

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

[ue/ue.d.ts:3200](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3200)

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

[ue/ue.d.ts:3202](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3202)

___

### RefFrameIndex

• **RefFrameIndex**: `number`

#### Defined in

[ue/ue.d.ts:3211](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3211)

___

### RefPoseSeq

• **RefPoseSeq**: [`AnimSequence`](ue_ue.AnimSequence.md)

#### Defined in

[ue/ue.d.ts:3210](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3210)

___

### RefPoseType

• **RefPoseType**: [`EAdditiveBasePoseType`](../enums/ue_ue.EAdditiveBasePoseType.md)

#### Defined in

[ue/ue.d.ts:3209](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3209)

___

### RetargetSource

• **RetargetSource**: `string`

#### Defined in

[ue/ue.d.ts:3212](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3212)

___

### RootMotionRootLock

• **RootMotionRootLock**: [`ERootMotionRootLock`](../enums/ue_ue.ERootMotionRootLock.md)

#### Defined in

[ue/ue.d.ts:3215](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3215)

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

### SourceFilePath

• **SourceFilePath**: `string`

#### Defined in

[ue/ue.d.ts:3222](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3222)

___

### SourceFileTimestamp

• **SourceFileTimestamp**: `string`

#### Defined in

[ue/ue.d.ts:3223](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3223)

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

[ue/ue.d.ts:3201](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3201)

___

### \_\_tid\_AnimSequenceBase\_\_

• **\_\_tid\_AnimSequenceBase\_\_**: `boolean`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[__tid_AnimSequenceBase__](ue_ue.AnimSequenceBase.md#__tid_animsequencebase__)

#### Defined in

[ue/ue.d.ts:3140](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3140)

___

### \_\_tid\_AnimSequence\_\_

• **\_\_tid\_AnimSequence\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:3230](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3230)

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

### bAllowFrameStripping

• **bAllowFrameStripping**: `boolean`

#### Defined in

[ue/ue.d.ts:3205](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3205)

___

### bDoNotOverrideCompression

• **bDoNotOverrideCompression**: `boolean`

#### Defined in

[ue/ue.d.ts:3220](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3220)

___

### bEnableRootMotion

• **bEnableRootMotion**: `boolean`

#### Defined in

[ue/ue.d.ts:3214](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3214)

___

### bForceRootLock

• **bForceRootLock**: `boolean`

#### Defined in

[ue/ue.d.ts:3216](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3216)

___

### bNeedsRebake

• **bNeedsRebake**: `boolean`

#### Defined in

[ue/ue.d.ts:3224](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3224)

___

### bRootMotionSettingsCopiedFromMontage

• **bRootMotionSettingsCopiedFromMontage**: `boolean`

#### Defined in

[ue/ue.d.ts:3218](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3218)

___

### bUseNormalizedRootMotionScale

• **bUseNormalizedRootMotionScale**: `boolean`

#### Defined in

[ue/ue.d.ts:3217](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3217)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimSequence`](ue_ue.AnimSequence.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimSequence`](ue_ue.AnimSequence.md)

#### Overrides

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[Find](ue_ue.AnimSequenceBase.md#find)

#### Defined in

[ue/ue.d.ts:3227](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3227)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimSequence`](ue_ue.AnimSequence.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimSequence`](ue_ue.AnimSequence.md)

#### Overrides

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[Load](ue_ue.AnimSequenceBase.md#load)

#### Defined in

[ue/ue.d.ts:3228](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3228)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[StaticClass](ue_ue.AnimSequenceBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:3226](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3226)
