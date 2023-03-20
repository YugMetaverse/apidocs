[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_CopyBoneDelta

# Class: AnimNode\_CopyBoneDelta

[ue/ue](../modules/ue_ue.md).AnimNode_CopyBoneDelta

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_CopyBoneDelta`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_CopyBoneDelta.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_CopyBoneDelta.md#actualalpha)
- [Alpha](ue_ue.AnimNode_CopyBoneDelta.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_CopyBoneDelta.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_CopyBoneDelta.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_CopyBoneDelta.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_CopyBoneDelta.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_CopyBoneDelta.md#alphascalebiasclamp)
- [ComponentPose](ue_ue.AnimNode_CopyBoneDelta.md#componentpose)
- [CopyMode](ue_ue.AnimNode_CopyBoneDelta.md#copymode)
- [LODThreshold](ue_ue.AnimNode_CopyBoneDelta.md#lodthreshold)
- [RotationMultiplier](ue_ue.AnimNode_CopyBoneDelta.md#rotationmultiplier)
- [ScaleMultiplier](ue_ue.AnimNode_CopyBoneDelta.md#scalemultiplier)
- [SourceBone](ue_ue.AnimNode_CopyBoneDelta.md#sourcebone)
- [TargetBone](ue_ue.AnimNode_CopyBoneDelta.md#targetbone)
- [TranslationMultiplier](ue_ue.AnimNode_CopyBoneDelta.md#translationmultiplier)
- [\_\_tid\_AnimNode\_CopyBoneDelta\_\_](ue_ue.AnimNode_CopyBoneDelta.md#__tid_animnode_copybonedelta__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_CopyBoneDelta.md#balphaboolenabled)
- [bCopyRotation](ue_ue.AnimNode_CopyBoneDelta.md#bcopyrotation)
- [bCopyScale](ue_ue.AnimNode_CopyBoneDelta.md#bcopyscale)
- [bCopyTranslation](ue_ue.AnimNode_CopyBoneDelta.md#bcopytranslation)

### Methods

- [StaticClass](ue_ue.AnimNode_CopyBoneDelta.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_CopyBoneDelta.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_CopyBoneDelta**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

• **new AnimNode_CopyBoneDelta**(`SourceBone`, `TargetBone`, `bCopyTranslation`, `bCopyRotation`, `bCopyScale`, `CopyMode`, `TranslationMultiplier`, `RotationMultiplier`, `ScaleMultiplier`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `TargetBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `bCopyTranslation` | `boolean` |
| `bCopyRotation` | `boolean` |
| `bCopyScale` | `boolean` |
| `CopyMode` | [`CopyBoneDeltaMode`](../enums/ue_ue.CopyBoneDeltaMode.md) |
| `TranslationMultiplier` | `number` |
| `RotationMultiplier` | `number` |
| `ScaleMultiplier` | `number` |

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

### CopyMode

• **CopyMode**: [`CopyBoneDeltaMode`](../enums/ue_ue.CopyBoneDeltaMode.md)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

___

### RotationMultiplier

• **RotationMultiplier**: `number`

___

### ScaleMultiplier

• **ScaleMultiplier**: `number`

___

### SourceBone

• **SourceBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### TargetBone

• **TargetBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### TranslationMultiplier

• **TranslationMultiplier**: `number`

___

### \_\_tid\_AnimNode\_CopyBoneDelta\_\_

• `Private` **\_\_tid\_AnimNode\_CopyBoneDelta\_\_**: `boolean`

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
