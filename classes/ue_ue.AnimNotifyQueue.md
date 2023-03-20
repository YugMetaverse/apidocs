[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNotifyQueue

# Class: AnimNotifyQueue

[ue/ue](../modules/ue_ue.md).AnimNotifyQueue

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNotifyQueue.md#constructor)

### Properties

- [AnimNotifies](ue_ue.AnimNotifyQueue.md#animnotifies)
- [UnfilteredMontageAnimNotifies](ue_ue.AnimNotifyQueue.md#unfilteredmontageanimnotifies)
- [\_\_tid\_AnimNotifyQueue\_\_](ue_ue.AnimNotifyQueue.md#__tid_animnotifyqueue__)

### Methods

- [StaticClass](ue_ue.AnimNotifyQueue.md#staticclass)
- [StaticStruct](ue_ue.AnimNotifyQueue.md#staticstruct)

## Constructors

### constructor

• **new AnimNotifyQueue**()

• **new AnimNotifyQueue**(`AnimNotifies`, `UnfilteredMontageAnimNotifies`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimNotifies` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyEventReference`](ue_ue.AnimNotifyEventReference.md)\> |
| `UnfilteredMontageAnimNotifies` | [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`AnimNotifyArray`](ue_ue.AnimNotifyArray.md)\> |

## Properties

### AnimNotifies

• **AnimNotifies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyEventReference`](ue_ue.AnimNotifyEventReference.md)\>

___

### UnfilteredMontageAnimNotifies

• **UnfilteredMontageAnimNotifies**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`AnimNotifyArray`](ue_ue.AnimNotifyArray.md)\>

___

### \_\_tid\_AnimNotifyQueue\_\_

• `Private` **\_\_tid\_AnimNotifyQueue\_\_**: `boolean`

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
