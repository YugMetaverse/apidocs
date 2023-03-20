[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneBoolChannel

# Class: MovieSceneBoolChannel

[ue/ue](../modules/ue_ue.md).MovieSceneBoolChannel

## Hierarchy

- [`MovieSceneChannel`](ue_ue.MovieSceneChannel.md)

  ↳ **`MovieSceneBoolChannel`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneBoolChannel.md#constructor)

### Properties

- [DefaultValue](ue_ue.MovieSceneBoolChannel.md#defaultvalue)
- [Times](ue_ue.MovieSceneBoolChannel.md#times)
- [Values](ue_ue.MovieSceneBoolChannel.md#values)
- [\_\_tid\_MovieSceneBoolChannel\_\_](ue_ue.MovieSceneBoolChannel.md#__tid_moviesceneboolchannel__)
- [bHasDefaultValue](ue_ue.MovieSceneBoolChannel.md#bhasdefaultvalue)

### Methods

- [StaticClass](ue_ue.MovieSceneBoolChannel.md#staticclass)
- [StaticStruct](ue_ue.MovieSceneBoolChannel.md#staticstruct)

## Constructors

### constructor

• **new MovieSceneBoolChannel**()

#### Overrides

[MovieSceneChannel](ue_ue.MovieSceneChannel.md).[constructor](ue_ue.MovieSceneChannel.md#constructor)

• **new MovieSceneBoolChannel**(`Times`, `DefaultValue`, `bHasDefaultValue`, `Values`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Times` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FrameNumber`](ue_ue.FrameNumber.md)\> |
| `DefaultValue` | `boolean` |
| `bHasDefaultValue` | `boolean` |
| `Values` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`boolean`\> |

#### Overrides

UE.MovieSceneChannel.constructor

## Properties

### DefaultValue

• **DefaultValue**: `boolean`

___

### Times

• **Times**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FrameNumber`](ue_ue.FrameNumber.md)\>

___

### Values

• **Values**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`boolean`\>

___

### \_\_tid\_MovieSceneBoolChannel\_\_

• `Private` **\_\_tid\_MovieSceneBoolChannel\_\_**: `boolean`

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
