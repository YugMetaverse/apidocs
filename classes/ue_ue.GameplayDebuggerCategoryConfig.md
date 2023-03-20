[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GameplayDebuggerCategoryConfig

# Class: GameplayDebuggerCategoryConfig

[ue/ue](../modules/ue_ue.md).GameplayDebuggerCategoryConfig

## Table of contents

### Constructors

- [constructor](ue_ue.GameplayDebuggerCategoryConfig.md#constructor)

### Properties

- [ActiveInGame](ue_ue.GameplayDebuggerCategoryConfig.md#activeingame)
- [ActiveInSimulate](ue_ue.GameplayDebuggerCategoryConfig.md#activeinsimulate)
- [CategoryName](ue_ue.GameplayDebuggerCategoryConfig.md#categoryname)
- [Hidden](ue_ue.GameplayDebuggerCategoryConfig.md#hidden)
- [InputHandlers](ue_ue.GameplayDebuggerCategoryConfig.md#inputhandlers)
- [SlotIdx](ue_ue.GameplayDebuggerCategoryConfig.md#slotidx)
- [\_\_tid\_GameplayDebuggerCategoryConfig\_\_](ue_ue.GameplayDebuggerCategoryConfig.md#__tid_gameplaydebuggercategoryconfig__)
- [bOverrideSlotIdx](ue_ue.GameplayDebuggerCategoryConfig.md#boverrideslotidx)

### Methods

- [StaticClass](ue_ue.GameplayDebuggerCategoryConfig.md#staticclass)
- [StaticStruct](ue_ue.GameplayDebuggerCategoryConfig.md#staticstruct)

## Constructors

### constructor

• **new GameplayDebuggerCategoryConfig**()

• **new GameplayDebuggerCategoryConfig**(`CategoryName`, `SlotIdx`, `ActiveInGame`, `ActiveInSimulate`, `Hidden`, `bOverrideSlotIdx`, `InputHandlers`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `CategoryName` | `string` |
| `SlotIdx` | `number` |
| `ActiveInGame` | [`EGameplayDebuggerOverrideMode`](../enums/ue_ue.EGameplayDebuggerOverrideMode.md) |
| `ActiveInSimulate` | [`EGameplayDebuggerOverrideMode`](../enums/ue_ue.EGameplayDebuggerOverrideMode.md) |
| `Hidden` | [`EGameplayDebuggerOverrideMode`](../enums/ue_ue.EGameplayDebuggerOverrideMode.md) |
| `bOverrideSlotIdx` | `boolean` |
| `InputHandlers` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameplayDebuggerInputConfig`](ue_ue.GameplayDebuggerInputConfig.md)\> |

## Properties

### ActiveInGame

• **ActiveInGame**: [`EGameplayDebuggerOverrideMode`](../enums/ue_ue.EGameplayDebuggerOverrideMode.md)

___

### ActiveInSimulate

• **ActiveInSimulate**: [`EGameplayDebuggerOverrideMode`](../enums/ue_ue.EGameplayDebuggerOverrideMode.md)

___

### CategoryName

• **CategoryName**: `string`

___

### Hidden

• **Hidden**: [`EGameplayDebuggerOverrideMode`](../enums/ue_ue.EGameplayDebuggerOverrideMode.md)

___

### InputHandlers

• **InputHandlers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameplayDebuggerInputConfig`](ue_ue.GameplayDebuggerInputConfig.md)\>

___

### SlotIdx

• **SlotIdx**: `number`

___

### \_\_tid\_GameplayDebuggerCategoryConfig\_\_

• `Private` **\_\_tid\_GameplayDebuggerCategoryConfig\_\_**: `boolean`

___

### bOverrideSlotIdx

• **bOverrideSlotIdx**: `boolean`

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
