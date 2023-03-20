[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneEvaluationField

# Class: MovieSceneEvaluationField

[ue/ue](../modules/ue_ue.md).MovieSceneEvaluationField

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneEvaluationField.md#constructor)

### Properties

- [Groups](ue_ue.MovieSceneEvaluationField.md#groups)
- [MetaData](ue_ue.MovieSceneEvaluationField.md#metadata)
- [Ranges](ue_ue.MovieSceneEvaluationField.md#ranges)
- [Signature](ue_ue.MovieSceneEvaluationField.md#signature)
- [\_\_tid\_MovieSceneEvaluationField\_\_](ue_ue.MovieSceneEvaluationField.md#__tid_moviesceneevaluationfield__)

### Methods

- [StaticClass](ue_ue.MovieSceneEvaluationField.md#staticclass)
- [StaticStruct](ue_ue.MovieSceneEvaluationField.md#staticstruct)

## Constructors

### constructor

• **new MovieSceneEvaluationField**()

• **new MovieSceneEvaluationField**(`Signature`, `Ranges`, `Groups`, `MetaData`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Signature` | [`Guid`](ue_ue_s.Guid.md) |
| `Ranges` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)\> |
| `Groups` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneEvaluationGroup`](ue_ue.MovieSceneEvaluationGroup.md)\> |
| `MetaData` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneEvaluationMetaData`](ue_ue.MovieSceneEvaluationMetaData.md)\> |

## Properties

### Groups

• **Groups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneEvaluationGroup`](ue_ue.MovieSceneEvaluationGroup.md)\>

___

### MetaData

• **MetaData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneEvaluationMetaData`](ue_ue.MovieSceneEvaluationMetaData.md)\>

___

### Ranges

• **Ranges**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)\>

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

___

### \_\_tid\_MovieSceneEvaluationField\_\_

• `Private` **\_\_tid\_MovieSceneEvaluationField\_\_**: `boolean`

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
