[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_StateMachine

# Class: AnimNode\_StateMachine

[ue/ue](../modules/ue_ue.md).AnimNode_StateMachine

## Hierarchy

- [`AnimNode_Base`](ue_ue.AnimNode_Base.md)

  ↳ **`AnimNode_StateMachine`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_StateMachine.md#constructor)

### Properties

- [MaxTransitionsPerFrame](ue_ue.AnimNode_StateMachine.md#maxtransitionsperframe)
- [StateMachineIndexInClass](ue_ue.AnimNode_StateMachine.md#statemachineindexinclass)
- [\_\_tid\_AnimNode\_StateMachine\_\_](ue_ue.AnimNode_StateMachine.md#__tid_animnode_statemachine__)
- [bReinitializeOnBecomingRelevant](ue_ue.AnimNode_StateMachine.md#breinitializeonbecomingrelevant)
- [bSkipFirstUpdateTransition](ue_ue.AnimNode_StateMachine.md#bskipfirstupdatetransition)

### Methods

- [StaticClass](ue_ue.AnimNode_StateMachine.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_StateMachine.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_StateMachine**()

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[constructor](ue_ue.AnimNode_Base.md#constructor)

#### Defined in

[ue/ue.d.ts:19701](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19701)

• **new AnimNode_StateMachine**(`StateMachineIndexInClass`, `MaxTransitionsPerFrame`, `bSkipFirstUpdateTransition`, `bReinitializeOnBecomingRelevant`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `StateMachineIndexInClass` | `number` |
| `MaxTransitionsPerFrame` | `number` |
| `bSkipFirstUpdateTransition` | `boolean` |
| `bReinitializeOnBecomingRelevant` | `boolean` |

#### Overrides

UE.AnimNode\_Base.constructor

#### Defined in

[ue/ue.d.ts:19702](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19702)

## Properties

### MaxTransitionsPerFrame

• **MaxTransitionsPerFrame**: `number`

#### Defined in

[ue/ue.d.ts:19704](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19704)

___

### StateMachineIndexInClass

• **StateMachineIndexInClass**: `number`

#### Defined in

[ue/ue.d.ts:19703](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19703)

___

### \_\_tid\_AnimNode\_StateMachine\_\_

• `Private` **\_\_tid\_AnimNode\_StateMachine\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:19712](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19712)

___

### bReinitializeOnBecomingRelevant

• **bReinitializeOnBecomingRelevant**: `boolean`

#### Defined in

[ue/ue.d.ts:19706](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19706)

___

### bSkipFirstUpdateTransition

• **bSkipFirstUpdateTransition**: `boolean`

#### Defined in

[ue/ue.d.ts:19705](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19705)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticClass](ue_ue.AnimNode_Base.md#staticclass)

#### Defined in

[ue/ue.d.ts:19710](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19710)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticStruct](ue_ue.AnimNode_Base.md#staticstruct)

#### Defined in

[ue/ue.d.ts:19711](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19711)
