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

#### Defined in

[ue/ue.d.ts:4844](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4844)

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

#### Defined in

[ue/ue.d.ts:4845](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4845)

## Properties

### EndNotify

• **EndNotify**: `number`

#### Defined in

[ue/ue.d.ts:4850](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4850)

___

### EntryRuleNodeIndex

• **EntryRuleNodeIndex**: `number`

#### Defined in

[ue/ue.d.ts:4853](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4853)

___

### FullyBlendedNotify

• **FullyBlendedNotify**: `number`

#### Defined in

[ue/ue.d.ts:4851](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4851)

___

### LayerNodeIndices

• **LayerNodeIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:4855](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4855)

___

### PlayerNodeIndices

• **PlayerNodeIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:4854](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4854)

___

### StartNotify

• **StartNotify**: `number`

#### Defined in

[ue/ue.d.ts:4849](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4849)

___

### StateName

• **StateName**: `string`

#### Defined in

[ue/ue.d.ts:4846](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4846)

___

### StateRootNodeIndex

• **StateRootNodeIndex**: `number`

#### Defined in

[ue/ue.d.ts:4848](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4848)

___

### Transitions

• **Transitions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BakedStateExitTransition`](ue_ue.BakedStateExitTransition.md)\>

#### Defined in

[ue/ue.d.ts:4847](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4847)

___

### \_\_tid\_BakedAnimationState\_\_

• `Private` **\_\_tid\_BakedAnimationState\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:4862](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4862)

___

### bAlwaysResetOnEntry

• **bAlwaysResetOnEntry**: `boolean`

#### Defined in

[ue/ue.d.ts:4856](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4856)

___

### bIsAConduit

• **bIsAConduit**: `boolean`

#### Defined in

[ue/ue.d.ts:4852](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4852)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:4860](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4860)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:4861](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4861)
