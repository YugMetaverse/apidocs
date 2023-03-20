[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BakedAnimationStateMachine

# Class: BakedAnimationStateMachine

[ue/ue](../modules/ue_ue.md).BakedAnimationStateMachine

## Table of contents

### Constructors

- [constructor](ue_ue.BakedAnimationStateMachine.md#constructor)

### Properties

- [InitialState](ue_ue.BakedAnimationStateMachine.md#initialstate)
- [MachineName](ue_ue.BakedAnimationStateMachine.md#machinename)
- [States](ue_ue.BakedAnimationStateMachine.md#states)
- [Transitions](ue_ue.BakedAnimationStateMachine.md#transitions)
- [\_\_tid\_BakedAnimationStateMachine\_\_](ue_ue.BakedAnimationStateMachine.md#__tid_bakedanimationstatemachine__)

### Methods

- [StaticClass](ue_ue.BakedAnimationStateMachine.md#staticclass)
- [StaticStruct](ue_ue.BakedAnimationStateMachine.md#staticstruct)

## Constructors

### constructor

• **new BakedAnimationStateMachine**()

• **new BakedAnimationStateMachine**(`MachineName`, `InitialState`, `States`, `Transitions`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MachineName` | `string` |
| `InitialState` | `number` |
| `States` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BakedAnimationState`](ue_ue.BakedAnimationState.md)\> |
| `Transitions` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationTransitionBetweenStates`](ue_ue.AnimationTransitionBetweenStates.md)\> |

## Properties

### InitialState

• **InitialState**: `number`

___

### MachineName

• **MachineName**: `string`

___

### States

• **States**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BakedAnimationState`](ue_ue.BakedAnimationState.md)\>

___

### Transitions

• **Transitions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationTransitionBetweenStates`](ue_ue.AnimationTransitionBetweenStates.md)\>

___

### \_\_tid\_BakedAnimationStateMachine\_\_

• `Private` **\_\_tid\_BakedAnimationStateMachine\_\_**: `boolean`

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
