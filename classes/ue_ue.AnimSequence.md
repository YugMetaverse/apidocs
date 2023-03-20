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

## Properties

### AdditiveAnimType

• **AdditiveAnimType**: [`EAdditiveAnimationType`](../enums/ue_ue.EAdditiveAnimationType.md)

___

### AnimNotifyTracks

• **AnimNotifyTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyTrack`](ue_ue.AnimNotifyTrack.md)\>

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[AnimNotifyTracks](ue_ue.AnimSequenceBase.md#animnotifytracks)

___

### AnimationTrackNames

• **AnimationTrackNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

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

### AuthoredSyncMarkers

• **AuthoredSyncMarkers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimSyncMarker`](ue_ue.AnimSyncMarker.md)\>

___

### ChildrenAssets

• **ChildrenAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationAsset`](ue_ue.AnimationAsset.md)\>

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[ChildrenAssets](ue_ue.AnimSequenceBase.md#childrenassets)

___

### CompressCommandletVersion

• **CompressCommandletVersion**: `number`

___

### CompressionErrorThresholdScale

• **CompressionErrorThresholdScale**: `number`

___

### CompressionScheme

• **CompressionScheme**: [`AnimCompress`](ue_ue.AnimCompress.md)

___

### CurveCompressionSettings

• **CurveCompressionSettings**: [`AnimCurveCompressionSettings`](ue_ue.AnimCurveCompressionSettings.md)

___

### ImportFileFramerate

• **ImportFileFramerate**: `number`

___

### ImportResampleFramerate

• **ImportResampleFramerate**: `number`

___

### Interpolation

• **Interpolation**: [`EAnimInterpolationType`](../enums/ue_ue.EAnimInterpolationType.md)

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

### NumFrames

• **NumFrames**: `number`

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

### RawDataGuid

• **RawDataGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### RefFrameIndex

• **RefFrameIndex**: `number`

___

### RefPoseSeq

• **RefPoseSeq**: [`AnimSequence`](ue_ue.AnimSequence.md)

___

### RefPoseType

• **RefPoseType**: [`EAdditiveBasePoseType`](../enums/ue_ue.EAdditiveBasePoseType.md)

___

### RetargetSource

• **RetargetSource**: `string`

___

### RootMotionRootLock

• **RootMotionRootLock**: [`ERootMotionRootLock`](../enums/ue_ue.ERootMotionRootLock.md)

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

### SourceFilePath

• **SourceFilePath**: `string`

___

### SourceFileTimestamp

• **SourceFileTimestamp**: `string`

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[ThumbnailInfo](ue_ue.AnimSequenceBase.md#thumbnailinfo)

___

### TrackToSkeletonMapTable

• **TrackToSkeletonMapTable**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TrackToSkeletonMap`](ue_ue.TrackToSkeletonMap.md)\>

___

### \_\_tid\_AnimSequenceBase\_\_

• **\_\_tid\_AnimSequenceBase\_\_**: `boolean`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[__tid_AnimSequenceBase__](ue_ue.AnimSequenceBase.md#__tid_animsequencebase__)

___

### \_\_tid\_AnimSequence\_\_

• **\_\_tid\_AnimSequence\_\_**: `boolean`

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

___

### bAllowFrameStripping

• **bAllowFrameStripping**: `boolean`

___

### bDoNotOverrideCompression

• **bDoNotOverrideCompression**: `boolean`

___

### bEnableRootMotion

• **bEnableRootMotion**: `boolean`

___

### bForceRootLock

• **bForceRootLock**: `boolean`

___

### bNeedsRebake

• **bNeedsRebake**: `boolean`

___

### bRootMotionSettingsCopiedFromMontage

• **bRootMotionSettingsCopiedFromMontage**: `boolean`

___

### bUseNormalizedRootMotionScale

• **bUseNormalizedRootMotionScale**: `boolean`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[StaticClass](ue_ue.AnimSequenceBase.md#staticclass)
