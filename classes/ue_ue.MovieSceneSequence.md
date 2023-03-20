[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneSequence

# Class: MovieSceneSequence

[ue/ue](../modules/ue_ue.md).MovieSceneSequence

## Hierarchy

- [`MovieSceneSignedObject`](ue_ue.MovieSceneSignedObject.md)

  ↳ **`MovieSceneSequence`**

  ↳↳ [`WidgetAnimation`](ue_ue.WidgetAnimation.md)

  ↳↳ [`LevelSequence`](ue_ue.LevelSequence.md)

  ↳↳ [`ActorSequence`](ue_ue.ActorSequence.md)

  ↳↳ [`TestMovieSceneSequence`](ue_ue.TestMovieSceneSequence.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneSequence.md#constructor)

### Properties

- [DefaultCompletionMode](ue_ue.MovieSceneSequence.md#defaultcompletionmode)
- [PrecompiledEvaluationTemplate](ue_ue.MovieSceneSequence.md#precompiledevaluationtemplate)
- [Signature](ue_ue.MovieSceneSequence.md#signature)
- [\_\_tid\_MovieSceneSequence\_\_](ue_ue.MovieSceneSequence.md#__tid_moviescenesequence__)
- [\_\_tid\_MovieSceneSignedObject\_\_](ue_ue.MovieSceneSequence.md#__tid_moviescenesignedobject__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneSequence.md#__tid_object__)
- [bParentContextsAreSignificant](ue_ue.MovieSceneSequence.md#bparentcontextsaresignificant)
- [bPlayableDirectly](ue_ue.MovieSceneSequence.md#bplayabledirectly)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneSequence.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneSequence.md#executeubergraph)
- [FindBindingByTag](ue_ue.MovieSceneSequence.md#findbindingbytag)
- [FindBindingsByTag](ue_ue.MovieSceneSequence.md#findbindingsbytag)
- [GetClass](ue_ue.MovieSceneSequence.md#getclass)
- [GetName](ue_ue.MovieSceneSequence.md#getname)
- [GetOuter](ue_ue.MovieSceneSequence.md#getouter)
- [GetWorld](ue_ue.MovieSceneSequence.md#getworld)
- [Find](ue_ue.MovieSceneSequence.md#find)
- [Load](ue_ue.MovieSceneSequence.md#load)
- [StaticClass](ue_ue.MovieSceneSequence.md#staticclass)

## Constructors

### constructor

• **new MovieSceneSequence**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[constructor](ue_ue.MovieSceneSignedObject.md#constructor)

#### Defined in

[ue/ue.d.ts:11509](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11509)

## Properties

### DefaultCompletionMode

• **DefaultCompletionMode**: [`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Defined in

[ue/ue.d.ts:11511](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11511)

___

### PrecompiledEvaluationTemplate

• **PrecompiledEvaluationTemplate**: [`MovieSceneEvaluationTemplate`](ue_ue.MovieSceneEvaluationTemplate.md)

#### Defined in

[ue/ue.d.ts:11510](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11510)

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[Signature](ue_ue.MovieSceneSignedObject.md#signature)

#### Defined in

[ue/ue.d.ts:11034](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11034)

___

### \_\_tid\_MovieSceneSequence\_\_

• **\_\_tid\_MovieSceneSequence\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:11520](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11520)

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneSignedObject.md#__tid_moviescenesignedobject__)

#### Defined in

[ue/ue.d.ts:11039](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11039)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[__tid_Object__](ue_ue.MovieSceneSignedObject.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bParentContextsAreSignificant

• **bParentContextsAreSignificant**: `boolean`

#### Defined in

[ue/ue.d.ts:11512](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11512)

___

### bPlayableDirectly

• **bPlayableDirectly**: `boolean`

#### Defined in

[ue/ue.d.ts:11513](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11513)

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

### FindBindingByTag

▸ **FindBindingByTag**(`InBindingName`): [`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBindingName` | `string` |

#### Returns

[`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md)

#### Defined in

[ue/ue.d.ts:11514](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11514)

___

### FindBindingsByTag

▸ **FindBindingsByTag**(`InBindingName`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBindingName` | `string` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md)\>

#### Defined in

[ue/ue.d.ts:11515](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11515)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneSequence`](ue_ue.MovieSceneSequence.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneSequence`](ue_ue.MovieSceneSequence.md)

#### Overrides

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[Find](ue_ue.MovieSceneSignedObject.md#find)

#### Defined in

[ue/ue.d.ts:11517](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11517)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneSequence`](ue_ue.MovieSceneSequence.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneSequence`](ue_ue.MovieSceneSequence.md)

#### Overrides

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[Load](ue_ue.MovieSceneSignedObject.md#load)

#### Defined in

[ue/ue.d.ts:11518](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11518)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[StaticClass](ue_ue.MovieSceneSignedObject.md#staticclass)

#### Defined in

[ue/ue.d.ts:11516](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11516)
