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

#### Defined in

[ue/ue.d.ts:17933](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17933)

• **new AnimNode_ApplyLimits**(`AngularRangeLimits`, `AngularOffsets`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `AngularRangeLimits` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AngularRangeLimit`](ue_ue.AngularRangeLimit.md)\> |
| `AngularOffsets` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:17934](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17934)

## Properties

### ActualAlpha

• **ActualAlpha**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ActualAlpha](ue_ue.AnimNode_SkeletalControlBase.md#actualalpha)

#### Defined in

[ue/ue.d.ts:17717](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17717)

___

### Alpha

• **Alpha**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[Alpha](ue_ue.AnimNode_SkeletalControlBase.md#alpha)

#### Defined in

[ue/ue.d.ts:17720](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17720)

___

### AlphaBoolBlend

• **AlphaBoolBlend**: [`InputAlphaBoolBlend`](ue_ue.InputAlphaBoolBlend.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaBoolBlend](ue_ue.AnimNode_SkeletalControlBase.md#alphaboolblend)

#### Defined in

[ue/ue.d.ts:17722](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17722)

___

### AlphaCurveName

• **AlphaCurveName**: `string`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaCurveName](ue_ue.AnimNode_SkeletalControlBase.md#alphacurvename)

#### Defined in

[ue/ue.d.ts:17723](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17723)

___

### AlphaInputType

• **AlphaInputType**: [`EAnimAlphaInputType`](../enums/ue_ue.EAnimAlphaInputType.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaInputType](ue_ue.AnimNode_SkeletalControlBase.md#alphainputtype)

#### Defined in

[ue/ue.d.ts:17718](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17718)

___

### AlphaScaleBias

• **AlphaScaleBias**: [`InputScaleBias`](ue_ue.InputScaleBias.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaScaleBias](ue_ue.AnimNode_SkeletalControlBase.md#alphascalebias)

#### Defined in

[ue/ue.d.ts:17721](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17721)

___

### AlphaScaleBiasClamp

• **AlphaScaleBiasClamp**: [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaScaleBiasClamp](ue_ue.AnimNode_SkeletalControlBase.md#alphascalebiasclamp)

#### Defined in

[ue/ue.d.ts:17724](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17724)

___

### AngularOffsets

• **AngularOffsets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Defined in

[ue/ue.d.ts:17936](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17936)

___

### AngularRangeLimits

• **AngularRangeLimits**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AngularRangeLimit`](ue_ue.AngularRangeLimit.md)\>

#### Defined in

[ue/ue.d.ts:17935](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17935)

___

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

#### Defined in

[ue/ue.d.ts:17715](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17715)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17716)

___

### \_\_tid\_AnimNode\_ApplyLimits\_\_

• `Private` **\_\_tid\_AnimNode\_ApplyLimits\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:17942](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17942)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

#### Defined in

[ue/ue.d.ts:17719](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17719)

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

[ue/ue.d.ts:17940](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17940)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:17941](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17941)
