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

## Properties

### MaxTransitionsPerFrame

• **MaxTransitionsPerFrame**: `number`

___

### StateMachineIndexInClass

• **StateMachineIndexInClass**: `number`

___

### \_\_tid\_AnimNode\_StateMachine\_\_

• `Private` **\_\_tid\_AnimNode\_StateMachine\_\_**: `boolean`

___

### bReinitializeOnBecomingRelevant

• **bReinitializeOnBecomingRelevant**: `boolean`

___

### bSkipFirstUpdateTransition

• **bSkipFirstUpdateTransition**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticClass](ue_ue.AnimNode_Base.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticStruct](ue_ue.AnimNode_Base.md#staticstruct)
