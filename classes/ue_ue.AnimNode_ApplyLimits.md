[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_ApplyLimits

# Class: AnimNode\_ApplyLimits

[ue/ue](../modules/ue_ue.md).AnimNode_ApplyLimits

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_ApplyLimits`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_ApplyLimits.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_ApplyLimits.md#actualalpha)
- [Alpha](ue_ue.AnimNode_ApplyLimits.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_ApplyLimits.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_ApplyLimits.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_ApplyLimits.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_ApplyLimits.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_ApplyLimits.md#alphascalebiasclamp)
- [AngularOffsets](ue_ue.AnimNode_ApplyLimits.md#angularoffsets)
- [AngularRangeLimits](ue_ue.AnimNode_ApplyLimits.md#angularrangelimits)
- [ComponentPose](ue_ue.AnimNode_ApplyLimits.md#componentpose)
- [LODThreshold](ue_ue.AnimNode_ApplyLimits.md#lodthreshold)
- [\_\_tid\_AnimNode\_ApplyLimits\_\_](ue_ue.AnimNode_ApplyLimits.md#__tid_animnode_applylimits__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_ApplyLimits.md#balphaboolenabled)

### Methods

- [StaticClass](ue_ue.AnimNode_ApplyLimits.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_ApplyLimits.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_ApplyLimits**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

• **new AnimNode_ApplyLimits**(`AngularRangeLimits`, `AngularOffsets`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `AngularRangeLimits` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AngularRangeLimit`](ue_ue.AngularRangeLimit.md)\> |
| `AngularOffsets` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\> |

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

### AngularOffsets

• **AngularOffsets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

___

### AngularRangeLimits

• **AngularRangeLimits**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AngularRangeLimit`](ue_ue.AngularRangeLimit.md)\>

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

### \_\_tid\_AnimNode\_ApplyLimits\_\_

• `Private` **\_\_tid\_AnimNode\_ApplyLimits\_\_**: `boolean`

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
