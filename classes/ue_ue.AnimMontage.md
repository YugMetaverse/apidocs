[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimMontage

# Class: AnimMontage

[ue/ue](../modules/ue_ue.md).AnimMontage

## Hierarchy

- [`AnimCompositeBase`](ue_ue.AnimCompositeBase.md)

  ↳ **`AnimMontage`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimMontage.md#constructor)

### Properties

- [AnimNotifyTracks](ue_ue.AnimMontage.md#animnotifytracks)
- [AssetMappingTable](ue_ue.AnimMontage.md#assetmappingtable)
- [AssetUserData](ue_ue.AnimMontage.md#assetuserdata)
- [BlendIn](ue_ue.AnimMontage.md#blendin)
- [BlendInTime](ue_ue.AnimMontage.md#blendintime)
- [BlendOut](ue_ue.AnimMontage.md#blendout)
- [BlendOutTime](ue_ue.AnimMontage.md#blendouttime)
- [BlendOutTriggerTime](ue_ue.AnimMontage.md#blendouttriggertime)
- [BranchingPointMarkers](ue_ue.AnimMontage.md#branchingpointmarkers)
- [BranchingPointStateNotifyIndices](ue_ue.AnimMontage.md#branchingpointstatenotifyindices)
- [BranchingPoints](ue_ue.AnimMontage.md#branchingpoints)
- [ChildrenAssets](ue_ue.AnimMontage.md#childrenassets)
- [CompositeSections](ue_ue.AnimMontage.md#compositesections)
- [MarkerData](ue_ue.AnimMontage.md#markerdata)
- [MetaData](ue_ue.AnimMontage.md#metadata)
- [Notifies](ue_ue.AnimMontage.md#notifies)
- [ParentAsset](ue_ue.AnimMontage.md#parentasset)
- [PreviewBasePose](ue_ue.AnimMontage.md#previewbasepose)
- [PreviewPoseAsset](ue_ue.AnimMontage.md#previewposeasset)
- [PreviewSkeletalMesh](ue_ue.AnimMontage.md#previewskeletalmesh)
- [RateScale](ue_ue.AnimMontage.md#ratescale)
- [RawCurveData](ue_ue.AnimMontage.md#rawcurvedata)
- [RootMotionRootLock](ue_ue.AnimMontage.md#rootmotionrootlock)
- [SequenceLength](ue_ue.AnimMontage.md#sequencelength)
- [Skeleton](ue_ue.AnimMontage.md#skeleton)
- [SlotAnimTracks](ue_ue.AnimMontage.md#slotanimtracks)
- [SyncGroup](ue_ue.AnimMontage.md#syncgroup)
- [SyncSlotIndex](ue_ue.AnimMontage.md#syncslotindex)
- [ThumbnailInfo](ue_ue.AnimMontage.md#thumbnailinfo)
- [TimeStretchCurve](ue_ue.AnimMontage.md#timestretchcurve)
- [TimeStretchCurveName](ue_ue.AnimMontage.md#timestretchcurvename)
- [\_\_tid\_AnimCompositeBase\_\_](ue_ue.AnimMontage.md#__tid_animcompositebase__)
- [\_\_tid\_AnimMontage\_\_](ue_ue.AnimMontage.md#__tid_animmontage__)
- [\_\_tid\_AnimSequenceBase\_\_](ue_ue.AnimMontage.md#__tid_animsequencebase__)
- [\_\_tid\_AnimationAsset\_\_](ue_ue.AnimMontage.md#__tid_animationasset__)
- [\_\_tid\_Object\_\_](ue_ue.AnimMontage.md#__tid_object__)
- [bEnableAutoBlendOut](ue_ue.AnimMontage.md#benableautoblendout)
- [bEnableRootMotionRotation](ue_ue.AnimMontage.md#benablerootmotionrotation)
- [bEnableRootMotionTranslation](ue_ue.AnimMontage.md#benablerootmotiontranslation)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimMontage.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimMontage.md#executeubergraph)
- [GetClass](ue_ue.AnimMontage.md#getclass)
- [GetDefaultBlendOutTime](ue_ue.AnimMontage.md#getdefaultblendouttime)
- [GetName](ue_ue.AnimMontage.md#getname)
- [GetOuter](ue_ue.AnimMontage.md#getouter)
- [GetPlayLength](ue_ue.AnimMontage.md#getplaylength)
- [GetWorld](ue_ue.AnimMontage.md#getworld)
- [Find](ue_ue.AnimMontage.md#find)
- [Load](ue_ue.AnimMontage.md#load)
- [StaticClass](ue_ue.AnimMontage.md#staticclass)

## Constructors

### constructor

• **new AnimMontage**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### BlendIn

• **BlendIn**: [`AlphaBlend`](ue_ue.AlphaBlend.md)

___

### BlendInTime

• **BlendInTime**: `number`

___

### BlendOut

• **BlendOut**: [`AlphaBlend`](ue_ue.AlphaBlend.md)

___

### BlendOutTime

• **BlendOutTime**: `number`

___

### BlendOutTriggerTime

• **BlendOutTriggerTime**: `number`

___

### BranchingPointMarkers

• **BranchingPointMarkers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BranchingPointMarker`](ue_ue.BranchingPointMarker.md)\>

___

### BranchingPointStateNotifyIndices

• **BranchingPointStateNotifyIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### BranchingPoints

• **BranchingPoints**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BranchingPoint`](ue_ue.BranchingPoint.md)\>

___

### ChildrenAssets

• **ChildrenAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationAsset`](ue_ue.AnimationAsset.md)\>

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[ChildrenAssets](ue_ue.AnimCompositeBase.md#childrenassets)

___

### CompositeSections

• **CompositeSections**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CompositeSection`](ue_ue.CompositeSection.md)\>

___

### MarkerData

• **MarkerData**: [`MarkerSyncData`](ue_ue.MarkerSyncData.md)

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

### RootMotionRootLock

• **RootMotionRootLock**: [`ERootMotionRootLock`](../enums/ue_ue.ERootMotionRootLock.md)

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

### SlotAnimTracks

• **SlotAnimTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SlotAnimationTrack`](ue_ue.SlotAnimationTrack.md)\>

___

### SyncGroup

• **SyncGroup**: `string`

___

### SyncSlotIndex

• **SyncSlotIndex**: `number`

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[ThumbnailInfo](ue_ue.AnimCompositeBase.md#thumbnailinfo)

___

### TimeStretchCurve

• **TimeStretchCurve**: [`TimeStretchCurve`](ue_ue.TimeStretchCurve.md)

___

### TimeStretchCurveName

• **TimeStretchCurveName**: `string`

___

### \_\_tid\_AnimCompositeBase\_\_

• **\_\_tid\_AnimCompositeBase\_\_**: `boolean`

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[__tid_AnimCompositeBase__](ue_ue.AnimCompositeBase.md#__tid_animcompositebase__)

___

### \_\_tid\_AnimMontage\_\_

• **\_\_tid\_AnimMontage\_\_**: `boolean`

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

___

### bEnableAutoBlendOut

• **bEnableAutoBlendOut**: `boolean`

___

### bEnableRootMotionRotation

• **bEnableRootMotionRotation**: `boolean`

___

### bEnableRootMotionTranslation

• **bEnableRootMotionTranslation**: `boolean`

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

### GetDefaultBlendOutTime

▸ **GetDefaultBlendOutTime**(): `number`

#### Returns

`number`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimMontage`](ue_ue.AnimMontage.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimMontage`](ue_ue.AnimMontage.md)

#### Overrides

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[Find](ue_ue.AnimCompositeBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimMontage`](ue_ue.AnimMontage.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimMontage`](ue_ue.AnimMontage.md)

#### Overrides

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[Load](ue_ue.AnimCompositeBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[StaticClass](ue_ue.AnimCompositeBase.md#staticclass)
