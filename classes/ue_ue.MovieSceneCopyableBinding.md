[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneCopyableBinding

# Class: MovieSceneCopyableBinding

[ue/ue](../modules/ue_ue.md).MovieSceneCopyableBinding

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MovieSceneCopyableBinding`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneCopyableBinding.md#constructor)

### Properties

- [Binding](ue_ue.MovieSceneCopyableBinding.md#binding)
- [Possessable](ue_ue.MovieSceneCopyableBinding.md#possessable)
- [Spawnable](ue_ue.MovieSceneCopyableBinding.md#spawnable)
- [SpawnableObjectTemplate](ue_ue.MovieSceneCopyableBinding.md#spawnableobjecttemplate)
- [Tracks](ue_ue.MovieSceneCopyableBinding.md#tracks)
- [\_\_tid\_MovieSceneCopyableBinding\_\_](ue_ue.MovieSceneCopyableBinding.md#__tid_moviescenecopyablebinding__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneCopyableBinding.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneCopyableBinding.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneCopyableBinding.md#executeubergraph)
- [GetClass](ue_ue.MovieSceneCopyableBinding.md#getclass)
- [GetName](ue_ue.MovieSceneCopyableBinding.md#getname)
- [GetOuter](ue_ue.MovieSceneCopyableBinding.md#getouter)
- [GetWorld](ue_ue.MovieSceneCopyableBinding.md#getworld)
- [Find](ue_ue.MovieSceneCopyableBinding.md#find)
- [Load](ue_ue.MovieSceneCopyableBinding.md#load)
- [StaticClass](ue_ue.MovieSceneCopyableBinding.md#staticclass)

## Constructors

### constructor

• **new MovieSceneCopyableBinding**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### Binding

• **Binding**: [`MovieSceneBinding`](ue_ue.MovieSceneBinding.md)

___

### Possessable

• **Possessable**: [`MovieScenePossessable`](ue_ue.MovieScenePossessable.md)

___

### Spawnable

• **Spawnable**: [`MovieSceneSpawnable`](ue_ue.MovieSceneSpawnable.md)

___

### SpawnableObjectTemplate

• **SpawnableObjectTemplate**: [`Object`](ue_ue.Object.md)

___

### Tracks

• **Tracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneTrack`](ue_ue.MovieSceneTrack.md)\>

___

### \_\_tid\_MovieSceneCopyableBinding\_\_

• **\_\_tid\_MovieSceneCopyableBinding\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneCopyableBinding`](ue_ue.MovieSceneCopyableBinding.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneCopyableBinding`](ue_ue.MovieSceneCopyableBinding.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneCopyableBinding`](ue_ue.MovieSceneCopyableBinding.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneCopyableBinding`](ue_ue.MovieSceneCopyableBinding.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
