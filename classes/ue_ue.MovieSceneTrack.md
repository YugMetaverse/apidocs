[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneTrack

# Class: MovieSceneTrack

[ue/ue](../modules/ue_ue.md).MovieSceneTrack

## Hierarchy

- [`MovieSceneSignedObject`](ue_ue.MovieSceneSignedObject.md)

  ↳ **`MovieSceneTrack`**

  ↳↳ [`MovieSceneNameableTrack`](ue_ue.MovieSceneNameableTrack.md)

  ↳↳ [`MovieScene3DConstraintTrack`](ue_ue.MovieScene3DConstraintTrack.md)

  ↳↳ [`MovieSceneSpawnTrack`](ue_ue.MovieSceneSpawnTrack.md)

  ↳↳ [`TestMovieSceneTrack`](ue_ue.TestMovieSceneTrack.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneTrack.md#constructor)

### Properties

- [DisplayOptions](ue_ue.MovieSceneTrack.md#displayoptions)
- [EvalOptions](ue_ue.MovieSceneTrack.md#evaloptions)
- [Signature](ue_ue.MovieSceneTrack.md#signature)
- [SortingOrder](ue_ue.MovieSceneTrack.md#sortingorder)
- [TrackTint](ue_ue.MovieSceneTrack.md#tracktint)
- [\_\_tid\_MovieSceneSignedObject\_\_](ue_ue.MovieSceneTrack.md#__tid_moviescenesignedobject__)
- [\_\_tid\_MovieSceneTrack\_\_](ue_ue.MovieSceneTrack.md#__tid_moviescenetrack__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneTrack.md#__tid_object__)
- [bIsEvalDisabled](ue_ue.MovieSceneTrack.md#bisevaldisabled)
- [bSupportsDefaultSections](ue_ue.MovieSceneTrack.md#bsupportsdefaultsections)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneTrack.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneTrack.md#executeubergraph)
- [GetClass](ue_ue.MovieSceneTrack.md#getclass)
- [GetName](ue_ue.MovieSceneTrack.md#getname)
- [GetOuter](ue_ue.MovieSceneTrack.md#getouter)
- [GetWorld](ue_ue.MovieSceneTrack.md#getworld)
- [Find](ue_ue.MovieSceneTrack.md#find)
- [Load](ue_ue.MovieSceneTrack.md#load)
- [StaticClass](ue_ue.MovieSceneTrack.md#staticclass)

## Constructors

### constructor

• **new MovieSceneTrack**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[constructor](ue_ue.MovieSceneSignedObject.md#constructor)

## Properties

### DisplayOptions

• **DisplayOptions**: [`MovieSceneTrackDisplayOptions`](ue_ue.MovieSceneTrackDisplayOptions.md)

___

### EvalOptions

• **EvalOptions**: [`MovieSceneTrackEvalOptions`](ue_ue.MovieSceneTrackEvalOptions.md)

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[Signature](ue_ue.MovieSceneSignedObject.md#signature)

___

### SortingOrder

• **SortingOrder**: `number`

___

### TrackTint

• **TrackTint**: [`Color`](ue_ue_s.Color.md)

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneSignedObject.md#__tid_moviescenesignedobject__)

___

### \_\_tid\_MovieSceneTrack\_\_

• **\_\_tid\_MovieSceneTrack\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[__tid_Object__](ue_ue.MovieSceneSignedObject.md#__tid_object__)

___

### bIsEvalDisabled

• **bIsEvalDisabled**: `boolean`

___

### bSupportsDefaultSections

• **bSupportsDefaultSections**: `boolean`

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

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[CreateDefaultSubobject](ue_ue.MovieSceneSignedObject.md#createdefaultsubobject)

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

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[ExecuteUbergraph](ue_ue.MovieSceneSignedObject.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetClass](ue_ue.MovieSceneSignedObject.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetName](ue_ue.MovieSceneSignedObject.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetOuter](ue_ue.MovieSceneSignedObject.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetWorld](ue_ue.MovieSceneSignedObject.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneTrack`](ue_ue.MovieSceneTrack.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneTrack`](ue_ue.MovieSceneTrack.md)

#### Overrides

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[Find](ue_ue.MovieSceneSignedObject.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneTrack`](ue_ue.MovieSceneTrack.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneTrack`](ue_ue.MovieSceneTrack.md)

#### Overrides

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[Load](ue_ue.MovieSceneSignedObject.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[StaticClass](ue_ue.MovieSceneSignedObject.md#staticclass)
