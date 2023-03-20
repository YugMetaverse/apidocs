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

#### Defined in

[ue/ue.d.ts:30881](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30881)

## Properties

### ContextMappings

• **ContextMappings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DialogueContextMapping`](ue_ue.DialogueContextMapping.md)\>

#### Defined in

[ue/ue.d.ts:30887](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30887)

___

### LocalizationGUID

• **LocalizationGUID**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:30888](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30888)

___

### SpokenText

• **SpokenText**: `string`

#### Defined in

[ue/ue.d.ts:30884](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30884)

___

### SubtitleOverride

• **SubtitleOverride**: `string`

#### Defined in

[ue/ue.d.ts:30885](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30885)

___

### VoiceActorDirection

• **VoiceActorDirection**: `string`

#### Defined in

[ue/ue.d.ts:30886](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30886)

___

### \_\_tid\_DialogueWave\_\_

• **\_\_tid\_DialogueWave\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:30893](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30893)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bMature

• **bMature**: `boolean`

#### Defined in

[ue/ue.d.ts:30882](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30882)

___

### bOverride\_SubtitleOverride

• **bOverride\_SubtitleOverride**: `boolean`

#### Defined in

[ue/ue.d.ts:30883](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30883)

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

#### Defined in

[ue/ue.d.ts:30890](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30890)

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

#### Defined in

[ue/ue.d.ts:30891](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30891)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:30889](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30889)
