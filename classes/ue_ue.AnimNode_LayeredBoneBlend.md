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

#### Defined in

[ue/ue.d.ts:18631](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18631)

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

#### Defined in

[ue/ue.d.ts:18632](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18632)

## Properties

### BasePose

• **BasePose**: [`PoseLink`](ue_ue.PoseLink.md)

#### Defined in

[ue/ue.d.ts:18633](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18633)

___

### BlendPoses

• **BlendPoses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseLink`](ue_ue.PoseLink.md)\>

#### Defined in

[ue/ue.d.ts:18634](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18634)

___

### BlendWeights

• **BlendWeights**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:18636](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18636)

___

### CurveBlendOption

• **CurveBlendOption**: [`ECurveBlendOption`](../enums/ue_ue.ECurveBlendOption.md)

#### Defined in

[ue/ue.d.ts:18639](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18639)

___

### LODThreshold

• **LODThreshold**: `number`

#### Defined in

[ue/ue.d.ts:18641](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18641)

___

### LayerSetup

• **LayerSetup**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InputBlendPose`](ue_ue.InputBlendPose.md)\>

#### Defined in

[ue/ue.d.ts:18635](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18635)

___

### PerBoneBlendWeights

• **PerBoneBlendWeights**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PerBoneBlendWeight`](ue_ue.PerBoneBlendWeight.md)\>

#### Defined in

[ue/ue.d.ts:18642](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18642)

___

### SkeletonGuid

• **SkeletonGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:18643](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18643)

___

### VirtualBoneGuid

• **VirtualBoneGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:18644](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18644)

___

### \_\_tid\_AnimNode\_LayeredBoneBlend\_\_

• `Private` **\_\_tid\_AnimNode\_LayeredBoneBlend\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:18650](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18650)

___

### bBlendRootMotionBasedOnRootBone

• **bBlendRootMotionBasedOnRootBone**: `boolean`

#### Defined in

[ue/ue.d.ts:18640](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18640)

___

### bMeshSpaceRotationBlend

• **bMeshSpaceRotationBlend**: `boolean`

#### Defined in

[ue/ue.d.ts:18637](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18637)

___

### bMeshSpaceScaleBlend

• **bMeshSpaceScaleBlend**: `boolean`

#### Defined in

[ue/ue.d.ts:18638](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18638)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticClass](ue_ue.AnimNode_Base.md#staticclass)

#### Defined in

[ue/ue.d.ts:18648](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18648)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticStruct](ue_ue.AnimNode_Base.md#staticstruct)

#### Defined in

[ue/ue.d.ts:18649](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18649)
