[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_SkeletalControlBase

# Class: AnimNode\_SkeletalControlBase

[ue/ue](../modules/ue_ue.md).AnimNode_SkeletalControlBase

## Hierarchy

- [`AnimNode_Base`](ue_ue.AnimNode_Base.md)

  ↳ **`AnimNode_SkeletalControlBase`**

  ↳↳ [`AnimNode_AnimDynamics`](ue_ue.AnimNode_AnimDynamics.md)

  ↳↳ [`AnimNode_ApplyLimits`](ue_ue.AnimNode_ApplyLimits.md)

  ↳↳ [`AnimNode_BoneDrivenController`](ue_ue.AnimNode_BoneDrivenController.md)

  ↳↳ [`AnimNode_CCDIK`](ue_ue.AnimNode_CCDIK.md)

  ↳↳ [`AnimNode_Constraint`](ue_ue.AnimNode_Constraint.md)

  ↳↳ [`AnimNode_CopyBone`](ue_ue.AnimNode_CopyBone.md)

  ↳↳ [`AnimNode_CopyBoneDelta`](ue_ue.AnimNode_CopyBoneDelta.md)

  ↳↳ [`AnimNode_Fabrik`](ue_ue.AnimNode_Fabrik.md)

  ↳↳ [`AnimNode_HandIKRetargeting`](ue_ue.AnimNode_HandIKRetargeting.md)

  ↳↳ [`AnimNode_LegIK`](ue_ue.AnimNode_LegIK.md)

  ↳↳ [`AnimNode_LookAt`](ue_ue.AnimNode_LookAt.md)

  ↳↳ [`AnimNode_ModifyBone`](ue_ue.AnimNode_ModifyBone.md)

  ↳↳ [`AnimNode_ObserveBone`](ue_ue.AnimNode_ObserveBone.md)

  ↳↳ [`AnimNode_ResetRoot`](ue_ue.AnimNode_ResetRoot.md)

  ↳↳ [`AnimNode_RigidBody`](ue_ue.AnimNode_RigidBody.md)

  ↳↳ [`AnimNode_RigidBody_Chaos`](ue_ue.AnimNode_RigidBody_Chaos.md)

  ↳↳ [`AnimNode_RotationMultiplier`](ue_ue.AnimNode_RotationMultiplier.md)

  ↳↳ [`AnimNode_SplineIK`](ue_ue.AnimNode_SplineIK.md)

  ↳↳ [`AnimNode_SpringBone`](ue_ue.AnimNode_SpringBone.md)

  ↳↳ [`AnimNode_Trail`](ue_ue.AnimNode_Trail.md)

  ↳↳ [`AnimNode_TwistCorrectiveNode`](ue_ue.AnimNode_TwistCorrectiveNode.md)

  ↳↳ [`AnimNode_TwoBoneIK`](ue_ue.AnimNode_TwoBoneIK.md)

  ↳↳ [`AnimNode_WheelHandler`](ue_ue.AnimNode_WheelHandler.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_SkeletalControlBase.md#actualalpha)
- [Alpha](ue_ue.AnimNode_SkeletalControlBase.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_SkeletalControlBase.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_SkeletalControlBase.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_SkeletalControlBase.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_SkeletalControlBase.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_SkeletalControlBase.md#alphascalebiasclamp)
- [ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)
- [LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)
- [\_\_tid\_AnimNode\_SkeletalControlBase\_\_](ue_ue.AnimNode_SkeletalControlBase.md#__tid_animnode_skeletalcontrolbase__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

### Methods

- [StaticClass](ue_ue.AnimNode_SkeletalControlBase.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_SkeletalControlBase**()

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[constructor](ue_ue.AnimNode_Base.md#constructor)

#### Defined in

[ue/ue.d.ts:17713](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17713)

• **new AnimNode_SkeletalControlBase**(`ComponentPose`, `LODThreshold`, `ActualAlpha`, `AlphaInputType`, `bAlphaBoolEnabled`, `Alpha`, `AlphaScaleBias`, `AlphaBoolBlend`, `AlphaCurveName`, `AlphaScaleBiasClamp`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ComponentPose` | [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md) |
| `LODThreshold` | `number` |
| `ActualAlpha` | `number` |
| `AlphaInputType` | [`EAnimAlphaInputType`](../enums/ue_ue.EAnimAlphaInputType.md) |
| `bAlphaBoolEnabled` | `boolean` |
| `Alpha` | `number` |
| `AlphaScaleBias` | [`InputScaleBias`](ue_ue.InputScaleBias.md) |
| `AlphaBoolBlend` | [`InputAlphaBoolBlend`](ue_ue.InputAlphaBoolBlend.md) |
| `AlphaCurveName` | `string` |
| `AlphaScaleBiasClamp` | [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md) |

#### Overrides

UE.AnimNode\_Base.constructor

#### Defined in

[ue/ue.d.ts:17714](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17714)

## Properties

### ActualAlpha

• **ActualAlpha**: `number`

#### Defined in

[ue/ue.d.ts:17717](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17717)

___

### Alpha

• **Alpha**: `number`

#### Defined in

[ue/ue.d.ts:17720](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17720)

___

### AlphaBoolBlend

• **AlphaBoolBlend**: [`InputAlphaBoolBlend`](ue_ue.InputAlphaBoolBlend.md)

#### Defined in

[ue/ue.d.ts:17722](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17722)

___

### AlphaCurveName

• **AlphaCurveName**: `string`

#### Defined in

[ue/ue.d.ts:17723](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17723)

___

### AlphaInputType

• **AlphaInputType**: [`EAnimAlphaInputType`](../enums/ue_ue.EAnimAlphaInputType.md)

#### Defined in

[ue/ue.d.ts:17718](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17718)

___

### AlphaScaleBias

• **AlphaScaleBias**: [`InputScaleBias`](ue_ue.InputScaleBias.md)

#### Defined in

[ue/ue.d.ts:17721](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17721)

___

### AlphaScaleBiasClamp

• **AlphaScaleBiasClamp**: [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md)

#### Defined in

[ue/ue.d.ts:17724](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17724)

___

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Defined in

[ue/ue.d.ts:17715](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17715)

___

### LODThreshold

• **LODThreshold**: `number`

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17716)

___

### \_\_tid\_AnimNode\_SkeletalControlBase\_\_

• `Private` **\_\_tid\_AnimNode\_SkeletalControlBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:17730](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17730)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:17719](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17719)

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

[ue/ue.d.ts:17728](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17728)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticStruct](ue_ue.AnimNode_Base.md#staticstruct)

#### Defined in

[ue/ue.d.ts:17729](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17729)