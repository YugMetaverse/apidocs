[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_CopyBone

# Class: AnimNode\_CopyBone

[ue/ue](../modules/ue_ue.md).AnimNode_CopyBone

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_CopyBone`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_CopyBone.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_CopyBone.md#actualalpha)
- [Alpha](ue_ue.AnimNode_CopyBone.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_CopyBone.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_CopyBone.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_CopyBone.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_CopyBone.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_CopyBone.md#alphascalebiasclamp)
- [ComponentPose](ue_ue.AnimNode_CopyBone.md#componentpose)
- [ControlSpace](ue_ue.AnimNode_CopyBone.md#controlspace)
- [LODThreshold](ue_ue.AnimNode_CopyBone.md#lodthreshold)
- [SourceBone](ue_ue.AnimNode_CopyBone.md#sourcebone)
- [TargetBone](ue_ue.AnimNode_CopyBone.md#targetbone)
- [\_\_tid\_AnimNode\_CopyBone\_\_](ue_ue.AnimNode_CopyBone.md#__tid_animnode_copybone__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_CopyBone.md#balphaboolenabled)
- [bCopyRotation](ue_ue.AnimNode_CopyBone.md#bcopyrotation)
- [bCopyScale](ue_ue.AnimNode_CopyBone.md#bcopyscale)
- [bCopyTranslation](ue_ue.AnimNode_CopyBone.md#bcopytranslation)

### Methods

- [StaticClass](ue_ue.AnimNode_CopyBone.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_CopyBone.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_CopyBone**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

• **new AnimNode_CopyBone**(`SourceBone`, `TargetBone`, `bCopyTranslation`, `bCopyRotation`, `bCopyScale`, `ControlSpace`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `TargetBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `bCopyTranslation` | `boolean` |
| `bCopyRotation` | `boolean` |
| `bCopyScale` | `boolean` |
| `ControlSpace` | [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md) |

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

### ControlSpace

• **ControlSpace**: [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

___

### SourceBone

• **SourceBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### TargetBone

• **TargetBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### \_\_tid\_AnimNode\_CopyBone\_\_

• `Private` **\_\_tid\_AnimNode\_CopyBone\_\_**: `boolean`

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

___

### bCopyRotation

• **bCopyRotation**: `boolean`

___

### bCopyScale

• **bCopyScale**: `boolean`

___

### bCopyTranslation

• **bCopyTranslation**: `boolean`

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
