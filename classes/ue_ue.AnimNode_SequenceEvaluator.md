[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_SequenceEvaluator

# Class: AnimNode\_SequenceEvaluator

[ue/ue](../modules/ue_ue.md).AnimNode_SequenceEvaluator

## Hierarchy

- [`AnimNode_AssetPlayerBase`](ue_ue.AnimNode_AssetPlayerBase.md)

  ↳ **`AnimNode_SequenceEvaluator`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_SequenceEvaluator.md#constructor)

### Properties

- [BlendWeight](ue_ue.AnimNode_SequenceEvaluator.md#blendweight)
- [ExplicitTime](ue_ue.AnimNode_SequenceEvaluator.md#explicittime)
- [GroupIndex](ue_ue.AnimNode_SequenceEvaluator.md#groupindex)
- [GroupRole](ue_ue.AnimNode_SequenceEvaluator.md#grouprole)
- [InternalTimeAccumulator](ue_ue.AnimNode_SequenceEvaluator.md#internaltimeaccumulator)
- [ReinitializationBehavior](ue_ue.AnimNode_SequenceEvaluator.md#reinitializationbehavior)
- [Sequence](ue_ue.AnimNode_SequenceEvaluator.md#sequence)
- [StartPosition](ue_ue.AnimNode_SequenceEvaluator.md#startposition)
- [\_\_tid\_AnimNode\_SequenceEvaluator\_\_](ue_ue.AnimNode_SequenceEvaluator.md#__tid_animnode_sequenceevaluator__)
- [bIgnoreForRelevancyTest](ue_ue.AnimNode_SequenceEvaluator.md#bignoreforrelevancytest)
- [bShouldLoop](ue_ue.AnimNode_SequenceEvaluator.md#bshouldloop)
- [bTeleportToExplicitTime](ue_ue.AnimNode_SequenceEvaluator.md#bteleporttoexplicittime)

### Methods

- [StaticClass](ue_ue.AnimNode_SequenceEvaluator.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_SequenceEvaluator.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_SequenceEvaluator**()

#### Overrides

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[constructor](ue_ue.AnimNode_AssetPlayerBase.md#constructor)

• **new AnimNode_SequenceEvaluator**(`Sequence`, `ExplicitTime`, `bShouldLoop`, `bTeleportToExplicitTime`, `ReinitializationBehavior`, `StartPosition`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Sequence` | [`AnimSequenceBase`](ue_ue.AnimSequenceBase.md) |
| `ExplicitTime` | `number` |
| `bShouldLoop` | `boolean` |
| `bTeleportToExplicitTime` | `boolean` |
| `ReinitializationBehavior` | [`ESequenceEvalReinit`](../enums/ue_ue.ESequenceEvalReinit.md) |
| `StartPosition` | `number` |

#### Overrides

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[constructor](ue_ue.AnimNode_AssetPlayerBase.md#constructor)

## Properties

### BlendWeight

• **BlendWeight**: `number`

#### Inherited from

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[BlendWeight](ue_ue.AnimNode_AssetPlayerBase.md#blendweight)

___

### ExplicitTime

• **ExplicitTime**: `number`

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

### ReinitializationBehavior

• **ReinitializationBehavior**: [`ESequenceEvalReinit`](../enums/ue_ue.ESequenceEvalReinit.md)

___

### Sequence

• **Sequence**: [`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)

___

### StartPosition

• **StartPosition**: `number`

___

### \_\_tid\_AnimNode\_SequenceEvaluator\_\_

• `Private` **\_\_tid\_AnimNode\_SequenceEvaluator\_\_**: `boolean`

___

### bIgnoreForRelevancyTest

• **bIgnoreForRelevancyTest**: `boolean`

#### Inherited from

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[bIgnoreForRelevancyTest](ue_ue.AnimNode_AssetPlayerBase.md#bignoreforrelevancytest)

___

### bShouldLoop

• **bShouldLoop**: `boolean`

___

### bTeleportToExplicitTime

• **bTeleportToExplicitTime**: `boolean`

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
