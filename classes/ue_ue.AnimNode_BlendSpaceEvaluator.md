[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_BlendSpaceEvaluator

# Class: AnimNode\_BlendSpaceEvaluator

[ue/ue](../modules/ue_ue.md).AnimNode_BlendSpaceEvaluator

## Hierarchy

- [`AnimNode_BlendSpacePlayer`](ue_ue.AnimNode_BlendSpacePlayer.md)

  ↳ **`AnimNode_BlendSpaceEvaluator`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_BlendSpaceEvaluator.md#constructor)

### Properties

- [BlendSpace](ue_ue.AnimNode_BlendSpaceEvaluator.md#blendspace)
- [BlendWeight](ue_ue.AnimNode_BlendSpaceEvaluator.md#blendweight)
- [GroupIndex](ue_ue.AnimNode_BlendSpaceEvaluator.md#groupindex)
- [GroupRole](ue_ue.AnimNode_BlendSpaceEvaluator.md#grouprole)
- [InternalTimeAccumulator](ue_ue.AnimNode_BlendSpaceEvaluator.md#internaltimeaccumulator)
- [NormalizedTime](ue_ue.AnimNode_BlendSpaceEvaluator.md#normalizedtime)
- [PlayRate](ue_ue.AnimNode_BlendSpaceEvaluator.md#playrate)
- [PreviousBlendSpace](ue_ue.AnimNode_BlendSpaceEvaluator.md#previousblendspace)
- [StartPosition](ue_ue.AnimNode_BlendSpaceEvaluator.md#startposition)
- [X](ue_ue.AnimNode_BlendSpaceEvaluator.md#x)
- [Y](ue_ue.AnimNode_BlendSpaceEvaluator.md#y)
- [Z](ue_ue.AnimNode_BlendSpaceEvaluator.md#z)
- [\_\_tid\_AnimNode\_BlendSpaceEvaluator\_\_](ue_ue.AnimNode_BlendSpaceEvaluator.md#__tid_animnode_blendspaceevaluator__)
- [bIgnoreForRelevancyTest](ue_ue.AnimNode_BlendSpaceEvaluator.md#bignoreforrelevancytest)
- [bLoop](ue_ue.AnimNode_BlendSpaceEvaluator.md#bloop)
- [bResetPlayTimeWhenBlendSpaceChanges](ue_ue.AnimNode_BlendSpaceEvaluator.md#bresetplaytimewhenblendspacechanges)

### Methods

- [StaticClass](ue_ue.AnimNode_BlendSpaceEvaluator.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_BlendSpaceEvaluator.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_BlendSpaceEvaluator**()

#### Overrides

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[constructor](ue_ue.AnimNode_BlendSpacePlayer.md#constructor)

#### Defined in

[ue/ue.d.ts:18123](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18123)

• **new AnimNode_BlendSpaceEvaluator**(`NormalizedTime`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `NormalizedTime` | `number` |

#### Overrides

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[constructor](ue_ue.AnimNode_BlendSpacePlayer.md#constructor)

#### Defined in

[ue/ue.d.ts:18124](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18124)

## Properties

### BlendSpace

• **BlendSpace**: [`BlendSpaceBase`](ue_ue.BlendSpaceBase.md)

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[BlendSpace](ue_ue.AnimNode_BlendSpacePlayer.md#blendspace)

#### Defined in

[ue/ue.d.ts:17589](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17589)

___

### BlendWeight

• **BlendWeight**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[BlendWeight](ue_ue.AnimNode_BlendSpacePlayer.md#blendweight)

#### Defined in

[ue/ue.d.ts:17569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17569)

___

### GroupIndex

• **GroupIndex**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[GroupIndex](ue_ue.AnimNode_BlendSpacePlayer.md#groupindex)

#### Defined in

[ue/ue.d.ts:17566](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17566)

___

### GroupRole

• **GroupRole**: [`EAnimGroupRole`](../enums/ue_ue.EAnimGroupRole.md)

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[GroupRole](ue_ue.AnimNode_BlendSpacePlayer.md#grouprole)

#### Defined in

[ue/ue.d.ts:17567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17567)

___

### InternalTimeAccumulator

• **InternalTimeAccumulator**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[InternalTimeAccumulator](ue_ue.AnimNode_BlendSpacePlayer.md#internaltimeaccumulator)

#### Defined in

[ue/ue.d.ts:17570](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17570)

___

### NormalizedTime

• **NormalizedTime**: `number`

#### Defined in

[ue/ue.d.ts:18125](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18125)

___

### PlayRate

• **PlayRate**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[PlayRate](ue_ue.AnimNode_BlendSpacePlayer.md#playrate)

#### Defined in

[ue/ue.d.ts:17585](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17585)

___

### PreviousBlendSpace

• **PreviousBlendSpace**: [`BlendSpaceBase`](ue_ue.BlendSpaceBase.md)

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[PreviousBlendSpace](ue_ue.AnimNode_BlendSpacePlayer.md#previousblendspace)

#### Defined in

[ue/ue.d.ts:17590](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17590)

___

### StartPosition

• **StartPosition**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[StartPosition](ue_ue.AnimNode_BlendSpacePlayer.md#startposition)

#### Defined in

[ue/ue.d.ts:17588](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17588)

___

### X

• **X**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[X](ue_ue.AnimNode_BlendSpacePlayer.md#x)

#### Defined in

[ue/ue.d.ts:17582](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17582)

___

### Y

• **Y**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[Y](ue_ue.AnimNode_BlendSpacePlayer.md#y)

#### Defined in

[ue/ue.d.ts:17583](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17583)

___

### Z

• **Z**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[Z](ue_ue.AnimNode_BlendSpacePlayer.md#z)

#### Defined in

[ue/ue.d.ts:17584](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17584)

___

### \_\_tid\_AnimNode\_BlendSpaceEvaluator\_\_

• `Private` **\_\_tid\_AnimNode\_BlendSpaceEvaluator\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:18131](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18131)

___

### bIgnoreForRelevancyTest

• **bIgnoreForRelevancyTest**: `boolean`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[bIgnoreForRelevancyTest](ue_ue.AnimNode_BlendSpacePlayer.md#bignoreforrelevancytest)

#### Defined in

[ue/ue.d.ts:17568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17568)

___

### bLoop

• **bLoop**: `boolean`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[bLoop](ue_ue.AnimNode_BlendSpacePlayer.md#bloop)

#### Defined in

[ue/ue.d.ts:17586](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17586)

___

### bResetPlayTimeWhenBlendSpaceChanges

• **bResetPlayTimeWhenBlendSpaceChanges**: `boolean`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[bResetPlayTimeWhenBlendSpaceChanges](ue_ue.AnimNode_BlendSpacePlayer.md#bresetplaytimewhenblendspacechanges)

#### Defined in

[ue/ue.d.ts:17587](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17587)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[StaticClass](ue_ue.AnimNode_BlendSpacePlayer.md#staticclass)

#### Defined in

[ue/ue.d.ts:18129](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18129)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[StaticStruct](ue_ue.AnimNode_BlendSpacePlayer.md#staticstruct)

#### Defined in

[ue/ue.d.ts:18130](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18130)
