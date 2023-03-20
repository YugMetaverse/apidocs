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

#### Defined in

[ue/ue.d.ts:19555](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19555)

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

#### Defined in

[ue/ue.d.ts:19556](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19556)

## Properties

### BlendWeight

• **BlendWeight**: `number`

#### Inherited from

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[BlendWeight](ue_ue.AnimNode_AssetPlayerBase.md#blendweight)

#### Defined in

[ue/ue.d.ts:17569](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17569)

___

### ExplicitTime

• **ExplicitTime**: `number`

#### Defined in

[ue/ue.d.ts:19558](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19558)

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

### ReinitializationBehavior

• **ReinitializationBehavior**: [`ESequenceEvalReinit`](../enums/ue_ue.ESequenceEvalReinit.md)

#### Defined in

[ue/ue.d.ts:19561](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19561)

___

### Sequence

• **Sequence**: [`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)

#### Defined in

[ue/ue.d.ts:19557](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19557)

___

### StartPosition

• **StartPosition**: `number`

#### Defined in

[ue/ue.d.ts:19562](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19562)

___

### \_\_tid\_AnimNode\_SequenceEvaluator\_\_

• `Private` **\_\_tid\_AnimNode\_SequenceEvaluator\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:19568](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19568)

___

### bIgnoreForRelevancyTest

• **bIgnoreForRelevancyTest**: `boolean`

#### Inherited from

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[bIgnoreForRelevancyTest](ue_ue.AnimNode_AssetPlayerBase.md#bignoreforrelevancytest)

#### Defined in

[ue/ue.d.ts:17568](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17568)

___

### bShouldLoop

• **bShouldLoop**: `boolean`

#### Defined in

[ue/ue.d.ts:19559](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19559)

___

### bTeleportToExplicitTime

• **bTeleportToExplicitTime**: `boolean`

#### Defined in

[ue/ue.d.ts:19560](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19560)

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

[ue/ue.d.ts:19566](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19566)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_AssetPlayerBase](ue_ue.AnimNode_AssetPlayerBase.md).[StaticStruct](ue_ue.AnimNode_AssetPlayerBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:19567](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19567)
