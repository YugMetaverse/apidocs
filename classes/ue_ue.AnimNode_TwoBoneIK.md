[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_TwoBoneIK

# Class: AnimNode\_TwoBoneIK

[ue/ue](../modules/ue_ue.md).AnimNode_TwoBoneIK

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_TwoBoneIK`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_TwoBoneIK.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_TwoBoneIK.md#actualalpha)
- [Alpha](ue_ue.AnimNode_TwoBoneIK.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_TwoBoneIK.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_TwoBoneIK.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_TwoBoneIK.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_TwoBoneIK.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_TwoBoneIK.md#alphascalebiasclamp)
- [ComponentPose](ue_ue.AnimNode_TwoBoneIK.md#componentpose)
- [EffectorLocation](ue_ue.AnimNode_TwoBoneIK.md#effectorlocation)
- [EffectorLocationSpace](ue_ue.AnimNode_TwoBoneIK.md#effectorlocationspace)
- [EffectorSpaceBoneName](ue_ue.AnimNode_TwoBoneIK.md#effectorspacebonename)
- [EffectorTarget](ue_ue.AnimNode_TwoBoneIK.md#effectortarget)
- [IKBone](ue_ue.AnimNode_TwoBoneIK.md#ikbone)
- [JointTarget](ue_ue.AnimNode_TwoBoneIK.md#jointtarget)
- [JointTargetLocation](ue_ue.AnimNode_TwoBoneIK.md#jointtargetlocation)
- [JointTargetLocationSpace](ue_ue.AnimNode_TwoBoneIK.md#jointtargetlocationspace)
- [JointTargetSpaceBoneName](ue_ue.AnimNode_TwoBoneIK.md#jointtargetspacebonename)
- [LODThreshold](ue_ue.AnimNode_TwoBoneIK.md#lodthreshold)
- [MaxStretchScale](ue_ue.AnimNode_TwoBoneIK.md#maxstretchscale)
- [StartStretchRatio](ue_ue.AnimNode_TwoBoneIK.md#startstretchratio)
- [StretchLimits](ue_ue.AnimNode_TwoBoneIK.md#stretchlimits)
- [TwistAxis](ue_ue.AnimNode_TwoBoneIK.md#twistaxis)
- [\_\_tid\_AnimNode\_TwoBoneIK\_\_](ue_ue.AnimNode_TwoBoneIK.md#__tid_animnode_twoboneik__)
- [bAllowStretching](ue_ue.AnimNode_TwoBoneIK.md#ballowstretching)
- [bAllowTwist](ue_ue.AnimNode_TwoBoneIK.md#ballowtwist)
- [bAlphaBoolEnabled](ue_ue.AnimNode_TwoBoneIK.md#balphaboolenabled)
- [bMaintainEffectorRelRot](ue_ue.AnimNode_TwoBoneIK.md#bmaintaineffectorrelrot)
- [bNoTwist](ue_ue.AnimNode_TwoBoneIK.md#bnotwist)
- [bTakeRotationFromEffectorSpace](ue_ue.AnimNode_TwoBoneIK.md#btakerotationfromeffectorspace)

### Methods

- [StaticClass](ue_ue.AnimNode_TwoBoneIK.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_TwoBoneIK.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_TwoBoneIK**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:19978](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19978)

• **new AnimNode_TwoBoneIK**(`IKBone`, `StartStretchRatio`, `MaxStretchScale`, `StretchLimits`, `bNoTwist`, `JointTargetSpaceBoneName`, `EffectorSpaceBoneName`, `EffectorLocation`, `EffectorTarget`, `JointTargetLocation`, `JointTarget`, `TwistAxis`, `EffectorLocationSpace`, `JointTargetLocationSpace`, `bAllowStretching`, `bTakeRotationFromEffectorSpace`, `bMaintainEffectorRelRot`, `bAllowTwist`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `IKBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `StartStretchRatio` | `number` |
| `MaxStretchScale` | `number` |
| `StretchLimits` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `bNoTwist` | `boolean` |
| `JointTargetSpaceBoneName` | `string` |
| `EffectorSpaceBoneName` | `string` |
| `EffectorLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `EffectorTarget` | [`BoneSocketTarget`](ue_ue.BoneSocketTarget.md) |
| `JointTargetLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `JointTarget` | [`BoneSocketTarget`](ue_ue.BoneSocketTarget.md) |
| `TwistAxis` | [`Axis`](ue_ue.Axis.md) |
| `EffectorLocationSpace` | [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md) |
| `JointTargetLocationSpace` | [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md) |
| `bAllowStretching` | `boolean` |
| `bTakeRotationFromEffectorSpace` | `boolean` |
| `bMaintainEffectorRelRot` | `boolean` |
| `bAllowTwist` | `boolean` |

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:19979](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19979)

## Properties

### ActualAlpha

• **ActualAlpha**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ActualAlpha](ue_ue.AnimNode_SkeletalControlBase.md#actualalpha)

#### Defined in

[ue/ue.d.ts:17717](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17717)

___

### Alpha

• **Alpha**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[Alpha](ue_ue.AnimNode_SkeletalControlBase.md#alpha)

#### Defined in

[ue/ue.d.ts:17720](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17720)

___

### AlphaBoolBlend

• **AlphaBoolBlend**: [`InputAlphaBoolBlend`](ue_ue.InputAlphaBoolBlend.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaBoolBlend](ue_ue.AnimNode_SkeletalControlBase.md#alphaboolblend)

#### Defined in

[ue/ue.d.ts:17722](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17722)

___

### AlphaCurveName

• **AlphaCurveName**: `string`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaCurveName](ue_ue.AnimNode_SkeletalControlBase.md#alphacurvename)

#### Defined in

[ue/ue.d.ts:17723](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17723)

___

### AlphaInputType

• **AlphaInputType**: [`EAnimAlphaInputType`](../enums/ue_ue.EAnimAlphaInputType.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaInputType](ue_ue.AnimNode_SkeletalControlBase.md#alphainputtype)

#### Defined in

[ue/ue.d.ts:17718](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17718)

___

### AlphaScaleBias

• **AlphaScaleBias**: [`InputScaleBias`](ue_ue.InputScaleBias.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaScaleBias](ue_ue.AnimNode_SkeletalControlBase.md#alphascalebias)

#### Defined in

[ue/ue.d.ts:17721](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17721)

___

### AlphaScaleBiasClamp

• **AlphaScaleBiasClamp**: [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaScaleBiasClamp](ue_ue.AnimNode_SkeletalControlBase.md#alphascalebiasclamp)

#### Defined in

[ue/ue.d.ts:17724](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17724)

___

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

#### Defined in

[ue/ue.d.ts:17715](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17715)

___

### EffectorLocation

• **EffectorLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:19987](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19987)

___

### EffectorLocationSpace

• **EffectorLocationSpace**: [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md)

#### Defined in

[ue/ue.d.ts:19992](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19992)

___

### EffectorSpaceBoneName

• **EffectorSpaceBoneName**: `string`

#### Defined in

[ue/ue.d.ts:19986](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19986)

___

### EffectorTarget

• **EffectorTarget**: [`BoneSocketTarget`](ue_ue.BoneSocketTarget.md)

#### Defined in

[ue/ue.d.ts:19988](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19988)

___

### IKBone

• **IKBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:19980](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19980)

___

### JointTarget

• **JointTarget**: [`BoneSocketTarget`](ue_ue.BoneSocketTarget.md)

#### Defined in

[ue/ue.d.ts:19990](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19990)

___

### JointTargetLocation

• **JointTargetLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:19989](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19989)

___

### JointTargetLocationSpace

• **JointTargetLocationSpace**: [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md)

#### Defined in

[ue/ue.d.ts:19993](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19993)

___

### JointTargetSpaceBoneName

• **JointTargetSpaceBoneName**: `string`

#### Defined in

[ue/ue.d.ts:19985](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19985)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17716)

___

### MaxStretchScale

• **MaxStretchScale**: `number`

#### Defined in

[ue/ue.d.ts:19982](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19982)

___

### StartStretchRatio

• **StartStretchRatio**: `number`

#### Defined in

[ue/ue.d.ts:19981](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19981)

___

### StretchLimits

• **StretchLimits**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:19983](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19983)

___

### TwistAxis

• **TwistAxis**: [`Axis`](ue_ue.Axis.md)

#### Defined in

[ue/ue.d.ts:19991](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19991)

___

### \_\_tid\_AnimNode\_TwoBoneIK\_\_

• `Private` **\_\_tid\_AnimNode\_TwoBoneIK\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:20003](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20003)

___

### bAllowStretching

• **bAllowStretching**: `boolean`

#### Defined in

[ue/ue.d.ts:19994](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19994)

___

### bAllowTwist

• **bAllowTwist**: `boolean`

#### Defined in

[ue/ue.d.ts:19997](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19997)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

#### Defined in

[ue/ue.d.ts:17719](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17719)

___

### bMaintainEffectorRelRot

• **bMaintainEffectorRelRot**: `boolean`

#### Defined in

[ue/ue.d.ts:19996](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19996)

___

### bNoTwist

• **bNoTwist**: `boolean`

#### Defined in

[ue/ue.d.ts:19984](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19984)

___

### bTakeRotationFromEffectorSpace

• **bTakeRotationFromEffectorSpace**: `boolean`

#### Defined in

[ue/ue.d.ts:19995](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19995)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticClass](ue_ue.AnimNode_SkeletalControlBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:20001](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20001)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:20002](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20002)
