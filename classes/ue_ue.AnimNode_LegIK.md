[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_LegIK

# Class: AnimNode\_LegIK

[ue/ue](../modules/ue_ue.md).AnimNode_LegIK

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_LegIK`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_LegIK.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_LegIK.md#actualalpha)
- [Alpha](ue_ue.AnimNode_LegIK.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_LegIK.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_LegIK.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_LegIK.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_LegIK.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_LegIK.md#alphascalebiasclamp)
- [ComponentPose](ue_ue.AnimNode_LegIK.md#componentpose)
- [LODThreshold](ue_ue.AnimNode_LegIK.md#lodthreshold)
- [LegsDefinition](ue_ue.AnimNode_LegIK.md#legsdefinition)
- [MaxIterations](ue_ue.AnimNode_LegIK.md#maxiterations)
- [ReachPrecision](ue_ue.AnimNode_LegIK.md#reachprecision)
- [\_\_tid\_AnimNode\_LegIK\_\_](ue_ue.AnimNode_LegIK.md#__tid_animnode_legik__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_LegIK.md#balphaboolenabled)

### Methods

- [StaticClass](ue_ue.AnimNode_LegIK.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_LegIK.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_LegIK**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

• **new AnimNode_LegIK**(`ReachPrecision`, `MaxIterations`, `LegsDefinition`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ReachPrecision` | `number` |
| `MaxIterations` | `number` |
| `LegsDefinition` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimLegIKDefinition`](ue_ue.AnimLegIKDefinition.md)\> |

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

### LegsDefinition

• **LegsDefinition**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimLegIKDefinition`](ue_ue.AnimLegIKDefinition.md)\>

___

### MaxIterations

• **MaxIterations**: `number`

___

### ReachPrecision

• **ReachPrecision**: `number`

___

### \_\_tid\_AnimNode\_LegIK\_\_

• `Private` **\_\_tid\_AnimNode\_LegIK\_\_**: `boolean`

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
