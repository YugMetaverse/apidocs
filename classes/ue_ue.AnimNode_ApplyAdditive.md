[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_ApplyAdditive

# Class: AnimNode\_ApplyAdditive

[ue/ue](../modules/ue_ue.md).AnimNode_ApplyAdditive

## Hierarchy

- [`AnimNode_Base`](ue_ue.AnimNode_Base.md)

  ↳ **`AnimNode_ApplyAdditive`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_ApplyAdditive.md#constructor)

### Properties

- [Additive](ue_ue.AnimNode_ApplyAdditive.md#additive)
- [Alpha](ue_ue.AnimNode_ApplyAdditive.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_ApplyAdditive.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_ApplyAdditive.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_ApplyAdditive.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_ApplyAdditive.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_ApplyAdditive.md#alphascalebiasclamp)
- [Base](ue_ue.AnimNode_ApplyAdditive.md#base)
- [LODThreshold](ue_ue.AnimNode_ApplyAdditive.md#lodthreshold)
- [\_\_tid\_AnimNode\_ApplyAdditive\_\_](ue_ue.AnimNode_ApplyAdditive.md#__tid_animnode_applyadditive__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_ApplyAdditive.md#balphaboolenabled)

### Methods

- [StaticClass](ue_ue.AnimNode_ApplyAdditive.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_ApplyAdditive.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_ApplyAdditive**()

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[constructor](ue_ue.AnimNode_Base.md#constructor)

• **new AnimNode_ApplyAdditive**(`Base`, `Additive`, `Alpha`, `AlphaScaleBias`, `LODThreshold`, `AlphaBoolBlend`, `AlphaCurveName`, `AlphaScaleBiasClamp`, `AlphaInputType`, `bAlphaBoolEnabled`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Base` | [`PoseLink`](ue_ue.PoseLink.md) |
| `Additive` | [`PoseLink`](ue_ue.PoseLink.md) |
| `Alpha` | `number` |
| `AlphaScaleBias` | [`InputScaleBias`](ue_ue.InputScaleBias.md) |
| `LODThreshold` | `number` |
| `AlphaBoolBlend` | [`InputAlphaBoolBlend`](ue_ue.InputAlphaBoolBlend.md) |
| `AlphaCurveName` | `string` |
| `AlphaScaleBiasClamp` | [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md) |
| `AlphaInputType` | [`EAnimAlphaInputType`](../enums/ue_ue.EAnimAlphaInputType.md) |
| `bAlphaBoolEnabled` | `boolean` |

#### Overrides

UE.AnimNode\_Base.constructor

## Properties

### Additive

• **Additive**: [`PoseLink`](ue_ue.PoseLink.md)

___

### Alpha

• **Alpha**: `number`

___

### AlphaBoolBlend

• **AlphaBoolBlend**: [`InputAlphaBoolBlend`](ue_ue.InputAlphaBoolBlend.md)

___

### AlphaCurveName

• **AlphaCurveName**: `string`

___

### AlphaInputType

• **AlphaInputType**: [`EAnimAlphaInputType`](../enums/ue_ue.EAnimAlphaInputType.md)

___

### AlphaScaleBias

• **AlphaScaleBias**: [`InputScaleBias`](ue_ue.InputScaleBias.md)

___

### AlphaScaleBiasClamp

• **AlphaScaleBiasClamp**: [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md)

___

### Base

• **Base**: [`PoseLink`](ue_ue.PoseLink.md)

___

### LODThreshold

• **LODThreshold**: `number`

___

### \_\_tid\_AnimNode\_ApplyAdditive\_\_

• `Private` **\_\_tid\_AnimNode\_ApplyAdditive\_\_**: `boolean`

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticClass](ue_ue.AnimNode_Base.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticStruct](ue_ue.AnimNode_Base.md#staticstruct)
