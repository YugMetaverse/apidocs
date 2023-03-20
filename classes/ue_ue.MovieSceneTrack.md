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

#### Defined in

[ue/ue.d.ts:11107](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11107)

## Properties

### DisplayOptions

• **DisplayOptions**: [`MovieSceneTrackDisplayOptions`](ue_ue.MovieSceneTrackDisplayOptions.md)

#### Defined in

[ue/ue.d.ts:11109](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11109)

___

### EvalOptions

• **EvalOptions**: [`MovieSceneTrackEvalOptions`](ue_ue.MovieSceneTrackEvalOptions.md)

#### Defined in

[ue/ue.d.ts:11108](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11108)

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[Signature](ue_ue.MovieSceneSignedObject.md#signature)

#### Defined in

[ue/ue.d.ts:11034](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11034)

___

### SortingOrder

• **SortingOrder**: `number`

#### Defined in

[ue/ue.d.ts:11112](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11112)

___

### TrackTint

• **TrackTint**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:11111](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11111)

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneSignedObject.md#__tid_moviescenesignedobject__)

#### Defined in

[ue/ue.d.ts:11039](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11039)

___

### \_\_tid\_MovieSceneTrack\_\_

• **\_\_tid\_MovieSceneTrack\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:11118](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11118)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[__tid_Object__](ue_ue.MovieSceneSignedObject.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bIsEvalDisabled

• **bIsEvalDisabled**: `boolean`

#### Defined in

[ue/ue.d.ts:11110](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11110)

___

### bSupportsDefaultSections

• **bSupportsDefaultSections**: `boolean`

#### Defined in

[ue/ue.d.ts:11113](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11113)

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

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[ExecuteUbergraph](ue_ue.MovieSceneSignedObject.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetClass](ue_ue.MovieSceneSignedObject.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetName](ue_ue.MovieSceneSignedObject.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetOuter](ue_ue.MovieSceneSignedObject.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetWorld](ue_ue.MovieSceneSignedObject.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:11115](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11115)

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

#### Defined in

[ue/ue.d.ts:11116](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11116)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[StaticClass](ue_ue.MovieSceneSignedObject.md#staticclass)

#### Defined in

[ue/ue.d.ts:11114](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11114)
