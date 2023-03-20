[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_ScaleChainLength

# Class: AnimNode\_ScaleChainLength

[ue/ue](../modules/ue_ue.md).AnimNode_ScaleChainLength

## Hierarchy

- [`AnimNode_Base`](ue_ue.AnimNode_Base.md)

  ↳ **`AnimNode_ScaleChainLength`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_ScaleChainLength.md#constructor)

### Properties

- [Alpha](ue_ue.AnimNode_ScaleChainLength.md#alpha)
- [AlphaScaleBias](ue_ue.AnimNode_ScaleChainLength.md#alphascalebias)
- [ChainEndBone](ue_ue.AnimNode_ScaleChainLength.md#chainendbone)
- [ChainInitialLength](ue_ue.AnimNode_ScaleChainLength.md#chaininitiallength)
- [ChainStartBone](ue_ue.AnimNode_ScaleChainLength.md#chainstartbone)
- [DefaultChainLength](ue_ue.AnimNode_ScaleChainLength.md#defaultchainlength)
- [InputPose](ue_ue.AnimNode_ScaleChainLength.md#inputpose)
- [TargetLocation](ue_ue.AnimNode_ScaleChainLength.md#targetlocation)
- [\_\_tid\_AnimNode\_ScaleChainLength\_\_](ue_ue.AnimNode_ScaleChainLength.md#__tid_animnode_scalechainlength__)

### Methods

- [StaticClass](ue_ue.AnimNode_ScaleChainLength.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_ScaleChainLength.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_ScaleChainLength**()

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[constructor](ue_ue.AnimNode_Base.md#constructor)

#### Defined in

[ue/ue.d.ts:19525](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19525)

• **new AnimNode_ScaleChainLength**(`InputPose`, `DefaultChainLength`, `ChainStartBone`, `ChainEndBone`, `TargetLocation`, `Alpha`, `AlphaScaleBias`, `ChainInitialLength`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InputPose` | [`PoseLink`](ue_ue.PoseLink.md) |
| `DefaultChainLength` | `number` |
| `ChainStartBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `ChainEndBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `TargetLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `Alpha` | `number` |
| `AlphaScaleBias` | [`InputScaleBias`](ue_ue.InputScaleBias.md) |
| `ChainInitialLength` | [`EScaleChainInitialLength`](../enums/ue_ue.EScaleChainInitialLength.md) |

#### Overrides

UE.AnimNode\_Base.constructor

#### Defined in

[ue/ue.d.ts:19526](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19526)

## Properties

### Alpha

• **Alpha**: `number`

#### Defined in

[ue/ue.d.ts:19532](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19532)

___

### AlphaScaleBias

• **AlphaScaleBias**: [`InputScaleBias`](ue_ue.InputScaleBias.md)

#### Defined in

[ue/ue.d.ts:19533](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19533)

___

### ChainEndBone

• **ChainEndBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:19530](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19530)

___

### ChainInitialLength

• **ChainInitialLength**: [`EScaleChainInitialLength`](../enums/ue_ue.EScaleChainInitialLength.md)

#### Defined in

[ue/ue.d.ts:19534](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19534)

___

### ChainStartBone

• **ChainStartBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:19529](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19529)

___

### DefaultChainLength

• **DefaultChainLength**: `number`

#### Defined in

[ue/ue.d.ts:19528](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19528)

___

### InputPose

• **InputPose**: [`PoseLink`](ue_ue.PoseLink.md)

#### Defined in

[ue/ue.d.ts:19527](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19527)

___

### TargetLocation

• **TargetLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:19531](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19531)

___

### \_\_tid\_AnimNode\_ScaleChainLength\_\_

• `Private` **\_\_tid\_AnimNode\_ScaleChainLength\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:19540](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19540)

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

[ue/ue.d.ts:19538](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19538)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticStruct](ue_ue.AnimNode_Base.md#staticstruct)

#### Defined in

[ue/ue.d.ts:19539](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19539)
