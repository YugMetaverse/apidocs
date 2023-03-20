[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_PoseByName

# Class: AnimNode\_PoseByName

[ue/ue](../modules/ue_ue.md).AnimNode_PoseByName

## Hierarchy

- [`AnimNode_PoseHandler`](ue_ue.AnimNode_PoseHandler.md)

  ↳ **`AnimNode_PoseByName`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_PoseByName.md#constructor)

### Properties

- [BlendWeight](ue_ue.AnimNode_PoseByName.md#blendweight)
- [GroupIndex](ue_ue.AnimNode_PoseByName.md#groupindex)
- [GroupRole](ue_ue.AnimNode_PoseByName.md#grouprole)
- [InternalTimeAccumulator](ue_ue.AnimNode_PoseByName.md#internaltimeaccumulator)
- [PoseAsset](ue_ue.AnimNode_PoseByName.md#poseasset)
- [PoseName](ue_ue.AnimNode_PoseByName.md#posename)
- [PoseWeight](ue_ue.AnimNode_PoseByName.md#poseweight)
- [\_\_tid\_AnimNode\_PoseByName\_\_](ue_ue.AnimNode_PoseByName.md#__tid_animnode_posebyname__)
- [bIgnoreForRelevancyTest](ue_ue.AnimNode_PoseByName.md#bignoreforrelevancytest)

### Methods

- [StaticClass](ue_ue.AnimNode_PoseByName.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_PoseByName.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_PoseByName**()

#### Overrides

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[constructor](ue_ue.AnimNode_PoseHandler.md#constructor)

#### Defined in

[ue/ue.d.ts:19122](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19122)

• **new AnimNode_PoseByName**(`PoseName`, `PoseWeight`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PoseName` | `string` |
| `PoseWeight` | `number` |

#### Overrides

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[constructor](ue_ue.AnimNode_PoseHandler.md#constructor)

#### Defined in

[ue/ue.d.ts:19123](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19123)

## Properties

### BlendWeight

• **BlendWeight**: `number`

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[BlendWeight](ue_ue.AnimNode_PoseHandler.md#blendweight)

#### Defined in

[ue/ue.d.ts:17569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17569)

___

### GroupIndex

• **GroupIndex**: `number`

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[GroupIndex](ue_ue.AnimNode_PoseHandler.md#groupindex)

#### Defined in

[ue/ue.d.ts:17566](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17566)

___

### GroupRole

• **GroupRole**: [`EAnimGroupRole`](../enums/ue_ue.EAnimGroupRole.md)

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[GroupRole](ue_ue.AnimNode_PoseHandler.md#grouprole)

#### Defined in

[ue/ue.d.ts:17567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17567)

___

### InternalTimeAccumulator

• **InternalTimeAccumulator**: `number`

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[InternalTimeAccumulator](ue_ue.AnimNode_PoseHandler.md#internaltimeaccumulator)

#### Defined in

[ue/ue.d.ts:17570](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17570)

___

### PoseAsset

• **PoseAsset**: [`PoseAsset`](ue_ue.PoseAsset.md)

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[PoseAsset](ue_ue.AnimNode_PoseHandler.md#poseasset)

#### Defined in

[ue/ue.d.ts:19088](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19088)

___

### PoseName

• **PoseName**: `string`

#### Defined in

[ue/ue.d.ts:19124](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19124)

___

### PoseWeight

• **PoseWeight**: `number`

#### Defined in

[ue/ue.d.ts:19125](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19125)

___

### \_\_tid\_AnimNode\_PoseByName\_\_

• `Private` **\_\_tid\_AnimNode\_PoseByName\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:19131](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19131)

___

### bIgnoreForRelevancyTest

• **bIgnoreForRelevancyTest**: `boolean`

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[bIgnoreForRelevancyTest](ue_ue.AnimNode_PoseHandler.md#bignoreforrelevancytest)

#### Defined in

[ue/ue.d.ts:17568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17568)

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

[ue/ue.d.ts:19129](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19129)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[StaticStruct](ue_ue.AnimNode_PoseHandler.md#staticstruct)

#### Defined in

[ue/ue.d.ts:19130](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19130)
