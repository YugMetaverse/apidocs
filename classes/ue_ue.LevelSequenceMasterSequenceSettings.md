[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LevelSequenceMasterSequenceSettings

# Class: LevelSequenceMasterSequenceSettings

[ue/ue](../modules/ue_ue.md).LevelSequenceMasterSequenceSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`LevelSequenceMasterSequenceSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.LevelSequenceMasterSequenceSettings.md#constructor)

### Properties

- [MasterSequenceBasePath](ue_ue.LevelSequenceMasterSequenceSettings.md#mastersequencebasepath)
- [MasterSequenceLevelSequenceToDuplicate](ue_ue.LevelSequenceMasterSequenceSettings.md#mastersequencelevelsequencetoduplicate)
- [MasterSequenceName](ue_ue.LevelSequenceMasterSequenceSettings.md#mastersequencename)
- [MasterSequenceNumShots](ue_ue.LevelSequenceMasterSequenceSettings.md#mastersequencenumshots)
- [MasterSequenceSuffix](ue_ue.LevelSequenceMasterSequenceSettings.md#mastersequencesuffix)
- [SubSequenceNames](ue_ue.LevelSequenceMasterSequenceSettings.md#subsequencenames)
- [\_\_tid\_LevelSequenceMasterSequenceSettings\_\_](ue_ue.LevelSequenceMasterSequenceSettings.md#__tid_levelsequencemastersequencesettings__)
- [\_\_tid\_Object\_\_](ue_ue.LevelSequenceMasterSequenceSettings.md#__tid_object__)
- [bInstanceSubSequences](ue_ue.LevelSequenceMasterSequenceSettings.md#binstancesubsequences)

### Methods

- [CreateDefaultSubobject](ue_ue.LevelSequenceMasterSequenceSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LevelSequenceMasterSequenceSettings.md#executeubergraph)
- [GetClass](ue_ue.LevelSequenceMasterSequenceSettings.md#getclass)
- [GetName](ue_ue.LevelSequenceMasterSequenceSettings.md#getname)
- [GetOuter](ue_ue.LevelSequenceMasterSequenceSettings.md#getouter)
- [GetWorld](ue_ue.LevelSequenceMasterSequenceSettings.md#getworld)
- [Find](ue_ue.LevelSequenceMasterSequenceSettings.md#find)
- [Load](ue_ue.LevelSequenceMasterSequenceSettings.md#load)
- [StaticClass](ue_ue.LevelSequenceMasterSequenceSettings.md#staticclass)

## Constructors

### constructor

• **new LevelSequenceMasterSequenceSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:45255](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45255)

## Properties

### MasterSequenceBasePath

• **MasterSequenceBasePath**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

#### Defined in

[ue/ue.d.ts:45258](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45258)

___

### MasterSequenceLevelSequenceToDuplicate

• **MasterSequenceLevelSequenceToDuplicate**: [`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`LevelSequence`](ue_ue.LevelSequence.md)\>

#### Defined in

[ue/ue.d.ts:45260](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45260)

___

### MasterSequenceName

• **MasterSequenceName**: `string`

#### Defined in

[ue/ue.d.ts:45256](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45256)

___

### MasterSequenceNumShots

• **MasterSequenceNumShots**: `number`

#### Defined in

[ue/ue.d.ts:45259](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45259)

___

### MasterSequenceSuffix

• **MasterSequenceSuffix**: `string`

#### Defined in

[ue/ue.d.ts:45257](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45257)

___

### SubSequenceNames

• **SubSequenceNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:45261](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45261)

___

### \_\_tid\_LevelSequenceMasterSequenceSettings\_\_

• **\_\_tid\_LevelSequenceMasterSequenceSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:45267](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45267)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bInstanceSubSequences

• **bInstanceSubSequences**: `boolean`

#### Defined in

[ue/ue.d.ts:45262](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45262)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LevelSequenceMasterSequenceSettings`](ue_ue.LevelSequenceMasterSequenceSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LevelSequenceMasterSequenceSettings`](ue_ue.LevelSequenceMasterSequenceSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:45264](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45264)

___

### Load

▸ `Static` **Load**(`InName`): [`LevelSequenceMasterSequenceSettings`](ue_ue.LevelSequenceMasterSequenceSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LevelSequenceMasterSequenceSettings`](ue_ue.LevelSequenceMasterSequenceSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:45265](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45265)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:45263](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45263)
