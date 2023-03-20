[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneActorReferenceData

# Class: MovieSceneActorReferenceData

[ue/ue](../modules/ue_ue.md).MovieSceneActorReferenceData

## Hierarchy

- [`MovieSceneChannel`](ue_ue.MovieSceneChannel.md)

  ↳ **`MovieSceneActorReferenceData`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneActorReferenceData.md#constructor)

### Properties

- [KeyTimes](ue_ue.MovieSceneActorReferenceData.md#keytimes)
- [KeyValues](ue_ue.MovieSceneActorReferenceData.md#keyvalues)
- [\_\_tid\_MovieSceneActorReferenceData\_\_](ue_ue.MovieSceneActorReferenceData.md#__tid_moviesceneactorreferencedata__)

### Methods

- [StaticClass](ue_ue.MovieSceneActorReferenceData.md#staticclass)
- [StaticStruct](ue_ue.MovieSceneActorReferenceData.md#staticstruct)

## Constructors

### constructor

• **new MovieSceneActorReferenceData**()

#### Overrides

[MovieSceneChannel](ue_ue.MovieSceneChannel.md).[constructor](ue_ue.MovieSceneChannel.md#constructor)

• **new MovieSceneActorReferenceData**(`KeyTimes`, `KeyValues`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyTimes` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FrameNumber`](ue_ue.FrameNumber.md)\> |
| `KeyValues` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneActorReferenceKey`](ue_ue.MovieSceneActorReferenceKey.md)\> |

#### Overrides

UE.MovieSceneChannel.constructor

## Properties

### KeyTimes

• **KeyTimes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FrameNumber`](ue_ue.FrameNumber.md)\>

___

### KeyValues

• **KeyValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneActorReferenceKey`](ue_ue.MovieSceneActorReferenceKey.md)\>

___

### \_\_tid\_MovieSceneActorReferenceData\_\_

• `Private` **\_\_tid\_MovieSceneActorReferenceData\_\_**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[MovieSceneChannel](ue_ue.MovieSceneChannel.md).[StaticClass](ue_ue.MovieSceneChannel.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[MovieSceneChannel](ue_ue.MovieSceneChannel.md).[StaticStruct](ue_ue.MovieSceneChannel.md#staticstruct)
