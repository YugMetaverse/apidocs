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

#### Defined in

[ue/ue.d.ts:11554](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11554)

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

#### Defined in

[ue/ue.d.ts:11555](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11555)

## Properties

### ChildPossessables

• **ChildPossessables**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>

#### Defined in

[ue/ue.d.ts:11562](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11562)

___

### GeneratedClass

• **GeneratedClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:11564](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11564)

___

### Guid

• **Guid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:11559](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11559)

___

### LevelName

• **LevelName**: `string`

#### Defined in

[ue/ue.d.ts:11565](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11565)

___

### Name

• **Name**: `string`

#### Defined in

[ue/ue.d.ts:11560](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11560)

___

### ObjectTemplate

• **ObjectTemplate**: [`Object`](ue_ue.Object.md)

#### Defined in

[ue/ue.d.ts:11561](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11561)

___

### Ownership

• **Ownership**: [`ESpawnOwnership`](../enums/ue_ue.ESpawnOwnership.md)

#### Defined in

[ue/ue.d.ts:11563](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11563)

___

### SpawnTransform

• **SpawnTransform**: [`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:11556](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11556)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:11557](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11557)

___

### \_\_tid\_MovieSceneSpawnable\_\_

• `Private` **\_\_tid\_MovieSceneSpawnable\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:11571](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11571)

___

### bContinuouslyRespawn

• **bContinuouslyRespawn**: `boolean`

#### Defined in

[ue/ue.d.ts:11558](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11558)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:11569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11569)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:11570](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11570)
