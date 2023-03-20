[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ActorSequenceObjectReference

# Class: ActorSequenceObjectReference

[ue/ue](../modules/ue_ue.md).ActorSequenceObjectReference

## Table of contents

### Constructors

- [constructor](ue_ue.ActorSequenceObjectReference.md#constructor)

### Properties

- [ActorId](ue_ue.ActorSequenceObjectReference.md#actorid)
- [PathToComponent](ue_ue.ActorSequenceObjectReference.md#pathtocomponent)
- [Type](ue_ue.ActorSequenceObjectReference.md#type)
- [\_\_tid\_ActorSequenceObjectReference\_\_](ue_ue.ActorSequenceObjectReference.md#__tid_actorsequenceobjectreference__)

### Methods

- [StaticClass](ue_ue.ActorSequenceObjectReference.md#staticclass)
- [StaticStruct](ue_ue.ActorSequenceObjectReference.md#staticstruct)

## Constructors

### constructor

• **new ActorSequenceObjectReference**()

• **new ActorSequenceObjectReference**(`Type`, `ActorId`, `PathToComponent`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Type` | [`EActorSequenceObjectReferenceType`](../enums/ue_ue.EActorSequenceObjectReferenceType.md) |
| `ActorId` | [`Guid`](ue_ue_s.Guid.md) |
| `PathToComponent` | `string` |

## Properties

### ActorId

• **ActorId**: [`Guid`](ue_ue_s.Guid.md)

___

### PathToComponent

• **PathToComponent**: `string`

___

### Type

• **Type**: [`EActorSequenceObjectReferenceType`](../enums/ue_ue.EActorSequenceObjectReferenceType.md)

___

### \_\_tid\_ActorSequenceObjectReference\_\_

• `Private` **\_\_tid\_ActorSequenceObjectReference\_\_**: `boolean`

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
