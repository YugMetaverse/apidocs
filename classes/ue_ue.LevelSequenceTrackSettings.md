[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LevelSequenceTrackSettings

# Class: LevelSequenceTrackSettings

[ue/ue](../modules/ue_ue.md).LevelSequenceTrackSettings

## Table of contents

### Constructors

- [constructor](ue_ue.LevelSequenceTrackSettings.md#constructor)

### Properties

- [DefaultPropertyTracks](ue_ue.LevelSequenceTrackSettings.md#defaultpropertytracks)
- [DefaultTracks](ue_ue.LevelSequenceTrackSettings.md#defaulttracks)
- [ExcludeDefaultPropertyTracks](ue_ue.LevelSequenceTrackSettings.md#excludedefaultpropertytracks)
- [ExcludeDefaultTracks](ue_ue.LevelSequenceTrackSettings.md#excludedefaulttracks)
- [MatchingActorClass](ue_ue.LevelSequenceTrackSettings.md#matchingactorclass)
- [\_\_tid\_LevelSequenceTrackSettings\_\_](ue_ue.LevelSequenceTrackSettings.md#__tid_levelsequencetracksettings__)

### Methods

- [StaticClass](ue_ue.LevelSequenceTrackSettings.md#staticclass)
- [StaticStruct](ue_ue.LevelSequenceTrackSettings.md#staticstruct)

## Constructors

### constructor

• **new LevelSequenceTrackSettings**()

• **new LevelSequenceTrackSettings**(`MatchingActorClass`, `DefaultTracks`, `ExcludeDefaultTracks`, `DefaultPropertyTracks`, `ExcludeDefaultPropertyTracks`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MatchingActorClass` | [`SoftClassPath`](ue_ue.SoftClassPath.md) |
| `DefaultTracks` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoftClassPath`](ue_ue.SoftClassPath.md)\> |
| `ExcludeDefaultTracks` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoftClassPath`](ue_ue.SoftClassPath.md)\> |
| `DefaultPropertyTracks` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LevelSequencePropertyTrackSettings`](ue_ue.LevelSequencePropertyTrackSettings.md)\> |
| `ExcludeDefaultPropertyTracks` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LevelSequencePropertyTrackSettings`](ue_ue.LevelSequencePropertyTrackSettings.md)\> |

## Properties

### DefaultPropertyTracks

• **DefaultPropertyTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LevelSequencePropertyTrackSettings`](ue_ue.LevelSequencePropertyTrackSettings.md)\>

___

### DefaultTracks

• **DefaultTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoftClassPath`](ue_ue.SoftClassPath.md)\>

___

### ExcludeDefaultPropertyTracks

• **ExcludeDefaultPropertyTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LevelSequencePropertyTrackSettings`](ue_ue.LevelSequencePropertyTrackSettings.md)\>

___

### ExcludeDefaultTracks

• **ExcludeDefaultTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoftClassPath`](ue_ue.SoftClassPath.md)\>

___

### MatchingActorClass

• **MatchingActorClass**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### \_\_tid\_LevelSequenceTrackSettings\_\_

• `Private` **\_\_tid\_LevelSequenceTrackSettings\_\_**: `boolean`

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
