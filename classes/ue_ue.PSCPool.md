[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PSCPool

# Class: PSCPool

[ue/ue](../modules/ue_ue.md).PSCPool

## Table of contents

### Constructors

- [constructor](ue_ue.PSCPool.md#constructor)

### Properties

- [FreeElements](ue_ue.PSCPool.md#freeelements)
- [InUseComponents\_Auto](ue_ue.PSCPool.md#inusecomponents_auto)
- [InUseComponents\_Manual](ue_ue.PSCPool.md#inusecomponents_manual)
- [\_\_tid\_PSCPool\_\_](ue_ue.PSCPool.md#__tid_pscpool__)

### Methods

- [StaticClass](ue_ue.PSCPool.md#staticclass)
- [StaticStruct](ue_ue.PSCPool.md#staticstruct)

## Constructors

### constructor

• **new PSCPool**()

• **new PSCPool**(`FreeElements`, `InUseComponents_Auto`, `InUseComponents_Manual`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `FreeElements` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PSCPoolElem`](ue_ue.PSCPoolElem.md)\> |
| `InUseComponents_Auto` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleSystemComponent`](ue_ue.ParticleSystemComponent.md)\> |
| `InUseComponents_Manual` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleSystemComponent`](ue_ue.ParticleSystemComponent.md)\> |

## Properties

### FreeElements

• **FreeElements**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PSCPoolElem`](ue_ue.PSCPoolElem.md)\>

___

### InUseComponents\_Auto

• **InUseComponents\_Auto**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleSystemComponent`](ue_ue.ParticleSystemComponent.md)\>

___

### InUseComponents\_Manual

• **InUseComponents\_Manual**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleSystemComponent`](ue_ue.ParticleSystemComponent.md)\>

___

### \_\_tid\_PSCPool\_\_

• `Private` **\_\_tid\_PSCPool\_\_**: `boolean`

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
