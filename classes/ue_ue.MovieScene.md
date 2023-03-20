[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieScene

# Class: MovieScene

[ue/ue](../modules/ue_ue.md).MovieScene

## Hierarchy

- [`MovieSceneSignedObject`](ue_ue.MovieSceneSignedObject.md)

  ↳ **`MovieScene`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieScene.md#constructor)

### Properties

- [BindingGroups](ue_ue.MovieScene.md#bindinggroups)
- [CameraCutTrack](ue_ue.MovieScene.md#cameracuttrack)
- [ClockSource](ue_ue.MovieScene.md#clocksource)
- [DisplayRate](ue_ue.MovieScene.md#displayrate)
- [EditorData](ue_ue.MovieScene.md#editordata)
- [EndTime](ue_ue.MovieScene.md#endtime)
- [EvaluationType](ue_ue.MovieScene.md#evaluationtype)
- [FixedFrameInterval](ue_ue.MovieScene.md#fixedframeinterval)
- [InTime](ue_ue.MovieScene.md#intime)
- [MarkedFrames](ue_ue.MovieScene.md#markedframes)
- [MasterTracks](ue_ue.MovieScene.md#mastertracks)
- [MuteNodes](ue_ue.MovieScene.md#mutenodes)
- [ObjectBindings](ue_ue.MovieScene.md#objectbindings)
- [ObjectsToDisplayNames](ue_ue.MovieScene.md#objectstodisplaynames)
- [ObjectsToLabels](ue_ue.MovieScene.md#objectstolabels)
- [OutTime](ue_ue.MovieScene.md#outtime)
- [PlaybackRange](ue_ue.MovieScene.md#playbackrange)
- [Possessables](ue_ue.MovieScene.md#possessables)
- [RootFolders](ue_ue.MovieScene.md#rootfolders)
- [SectionGroups](ue_ue.MovieScene.md#sectiongroups)
- [SelectionRange](ue_ue.MovieScene.md#selectionrange)
- [Signature](ue_ue.MovieScene.md#signature)
- [SoloNodes](ue_ue.MovieScene.md#solonodes)
- [Spawnables](ue_ue.MovieScene.md#spawnables)
- [StartTime](ue_ue.MovieScene.md#starttime)
- [TickResolution](ue_ue.MovieScene.md#tickresolution)
- [TimecodeSource](ue_ue.MovieScene.md#timecodesource)
- [\_\_tid\_MovieSceneSignedObject\_\_](ue_ue.MovieScene.md#__tid_moviescenesignedobject__)
- [\_\_tid\_MovieScene\_\_](ue_ue.MovieScene.md#__tid_moviescene__)
- [\_\_tid\_Object\_\_](ue_ue.MovieScene.md#__tid_object__)
- [bForceFixedFrameIntervalPlayback](ue_ue.MovieScene.md#bforcefixedframeintervalplayback)
- [bPlaybackRangeLocked](ue_ue.MovieScene.md#bplaybackrangelocked)
- [bReadOnly](ue_ue.MovieScene.md#breadonly)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieScene.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieScene.md#executeubergraph)
- [GetClass](ue_ue.MovieScene.md#getclass)
- [GetName](ue_ue.MovieScene.md#getname)
- [GetOuter](ue_ue.MovieScene.md#getouter)
- [GetWorld](ue_ue.MovieScene.md#getworld)
- [Find](ue_ue.MovieScene.md#find)
- [Load](ue_ue.MovieScene.md#load)
- [StaticClass](ue_ue.MovieScene.md#staticclass)

## Constructors

### constructor

• **new MovieScene**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[constructor](ue_ue.MovieSceneSignedObject.md#constructor)

## Properties

### BindingGroups

• **BindingGroups**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`MovieSceneObjectBindingIDs`](ue_ue.MovieSceneObjectBindingIDs.md)\>

___

### CameraCutTrack

• **CameraCutTrack**: [`MovieSceneTrack`](ue_ue.MovieSceneTrack.md)

___

### ClockSource

• **ClockSource**: [`EUpdateClockSource`](../enums/ue_ue.EUpdateClockSource.md)

___

### DisplayRate

• **DisplayRate**: [`FrameRate`](ue_ue.FrameRate.md)

___

### EditorData

• **EditorData**: [`MovieSceneEditorData`](ue_ue.MovieSceneEditorData.md)

___

### EndTime

• **EndTime**: `number`

___

### EvaluationType

• **EvaluationType**: [`EMovieSceneEvaluationType`](../enums/ue_ue.EMovieSceneEvaluationType.md)

___

### FixedFrameInterval

• **FixedFrameInterval**: `number`

___

### InTime

• **InTime**: `number`

___

### MarkedFrames

• **MarkedFrames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneMarkedFrame`](ue_ue.MovieSceneMarkedFrame.md)\>

___

### MasterTracks

• **MasterTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneTrack`](ue_ue.MovieSceneTrack.md)\>

___

### MuteNodes

• **MuteNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ObjectBindings

• **ObjectBindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneBinding`](ue_ue.MovieSceneBinding.md)\>

___

### ObjectsToDisplayNames

• **ObjectsToDisplayNames**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\>

___

### ObjectsToLabels

• **ObjectsToLabels**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`MovieSceneTrackLabels`](ue_ue.MovieSceneTrackLabels.md)\>

___

### OutTime

• **OutTime**: `number`

___

### PlaybackRange

• **PlaybackRange**: [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)

___

### Possessables

• **Possessables**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieScenePossessable`](ue_ue.MovieScenePossessable.md)\>

___

### RootFolders

• **RootFolders**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneFolder`](ue_ue.MovieSceneFolder.md)\>

___

### SectionGroups

• **SectionGroups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneSectionGroup`](ue_ue.MovieSceneSectionGroup.md)\>

___

### SelectionRange

• **SelectionRange**: [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[Signature](ue_ue.MovieSceneSignedObject.md#signature)

___

### SoloNodes

• **SoloNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### Spawnables

• **Spawnables**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneSpawnable`](ue_ue.MovieSceneSpawnable.md)\>

___

### StartTime

• **StartTime**: `number`

___

### TickResolution

• **TickResolution**: [`FrameRate`](ue_ue.FrameRate.md)

___

### TimecodeSource

• **TimecodeSource**: [`MovieSceneTimecodeSource`](ue_ue.MovieSceneTimecodeSource.md)

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneSignedObject.md#__tid_moviescenesignedobject__)

___

### \_\_tid\_MovieScene\_\_

• **\_\_tid\_MovieScene\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[__tid_Object__](ue_ue.MovieSceneSignedObject.md#__tid_object__)

___

### bForceFixedFrameIntervalPlayback

• **bForceFixedFrameIntervalPlayback**: `boolean`

___

### bPlaybackRangeLocked

• **bPlaybackRangeLocked**: `boolean`

___

### bReadOnly

• **bReadOnly**: `boolean`

## Methods

### CreateDefaultSubobject

▸ **CreateDefaultSubobject**(`p0`, `p1`, `p2`, `p3`, `p4`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `string` |
| `p1` | [`Class`](ue_ue.Class.md) |
| `p2` | [`Class`](ue_ue.Class.md) |
| `p3` | `boolean` |
| `p4` | `boolean` |

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[CreateDefaultSubobject](ue_ue.MovieSceneSignedObject.md#createdefaultsubobject)

___

### ExecuteUbergraph

▸ **ExecuteUbergraph**(`EntryPoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EntryPoint` | `number` |

#### Returns

`void`

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[ExecuteUbergraph](ue_ue.MovieSceneSignedObject.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetClass](ue_ue.MovieSceneSignedObject.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetName](ue_ue.MovieSceneSignedObject.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetOuter](ue_ue.MovieSceneSignedObject.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetWorld](ue_ue.MovieSceneSignedObject.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieScene`](ue_ue.MovieScene.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieScene`](ue_ue.MovieScene.md)

#### Overrides

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[Find](ue_ue.MovieSceneSignedObject.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieScene`](ue_ue.MovieScene.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieScene`](ue_ue.MovieScene.md)

#### Overrides

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[Load](ue_ue.MovieSceneSignedObject.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[StaticClass](ue_ue.MovieSceneSignedObject.md#staticclass)
