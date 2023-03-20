[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BlendSpace1D

# Class: BlendSpace1D

[ue/ue](../modules/ue_ue.md).BlendSpace1D

## Hierarchy

- [`BlendSpaceBase`](ue_ue.BlendSpaceBase.md)

  ↳ **`BlendSpace1D`**

  ↳↳ [`AimOffsetBlendSpace1D`](ue_ue.AimOffsetBlendSpace1D.md)

## Table of contents

### Constructors

- [constructor](ue_ue.BlendSpace1D.md#constructor)

### Properties

- [AnimLength](ue_ue.BlendSpace1D.md#animlength)
- [AssetMappingTable](ue_ue.BlendSpace1D.md#assetmappingtable)
- [AssetUserData](ue_ue.BlendSpace1D.md#assetuserdata)
- [BlendParameters](ue_ue.BlendSpace1D.md#blendparameters)
- [ChildrenAssets](ue_ue.BlendSpace1D.md#childrenassets)
- [GridSamples](ue_ue.BlendSpace1D.md#gridsamples)
- [InterpolationParam](ue_ue.BlendSpace1D.md#interpolationparam)
- [MetaData](ue_ue.BlendSpace1D.md#metadata)
- [NotifyTriggerMode](ue_ue.BlendSpace1D.md#notifytriggermode)
- [ParentAsset](ue_ue.BlendSpace1D.md#parentasset)
- [PerBoneBlend](ue_ue.BlendSpace1D.md#perboneblend)
- [PreviewBasePose](ue_ue.BlendSpace1D.md#previewbasepose)
- [PreviewPoseAsset](ue_ue.BlendSpace1D.md#previewposeasset)
- [PreviewSkeletalMesh](ue_ue.BlendSpace1D.md#previewskeletalmesh)
- [SampleData](ue_ue.BlendSpace1D.md#sampledata)
- [SampleIndexWithMarkers](ue_ue.BlendSpace1D.md#sampleindexwithmarkers)
- [Skeleton](ue_ue.BlendSpace1D.md#skeleton)
- [TargetWeightInterpolationSpeedPerSec](ue_ue.BlendSpace1D.md#targetweightinterpolationspeedpersec)
- [ThumbnailInfo](ue_ue.BlendSpace1D.md#thumbnailinfo)
- [\_\_tid\_AnimationAsset\_\_](ue_ue.BlendSpace1D.md#__tid_animationasset__)
- [\_\_tid\_BlendSpace1D\_\_](ue_ue.BlendSpace1D.md#__tid_blendspace1d__)
- [\_\_tid\_BlendSpaceBase\_\_](ue_ue.BlendSpace1D.md#__tid_blendspacebase__)
- [\_\_tid\_Object\_\_](ue_ue.BlendSpace1D.md#__tid_object__)
- [bDisplayEditorVertically](ue_ue.BlendSpace1D.md#bdisplayeditorvertically)
- [bRotationBlendInMeshSpace](ue_ue.BlendSpace1D.md#brotationblendinmeshspace)
- [bScaleAnimation](ue_ue.BlendSpace1D.md#bscaleanimation)

### Methods

- [CreateDefaultSubobject](ue_ue.BlendSpace1D.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BlendSpace1D.md#executeubergraph)
- [GetClass](ue_ue.BlendSpace1D.md#getclass)
- [GetName](ue_ue.BlendSpace1D.md#getname)
- [GetOuter](ue_ue.BlendSpace1D.md#getouter)
- [GetWorld](ue_ue.BlendSpace1D.md#getworld)
- [Find](ue_ue.BlendSpace1D.md#find)
- [Load](ue_ue.BlendSpace1D.md#load)
- [StaticClass](ue_ue.BlendSpace1D.md#staticclass)

## Constructors

### constructor

• **new BlendSpace1D**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[constructor](ue_ue.BlendSpaceBase.md#constructor)

#### Defined in

[ue/ue.d.ts:15272](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15272)

## Properties

### AnimLength

• **AnimLength**: `number`

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[AnimLength](ue_ue.BlendSpaceBase.md#animlength)

#### Defined in

[ue/ue.d.ts:15235](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15235)

___

### AssetMappingTable

• **AssetMappingTable**: [`AssetMappingTable`](ue_ue.AssetMappingTable.md)

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[AssetMappingTable](ue_ue.BlendSpaceBase.md#assetmappingtable)

#### Defined in

[ue/ue.d.ts:2766](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2766)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[AssetUserData](ue_ue.BlendSpaceBase.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:2767](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2767)

___

### BlendParameters

• **BlendParameters**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`BlendParameter`](ue_ue.BlendParameter.md)\>

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[BlendParameters](ue_ue.BlendSpaceBase.md#blendparameters)

#### Defined in

[ue/ue.d.ts:15243](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15243)

___

### ChildrenAssets

• **ChildrenAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationAsset`](ue_ue.AnimationAsset.md)\>

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[ChildrenAssets](ue_ue.BlendSpaceBase.md#childrenassets)

#### Defined in

[ue/ue.d.ts:2765](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2765)

___

### GridSamples

• **GridSamples**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EditorElement`](ue_ue.EditorElement.md)\>

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[GridSamples](ue_ue.BlendSpaceBase.md#gridsamples)

#### Defined in

[ue/ue.d.ts:15242](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15242)

___

### InterpolationParam

• **InterpolationParam**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`InterpolationParameter`](ue_ue.InterpolationParameter.md)\>

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[InterpolationParam](ue_ue.BlendSpaceBase.md#interpolationparam)

#### Defined in

[ue/ue.d.ts:15236](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15236)

___

### MetaData

• **MetaData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimMetaData`](ue_ue.AnimMetaData.md)\>

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[MetaData](ue_ue.BlendSpaceBase.md#metadata)

#### Defined in

[ue/ue.d.ts:2763](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2763)

___

### NotifyTriggerMode

• **NotifyTriggerMode**: [`ENotifyTriggerMode`](../enums/ue_ue.ENotifyTriggerMode.md)

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[NotifyTriggerMode](ue_ue.BlendSpaceBase.md#notifytriggermode)

#### Defined in

[ue/ue.d.ts:15238](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15238)

___

### ParentAsset

• **ParentAsset**: [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[ParentAsset](ue_ue.BlendSpaceBase.md#parentasset)

#### Defined in

[ue/ue.d.ts:2764](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2764)

___

### PerBoneBlend

• **PerBoneBlend**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PerBoneInterpolation`](ue_ue.PerBoneInterpolation.md)\>

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[PerBoneBlend](ue_ue.BlendSpaceBase.md#perboneblend)

#### Defined in

[ue/ue.d.ts:15239](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15239)

___

### PreviewBasePose

• **PreviewBasePose**: [`AnimSequence`](ue_ue.AnimSequence.md)

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[PreviewBasePose](ue_ue.BlendSpaceBase.md#previewbasepose)

#### Defined in

[ue/ue.d.ts:15234](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15234)

___

### PreviewPoseAsset

• **PreviewPoseAsset**: [`PoseAsset`](ue_ue.PoseAsset.md)

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[PreviewPoseAsset](ue_ue.BlendSpaceBase.md#previewposeasset)

#### Defined in

[ue/ue.d.ts:2769](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2769)

___

### PreviewSkeletalMesh

• **PreviewSkeletalMesh**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`SkeletalMesh`](ue_ue.SkeletalMesh.md)\>

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[PreviewSkeletalMesh](ue_ue.BlendSpaceBase.md#previewskeletalmesh)

#### Defined in

[ue/ue.d.ts:2770](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2770)

___

### SampleData

• **SampleData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlendSample`](ue_ue.BlendSample.md)\>

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[SampleData](ue_ue.BlendSpaceBase.md#sampledata)

#### Defined in

[ue/ue.d.ts:15241](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15241)

___

### SampleIndexWithMarkers

• **SampleIndexWithMarkers**: `number`

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[SampleIndexWithMarkers](ue_ue.BlendSpaceBase.md#sampleindexwithmarkers)

#### Defined in

[ue/ue.d.ts:15240](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15240)

___

### Skeleton

• **Skeleton**: [`Skeleton`](ue_ue.Skeleton.md)

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[Skeleton](ue_ue.BlendSpaceBase.md#skeleton)

#### Defined in

[ue/ue.d.ts:2762](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2762)

___

### TargetWeightInterpolationSpeedPerSec

• **TargetWeightInterpolationSpeedPerSec**: `number`

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[TargetWeightInterpolationSpeedPerSec](ue_ue.BlendSpaceBase.md#targetweightinterpolationspeedpersec)

#### Defined in

[ue/ue.d.ts:15237](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15237)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[ThumbnailInfo](ue_ue.BlendSpaceBase.md#thumbnailinfo)

#### Defined in

[ue/ue.d.ts:2768](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2768)

___

### \_\_tid\_AnimationAsset\_\_

• **\_\_tid\_AnimationAsset\_\_**: `boolean`

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[__tid_AnimationAsset__](ue_ue.BlendSpaceBase.md#__tid_animationasset__)

#### Defined in

[ue/ue.d.ts:2775](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2775)

___

### \_\_tid\_BlendSpace1D\_\_

• **\_\_tid\_BlendSpace1D\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:15279](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15279)

___

### \_\_tid\_BlendSpaceBase\_\_

• **\_\_tid\_BlendSpaceBase\_\_**: `boolean`

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[__tid_BlendSpaceBase__](ue_ue.BlendSpaceBase.md#__tid_blendspacebase__)

#### Defined in

[ue/ue.d.ts:15248](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15248)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[__tid_Object__](ue_ue.BlendSpaceBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bDisplayEditorVertically

• **bDisplayEditorVertically**: `boolean`

#### Defined in

[ue/ue.d.ts:15273](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15273)

___

### bRotationBlendInMeshSpace

• **bRotationBlendInMeshSpace**: `boolean`

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[bRotationBlendInMeshSpace](ue_ue.BlendSpaceBase.md#brotationblendinmeshspace)

#### Defined in

[ue/ue.d.ts:15233](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15233)

___

### bScaleAnimation

• **bScaleAnimation**: `boolean`

#### Defined in

[ue/ue.d.ts:15274](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15274)

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

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[CreateDefaultSubobject](ue_ue.BlendSpaceBase.md#createdefaultsubobject)

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

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[ExecuteUbergraph](ue_ue.BlendSpaceBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[GetClass](ue_ue.BlendSpaceBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[GetName](ue_ue.BlendSpaceBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[GetOuter](ue_ue.BlendSpaceBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[GetWorld](ue_ue.BlendSpaceBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BlendSpace1D`](ue_ue.BlendSpace1D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BlendSpace1D`](ue_ue.BlendSpace1D.md)

#### Overrides

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[Find](ue_ue.BlendSpaceBase.md#find)

#### Defined in

[ue/ue.d.ts:15276](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15276)

___

### Load

▸ `Static` **Load**(`InName`): [`BlendSpace1D`](ue_ue.BlendSpace1D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BlendSpace1D`](ue_ue.BlendSpace1D.md)

#### Overrides

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[Load](ue_ue.BlendSpaceBase.md#load)

#### Defined in

[ue/ue.d.ts:15277](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15277)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[StaticClass](ue_ue.BlendSpaceBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:15275](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15275)
