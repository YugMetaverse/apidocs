[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LevelSequence

# Class: LevelSequence

[ue/ue](../modules/ue_ue.md).LevelSequence

## Hierarchy

- [`MovieSceneSequence`](ue_ue.MovieSceneSequence.md)

  ↳ **`LevelSequence`**

## Table of contents

### Constructors

- [constructor](ue_ue.LevelSequence.md#constructor)

### Properties

- [BindingReferences](ue_ue.LevelSequence.md#bindingreferences)
- [DefaultCompletionMode](ue_ue.LevelSequence.md#defaultcompletionmode)
- [DirectorBlueprint](ue_ue.LevelSequence.md#directorblueprint)
- [DirectorClass](ue_ue.LevelSequence.md#directorclass)
- [MetaDataObjects](ue_ue.LevelSequence.md#metadataobjects)
- [MovieScene](ue_ue.LevelSequence.md#moviescene)
- [ObjectReferences](ue_ue.LevelSequence.md#objectreferences)
- [PossessedObjects](ue_ue.LevelSequence.md#possessedobjects)
- [PrecompiledEvaluationTemplate](ue_ue.LevelSequence.md#precompiledevaluationtemplate)
- [Signature](ue_ue.LevelSequence.md#signature)
- [\_\_tid\_LevelSequence\_\_](ue_ue.LevelSequence.md#__tid_levelsequence__)
- [\_\_tid\_MovieSceneSequence\_\_](ue_ue.LevelSequence.md#__tid_moviescenesequence__)
- [\_\_tid\_MovieSceneSignedObject\_\_](ue_ue.LevelSequence.md#__tid_moviescenesignedobject__)
- [\_\_tid\_Object\_\_](ue_ue.LevelSequence.md#__tid_object__)
- [bParentContextsAreSignificant](ue_ue.LevelSequence.md#bparentcontextsaresignificant)
- [bPlayableDirectly](ue_ue.LevelSequence.md#bplayabledirectly)

### Methods

- [CopyMetaData](ue_ue.LevelSequence.md#copymetadata)
- [CreateDefaultSubobject](ue_ue.LevelSequence.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LevelSequence.md#executeubergraph)
- [FindBindingByTag](ue_ue.LevelSequence.md#findbindingbytag)
- [FindBindingsByTag](ue_ue.LevelSequence.md#findbindingsbytag)
- [FindMetaDataByClass](ue_ue.LevelSequence.md#findmetadatabyclass)
- [FindOrAddMetaDataByClass](ue_ue.LevelSequence.md#findoraddmetadatabyclass)
- [GetClass](ue_ue.LevelSequence.md#getclass)
- [GetName](ue_ue.LevelSequence.md#getname)
- [GetOuter](ue_ue.LevelSequence.md#getouter)
- [GetWorld](ue_ue.LevelSequence.md#getworld)
- [RemoveMetaDataByClass](ue_ue.LevelSequence.md#removemetadatabyclass)
- [Find](ue_ue.LevelSequence.md#find)
- [Load](ue_ue.LevelSequence.md#load)
- [StaticClass](ue_ue.LevelSequence.md#staticclass)

## Constructors

### constructor

• **new LevelSequence**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[constructor](ue_ue.MovieSceneSequence.md#constructor)

## Properties

### BindingReferences

• **BindingReferences**: [`LevelSequenceBindingReferences`](ue_ue.LevelSequenceBindingReferences.md)

___

### DefaultCompletionMode

• **DefaultCompletionMode**: [`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[DefaultCompletionMode](ue_ue.MovieSceneSequence.md#defaultcompletionmode)

___

### DirectorBlueprint

• **DirectorBlueprint**: [`Blueprint`](ue_ue.Blueprint.md)

___

### DirectorClass

• **DirectorClass**: [`Class`](ue_ue.Class.md)

___

### MetaDataObjects

• **MetaDataObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

___

### MovieScene

• **MovieScene**: [`MovieScene`](ue_ue.MovieScene.md)

___

### ObjectReferences

• **ObjectReferences**: [`LevelSequenceObjectReferenceMap`](ue_ue.LevelSequenceObjectReferenceMap.md)

___

### PossessedObjects

• **PossessedObjects**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`LevelSequenceObject`](ue_ue.LevelSequenceObject.md)\>

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

### \_\_tid\_LevelSequence\_\_

• **\_\_tid\_LevelSequence\_\_**: `boolean`

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

### CopyMetaData

▸ **CopyMetaData**(`InMetaData`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InMetaData` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`Object`](ue_ue.Object.md)

___

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

### FindMetaDataByClass

▸ **FindMetaDataByClass**(`InClass`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`Object`](ue_ue.Object.md)

___

### FindOrAddMetaDataByClass

▸ **FindOrAddMetaDataByClass**(`InClass`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`Object`](ue_ue.Object.md)

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

### RemoveMetaDataByClass

▸ **RemoveMetaDataByClass**(`InClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LevelSequence`](ue_ue.LevelSequence.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LevelSequence`](ue_ue.LevelSequence.md)

#### Overrides

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[Find](ue_ue.MovieSceneSequence.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LevelSequence`](ue_ue.LevelSequence.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LevelSequence`](ue_ue.LevelSequence.md)

#### Overrides

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[Load](ue_ue.MovieSceneSequence.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[StaticClass](ue_ue.MovieSceneSequence.md#staticclass)
