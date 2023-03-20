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

#### Defined in

[ue/ue.d.ts:51705](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51705)

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

#### Defined in

[ue/ue.d.ts:51706](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51706)

## Properties

### BoundObjectPinName

• **BoundObjectPinName**: `string`

#### Defined in

[ue/ue.d.ts:51710](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51710)

___

### CompiledFunctionName

• **CompiledFunctionName**: `string`

#### Defined in

[ue/ue.d.ts:51709](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51709)

___

### FunctionEntry

• **FunctionEntry**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:51714](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51714)

___

### GraphGuid

• **GraphGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:51711](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51711)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:51712](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51712)

___

### PayloadVariables

• **PayloadVariables**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`MovieSceneEventPayloadVariable`](ue_ue.MovieSceneEventPayloadVariable.md)\>

#### Defined in

[ue/ue.d.ts:51708](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51708)

___

### Ptrs

• **Ptrs**: [`MovieSceneEventPtrs`](ue_ue.MovieSceneEventPtrs.md)

#### Defined in

[ue/ue.d.ts:51707](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51707)

___

### WeakCachedEndpoint

• **WeakCachedEndpoint**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:51713](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51713)

___

### \_\_tid\_MovieSceneEvent\_\_

• `Private` **\_\_tid\_MovieSceneEvent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:51720](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51720)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:51718](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51718)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:51719](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51719)
