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

#### Defined in

[ue/ue.d.ts:17580](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17580)

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

#### Defined in

[ue/ue.d.ts:17581](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17581)

## Properties

### BlendSpace

• **BlendSpace**: [`BlendSpaceBase`](ue_ue.BlendSpaceBase.md)

#### Defined in

[ue/ue.d.ts:17589](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17589)

___

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

### PlayRate

• **PlayRate**: `number`

#### Defined in

[ue/ue.d.ts:17585](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17585)

___

### PreviousBlendSpace

• **PreviousBlendSpace**: [`BlendSpaceBase`](ue_ue.BlendSpaceBase.md)

#### Defined in

[ue/ue.d.ts:17590](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17590)

___

### StartPosition

• **StartPosition**: `number`

#### Defined in

[ue/ue.d.ts:17588](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17588)

___

### X

• **X**: `number`

#### Defined in

[ue/ue.d.ts:17582](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17582)

___

### Y

• **Y**: `number`

#### Defined in

[ue/ue.d.ts:17583](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17583)

___

### Z

• **Z**: `number`

#### Defined in

[ue/ue.d.ts:17584](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17584)

___

### \_\_tid\_AnimNode\_BlendSpacePlayer\_\_

• `Private` **\_\_tid\_AnimNode\_BlendSpacePlayer\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:17596](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17596)

___

### bIgnoreForRelevancyTest

• **bIgnoreForRelevancyTest**: `boolean`

#### Inherited from

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[bIgnoreForRelevancyTest](ue_ue.AnimNode_AssetPlayerBase.md#bignoreforrelevancytest)

#### Defined in

[ue/ue.d.ts:17568](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17568)

___

### bLoop

• **bLoop**: `boolean`

#### Defined in

[ue/ue.d.ts:17586](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17586)

___

### bResetPlayTimeWhenBlendSpaceChanges

• **bResetPlayTimeWhenBlendSpaceChanges**: `boolean`

#### Defined in

[ue/ue.d.ts:17587](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17587)

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

[ue/ue.d.ts:17594](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17594)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[StaticStruct](ue_ue.AnimNode_AssetPlayerBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:17595](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17595)
