[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BakedAnimationState

# Class: BakedAnimationState

[ue/ue](../modules/ue_ue.md).BakedAnimationState

## Table of contents

### Constructors

- [constructor](ue_ue.BakedAnimationState.md#constructor)

### Properties

- [EndNotify](ue_ue.BakedAnimationState.md#endnotify)
- [EntryRuleNodeIndex](ue_ue.BakedAnimationState.md#entryrulenodeindex)
- [FullyBlendedNotify](ue_ue.BakedAnimationState.md#fullyblendednotify)
- [LayerNodeIndices](ue_ue.BakedAnimationState.md#layernodeindices)
- [PlayerNodeIndices](ue_ue.BakedAnimationState.md#playernodeindices)
- [StartNotify](ue_ue.BakedAnimationState.md#startnotify)
- [StateName](ue_ue.BakedAnimationState.md#statename)
- [StateRootNodeIndex](ue_ue.BakedAnimationState.md#staterootnodeindex)
- [Transitions](ue_ue.BakedAnimationState.md#transitions)
- [\_\_tid\_BakedAnimationState\_\_](ue_ue.BakedAnimationState.md#__tid_bakedanimationstate__)
- [bAlwaysResetOnEntry](ue_ue.BakedAnimationState.md#balwaysresetonentry)
- [bIsAConduit](ue_ue.BakedAnimationState.md#bisaconduit)

### Methods

- [StaticClass](ue_ue.BakedAnimationState.md#staticclass)
- [StaticStruct](ue_ue.BakedAnimationState.md#staticstruct)

## Constructors

### constructor

• **new BakedAnimationState**()

• **new BakedAnimationState**(`StateName`, `Transitions`, `StateRootNodeIndex`, `StartNotify`, `EndNotify`, `FullyBlendedNotify`, `bIsAConduit`, `EntryRuleNodeIndex`, `PlayerNodeIndices`, `LayerNodeIndices`, `bAlwaysResetOnEntry`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `StateName` | `string` |
| `Transitions` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BakedStateExitTransition`](ue_ue.BakedStateExitTransition.md)\> |
| `StateRootNodeIndex` | `number` |
| `StartNotify` | `number` |
| `EndNotify` | `number` |
| `FullyBlendedNotify` | `number` |
| `bIsAConduit` | `boolean` |
| `EntryRuleNodeIndex` | `number` |
| `PlayerNodeIndices` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `LayerNodeIndices` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `bAlwaysResetOnEntry` | `boolean` |

## Properties

### EndNotify

• **EndNotify**: `number`

___

### EntryRuleNodeIndex

• **EntryRuleNodeIndex**: `number`

___

### FullyBlendedNotify

• **FullyBlendedNotify**: `number`

___

### LayerNodeIndices

• **LayerNodeIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### PlayerNodeIndices

• **PlayerNodeIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### StartNotify

• **StartNotify**: `number`

___

### StateName

• **StateName**: `string`

___

### StateRootNodeIndex

• **StateRootNodeIndex**: `number`

___

### Transitions

• **Transitions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BakedStateExitTransition`](ue_ue.BakedStateExitTransition.md)\>

___

### \_\_tid\_BakedAnimationState\_\_

• `Private` **\_\_tid\_BakedAnimationState\_\_**: `boolean`

___

### bAlwaysResetOnEntry

• **bAlwaysResetOnEntry**: `boolean`

___

### bIsAConduit

• **bIsAConduit**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
