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

## Properties

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

### PlayRateBasis

• **PlayRateBasis**: `number`

___

### PlayRateScaleBiasClamp

• **PlayRateScaleBiasClamp**: [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md)

___

### Sequence

• **Sequence**: [`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)

___

### StartPosition

• **StartPosition**: `number`

___

### \_\_tid\_AnimNode\_SequencePlayer\_\_

• `Private` **\_\_tid\_AnimNode\_SequencePlayer\_\_**: `boolean`

___

### bIgnoreForRelevancyTest

• **bIgnoreForRelevancyTest**: `boolean`

#### Inherited from

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[bIgnoreForRelevancyTest](ue_ue.AnimNode_AssetPlayerBase.md#bignoreforrelevancytest)

___

### bLoopAnimation

• **bLoopAnimation**: `boolean`

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
