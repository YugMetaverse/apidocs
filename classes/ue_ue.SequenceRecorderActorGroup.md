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

#### Defined in

[ue/ue.d.ts:60080](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60080)

## Properties

### GroupName

• **GroupName**: `string`

#### Defined in

[ue/ue.d.ts:60081](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60081)

___

### RecordedActors

• **RecordedActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorRecording`](ue_ue.ActorRecording.md)\>

#### Defined in

[ue/ue.d.ts:60088](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60088)

___

### SequenceName

• **SequenceName**: `string`

#### Defined in

[ue/ue.d.ts:60082](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60082)

___

### SequenceRecordingBasePath

• **SequenceRecordingBasePath**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

#### Defined in

[ue/ue.d.ts:60083](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60083)

___

### TargetLevelSequence

• **TargetLevelSequence**: [`LevelSequence`](ue_ue.LevelSequence.md)

#### Defined in

[ue/ue.d.ts:60085](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60085)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_SequenceRecorderActorGroup\_\_

• **\_\_tid\_SequenceRecorderActorGroup\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:60093](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60093)

___

### bDuplicateTargetLevelSequence

• **bDuplicateTargetLevelSequence**: `boolean`

#### Defined in

[ue/ue.d.ts:60086](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60086)

___

### bRecordTargetLevelSequenceLength

• **bRecordTargetLevelSequenceLength**: `boolean`

#### Defined in

[ue/ue.d.ts:60087](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60087)

___

### bSpecifyTargetLevelSequence

• **bSpecifyTargetLevelSequence**: `boolean`

#### Defined in

[ue/ue.d.ts:60084](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60084)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:60090](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60090)

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

#### Defined in

[ue/ue.d.ts:60091](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60091)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:60089](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60089)
