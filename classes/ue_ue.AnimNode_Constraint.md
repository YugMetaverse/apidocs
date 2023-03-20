[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_Constraint

# Class: AnimNode\_Constraint

[ue/ue](../modules/ue_ue.md).AnimNode_Constraint

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_Constraint`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_Constraint.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_Constraint.md#actualalpha)
- [Alpha](ue_ue.AnimNode_Constraint.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_Constraint.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_Constraint.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_Constraint.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_Constraint.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_Constraint.md#alphascalebiasclamp)
- [BoneToModify](ue_ue.AnimNode_Constraint.md#bonetomodify)
- [ComponentPose](ue_ue.AnimNode_Constraint.md#componentpose)
- [ConstraintSetup](ue_ue.AnimNode_Constraint.md#constraintsetup)
- [ConstraintWeights](ue_ue.AnimNode_Constraint.md#constraintweights)
- [LODThreshold](ue_ue.AnimNode_Constraint.md#lodthreshold)
- [\_\_tid\_AnimNode\_Constraint\_\_](ue_ue.AnimNode_Constraint.md#__tid_animnode_constraint__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_Constraint.md#balphaboolenabled)

### Methods

- [StaticClass](ue_ue.AnimNode_Constraint.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_Constraint.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_Constraint**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

• **new AnimNode_Constraint**(`BoneToModify`, `ConstraintSetup`, `ConstraintWeights`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneToModify` | [`BoneReference`](ue_ue.BoneReference.md) |
| `ConstraintSetup` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Constraint`](ue_ue.Constraint.md)\> |
| `ConstraintWeights` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

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

### ConstraintSetup

• **ConstraintSetup**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Constraint`](ue_ue.Constraint.md)\>

___

### ConstraintWeights

• **ConstraintWeights**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

___

### \_\_tid\_AnimNode\_Constraint\_\_

• `Private` **\_\_tid\_AnimNode\_Constraint\_\_**: `boolean`

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
