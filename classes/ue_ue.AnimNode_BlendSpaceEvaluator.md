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

• **new AnimNode_BlendSpaceEvaluator**(`NormalizedTime`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `NormalizedTime` | `number` |

#### Overrides

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[constructor](ue_ue.AnimNode_BlendSpacePlayer.md#constructor)

## Properties

### BlendSpace

• **BlendSpace**: [`BlendSpaceBase`](ue_ue.BlendSpaceBase.md)

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[BlendSpace](ue_ue.AnimNode_BlendSpacePlayer.md#blendspace)

___

### BlendWeight

• **BlendWeight**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[BlendWeight](ue_ue.AnimNode_BlendSpacePlayer.md#blendweight)

___

### GroupIndex

• **GroupIndex**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[GroupIndex](ue_ue.AnimNode_BlendSpacePlayer.md#groupindex)

___

### GroupRole

• **GroupRole**: [`EAnimGroupRole`](../enums/ue_ue.EAnimGroupRole.md)

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[GroupRole](ue_ue.AnimNode_BlendSpacePlayer.md#grouprole)

___

### InternalTimeAccumulator

• **InternalTimeAccumulator**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[InternalTimeAccumulator](ue_ue.AnimNode_BlendSpacePlayer.md#internaltimeaccumulator)

___

### NormalizedTime

• **NormalizedTime**: `number`

___

### PlayRate

• **PlayRate**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[PlayRate](ue_ue.AnimNode_BlendSpacePlayer.md#playrate)

___

### PreviousBlendSpace

• **PreviousBlendSpace**: [`BlendSpaceBase`](ue_ue.BlendSpaceBase.md)

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[PreviousBlendSpace](ue_ue.AnimNode_BlendSpacePlayer.md#previousblendspace)

___

### StartPosition

• **StartPosition**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[StartPosition](ue_ue.AnimNode_BlendSpacePlayer.md#startposition)

___

### X

• **X**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[X](ue_ue.AnimNode_BlendSpacePlayer.md#x)

___

### Y

• **Y**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[Y](ue_ue.AnimNode_BlendSpacePlayer.md#y)

___

### Z

• **Z**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[Z](ue_ue.AnimNode_BlendSpacePlayer.md#z)

___

### \_\_tid\_AnimNode\_BlendSpaceEvaluator\_\_

• `Private` **\_\_tid\_AnimNode\_BlendSpaceEvaluator\_\_**: `boolean`

___

### bIgnoreForRelevancyTest

• **bIgnoreForRelevancyTest**: `boolean`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[bIgnoreForRelevancyTest](ue_ue.AnimNode_BlendSpacePlayer.md#bignoreforrelevancytest)

___

### bLoop

• **bLoop**: `boolean`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[bLoop](ue_ue.AnimNode_BlendSpacePlayer.md#bloop)

___

### bResetPlayTimeWhenBlendSpaceChanges

• **bResetPlayTimeWhenBlendSpaceChanges**: `boolean`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[bResetPlayTimeWhenBlendSpaceChanges](ue_ue.AnimNode_BlendSpacePlayer.md#bresetplaytimewhenblendspacechanges)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[StaticClass](ue_ue.AnimNode_BlendSpacePlayer.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[StaticStruct](ue_ue.AnimNode_BlendSpacePlayer.md#staticstruct)
