[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_BlendBoneByChannel

# Class: AnimNode\_BlendBoneByChannel

[ue/ue](../modules/ue_ue.md).AnimNode_BlendBoneByChannel

## Hierarchy

- [`AnimNode_Base`](ue_ue.AnimNode_Base.md)

  ↳ **`AnimNode_BlendBoneByChannel`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_BlendBoneByChannel.md#constructor)

### Properties

- [A](ue_ue.AnimNode_BlendBoneByChannel.md#a)
- [Alpha](ue_ue.AnimNode_BlendBoneByChannel.md#alpha)
- [AlphaScaleBias](ue_ue.AnimNode_BlendBoneByChannel.md#alphascalebias)
- [B](ue_ue.AnimNode_BlendBoneByChannel.md#b)
- [BoneDefinitions](ue_ue.AnimNode_BlendBoneByChannel.md#bonedefinitions)
- [TransformsSpace](ue_ue.AnimNode_BlendBoneByChannel.md#transformsspace)
- [\_\_tid\_AnimNode\_BlendBoneByChannel\_\_](ue_ue.AnimNode_BlendBoneByChannel.md#__tid_animnode_blendbonebychannel__)

### Methods

- [StaticClass](ue_ue.AnimNode_BlendBoneByChannel.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_BlendBoneByChannel.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_BlendBoneByChannel**()

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[constructor](ue_ue.AnimNode_Base.md#constructor)

#### Defined in

[ue/ue.d.ts:17999](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17999)

• **new AnimNode_BlendBoneByChannel**(`A`, `B`, `BoneDefinitions`, `Alpha`, `AlphaScaleBias`, `TransformsSpace`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`PoseLink`](ue_ue.PoseLink.md) |
| `B` | [`PoseLink`](ue_ue.PoseLink.md) |
| `BoneDefinitions` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlendBoneByChannelEntry`](ue_ue.BlendBoneByChannelEntry.md)\> |
| `Alpha` | `number` |
| `AlphaScaleBias` | [`InputScaleBias`](ue_ue.InputScaleBias.md) |
| `TransformsSpace` | [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md) |

#### Overrides

UE.AnimNode\_Base.constructor

#### Defined in

[ue/ue.d.ts:18000](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18000)

## Properties

### A

• **A**: [`PoseLink`](ue_ue.PoseLink.md)

#### Defined in

[ue/ue.d.ts:18001](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18001)

___

### Alpha

• **Alpha**: `number`

#### Defined in

[ue/ue.d.ts:18004](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18004)

___

### AlphaScaleBias

• **AlphaScaleBias**: [`InputScaleBias`](ue_ue.InputScaleBias.md)

#### Defined in

[ue/ue.d.ts:18005](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18005)

___

### B

• **B**: [`PoseLink`](ue_ue.PoseLink.md)

#### Defined in

[ue/ue.d.ts:18002](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18002)

___

### BoneDefinitions

• **BoneDefinitions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlendBoneByChannelEntry`](ue_ue.BlendBoneByChannelEntry.md)\>

#### Defined in

[ue/ue.d.ts:18003](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18003)

___

### TransformsSpace

• **TransformsSpace**: [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md)

#### Defined in

[ue/ue.d.ts:18006](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18006)

___

### \_\_tid\_AnimNode\_BlendBoneByChannel\_\_

• `Private` **\_\_tid\_AnimNode\_BlendBoneByChannel\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:18012](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18012)

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

[ue/ue.d.ts:18010](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18010)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticStruct](ue_ue.AnimNode_Base.md#staticstruct)

#### Defined in

[ue/ue.d.ts:18011](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18011)
