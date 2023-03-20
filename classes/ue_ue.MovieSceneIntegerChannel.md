[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneIntegerChannel

# Class: MovieSceneIntegerChannel

[ue/ue](../modules/ue_ue.md).MovieSceneIntegerChannel

## Hierarchy

- [`MovieSceneChannel`](ue_ue.MovieSceneChannel.md)

  ↳ **`MovieSceneIntegerChannel`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneIntegerChannel.md#constructor)

### Properties

- [DefaultValue](ue_ue.MovieSceneIntegerChannel.md#defaultvalue)
- [Times](ue_ue.MovieSceneIntegerChannel.md#times)
- [Values](ue_ue.MovieSceneIntegerChannel.md#values)
- [\_\_tid\_MovieSceneIntegerChannel\_\_](ue_ue.MovieSceneIntegerChannel.md#__tid_moviesceneintegerchannel__)
- [bHasDefaultValue](ue_ue.MovieSceneIntegerChannel.md#bhasdefaultvalue)

### Methods

- [StaticClass](ue_ue.MovieSceneIntegerChannel.md#staticclass)
- [StaticStruct](ue_ue.MovieSceneIntegerChannel.md#staticstruct)

## Constructors

### constructor

• **new MovieSceneIntegerChannel**()

#### Overrides

[MovieSceneChannel](ue_ue.MovieSceneChannel.md).[constructor](ue_ue.MovieSceneChannel.md#constructor)

• **new MovieSceneIntegerChannel**(`Times`, `DefaultValue`, `bHasDefaultValue`, `Values`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Times` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FrameNumber`](ue_ue.FrameNumber.md)\> |
| `DefaultValue` | `number` |
| `bHasDefaultValue` | `boolean` |
| `Values` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Overrides

UE.MovieSceneChannel.constructor

## Properties

### DefaultValue

• **DefaultValue**: `number`

___

### Times

• **Times**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FrameNumber`](ue_ue.FrameNumber.md)\>

___

### Values

• **Values**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### \_\_tid\_MovieSceneIntegerChannel\_\_

• `Private` **\_\_tid\_MovieSceneIntegerChannel\_\_**: `boolean`

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
