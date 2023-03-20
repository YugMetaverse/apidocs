[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_SequencePlayer

# Class: AnimNode\_SequencePlayer

[ue/ue](../modules/ue_ue.md).AnimNode_SequencePlayer

## Hierarchy

- [`AnimNode_AssetPlayerBase`](ue_ue.AnimNode_AssetPlayerBase.md)

  ↳ **`AnimNode_SequencePlayer`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_SequencePlayer.md#constructor)

### Properties

- [BlendWeight](ue_ue.AnimNode_SequencePlayer.md#blendweight)
- [GroupIndex](ue_ue.AnimNode_SequencePlayer.md#groupindex)
- [GroupRole](ue_ue.AnimNode_SequencePlayer.md#grouprole)
- [InternalTimeAccumulator](ue_ue.AnimNode_SequencePlayer.md#internaltimeaccumulator)
- [PlayRate](ue_ue.AnimNode_SequencePlayer.md#playrate)
- [PlayRateBasis](ue_ue.AnimNode_SequencePlayer.md#playratebasis)
- [PlayRateScaleBiasClamp](ue_ue.AnimNode_SequencePlayer.md#playratescalebiasclamp)
- [Sequence](ue_ue.AnimNode_SequencePlayer.md#sequence)
- [StartPosition](ue_ue.AnimNode_SequencePlayer.md#startposition)
- [\_\_tid\_AnimNode\_SequencePlayer\_\_](ue_ue.AnimNode_SequencePlayer.md#__tid_animnode_sequenceplayer__)
- [bIgnoreForRelevancyTest](ue_ue.AnimNode_SequencePlayer.md#bignoreforrelevancytest)
- [bLoopAnimation](ue_ue.AnimNode_SequencePlayer.md#bloopanimation)

### Methods

- [StaticClass](ue_ue.AnimNode_SequencePlayer.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_SequencePlayer.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_SequencePlayer**()

#### Overrides

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[constructor](ue_ue.AnimNode_AssetPlayerBase.md#constructor)

#### Defined in

[ue/ue.d.ts:19582](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19582)

• **new AnimNode_SequencePlayer**(`Sequence`, `PlayRateBasis`, `PlayRate`, `PlayRateScaleBiasClamp`, `StartPosition`, `bLoopAnimation`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Sequence` | [`AnimSequenceBase`](ue_ue.AnimSequenceBase.md) |
| `PlayRateBasis` | `number` |
| `PlayRate` | `number` |
| `PlayRateScaleBiasClamp` | [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md) |
| `StartPosition` | `number` |
| `bLoopAnimation` | `boolean` |

#### Overrides

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[constructor](ue_ue.AnimNode_AssetPlayerBase.md#constructor)

#### Defined in

[ue/ue.d.ts:19583](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19583)

## Properties

### BlendWeight

• **BlendWeight**: `number`

#### Inherited from

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[BlendWeight](ue_ue.AnimNode_AssetPlayerBase.md#blendweight)

#### Defined in

[ue/ue.d.ts:17569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17569)

___

### GroupIndex

• **GroupIndex**: `number`

#### Inherited from

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[GroupIndex](ue_ue.AnimNode_AssetPlayerBase.md#groupindex)

#### Defined in

[ue/ue.d.ts:17566](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17566)

___

### GroupRole

• **GroupRole**: [`EAnimGroupRole`](../enums/ue_ue.EAnimGroupRole.md)

#### Inherited from

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[GroupRole](ue_ue.AnimNode_AssetPlayerBase.md#grouprole)

#### Defined in

[ue/ue.d.ts:17567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17567)

___

### InternalTimeAccumulator

• **InternalTimeAccumulator**: `number`

#### Inherited from

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[InternalTimeAccumulator](ue_ue.AnimNode_AssetPlayerBase.md#internaltimeaccumulator)

#### Defined in

[ue/ue.d.ts:17570](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17570)

___

### PlayRate

• **PlayRate**: `number`

#### Defined in

[ue/ue.d.ts:19586](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19586)

___

### PlayRateBasis

• **PlayRateBasis**: `number`

#### Defined in

[ue/ue.d.ts:19585](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19585)

___

### PlayRateScaleBiasClamp

• **PlayRateScaleBiasClamp**: [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md)

#### Defined in

[ue/ue.d.ts:19587](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19587)

___

### Sequence

• **Sequence**: [`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)

#### Defined in

[ue/ue.d.ts:19584](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19584)

___

### StartPosition

• **StartPosition**: `number`

#### Defined in

[ue/ue.d.ts:19588](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19588)

___

### \_\_tid\_AnimNode\_SequencePlayer\_\_

• `Private` **\_\_tid\_AnimNode\_SequencePlayer\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:19595](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19595)

___

### bIgnoreForRelevancyTest

• **bIgnoreForRelevancyTest**: `boolean`

#### Inherited from

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[bIgnoreForRelevancyTest](ue_ue.AnimNode_AssetPlayerBase.md#bignoreforrelevancytest)

#### Defined in

[ue/ue.d.ts:17568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17568)

___

### bLoopAnimation

• **bLoopAnimation**: `boolean`

#### Defined in

[ue/ue.d.ts:19589](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19589)

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

[ue/ue.d.ts:19593](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19593)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[StaticStruct](ue_ue.AnimNode_AssetPlayerBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:19594](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19594)
