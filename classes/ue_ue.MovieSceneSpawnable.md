[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneSpawnable

# Class: MovieSceneSpawnable

[ue/ue](../modules/ue_ue.md).MovieSceneSpawnable

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneSpawnable.md#constructor)

### Properties

- [ChildPossessables](ue_ue.MovieSceneSpawnable.md#childpossessables)
- [GeneratedClass](ue_ue.MovieSceneSpawnable.md#generatedclass)
- [Guid](ue_ue.MovieSceneSpawnable.md#guid)
- [LevelName](ue_ue.MovieSceneSpawnable.md#levelname)
- [Name](ue_ue.MovieSceneSpawnable.md#name)
- [ObjectTemplate](ue_ue.MovieSceneSpawnable.md#objecttemplate)
- [Ownership](ue_ue.MovieSceneSpawnable.md#ownership)
- [SpawnTransform](ue_ue.MovieSceneSpawnable.md#spawntransform)
- [Tags](ue_ue.MovieSceneSpawnable.md#tags)
- [\_\_tid\_MovieSceneSpawnable\_\_](ue_ue.MovieSceneSpawnable.md#__tid_moviescenespawnable__)
- [bContinuouslyRespawn](ue_ue.MovieSceneSpawnable.md#bcontinuouslyrespawn)

### Methods

- [StaticClass](ue_ue.MovieSceneSpawnable.md#staticclass)
- [StaticStruct](ue_ue.MovieSceneSpawnable.md#staticstruct)

## Constructors

### constructor

• **new MovieSceneSpawnable**()

• **new MovieSceneSpawnable**(`SpawnTransform`, `Tags`, `bContinuouslyRespawn`, `Guid`, `Name`, `ObjectTemplate`, `ChildPossessables`, `Ownership`, `GeneratedClass`, `LevelName`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SpawnTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `Tags` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `bContinuouslyRespawn` | `boolean` |
| `Guid` | [`Guid`](ue_ue_s.Guid.md) |
| `Name` | `string` |
| `ObjectTemplate` | [`Object`](ue_ue.Object.md) |
| `ChildPossessables` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\> |
| `Ownership` | [`ESpawnOwnership`](../enums/ue_ue.ESpawnOwnership.md) |
| `GeneratedClass` | [`Class`](ue_ue.Class.md) |
| `LevelName` | `string` |

## Properties

### ChildPossessables

• **ChildPossessables**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>

___

### GeneratedClass

• **GeneratedClass**: [`Class`](ue_ue.Class.md)

___

### Guid

• **Guid**: [`Guid`](ue_ue_s.Guid.md)

___

### LevelName

• **LevelName**: `string`

___

### Name

• **Name**: `string`

___

### ObjectTemplate

• **ObjectTemplate**: [`Object`](ue_ue.Object.md)

___

### Ownership

• **Ownership**: [`ESpawnOwnership`](../enums/ue_ue.ESpawnOwnership.md)

___

### SpawnTransform

• **SpawnTransform**: [`Transform`](ue_ue_s.Transform.md)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### \_\_tid\_MovieSceneSpawnable\_\_

• `Private` **\_\_tid\_MovieSceneSpawnable\_\_**: `boolean`

___

### bContinuouslyRespawn

• **bContinuouslyRespawn**: `boolean`

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
