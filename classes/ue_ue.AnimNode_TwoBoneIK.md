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

## Properties

### ActualAlpha

• **ActualAlpha**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ActualAlpha](ue_ue.AnimNode_SkeletalControlBase.md#actualalpha)

___

### Alpha

• **Alpha**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[Alpha](ue_ue.AnimNode_SkeletalControlBase.md#alpha)

___

### AlphaBoolBlend

• **AlphaBoolBlend**: [`InputAlphaBoolBlend`](ue_ue.InputAlphaBoolBlend.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaBoolBlend](ue_ue.AnimNode_SkeletalControlBase.md#alphaboolblend)

___

### AlphaCurveName

• **AlphaCurveName**: `string`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaCurveName](ue_ue.AnimNode_SkeletalControlBase.md#alphacurvename)

___

### AlphaInputType

• **AlphaInputType**: [`EAnimAlphaInputType`](../enums/ue_ue.EAnimAlphaInputType.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaInputType](ue_ue.AnimNode_SkeletalControlBase.md#alphainputtype)

___

### AlphaScaleBias

• **AlphaScaleBias**: [`InputScaleBias`](ue_ue.InputScaleBias.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaScaleBias](ue_ue.AnimNode_SkeletalControlBase.md#alphascalebias)

___

### AlphaScaleBiasClamp

• **AlphaScaleBiasClamp**: [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaScaleBiasClamp](ue_ue.AnimNode_SkeletalControlBase.md#alphascalebiasclamp)

___

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

___

### EffectorLocation

• **EffectorLocation**: [`Vector`](ue_ue_s.Vector.md)

___

### EffectorLocationSpace

• **EffectorLocationSpace**: [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md)

___

### EffectorSpaceBoneName

• **EffectorSpaceBoneName**: `string`

___

### EffectorTarget

• **EffectorTarget**: [`BoneSocketTarget`](ue_ue.BoneSocketTarget.md)

___

### IKBone

• **IKBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### JointTarget

• **JointTarget**: [`BoneSocketTarget`](ue_ue.BoneSocketTarget.md)

___

### JointTargetLocation

• **JointTargetLocation**: [`Vector`](ue_ue_s.Vector.md)

___

### JointTargetLocationSpace

• **JointTargetLocationSpace**: [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md)

___

### JointTargetSpaceBoneName

• **JointTargetSpaceBoneName**: `string`

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

___

### MaxStretchScale

• **MaxStretchScale**: `number`

___

### StartStretchRatio

• **StartStretchRatio**: `number`

___

### StretchLimits

• **StretchLimits**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### TwistAxis

• **TwistAxis**: [`Axis`](ue_ue.Axis.md)

___

### \_\_tid\_AnimNode\_TwoBoneIK\_\_

• `Private` **\_\_tid\_AnimNode\_TwoBoneIK\_\_**: `boolean`

___

### bAllowStretching

• **bAllowStretching**: `boolean`

___

### bAllowTwist

• **bAllowTwist**: `boolean`

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

___

### bMaintainEffectorRelRot

• **bMaintainEffectorRelRot**: `boolean`

___

### bNoTwist

• **bNoTwist**: `boolean`

___

### bTakeRotationFromEffectorSpace

• **bTakeRotationFromEffectorSpace**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticClass](ue_ue.AnimNode_SkeletalControlBase.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)
