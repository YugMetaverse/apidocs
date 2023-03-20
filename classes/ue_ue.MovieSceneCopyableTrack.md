[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneCopyableTrack

# Class: MovieSceneCopyableTrack

[ue/ue](../modules/ue_ue.md).MovieSceneCopyableTrack

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MovieSceneCopyableTrack`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneCopyableTrack.md#constructor)

### Properties

- [Track](ue_ue.MovieSceneCopyableTrack.md#track)
- [\_\_tid\_MovieSceneCopyableTrack\_\_](ue_ue.MovieSceneCopyableTrack.md#__tid_moviescenecopyabletrack__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneCopyableTrack.md#__tid_object__)
- [bIsAMasterTrack](ue_ue.MovieSceneCopyableTrack.md#bisamastertrack)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneCopyableTrack.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneCopyableTrack.md#executeubergraph)
- [GetClass](ue_ue.MovieSceneCopyableTrack.md#getclass)
- [GetName](ue_ue.MovieSceneCopyableTrack.md#getname)
- [GetOuter](ue_ue.MovieSceneCopyableTrack.md#getouter)
- [GetWorld](ue_ue.MovieSceneCopyableTrack.md#getworld)
- [Find](ue_ue.MovieSceneCopyableTrack.md#find)
- [Load](ue_ue.MovieSceneCopyableTrack.md#load)
- [StaticClass](ue_ue.MovieSceneCopyableTrack.md#staticclass)

## Constructors

### constructor

• **new MovieSceneCopyableTrack**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### Track

• **Track**: [`MovieSceneTrack`](ue_ue.MovieSceneTrack.md)

___

### \_\_tid\_MovieSceneCopyableTrack\_\_

• **\_\_tid\_MovieSceneCopyableTrack\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bIsAMasterTrack

• **bIsAMasterTrack**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneCopyableTrack`](ue_ue.MovieSceneCopyableTrack.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneCopyableTrack`](ue_ue.MovieSceneCopyableTrack.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneCopyableTrack`](ue_ue.MovieSceneCopyableTrack.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneCopyableTrack`](ue_ue.MovieSceneCopyableTrack.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
