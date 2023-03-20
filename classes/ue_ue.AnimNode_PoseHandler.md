[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_PoseHandler

# Class: AnimNode\_PoseHandler

[ue/ue](../modules/ue_ue.md).AnimNode_PoseHandler

## Hierarchy

- [`AnimNode_AssetPlayerBase`](ue_ue.AnimNode_AssetPlayerBase.md)

  ↳ **`AnimNode_PoseHandler`**

  ↳↳ [`AnimNode_PoseBlendNode`](ue_ue.AnimNode_PoseBlendNode.md)

  ↳↳ [`AnimNode_PoseByName`](ue_ue.AnimNode_PoseByName.md)

  ↳↳ [`AnimNode_PoseDriver`](ue_ue.AnimNode_PoseDriver.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_PoseHandler.md#constructor)

### Properties

- [BlendWeight](ue_ue.AnimNode_PoseHandler.md#blendweight)
- [GroupIndex](ue_ue.AnimNode_PoseHandler.md#groupindex)
- [GroupRole](ue_ue.AnimNode_PoseHandler.md#grouprole)
- [InternalTimeAccumulator](ue_ue.AnimNode_PoseHandler.md#internaltimeaccumulator)
- [PoseAsset](ue_ue.AnimNode_PoseHandler.md#poseasset)
- [\_\_tid\_AnimNode\_PoseHandler\_\_](ue_ue.AnimNode_PoseHandler.md#__tid_animnode_posehandler__)
- [bIgnoreForRelevancyTest](ue_ue.AnimNode_PoseHandler.md#bignoreforrelevancytest)

### Methods

- [StaticClass](ue_ue.AnimNode_PoseHandler.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_PoseHandler.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_PoseHandler**()

#### Overrides

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[constructor](ue_ue.AnimNode_AssetPlayerBase.md#constructor)

#### Defined in

[ue/ue.d.ts:19086](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19086)

• **new AnimNode_PoseHandler**(`PoseAsset`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PoseAsset` | [`PoseAsset`](ue_ue.PoseAsset.md) |

#### Overrides

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[constructor](ue_ue.AnimNode_AssetPlayerBase.md#constructor)

#### Defined in

[ue/ue.d.ts:19087](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19087)

## Properties

### BlendWeight

• **BlendWeight**: `number`

#### Inherited from

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[BlendWeight](ue_ue.AnimNode_AssetPlayerBase.md#blendweight)

#### Defined in

[ue/ue.d.ts:17569](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17569)

___

### GroupIndex

• **GroupIndex**: `number`

#### Inherited from

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[GroupIndex](ue_ue.AnimNode_AssetPlayerBase.md#groupindex)

#### Defined in

[ue/ue.d.ts:17566](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17566)

___

### GroupRole

• **GroupRole**: [`EAnimGroupRole`](../enums/ue_ue.EAnimGroupRole.md)

#### Inherited from

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[GroupRole](ue_ue.AnimNode_AssetPlayerBase.md#grouprole)

#### Defined in

[ue/ue.d.ts:17567](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17567)

___

### InternalTimeAccumulator

• **InternalTimeAccumulator**: `number`

#### Inherited from

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[InternalTimeAccumulator](ue_ue.AnimNode_AssetPlayerBase.md#internaltimeaccumulator)

#### Defined in

[ue/ue.d.ts:17570](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17570)

___

### PoseAsset

• **PoseAsset**: [`PoseAsset`](ue_ue.PoseAsset.md)

#### Defined in

[ue/ue.d.ts:19088](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19088)

___

### \_\_tid\_AnimNode\_PoseHandler\_\_

• `Private` **\_\_tid\_AnimNode\_PoseHandler\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:19094](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19094)

___

### bIgnoreForRelevancyTest

• **bIgnoreForRelevancyTest**: `boolean`

#### Inherited from

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[bIgnoreForRelevancyTest](ue_ue.AnimNode_AssetPlayerBase.md#bignoreforrelevancytest)

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

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[StaticClass](ue_ue.AnimNode_AssetPlayerBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:19092](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19092)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[StaticStruct](ue_ue.AnimNode_AssetPlayerBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:19093](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19093)
