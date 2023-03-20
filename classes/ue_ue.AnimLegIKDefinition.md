[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimLegIKDefinition

# Class: AnimLegIKDefinition

[ue/ue](../modules/ue_ue.md).AnimLegIKDefinition

## Table of contents

### Constructors

- [constructor](ue_ue.AnimLegIKDefinition.md#constructor)

### Properties

- [FKFootBone](ue_ue.AnimLegIKDefinition.md#fkfootbone)
- [FootBoneForwardAxis](ue_ue.AnimLegIKDefinition.md#footboneforwardaxis)
- [HingeRotationAxis](ue_ue.AnimLegIKDefinition.md#hingerotationaxis)
- [IKFootBone](ue_ue.AnimLegIKDefinition.md#ikfootbone)
- [MinRotationAngle](ue_ue.AnimLegIKDefinition.md#minrotationangle)
- [NumBonesInLimb](ue_ue.AnimLegIKDefinition.md#numbonesinlimb)
- [\_\_tid\_AnimLegIKDefinition\_\_](ue_ue.AnimLegIKDefinition.md#__tid_animlegikdefinition__)
- [bEnableKneeTwistCorrection](ue_ue.AnimLegIKDefinition.md#benablekneetwistcorrection)
- [bEnableRotationLimit](ue_ue.AnimLegIKDefinition.md#benablerotationlimit)

### Methods

- [StaticClass](ue_ue.AnimLegIKDefinition.md#staticclass)
- [StaticStruct](ue_ue.AnimLegIKDefinition.md#staticstruct)

## Constructors

### constructor

• **new AnimLegIKDefinition**()

• **new AnimLegIKDefinition**(`IKFootBone`, `FKFootBone`, `NumBonesInLimb`, `MinRotationAngle`, `FootBoneForwardAxis`, `HingeRotationAxis`, `bEnableRotationLimit`, `bEnableKneeTwistCorrection`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `IKFootBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `FKFootBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `NumBonesInLimb` | `number` |
| `MinRotationAngle` | `number` |
| `FootBoneForwardAxis` | [`EAxis`](../enums/ue_ue.EAxis.md) |
| `HingeRotationAxis` | [`EAxis`](../enums/ue_ue.EAxis.md) |
| `bEnableRotationLimit` | `boolean` |
| `bEnableKneeTwistCorrection` | `boolean` |

## Properties

### FKFootBone

• **FKFootBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### FootBoneForwardAxis

• **FootBoneForwardAxis**: [`EAxis`](../enums/ue_ue.EAxis.md)

___

### HingeRotationAxis

• **HingeRotationAxis**: [`EAxis`](../enums/ue_ue.EAxis.md)

___

### IKFootBone

• **IKFootBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### MinRotationAngle

• **MinRotationAngle**: `number`

___

### NumBonesInLimb

• **NumBonesInLimb**: `number`

___

### \_\_tid\_AnimLegIKDefinition\_\_

• `Private` **\_\_tid\_AnimLegIKDefinition\_\_**: `boolean`

___

### bEnableKneeTwistCorrection

• **bEnableKneeTwistCorrection**: `boolean`

___

### bEnableRotationLimit

• **bEnableRotationLimit**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
