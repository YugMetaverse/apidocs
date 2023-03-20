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

#### Defined in

[ue/ue.d.ts:60170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60170)

## Properties

### ActorFilter

• **ActorFilter**: [`SequenceRecorderActorFilter`](ue_ue.SequenceRecorderActorFilter.md)

#### Defined in

[ue/ue.d.ts:60190](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60190)

___

### ActorsAndPropertiesToRecord

• **ActorsAndPropertiesToRecord**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertiesToRecordForActorClass`](ue_ue.PropertiesToRecordForActorClass.md)\>

#### Defined in

[ue/ue.d.ts:60195](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60195)

___

### AnimationSubDirectory

• **AnimationSubDirectory**: `string`

#### Defined in

[ue/ue.d.ts:60178](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60178)

___

### AudioGain

• **AudioGain**: `number`

#### Defined in

[ue/ue.d.ts:60180](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60180)

___

### AudioSubDirectory

• **AudioSubDirectory**: `string`

#### Defined in

[ue/ue.d.ts:60184](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60184)

___

### AudioTrackName

• **AudioTrackName**: `string`

#### Defined in

[ue/ue.d.ts:60183](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60183)

___

### ClassesAndPropertiesToRecord

• **ClassesAndPropertiesToRecord**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertiesToRecordForClass`](ue_ue.PropertiesToRecordForClass.md)\>

#### Defined in

[ue/ue.d.ts:60194](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60194)

___

### DefaultAnimationSettings

• **DefaultAnimationSettings**: [`AnimationRecordingSettings`](ue_ue.AnimationRecordingSettings.md)

#### Defined in

[ue/ue.d.ts:60192](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60192)

___

### GlobalTimeDilation

• **GlobalTimeDilation**: `number`

#### Defined in

[ue/ue.d.ts:60176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60176)

___

### LevelSequenceActorsToTrigger

• **LevelSequenceActorsToTrigger**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`LevelSequenceActor`](ue_ue.LevelSequenceActor.md)\>\>

#### Defined in

[ue/ue.d.ts:60191](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60191)

___

### NearbyActorRecordingProximity

• **NearbyActorRecordingProximity**: `number`

#### Defined in

[ue/ue.d.ts:60186](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60186)

___

### PerActorSettings

• **PerActorSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SettingsForActorClass`](ue_ue.SettingsForActorClass.md)\>

#### Defined in

[ue/ue.d.ts:60196](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60196)

___

### RecordAudio

• **RecordAudio**: [`EAudioRecordingMode`](../enums/ue_ue.EAudioRecordingMode.md)

#### Defined in

[ue/ue.d.ts:60179](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60179)

___

### RecordingDelay

• **RecordingDelay**: `number`

#### Defined in

[ue/ue.d.ts:60174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60174)

___

### SequenceLength

• **SequenceLength**: `number`

#### Defined in

[ue/ue.d.ts:60173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60173)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SequenceRecorderSettings\_\_

• **\_\_tid\_SequenceRecorderSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:60201](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60201)

___

### bAllowLooping

• **bAllowLooping**: `boolean`

#### Defined in

[ue/ue.d.ts:60175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60175)

___

### bAutoSaveAsset

• **bAutoSaveAsset**: `boolean`

#### Defined in

[ue/ue.d.ts:60189](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60189)

___

### bCreateLevelSequence

• **bCreateLevelSequence**: `boolean`

#### Defined in

[ue/ue.d.ts:60171](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60171)

___

### bIgnoreTimeDilation

• **bIgnoreTimeDilation**: `boolean`

#### Defined in

[ue/ue.d.ts:60177](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60177)

___

### bImmersiveMode

• **bImmersiveMode**: `boolean`

#### Defined in

[ue/ue.d.ts:60172](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60172)

___

### bRecordNearbySpawnedActors

• **bRecordNearbySpawnedActors**: `boolean`

#### Defined in

[ue/ue.d.ts:60185](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60185)

___

### bRecordSequencerSpawnedActors

• **bRecordSequencerSpawnedActors**: `boolean`

#### Defined in

[ue/ue.d.ts:60193](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60193)

___

### bRecordWorldSettingsActor

• **bRecordWorldSettingsActor**: `boolean`

#### Defined in

[ue/ue.d.ts:60187](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60187)

___

### bReduceKeys

• **bReduceKeys**: `boolean`

#### Defined in

[ue/ue.d.ts:60188](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60188)

___

### bReplaceRecordedAudio

• **bReplaceRecordedAudio**: `boolean`

#### Defined in

[ue/ue.d.ts:60182](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60182)

___

### bSplitAudioChannelsIntoSeparateTracks

• **bSplitAudioChannelsIntoSeparateTracks**: `boolean`

#### Defined in

[ue/ue.d.ts:60181](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60181)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:60198](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60198)

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

#### Defined in

[ue/ue.d.ts:60199](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60199)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:60197](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60197)
