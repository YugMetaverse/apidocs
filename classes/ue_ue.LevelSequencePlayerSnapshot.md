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

#### Defined in

[ue/ue.d.ts:22718](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22718)

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

#### Defined in

[ue/ue.d.ts:22719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22719)

## Properties

### ActiveShot

• **ActiveShot**: [`LevelSequence`](ue_ue.LevelSequence.md)

#### Defined in

[ue/ue.d.ts:22729](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22729)

___

### CameraComponent

• **CameraComponent**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`CameraComponent`](ue_ue.CameraComponent.md)\>

#### Defined in

[ue/ue.d.ts:22727](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22727)

___

### CurrentShotLocalTime

• **CurrentShotLocalTime**: [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Defined in

[ue/ue.d.ts:22724](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22724)

___

### CurrentShotName

• **CurrentShotName**: `string`

#### Defined in

[ue/ue.d.ts:22723](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22723)

___

### CurrentShotSourceTime

• **CurrentShotSourceTime**: [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Defined in

[ue/ue.d.ts:22725](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22725)

___

### MasterName

• **MasterName**: `string`

#### Defined in

[ue/ue.d.ts:22720](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22720)

___

### MasterTime

• **MasterTime**: [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Defined in

[ue/ue.d.ts:22721](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22721)

___

### Settings

• **Settings**: [`LevelSequenceSnapshotSettings`](ue_ue.LevelSequenceSnapshotSettings.md)

#### Defined in

[ue/ue.d.ts:22728](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22728)

___

### ShotID

• **ShotID**: [`MovieSceneSequenceID`](ue_ue.MovieSceneSequenceID.md)

#### Defined in

[ue/ue.d.ts:22730](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22730)

___

### SourceTime

• **SourceTime**: [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Defined in

[ue/ue.d.ts:22722](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22722)

___

### SourceTimecode

• **SourceTimecode**: `string`

#### Defined in

[ue/ue.d.ts:22726](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22726)

___

### \_\_tid\_LevelSequencePlayerSnapshot\_\_

• `Private` **\_\_tid\_LevelSequencePlayerSnapshot\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:22736](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22736)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:22734](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22734)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:22735](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22735)
