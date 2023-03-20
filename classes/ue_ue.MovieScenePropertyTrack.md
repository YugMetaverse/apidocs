[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieScenePropertyTrack

# Class: MovieScenePropertyTrack

[ue/ue](../modules/ue_ue.md).MovieScenePropertyTrack

## Hierarchy

- [`MovieSceneNameableTrack`](ue_ue.MovieSceneNameableTrack.md)

  ↳ **`MovieScenePropertyTrack`**

  ↳↳ [`MovieScene2DTransformTrack`](ue_ue.MovieScene2DTransformTrack.md)

  ↳↳ [`MovieScene3DTransformTrack`](ue_ue.MovieScene3DTransformTrack.md)

  ↳↳ [`MovieSceneActorReferenceTrack`](ue_ue.MovieSceneActorReferenceTrack.md)

  ↳↳ [`MovieSceneBoolTrack`](ue_ue.MovieSceneBoolTrack.md)

  ↳↳ [`MovieSceneByteTrack`](ue_ue.MovieSceneByteTrack.md)

  ↳↳ [`MovieSceneColorTrack`](ue_ue.MovieSceneColorTrack.md)

  ↳↳ [`MovieSceneEnumTrack`](ue_ue.MovieSceneEnumTrack.md)

  ↳↳ [`MovieSceneEulerTransformTrack`](ue_ue.MovieSceneEulerTransformTrack.md)

  ↳↳ [`MovieSceneFloatTrack`](ue_ue.MovieSceneFloatTrack.md)

  ↳↳ [`MovieSceneIntegerTrack`](ue_ue.MovieSceneIntegerTrack.md)

  ↳↳ [`MovieSceneMarginTrack`](ue_ue.MovieSceneMarginTrack.md)

  ↳↳ [`MovieSceneObjectPropertyTrack`](ue_ue.MovieSceneObjectPropertyTrack.md)

  ↳↳ [`MovieScenePrimitiveMaterialTrack`](ue_ue.MovieScenePrimitiveMaterialTrack.md)

  ↳↳ [`MovieSceneStringTrack`](ue_ue.MovieSceneStringTrack.md)

  ↳↳ [`MovieSceneTransformTrack`](ue_ue.MovieSceneTransformTrack.md)

  ↳↳ [`MovieSceneVectorTrack`](ue_ue.MovieSceneVectorTrack.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MovieScenePropertyTrack.md#constructor)

### Properties

- [DisplayName](ue_ue.MovieScenePropertyTrack.md#displayname)
- [DisplayOptions](ue_ue.MovieScenePropertyTrack.md#displayoptions)
- [EvalOptions](ue_ue.MovieScenePropertyTrack.md#evaloptions)
- [PropertyName](ue_ue.MovieScenePropertyTrack.md#propertyname)
- [PropertyPath](ue_ue.MovieScenePropertyTrack.md#propertypath)
- [SectionToKey](ue_ue.MovieScenePropertyTrack.md#sectiontokey)
- [Sections](ue_ue.MovieScenePropertyTrack.md#sections)
- [Signature](ue_ue.MovieScenePropertyTrack.md#signature)
- [SortingOrder](ue_ue.MovieScenePropertyTrack.md#sortingorder)
- [TrackTint](ue_ue.MovieScenePropertyTrack.md#tracktint)
- [UniqueTrackName](ue_ue.MovieScenePropertyTrack.md#uniquetrackname)
- [\_\_tid\_MovieSceneNameableTrack\_\_](ue_ue.MovieScenePropertyTrack.md#__tid_moviescenenameabletrack__)
- [\_\_tid\_MovieScenePropertyTrack\_\_](ue_ue.MovieScenePropertyTrack.md#__tid_moviescenepropertytrack__)
- [\_\_tid\_MovieSceneSignedObject\_\_](ue_ue.MovieScenePropertyTrack.md#__tid_moviescenesignedobject__)
- [\_\_tid\_MovieSceneTrack\_\_](ue_ue.MovieScenePropertyTrack.md#__tid_moviescenetrack__)
- [\_\_tid\_Object\_\_](ue_ue.MovieScenePropertyTrack.md#__tid_object__)
- [bIsEvalDisabled](ue_ue.MovieScenePropertyTrack.md#bisevaldisabled)
- [bSupportsDefaultSections](ue_ue.MovieScenePropertyTrack.md#bsupportsdefaultsections)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieScenePropertyTrack.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieScenePropertyTrack.md#executeubergraph)
- [GetClass](ue_ue.MovieScenePropertyTrack.md#getclass)
- [GetName](ue_ue.MovieScenePropertyTrack.md#getname)
- [GetOuter](ue_ue.MovieScenePropertyTrack.md#getouter)
- [GetWorld](ue_ue.MovieScenePropertyTrack.md#getworld)
- [Find](ue_ue.MovieScenePropertyTrack.md#find)
- [Load](ue_ue.MovieScenePropertyTrack.md#load)
- [StaticClass](ue_ue.MovieScenePropertyTrack.md#staticclass)

## Constructors

### constructor

• **new MovieScenePropertyTrack**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### PropertyName

• **PropertyName**: `string`

___

### PropertyPath

• **PropertyPath**: `string`

___

### SectionToKey

• **SectionToKey**: [`MovieSceneSection`](ue_ue.MovieSceneSection.md)

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

### UniqueTrackName

• **UniqueTrackName**: `string`

___

### \_\_tid\_MovieSceneNameableTrack\_\_

• **\_\_tid\_MovieSceneNameableTrack\_\_**: `boolean`

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[__tid_MovieSceneNameableTrack__](ue_ue.MovieSceneNameableTrack.md#__tid_moviescenenameabletrack__)

___

### \_\_tid\_MovieScenePropertyTrack\_\_

• **\_\_tid\_MovieScenePropertyTrack\_\_**: `boolean`

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneNameableTrack.md#__tid_moviescenesignedobject__)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieScenePropertyTrack`](ue_ue.MovieScenePropertyTrack.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieScenePropertyTrack`](ue_ue.MovieScenePropertyTrack.md)

#### Overrides

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[Find](ue_ue.MovieSceneNameableTrack.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieScenePropertyTrack`](ue_ue.MovieScenePropertyTrack.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieScenePropertyTrack`](ue_ue.MovieScenePropertyTrack.md)

#### Overrides

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[Load](ue_ue.MovieSceneNameableTrack.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[StaticClass](ue_ue.MovieSceneNameableTrack.md#staticclass)
