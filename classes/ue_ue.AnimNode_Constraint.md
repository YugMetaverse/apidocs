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

#### Defined in

[ue/ue.d.ts:18312](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18312)

• **new AnimNode_Constraint**(`BoneToModify`, `ConstraintSetup`, `ConstraintWeights`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneToModify` | [`BoneReference`](ue_ue.BoneReference.md) |
| `ConstraintSetup` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Constraint`](ue_ue.Constraint.md)\> |
| `ConstraintWeights` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:18313](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18313)

## Properties

### ActualAlpha

• **ActualAlpha**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ActualAlpha](ue_ue.AnimNode_SkeletalControlBase.md#actualalpha)

#### Defined in

[ue/ue.d.ts:17717](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17717)

___

### Alpha

• **Alpha**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[Alpha](ue_ue.AnimNode_SkeletalControlBase.md#alpha)

#### Defined in

[ue/ue.d.ts:17720](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17720)

___

### AlphaBoolBlend

• **AlphaBoolBlend**: [`InputAlphaBoolBlend`](ue_ue.InputAlphaBoolBlend.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaBoolBlend](ue_ue.AnimNode_SkeletalControlBase.md#alphaboolblend)

#### Defined in

[ue/ue.d.ts:17722](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17722)

___

### AlphaCurveName

• **AlphaCurveName**: `string`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaCurveName](ue_ue.AnimNode_SkeletalControlBase.md#alphacurvename)

#### Defined in

[ue/ue.d.ts:17723](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17723)

___

### AlphaInputType

• **AlphaInputType**: [`EAnimAlphaInputType`](../enums/ue_ue.EAnimAlphaInputType.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaInputType](ue_ue.AnimNode_SkeletalControlBase.md#alphainputtype)

#### Defined in

[ue/ue.d.ts:17718](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17718)

___

### AlphaScaleBias

• **AlphaScaleBias**: [`InputScaleBias`](ue_ue.InputScaleBias.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaScaleBias](ue_ue.AnimNode_SkeletalControlBase.md#alphascalebias)

#### Defined in

[ue/ue.d.ts:17721](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17721)

___

### AlphaScaleBiasClamp

• **AlphaScaleBiasClamp**: [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaScaleBiasClamp](ue_ue.AnimNode_SkeletalControlBase.md#alphascalebiasclamp)

#### Defined in

[ue/ue.d.ts:17724](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17724)

___

### BoneToModify

• **BoneToModify**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:18314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18314)

___

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

#### Defined in

[ue/ue.d.ts:17715](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17715)

___

### ConstraintSetup

• **ConstraintSetup**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Constraint`](ue_ue.Constraint.md)\>

#### Defined in

[ue/ue.d.ts:18315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18315)

___

### ConstraintWeights

• **ConstraintWeights**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:18316](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18316)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17716)

___

### \_\_tid\_AnimNode\_Constraint\_\_

• `Private` **\_\_tid\_AnimNode\_Constraint\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:18322](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18322)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

#### Defined in

[ue/ue.d.ts:17719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17719)

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

[ue/ue.d.ts:18320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18320)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:18321](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18321)
