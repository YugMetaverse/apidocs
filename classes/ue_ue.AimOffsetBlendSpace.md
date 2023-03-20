[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AimOffsetBlendSpace

# Class: AimOffsetBlendSpace

[ue/ue](../modules/ue_ue.md).AimOffsetBlendSpace

## Hierarchy

- [`BlendSpace`](ue_ue.BlendSpace.md)

  ↳ **`AimOffsetBlendSpace`**

## Table of contents

### Constructors

- [constructor](ue_ue.AimOffsetBlendSpace.md#constructor)

### Properties

- [AnimLength](ue_ue.AimOffsetBlendSpace.md#animlength)
- [AssetMappingTable](ue_ue.AimOffsetBlendSpace.md#assetmappingtable)
- [AssetUserData](ue_ue.AimOffsetBlendSpace.md#assetuserdata)
- [AxisToScaleAnimation](ue_ue.AimOffsetBlendSpace.md#axistoscaleanimation)
- [BlendParameters](ue_ue.AimOffsetBlendSpace.md#blendparameters)
- [ChildrenAssets](ue_ue.AimOffsetBlendSpace.md#childrenassets)
- [GridSamples](ue_ue.AimOffsetBlendSpace.md#gridsamples)
- [InterpolationParam](ue_ue.AimOffsetBlendSpace.md#interpolationparam)
- [MetaData](ue_ue.AimOffsetBlendSpace.md#metadata)
- [NotifyTriggerMode](ue_ue.AimOffsetBlendSpace.md#notifytriggermode)
- [ParentAsset](ue_ue.AimOffsetBlendSpace.md#parentasset)
- [PerBoneBlend](ue_ue.AimOffsetBlendSpace.md#perboneblend)
- [PreviewBasePose](ue_ue.AimOffsetBlendSpace.md#previewbasepose)
- [PreviewPoseAsset](ue_ue.AimOffsetBlendSpace.md#previewposeasset)
- [PreviewSkeletalMesh](ue_ue.AimOffsetBlendSpace.md#previewskeletalmesh)
- [SampleData](ue_ue.AimOffsetBlendSpace.md#sampledata)
- [SampleIndexWithMarkers](ue_ue.AimOffsetBlendSpace.md#sampleindexwithmarkers)
- [Skeleton](ue_ue.AimOffsetBlendSpace.md#skeleton)
- [TargetWeightInterpolationSpeedPerSec](ue_ue.AimOffsetBlendSpace.md#targetweightinterpolationspeedpersec)
- [ThumbnailInfo](ue_ue.AimOffsetBlendSpace.md#thumbnailinfo)
- [\_\_tid\_AimOffsetBlendSpace\_\_](ue_ue.AimOffsetBlendSpace.md#__tid_aimoffsetblendspace__)
- [\_\_tid\_AnimationAsset\_\_](ue_ue.AimOffsetBlendSpace.md#__tid_animationasset__)
- [\_\_tid\_BlendSpaceBase\_\_](ue_ue.AimOffsetBlendSpace.md#__tid_blendspacebase__)
- [\_\_tid\_BlendSpace\_\_](ue_ue.AimOffsetBlendSpace.md#__tid_blendspace__)
- [\_\_tid\_Object\_\_](ue_ue.AimOffsetBlendSpace.md#__tid_object__)
- [bRotationBlendInMeshSpace](ue_ue.AimOffsetBlendSpace.md#brotationblendinmeshspace)

### Methods

- [CreateDefaultSubobject](ue_ue.AimOffsetBlendSpace.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AimOffsetBlendSpace.md#executeubergraph)
- [GetClass](ue_ue.AimOffsetBlendSpace.md#getclass)
- [GetName](ue_ue.AimOffsetBlendSpace.md#getname)
- [GetOuter](ue_ue.AimOffsetBlendSpace.md#getouter)
- [GetWorld](ue_ue.AimOffsetBlendSpace.md#getworld)
- [Find](ue_ue.AimOffsetBlendSpace.md#find)
- [Load](ue_ue.AimOffsetBlendSpace.md#load)
- [StaticClass](ue_ue.AimOffsetBlendSpace.md#staticclass)

## Constructors

### constructor

• **new AimOffsetBlendSpace**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlendSpace](ue_ue.BlendSpace.md).[constructor](ue_ue.BlendSpace.md#constructor)

## Properties

### AnimLength

• **AnimLength**: `number`

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[AnimLength](ue_ue.BlendSpace.md#animlength)

___

### AssetMappingTable

• **AssetMappingTable**: [`AssetMappingTable`](ue_ue.AssetMappingTable.md)

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[AssetMappingTable](ue_ue.BlendSpace.md#assetmappingtable)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[AssetUserData](ue_ue.BlendSpace.md#assetuserdata)

___

### AxisToScaleAnimation

• **AxisToScaleAnimation**: [`EBlendSpaceAxis`](../enums/ue_ue.EBlendSpaceAxis.md)

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[AxisToScaleAnimation](ue_ue.BlendSpace.md#axistoscaleanimation)

___

### BlendParameters

• **BlendParameters**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`BlendParameter`](ue_ue.BlendParameter.md)\>

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[BlendParameters](ue_ue.BlendSpace.md#blendparameters)

___

### ChildrenAssets

• **ChildrenAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationAsset`](ue_ue.AnimationAsset.md)\>

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[ChildrenAssets](ue_ue.BlendSpace.md#childrenassets)

___

### GridSamples

• **GridSamples**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EditorElement`](ue_ue.EditorElement.md)\>

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[GridSamples](ue_ue.BlendSpace.md#gridsamples)

___

### InterpolationParam

• **InterpolationParam**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`InterpolationParameter`](ue_ue.InterpolationParameter.md)\>

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[InterpolationParam](ue_ue.BlendSpace.md#interpolationparam)

___

### MetaData

• **MetaData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimMetaData`](ue_ue.AnimMetaData.md)\>

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[MetaData](ue_ue.BlendSpace.md#metadata)

___

### NotifyTriggerMode

• **NotifyTriggerMode**: [`ENotifyTriggerMode`](../enums/ue_ue.ENotifyTriggerMode.md)

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[NotifyTriggerMode](ue_ue.BlendSpace.md#notifytriggermode)

___

### ParentAsset

• **ParentAsset**: [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[ParentAsset](ue_ue.BlendSpace.md#parentasset)

___

### PerBoneBlend

• **PerBoneBlend**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PerBoneInterpolation`](ue_ue.PerBoneInterpolation.md)\>

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[PerBoneBlend](ue_ue.BlendSpace.md#perboneblend)

___

### PreviewBasePose

• **PreviewBasePose**: [`AnimSequence`](ue_ue.AnimSequence.md)

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[PreviewBasePose](ue_ue.BlendSpace.md#previewbasepose)

___

### PreviewPoseAsset

• **PreviewPoseAsset**: [`PoseAsset`](ue_ue.PoseAsset.md)

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[PreviewPoseAsset](ue_ue.BlendSpace.md#previewposeasset)

___

### PreviewSkeletalMesh

• **PreviewSkeletalMesh**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`SkeletalMesh`](ue_ue.SkeletalMesh.md)\>

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[PreviewSkeletalMesh](ue_ue.BlendSpace.md#previewskeletalmesh)

___

### SampleData

• **SampleData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlendSample`](ue_ue.BlendSample.md)\>

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[SampleData](ue_ue.BlendSpace.md#sampledata)

___

### SampleIndexWithMarkers

• **SampleIndexWithMarkers**: `number`

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[SampleIndexWithMarkers](ue_ue.BlendSpace.md#sampleindexwithmarkers)

___

### Skeleton

• **Skeleton**: [`Skeleton`](ue_ue.Skeleton.md)

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[Skeleton](ue_ue.BlendSpace.md#skeleton)

___

### TargetWeightInterpolationSpeedPerSec

• **TargetWeightInterpolationSpeedPerSec**: `number`

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[TargetWeightInterpolationSpeedPerSec](ue_ue.BlendSpace.md#targetweightinterpolationspeedpersec)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[ThumbnailInfo](ue_ue.BlendSpace.md#thumbnailinfo)

___

### \_\_tid\_AimOffsetBlendSpace\_\_

• **\_\_tid\_AimOffsetBlendSpace\_\_**: `boolean`

___

### \_\_tid\_AnimationAsset\_\_

• **\_\_tid\_AnimationAsset\_\_**: `boolean`

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[__tid_AnimationAsset__](ue_ue.BlendSpace.md#__tid_animationasset__)

___

### \_\_tid\_BlendSpaceBase\_\_

• **\_\_tid\_BlendSpaceBase\_\_**: `boolean`

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[__tid_BlendSpaceBase__](ue_ue.BlendSpace.md#__tid_blendspacebase__)

___

### \_\_tid\_BlendSpace\_\_

• **\_\_tid\_BlendSpace\_\_**: `boolean`

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[__tid_BlendSpace__](ue_ue.BlendSpace.md#__tid_blendspace__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[__tid_Object__](ue_ue.BlendSpace.md#__tid_object__)

___

### bRotationBlendInMeshSpace

• **bRotationBlendInMeshSpace**: `boolean`

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[bRotationBlendInMeshSpace](ue_ue.BlendSpace.md#brotationblendinmeshspace)

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

[BlendSpace](ue_ue.BlendSpace.md).[CreateDefaultSubobject](ue_ue.BlendSpace.md#createdefaultsubobject)

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

[BlendSpace](ue_ue.BlendSpace.md).[ExecuteUbergraph](ue_ue.BlendSpace.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[GetClass](ue_ue.BlendSpace.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[GetName](ue_ue.BlendSpace.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[GetOuter](ue_ue.BlendSpace.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlendSpace](ue_ue.BlendSpace.md).[GetWorld](ue_ue.BlendSpace.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AimOffsetBlendSpace`](ue_ue.AimOffsetBlendSpace.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AimOffsetBlendSpace`](ue_ue.AimOffsetBlendSpace.md)

#### Overrides

[BlendSpace](ue_ue.BlendSpace.md).[Find](ue_ue.BlendSpace.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AimOffsetBlendSpace`](ue_ue.AimOffsetBlendSpace.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AimOffsetBlendSpace`](ue_ue.AimOffsetBlendSpace.md)

#### Overrides

[BlendSpace](ue_ue.BlendSpace.md).[Load](ue_ue.BlendSpace.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlendSpace](ue_ue.BlendSpace.md).[StaticClass](ue_ue.BlendSpace.md#staticclass)
