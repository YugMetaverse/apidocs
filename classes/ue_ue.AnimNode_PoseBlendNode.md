[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_PoseBlendNode

# Class: AnimNode\_PoseBlendNode

[ue/ue](../modules/ue_ue.md).AnimNode_PoseBlendNode

## Hierarchy

- [`AnimNode_PoseHandler`](ue_ue.AnimNode_PoseHandler.md)

  ↳ **`AnimNode_PoseBlendNode`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_PoseBlendNode.md#constructor)

### Properties

- [BlendOption](ue_ue.AnimNode_PoseBlendNode.md#blendoption)
- [BlendWeight](ue_ue.AnimNode_PoseBlendNode.md#blendweight)
- [CustomCurve](ue_ue.AnimNode_PoseBlendNode.md#customcurve)
- [GroupIndex](ue_ue.AnimNode_PoseBlendNode.md#groupindex)
- [GroupRole](ue_ue.AnimNode_PoseBlendNode.md#grouprole)
- [InternalTimeAccumulator](ue_ue.AnimNode_PoseBlendNode.md#internaltimeaccumulator)
- [PoseAsset](ue_ue.AnimNode_PoseBlendNode.md#poseasset)
- [SourcePose](ue_ue.AnimNode_PoseBlendNode.md#sourcepose)
- [\_\_tid\_AnimNode\_PoseBlendNode\_\_](ue_ue.AnimNode_PoseBlendNode.md#__tid_animnode_poseblendnode__)
- [bIgnoreForRelevancyTest](ue_ue.AnimNode_PoseBlendNode.md#bignoreforrelevancytest)

### Methods

- [StaticClass](ue_ue.AnimNode_PoseBlendNode.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_PoseBlendNode.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_PoseBlendNode**()

#### Overrides

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[constructor](ue_ue.AnimNode_PoseHandler.md#constructor)

#### Defined in

[ue/ue.d.ts:19098](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19098)

• **new AnimNode_PoseBlendNode**(`SourcePose`, `BlendOption`, `CustomCurve`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourcePose` | [`PoseLink`](ue_ue.PoseLink.md) |
| `BlendOption` | [`EAlphaBlendOption`](../enums/ue_ue.EAlphaBlendOption.md) |
| `CustomCurve` | [`CurveFloat`](ue_ue.CurveFloat.md) |

#### Overrides

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[constructor](ue_ue.AnimNode_PoseHandler.md#constructor)

#### Defined in

[ue/ue.d.ts:19099](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19099)

## Properties

### BlendOption

• **BlendOption**: [`EAlphaBlendOption`](../enums/ue_ue.EAlphaBlendOption.md)

#### Defined in

[ue/ue.d.ts:19101](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19101)

___

### BlendWeight

• **BlendWeight**: `number`

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[BlendWeight](ue_ue.AnimNode_PoseHandler.md#blendweight)

#### Defined in

[ue/ue.d.ts:17569](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17569)

___

### CustomCurve

• **CustomCurve**: [`CurveFloat`](ue_ue.CurveFloat.md)

#### Defined in

[ue/ue.d.ts:19102](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19102)

___

### GroupIndex

• **GroupIndex**: `number`

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[GroupIndex](ue_ue.AnimNode_PoseHandler.md#groupindex)

#### Defined in

[ue/ue.d.ts:17566](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17566)

___

### GroupRole

• **GroupRole**: [`EAnimGroupRole`](../enums/ue_ue.EAnimGroupRole.md)

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[GroupRole](ue_ue.AnimNode_PoseHandler.md#grouprole)

#### Defined in

[ue/ue.d.ts:17567](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17567)

___

### InternalTimeAccumulator

• **InternalTimeAccumulator**: `number`

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[InternalTimeAccumulator](ue_ue.AnimNode_PoseHandler.md#internaltimeaccumulator)

#### Defined in

[ue/ue.d.ts:17570](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17570)

___

### PoseAsset

• **PoseAsset**: [`PoseAsset`](ue_ue.PoseAsset.md)

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[PoseAsset](ue_ue.AnimNode_PoseHandler.md#poseasset)

#### Defined in

[ue/ue.d.ts:19088](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19088)

___

### SourcePose

• **SourcePose**: [`PoseLink`](ue_ue.PoseLink.md)

#### Defined in

[ue/ue.d.ts:19100](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19100)

___

### \_\_tid\_AnimNode\_PoseBlendNode\_\_

• `Private` **\_\_tid\_AnimNode\_PoseBlendNode\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:19108](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19108)

___

### bIgnoreForRelevancyTest

• **bIgnoreForRelevancyTest**: `boolean`

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[bIgnoreForRelevancyTest](ue_ue.AnimNode_PoseHandler.md#bignoreforrelevancytest)

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

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[StaticClass](ue_ue.AnimNode_PoseHandler.md#staticclass)

#### Defined in

[ue/ue.d.ts:19106](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19106)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[StaticStruct](ue_ue.AnimNode_PoseHandler.md#staticstruct)

#### Defined in

[ue/ue.d.ts:19107](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19107)
