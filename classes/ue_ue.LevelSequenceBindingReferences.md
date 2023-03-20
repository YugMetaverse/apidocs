[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LevelSequenceBindingReferences

# Class: LevelSequenceBindingReferences

[ue/ue](../modules/ue_ue.md).LevelSequenceBindingReferences

## Table of contents

### Constructors

- [constructor](ue_ue.LevelSequenceBindingReferences.md#constructor)

### Properties

- [AnimSequenceInstances](ue_ue.LevelSequenceBindingReferences.md#animsequenceinstances)
- [BindingIdToReferences](ue_ue.LevelSequenceBindingReferences.md#bindingidtoreferences)
- [\_\_tid\_LevelSequenceBindingReferences\_\_](ue_ue.LevelSequenceBindingReferences.md#__tid_levelsequencebindingreferences__)

### Methods

- [StaticClass](ue_ue.LevelSequenceBindingReferences.md#staticclass)
- [StaticStruct](ue_ue.LevelSequenceBindingReferences.md#staticstruct)

## Constructors

### constructor

• **new LevelSequenceBindingReferences**()

#### Defined in

[ue/ue.d.ts:13998](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13998)

• **new LevelSequenceBindingReferences**(`BindingIdToReferences`, `AnimSequenceInstances`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BindingIdToReferences` | [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Guid`](ue_ue_s.Guid.md), [`LevelSequenceBindingReferenceArray`](ue_ue.LevelSequenceBindingReferenceArray.md)\> |
| `AnimSequenceInstances` | [`TSet`](../interfaces/ue_puerts.TSet.md)<[`Guid`](ue_ue_s.Guid.md)\> |

#### Defined in

[ue/ue.d.ts:13999](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13999)

## Properties

### AnimSequenceInstances

• **AnimSequenceInstances**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`Guid`](ue_ue_s.Guid.md)\>

#### Defined in

[ue/ue.d.ts:14001](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14001)

___

### BindingIdToReferences

• **BindingIdToReferences**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Guid`](ue_ue_s.Guid.md), [`LevelSequenceBindingReferenceArray`](ue_ue.LevelSequenceBindingReferenceArray.md)\>

#### Defined in

[ue/ue.d.ts:14000](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14000)

___

### \_\_tid\_LevelSequenceBindingReferences\_\_

• `Private` **\_\_tid\_LevelSequenceBindingReferences\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:14007](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14007)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:14005](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14005)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:14006](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14006)
