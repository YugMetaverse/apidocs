[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_LayeredBoneBlend

# Class: AnimNode\_LayeredBoneBlend

[ue/ue](../modules/ue_ue.md).AnimNode_LayeredBoneBlend

## Hierarchy

- [`AnimNode_Base`](ue_ue.AnimNode_Base.md)

  ↳ **`AnimNode_LayeredBoneBlend`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_LayeredBoneBlend.md#constructor)

### Properties

- [BasePose](ue_ue.AnimNode_LayeredBoneBlend.md#basepose)
- [BlendPoses](ue_ue.AnimNode_LayeredBoneBlend.md#blendposes)
- [BlendWeights](ue_ue.AnimNode_LayeredBoneBlend.md#blendweights)
- [CurveBlendOption](ue_ue.AnimNode_LayeredBoneBlend.md#curveblendoption)
- [LODThreshold](ue_ue.AnimNode_LayeredBoneBlend.md#lodthreshold)
- [LayerSetup](ue_ue.AnimNode_LayeredBoneBlend.md#layersetup)
- [PerBoneBlendWeights](ue_ue.AnimNode_LayeredBoneBlend.md#perboneblendweights)
- [SkeletonGuid](ue_ue.AnimNode_LayeredBoneBlend.md#skeletonguid)
- [VirtualBoneGuid](ue_ue.AnimNode_LayeredBoneBlend.md#virtualboneguid)
- [\_\_tid\_AnimNode\_LayeredBoneBlend\_\_](ue_ue.AnimNode_LayeredBoneBlend.md#__tid_animnode_layeredboneblend__)
- [bBlendRootMotionBasedOnRootBone](ue_ue.AnimNode_LayeredBoneBlend.md#bblendrootmotionbasedonrootbone)
- [bMeshSpaceRotationBlend](ue_ue.AnimNode_LayeredBoneBlend.md#bmeshspacerotationblend)
- [bMeshSpaceScaleBlend](ue_ue.AnimNode_LayeredBoneBlend.md#bmeshspacescaleblend)

### Methods

- [StaticClass](ue_ue.AnimNode_LayeredBoneBlend.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_LayeredBoneBlend.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_LayeredBoneBlend**()

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[constructor](ue_ue.AnimNode_Base.md#constructor)

• **new AnimNode_LayeredBoneBlend**(`BasePose`, `BlendPoses`, `LayerSetup`, `BlendWeights`, `bMeshSpaceRotationBlend`, `bMeshSpaceScaleBlend`, `CurveBlendOption`, `bBlendRootMotionBasedOnRootBone`, `LODThreshold`, `PerBoneBlendWeights`, `SkeletonGuid`, `VirtualBoneGuid`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BasePose` | [`PoseLink`](ue_ue.PoseLink.md) |
| `BlendPoses` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseLink`](ue_ue.PoseLink.md)\> |
| `LayerSetup` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InputBlendPose`](ue_ue.InputBlendPose.md)\> |
| `BlendWeights` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `bMeshSpaceRotationBlend` | `boolean` |
| `bMeshSpaceScaleBlend` | `boolean` |
| `CurveBlendOption` | [`ECurveBlendOption`](../enums/ue_ue.ECurveBlendOption.md) |
| `bBlendRootMotionBasedOnRootBone` | `boolean` |
| `LODThreshold` | `number` |
| `PerBoneBlendWeights` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PerBoneBlendWeight`](ue_ue.PerBoneBlendWeight.md)\> |
| `SkeletonGuid` | [`Guid`](ue_ue_s.Guid.md) |
| `VirtualBoneGuid` | [`Guid`](ue_ue_s.Guid.md) |

#### Overrides

UE.AnimNode\_Base.constructor

## Properties

### BasePose

• **BasePose**: [`PoseLink`](ue_ue.PoseLink.md)

___

### BlendPoses

• **BlendPoses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseLink`](ue_ue.PoseLink.md)\>

___

### BlendWeights

• **BlendWeights**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### CurveBlendOption

• **CurveBlendOption**: [`ECurveBlendOption`](../enums/ue_ue.ECurveBlendOption.md)

___

### LODThreshold

• **LODThreshold**: `number`

___

### LayerSetup

• **LayerSetup**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InputBlendPose`](ue_ue.InputBlendPose.md)\>

___

### PerBoneBlendWeights

• **PerBoneBlendWeights**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PerBoneBlendWeight`](ue_ue.PerBoneBlendWeight.md)\>

___

### SkeletonGuid

• **SkeletonGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### VirtualBoneGuid

• **VirtualBoneGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### \_\_tid\_AnimNode\_LayeredBoneBlend\_\_

• `Private` **\_\_tid\_AnimNode\_LayeredBoneBlend\_\_**: `boolean`

___

### bBlendRootMotionBasedOnRootBone

• **bBlendRootMotionBasedOnRootBone**: `boolean`

___

### bMeshSpaceRotationBlend

• **bMeshSpaceRotationBlend**: `boolean`

___

### bMeshSpaceScaleBlend

• **bMeshSpaceScaleBlend**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticClass](ue_ue.AnimNode_Base.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticStruct](ue_ue.AnimNode_Base.md#staticstruct)
