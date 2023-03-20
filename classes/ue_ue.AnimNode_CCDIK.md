[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_CCDIK

# Class: AnimNode\_CCDIK

[ue/ue](../modules/ue_ue.md).AnimNode_CCDIK

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_CCDIK`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_CCDIK.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_CCDIK.md#actualalpha)
- [Alpha](ue_ue.AnimNode_CCDIK.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_CCDIK.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_CCDIK.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_CCDIK.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_CCDIK.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_CCDIK.md#alphascalebiasclamp)
- [ComponentPose](ue_ue.AnimNode_CCDIK.md#componentpose)
- [EffectorLocation](ue_ue.AnimNode_CCDIK.md#effectorlocation)
- [EffectorLocationSpace](ue_ue.AnimNode_CCDIK.md#effectorlocationspace)
- [EffectorTarget](ue_ue.AnimNode_CCDIK.md#effectortarget)
- [LODThreshold](ue_ue.AnimNode_CCDIK.md#lodthreshold)
- [MaxIterations](ue_ue.AnimNode_CCDIK.md#maxiterations)
- [Precision](ue_ue.AnimNode_CCDIK.md#precision)
- [RootBone](ue_ue.AnimNode_CCDIK.md#rootbone)
- [RotationLimitPerJoints](ue_ue.AnimNode_CCDIK.md#rotationlimitperjoints)
- [TipBone](ue_ue.AnimNode_CCDIK.md#tipbone)
- [\_\_tid\_AnimNode\_CCDIK\_\_](ue_ue.AnimNode_CCDIK.md#__tid_animnode_ccdik__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_CCDIK.md#balphaboolenabled)
- [bEnableRotationLimit](ue_ue.AnimNode_CCDIK.md#benablerotationlimit)
- [bStartFromTail](ue_ue.AnimNode_CCDIK.md#bstartfromtail)

### Methods

- [StaticClass](ue_ue.AnimNode_CCDIK.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_CCDIK.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_CCDIK**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

• **new AnimNode_CCDIK**(`EffectorLocation`, `EffectorLocationSpace`, `EffectorTarget`, `TipBone`, `RootBone`, `Precision`, `MaxIterations`, `bStartFromTail`, `bEnableRotationLimit`, `RotationLimitPerJoints`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `EffectorLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `EffectorLocationSpace` | [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md) |
| `EffectorTarget` | [`BoneSocketTarget`](ue_ue.BoneSocketTarget.md) |
| `TipBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `RootBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `Precision` | `number` |
| `MaxIterations` | `number` |
| `bStartFromTail` | `boolean` |
| `bEnableRotationLimit` | `boolean` |
| `RotationLimitPerJoints` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

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

### EffectorTarget

• **EffectorTarget**: [`BoneSocketTarget`](ue_ue.BoneSocketTarget.md)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

___

### MaxIterations

• **MaxIterations**: `number`

___

### Precision

• **Precision**: `number`

___

### RootBone

• **RootBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### RotationLimitPerJoints

• **RotationLimitPerJoints**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### TipBone

• **TipBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### \_\_tid\_AnimNode\_CCDIK\_\_

• `Private` **\_\_tid\_AnimNode\_CCDIK\_\_**: `boolean`

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

___

### bEnableRotationLimit

• **bEnableRotationLimit**: `boolean`

___

### bStartFromTail

• **bStartFromTail**: `boolean`

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
