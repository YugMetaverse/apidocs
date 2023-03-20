[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneSpawnTrack

# Class: MovieSceneSpawnTrack

[ue/ue](../modules/ue_ue.md).MovieSceneSpawnTrack

## Hierarchy

- [`MovieSceneTrack`](ue_ue.MovieSceneTrack.md)

  ↳ **`MovieSceneSpawnTrack`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneSpawnTrack.md#constructor)

### Properties

- [DisplayOptions](ue_ue.MovieSceneSpawnTrack.md#displayoptions)
- [EvalOptions](ue_ue.MovieSceneSpawnTrack.md#evaloptions)
- [ObjectGuid](ue_ue.MovieSceneSpawnTrack.md#objectguid)
- [Sections](ue_ue.MovieSceneSpawnTrack.md#sections)
- [Signature](ue_ue.MovieSceneSpawnTrack.md#signature)
- [SortingOrder](ue_ue.MovieSceneSpawnTrack.md#sortingorder)
- [TrackTint](ue_ue.MovieSceneSpawnTrack.md#tracktint)
- [\_\_tid\_MovieSceneSignedObject\_\_](ue_ue.MovieSceneSpawnTrack.md#__tid_moviescenesignedobject__)
- [\_\_tid\_MovieSceneSpawnTrack\_\_](ue_ue.MovieSceneSpawnTrack.md#__tid_moviescenespawntrack__)
- [\_\_tid\_MovieSceneTrack\_\_](ue_ue.MovieSceneSpawnTrack.md#__tid_moviescenetrack__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneSpawnTrack.md#__tid_object__)
- [bIsEvalDisabled](ue_ue.MovieSceneSpawnTrack.md#bisevaldisabled)
- [bSupportsDefaultSections](ue_ue.MovieSceneSpawnTrack.md#bsupportsdefaultsections)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneSpawnTrack.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneSpawnTrack.md#executeubergraph)
- [GetClass](ue_ue.MovieSceneSpawnTrack.md#getclass)
- [GetName](ue_ue.MovieSceneSpawnTrack.md#getname)
- [GetOuter](ue_ue.MovieSceneSpawnTrack.md#getouter)
- [GetWorld](ue_ue.MovieSceneSpawnTrack.md#getworld)
- [Find](ue_ue.MovieSceneSpawnTrack.md#find)
- [Load](ue_ue.MovieSceneSpawnTrack.md#load)
- [StaticClass](ue_ue.MovieSceneSpawnTrack.md#staticclass)

## Constructors

### constructor

• **new MovieSceneSpawnTrack**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[constructor](ue_ue.MovieSceneTrack.md#constructor)

## Properties

### DisplayOptions

• **DisplayOptions**: [`MovieSceneTrackDisplayOptions`](ue_ue.MovieSceneTrackDisplayOptions.md)

#### Inherited from

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[DisplayOptions](ue_ue.MovieSceneTrack.md#displayoptions)

___

### EvalOptions

• **EvalOptions**: [`MovieSceneTrackEvalOptions`](ue_ue.MovieSceneTrackEvalOptions.md)

#### Inherited from

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[EvalOptions](ue_ue.MovieSceneTrack.md#evaloptions)

___

### ObjectGuid

• **ObjectGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### Sections

• **Sections**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneSection`](ue_ue.MovieSceneSection.md)\>

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[Signature](ue_ue.MovieSceneTrack.md#signature)

___

### SortingOrder

• **SortingOrder**: `number`

#### Inherited from

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[SortingOrder](ue_ue.MovieSceneTrack.md#sortingorder)

___

### TrackTint

• **TrackTint**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[TrackTint](ue_ue.MovieSceneTrack.md#tracktint)

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneTrack.md#__tid_moviescenesignedobject__)

___

### \_\_tid\_MovieSceneSpawnTrack\_\_

• **\_\_tid\_MovieSceneSpawnTrack\_\_**: `boolean`

___

### \_\_tid\_MovieSceneTrack\_\_

• **\_\_tid\_MovieSceneTrack\_\_**: `boolean`

#### Inherited from

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[__tid_MovieSceneTrack__](ue_ue.MovieSceneTrack.md#__tid_moviescenetrack__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[__tid_Object__](ue_ue.MovieSceneTrack.md#__tid_object__)

___

### bIsEvalDisabled

• **bIsEvalDisabled**: `boolean`

#### Inherited from

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[bIsEvalDisabled](ue_ue.MovieSceneTrack.md#bisevaldisabled)

___

### bSupportsDefaultSections

• **bSupportsDefaultSections**: `boolean`

#### Inherited from

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[bSupportsDefaultSections](ue_ue.MovieSceneTrack.md#bsupportsdefaultsections)

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

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[CreateDefaultSubobject](ue_ue.MovieSceneTrack.md#createdefaultsubobject)

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

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[ExecuteUbergraph](ue_ue.MovieSceneTrack.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[GetClass](ue_ue.MovieSceneTrack.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[GetName](ue_ue.MovieSceneTrack.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[GetOuter](ue_ue.MovieSceneTrack.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[GetWorld](ue_ue.MovieSceneTrack.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneSpawnTrack`](ue_ue.MovieSceneSpawnTrack.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneSpawnTrack`](ue_ue.MovieSceneSpawnTrack.md)

#### Overrides

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[Find](ue_ue.MovieSceneTrack.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneSpawnTrack`](ue_ue.MovieSceneSpawnTrack.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneSpawnTrack`](ue_ue.MovieSceneSpawnTrack.md)

#### Overrides

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[Load](ue_ue.MovieSceneTrack.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[StaticClass](ue_ue.MovieSceneTrack.md#staticclass)
