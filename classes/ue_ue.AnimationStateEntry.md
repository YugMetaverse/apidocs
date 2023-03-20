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

#### Defined in

[ue/ue.d.ts:17030](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17030)

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

#### Defined in

[ue/ue.d.ts:17031](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17031)

## Properties

### AnimationSetups

• **AnimationSetups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationSetup`](ue_ue.AnimationSetup.md)\>

#### Defined in

[ue/ue.d.ts:17033](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17033)

___

### BlendTime

• **BlendTime**: `number`

#### Defined in

[ue/ue.d.ts:17036](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17036)

___

### MaximumNumberOfConcurrentInstances

• **MaximumNumberOfConcurrentInstances**: [`PerPlatformInt`](ue_ue.PerPlatformInt.md)

#### Defined in

[ue/ue.d.ts:17040](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17040)

___

### NextState

• **NextState**: `number`

#### Defined in

[ue/ue.d.ts:17039](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17039)

___

### State

• **State**: `number`

#### Defined in

[ue/ue.d.ts:17032](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17032)

___

### WiggleTimePercentage

• **WiggleTimePercentage**: `number`

#### Defined in

[ue/ue.d.ts:17041](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17041)

___

### \_\_tid\_AnimationStateEntry\_\_

• `Private` **\_\_tid\_AnimationStateEntry\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:17048](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17048)

___

### bAdditive

• **bAdditive**: `boolean`

#### Defined in

[ue/ue.d.ts:17035](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17035)

___

### bOnDemand

• **bOnDemand**: `boolean`

#### Defined in

[ue/ue.d.ts:17034](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17034)

___

### bRequiresCurves

• **bRequiresCurves**: `boolean`

#### Defined in

[ue/ue.d.ts:17042](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17042)

___

### bReturnToPreviousState

• **bReturnToPreviousState**: `boolean`

#### Defined in

[ue/ue.d.ts:17037](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17037)

___

### bSetNextState

• **bSetNextState**: `boolean`

#### Defined in

[ue/ue.d.ts:17038](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17038)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:17046](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17046)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:17047](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17047)
