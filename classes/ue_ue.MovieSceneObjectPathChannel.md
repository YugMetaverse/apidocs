[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneObjectPathChannel

# Class: MovieSceneObjectPathChannel

[ue/ue](../modules/ue_ue.md).MovieSceneObjectPathChannel

## Hierarchy

- [`MovieSceneChannel`](ue_ue.MovieSceneChannel.md)

  ↳ **`MovieSceneObjectPathChannel`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneObjectPathChannel.md#constructor)

### Properties

- [DefaultValue](ue_ue.MovieSceneObjectPathChannel.md#defaultvalue)
- [PropertyClass](ue_ue.MovieSceneObjectPathChannel.md#propertyclass)
- [Times](ue_ue.MovieSceneObjectPathChannel.md#times)
- [Values](ue_ue.MovieSceneObjectPathChannel.md#values)
- [\_\_tid\_MovieSceneObjectPathChannel\_\_](ue_ue.MovieSceneObjectPathChannel.md#__tid_moviesceneobjectpathchannel__)

### Methods

- [StaticClass](ue_ue.MovieSceneObjectPathChannel.md#staticclass)
- [StaticStruct](ue_ue.MovieSceneObjectPathChannel.md#staticstruct)

## Constructors

### constructor

• **new MovieSceneObjectPathChannel**()

#### Overrides

[MovieSceneChannel](ue_ue.MovieSceneChannel.md).[constructor](ue_ue.MovieSceneChannel.md#constructor)

• **new MovieSceneObjectPathChannel**(`PropertyClass`, `Times`, `Values`, `DefaultValue`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PropertyClass` | [`Class`](ue_ue.Class.md) |
| `Times` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FrameNumber`](ue_ue.FrameNumber.md)\> |
| `Values` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneObjectPathChannelKeyValue`](ue_ue.MovieSceneObjectPathChannelKeyValue.md)\> |
| `DefaultValue` | [`MovieSceneObjectPathChannelKeyValue`](ue_ue.MovieSceneObjectPathChannelKeyValue.md) |

#### Overrides

UE.MovieSceneChannel.constructor

## Properties

### DefaultValue

• **DefaultValue**: [`MovieSceneObjectPathChannelKeyValue`](ue_ue.MovieSceneObjectPathChannelKeyValue.md)

___

### PropertyClass

• **PropertyClass**: [`Class`](ue_ue.Class.md)

___

### Times

• **Times**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FrameNumber`](ue_ue.FrameNumber.md)\>

___

### Values

• **Values**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneObjectPathChannelKeyValue`](ue_ue.MovieSceneObjectPathChannelKeyValue.md)\>

___

### \_\_tid\_MovieSceneObjectPathChannel\_\_

• `Private` **\_\_tid\_MovieSceneObjectPathChannel\_\_**: `boolean`

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
