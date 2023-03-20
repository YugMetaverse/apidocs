[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_ObserveBone

# Class: AnimNode\_ObserveBone

[ue/ue](../modules/ue_ue.md).AnimNode_ObserveBone

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_ObserveBone`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_ObserveBone.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_ObserveBone.md#actualalpha)
- [Alpha](ue_ue.AnimNode_ObserveBone.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_ObserveBone.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_ObserveBone.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_ObserveBone.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_ObserveBone.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_ObserveBone.md#alphascalebiasclamp)
- [BoneToObserve](ue_ue.AnimNode_ObserveBone.md#bonetoobserve)
- [ComponentPose](ue_ue.AnimNode_ObserveBone.md#componentpose)
- [DisplaySpace](ue_ue.AnimNode_ObserveBone.md#displayspace)
- [LODThreshold](ue_ue.AnimNode_ObserveBone.md#lodthreshold)
- [Rotation](ue_ue.AnimNode_ObserveBone.md#rotation)
- [Scale](ue_ue.AnimNode_ObserveBone.md#scale)
- [Translation](ue_ue.AnimNode_ObserveBone.md#translation)
- [\_\_tid\_AnimNode\_ObserveBone\_\_](ue_ue.AnimNode_ObserveBone.md#__tid_animnode_observebone__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_ObserveBone.md#balphaboolenabled)
- [bRelativeToRefPose](ue_ue.AnimNode_ObserveBone.md#brelativetorefpose)

### Methods

- [StaticClass](ue_ue.AnimNode_ObserveBone.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_ObserveBone.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_ObserveBone**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

• **new AnimNode_ObserveBone**(`BoneToObserve`, `DisplaySpace`, `bRelativeToRefPose`, `Translation`, `Rotation`, `Scale`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneToObserve` | [`BoneReference`](ue_ue.BoneReference.md) |
| `DisplaySpace` | [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md) |
| `bRelativeToRefPose` | `boolean` |
| `Translation` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `Scale` | [`Vector`](ue_ue_s.Vector.md) |

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

### BoneToObserve

• **BoneToObserve**: [`BoneReference`](ue_ue.BoneReference.md)

___

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

___

### DisplaySpace

• **DisplaySpace**: [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

___

### Rotation

• **Rotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### Scale

• **Scale**: [`Vector`](ue_ue_s.Vector.md)

___

### Translation

• **Translation**: [`Vector`](ue_ue_s.Vector.md)

___

### \_\_tid\_AnimNode\_ObserveBone\_\_

• `Private` **\_\_tid\_AnimNode\_ObserveBone\_\_**: `boolean`

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

___

### bRelativeToRefPose

• **bRelativeToRefPose**: `boolean`

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
