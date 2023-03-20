[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MediaPlayerRecording

# Class: MediaPlayerRecording

[ue/ue](../modules/ue_ue.md).MediaPlayerRecording

## Hierarchy

- [`SequenceRecordingBase`](ue_ue.SequenceRecordingBase.md)

  ↳ **`MediaPlayerRecording`**

## Table of contents

### Constructors

- [constructor](ue_ue.MediaPlayerRecording.md#constructor)

### Properties

- [MediaPlayerToRecord](ue_ue.MediaPlayerRecording.md#mediaplayertorecord)
- [RecordingSettings](ue_ue.MediaPlayerRecording.md#recordingsettings)
- [\_\_tid\_MediaPlayerRecording\_\_](ue_ue.MediaPlayerRecording.md#__tid_mediaplayerrecording__)
- [\_\_tid\_Object\_\_](ue_ue.MediaPlayerRecording.md#__tid_object__)
- [\_\_tid\_SequenceRecordingBase\_\_](ue_ue.MediaPlayerRecording.md#__tid_sequencerecordingbase__)

### Methods

- [CreateDefaultSubobject](ue_ue.MediaPlayerRecording.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MediaPlayerRecording.md#executeubergraph)
- [GetClass](ue_ue.MediaPlayerRecording.md#getclass)
- [GetName](ue_ue.MediaPlayerRecording.md#getname)
- [GetOuter](ue_ue.MediaPlayerRecording.md#getouter)
- [GetWorld](ue_ue.MediaPlayerRecording.md#getworld)
- [Find](ue_ue.MediaPlayerRecording.md#find)
- [Load](ue_ue.MediaPlayerRecording.md#load)
- [StaticClass](ue_ue.MediaPlayerRecording.md#staticclass)

## Constructors

### constructor

• **new MediaPlayerRecording**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[constructor](ue_ue.SequenceRecordingBase.md#constructor)

## Properties

### MediaPlayerToRecord

• **MediaPlayerToRecord**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`MediaPlayer`](ue_ue.MediaPlayer.md)\>

___

### RecordingSettings

• **RecordingSettings**: [`MediaPlayerRecordingSettings`](ue_ue.MediaPlayerRecordingSettings.md)

___

### \_\_tid\_MediaPlayerRecording\_\_

• **\_\_tid\_MediaPlayerRecording\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MediaPlayerRecording`](ue_ue.MediaPlayerRecording.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MediaPlayerRecording`](ue_ue.MediaPlayerRecording.md)

#### Overrides

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[Find](ue_ue.SequenceRecordingBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MediaPlayerRecording`](ue_ue.MediaPlayerRecording.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MediaPlayerRecording`](ue_ue.MediaPlayerRecording.md)

#### Overrides

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[Load](ue_ue.SequenceRecordingBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[StaticClass](ue_ue.SequenceRecordingBase.md#staticclass)
