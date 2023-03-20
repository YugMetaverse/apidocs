[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_RotationMultiplier

# Class: AnimNode\_RotationMultiplier

[ue/ue](../modules/ue_ue.md).AnimNode_RotationMultiplier

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_RotationMultiplier`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_RotationMultiplier.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_RotationMultiplier.md#actualalpha)
- [Alpha](ue_ue.AnimNode_RotationMultiplier.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_RotationMultiplier.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_RotationMultiplier.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_RotationMultiplier.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_RotationMultiplier.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_RotationMultiplier.md#alphascalebiasclamp)
- [ComponentPose](ue_ue.AnimNode_RotationMultiplier.md#componentpose)
- [LODThreshold](ue_ue.AnimNode_RotationMultiplier.md#lodthreshold)
- [Multiplier](ue_ue.AnimNode_RotationMultiplier.md#multiplier)
- [RotationAxisToRefer](ue_ue.AnimNode_RotationMultiplier.md#rotationaxistorefer)
- [SourceBone](ue_ue.AnimNode_RotationMultiplier.md#sourcebone)
- [TargetBone](ue_ue.AnimNode_RotationMultiplier.md#targetbone)
- [\_\_tid\_AnimNode\_RotationMultiplier\_\_](ue_ue.AnimNode_RotationMultiplier.md#__tid_animnode_rotationmultiplier__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_RotationMultiplier.md#balphaboolenabled)
- [bIsAdditive](ue_ue.AnimNode_RotationMultiplier.md#bisadditive)

### Methods

- [StaticClass](ue_ue.AnimNode_RotationMultiplier.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_RotationMultiplier.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_RotationMultiplier**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

• **new AnimNode_RotationMultiplier**(`TargetBone`, `SourceBone`, `Multiplier`, `RotationAxisToRefer`, `bIsAdditive`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `SourceBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `Multiplier` | `number` |
| `RotationAxisToRefer` | [`EBoneAxis`](../enums/ue_ue.EBoneAxis.md) |
| `bIsAdditive` | `boolean` |

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

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

___

### Multiplier

• **Multiplier**: `number`

___

### RotationAxisToRefer

• **RotationAxisToRefer**: [`EBoneAxis`](../enums/ue_ue.EBoneAxis.md)

___

### SourceBone

• **SourceBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### TargetBone

• **TargetBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### \_\_tid\_AnimNode\_RotationMultiplier\_\_

• `Private` **\_\_tid\_AnimNode\_RotationMultiplier\_\_**: `boolean`

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

___

### bIsAdditive

• **bIsAdditive**: `boolean`

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
