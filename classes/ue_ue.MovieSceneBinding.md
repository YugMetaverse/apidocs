[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneBinding

# Class: MovieSceneBinding

[ue/ue](../modules/ue_ue.md).MovieSceneBinding

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneBinding.md#constructor)

### Properties

- [BindingName](ue_ue.MovieSceneBinding.md#bindingname)
- [ObjectGuid](ue_ue.MovieSceneBinding.md#objectguid)
- [SortingOrder](ue_ue.MovieSceneBinding.md#sortingorder)
- [Tracks](ue_ue.MovieSceneBinding.md#tracks)
- [\_\_tid\_MovieSceneBinding\_\_](ue_ue.MovieSceneBinding.md#__tid_moviescenebinding__)

### Methods

- [StaticClass](ue_ue.MovieSceneBinding.md#staticclass)
- [StaticStruct](ue_ue.MovieSceneBinding.md#staticstruct)

## Constructors

### constructor

• **new MovieSceneBinding**()

• **new MovieSceneBinding**(`ObjectGuid`, `BindingName`, `Tracks`, `SortingOrder`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ObjectGuid` | [`Guid`](ue_ue_s.Guid.md) |
| `BindingName` | `string` |
| `Tracks` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneTrack`](ue_ue.MovieSceneTrack.md)\> |
| `SortingOrder` | `number` |

## Properties

### BindingName

• **BindingName**: `string`

___

### ObjectGuid

• **ObjectGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### SortingOrder

• **SortingOrder**: `number`

___

### Tracks

• **Tracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneTrack`](ue_ue.MovieSceneTrack.md)\>

___

### \_\_tid\_MovieSceneBinding\_\_

• `Private` **\_\_tid\_MovieSceneBinding\_\_**: `boolean`

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
