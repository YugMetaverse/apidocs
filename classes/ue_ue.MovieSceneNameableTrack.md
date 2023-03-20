[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneNameableTrack

# Class: MovieSceneNameableTrack

[ue/ue](../modules/ue_ue.md).MovieSceneNameableTrack

## Hierarchy

- [`MovieSceneTrack`](ue_ue.MovieSceneTrack.md)

  ↳ **`MovieSceneNameableTrack`**

  ↳↳ [`MovieScenePropertyTrack`](ue_ue.MovieScenePropertyTrack.md)

  ↳↳ [`MovieSceneAudioTrack`](ue_ue.MovieSceneAudioTrack.md)

  ↳↳ [`MovieSceneCameraAnimTrack`](ue_ue.MovieSceneCameraAnimTrack.md)

  ↳↳ [`MovieSceneCameraCutTrack`](ue_ue.MovieSceneCameraCutTrack.md)

  ↳↳ [`MovieSceneCameraShakeTrack`](ue_ue.MovieSceneCameraShakeTrack.md)

  ↳↳ [`MovieSceneSubTrack`](ue_ue.MovieSceneSubTrack.md)

  ↳↳ [`MovieSceneMaterialTrack`](ue_ue.MovieSceneMaterialTrack.md)

  ↳↳ [`MovieSceneEventTrack`](ue_ue.MovieSceneEventTrack.md)

  ↳↳ [`MovieSceneGeometryCacheTrack`](ue_ue.MovieSceneGeometryCacheTrack.md)

  ↳↳ [`MovieSceneLevelVisibilityTrack`](ue_ue.MovieSceneLevelVisibilityTrack.md)

  ↳↳ [`MovieSceneMediaTrack`](ue_ue.MovieSceneMediaTrack.md)

  ↳↳ [`MovieSceneParticleParameterTrack`](ue_ue.MovieSceneParticleParameterTrack.md)

  ↳↳ [`MovieSceneParticleTrack`](ue_ue.MovieSceneParticleTrack.md)

  ↳↳ [`MovieSceneSkeletalAnimationTrack`](ue_ue.MovieSceneSkeletalAnimationTrack.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneNameableTrack.md#constructor)

### Properties

- [DisplayName](ue_ue.MovieSceneNameableTrack.md#displayname)
- [DisplayOptions](ue_ue.MovieSceneNameableTrack.md#displayoptions)
- [EvalOptions](ue_ue.MovieSceneNameableTrack.md#evaloptions)
- [Signature](ue_ue.MovieSceneNameableTrack.md#signature)
- [SortingOrder](ue_ue.MovieSceneNameableTrack.md#sortingorder)
- [TrackTint](ue_ue.MovieSceneNameableTrack.md#tracktint)
- [\_\_tid\_MovieSceneNameableTrack\_\_](ue_ue.MovieSceneNameableTrack.md#__tid_moviescenenameabletrack__)
- [\_\_tid\_MovieSceneSignedObject\_\_](ue_ue.MovieSceneNameableTrack.md#__tid_moviescenesignedobject__)
- [\_\_tid\_MovieSceneTrack\_\_](ue_ue.MovieSceneNameableTrack.md#__tid_moviescenetrack__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneNameableTrack.md#__tid_object__)
- [bIsEvalDisabled](ue_ue.MovieSceneNameableTrack.md#bisevaldisabled)
- [bSupportsDefaultSections](ue_ue.MovieSceneNameableTrack.md#bsupportsdefaultsections)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneNameableTrack.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneNameableTrack.md#executeubergraph)
- [GetClass](ue_ue.MovieSceneNameableTrack.md#getclass)
- [GetName](ue_ue.MovieSceneNameableTrack.md#getname)
- [GetOuter](ue_ue.MovieSceneNameableTrack.md#getouter)
- [GetWorld](ue_ue.MovieSceneNameableTrack.md#getworld)
- [Find](ue_ue.MovieSceneNameableTrack.md#find)
- [Load](ue_ue.MovieSceneNameableTrack.md#load)
- [StaticClass](ue_ue.MovieSceneNameableTrack.md#staticclass)

## Constructors

### constructor

• **new MovieSceneNameableTrack**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[constructor](ue_ue.MovieSceneTrack.md#constructor)

## Properties

### DisplayName

• **DisplayName**: `string`

___

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

### \_\_tid\_MovieSceneNameableTrack\_\_

• **\_\_tid\_MovieSceneNameableTrack\_\_**: `boolean`

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneTrack.md#__tid_moviescenesignedobject__)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneNameableTrack`](ue_ue.MovieSceneNameableTrack.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneNameableTrack`](ue_ue.MovieSceneNameableTrack.md)

#### Overrides

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[Find](ue_ue.MovieSceneTrack.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneNameableTrack`](ue_ue.MovieSceneNameableTrack.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneNameableTrack`](ue_ue.MovieSceneNameableTrack.md)

#### Overrides

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[Load](ue_ue.MovieSceneTrack.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneTrack](ue_ue.MovieSceneTrack.md).[StaticClass](ue_ue.MovieSceneTrack.md#staticclass)
