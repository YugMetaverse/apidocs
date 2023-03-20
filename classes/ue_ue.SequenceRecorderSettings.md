[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SequenceRecorderSettings

# Class: SequenceRecorderSettings

[ue/ue](../modules/ue_ue.md).SequenceRecorderSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`SequenceRecorderSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.SequenceRecorderSettings.md#constructor)

### Properties

- [ActorFilter](ue_ue.SequenceRecorderSettings.md#actorfilter)
- [ActorsAndPropertiesToRecord](ue_ue.SequenceRecorderSettings.md#actorsandpropertiestorecord)
- [AnimationSubDirectory](ue_ue.SequenceRecorderSettings.md#animationsubdirectory)
- [AudioGain](ue_ue.SequenceRecorderSettings.md#audiogain)
- [AudioSubDirectory](ue_ue.SequenceRecorderSettings.md#audiosubdirectory)
- [AudioTrackName](ue_ue.SequenceRecorderSettings.md#audiotrackname)
- [ClassesAndPropertiesToRecord](ue_ue.SequenceRecorderSettings.md#classesandpropertiestorecord)
- [DefaultAnimationSettings](ue_ue.SequenceRecorderSettings.md#defaultanimationsettings)
- [GlobalTimeDilation](ue_ue.SequenceRecorderSettings.md#globaltimedilation)
- [LevelSequenceActorsToTrigger](ue_ue.SequenceRecorderSettings.md#levelsequenceactorstotrigger)
- [NearbyActorRecordingProximity](ue_ue.SequenceRecorderSettings.md#nearbyactorrecordingproximity)
- [PerActorSettings](ue_ue.SequenceRecorderSettings.md#peractorsettings)
- [RecordAudio](ue_ue.SequenceRecorderSettings.md#recordaudio)
- [RecordingDelay](ue_ue.SequenceRecorderSettings.md#recordingdelay)
- [SequenceLength](ue_ue.SequenceRecorderSettings.md#sequencelength)
- [\_\_tid\_Object\_\_](ue_ue.SequenceRecorderSettings.md#__tid_object__)
- [\_\_tid\_SequenceRecorderSettings\_\_](ue_ue.SequenceRecorderSettings.md#__tid_sequencerecordersettings__)
- [bAllowLooping](ue_ue.SequenceRecorderSettings.md#ballowlooping)
- [bAutoSaveAsset](ue_ue.SequenceRecorderSettings.md#bautosaveasset)
- [bCreateLevelSequence](ue_ue.SequenceRecorderSettings.md#bcreatelevelsequence)
- [bIgnoreTimeDilation](ue_ue.SequenceRecorderSettings.md#bignoretimedilation)
- [bImmersiveMode](ue_ue.SequenceRecorderSettings.md#bimmersivemode)
- [bRecordNearbySpawnedActors](ue_ue.SequenceRecorderSettings.md#brecordnearbyspawnedactors)
- [bRecordSequencerSpawnedActors](ue_ue.SequenceRecorderSettings.md#brecordsequencerspawnedactors)
- [bRecordWorldSettingsActor](ue_ue.SequenceRecorderSettings.md#brecordworldsettingsactor)
- [bReduceKeys](ue_ue.SequenceRecorderSettings.md#breducekeys)
- [bReplaceRecordedAudio](ue_ue.SequenceRecorderSettings.md#breplacerecordedaudio)
- [bSplitAudioChannelsIntoSeparateTracks](ue_ue.SequenceRecorderSettings.md#bsplitaudiochannelsintoseparatetracks)

### Methods

- [CreateDefaultSubobject](ue_ue.SequenceRecorderSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SequenceRecorderSettings.md#executeubergraph)
- [GetClass](ue_ue.SequenceRecorderSettings.md#getclass)
- [GetName](ue_ue.SequenceRecorderSettings.md#getname)
- [GetOuter](ue_ue.SequenceRecorderSettings.md#getouter)
- [GetWorld](ue_ue.SequenceRecorderSettings.md#getworld)
- [Find](ue_ue.SequenceRecorderSettings.md#find)
- [Load](ue_ue.SequenceRecorderSettings.md#load)
- [StaticClass](ue_ue.SequenceRecorderSettings.md#staticclass)

## Constructors

### constructor

• **new SequenceRecorderSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ActorFilter

• **ActorFilter**: [`SequenceRecorderActorFilter`](ue_ue.SequenceRecorderActorFilter.md)

___

### ActorsAndPropertiesToRecord

• **ActorsAndPropertiesToRecord**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertiesToRecordForActorClass`](ue_ue.PropertiesToRecordForActorClass.md)\>

___

### AnimationSubDirectory

• **AnimationSubDirectory**: `string`

___

### AudioGain

• **AudioGain**: `number`

___

### AudioSubDirectory

• **AudioSubDirectory**: `string`

___

### AudioTrackName

• **AudioTrackName**: `string`

___

### ClassesAndPropertiesToRecord

• **ClassesAndPropertiesToRecord**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertiesToRecordForClass`](ue_ue.PropertiesToRecordForClass.md)\>

___

### DefaultAnimationSettings

• **DefaultAnimationSettings**: [`AnimationRecordingSettings`](ue_ue.AnimationRecordingSettings.md)

___

### GlobalTimeDilation

• **GlobalTimeDilation**: `number`

___

### LevelSequenceActorsToTrigger

• **LevelSequenceActorsToTrigger**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`LevelSequenceActor`](ue_ue.LevelSequenceActor.md)\>\>

___

### NearbyActorRecordingProximity

• **NearbyActorRecordingProximity**: `number`

___

### PerActorSettings

• **PerActorSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SettingsForActorClass`](ue_ue.SettingsForActorClass.md)\>

___

### RecordAudio

• **RecordAudio**: [`EAudioRecordingMode`](../enums/ue_ue.EAudioRecordingMode.md)

___

### RecordingDelay

• **RecordingDelay**: `number`

___

### SequenceLength

• **SequenceLength**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_SequenceRecorderSettings\_\_

• **\_\_tid\_SequenceRecorderSettings\_\_**: `boolean`

___

### bAllowLooping

• **bAllowLooping**: `boolean`

___

### bAutoSaveAsset

• **bAutoSaveAsset**: `boolean`

___

### bCreateLevelSequence

• **bCreateLevelSequence**: `boolean`

___

### bIgnoreTimeDilation

• **bIgnoreTimeDilation**: `boolean`

___

### bImmersiveMode

• **bImmersiveMode**: `boolean`

___

### bRecordNearbySpawnedActors

• **bRecordNearbySpawnedActors**: `boolean`

___

### bRecordSequencerSpawnedActors

• **bRecordSequencerSpawnedActors**: `boolean`

___

### bRecordWorldSettingsActor

• **bRecordWorldSettingsActor**: `boolean`

___

### bReduceKeys

• **bReduceKeys**: `boolean`

___

### bReplaceRecordedAudio

• **bReplaceRecordedAudio**: `boolean`

___

### bSplitAudioChannelsIntoSeparateTracks

• **bSplitAudioChannelsIntoSeparateTracks**: `boolean`

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SequenceRecorderSettings`](ue_ue.SequenceRecorderSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SequenceRecorderSettings`](ue_ue.SequenceRecorderSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SequenceRecorderSettings`](ue_ue.SequenceRecorderSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SequenceRecorderSettings`](ue_ue.SequenceRecorderSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
