[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_ModifyBone

# Class: AnimNode\_ModifyBone

[ue/ue](../modules/ue_ue.md).AnimNode_ModifyBone

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_ModifyBone`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_ModifyBone.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_ModifyBone.md#actualalpha)
- [Alpha](ue_ue.AnimNode_ModifyBone.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_ModifyBone.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_ModifyBone.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_ModifyBone.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_ModifyBone.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_ModifyBone.md#alphascalebiasclamp)
- [BoneToModify](ue_ue.AnimNode_ModifyBone.md#bonetomodify)
- [ComponentPose](ue_ue.AnimNode_ModifyBone.md#componentpose)
- [LODThreshold](ue_ue.AnimNode_ModifyBone.md#lodthreshold)
- [Rotation](ue_ue.AnimNode_ModifyBone.md#rotation)
- [RotationMode](ue_ue.AnimNode_ModifyBone.md#rotationmode)
- [RotationSpace](ue_ue.AnimNode_ModifyBone.md#rotationspace)
- [Scale](ue_ue.AnimNode_ModifyBone.md#scale)
- [ScaleMode](ue_ue.AnimNode_ModifyBone.md#scalemode)
- [ScaleSpace](ue_ue.AnimNode_ModifyBone.md#scalespace)
- [Translation](ue_ue.AnimNode_ModifyBone.md#translation)
- [TranslationMode](ue_ue.AnimNode_ModifyBone.md#translationmode)
- [TranslationSpace](ue_ue.AnimNode_ModifyBone.md#translationspace)
- [\_\_tid\_AnimNode\_ModifyBone\_\_](ue_ue.AnimNode_ModifyBone.md#__tid_animnode_modifybone__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_ModifyBone.md#balphaboolenabled)

### Methods

- [StaticClass](ue_ue.AnimNode_ModifyBone.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_ModifyBone.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_ModifyBone**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

• **new AnimNode_ModifyBone**(`BoneToModify`, `Translation`, `Rotation`, `Scale`, `TranslationMode`, `RotationMode`, `ScaleMode`, `TranslationSpace`, `RotationSpace`, `ScaleSpace`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneToModify` | [`BoneReference`](ue_ue.BoneReference.md) |
| `Translation` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `Scale` | [`Vector`](ue_ue_s.Vector.md) |
| `TranslationMode` | [`EBoneModificationMode`](../enums/ue_ue.EBoneModificationMode.md) |
| `RotationMode` | [`EBoneModificationMode`](../enums/ue_ue.EBoneModificationMode.md) |
| `ScaleMode` | [`EBoneModificationMode`](../enums/ue_ue.EBoneModificationMode.md) |
| `TranslationSpace` | [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md) |
| `RotationSpace` | [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md) |
| `ScaleSpace` | [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md) |

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

### BoneToModify

• **BoneToModify**: [`BoneReference`](ue_ue.BoneReference.md)

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

### Rotation

• **Rotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### RotationMode

• **RotationMode**: [`EBoneModificationMode`](../enums/ue_ue.EBoneModificationMode.md)

___

### RotationSpace

• **RotationSpace**: [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md)

___

### Scale

• **Scale**: [`Vector`](ue_ue_s.Vector.md)

___

### ScaleMode

• **ScaleMode**: [`EBoneModificationMode`](../enums/ue_ue.EBoneModificationMode.md)

___

### ScaleSpace

• **ScaleSpace**: [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md)

___

### Translation

• **Translation**: [`Vector`](ue_ue_s.Vector.md)

___

### TranslationMode

• **TranslationMode**: [`EBoneModificationMode`](../enums/ue_ue.EBoneModificationMode.md)

___

### TranslationSpace

• **TranslationSpace**: [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md)

___

### \_\_tid\_AnimNode\_ModifyBone\_\_

• `Private` **\_\_tid\_AnimNode\_ModifyBone\_\_**: `boolean`

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

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
