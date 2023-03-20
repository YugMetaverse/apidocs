[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TestMovieSceneSequence

# Class: TestMovieSceneSequence

[ue/ue](../modules/ue_ue.md).TestMovieSceneSequence

## Hierarchy

- [`MovieSceneSequence`](ue_ue.MovieSceneSequence.md)

  ↳ **`TestMovieSceneSequence`**

## Table of contents

### Constructors

- [constructor](ue_ue.TestMovieSceneSequence.md#constructor)

### Properties

- [DefaultCompletionMode](ue_ue.TestMovieSceneSequence.md#defaultcompletionmode)
- [MovieScene](ue_ue.TestMovieSceneSequence.md#moviescene)
- [PrecompiledEvaluationTemplate](ue_ue.TestMovieSceneSequence.md#precompiledevaluationtemplate)
- [Signature](ue_ue.TestMovieSceneSequence.md#signature)
- [\_\_tid\_MovieSceneSequence\_\_](ue_ue.TestMovieSceneSequence.md#__tid_moviescenesequence__)
- [\_\_tid\_MovieSceneSignedObject\_\_](ue_ue.TestMovieSceneSequence.md#__tid_moviescenesignedobject__)
- [\_\_tid\_Object\_\_](ue_ue.TestMovieSceneSequence.md#__tid_object__)
- [\_\_tid\_TestMovieSceneSequence\_\_](ue_ue.TestMovieSceneSequence.md#__tid_testmoviescenesequence__)
- [bParentContextsAreSignificant](ue_ue.TestMovieSceneSequence.md#bparentcontextsaresignificant)
- [bPlayableDirectly](ue_ue.TestMovieSceneSequence.md#bplayabledirectly)

### Methods

- [CreateDefaultSubobject](ue_ue.TestMovieSceneSequence.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TestMovieSceneSequence.md#executeubergraph)
- [FindBindingByTag](ue_ue.TestMovieSceneSequence.md#findbindingbytag)
- [FindBindingsByTag](ue_ue.TestMovieSceneSequence.md#findbindingsbytag)
- [GetClass](ue_ue.TestMovieSceneSequence.md#getclass)
- [GetName](ue_ue.TestMovieSceneSequence.md#getname)
- [GetOuter](ue_ue.TestMovieSceneSequence.md#getouter)
- [GetWorld](ue_ue.TestMovieSceneSequence.md#getworld)
- [Find](ue_ue.TestMovieSceneSequence.md#find)
- [Load](ue_ue.TestMovieSceneSequence.md#load)
- [StaticClass](ue_ue.TestMovieSceneSequence.md#staticclass)

## Constructors

### constructor

• **new TestMovieSceneSequence**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[constructor](ue_ue.MovieSceneSequence.md#constructor)

## Properties

### DefaultCompletionMode

• **DefaultCompletionMode**: [`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[DefaultCompletionMode](ue_ue.MovieSceneSequence.md#defaultcompletionmode)

___

### MovieScene

• **MovieScene**: [`MovieScene`](ue_ue.MovieScene.md)

___

### PrecompiledEvaluationTemplate

• **PrecompiledEvaluationTemplate**: [`MovieSceneEvaluationTemplate`](ue_ue.MovieSceneEvaluationTemplate.md)

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[PrecompiledEvaluationTemplate](ue_ue.MovieSceneSequence.md#precompiledevaluationtemplate)

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[Signature](ue_ue.MovieSceneSequence.md#signature)

___

### \_\_tid\_MovieSceneSequence\_\_

• **\_\_tid\_MovieSceneSequence\_\_**: `boolean`

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[__tid_MovieSceneSequence__](ue_ue.MovieSceneSequence.md#__tid_moviescenesequence__)

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneSequence.md#__tid_moviescenesignedobject__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[__tid_Object__](ue_ue.MovieSceneSequence.md#__tid_object__)

___

### \_\_tid\_TestMovieSceneSequence\_\_

• **\_\_tid\_TestMovieSceneSequence\_\_**: `boolean`

___

### bParentContextsAreSignificant

• **bParentContextsAreSignificant**: `boolean`

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[bParentContextsAreSignificant](ue_ue.MovieSceneSequence.md#bparentcontextsaresignificant)

___

### bPlayableDirectly

• **bPlayableDirectly**: `boolean`

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[bPlayableDirectly](ue_ue.MovieSceneSequence.md#bplayabledirectly)

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

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[CreateDefaultSubobject](ue_ue.MovieSceneSequence.md#createdefaultsubobject)

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

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[ExecuteUbergraph](ue_ue.MovieSceneSequence.md#executeubergraph)

___

### FindBindingByTag

▸ **FindBindingByTag**(`InBindingName`): [`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBindingName` | `string` |

#### Returns

[`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md)

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[FindBindingByTag](ue_ue.MovieSceneSequence.md#findbindingbytag)

___

### FindBindingsByTag

▸ **FindBindingsByTag**(`InBindingName`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBindingName` | `string` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md)\>

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[FindBindingsByTag](ue_ue.MovieSceneSequence.md#findbindingsbytag)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[GetClass](ue_ue.MovieSceneSequence.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[GetName](ue_ue.MovieSceneSequence.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[GetOuter](ue_ue.MovieSceneSequence.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[GetWorld](ue_ue.MovieSceneSequence.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TestMovieSceneSequence`](ue_ue.TestMovieSceneSequence.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TestMovieSceneSequence`](ue_ue.TestMovieSceneSequence.md)

#### Overrides

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[Find](ue_ue.MovieSceneSequence.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TestMovieSceneSequence`](ue_ue.TestMovieSceneSequence.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TestMovieSceneSequence`](ue_ue.TestMovieSceneSequence.md)

#### Overrides

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[Load](ue_ue.MovieSceneSequence.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[StaticClass](ue_ue.MovieSceneSequence.md#staticclass)
