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

#### Defined in

[ue/ue.d.ts:14025](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14025)

## Properties

### BindingReferences

• **BindingReferences**: [`LevelSequenceBindingReferences`](ue_ue.LevelSequenceBindingReferences.md)

#### Defined in

[ue/ue.d.ts:14028](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14028)

___

### DefaultCompletionMode

• **DefaultCompletionMode**: [`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[DefaultCompletionMode](ue_ue.MovieSceneSequence.md#defaultcompletionmode)

#### Defined in

[ue/ue.d.ts:11511](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11511)

___

### DirectorBlueprint

• **DirectorBlueprint**: [`Blueprint`](ue_ue.Blueprint.md)

#### Defined in

[ue/ue.d.ts:14030](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14030)

___

### DirectorClass

• **DirectorClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:14031](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14031)

___

### MetaDataObjects

• **MetaDataObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:14032](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14032)

___

### MovieScene

• **MovieScene**: [`MovieScene`](ue_ue.MovieScene.md)

#### Defined in

[ue/ue.d.ts:14026](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14026)

___

### ObjectReferences

• **ObjectReferences**: [`LevelSequenceObjectReferenceMap`](ue_ue.LevelSequenceObjectReferenceMap.md)

#### Defined in

[ue/ue.d.ts:14027](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14027)

___

### PossessedObjects

• **PossessedObjects**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`LevelSequenceObject`](ue_ue.LevelSequenceObject.md)\>

#### Defined in

[ue/ue.d.ts:14029](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14029)

___

### PrecompiledEvaluationTemplate

• **PrecompiledEvaluationTemplate**: [`MovieSceneEvaluationTemplate`](ue_ue.MovieSceneEvaluationTemplate.md)

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[PrecompiledEvaluationTemplate](ue_ue.MovieSceneSequence.md#precompiledevaluationtemplate)

#### Defined in

[ue/ue.d.ts:11510](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11510)

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[Signature](ue_ue.MovieSceneSequence.md#signature)

#### Defined in

[ue/ue.d.ts:11034](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11034)

___

### \_\_tid\_LevelSequence\_\_

• **\_\_tid\_LevelSequence\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:14041](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14041)

___

### \_\_tid\_MovieSceneSequence\_\_

• **\_\_tid\_MovieSceneSequence\_\_**: `boolean`

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[__tid_MovieSceneSequence__](ue_ue.MovieSceneSequence.md#__tid_moviescenesequence__)

#### Defined in

[ue/ue.d.ts:11520](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11520)

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneSequence.md#__tid_moviescenesignedobject__)

#### Defined in

[ue/ue.d.ts:11039](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11039)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[__tid_Object__](ue_ue.MovieSceneSequence.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bParentContextsAreSignificant

• **bParentContextsAreSignificant**: `boolean`

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[bParentContextsAreSignificant](ue_ue.MovieSceneSequence.md#bparentcontextsaresignificant)

#### Defined in

[ue/ue.d.ts:11512](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11512)

___

### bPlayableDirectly

• **bPlayableDirectly**: `boolean`

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[bPlayableDirectly](ue_ue.MovieSceneSequence.md#bplayabledirectly)

#### Defined in

[ue/ue.d.ts:11513](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11513)

## Methods

### CopyMetaData

▸ **CopyMetaData**(`InMetaData`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InMetaData` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`Object`](ue_ue.Object.md)

#### Defined in

[ue/ue.d.ts:14033](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14033)

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

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[ExecuteUbergraph](ue_ue.MovieSceneSequence.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

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

#### Defined in

[ue/ue.d.ts:11514](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11514)

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

#### Defined in

[ue/ue.d.ts:11515](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11515)

___

### FindMetaDataByClass

▸ **FindMetaDataByClass**(`InClass`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`Object`](ue_ue.Object.md)

#### Defined in

[ue/ue.d.ts:14034](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14034)

___

### FindOrAddMetaDataByClass

▸ **FindOrAddMetaDataByClass**(`InClass`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`Object`](ue_ue.Object.md)

#### Defined in

[ue/ue.d.ts:14035](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14035)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[GetClass](ue_ue.MovieSceneSequence.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[GetName](ue_ue.MovieSceneSequence.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[GetOuter](ue_ue.MovieSceneSequence.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[GetWorld](ue_ue.MovieSceneSequence.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### RemoveMetaDataByClass

▸ **RemoveMetaDataByClass**(`InClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14036](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14036)

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

#### Defined in

[ue/ue.d.ts:14038](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14038)

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

#### Defined in

[ue/ue.d.ts:14039](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14039)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[StaticClass](ue_ue.MovieSceneSequence.md#staticclass)

#### Defined in

[ue/ue.d.ts:14037](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14037)
