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

## Properties

### AnimLength

• **AnimLength**: `number`

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[AnimLength](ue_ue.BlendSpaceBase.md#animlength)

___

### AssetMappingTable

• **AssetMappingTable**: [`AssetMappingTable`](ue_ue.AssetMappingTable.md)

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[AssetMappingTable](ue_ue.BlendSpaceBase.md#assetmappingtable)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[AssetUserData](ue_ue.BlendSpaceBase.md#assetuserdata)

___

### BlendParameters

• **BlendParameters**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`BlendParameter`](ue_ue.BlendParameter.md)\>

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[BlendParameters](ue_ue.BlendSpaceBase.md#blendparameters)

___

### ChildrenAssets

• **ChildrenAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationAsset`](ue_ue.AnimationAsset.md)\>

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[ChildrenAssets](ue_ue.BlendSpaceBase.md#childrenassets)

___

### GridSamples

• **GridSamples**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EditorElement`](ue_ue.EditorElement.md)\>

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[GridSamples](ue_ue.BlendSpaceBase.md#gridsamples)

___

### InterpolationParam

• **InterpolationParam**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`InterpolationParameter`](ue_ue.InterpolationParameter.md)\>

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[InterpolationParam](ue_ue.BlendSpaceBase.md#interpolationparam)

___

### MetaData

• **MetaData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimMetaData`](ue_ue.AnimMetaData.md)\>

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[MetaData](ue_ue.BlendSpaceBase.md#metadata)

___

### NotifyTriggerMode

• **NotifyTriggerMode**: [`ENotifyTriggerMode`](../enums/ue_ue.ENotifyTriggerMode.md)

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[NotifyTriggerMode](ue_ue.BlendSpaceBase.md#notifytriggermode)

___

### ParentAsset

• **ParentAsset**: [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[ParentAsset](ue_ue.BlendSpaceBase.md#parentasset)

___

### PerBoneBlend

• **PerBoneBlend**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PerBoneInterpolation`](ue_ue.PerBoneInterpolation.md)\>

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[PerBoneBlend](ue_ue.BlendSpaceBase.md#perboneblend)

___

### PreviewBasePose

• **PreviewBasePose**: [`AnimSequence`](ue_ue.AnimSequence.md)

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[PreviewBasePose](ue_ue.BlendSpaceBase.md#previewbasepose)

___

### PreviewPoseAsset

• **PreviewPoseAsset**: [`PoseAsset`](ue_ue.PoseAsset.md)

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[PreviewPoseAsset](ue_ue.BlendSpaceBase.md#previewposeasset)

___

### PreviewSkeletalMesh

• **PreviewSkeletalMesh**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`SkeletalMesh`](ue_ue.SkeletalMesh.md)\>

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[PreviewSkeletalMesh](ue_ue.BlendSpaceBase.md#previewskeletalmesh)

___

### SampleData

• **SampleData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlendSample`](ue_ue.BlendSample.md)\>

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[SampleData](ue_ue.BlendSpaceBase.md#sampledata)

___

### SampleIndexWithMarkers

• **SampleIndexWithMarkers**: `number`

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[SampleIndexWithMarkers](ue_ue.BlendSpaceBase.md#sampleindexwithmarkers)

___

### Skeleton

• **Skeleton**: [`Skeleton`](ue_ue.Skeleton.md)

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[Skeleton](ue_ue.BlendSpaceBase.md#skeleton)

___

### TargetWeightInterpolationSpeedPerSec

• **TargetWeightInterpolationSpeedPerSec**: `number`

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[TargetWeightInterpolationSpeedPerSec](ue_ue.BlendSpaceBase.md#targetweightinterpolationspeedpersec)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[ThumbnailInfo](ue_ue.BlendSpaceBase.md#thumbnailinfo)

___

### \_\_tid\_AnimationAsset\_\_

• **\_\_tid\_AnimationAsset\_\_**: `boolean`

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[__tid_AnimationAsset__](ue_ue.BlendSpaceBase.md#__tid_animationasset__)

___

### \_\_tid\_BlendSpace1D\_\_

• **\_\_tid\_BlendSpace1D\_\_**: `boolean`

___

### \_\_tid\_BlendSpaceBase\_\_

• **\_\_tid\_BlendSpaceBase\_\_**: `boolean`

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[__tid_BlendSpaceBase__](ue_ue.BlendSpaceBase.md#__tid_blendspacebase__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[__tid_Object__](ue_ue.BlendSpaceBase.md#__tid_object__)

___

### bDisplayEditorVertically

• **bDisplayEditorVertically**: `boolean`

___

### bRotationBlendInMeshSpace

• **bRotationBlendInMeshSpace**: `boolean`

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[bRotationBlendInMeshSpace](ue_ue.BlendSpaceBase.md#brotationblendinmeshspace)

___

### bScaleAnimation

• **bScaleAnimation**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[GetClass](ue_ue.BlendSpaceBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[GetName](ue_ue.BlendSpaceBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[GetOuter](ue_ue.BlendSpaceBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[GetWorld](ue_ue.BlendSpaceBase.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlendSpaceBase](ue_ue.BlendSpaceBase.md).[StaticClass](ue_ue.BlendSpaceBase.md#staticclass)
