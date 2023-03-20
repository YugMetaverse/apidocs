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

#### Defined in

[ue/ue.d.ts:20018](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20018)

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

#### Defined in

[ue/ue.d.ts:20019](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20019)

## Properties

### A

• **A**: [`PoseLink`](ue_ue.PoseLink.md)

#### Defined in

[ue/ue.d.ts:20020](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20020)

___

### Alpha

• **Alpha**: `number`

#### Defined in

[ue/ue.d.ts:20025](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20025)

___

### AlphaBoolBlend

• **AlphaBoolBlend**: [`InputAlphaBoolBlend`](ue_ue.InputAlphaBoolBlend.md)

#### Defined in

[ue/ue.d.ts:20027](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20027)

___

### AlphaCurveName

• **AlphaCurveName**: `string`

#### Defined in

[ue/ue.d.ts:20028](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20028)

___

### AlphaInputType

• **AlphaInputType**: [`EAnimAlphaInputType`](../enums/ue_ue.EAnimAlphaInputType.md)

#### Defined in

[ue/ue.d.ts:20022](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20022)

___

### AlphaScaleBias

• **AlphaScaleBias**: [`InputScaleBias`](ue_ue.InputScaleBias.md)

#### Defined in

[ue/ue.d.ts:20026](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20026)

___

### AlphaScaleBiasClamp

• **AlphaScaleBiasClamp**: [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md)

#### Defined in

[ue/ue.d.ts:20029](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20029)

___

### B

• **B**: [`PoseLink`](ue_ue.PoseLink.md)

#### Defined in

[ue/ue.d.ts:20021](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20021)

___

### \_\_tid\_AnimNode\_TwoWayBlend\_\_

• `Private` **\_\_tid\_AnimNode\_TwoWayBlend\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:20035](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20035)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:20023](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20023)

___

### bResetChildOnActivation

• **bResetChildOnActivation**: `boolean`

#### Defined in

[ue/ue.d.ts:20024](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20024)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticClass](ue_ue.AnimNode_Base.md#staticclass)

#### Defined in

[ue/ue.d.ts:20033](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20033)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticStruct](ue_ue.AnimNode_Base.md#staticstruct)

#### Defined in

[ue/ue.d.ts:20034](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20034)
