[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DialogueWave

# Class: DialogueWave

[ue/ue](../modules/ue_ue.md).DialogueWave

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`DialogueWave`**

## Table of contents

### Constructors

- [constructor](ue_ue.DialogueWave.md#constructor)

### Properties

- [ContextMappings](ue_ue.DialogueWave.md#contextmappings)
- [LocalizationGUID](ue_ue.DialogueWave.md#localizationguid)
- [SpokenText](ue_ue.DialogueWave.md#spokentext)
- [SubtitleOverride](ue_ue.DialogueWave.md#subtitleoverride)
- [VoiceActorDirection](ue_ue.DialogueWave.md#voiceactordirection)
- [\_\_tid\_DialogueWave\_\_](ue_ue.DialogueWave.md#__tid_dialoguewave__)
- [\_\_tid\_Object\_\_](ue_ue.DialogueWave.md#__tid_object__)
- [bMature](ue_ue.DialogueWave.md#bmature)
- [bOverride\_SubtitleOverride](ue_ue.DialogueWave.md#boverride_subtitleoverride)

### Methods

- [CreateDefaultSubobject](ue_ue.DialogueWave.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DialogueWave.md#executeubergraph)
- [GetClass](ue_ue.DialogueWave.md#getclass)
- [GetName](ue_ue.DialogueWave.md#getname)
- [GetOuter](ue_ue.DialogueWave.md#getouter)
- [GetWorld](ue_ue.DialogueWave.md#getworld)
- [Find](ue_ue.DialogueWave.md#find)
- [Load](ue_ue.DialogueWave.md#load)
- [StaticClass](ue_ue.DialogueWave.md#staticclass)

## Constructors

### constructor

• **new DialogueWave**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ContextMappings

• **ContextMappings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DialogueContextMapping`](ue_ue.DialogueContextMapping.md)\>

___

### LocalizationGUID

• **LocalizationGUID**: [`Guid`](ue_ue_s.Guid.md)

___

### SpokenText

• **SpokenText**: `string`

___

### SubtitleOverride

• **SubtitleOverride**: `string`

___

### VoiceActorDirection

• **VoiceActorDirection**: `string`

___

### \_\_tid\_DialogueWave\_\_

• **\_\_tid\_DialogueWave\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bMature

• **bMature**: `boolean`

___

### bOverride\_SubtitleOverride

• **bOverride\_SubtitleOverride**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DialogueWave`](ue_ue.DialogueWave.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DialogueWave`](ue_ue.DialogueWave.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DialogueWave`](ue_ue.DialogueWave.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DialogueWave`](ue_ue.DialogueWave.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
