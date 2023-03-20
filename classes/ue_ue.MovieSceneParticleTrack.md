[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneParticleTrack

# Class: MovieSceneParticleTrack

[ue/ue](../modules/ue_ue.md).MovieSceneParticleTrack

## Hierarchy

- [`MovieSceneNameableTrack`](ue_ue.MovieSceneNameableTrack.md)

  ↳ **`MovieSceneParticleTrack`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneParticleTrack.md#constructor)

### Properties

- [DisplayName](ue_ue.MovieSceneParticleTrack.md#displayname)
- [DisplayOptions](ue_ue.MovieSceneParticleTrack.md#displayoptions)
- [EvalOptions](ue_ue.MovieSceneParticleTrack.md#evaloptions)
- [ParticleSections](ue_ue.MovieSceneParticleTrack.md#particlesections)
- [Signature](ue_ue.MovieSceneParticleTrack.md#signature)
- [SortingOrder](ue_ue.MovieSceneParticleTrack.md#sortingorder)
- [TrackTint](ue_ue.MovieSceneParticleTrack.md#tracktint)
- [\_\_tid\_MovieSceneNameableTrack\_\_](ue_ue.MovieSceneParticleTrack.md#__tid_moviescenenameabletrack__)
- [\_\_tid\_MovieSceneParticleTrack\_\_](ue_ue.MovieSceneParticleTrack.md#__tid_moviesceneparticletrack__)
- [\_\_tid\_MovieSceneSignedObject\_\_](ue_ue.MovieSceneParticleTrack.md#__tid_moviescenesignedobject__)
- [\_\_tid\_MovieSceneTrack\_\_](ue_ue.MovieSceneParticleTrack.md#__tid_moviescenetrack__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneParticleTrack.md#__tid_object__)
- [bIsEvalDisabled](ue_ue.MovieSceneParticleTrack.md#bisevaldisabled)
- [bSupportsDefaultSections](ue_ue.MovieSceneParticleTrack.md#bsupportsdefaultsections)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneParticleTrack.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneParticleTrack.md#executeubergraph)
- [GetClass](ue_ue.MovieSceneParticleTrack.md#getclass)
- [GetName](ue_ue.MovieSceneParticleTrack.md#getname)
- [GetOuter](ue_ue.MovieSceneParticleTrack.md#getouter)
- [GetWorld](ue_ue.MovieSceneParticleTrack.md#getworld)
- [Find](ue_ue.MovieSceneParticleTrack.md#find)
- [Load](ue_ue.MovieSceneParticleTrack.md#load)
- [StaticClass](ue_ue.MovieSceneParticleTrack.md#staticclass)

## Constructors

### constructor

• **new MovieSceneParticleTrack**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[constructor](ue_ue.MovieSceneNameableTrack.md#constructor)

#### Defined in

[ue/ue.d.ts:52213](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L52213)

## Properties

### DisplayName

• **DisplayName**: `string`

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[DisplayName](ue_ue.MovieSceneNameableTrack.md#displayname)

#### Defined in

[ue/ue.d.ts:50998](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50998)

___

### DisplayOptions

• **DisplayOptions**: [`MovieSceneTrackDisplayOptions`](ue_ue.MovieSceneTrackDisplayOptions.md)

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[DisplayOptions](ue_ue.MovieSceneNameableTrack.md#displayoptions)

#### Defined in

[ue/ue.d.ts:11109](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11109)

___

### EvalOptions

• **EvalOptions**: [`MovieSceneTrackEvalOptions`](ue_ue.MovieSceneTrackEvalOptions.md)

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[EvalOptions](ue_ue.MovieSceneNameableTrack.md#evaloptions)

#### Defined in

[ue/ue.d.ts:11108](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11108)

___

### ParticleSections

• **ParticleSections**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneSection`](ue_ue.MovieSceneSection.md)\>

#### Defined in

[ue/ue.d.ts:52214](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L52214)

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[Signature](ue_ue.MovieSceneNameableTrack.md#signature)

#### Defined in

[ue/ue.d.ts:11034](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11034)

___

### SortingOrder

• **SortingOrder**: `number`

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[SortingOrder](ue_ue.MovieSceneNameableTrack.md#sortingorder)

#### Defined in

[ue/ue.d.ts:11112](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11112)

___

### TrackTint

• **TrackTint**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[TrackTint](ue_ue.MovieSceneNameableTrack.md#tracktint)

#### Defined in

[ue/ue.d.ts:11111](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11111)

___

### \_\_tid\_MovieSceneNameableTrack\_\_

• **\_\_tid\_MovieSceneNameableTrack\_\_**: `boolean`

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[__tid_MovieSceneNameableTrack__](ue_ue.MovieSceneNameableTrack.md#__tid_moviescenenameabletrack__)

#### Defined in

[ue/ue.d.ts:51003](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L51003)

___

### \_\_tid\_MovieSceneParticleTrack\_\_

• **\_\_tid\_MovieSceneParticleTrack\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:52219](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L52219)

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneNameableTrack.md#__tid_moviescenesignedobject__)

#### Defined in

[ue/ue.d.ts:11039](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11039)

___

### \_\_tid\_MovieSceneTrack\_\_

• **\_\_tid\_MovieSceneTrack\_\_**: `boolean`

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[__tid_MovieSceneTrack__](ue_ue.MovieSceneNameableTrack.md#__tid_moviescenetrack__)

#### Defined in

[ue/ue.d.ts:11118](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11118)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[__tid_Object__](ue_ue.MovieSceneNameableTrack.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bIsEvalDisabled

• **bIsEvalDisabled**: `boolean`

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[bIsEvalDisabled](ue_ue.MovieSceneNameableTrack.md#bisevaldisabled)

#### Defined in

[ue/ue.d.ts:11110](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11110)

___

### bSupportsDefaultSections

• **bSupportsDefaultSections**: `boolean`

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[bSupportsDefaultSections](ue_ue.MovieSceneNameableTrack.md#bsupportsdefaultsections)

#### Defined in

[ue/ue.d.ts:11113](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11113)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[GetClass](ue_ue.MovieSceneNameableTrack.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[GetName](ue_ue.MovieSceneNameableTrack.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[GetOuter](ue_ue.MovieSceneNameableTrack.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[GetWorld](ue_ue.MovieSceneNameableTrack.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneParticleTrack`](ue_ue.MovieSceneParticleTrack.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneParticleTrack`](ue_ue.MovieSceneParticleTrack.md)

#### Overrides

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[Find](ue_ue.MovieSceneNameableTrack.md#find)

#### Defined in

[ue/ue.d.ts:52216](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L52216)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneParticleTrack`](ue_ue.MovieSceneParticleTrack.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneParticleTrack`](ue_ue.MovieSceneParticleTrack.md)

#### Overrides

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[Load](ue_ue.MovieSceneNameableTrack.md#load)

#### Defined in

[ue/ue.d.ts:52217](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L52217)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneNameableTrack](ue_ue.MovieSceneNameableTrack.md).[StaticClass](ue_ue.MovieSceneNameableTrack.md#staticclass)

#### Defined in

[ue/ue.d.ts:52215](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L52215)
