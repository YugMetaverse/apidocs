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

#### Defined in

[ue/ue.d.ts:14063](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14063)

## Properties

### ActorSettings

• **ActorSettings**: [`ActorRecordingSettings`](ue_ue.ActorRecordingSettings.md)

#### Defined in

[ue/ue.d.ts:14064](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14064)

___

### ActorToRecord

• **ActorToRecord**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Defined in

[ue/ue.d.ts:14074](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14074)

___

### AnimationSettings

• **AnimationSettings**: [`AnimationRecordingSettings`](ue_ue.AnimationRecordingSettings.md)

#### Defined in

[ue/ue.d.ts:14072](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14072)

___

### TakeNumber

• **TakeNumber**: `number`

#### Defined in

[ue/ue.d.ts:14069](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14069)

___

### TargetAnimation

• **TargetAnimation**: [`AnimSequence`](ue_ue.AnimSequence.md)

#### Defined in

[ue/ue.d.ts:14071](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14071)

___

### TargetLevelSequence

• **TargetLevelSequence**: [`LevelSequence`](ue_ue.LevelSequence.md)

#### Defined in

[ue/ue.d.ts:14067](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14067)

___

### TargetName

• **TargetName**: `string`

#### Defined in

[ue/ue.d.ts:14068](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14068)

___

### \_\_tid\_ActorRecording\_\_

• **\_\_tid\_ActorRecording\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:14079](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14079)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[__tid_Object__](ue_ue.SequenceRecordingBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_SequenceRecordingBase\_\_

• **\_\_tid\_SequenceRecordingBase\_\_**: `boolean`

#### Inherited from

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[__tid_SequenceRecordingBase__](ue_ue.SequenceRecordingBase.md#__tid_sequencerecordingbase__)

#### Defined in

[ue/ue.d.ts:13946](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13946)

___

### bActive

• **bActive**: `boolean`

#### Defined in

[ue/ue.d.ts:14065](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14065)

___

### bCreateLevelSequence

• **bCreateLevelSequence**: `boolean`

#### Defined in

[ue/ue.d.ts:14066](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14066)

___

### bRecordToPossessable

• **bRecordToPossessable**: `boolean`

#### Defined in

[ue/ue.d.ts:14073](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14073)

___

### bSpecifyTargetAnimation

• **bSpecifyTargetAnimation**: `boolean`

#### Defined in

[ue/ue.d.ts:14070](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14070)

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

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[ExecuteUbergraph](ue_ue.SequenceRecordingBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[GetClass](ue_ue.SequenceRecordingBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[GetName](ue_ue.SequenceRecordingBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[GetOuter](ue_ue.SequenceRecordingBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[GetWorld](ue_ue.SequenceRecordingBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:14076](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14076)

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

#### Defined in

[ue/ue.d.ts:14077](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14077)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SequenceRecordingBase](ue_ue.SequenceRecordingBase.md).[StaticClass](ue_ue.SequenceRecordingBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:14075](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14075)
