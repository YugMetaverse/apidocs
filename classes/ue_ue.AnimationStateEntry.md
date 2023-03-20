[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimationStateEntry

# Class: AnimationStateEntry

[ue/ue](../modules/ue_ue.md).AnimationStateEntry

## Table of contents

### Constructors

- [constructor](ue_ue.AnimationStateEntry.md#constructor)

### Properties

- [AnimationSetups](ue_ue.AnimationStateEntry.md#animationsetups)
- [BlendTime](ue_ue.AnimationStateEntry.md#blendtime)
- [MaximumNumberOfConcurrentInstances](ue_ue.AnimationStateEntry.md#maximumnumberofconcurrentinstances)
- [NextState](ue_ue.AnimationStateEntry.md#nextstate)
- [State](ue_ue.AnimationStateEntry.md#state)
- [WiggleTimePercentage](ue_ue.AnimationStateEntry.md#wiggletimepercentage)
- [\_\_tid\_AnimationStateEntry\_\_](ue_ue.AnimationStateEntry.md#__tid_animationstateentry__)
- [bAdditive](ue_ue.AnimationStateEntry.md#badditive)
- [bOnDemand](ue_ue.AnimationStateEntry.md#bondemand)
- [bRequiresCurves](ue_ue.AnimationStateEntry.md#brequirescurves)
- [bReturnToPreviousState](ue_ue.AnimationStateEntry.md#breturntopreviousstate)
- [bSetNextState](ue_ue.AnimationStateEntry.md#bsetnextstate)

### Methods

- [StaticClass](ue_ue.AnimationStateEntry.md#staticclass)
- [StaticStruct](ue_ue.AnimationStateEntry.md#staticstruct)

## Constructors

### constructor

• **new AnimationStateEntry**()

• **new AnimationStateEntry**(`State`, `AnimationSetups`, `bOnDemand`, `bAdditive`, `BlendTime`, `bReturnToPreviousState`, `bSetNextState`, `NextState`, `MaximumNumberOfConcurrentInstances`, `WiggleTimePercentage`, `bRequiresCurves`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `State` | `number` |
| `AnimationSetups` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationSetup`](ue_ue.AnimationSetup.md)\> |
| `bOnDemand` | `boolean` |
| `bAdditive` | `boolean` |
| `BlendTime` | `number` |
| `bReturnToPreviousState` | `boolean` |
| `bSetNextState` | `boolean` |
| `NextState` | `number` |
| `MaximumNumberOfConcurrentInstances` | [`PerPlatformInt`](ue_ue.PerPlatformInt.md) |
| `WiggleTimePercentage` | `number` |
| `bRequiresCurves` | `boolean` |

## Properties

### AnimationSetups

• **AnimationSetups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationSetup`](ue_ue.AnimationSetup.md)\>

___

### BlendTime

• **BlendTime**: `number`

___

### MaximumNumberOfConcurrentInstances

• **MaximumNumberOfConcurrentInstances**: [`PerPlatformInt`](ue_ue.PerPlatformInt.md)

___

### NextState

• **NextState**: `number`

___

### State

• **State**: `number`

___

### WiggleTimePercentage

• **WiggleTimePercentage**: `number`

___

### \_\_tid\_AnimationStateEntry\_\_

• `Private` **\_\_tid\_AnimationStateEntry\_\_**: `boolean`

___

### bAdditive

• **bAdditive**: `boolean`

___

### bOnDemand

• **bOnDemand**: `boolean`

___

### bRequiresCurves

• **bRequiresCurves**: `boolean`

___

### bReturnToPreviousState

• **bReturnToPreviousState**: `boolean`

___

### bSetNextState

• **bSetNextState**: `boolean`

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
