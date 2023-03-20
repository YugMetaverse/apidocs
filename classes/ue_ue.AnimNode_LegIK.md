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

#### Defined in

[ue/ue.d.ts:18683](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18683)

• **new AnimNode_LegIK**(`ReachPrecision`, `MaxIterations`, `LegsDefinition`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ReachPrecision` | `number` |
| `MaxIterations` | `number` |
| `LegsDefinition` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimLegIKDefinition`](ue_ue.AnimLegIKDefinition.md)\> |

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:18684](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18684)

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

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

#### Defined in

[ue/ue.d.ts:17715](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17715)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17716)

___

### LegsDefinition

• **LegsDefinition**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimLegIKDefinition`](ue_ue.AnimLegIKDefinition.md)\>

#### Defined in

[ue/ue.d.ts:18687](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18687)

___

### MaxIterations

• **MaxIterations**: `number`

#### Defined in

[ue/ue.d.ts:18686](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18686)

___

### ReachPrecision

• **ReachPrecision**: `number`

#### Defined in

[ue/ue.d.ts:18685](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18685)

___

### \_\_tid\_AnimNode\_LegIK\_\_

• `Private` **\_\_tid\_AnimNode\_LegIK\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:18693](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18693)

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

[ue/ue.d.ts:18691](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18691)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:18692](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18692)
