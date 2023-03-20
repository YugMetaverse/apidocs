[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SequenceRecorderActorGroup

# Class: SequenceRecorderActorGroup

[ue/ue](../modules/ue_ue.md).SequenceRecorderActorGroup

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`SequenceRecorderActorGroup`**

## Table of contents

### Constructors

- [constructor](ue_ue.SequenceRecorderActorGroup.md#constructor)

### Properties

- [GroupName](ue_ue.SequenceRecorderActorGroup.md#groupname)
- [RecordedActors](ue_ue.SequenceRecorderActorGroup.md#recordedactors)
- [SequenceName](ue_ue.SequenceRecorderActorGroup.md#sequencename)
- [SequenceRecordingBasePath](ue_ue.SequenceRecorderActorGroup.md#sequencerecordingbasepath)
- [TargetLevelSequence](ue_ue.SequenceRecorderActorGroup.md#targetlevelsequence)
- [\_\_tid\_Object\_\_](ue_ue.SequenceRecorderActorGroup.md#__tid_object__)
- [\_\_tid\_SequenceRecorderActorGroup\_\_](ue_ue.SequenceRecorderActorGroup.md#__tid_sequencerecorderactorgroup__)
- [bDuplicateTargetLevelSequence](ue_ue.SequenceRecorderActorGroup.md#bduplicatetargetlevelsequence)
- [bRecordTargetLevelSequenceLength](ue_ue.SequenceRecorderActorGroup.md#brecordtargetlevelsequencelength)
- [bSpecifyTargetLevelSequence](ue_ue.SequenceRecorderActorGroup.md#bspecifytargetlevelsequence)

### Methods

- [CreateDefaultSubobject](ue_ue.SequenceRecorderActorGroup.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SequenceRecorderActorGroup.md#executeubergraph)
- [GetClass](ue_ue.SequenceRecorderActorGroup.md#getclass)
- [GetName](ue_ue.SequenceRecorderActorGroup.md#getname)
- [GetOuter](ue_ue.SequenceRecorderActorGroup.md#getouter)
- [GetWorld](ue_ue.SequenceRecorderActorGroup.md#getworld)
- [Find](ue_ue.SequenceRecorderActorGroup.md#find)
- [Load](ue_ue.SequenceRecorderActorGroup.md#load)
- [StaticClass](ue_ue.SequenceRecorderActorGroup.md#staticclass)

## Constructors

### constructor

• **new SequenceRecorderActorGroup**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### GroupName

• **GroupName**: `string`

___

### RecordedActors

• **RecordedActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorRecording`](ue_ue.ActorRecording.md)\>

___

### SequenceName

• **SequenceName**: `string`

___

### SequenceRecordingBasePath

• **SequenceRecordingBasePath**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

___

### TargetLevelSequence

• **TargetLevelSequence**: [`LevelSequence`](ue_ue.LevelSequence.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_SequenceRecorderActorGroup\_\_

• **\_\_tid\_SequenceRecorderActorGroup\_\_**: `boolean`

___

### bDuplicateTargetLevelSequence

• **bDuplicateTargetLevelSequence**: `boolean`

___

### bRecordTargetLevelSequenceLength

• **bRecordTargetLevelSequenceLength**: `boolean`

___

### bSpecifyTargetLevelSequence

• **bSpecifyTargetLevelSequence**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SequenceRecorderActorGroup`](ue_ue.SequenceRecorderActorGroup.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SequenceRecorderActorGroup`](ue_ue.SequenceRecorderActorGroup.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SequenceRecorderActorGroup`](ue_ue.SequenceRecorderActorGroup.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SequenceRecorderActorGroup`](ue_ue.SequenceRecorderActorGroup.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
