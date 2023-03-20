[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneEvent

# Class: MovieSceneEvent

[ue/ue](../modules/ue_ue.md).MovieSceneEvent

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneEvent.md#constructor)

### Properties

- [BoundObjectPinName](ue_ue.MovieSceneEvent.md#boundobjectpinname)
- [CompiledFunctionName](ue_ue.MovieSceneEvent.md#compiledfunctionname)
- [FunctionEntry](ue_ue.MovieSceneEvent.md#functionentry)
- [GraphGuid](ue_ue.MovieSceneEvent.md#graphguid)
- [NodeGuid](ue_ue.MovieSceneEvent.md#nodeguid)
- [PayloadVariables](ue_ue.MovieSceneEvent.md#payloadvariables)
- [Ptrs](ue_ue.MovieSceneEvent.md#ptrs)
- [WeakCachedEndpoint](ue_ue.MovieSceneEvent.md#weakcachedendpoint)
- [\_\_tid\_MovieSceneEvent\_\_](ue_ue.MovieSceneEvent.md#__tid_moviesceneevent__)

### Methods

- [StaticClass](ue_ue.MovieSceneEvent.md#staticclass)
- [StaticStruct](ue_ue.MovieSceneEvent.md#staticstruct)

## Constructors

### constructor

• **new MovieSceneEvent**()

• **new MovieSceneEvent**(`Ptrs`, `PayloadVariables`, `CompiledFunctionName`, `BoundObjectPinName`, `GraphGuid`, `NodeGuid`, `WeakCachedEndpoint`, `FunctionEntry`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Ptrs` | [`MovieSceneEventPtrs`](ue_ue.MovieSceneEventPtrs.md) |
| `PayloadVariables` | [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`MovieSceneEventPayloadVariable`](ue_ue.MovieSceneEventPayloadVariable.md)\> |
| `CompiledFunctionName` | `string` |
| `BoundObjectPinName` | `string` |
| `GraphGuid` | [`Guid`](ue_ue_s.Guid.md) |
| `NodeGuid` | [`Guid`](ue_ue_s.Guid.md) |
| `WeakCachedEndpoint` | [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\> |
| `FunctionEntry` | [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\> |

## Properties

### BoundObjectPinName

• **BoundObjectPinName**: `string`

___

### CompiledFunctionName

• **CompiledFunctionName**: `string`

___

### FunctionEntry

• **FunctionEntry**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\>

___

### GraphGuid

• **GraphGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### PayloadVariables

• **PayloadVariables**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`MovieSceneEventPayloadVariable`](ue_ue.MovieSceneEventPayloadVariable.md)\>

___

### Ptrs

• **Ptrs**: [`MovieSceneEventPtrs`](ue_ue.MovieSceneEventPtrs.md)

___

### WeakCachedEndpoint

• **WeakCachedEndpoint**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\>

___

### \_\_tid\_MovieSceneEvent\_\_

• `Private` **\_\_tid\_MovieSceneEvent\_\_**: `boolean`

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
