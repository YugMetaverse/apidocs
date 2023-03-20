[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ActorRecording

# Class: ActorRecording

[ue/ue](../modules/ue_ue.md).ActorRecording

## Hierarchy

- [`SequenceRecordingBase`](ue_ue.SequenceRecordingBase.md)

  ↳ **`ActorRecording`**

## Table of contents

### Constructors

- [constructor](ue_ue.ActorRecording.md#constructor)

### Properties

- [ActorSettings](ue_ue.ActorRecording.md#actorsettings)
- [ActorToRecord](ue_ue.ActorRecording.md#actortorecord)
- [AnimationSettings](ue_ue.ActorRecording.md#animationsettings)
- [TakeNumber](ue_ue.ActorRecording.md#takenumber)
- [TargetAnimation](ue_ue.ActorRecording.md#targetanimation)
- [TargetLevelSequence](ue_ue.ActorRecording.md#targetlevelsequence)
- [TargetName](ue_ue.ActorRecording.md#targetname)
- [\_\_tid\_ActorRecording\_\_](ue_ue.ActorRecording.md#__tid_actorrecording__)
- [\_\_tid\_Object\_\_](ue_ue.ActorRecording.md#__tid_object__)
- [\_\_tid\_SequenceRecordingBase\_\_](ue_ue.ActorRecording.md#__tid_sequencerecordingbase__)
- [bActive](ue_ue.ActorRecording.md#bactive)
- [bCreateLevelSequence](ue_ue.ActorRecording.md#bcreatelevelsequence)
- [bRecordToPossessable](ue_ue.ActorRecording.md#brecordtopossessable)
- [bSpecifyTargetAnimation](ue_ue.ActorRecording.md#bspecifytargetanimation)

### Methods

- [CreateDefaultSubobject](ue_ue.ActorRecording.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ActorRecording.md#executeubergraph)
- [GetClass](ue_ue.ActorRecording.md#getclass)
- [GetName](ue_ue.ActorRecording.md#getname)
- [GetOuter](ue_ue.ActorRecording.md#getouter)
- [GetWorld](ue_ue.ActorRecording.md#getworld)
- [Find](ue_ue.ActorRecording.md#find)
- [Load](ue_ue.ActorRecording.md#load)
- [StaticClass](ue_ue.ActorRecording.md#staticclass)

## Constructors

### constructor

• **new ActorRecording**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[constructor](ue_ue.SequenceRecordingBase.md#constructor)

## Properties

### ActorSettings

• **ActorSettings**: [`ActorRecordingSettings`](ue_ue.ActorRecordingSettings.md)

___

### ActorToRecord

• **ActorToRecord**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`Actor`](ue_ue.Actor.md)\>

___

### AnimationSettings

• **AnimationSettings**: [`AnimationRecordingSettings`](ue_ue.AnimationRecordingSettings.md)

___

### TakeNumber

• **TakeNumber**: `number`

___

### TargetAnimation

• **TargetAnimation**: [`AnimSequence`](ue_ue.AnimSequence.md)

___

### TargetLevelSequence

• **TargetLevelSequence**: [`LevelSequence`](ue_ue.LevelSequence.md)

___

### TargetName

• **TargetName**: `string`

___

### \_\_tid\_ActorRecording\_\_

• **\_\_tid\_ActorRecording\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[__tid_Object__](ue_ue.SequenceRecordingBase.md#__tid_object__)

___

### \_\_tid\_SequenceRecordingBase\_\_

• **\_\_tid\_SequenceRecordingBase\_\_**: `boolean`

#### Inherited from

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[__tid_SequenceRecordingBase__](ue_ue.SequenceRecordingBase.md#__tid_sequencerecordingbase__)

___

### bActive

• **bActive**: `boolean`

___

### bCreateLevelSequence

• **bCreateLevelSequence**: `boolean`

___

### bRecordToPossessable

• **bRecordToPossessable**: `boolean`

___

### bSpecifyTargetAnimation

• **bSpecifyTargetAnimation**: `boolean`

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

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[CreateDefaultSubobject](ue_ue.SequenceRecordingBase.md#createdefaultsubobject)

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

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[ExecuteUbergraph](ue_ue.SequenceRecordingBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[GetClass](ue_ue.SequenceRecordingBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[GetName](ue_ue.SequenceRecordingBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[GetOuter](ue_ue.SequenceRecordingBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[GetWorld](ue_ue.SequenceRecordingBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ActorRecording`](ue_ue.ActorRecording.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ActorRecording`](ue_ue.ActorRecording.md)

#### Overrides

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[Find](ue_ue.SequenceRecordingBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ActorRecording`](ue_ue.ActorRecording.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ActorRecording`](ue_ue.ActorRecording.md)

#### Overrides

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[Load](ue_ue.SequenceRecordingBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[StaticClass](ue_ue.SequenceRecordingBase.md#staticclass)
