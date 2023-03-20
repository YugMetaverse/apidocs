[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_BlendSpacePlayer

# Class: AnimNode\_BlendSpacePlayer

[ue/ue](../modules/ue_ue.md).AnimNode_BlendSpacePlayer

## Hierarchy

- [`AnimNode_AssetPlayerBase`](ue_ue.AnimNode_AssetPlayerBase.md)

  ↳ **`AnimNode_BlendSpacePlayer`**

  ↳↳ [`AnimNode_AimOffsetLookAt`](ue_ue.AnimNode_AimOffsetLookAt.md)

  ↳↳ [`AnimNode_BlendSpaceEvaluator`](ue_ue.AnimNode_BlendSpaceEvaluator.md)

  ↳↳ [`AnimNode_RotationOffsetBlendSpace`](ue_ue.AnimNode_RotationOffsetBlendSpace.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_BlendSpacePlayer.md#constructor)

### Properties

- [BlendSpace](ue_ue.AnimNode_BlendSpacePlayer.md#blendspace)
- [BlendWeight](ue_ue.AnimNode_BlendSpacePlayer.md#blendweight)
- [GroupIndex](ue_ue.AnimNode_BlendSpacePlayer.md#groupindex)
- [GroupRole](ue_ue.AnimNode_BlendSpacePlayer.md#grouprole)
- [InternalTimeAccumulator](ue_ue.AnimNode_BlendSpacePlayer.md#internaltimeaccumulator)
- [PlayRate](ue_ue.AnimNode_BlendSpacePlayer.md#playrate)
- [PreviousBlendSpace](ue_ue.AnimNode_BlendSpacePlayer.md#previousblendspace)
- [StartPosition](ue_ue.AnimNode_BlendSpacePlayer.md#startposition)
- [X](ue_ue.AnimNode_BlendSpacePlayer.md#x)
- [Y](ue_ue.AnimNode_BlendSpacePlayer.md#y)
- [Z](ue_ue.AnimNode_BlendSpacePlayer.md#z)
- [\_\_tid\_AnimNode\_BlendSpacePlayer\_\_](ue_ue.AnimNode_BlendSpacePlayer.md#__tid_animnode_blendspaceplayer__)
- [bIgnoreForRelevancyTest](ue_ue.AnimNode_BlendSpacePlayer.md#bignoreforrelevancytest)
- [bLoop](ue_ue.AnimNode_BlendSpacePlayer.md#bloop)
- [bResetPlayTimeWhenBlendSpaceChanges](ue_ue.AnimNode_BlendSpacePlayer.md#bresetplaytimewhenblendspacechanges)

### Methods

- [StaticClass](ue_ue.AnimNode_BlendSpacePlayer.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_BlendSpacePlayer.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_BlendSpacePlayer**()

#### Overrides

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[constructor](ue_ue.AnimNode_AssetPlayerBase.md#constructor)

• **new AnimNode_BlendSpacePlayer**(`X`, `Y`, `Z`, `PlayRate`, `bLoop`, `bResetPlayTimeWhenBlendSpaceChanges`, `StartPosition`, `BlendSpace`, `PreviousBlendSpace`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `X` | `number` |
| `Y` | `number` |
| `Z` | `number` |
| `PlayRate` | `number` |
| `bLoop` | `boolean` |
| `bResetPlayTimeWhenBlendSpaceChanges` | `boolean` |
| `StartPosition` | `number` |
| `BlendSpace` | [`BlendSpaceBase`](ue_ue.BlendSpaceBase.md) |
| `PreviousBlendSpace` | [`BlendSpaceBase`](ue_ue.BlendSpaceBase.md) |

#### Overrides

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[constructor](ue_ue.AnimNode_AssetPlayerBase.md#constructor)

## Properties

### BlendSpace

• **BlendSpace**: [`BlendSpaceBase`](ue_ue.BlendSpaceBase.md)

___

### BlendWeight

• **BlendWeight**: `number`

#### Inherited from

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[BlendWeight](ue_ue.AnimNode_AssetPlayerBase.md#blendweight)

___

### GroupIndex

• **GroupIndex**: `number`

#### Inherited from

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[GroupIndex](ue_ue.AnimNode_AssetPlayerBase.md#groupindex)

___

### GroupRole

• **GroupRole**: [`EAnimGroupRole`](../enums/ue_ue.EAnimGroupRole.md)

#### Inherited from

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[GroupRole](ue_ue.AnimNode_AssetPlayerBase.md#grouprole)

___

### InternalTimeAccumulator

• **InternalTimeAccumulator**: `number`

#### Inherited from

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[InternalTimeAccumulator](ue_ue.AnimNode_AssetPlayerBase.md#internaltimeaccumulator)

___

### PlayRate

• **PlayRate**: `number`

___

### PreviousBlendSpace

• **PreviousBlendSpace**: [`BlendSpaceBase`](ue_ue.BlendSpaceBase.md)

___

### StartPosition

• **StartPosition**: `number`

___

### X

• **X**: `number`

___

### Y

• **Y**: `number`

___

### Z

• **Z**: `number`

___

### \_\_tid\_AnimNode\_BlendSpacePlayer\_\_

• `Private` **\_\_tid\_AnimNode\_BlendSpacePlayer\_\_**: `boolean`

___

### bIgnoreForRelevancyTest

• **bIgnoreForRelevancyTest**: `boolean`

#### Inherited from

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[bIgnoreForRelevancyTest](ue_ue.AnimNode_AssetPlayerBase.md#bignoreforrelevancytest)

___

### bLoop

• **bLoop**: `boolean`

___

### bResetPlayTimeWhenBlendSpaceChanges

• **bResetPlayTimeWhenBlendSpaceChanges**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[StaticClass](ue_ue.AnimNode_AssetPlayerBase.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[StaticStruct](ue_ue.AnimNode_AssetPlayerBase.md#staticstruct)
