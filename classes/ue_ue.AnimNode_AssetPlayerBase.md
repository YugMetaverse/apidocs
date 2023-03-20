[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_AssetPlayerBase

# Class: AnimNode\_AssetPlayerBase

[ue/ue](../modules/ue_ue.md).AnimNode_AssetPlayerBase

## Hierarchy

- [`AnimNode_Base`](ue_ue.AnimNode_Base.md)

  ↳ **`AnimNode_AssetPlayerBase`**

  ↳↳ [`AnimNode_BlendSpacePlayer`](ue_ue.AnimNode_BlendSpacePlayer.md)

  ↳↳ [`AnimNode_PoseHandler`](ue_ue.AnimNode_PoseHandler.md)

  ↳↳ [`AnimNode_SequenceEvaluator`](ue_ue.AnimNode_SequenceEvaluator.md)

  ↳↳ [`AnimNode_SequencePlayer`](ue_ue.AnimNode_SequencePlayer.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_AssetPlayerBase.md#constructor)

### Properties

- [BlendWeight](ue_ue.AnimNode_AssetPlayerBase.md#blendweight)
- [GroupIndex](ue_ue.AnimNode_AssetPlayerBase.md#groupindex)
- [GroupRole](ue_ue.AnimNode_AssetPlayerBase.md#grouprole)
- [InternalTimeAccumulator](ue_ue.AnimNode_AssetPlayerBase.md#internaltimeaccumulator)
- [\_\_tid\_AnimNode\_AssetPlayerBase\_\_](ue_ue.AnimNode_AssetPlayerBase.md#__tid_animnode_assetplayerbase__)
- [bIgnoreForRelevancyTest](ue_ue.AnimNode_AssetPlayerBase.md#bignoreforrelevancytest)

### Methods

- [StaticClass](ue_ue.AnimNode_AssetPlayerBase.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_AssetPlayerBase.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_AssetPlayerBase**()

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[constructor](ue_ue.AnimNode_Base.md#constructor)

#### Defined in

[ue/ue.d.ts:17564](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17564)

• **new AnimNode_AssetPlayerBase**(`GroupIndex`, `GroupRole`, `bIgnoreForRelevancyTest`, `BlendWeight`, `InternalTimeAccumulator`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `GroupIndex` | `number` |
| `GroupRole` | [`EAnimGroupRole`](../enums/ue_ue.EAnimGroupRole.md) |
| `bIgnoreForRelevancyTest` | `boolean` |
| `BlendWeight` | `number` |
| `InternalTimeAccumulator` | `number` |

#### Overrides

UE.AnimNode\_Base.constructor

#### Defined in

[ue/ue.d.ts:17565](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17565)

## Properties

### BlendWeight

• **BlendWeight**: `number`

#### Defined in

[ue/ue.d.ts:17569](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17569)

___

### GroupIndex

• **GroupIndex**: `number`

#### Defined in

[ue/ue.d.ts:17566](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17566)

___

### GroupRole

• **GroupRole**: [`EAnimGroupRole`](../enums/ue_ue.EAnimGroupRole.md)

#### Defined in

[ue/ue.d.ts:17567](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17567)

___

### InternalTimeAccumulator

• **InternalTimeAccumulator**: `number`

#### Defined in

[ue/ue.d.ts:17570](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17570)

___

### \_\_tid\_AnimNode\_AssetPlayerBase\_\_

• `Private` **\_\_tid\_AnimNode\_AssetPlayerBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:17576](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17576)

___

### bIgnoreForRelevancyTest

• **bIgnoreForRelevancyTest**: `boolean`

#### Defined in

[ue/ue.d.ts:17568](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17568)

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

[ue/ue.d.ts:17574](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17574)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticStruct](ue_ue.AnimNode_Base.md#staticstruct)

#### Defined in

[ue/ue.d.ts:17575](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17575)
