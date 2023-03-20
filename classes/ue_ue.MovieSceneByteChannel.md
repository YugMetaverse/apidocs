[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneByteChannel

# Class: MovieSceneByteChannel

[ue/ue](../modules/ue_ue.md).MovieSceneByteChannel

## Hierarchy

- [`MovieSceneChannel`](ue_ue.MovieSceneChannel.md)

  ↳ **`MovieSceneByteChannel`**

  ↳↳ [`MovieSceneParticleChannel`](ue_ue.MovieSceneParticleChannel.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneByteChannel.md#constructor)

### Properties

- [DefaultValue](ue_ue.MovieSceneByteChannel.md#defaultvalue)
- [Enum](ue_ue.MovieSceneByteChannel.md#enum)
- [Times](ue_ue.MovieSceneByteChannel.md#times)
- [Values](ue_ue.MovieSceneByteChannel.md#values)
- [\_\_tid\_MovieSceneByteChannel\_\_](ue_ue.MovieSceneByteChannel.md#__tid_moviescenebytechannel__)
- [bHasDefaultValue](ue_ue.MovieSceneByteChannel.md#bhasdefaultvalue)

### Methods

- [StaticClass](ue_ue.MovieSceneByteChannel.md#staticclass)
- [StaticStruct](ue_ue.MovieSceneByteChannel.md#staticstruct)

## Constructors

### constructor

• **new MovieSceneByteChannel**()

#### Overrides

[MovieSceneChannel](ue_ue.MovieSceneChannel.md).[constructor](ue_ue.MovieSceneChannel.md#constructor)

• **new MovieSceneByteChannel**(`Times`, `DefaultValue`, `bHasDefaultValue`, `Values`, `Enum`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Times` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FrameNumber`](ue_ue.FrameNumber.md)\> |
| `DefaultValue` | `number` |
| `bHasDefaultValue` | `boolean` |
| `Values` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `Enum` | [`Enum`](ue_ue.Enum.md) |

#### Overrides

UE.MovieSceneChannel.constructor

## Properties

### DefaultValue

• **DefaultValue**: `number`

___

### Enum

• **Enum**: [`Enum`](ue_ue.Enum.md)

___

### Times

• **Times**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FrameNumber`](ue_ue.FrameNumber.md)\>

___

### Values

• **Values**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### \_\_tid\_MovieSceneByteChannel\_\_

• `Private` **\_\_tid\_MovieSceneByteChannel\_\_**: `boolean`

___

### bHasDefaultValue

• **bHasDefaultValue**: `boolean`

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
