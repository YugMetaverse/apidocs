[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneStringChannel

# Class: MovieSceneStringChannel

[ue/ue](../modules/ue_ue.md).MovieSceneStringChannel

## Hierarchy

- [`MovieSceneChannel`](ue_ue.MovieSceneChannel.md)

  ↳ **`MovieSceneStringChannel`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneStringChannel.md#constructor)

### Properties

- [DefaultValue](ue_ue.MovieSceneStringChannel.md#defaultvalue)
- [Times](ue_ue.MovieSceneStringChannel.md#times)
- [Values](ue_ue.MovieSceneStringChannel.md#values)
- [\_\_tid\_MovieSceneStringChannel\_\_](ue_ue.MovieSceneStringChannel.md#__tid_moviescenestringchannel__)
- [bHasDefaultValue](ue_ue.MovieSceneStringChannel.md#bhasdefaultvalue)

### Methods

- [StaticClass](ue_ue.MovieSceneStringChannel.md#staticclass)
- [StaticStruct](ue_ue.MovieSceneStringChannel.md#staticstruct)

## Constructors

### constructor

• **new MovieSceneStringChannel**()

#### Overrides

[MovieSceneChannel](ue_ue.MovieSceneChannel.md).[constructor](ue_ue.MovieSceneChannel.md#constructor)

• **new MovieSceneStringChannel**(`Times`, `Values`, `DefaultValue`, `bHasDefaultValue`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Times` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FrameNumber`](ue_ue.FrameNumber.md)\> |
| `Values` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `DefaultValue` | `string` |
| `bHasDefaultValue` | `boolean` |

#### Overrides

UE.MovieSceneChannel.constructor

## Properties

### DefaultValue

• **DefaultValue**: `string`

___

### Times

• **Times**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FrameNumber`](ue_ue.FrameNumber.md)\>

___

### Values

• **Values**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### \_\_tid\_MovieSceneStringChannel\_\_

• `Private` **\_\_tid\_MovieSceneStringChannel\_\_**: `boolean`

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
