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

#### Defined in

[ue/ue.d.ts:11779](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11779)

## Properties

### BlendType

• **BlendType**: [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Defined in

[ue/ue.d.ts:11796](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11796)

___

### Easing

• **Easing**: [`MovieSceneEasingSettings`](ue_ue.MovieSceneEasingSettings.md)

#### Defined in

[ue/ue.d.ts:11781](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11781)

___

### EndTime

• **EndTime**: `number`

#### Defined in

[ue/ue.d.ts:11791](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11791)

___

### EvalOptions

• **EvalOptions**: [`MovieSceneSectionEvalOptions`](ue_ue.MovieSceneSectionEvalOptions.md)

#### Defined in

[ue/ue.d.ts:11780](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11780)

___

### OverlapPriority

• **OverlapPriority**: `number`

#### Defined in

[ue/ue.d.ts:11787](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11787)

___

### PostRollFrames

• **PostRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Defined in

[ue/ue.d.ts:11785](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11785)

___

### PostRollTime

• **PostRollTime**: `number`

#### Defined in

[ue/ue.d.ts:11793](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11793)

___

### PreRollFrames

• **PreRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Defined in

[ue/ue.d.ts:11784](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11784)

___

### PreRollTime

• **PreRollTime**: `number`

#### Defined in

[ue/ue.d.ts:11792](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11792)

___

### RowIndex

• **RowIndex**: `number`

#### Defined in

[ue/ue.d.ts:11786](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11786)

___

### SectionRange

• **SectionRange**: [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)

#### Defined in

[ue/ue.d.ts:11782](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11782)

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[Signature](ue_ue.MovieSceneSignedObject.md#signature)

#### Defined in

[ue/ue.d.ts:11034](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11034)

___

### StartTime

• **StartTime**: `number`

#### Defined in

[ue/ue.d.ts:11790](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11790)

___

### TimecodeSource

• **TimecodeSource**: [`MovieSceneTimecodeSource`](ue_ue.MovieSceneTimecodeSource.md)

#### Defined in

[ue/ue.d.ts:11783](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11783)

___

### \_\_tid\_MovieSceneSection\_\_

• **\_\_tid\_MovieSceneSection\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:11817](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11817)

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneSignedObject.md#__tid_moviescenesignedobject__)

#### Defined in

[ue/ue.d.ts:11039](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11039)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[__tid_Object__](ue_ue.MovieSceneSignedObject.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bIsActive

• **bIsActive**: `boolean`

#### Defined in

[ue/ue.d.ts:11788](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11788)

___

### bIsInfinite

• **bIsInfinite**: `boolean`

#### Defined in

[ue/ue.d.ts:11794](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11794)

___

### bIsLocked

• **bIsLocked**: `boolean`

#### Defined in

[ue/ue.d.ts:11789](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11789)

___

### bSupportsInfiniteRange

• **bSupportsInfiniteRange**: `boolean`

#### Defined in

[ue/ue.d.ts:11795](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11795)

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

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[ExecuteUbergraph](ue_ue.MovieSceneSignedObject.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetBlendType

▸ **GetBlendType**(): [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Returns

[`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Defined in

[ue/ue.d.ts:11797](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11797)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetClass](ue_ue.MovieSceneSignedObject.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetCompletionMode

▸ **GetCompletionMode**(): [`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Returns

[`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Defined in

[ue/ue.d.ts:11798](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11798)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetName](ue_ue.MovieSceneSignedObject.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetOuter](ue_ue.MovieSceneSignedObject.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetOverlapPriority

▸ **GetOverlapPriority**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:11799](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11799)

___

### GetPostRollFrames

▸ **GetPostRollFrames**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:11800](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11800)

___

### GetPreRollFrames

▸ **GetPreRollFrames**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:11801](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11801)

___

### GetRowIndex

▸ **GetRowIndex**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:11802](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11802)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[GetWorld](ue_ue.MovieSceneSignedObject.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:11803](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11803)

___

### IsLocked

▸ **IsLocked**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:11804](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11804)

___

### SetBlendType

▸ **SetBlendType**(`InBlendType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBlendType` | [`EMovieSceneBlendType`](../enums/ue_ue.EMovieSceneBlendType.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:11805](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11805)

___

### SetCompletionMode

▸ **SetCompletionMode**(`InCompletionMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InCompletionMode` | [`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:11806](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11806)

___

### SetIsActive

▸ **SetIsActive**(`bInIsActive`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInIsActive` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:11807](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11807)

___

### SetIsLocked

▸ **SetIsLocked**(`bInIsLocked`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInIsLocked` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:11808](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11808)

___

### SetOverlapPriority

▸ **SetOverlapPriority**(`NewPriority`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPriority` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:11809](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11809)

___

### SetPostRollFrames

▸ **SetPostRollFrames**(`InPostRollFrames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPostRollFrames` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:11810](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11810)

___

### SetPreRollFrames

▸ **SetPreRollFrames**(`InPreRollFrames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPreRollFrames` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:11811](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11811)

___

### SetRowIndex

▸ **SetRowIndex**(`NewRowIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRowIndex` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:11812](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11812)

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

#### Defined in

[ue/ue.d.ts:11814](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11814)

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

#### Defined in

[ue/ue.d.ts:11815](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11815)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneSignedObject](ue_ue.MovieSceneSignedObject.md).[StaticClass](ue_ue.MovieSceneSignedObject.md#staticclass)

#### Defined in

[ue/ue.d.ts:11813](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11813)
