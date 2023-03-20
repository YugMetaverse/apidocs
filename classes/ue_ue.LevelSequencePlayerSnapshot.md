[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LevelSequencePlayerSnapshot

# Class: LevelSequencePlayerSnapshot

[ue/ue](../modules/ue_ue.md).LevelSequencePlayerSnapshot

## Table of contents

### Constructors

- [constructor](ue_ue.LevelSequencePlayerSnapshot.md#constructor)

### Properties

- [ActiveShot](ue_ue.LevelSequencePlayerSnapshot.md#activeshot)
- [CameraComponent](ue_ue.LevelSequencePlayerSnapshot.md#cameracomponent)
- [CurrentShotLocalTime](ue_ue.LevelSequencePlayerSnapshot.md#currentshotlocaltime)
- [CurrentShotName](ue_ue.LevelSequencePlayerSnapshot.md#currentshotname)
- [CurrentShotSourceTime](ue_ue.LevelSequencePlayerSnapshot.md#currentshotsourcetime)
- [MasterName](ue_ue.LevelSequencePlayerSnapshot.md#mastername)
- [MasterTime](ue_ue.LevelSequencePlayerSnapshot.md#mastertime)
- [Settings](ue_ue.LevelSequencePlayerSnapshot.md#settings)
- [ShotID](ue_ue.LevelSequencePlayerSnapshot.md#shotid)
- [SourceTime](ue_ue.LevelSequencePlayerSnapshot.md#sourcetime)
- [SourceTimecode](ue_ue.LevelSequencePlayerSnapshot.md#sourcetimecode)
- [\_\_tid\_LevelSequencePlayerSnapshot\_\_](ue_ue.LevelSequencePlayerSnapshot.md#__tid_levelsequenceplayersnapshot__)

### Methods

- [StaticClass](ue_ue.LevelSequencePlayerSnapshot.md#staticclass)
- [StaticStruct](ue_ue.LevelSequencePlayerSnapshot.md#staticstruct)

## Constructors

### constructor

• **new LevelSequencePlayerSnapshot**()

• **new LevelSequencePlayerSnapshot**(`MasterName`, `MasterTime`, `SourceTime`, `CurrentShotName`, `CurrentShotLocalTime`, `CurrentShotSourceTime`, `SourceTimecode`, `CameraComponent`, `Settings`, `ActiveShot`, `ShotID`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MasterName` | `string` |
| `MasterTime` | [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md) |
| `SourceTime` | [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md) |
| `CurrentShotName` | `string` |
| `CurrentShotLocalTime` | [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md) |
| `CurrentShotSourceTime` | [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md) |
| `SourceTimecode` | `string` |
| `CameraComponent` | [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`CameraComponent`](ue_ue.CameraComponent.md)\> |
| `Settings` | [`LevelSequenceSnapshotSettings`](ue_ue.LevelSequenceSnapshotSettings.md) |
| `ActiveShot` | [`LevelSequence`](ue_ue.LevelSequence.md) |
| `ShotID` | [`MovieSceneSequenceID`](ue_ue.MovieSceneSequenceID.md) |

## Properties

### ActiveShot

• **ActiveShot**: [`LevelSequence`](ue_ue.LevelSequence.md)

___

### CameraComponent

• **CameraComponent**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`CameraComponent`](ue_ue.CameraComponent.md)\>

___

### CurrentShotLocalTime

• **CurrentShotLocalTime**: [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

___

### CurrentShotName

• **CurrentShotName**: `string`

___

### CurrentShotSourceTime

• **CurrentShotSourceTime**: [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

___

### MasterName

• **MasterName**: `string`

___

### MasterTime

• **MasterTime**: [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

___

### Settings

• **Settings**: [`LevelSequenceSnapshotSettings`](ue_ue.LevelSequenceSnapshotSettings.md)

___

### ShotID

• **ShotID**: [`MovieSceneSequenceID`](ue_ue.MovieSceneSequenceID.md)

___

### SourceTime

• **SourceTime**: [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

___

### SourceTimecode

• **SourceTimecode**: `string`

___

### \_\_tid\_LevelSequencePlayerSnapshot\_\_

• `Private` **\_\_tid\_LevelSequencePlayerSnapshot\_\_**: `boolean`

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
