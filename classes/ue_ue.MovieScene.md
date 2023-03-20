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

#### Defined in

[ue/ue.d.ts:11833](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11833)

## Properties

### BindingGroups

• **BindingGroups**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`MovieSceneObjectBindingIDs`](ue_ue.MovieSceneObjectBindingIDs.md)\>

#### Defined in

[ue/ue.d.ts:11838](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11838)

___

### CameraCutTrack

• **CameraCutTrack**: [`MovieSceneTrack`](ue_ue.MovieSceneTrack.md)

#### Defined in

[ue/ue.d.ts:11840](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11840)

___

### ClockSource

• **ClockSource**: [`EUpdateClockSource`](../enums/ue_ue.EUpdateClockSource.md)

#### Defined in

[ue/ue.d.ts:11846](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11846)

___

### DisplayRate

• **DisplayRate**: [`FrameRate`](ue_ue.FrameRate.md)

#### Defined in

[ue/ue.d.ts:11844](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11844)

___

### EditorData

• **EditorData**: [`MovieSceneEditorData`](ue_ue.MovieSceneEditorData.md)

#### Defined in

[ue/ue.d.ts:11852](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11852)

___

### EndTime

• **EndTime**: `number`

#### Defined in

[ue/ue.d.ts:11860](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11860)

___

### EvaluationType

• **EvaluationType**: [`EMovieSceneEvaluationType`](../enums/ue_ue.EMovieSceneEvaluationType.md)

#### Defined in

[ue/ue.d.ts:11845](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11845)

___

### FixedFrameInterval

• **FixedFrameInterval**: `number`

#### Defined in

[ue/ue.d.ts:11862](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11862)

___

### InTime

• **InTime**: `number`

#### Defined in

[ue/ue.d.ts:11857](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11857)

___

### MarkedFrames

• **MarkedFrames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneMarkedFrame`](ue_ue.MovieSceneMarkedFrame.md)\>

#### Defined in

[ue/ue.d.ts:11847](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11847)

___

### MasterTracks

• **MasterTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneTrack`](ue_ue.MovieSceneTrack.md)\>

#### Defined in

[ue/ue.d.ts:11839](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11839)

___

### MuteNodes

• **MuteNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:11855](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11855)

___

### ObjectBindings

• **ObjectBindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneBinding`](ue_ue.MovieSceneBinding.md)\>

#### Defined in

[ue/ue.d.ts:11837](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11837)

___

### ObjectsToDisplayNames

• **ObjectsToDisplayNames**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\>

#### Defined in

[ue/ue.d.ts:11850](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11850)

___

### ObjectsToLabels

• **ObjectsToLabels**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`MovieSceneTrackLabels`](ue_ue.MovieSceneTrackLabels.md)\>

#### Defined in

[ue/ue.d.ts:11851](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11851)

___

### OutTime

• **OutTime**: `number`

#### Defined in

[ue/ue.d.ts:11858](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11858)

___

### PlaybackRange

• **PlaybackRange**: [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)

#### Defined in

[ue/ue.d.ts:11842](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11842)

___

### Possessables

• **Possessables**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieScenePossessable`](ue_ue.MovieScenePossessable.md)\>

#### Defined in

[ue/ue.d.ts:11836](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11836)

___

### RootFolders

• **RootFolders**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneFolder`](ue_ue.MovieSceneFolder.md)\>

#### Defined in

[ue/ue.d.ts:11853](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11853)

___

### SectionGroups

• **SectionGroups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneSectionGroup`](ue_ue.MovieSceneSectionGroup.md)\>

#### Defined in

[ue/ue.d.ts:11856](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11856)

___

### SelectionRange

• **SelectionRange**: [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)

#### Defined in

[ue/ue.d.ts:11841](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11841)

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[Signature](ue_ue.MovieSceneSignedObject.md#signature)

#### Defined in

[ue/ue.d.ts:11034](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11034)

___

### SoloNodes

• **SoloNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:11854](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11854)

___

### Spawnables

• **Spawnables**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneSpawnable`](ue_ue.MovieSceneSpawnable.md)\>

#### Defined in

[ue/ue.d.ts:11835](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11835)

___

### StartTime

• **StartTime**: `number`

#### Defined in

[ue/ue.d.ts:11859](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11859)

___

### TickResolution

• **TickResolution**: [`FrameRate`](ue_ue.FrameRate.md)

#### Defined in

[ue/ue.d.ts:11843](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11843)

___

### TimecodeSource

• **TimecodeSource**: [`MovieSceneTimecodeSource`](ue_ue.MovieSceneTimecodeSource.md)

#### Defined in

[ue/ue.d.ts:11834](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11834)

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneSignedObject.md#__tid_moviescenesignedobject__)

#### Defined in

[ue/ue.d.ts:11039](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11039)

___

### \_\_tid\_MovieScene\_\_

• **\_\_tid\_MovieScene\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:11867](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11867)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[__tid_Object__](ue_ue.MovieSceneSignedObject.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bForceFixedFrameIntervalPlayback

• **bForceFixedFrameIntervalPlayback**: `boolean`

#### Defined in

[ue/ue.d.ts:11861](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11861)

___

### bPlaybackRangeLocked

• **bPlaybackRangeLocked**: `boolean`

#### Defined in

[ue/ue.d.ts:11849](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11849)

___

### bReadOnly

• **bReadOnly**: `boolean`

#### Defined in

[ue/ue.d.ts:11848](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11848)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetClass](ue_ue.MovieSceneSignedObject.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetName](ue_ue.MovieSceneSignedObject.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetOuter](ue_ue.MovieSceneSignedObject.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetWorld](ue_ue.MovieSceneSignedObject.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:11864](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11864)

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

#### Defined in

[ue/ue.d.ts:11865](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11865)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[StaticClass](ue_ue.MovieSceneSignedObject.md#staticclass)

#### Defined in

[ue/ue.d.ts:11863](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11863)
