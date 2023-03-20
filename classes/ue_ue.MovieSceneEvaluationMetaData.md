[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneEvaluationMetaData

# Class: MovieSceneEvaluationMetaData

[ue/ue](../modules/ue_ue.md).MovieSceneEvaluationMetaData

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneEvaluationMetaData.md#constructor)

### Properties

- [ActiveEntities](ue_ue.MovieSceneEvaluationMetaData.md#activeentities)
- [ActiveSequences](ue_ue.MovieSceneEvaluationMetaData.md#activesequences)
- [SubTemplateSerialNumbers](ue_ue.MovieSceneEvaluationMetaData.md#subtemplateserialnumbers)
- [\_\_tid\_MovieSceneEvaluationMetaData\_\_](ue_ue.MovieSceneEvaluationMetaData.md#__tid_moviesceneevaluationmetadata__)

### Methods

- [StaticClass](ue_ue.MovieSceneEvaluationMetaData.md#staticclass)
- [StaticStruct](ue_ue.MovieSceneEvaluationMetaData.md#staticstruct)

## Constructors

### constructor

• **new MovieSceneEvaluationMetaData**()

• **new MovieSceneEvaluationMetaData**(`ActiveSequences`, `ActiveEntities`, `SubTemplateSerialNumbers`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActiveSequences` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneSequenceID`](ue_ue.MovieSceneSequenceID.md)\> |
| `ActiveEntities` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneOrderedEvaluationKey`](ue_ue.MovieSceneOrderedEvaluationKey.md)\> |
| `SubTemplateSerialNumbers` | [`TMap`](../interfaces/ue_puerts.TMap.md)<[`MovieSceneSequenceID`](ue_ue.MovieSceneSequenceID.md), `number`\> |

## Properties

### ActiveEntities

• **ActiveEntities**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneOrderedEvaluationKey`](ue_ue.MovieSceneOrderedEvaluationKey.md)\>

___

### ActiveSequences

• **ActiveSequences**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneSequenceID`](ue_ue.MovieSceneSequenceID.md)\>

___

### SubTemplateSerialNumbers

• **SubTemplateSerialNumbers**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`MovieSceneSequenceID`](ue_ue.MovieSceneSequenceID.md), `number`\>

___

### \_\_tid\_MovieSceneEvaluationMetaData\_\_

• `Private` **\_\_tid\_MovieSceneEvaluationMetaData\_\_**: `boolean`

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
