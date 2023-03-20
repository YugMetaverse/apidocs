[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_PoseDriver

# Class: AnimNode\_PoseDriver

[ue/ue](../modules/ue_ue.md).AnimNode_PoseDriver

## Hierarchy

- [`AnimNode_PoseHandler`](ue_ue.AnimNode_PoseHandler.md)

  ↳ **`AnimNode_PoseDriver`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_PoseDriver.md#constructor)

### Properties

- [BlendWeight](ue_ue.AnimNode_PoseDriver.md#blendweight)
- [DriveOutput](ue_ue.AnimNode_PoseDriver.md#driveoutput)
- [DriveSource](ue_ue.AnimNode_PoseDriver.md#drivesource)
- [EvalSpaceBone](ue_ue.AnimNode_PoseDriver.md#evalspacebone)
- [GroupIndex](ue_ue.AnimNode_PoseDriver.md#groupindex)
- [GroupRole](ue_ue.AnimNode_PoseDriver.md#grouprole)
- [InternalTimeAccumulator](ue_ue.AnimNode_PoseDriver.md#internaltimeaccumulator)
- [OnlyDriveBones](ue_ue.AnimNode_PoseDriver.md#onlydrivebones)
- [PoseAsset](ue_ue.AnimNode_PoseDriver.md#poseasset)
- [PoseTargets](ue_ue.AnimNode_PoseDriver.md#posetargets)
- [RBFParams](ue_ue.AnimNode_PoseDriver.md#rbfparams)
- [RadialScaling](ue_ue.AnimNode_PoseDriver.md#radialscaling)
- [SourceBone](ue_ue.AnimNode_PoseDriver.md#sourcebone)
- [SourceBones](ue_ue.AnimNode_PoseDriver.md#sourcebones)
- [SourcePose](ue_ue.AnimNode_PoseDriver.md#sourcepose)
- [TwistAxis](ue_ue.AnimNode_PoseDriver.md#twistaxis)
- [Type](ue_ue.AnimNode_PoseDriver.md#type)
- [\_\_tid\_AnimNode\_PoseDriver\_\_](ue_ue.AnimNode_PoseDriver.md#__tid_animnode_posedriver__)
- [bIgnoreForRelevancyTest](ue_ue.AnimNode_PoseDriver.md#bignoreforrelevancytest)
- [bOnlyDriveSelectedBones](ue_ue.AnimNode_PoseDriver.md#bonlydriveselectedbones)

### Methods

- [StaticClass](ue_ue.AnimNode_PoseDriver.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_PoseDriver.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_PoseDriver**()

#### Overrides

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[constructor](ue_ue.AnimNode_PoseHandler.md#constructor)

#### Defined in

[ue/ue.d.ts:19206](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19206)

• **new AnimNode_PoseDriver**(`SourcePose`, `SourceBones`, `OnlyDriveBones`, `PoseTargets`, `EvalSpaceBone`, `RBFParams`, `SourceBone`, `TwistAxis`, `Type`, `RadialScaling`, `DriveSource`, `DriveOutput`, `bOnlyDriveSelectedBones`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourcePose` | [`PoseLink`](ue_ue.PoseLink.md) |
| `SourceBones` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoneReference`](ue_ue.BoneReference.md)\> |
| `OnlyDriveBones` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoneReference`](ue_ue.BoneReference.md)\> |
| `PoseTargets` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseDriverTarget`](ue_ue.PoseDriverTarget.md)\> |
| `EvalSpaceBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `RBFParams` | [`RBFParams`](ue_ue.RBFParams.md) |
| `SourceBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `TwistAxis` | [`EBoneAxis`](../enums/ue_ue.EBoneAxis.md) |
| `Type` | [`EPoseDriverType`](../enums/ue_ue.EPoseDriverType.md) |
| `RadialScaling` | `number` |
| `DriveSource` | [`EPoseDriverSource`](../enums/ue_ue.EPoseDriverSource.md) |
| `DriveOutput` | [`EPoseDriverOutput`](../enums/ue_ue.EPoseDriverOutput.md) |
| `bOnlyDriveSelectedBones` | `boolean` |

#### Overrides

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[constructor](ue_ue.AnimNode_PoseHandler.md#constructor)

#### Defined in

[ue/ue.d.ts:19207](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19207)

## Properties

### BlendWeight

• **BlendWeight**: `number`

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[BlendWeight](ue_ue.AnimNode_PoseHandler.md#blendweight)

#### Defined in

[ue/ue.d.ts:17569](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17569)

___

### DriveOutput

• **DriveOutput**: [`EPoseDriverOutput`](../enums/ue_ue.EPoseDriverOutput.md)

#### Defined in

[ue/ue.d.ts:19219](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19219)

___

### DriveSource

• **DriveSource**: [`EPoseDriverSource`](../enums/ue_ue.EPoseDriverSource.md)

#### Defined in

[ue/ue.d.ts:19218](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19218)

___

### EvalSpaceBone

• **EvalSpaceBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:19212](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19212)

___

### GroupIndex

• **GroupIndex**: `number`

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[GroupIndex](ue_ue.AnimNode_PoseHandler.md#groupindex)

#### Defined in

[ue/ue.d.ts:17566](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17566)

___

### GroupRole

• **GroupRole**: [`EAnimGroupRole`](../enums/ue_ue.EAnimGroupRole.md)

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[GroupRole](ue_ue.AnimNode_PoseHandler.md#grouprole)

#### Defined in

[ue/ue.d.ts:17567](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17567)

___

### InternalTimeAccumulator

• **InternalTimeAccumulator**: `number`

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[InternalTimeAccumulator](ue_ue.AnimNode_PoseHandler.md#internaltimeaccumulator)

#### Defined in

[ue/ue.d.ts:17570](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17570)

___

### OnlyDriveBones

• **OnlyDriveBones**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoneReference`](ue_ue.BoneReference.md)\>

#### Defined in

[ue/ue.d.ts:19210](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19210)

___

### PoseAsset

• **PoseAsset**: [`PoseAsset`](ue_ue.PoseAsset.md)

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[PoseAsset](ue_ue.AnimNode_PoseHandler.md#poseasset)

#### Defined in

[ue/ue.d.ts:19088](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19088)

___

### PoseTargets

• **PoseTargets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseDriverTarget`](ue_ue.PoseDriverTarget.md)\>

#### Defined in

[ue/ue.d.ts:19211](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19211)

___

### RBFParams

• **RBFParams**: [`RBFParams`](ue_ue.RBFParams.md)

#### Defined in

[ue/ue.d.ts:19213](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19213)

___

### RadialScaling

• **RadialScaling**: `number`

#### Defined in

[ue/ue.d.ts:19217](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19217)

___

### SourceBone

• **SourceBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:19214](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19214)

___

### SourceBones

• **SourceBones**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoneReference`](ue_ue.BoneReference.md)\>

#### Defined in

[ue/ue.d.ts:19209](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19209)

___

### SourcePose

• **SourcePose**: [`PoseLink`](ue_ue.PoseLink.md)

#### Defined in

[ue/ue.d.ts:19208](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19208)

___

### TwistAxis

• **TwistAxis**: [`EBoneAxis`](../enums/ue_ue.EBoneAxis.md)

#### Defined in

[ue/ue.d.ts:19215](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19215)

___

### Type

• **Type**: [`EPoseDriverType`](../enums/ue_ue.EPoseDriverType.md)

#### Defined in

[ue/ue.d.ts:19216](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19216)

___

### \_\_tid\_AnimNode\_PoseDriver\_\_

• `Private` **\_\_tid\_AnimNode\_PoseDriver\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:19226](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19226)

___

### bIgnoreForRelevancyTest

• **bIgnoreForRelevancyTest**: `boolean`

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[bIgnoreForRelevancyTest](ue_ue.AnimNode_PoseHandler.md#bignoreforrelevancytest)

#### Defined in

[ue/ue.d.ts:17568](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17568)

___

### bOnlyDriveSelectedBones

• **bOnlyDriveSelectedBones**: `boolean`

#### Defined in

[ue/ue.d.ts:19220](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19220)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[StaticClass](ue_ue.AnimNode_PoseHandler.md#staticclass)

#### Defined in

[ue/ue.d.ts:19224](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19224)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[StaticStruct](ue_ue.AnimNode_PoseHandler.md#staticstruct)

#### Defined in

[ue/ue.d.ts:19225](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19225)
