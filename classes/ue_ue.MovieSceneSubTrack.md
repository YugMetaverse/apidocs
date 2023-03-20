[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneSubTrack

# Class: MovieSceneSubTrack

[ue/ue](../modules/ue_ue.md).MovieSceneSubTrack

## Hierarchy

- [`MovieSceneNameableTrack`](ue_ue.MovieSceneNameableTrack.md)

  ↳ **`MovieSceneSubTrack`**

  ↳↳ [`MovieSceneCinematicShotTrack`](ue_ue.MovieSceneCinematicShotTrack.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneSubTrack.md#constructor)

### Properties

- [DisplayName](ue_ue.MovieSceneSubTrack.md#displayname)
- [DisplayOptions](ue_ue.MovieSceneSubTrack.md#displayoptions)
- [EvalOptions](ue_ue.MovieSceneSubTrack.md#evaloptions)
- [Sections](ue_ue.MovieSceneSubTrack.md#sections)
- [Signature](ue_ue.MovieSceneSubTrack.md#signature)
- [SortingOrder](ue_ue.MovieSceneSubTrack.md#sortingorder)
- [TrackTint](ue_ue.MovieSceneSubTrack.md#tracktint)
- [\_\_tid\_MovieSceneNameableTrack\_\_](ue_ue.MovieSceneSubTrack.md#__tid_moviescenenameabletrack__)
- [\_\_tid\_MovieSceneSignedObject\_\_](ue_ue.MovieSceneSubTrack.md#__tid_moviescenesignedobject__)
- [\_\_tid\_MovieSceneSubTrack\_\_](ue_ue.MovieSceneSubTrack.md#__tid_moviescenesubtrack__)
- [\_\_tid\_MovieSceneTrack\_\_](ue_ue.MovieSceneSubTrack.md#__tid_moviescenetrack__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneSubTrack.md#__tid_object__)
- [bIsEvalDisabled](ue_ue.MovieSceneSubTrack.md#bisevaldisabled)
- [bSupportsDefaultSections](ue_ue.MovieSceneSubTrack.md#bsupportsdefaultsections)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneSubTrack.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneSubTrack.md#executeubergraph)
- [GetClass](ue_ue.MovieSceneSubTrack.md#getclass)
- [GetName](ue_ue.MovieSceneSubTrack.md#getname)
- [GetOuter](ue_ue.MovieSceneSubTrack.md#getouter)
- [GetWorld](ue_ue.MovieSceneSubTrack.md#getworld)
- [Find](ue_ue.MovieSceneSubTrack.md#find)
- [Load](ue_ue.MovieSceneSubTrack.md#load)
- [StaticClass](ue_ue.MovieSceneSubTrack.md#staticclass)

## Constructors

### constructor

• **new MovieSceneSubTrack**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[constructor](ue_ue.MovieSceneNameableTrack.md#constructor)

## Properties

### DisplayName

• **DisplayName**: `string`

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[DisplayName](ue_ue.MovieSceneNameableTrack.md#displayname)

___

### DisplayOptions

• **DisplayOptions**: [`MovieSceneTrackDisplayOptions`](ue_ue.MovieSceneTrackDisplayOptions.md)

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[DisplayOptions](ue_ue.MovieSceneNameableTrack.md#displayoptions)

___

### EvalOptions

• **EvalOptions**: [`MovieSceneTrackEvalOptions`](ue_ue.MovieSceneTrackEvalOptions.md)

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[EvalOptions](ue_ue.MovieSceneNameableTrack.md#evaloptions)

___

### Sections

• **Sections**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneSection`](ue_ue.MovieSceneSection.md)\>

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[Signature](ue_ue.MovieSceneNameableTrack.md#signature)

___

### SortingOrder

• **SortingOrder**: `number`

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[SortingOrder](ue_ue.MovieSceneNameableTrack.md#sortingorder)

___

### TrackTint

• **TrackTint**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[TrackTint](ue_ue.MovieSceneNameableTrack.md#tracktint)

___

### \_\_tid\_MovieSceneNameableTrack\_\_

• **\_\_tid\_MovieSceneNameableTrack\_\_**: `boolean`

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[__tid_MovieSceneNameableTrack__](ue_ue.MovieSceneNameableTrack.md#__tid_moviescenenameabletrack__)

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneNameableTrack.md#__tid_moviescenesignedobject__)

___

### \_\_tid\_MovieSceneSubTrack\_\_

• **\_\_tid\_MovieSceneSubTrack\_\_**: `boolean`

___

### \_\_tid\_MovieSceneTrack\_\_

• **\_\_tid\_MovieSceneTrack\_\_**: `boolean`

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[__tid_MovieSceneTrack__](ue_ue.MovieSceneNameableTrack.md#__tid_moviescenetrack__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[__tid_Object__](ue_ue.MovieSceneNameableTrack.md#__tid_object__)

___

### bIsEvalDisabled

• **bIsEvalDisabled**: `boolean`

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[bIsEvalDisabled](ue_ue.MovieSceneNameableTrack.md#bisevaldisabled)

___

### bSupportsDefaultSections

• **bSupportsDefaultSections**: `boolean`

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[bSupportsDefaultSections](ue_ue.MovieSceneNameableTrack.md#bsupportsdefaultsections)

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

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[CreateDefaultSubobject](ue_ue.MovieSceneNameableTrack.md#createdefaultsubobject)

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

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[ExecuteUbergraph](ue_ue.MovieSceneNameableTrack.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[GetClass](ue_ue.MovieSceneNameableTrack.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[GetName](ue_ue.MovieSceneNameableTrack.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[GetOuter](ue_ue.MovieSceneNameableTrack.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[GetWorld](ue_ue.MovieSceneNameableTrack.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneSubTrack`](ue_ue.MovieSceneSubTrack.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneSubTrack`](ue_ue.MovieSceneSubTrack.md)

#### Overrides

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[Find](ue_ue.MovieSceneNameableTrack.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneSubTrack`](ue_ue.MovieSceneSubTrack.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneSubTrack`](ue_ue.MovieSceneSubTrack.md)

#### Overrides

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[Load](ue_ue.MovieSceneNameableTrack.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[StaticClass](ue_ue.MovieSceneNameableTrack.md#staticclass)
