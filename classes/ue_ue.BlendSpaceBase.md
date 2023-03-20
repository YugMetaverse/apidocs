[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BlendSpaceBase

# Class: BlendSpaceBase

[ue/ue](../modules/ue_ue.md).BlendSpaceBase

## Hierarchy

- [`AnimationAsset`](ue_ue.AnimationAsset.md)

  ↳ **`BlendSpaceBase`**

  ↳↳ [`BlendSpace`](ue_ue.BlendSpace.md)

  ↳↳ [`BlendSpace1D`](ue_ue.BlendSpace1D.md)

## Table of contents

### Constructors

- [constructor](ue_ue.BlendSpaceBase.md#constructor)

### Properties

- [AnimLength](ue_ue.BlendSpaceBase.md#animlength)
- [AssetMappingTable](ue_ue.BlendSpaceBase.md#assetmappingtable)
- [AssetUserData](ue_ue.BlendSpaceBase.md#assetuserdata)
- [BlendParameters](ue_ue.BlendSpaceBase.md#blendparameters)
- [ChildrenAssets](ue_ue.BlendSpaceBase.md#childrenassets)
- [GridSamples](ue_ue.BlendSpaceBase.md#gridsamples)
- [InterpolationParam](ue_ue.BlendSpaceBase.md#interpolationparam)
- [MetaData](ue_ue.BlendSpaceBase.md#metadata)
- [NotifyTriggerMode](ue_ue.BlendSpaceBase.md#notifytriggermode)
- [ParentAsset](ue_ue.BlendSpaceBase.md#parentasset)
- [PerBoneBlend](ue_ue.BlendSpaceBase.md#perboneblend)
- [PreviewBasePose](ue_ue.BlendSpaceBase.md#previewbasepose)
- [PreviewPoseAsset](ue_ue.BlendSpaceBase.md#previewposeasset)
- [PreviewSkeletalMesh](ue_ue.BlendSpaceBase.md#previewskeletalmesh)
- [SampleData](ue_ue.BlendSpaceBase.md#sampledata)
- [SampleIndexWithMarkers](ue_ue.BlendSpaceBase.md#sampleindexwithmarkers)
- [Skeleton](ue_ue.BlendSpaceBase.md#skeleton)
- [TargetWeightInterpolationSpeedPerSec](ue_ue.BlendSpaceBase.md#targetweightinterpolationspeedpersec)
- [ThumbnailInfo](ue_ue.BlendSpaceBase.md#thumbnailinfo)
- [\_\_tid\_AnimationAsset\_\_](ue_ue.BlendSpaceBase.md#__tid_animationasset__)
- [\_\_tid\_BlendSpaceBase\_\_](ue_ue.BlendSpaceBase.md#__tid_blendspacebase__)
- [\_\_tid\_Object\_\_](ue_ue.BlendSpaceBase.md#__tid_object__)
- [bRotationBlendInMeshSpace](ue_ue.BlendSpaceBase.md#brotationblendinmeshspace)

### Methods

- [CreateDefaultSubobject](ue_ue.BlendSpaceBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BlendSpaceBase.md#executeubergraph)
- [GetClass](ue_ue.BlendSpaceBase.md#getclass)
- [GetName](ue_ue.BlendSpaceBase.md#getname)
- [GetOuter](ue_ue.BlendSpaceBase.md#getouter)
- [GetWorld](ue_ue.BlendSpaceBase.md#getworld)
- [Find](ue_ue.BlendSpaceBase.md#find)
- [Load](ue_ue.BlendSpaceBase.md#load)
- [StaticClass](ue_ue.BlendSpaceBase.md#staticclass)

## Constructors

### constructor

• **new BlendSpaceBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimationAsset](ue_ue.AnimationAsset.md).[constructor](ue_ue.AnimationAsset.md#constructor)

#### Defined in

[ue/ue.d.ts:15232](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15232)

## Properties

### AnimLength

• **AnimLength**: `number`

#### Defined in

[ue/ue.d.ts:15235](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15235)

___

### AssetMappingTable

• **AssetMappingTable**: [`AssetMappingTable`](ue_ue.AssetMappingTable.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[AssetMappingTable](ue_ue.AnimationAsset.md#assetmappingtable)

#### Defined in

[ue/ue.d.ts:2766](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2766)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[AssetUserData](ue_ue.AnimationAsset.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:2767](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2767)

___

### BlendParameters

• **BlendParameters**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`BlendParameter`](ue_ue.BlendParameter.md)\>

#### Defined in

[ue/ue.d.ts:15243](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15243)

___

### ChildrenAssets

• **ChildrenAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationAsset`](ue_ue.AnimationAsset.md)\>

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[ChildrenAssets](ue_ue.AnimationAsset.md#childrenassets)

#### Defined in

[ue/ue.d.ts:2765](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2765)

___

### GridSamples

• **GridSamples**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EditorElement`](ue_ue.EditorElement.md)\>

#### Defined in

[ue/ue.d.ts:15242](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15242)

___

### InterpolationParam

• **InterpolationParam**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`InterpolationParameter`](ue_ue.InterpolationParameter.md)\>

#### Defined in

[ue/ue.d.ts:15236](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15236)

___

### MetaData

• **MetaData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimMetaData`](ue_ue.AnimMetaData.md)\>

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[MetaData](ue_ue.AnimationAsset.md#metadata)

#### Defined in

[ue/ue.d.ts:2763](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2763)

___

### NotifyTriggerMode

• **NotifyTriggerMode**: [`ENotifyTriggerMode`](../enums/ue_ue.ENotifyTriggerMode.md)

#### Defined in

[ue/ue.d.ts:15238](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15238)

___

### ParentAsset

• **ParentAsset**: [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[ParentAsset](ue_ue.AnimationAsset.md#parentasset)

#### Defined in

[ue/ue.d.ts:2764](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2764)

___

### PerBoneBlend

• **PerBoneBlend**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PerBoneInterpolation`](ue_ue.PerBoneInterpolation.md)\>

#### Defined in

[ue/ue.d.ts:15239](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15239)

___

### PreviewBasePose

• **PreviewBasePose**: [`AnimSequence`](ue_ue.AnimSequence.md)

#### Defined in

[ue/ue.d.ts:15234](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15234)

___

### PreviewPoseAsset

• **PreviewPoseAsset**: [`PoseAsset`](ue_ue.PoseAsset.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[PreviewPoseAsset](ue_ue.AnimationAsset.md#previewposeasset)

#### Defined in

[ue/ue.d.ts:2769](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2769)

___

### PreviewSkeletalMesh

• **PreviewSkeletalMesh**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`SkeletalMesh`](ue_ue.SkeletalMesh.md)\>

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[PreviewSkeletalMesh](ue_ue.AnimationAsset.md#previewskeletalmesh)

#### Defined in

[ue/ue.d.ts:2770](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2770)

___

### SampleData

• **SampleData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlendSample`](ue_ue.BlendSample.md)\>

#### Defined in

[ue/ue.d.ts:15241](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15241)

___

### SampleIndexWithMarkers

• **SampleIndexWithMarkers**: `number`

#### Defined in

[ue/ue.d.ts:15240](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15240)

___

### Skeleton

• **Skeleton**: [`Skeleton`](ue_ue.Skeleton.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[Skeleton](ue_ue.AnimationAsset.md#skeleton)

#### Defined in

[ue/ue.d.ts:2762](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2762)

___

### TargetWeightInterpolationSpeedPerSec

• **TargetWeightInterpolationSpeedPerSec**: `number`

#### Defined in

[ue/ue.d.ts:15237](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15237)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[ThumbnailInfo](ue_ue.AnimationAsset.md#thumbnailinfo)

#### Defined in

[ue/ue.d.ts:2768](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2768)

___

### \_\_tid\_AnimationAsset\_\_

• **\_\_tid\_AnimationAsset\_\_**: `boolean`

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[__tid_AnimationAsset__](ue_ue.AnimationAsset.md#__tid_animationasset__)

#### Defined in

[ue/ue.d.ts:2775](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2775)

___

### \_\_tid\_BlendSpaceBase\_\_

• **\_\_tid\_BlendSpaceBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:15248](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15248)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[__tid_Object__](ue_ue.AnimationAsset.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bRotationBlendInMeshSpace

• **bRotationBlendInMeshSpace**: `boolean`

#### Defined in

[ue/ue.d.ts:15233](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15233)

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

[AnimationAsset](ue_ue.AnimationAsset.md).[ExecuteUbergraph](ue_ue.AnimationAsset.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[GetClass](ue_ue.AnimationAsset.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[GetName](ue_ue.AnimationAsset.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[GetOuter](ue_ue.AnimationAsset.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[GetWorld](ue_ue.AnimationAsset.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BlendSpaceBase`](ue_ue.BlendSpaceBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BlendSpaceBase`](ue_ue.BlendSpaceBase.md)

#### Overrides

[AnimationAsset](ue_ue.AnimationAsset.md).[Find](ue_ue.AnimationAsset.md#find)

#### Defined in

[ue/ue.d.ts:15245](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15245)

___

### Load

▸ `Static` **Load**(`InName`): [`BlendSpaceBase`](ue_ue.BlendSpaceBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BlendSpaceBase`](ue_ue.BlendSpaceBase.md)

#### Overrides

[AnimationAsset](ue_ue.AnimationAsset.md).[Load](ue_ue.AnimationAsset.md#load)

#### Defined in

[ue/ue.d.ts:15246](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15246)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimationAsset](ue_ue.AnimationAsset.md).[StaticClass](ue_ue.AnimationAsset.md#staticclass)

#### Defined in

[ue/ue.d.ts:15244](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15244)
