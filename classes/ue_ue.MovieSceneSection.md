[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneSection

# Class: MovieSceneSection

[ue/ue](../modules/ue_ue.md).MovieSceneSection

## Hierarchy

- [`MovieSceneSignedObject`](ue_ue.MovieSceneSignedObject.md)

  ↳ **`MovieSceneSection`**

  ↳↳ [`MovieScene2DTransformSection`](ue_ue.MovieScene2DTransformSection.md)

  ↳↳ [`MovieScene3DConstraintSection`](ue_ue.MovieScene3DConstraintSection.md)

  ↳↳ [`MovieScene3DTransformSection`](ue_ue.MovieScene3DTransformSection.md)

  ↳↳ [`MovieSceneActorReferenceSection`](ue_ue.MovieSceneActorReferenceSection.md)

  ↳↳ [`MovieSceneAudioSection`](ue_ue.MovieSceneAudioSection.md)

  ↳↳ [`MovieSceneBoolSection`](ue_ue.MovieSceneBoolSection.md)

  ↳↳ [`MovieSceneByteSection`](ue_ue.MovieSceneByteSection.md)

  ↳↳ [`MovieSceneCameraAnimSection`](ue_ue.MovieSceneCameraAnimSection.md)

  ↳↳ [`MovieSceneCameraCutSection`](ue_ue.MovieSceneCameraCutSection.md)

  ↳↳ [`MovieSceneCameraShakeSection`](ue_ue.MovieSceneCameraShakeSection.md)

  ↳↳ [`MovieSceneSubSection`](ue_ue.MovieSceneSubSection.md)

  ↳↳ [`MovieSceneColorSection`](ue_ue.MovieSceneColorSection.md)

  ↳↳ [`MovieSceneEnumSection`](ue_ue.MovieSceneEnumSection.md)

  ↳↳ [`MovieSceneEventSectionBase`](ue_ue.MovieSceneEventSectionBase.md)

  ↳↳ [`MovieSceneEventSection`](ue_ue.MovieSceneEventSection.md)

  ↳↳ [`MovieSceneFloatSection`](ue_ue.MovieSceneFloatSection.md)

  ↳↳ [`MovieSceneGeometryCacheSection`](ue_ue.MovieSceneGeometryCacheSection.md)

  ↳↳ [`MovieSceneIntegerSection`](ue_ue.MovieSceneIntegerSection.md)

  ↳↳ [`MovieSceneLevelVisibilitySection`](ue_ue.MovieSceneLevelVisibilitySection.md)

  ↳↳ [`MovieSceneMarginSection`](ue_ue.MovieSceneMarginSection.md)

  ↳↳ [`MovieSceneMediaSection`](ue_ue.MovieSceneMediaSection.md)

  ↳↳ [`MovieSceneObjectPropertySection`](ue_ue.MovieSceneObjectPropertySection.md)

  ↳↳ [`MovieSceneParameterSection`](ue_ue.MovieSceneParameterSection.md)

  ↳↳ [`MovieSceneParticleSection`](ue_ue.MovieSceneParticleSection.md)

  ↳↳ [`MovieScenePrimitiveMaterialSection`](ue_ue.MovieScenePrimitiveMaterialSection.md)

  ↳↳ [`MovieSceneSkeletalAnimationSection`](ue_ue.MovieSceneSkeletalAnimationSection.md)

  ↳↳ [`MovieSceneStringSection`](ue_ue.MovieSceneStringSection.md)

  ↳↳ [`MovieSceneVectorSection`](ue_ue.MovieSceneVectorSection.md)

  ↳↳ [`TestMovieSceneSection`](ue_ue.TestMovieSceneSection.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneSection.md#constructor)

### Properties

- [BlendType](ue_ue.MovieSceneSection.md#blendtype)
- [Easing](ue_ue.MovieSceneSection.md#easing)
- [EndTime](ue_ue.MovieSceneSection.md#endtime)
- [EvalOptions](ue_ue.MovieSceneSection.md#evaloptions)
- [OverlapPriority](ue_ue.MovieSceneSection.md#overlappriority)
- [PostRollFrames](ue_ue.MovieSceneSection.md#postrollframes)
- [PostRollTime](ue_ue.MovieSceneSection.md#postrolltime)
- [PreRollFrames](ue_ue.MovieSceneSection.md#prerollframes)
- [PreRollTime](ue_ue.MovieSceneSection.md#prerolltime)
- [RowIndex](ue_ue.MovieSceneSection.md#rowindex)
- [SectionRange](ue_ue.MovieSceneSection.md#sectionrange)
- [Signature](ue_ue.MovieSceneSection.md#signature)
- [StartTime](ue_ue.MovieSceneSection.md#starttime)
- [TimecodeSource](ue_ue.MovieSceneSection.md#timecodesource)
- [\_\_tid\_MovieSceneSection\_\_](ue_ue.MovieSceneSection.md#__tid_moviescenesection__)
- [\_\_tid\_MovieSceneSignedObject\_\_](ue_ue.MovieSceneSection.md#__tid_moviescenesignedobject__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneSection.md#__tid_object__)
- [bIsActive](ue_ue.MovieSceneSection.md#bisactive)
- [bIsInfinite](ue_ue.MovieSceneSection.md#bisinfinite)
- [bIsLocked](ue_ue.MovieSceneSection.md#bislocked)
- [bSupportsInfiniteRange](ue_ue.MovieSceneSection.md#bsupportsinfiniterange)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneSection.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneSection.md#executeubergraph)
- [GetBlendType](ue_ue.MovieSceneSection.md#getblendtype)
- [GetClass](ue_ue.MovieSceneSection.md#getclass)
- [GetCompletionMode](ue_ue.MovieSceneSection.md#getcompletionmode)
- [GetName](ue_ue.MovieSceneSection.md#getname)
- [GetOuter](ue_ue.MovieSceneSection.md#getouter)
- [GetOverlapPriority](ue_ue.MovieSceneSection.md#getoverlappriority)
- [GetPostRollFrames](ue_ue.MovieSceneSection.md#getpostrollframes)
- [GetPreRollFrames](ue_ue.MovieSceneSection.md#getprerollframes)
- [GetRowIndex](ue_ue.MovieSceneSection.md#getrowindex)
- [GetWorld](ue_ue.MovieSceneSection.md#getworld)
- [IsActive](ue_ue.MovieSceneSection.md#isactive)
- [IsLocked](ue_ue.MovieSceneSection.md#islocked)
- [SetBlendType](ue_ue.MovieSceneSection.md#setblendtype)
- [SetCompletionMode](ue_ue.MovieSceneSection.md#setcompletionmode)
- [SetIsActive](ue_ue.MovieSceneSection.md#setisactive)
- [SetIsLocked](ue_ue.MovieSceneSection.md#setislocked)
- [SetOverlapPriority](ue_ue.MovieSceneSection.md#setoverlappriority)
- [SetPostRollFrames](ue_ue.MovieSceneSection.md#setpostrollframes)
- [SetPreRollFrames](ue_ue.MovieSceneSection.md#setprerollframes)
- [SetRowIndex](ue_ue.MovieSceneSection.md#setrowindex)
- [Find](ue_ue.MovieSceneSection.md#find)
- [Load](ue_ue.MovieSceneSection.md#load)
- [StaticClass](ue_ue.MovieSceneSection.md#staticclass)

## Constructors

### constructor

• **new MovieSceneSection**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[constructor](ue_ue.MovieSceneSignedObject.md#constructor)

## Properties

### BlendType

• **BlendType**: [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

___

### Easing

• **Easing**: [`MovieSceneEasingSettings`](ue_ue.MovieSceneEasingSettings.md)

___

### EndTime

• **EndTime**: `number`

___

### EvalOptions

• **EvalOptions**: [`MovieSceneSectionEvalOptions`](ue_ue.MovieSceneSectionEvalOptions.md)

___

### OverlapPriority

• **OverlapPriority**: `number`

___

### PostRollFrames

• **PostRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

___

### PostRollTime

• **PostRollTime**: `number`

___

### PreRollFrames

• **PreRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

___

### PreRollTime

• **PreRollTime**: `number`

___

### RowIndex

• **RowIndex**: `number`

___

### SectionRange

• **SectionRange**: [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[Signature](ue_ue.MovieSceneSignedObject.md#signature)

___

### StartTime

• **StartTime**: `number`

___

### TimecodeSource

• **TimecodeSource**: [`MovieSceneTimecodeSource`](ue_ue.MovieSceneTimecodeSource.md)

___

### \_\_tid\_MovieSceneSection\_\_

• **\_\_tid\_MovieSceneSection\_\_**: `boolean`

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneSignedObject.md#__tid_moviescenesignedobject__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[__tid_Object__](ue_ue.MovieSceneSignedObject.md#__tid_object__)

___

### bIsActive

• **bIsActive**: `boolean`

___

### bIsInfinite

• **bIsInfinite**: `boolean`

___

### bIsLocked

• **bIsLocked**: `boolean`

___

### bSupportsInfiniteRange

• **bSupportsInfiniteRange**: `boolean`

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

### GetBlendType

▸ **GetBlendType**(): [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Returns

[`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetClass](ue_ue.MovieSceneSignedObject.md#getclass)

___

### GetCompletionMode

▸ **GetCompletionMode**(): [`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Returns

[`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

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

### GetOverlapPriority

▸ **GetOverlapPriority**(): `number`

#### Returns

`number`

___

### GetPostRollFrames

▸ **GetPostRollFrames**(): `number`

#### Returns

`number`

___

### GetPreRollFrames

▸ **GetPreRollFrames**(): `number`

#### Returns

`number`

___

### GetRowIndex

▸ **GetRowIndex**(): `number`

#### Returns

`number`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetWorld](ue_ue.MovieSceneSignedObject.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

___

### IsLocked

▸ **IsLocked**(): `boolean`

#### Returns

`boolean`

___

### SetBlendType

▸ **SetBlendType**(`InBlendType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBlendType` | [`EMovieSceneBlendType`](../enums/ue_ue.EMovieSceneBlendType.md) |

#### Returns

`void`

___

### SetCompletionMode

▸ **SetCompletionMode**(`InCompletionMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InCompletionMode` | [`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md) |

#### Returns

`void`

___

### SetIsActive

▸ **SetIsActive**(`bInIsActive`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInIsActive` | `boolean` |

#### Returns

`void`

___

### SetIsLocked

▸ **SetIsLocked**(`bInIsLocked`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInIsLocked` | `boolean` |

#### Returns

`void`

___

### SetOverlapPriority

▸ **SetOverlapPriority**(`NewPriority`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPriority` | `number` |

#### Returns

`void`

___

### SetPostRollFrames

▸ **SetPostRollFrames**(`InPostRollFrames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPostRollFrames` | `number` |

#### Returns

`void`

___

### SetPreRollFrames

▸ **SetPreRollFrames**(`InPreRollFrames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPreRollFrames` | `number` |

#### Returns

`void`

___

### SetRowIndex

▸ **SetRowIndex**(`NewRowIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRowIndex` | `number` |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneSection`](ue_ue.MovieSceneSection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneSection`](ue_ue.MovieSceneSection.md)

#### Overrides

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[Find](ue_ue.MovieSceneSignedObject.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneSection`](ue_ue.MovieSceneSection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneSection`](ue_ue.MovieSceneSection.md)

#### Overrides

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[Load](ue_ue.MovieSceneSignedObject.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[StaticClass](ue_ue.MovieSceneSignedObject.md#staticclass)
