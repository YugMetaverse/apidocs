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

## Properties

### A

• **A**: [`PoseLink`](ue_ue.PoseLink.md)

___

### Alpha

• **Alpha**: `number`

___

### AlphaScaleBias

• **AlphaScaleBias**: [`InputScaleBias`](ue_ue.InputScaleBias.md)

___

### B

• **B**: [`PoseLink`](ue_ue.PoseLink.md)

___

### BoneDefinitions

• **BoneDefinitions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlendBoneByChannelEntry`](ue_ue.BlendBoneByChannelEntry.md)\>

___

### TransformsSpace

• **TransformsSpace**: [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md)

___

### \_\_tid\_AnimNode\_BlendBoneByChannel\_\_

• `Private` **\_\_tid\_AnimNode\_BlendBoneByChannel\_\_**: `boolean`

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
