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

#### Defined in

[ue/ue.d.ts:2956](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2956)

## Properties

### AnimNotifyTracks

• **AnimNotifyTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyTrack`](ue_ue.AnimNotifyTrack.md)\>

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[AnimNotifyTracks](ue_ue.AnimCompositeBase.md#animnotifytracks)

#### Defined in

[ue/ue.d.ts:3134](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3134)

___

### AssetMappingTable

• **AssetMappingTable**: [`AssetMappingTable`](ue_ue.AssetMappingTable.md)

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[AssetMappingTable](ue_ue.AnimCompositeBase.md#assetmappingtable)

#### Defined in

[ue/ue.d.ts:2766](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2766)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[AssetUserData](ue_ue.AnimCompositeBase.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:2767](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2767)

___

### BlendIn

• **BlendIn**: [`AlphaBlend`](ue_ue.AlphaBlend.md)

#### Defined in

[ue/ue.d.ts:2957](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2957)

___

### BlendInTime

• **BlendInTime**: `number`

#### Defined in

[ue/ue.d.ts:2958](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2958)

___

### BlendOut

• **BlendOut**: [`AlphaBlend`](ue_ue.AlphaBlend.md)

#### Defined in

[ue/ue.d.ts:2959](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2959)

___

### BlendOutTime

• **BlendOutTime**: `number`

#### Defined in

[ue/ue.d.ts:2960](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2960)

___

### BlendOutTriggerTime

• **BlendOutTriggerTime**: `number`

#### Defined in

[ue/ue.d.ts:2961](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2961)

___

### BranchingPointMarkers

• **BranchingPointMarkers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BranchingPointMarker`](ue_ue.BranchingPointMarker.md)\>

#### Defined in

[ue/ue.d.ts:2973](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2973)

___

### BranchingPointStateNotifyIndices

• **BranchingPointStateNotifyIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:2974](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2974)

___

### BranchingPoints

• **BranchingPoints**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BranchingPoint`](ue_ue.BranchingPoint.md)\>

#### Defined in

[ue/ue.d.ts:2967](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2967)

___

### ChildrenAssets

• **ChildrenAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationAsset`](ue_ue.AnimationAsset.md)\>

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[ChildrenAssets](ue_ue.AnimCompositeBase.md#childrenassets)

#### Defined in

[ue/ue.d.ts:2765](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2765)

___

### CompositeSections

• **CompositeSections**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CompositeSection`](ue_ue.CompositeSection.md)\>

#### Defined in

[ue/ue.d.ts:2965](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2965)

___

### MarkerData

• **MarkerData**: [`MarkerSyncData`](ue_ue.MarkerSyncData.md)

#### Defined in

[ue/ue.d.ts:2964](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2964)

___

### MetaData

• **MetaData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimMetaData`](ue_ue.AnimMetaData.md)\>

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[MetaData](ue_ue.AnimCompositeBase.md#metadata)

#### Defined in

[ue/ue.d.ts:2763](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2763)

___

### Notifies

• **Notifies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)\>

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[Notifies](ue_ue.AnimCompositeBase.md#notifies)

#### Defined in

[ue/ue.d.ts:3130](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3130)

___

### ParentAsset

• **ParentAsset**: [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[ParentAsset](ue_ue.AnimCompositeBase.md#parentasset)

#### Defined in

[ue/ue.d.ts:2764](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2764)

___

### PreviewBasePose

• **PreviewBasePose**: [`AnimSequence`](ue_ue.AnimSequence.md)

#### Defined in

[ue/ue.d.ts:2972](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2972)

___

### PreviewPoseAsset

• **PreviewPoseAsset**: [`PoseAsset`](ue_ue.PoseAsset.md)

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[PreviewPoseAsset](ue_ue.AnimCompositeBase.md#previewposeasset)

#### Defined in

[ue/ue.d.ts:2769](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2769)

___

### PreviewSkeletalMesh

• **PreviewSkeletalMesh**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`SkeletalMesh`](ue_ue.SkeletalMesh.md)\>

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[PreviewSkeletalMesh](ue_ue.AnimCompositeBase.md#previewskeletalmesh)

#### Defined in

[ue/ue.d.ts:2770](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2770)

___

### RateScale

• **RateScale**: `number`

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[RateScale](ue_ue.AnimCompositeBase.md#ratescale)

#### Defined in

[ue/ue.d.ts:3132](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3132)

___

### RawCurveData

• **RawCurveData**: [`RawCurveTracks`](ue_ue.RawCurveTracks.md)

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[RawCurveData](ue_ue.AnimCompositeBase.md#rawcurvedata)

#### Defined in

[ue/ue.d.ts:3133](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3133)

___

### RootMotionRootLock

• **RootMotionRootLock**: [`ERootMotionRootLock`](../enums/ue_ue.ERootMotionRootLock.md)

#### Defined in

[ue/ue.d.ts:2971](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2971)

___

### SequenceLength

• **SequenceLength**: `number`

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[SequenceLength](ue_ue.AnimCompositeBase.md#sequencelength)

#### Defined in

[ue/ue.d.ts:3131](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3131)

___

### Skeleton

• **Skeleton**: [`Skeleton`](ue_ue.Skeleton.md)

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[Skeleton](ue_ue.AnimCompositeBase.md#skeleton)

#### Defined in

[ue/ue.d.ts:2762](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2762)

___

### SlotAnimTracks

• **SlotAnimTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SlotAnimationTrack`](ue_ue.SlotAnimationTrack.md)\>

#### Defined in

[ue/ue.d.ts:2966](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2966)

___

### SyncGroup

• **SyncGroup**: `string`

#### Defined in

[ue/ue.d.ts:2962](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2962)

___

### SyncSlotIndex

• **SyncSlotIndex**: `number`

#### Defined in

[ue/ue.d.ts:2963](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2963)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[ThumbnailInfo](ue_ue.AnimCompositeBase.md#thumbnailinfo)

#### Defined in

[ue/ue.d.ts:2768](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2768)

___

### TimeStretchCurve

• **TimeStretchCurve**: [`TimeStretchCurve`](ue_ue.TimeStretchCurve.md)

#### Defined in

[ue/ue.d.ts:2975](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2975)

___

### TimeStretchCurveName

• **TimeStretchCurveName**: `string`

#### Defined in

[ue/ue.d.ts:2976](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2976)

___

### \_\_tid\_AnimCompositeBase\_\_

• **\_\_tid\_AnimCompositeBase\_\_**: `boolean`

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[__tid_AnimCompositeBase__](ue_ue.AnimCompositeBase.md#__tid_animcompositebase__)

#### Defined in

[ue/ue.d.ts:2784](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2784)

___

### \_\_tid\_AnimMontage\_\_

• **\_\_tid\_AnimMontage\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:2982](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2982)

___

### \_\_tid\_AnimSequenceBase\_\_

• **\_\_tid\_AnimSequenceBase\_\_**: `boolean`

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[__tid_AnimSequenceBase__](ue_ue.AnimCompositeBase.md#__tid_animsequencebase__)

#### Defined in

[ue/ue.d.ts:3140](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3140)

___

### \_\_tid\_AnimationAsset\_\_

• **\_\_tid\_AnimationAsset\_\_**: `boolean`

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[__tid_AnimationAsset__](ue_ue.AnimCompositeBase.md#__tid_animationasset__)

#### Defined in

[ue/ue.d.ts:2775](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2775)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[__tid_Object__](ue_ue.AnimCompositeBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bEnableAutoBlendOut

• **bEnableAutoBlendOut**: `boolean`

#### Defined in

[ue/ue.d.ts:2970](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2970)

___

### bEnableRootMotionRotation

• **bEnableRootMotionRotation**: `boolean`

#### Defined in

[ue/ue.d.ts:2969](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2969)

___

### bEnableRootMotionTranslation

• **bEnableRootMotionTranslation**: `boolean`

#### Defined in

[ue/ue.d.ts:2968](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2968)

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

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[ExecuteUbergraph](ue_ue.AnimCompositeBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[GetClass](ue_ue.AnimCompositeBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetDefaultBlendOutTime

▸ **GetDefaultBlendOutTime**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:2977](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2977)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[GetName](ue_ue.AnimCompositeBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[GetOuter](ue_ue.AnimCompositeBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetPlayLength

▸ **GetPlayLength**(): `number`

#### Returns

`number`

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[GetPlayLength](ue_ue.AnimCompositeBase.md#getplaylength)

#### Defined in

[ue/ue.d.ts:3135](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3135)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[GetWorld](ue_ue.AnimCompositeBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:2979](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2979)

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

#### Defined in

[ue/ue.d.ts:2980](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2980)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimCompositeBase](ue_ue.AnimCompositeBase.md).[StaticClass](ue_ue.AnimCompositeBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:2978](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2978)
