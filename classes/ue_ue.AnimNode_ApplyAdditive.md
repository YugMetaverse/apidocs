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

#### Defined in

[ue/ue.d.ts:17888](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17888)

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

#### Defined in

[ue/ue.d.ts:17889](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17889)

## Properties

### Additive

• **Additive**: [`PoseLink`](ue_ue.PoseLink.md)

#### Defined in

[ue/ue.d.ts:17891](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17891)

___

### Alpha

• **Alpha**: `number`

#### Defined in

[ue/ue.d.ts:17892](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17892)

___

### AlphaBoolBlend

• **AlphaBoolBlend**: [`InputAlphaBoolBlend`](ue_ue.InputAlphaBoolBlend.md)

#### Defined in

[ue/ue.d.ts:17895](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17895)

___

### AlphaCurveName

• **AlphaCurveName**: `string`

#### Defined in

[ue/ue.d.ts:17896](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17896)

___

### AlphaInputType

• **AlphaInputType**: [`EAnimAlphaInputType`](../enums/ue_ue.EAnimAlphaInputType.md)

#### Defined in

[ue/ue.d.ts:17898](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17898)

___

### AlphaScaleBias

• **AlphaScaleBias**: [`InputScaleBias`](ue_ue.InputScaleBias.md)

#### Defined in

[ue/ue.d.ts:17893](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17893)

___

### AlphaScaleBiasClamp

• **AlphaScaleBiasClamp**: [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md)

#### Defined in

[ue/ue.d.ts:17897](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17897)

___

### Base

• **Base**: [`PoseLink`](ue_ue.PoseLink.md)

#### Defined in

[ue/ue.d.ts:17890](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17890)

___

### LODThreshold

• **LODThreshold**: `number`

#### Defined in

[ue/ue.d.ts:17894](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17894)

___

### \_\_tid\_AnimNode\_ApplyAdditive\_\_

• `Private` **\_\_tid\_AnimNode\_ApplyAdditive\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:17905](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17905)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:17899](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17899)

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

[ue/ue.d.ts:17903](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17903)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticStruct](ue_ue.AnimNode_Base.md#staticstruct)

#### Defined in

[ue/ue.d.ts:17904](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17904)
