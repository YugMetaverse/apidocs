[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneEventChannel

# Class: MovieSceneEventChannel

[ue/ue](../modules/ue_ue.md).MovieSceneEventChannel

## Hierarchy

- [`MovieSceneChannel`](ue_ue.MovieSceneChannel.md)

  ↳ **`MovieSceneEventChannel`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneEventChannel.md#constructor)

### Properties

- [KeyTimes](ue_ue.MovieSceneEventChannel.md#keytimes)
- [KeyValues](ue_ue.MovieSceneEventChannel.md#keyvalues)
- [\_\_tid\_MovieSceneEventChannel\_\_](ue_ue.MovieSceneEventChannel.md#__tid_moviesceneeventchannel__)

### Methods

- [StaticClass](ue_ue.MovieSceneEventChannel.md#staticclass)
- [StaticStruct](ue_ue.MovieSceneEventChannel.md#staticstruct)

## Constructors

### constructor

• **new MovieSceneEventChannel**()

#### Overrides

[MovieSceneChannel](ue_ue.MovieSceneChannel.md).[constructor](ue_ue.MovieSceneChannel.md#constructor)

• **new MovieSceneEventChannel**(`KeyTimes`, `KeyValues`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyTimes` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FrameNumber`](ue_ue.FrameNumber.md)\> |
| `KeyValues` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneEvent`](ue_ue.MovieSceneEvent.md)\> |

#### Overrides

UE.MovieSceneChannel.constructor

## Properties

### KeyTimes

• **KeyTimes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FrameNumber`](ue_ue.FrameNumber.md)\>

___

### KeyValues

• **KeyValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneEvent`](ue_ue.MovieSceneEvent.md)\>

___

### \_\_tid\_MovieSceneEventChannel\_\_

• `Private` **\_\_tid\_MovieSceneEventChannel\_\_**: `boolean`

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
