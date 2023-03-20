[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_TwoWayBlend

# Class: AnimNode\_TwoWayBlend

[ue/ue](../modules/ue_ue.md).AnimNode_TwoWayBlend

## Hierarchy

- [`AnimNode_Base`](ue_ue.AnimNode_Base.md)

  ↳ **`AnimNode_TwoWayBlend`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_TwoWayBlend.md#constructor)

### Properties

- [A](ue_ue.AnimNode_TwoWayBlend.md#a)
- [Alpha](ue_ue.AnimNode_TwoWayBlend.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_TwoWayBlend.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_TwoWayBlend.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_TwoWayBlend.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_TwoWayBlend.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_TwoWayBlend.md#alphascalebiasclamp)
- [B](ue_ue.AnimNode_TwoWayBlend.md#b)
- [\_\_tid\_AnimNode\_TwoWayBlend\_\_](ue_ue.AnimNode_TwoWayBlend.md#__tid_animnode_twowayblend__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_TwoWayBlend.md#balphaboolenabled)
- [bResetChildOnActivation](ue_ue.AnimNode_TwoWayBlend.md#bresetchildonactivation)

### Methods

- [StaticClass](ue_ue.AnimNode_TwoWayBlend.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_TwoWayBlend.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_TwoWayBlend**()

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[constructor](ue_ue.AnimNode_Base.md#constructor)

• **new AnimNode_TwoWayBlend**(`A`, `B`, `AlphaInputType`, `bAlphaBoolEnabled`, `bResetChildOnActivation`, `Alpha`, `AlphaScaleBias`, `AlphaBoolBlend`, `AlphaCurveName`, `AlphaScaleBiasClamp`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`PoseLink`](ue_ue.PoseLink.md) |
| `B` | [`PoseLink`](ue_ue.PoseLink.md) |
| `AlphaInputType` | [`EAnimAlphaInputType`](../enums/ue_ue.EAnimAlphaInputType.md) |
| `bAlphaBoolEnabled` | `boolean` |
| `bResetChildOnActivation` | `boolean` |
| `Alpha` | `number` |
| `AlphaScaleBias` | [`InputScaleBias`](ue_ue.InputScaleBias.md) |
| `AlphaBoolBlend` | [`InputAlphaBoolBlend`](ue_ue.InputAlphaBoolBlend.md) |
| `AlphaCurveName` | `string` |
| `AlphaScaleBiasClamp` | [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md) |

#### Overrides

UE.AnimNode\_Base.constructor

## Properties

### A

• **A**: [`PoseLink`](ue_ue.PoseLink.md)

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

### B

• **B**: [`PoseLink`](ue_ue.PoseLink.md)

___

### \_\_tid\_AnimNode\_TwoWayBlend\_\_

• `Private` **\_\_tid\_AnimNode\_TwoWayBlend\_\_**: `boolean`

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

___

### bResetChildOnActivation

• **bResetChildOnActivation**: `boolean`

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
