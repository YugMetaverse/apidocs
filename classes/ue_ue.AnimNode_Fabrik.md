[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_Fabrik

# Class: AnimNode\_Fabrik

[ue/ue](../modules/ue_ue.md).AnimNode_Fabrik

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_Fabrik`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_Fabrik.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_Fabrik.md#actualalpha)
- [Alpha](ue_ue.AnimNode_Fabrik.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_Fabrik.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_Fabrik.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_Fabrik.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_Fabrik.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_Fabrik.md#alphascalebiasclamp)
- [ComponentPose](ue_ue.AnimNode_Fabrik.md#componentpose)
- [EffectorRotationSource](ue_ue.AnimNode_Fabrik.md#effectorrotationsource)
- [EffectorTarget](ue_ue.AnimNode_Fabrik.md#effectortarget)
- [EffectorTransform](ue_ue.AnimNode_Fabrik.md#effectortransform)
- [EffectorTransformBone](ue_ue.AnimNode_Fabrik.md#effectortransformbone)
- [EffectorTransformSpace](ue_ue.AnimNode_Fabrik.md#effectortransformspace)
- [LODThreshold](ue_ue.AnimNode_Fabrik.md#lodthreshold)
- [MaxIterations](ue_ue.AnimNode_Fabrik.md#maxiterations)
- [Precision](ue_ue.AnimNode_Fabrik.md#precision)
- [RootBone](ue_ue.AnimNode_Fabrik.md#rootbone)
- [TipBone](ue_ue.AnimNode_Fabrik.md#tipbone)
- [\_\_tid\_AnimNode\_Fabrik\_\_](ue_ue.AnimNode_Fabrik.md#__tid_animnode_fabrik__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_Fabrik.md#balphaboolenabled)
- [bEnableDebugDraw](ue_ue.AnimNode_Fabrik.md#benabledebugdraw)

### Methods

- [StaticClass](ue_ue.AnimNode_Fabrik.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_Fabrik.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_Fabrik**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

• **new AnimNode_Fabrik**(`EffectorTransform`, `EffectorTarget`, `TipBone`, `RootBone`, `Precision`, `MaxIterations`, `EffectorTransformSpace`, `EffectorRotationSource`, `bEnableDebugDraw`, `EffectorTransformBone`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `EffectorTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `EffectorTarget` | [`BoneSocketTarget`](ue_ue.BoneSocketTarget.md) |
| `TipBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `RootBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `Precision` | `number` |
| `MaxIterations` | `number` |
| `EffectorTransformSpace` | [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md) |
| `EffectorRotationSource` | [`EBoneRotationSource`](../enums/ue_ue.EBoneRotationSource.md) |
| `bEnableDebugDraw` | `boolean` |
| `EffectorTransformBone` | [`BoneReference`](ue_ue.BoneReference.md) |

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

### EffectorRotationSource

• **EffectorRotationSource**: [`EBoneRotationSource`](../enums/ue_ue.EBoneRotationSource.md)

___

### EffectorTarget

• **EffectorTarget**: [`BoneSocketTarget`](ue_ue.BoneSocketTarget.md)

___

### EffectorTransform

• **EffectorTransform**: [`Transform`](ue_ue_s.Transform.md)

___

### EffectorTransformBone

• **EffectorTransformBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### EffectorTransformSpace

• **EffectorTransformSpace**: [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md)

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

### TipBone

• **TipBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### \_\_tid\_AnimNode\_Fabrik\_\_

• `Private` **\_\_tid\_AnimNode\_Fabrik\_\_**: `boolean`

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

___

### bEnableDebugDraw

• **bEnableDebugDraw**: `boolean`

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
