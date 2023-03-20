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

## Properties

### MasterSequenceBasePath

• **MasterSequenceBasePath**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

___

### MasterSequenceLevelSequenceToDuplicate

• **MasterSequenceLevelSequenceToDuplicate**: [`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`LevelSequence`](ue_ue.LevelSequence.md)\>

___

### MasterSequenceName

• **MasterSequenceName**: `string`

___

### MasterSequenceNumShots

• **MasterSequenceNumShots**: `number`

___

### MasterSequenceSuffix

• **MasterSequenceSuffix**: `string`

___

### SubSequenceNames

• **SubSequenceNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### \_\_tid\_LevelSequenceMasterSequenceSettings\_\_

• **\_\_tid\_LevelSequenceMasterSequenceSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bInstanceSubSequences

• **bInstanceSubSequences**: `boolean`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
