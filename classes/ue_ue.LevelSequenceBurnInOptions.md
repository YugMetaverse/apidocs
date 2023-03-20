[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LevelSequenceBurnInOptions

# Class: LevelSequenceBurnInOptions

[ue/ue](../modules/ue_ue.md).LevelSequenceBurnInOptions

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`LevelSequenceBurnInOptions`**

## Table of contents

### Constructors

- [constructor](ue_ue.LevelSequenceBurnInOptions.md#constructor)

### Properties

- [BurnInClass](ue_ue.LevelSequenceBurnInOptions.md#burninclass)
- [Settings](ue_ue.LevelSequenceBurnInOptions.md#settings)
- [\_\_tid\_LevelSequenceBurnInOptions\_\_](ue_ue.LevelSequenceBurnInOptions.md#__tid_levelsequenceburninoptions__)
- [\_\_tid\_Object\_\_](ue_ue.LevelSequenceBurnInOptions.md#__tid_object__)
- [bUseBurnIn](ue_ue.LevelSequenceBurnInOptions.md#buseburnin)

### Methods

- [CreateDefaultSubobject](ue_ue.LevelSequenceBurnInOptions.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LevelSequenceBurnInOptions.md#executeubergraph)
- [GetClass](ue_ue.LevelSequenceBurnInOptions.md#getclass)
- [GetName](ue_ue.LevelSequenceBurnInOptions.md#getname)
- [GetOuter](ue_ue.LevelSequenceBurnInOptions.md#getouter)
- [GetWorld](ue_ue.LevelSequenceBurnInOptions.md#getworld)
- [SetBurnIn](ue_ue.LevelSequenceBurnInOptions.md#setburnin)
- [Find](ue_ue.LevelSequenceBurnInOptions.md#find)
- [Load](ue_ue.LevelSequenceBurnInOptions.md#load)
- [StaticClass](ue_ue.LevelSequenceBurnInOptions.md#staticclass)

## Constructors

### constructor

• **new LevelSequenceBurnInOptions**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### BurnInClass

• **BurnInClass**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### Settings

• **Settings**: [`LevelSequenceBurnInInitSettings`](ue_ue.LevelSequenceBurnInInitSettings.md)

___

### \_\_tid\_LevelSequenceBurnInOptions\_\_

• **\_\_tid\_LevelSequenceBurnInOptions\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bUseBurnIn

• **bUseBurnIn**: `boolean`

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

### SetBurnIn

▸ **SetBurnIn**(`InBurnInClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBurnInClass` | [`SoftClassPath`](ue_ue.SoftClassPath.md) |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LevelSequenceBurnInOptions`](ue_ue.LevelSequenceBurnInOptions.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LevelSequenceBurnInOptions`](ue_ue.LevelSequenceBurnInOptions.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LevelSequenceBurnInOptions`](ue_ue.LevelSequenceBurnInOptions.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LevelSequenceBurnInOptions`](ue_ue.LevelSequenceBurnInOptions.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
