[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneSubSection

# Class: MovieSceneSubSection

[ue/ue](../modules/ue_ue.md).MovieSceneSubSection

## Hierarchy

- [`MovieSceneSection`](ue_ue.MovieSceneSection.md)

  ↳ **`MovieSceneSubSection`**

  ↳↳ [`MovieSceneCinematicShotSection`](ue_ue.MovieSceneCinematicShotSection.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneSubSection.md#constructor)

### Properties

- [ActorToRecord](ue_ue.MovieSceneSubSection.md#actortorecord)
- [BlendType](ue_ue.MovieSceneSubSection.md#blendtype)
- [Easing](ue_ue.MovieSceneSubSection.md#easing)
- [EndTime](ue_ue.MovieSceneSubSection.md#endtime)
- [EvalOptions](ue_ue.MovieSceneSubSection.md#evaloptions)
- [OverlapPriority](ue_ue.MovieSceneSubSection.md#overlappriority)
- [Parameters](ue_ue.MovieSceneSubSection.md#parameters)
- [PostRollFrames](ue_ue.MovieSceneSubSection.md#postrollframes)
- [PostRollTime](ue_ue.MovieSceneSubSection.md#postrolltime)
- [PreRollFrames](ue_ue.MovieSceneSubSection.md#prerollframes)
- [PreRollTime](ue_ue.MovieSceneSubSection.md#prerolltime)
- [PrerollTime](ue_ue.MovieSceneSubSection.md#prerolltime-1)
- [RowIndex](ue_ue.MovieSceneSubSection.md#rowindex)
- [SectionRange](ue_ue.MovieSceneSubSection.md#sectionrange)
- [Signature](ue_ue.MovieSceneSubSection.md#signature)
- [StartOffset](ue_ue.MovieSceneSubSection.md#startoffset)
- [StartTime](ue_ue.MovieSceneSubSection.md#starttime)
- [SubSequence](ue_ue.MovieSceneSubSection.md#subsequence)
- [TargetPathToRecordTo](ue_ue.MovieSceneSubSection.md#targetpathtorecordto)
- [TargetSequenceName](ue_ue.MovieSceneSubSection.md#targetsequencename)
- [TimeScale](ue_ue.MovieSceneSubSection.md#timescale)
- [TimecodeSource](ue_ue.MovieSceneSubSection.md#timecodesource)
- [\_\_tid\_MovieSceneSection\_\_](ue_ue.MovieSceneSubSection.md#__tid_moviescenesection__)
- [\_\_tid\_MovieSceneSignedObject\_\_](ue_ue.MovieSceneSubSection.md#__tid_moviescenesignedobject__)
- [\_\_tid\_MovieSceneSubSection\_\_](ue_ue.MovieSceneSubSection.md#__tid_moviescenesubsection__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneSubSection.md#__tid_object__)
- [bIsActive](ue_ue.MovieSceneSubSection.md#bisactive)
- [bIsInfinite](ue_ue.MovieSceneSubSection.md#bisinfinite)
- [bIsLocked](ue_ue.MovieSceneSubSection.md#bislocked)
- [bSupportsInfiniteRange](ue_ue.MovieSceneSubSection.md#bsupportsinfiniterange)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneSubSection.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneSubSection.md#executeubergraph)
- [GetBlendType](ue_ue.MovieSceneSubSection.md#getblendtype)
- [GetClass](ue_ue.MovieSceneSubSection.md#getclass)
- [GetCompletionMode](ue_ue.MovieSceneSubSection.md#getcompletionmode)
- [GetName](ue_ue.MovieSceneSubSection.md#getname)
- [GetOuter](ue_ue.MovieSceneSubSection.md#getouter)
- [GetOverlapPriority](ue_ue.MovieSceneSubSection.md#getoverlappriority)
- [GetPostRollFrames](ue_ue.MovieSceneSubSection.md#getpostrollframes)
- [GetPreRollFrames](ue_ue.MovieSceneSubSection.md#getprerollframes)
- [GetRowIndex](ue_ue.MovieSceneSubSection.md#getrowindex)
- [GetSequence](ue_ue.MovieSceneSubSection.md#getsequence)
- [GetWorld](ue_ue.MovieSceneSubSection.md#getworld)
- [IsActive](ue_ue.MovieSceneSubSection.md#isactive)
- [IsLocked](ue_ue.MovieSceneSubSection.md#islocked)
- [SetBlendType](ue_ue.MovieSceneSubSection.md#setblendtype)
- [SetCompletionMode](ue_ue.MovieSceneSubSection.md#setcompletionmode)
- [SetIsActive](ue_ue.MovieSceneSubSection.md#setisactive)
- [SetIsLocked](ue_ue.MovieSceneSubSection.md#setislocked)
- [SetOverlapPriority](ue_ue.MovieSceneSubSection.md#setoverlappriority)
- [SetPostRollFrames](ue_ue.MovieSceneSubSection.md#setpostrollframes)
- [SetPreRollFrames](ue_ue.MovieSceneSubSection.md#setprerollframes)
- [SetRowIndex](ue_ue.MovieSceneSubSection.md#setrowindex)
- [SetSequence](ue_ue.MovieSceneSubSection.md#setsequence)
- [Find](ue_ue.MovieSceneSubSection.md#find)
- [Load](ue_ue.MovieSceneSubSection.md#load)
- [StaticClass](ue_ue.MovieSceneSubSection.md#staticclass)

## Constructors

### constructor

• **new MovieSceneSubSection**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneSection](ue_ue.MovieSceneSection.md).[constructor](ue_ue.MovieSceneSection.md#constructor)

#### Defined in

[ue/ue.d.ts:51501](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51501)

## Properties

### ActorToRecord

• **ActorToRecord**: [`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Defined in

[ue/ue.d.ts:51507](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51507)

___

### BlendType

• **BlendType**: [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[BlendType](ue_ue.MovieSceneSection.md#blendtype)

#### Defined in

[ue/ue.d.ts:11796](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11796)

___

### Easing

• **Easing**: [`MovieSceneEasingSettings`](ue_ue.MovieSceneEasingSettings.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[Easing](ue_ue.MovieSceneSection.md#easing)

#### Defined in

[ue/ue.d.ts:11781](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11781)

___

### EndTime

• **EndTime**: `number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[EndTime](ue_ue.MovieSceneSection.md#endtime)

#### Defined in

[ue/ue.d.ts:11791](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11791)

___

### EvalOptions

• **EvalOptions**: [`MovieSceneSectionEvalOptions`](ue_ue.MovieSceneSectionEvalOptions.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[EvalOptions](ue_ue.MovieSceneSection.md#evaloptions)

#### Defined in

[ue/ue.d.ts:11780](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11780)

___

### OverlapPriority

• **OverlapPriority**: `number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[OverlapPriority](ue_ue.MovieSceneSection.md#overlappriority)

#### Defined in

[ue/ue.d.ts:11787](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11787)

___

### Parameters

• **Parameters**: [`MovieSceneSectionParameters`](ue_ue.MovieSceneSectionParameters.md)

#### Defined in

[ue/ue.d.ts:51502](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51502)

___

### PostRollFrames

• **PostRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[PostRollFrames](ue_ue.MovieSceneSection.md#postrollframes)

#### Defined in

[ue/ue.d.ts:11785](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11785)

___

### PostRollTime

• **PostRollTime**: `number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[PostRollTime](ue_ue.MovieSceneSection.md#postrolltime)

#### Defined in

[ue/ue.d.ts:11793](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11793)

___

### PreRollFrames

• **PreRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[PreRollFrames](ue_ue.MovieSceneSection.md#prerollframes)

#### Defined in

[ue/ue.d.ts:11784](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11784)

___

### PreRollTime

• **PreRollTime**: `number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[PreRollTime](ue_ue.MovieSceneSection.md#prerolltime)

#### Defined in

[ue/ue.d.ts:11792](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11792)

___

### PrerollTime

• **PrerollTime**: `number`

#### Defined in

[ue/ue.d.ts:51505](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51505)

___

### RowIndex

• **RowIndex**: `number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[RowIndex](ue_ue.MovieSceneSection.md#rowindex)

#### Defined in

[ue/ue.d.ts:11786](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11786)

___

### SectionRange

• **SectionRange**: [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[SectionRange](ue_ue.MovieSceneSection.md#sectionrange)

#### Defined in

[ue/ue.d.ts:11782](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11782)

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[Signature](ue_ue.MovieSceneSection.md#signature)

#### Defined in

[ue/ue.d.ts:11034](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11034)

___

### StartOffset

• **StartOffset**: `number`

#### Defined in

[ue/ue.d.ts:51503](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51503)

___

### StartTime

• **StartTime**: `number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[StartTime](ue_ue.MovieSceneSection.md#starttime)

#### Defined in

[ue/ue.d.ts:11790](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11790)

___

### SubSequence

• **SubSequence**: [`MovieSceneSequence`](ue_ue.MovieSceneSequence.md)

#### Defined in

[ue/ue.d.ts:51506](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51506)

___

### TargetPathToRecordTo

• **TargetPathToRecordTo**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

#### Defined in

[ue/ue.d.ts:51509](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51509)

___

### TargetSequenceName

• **TargetSequenceName**: `string`

#### Defined in

[ue/ue.d.ts:51508](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51508)

___

### TimeScale

• **TimeScale**: `number`

#### Defined in

[ue/ue.d.ts:51504](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51504)

___

### TimecodeSource

• **TimecodeSource**: [`MovieSceneTimecodeSource`](ue_ue.MovieSceneTimecodeSource.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[TimecodeSource](ue_ue.MovieSceneSection.md#timecodesource)

#### Defined in

[ue/ue.d.ts:11783](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11783)

___

### \_\_tid\_MovieSceneSection\_\_

• **\_\_tid\_MovieSceneSection\_\_**: `boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[__tid_MovieSceneSection__](ue_ue.MovieSceneSection.md#__tid_moviescenesection__)

#### Defined in

[ue/ue.d.ts:11817](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11817)

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneSection.md#__tid_moviescenesignedobject__)

#### Defined in

[ue/ue.d.ts:11039](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11039)

___

### \_\_tid\_MovieSceneSubSection\_\_

• **\_\_tid\_MovieSceneSubSection\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:51516](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51516)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[__tid_Object__](ue_ue.MovieSceneSection.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[bIsActive](ue_ue.MovieSceneSection.md#bisactive)

#### Defined in

[ue/ue.d.ts:11788](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11788)

___

### bIsInfinite

• **bIsInfinite**: `boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[bIsInfinite](ue_ue.MovieSceneSection.md#bisinfinite)

#### Defined in

[ue/ue.d.ts:11794](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11794)

___

### bIsLocked

• **bIsLocked**: `boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[bIsLocked](ue_ue.MovieSceneSection.md#bislocked)

#### Defined in

[ue/ue.d.ts:11789](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11789)

___

### bSupportsInfiniteRange

• **bSupportsInfiniteRange**: `boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[bSupportsInfiniteRange](ue_ue.MovieSceneSection.md#bsupportsinfiniterange)

#### Defined in

[ue/ue.d.ts:11795](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11795)

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

[MovieSceneSection](ue_ue.MovieSceneSection.md).[CreateDefaultSubobject](ue_ue.MovieSceneSection.md#createdefaultsubobject)

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

[MovieSceneSection](ue_ue.MovieSceneSection.md).[ExecuteUbergraph](ue_ue.MovieSceneSection.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetBlendType

▸ **GetBlendType**(): [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Returns

[`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetBlendType](ue_ue.MovieSceneSection.md#getblendtype)

#### Defined in

[ue/ue.d.ts:11797](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11797)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetClass](ue_ue.MovieSceneSection.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetCompletionMode

▸ **GetCompletionMode**(): [`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Returns

[`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetCompletionMode](ue_ue.MovieSceneSection.md#getcompletionmode)

#### Defined in

[ue/ue.d.ts:11798](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11798)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetName](ue_ue.MovieSceneSection.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetOuter](ue_ue.MovieSceneSection.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetOverlapPriority

▸ **GetOverlapPriority**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetOverlapPriority](ue_ue.MovieSceneSection.md#getoverlappriority)

#### Defined in

[ue/ue.d.ts:11799](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11799)

___

### GetPostRollFrames

▸ **GetPostRollFrames**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetPostRollFrames](ue_ue.MovieSceneSection.md#getpostrollframes)

#### Defined in

[ue/ue.d.ts:11800](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11800)

___

### GetPreRollFrames

▸ **GetPreRollFrames**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetPreRollFrames](ue_ue.MovieSceneSection.md#getprerollframes)

#### Defined in

[ue/ue.d.ts:11801](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11801)

___

### GetRowIndex

▸ **GetRowIndex**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetRowIndex](ue_ue.MovieSceneSection.md#getrowindex)

#### Defined in

[ue/ue.d.ts:11802](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11802)

___

### GetSequence

▸ **GetSequence**(): [`MovieSceneSequence`](ue_ue.MovieSceneSequence.md)

#### Returns

[`MovieSceneSequence`](ue_ue.MovieSceneSequence.md)

#### Defined in

[ue/ue.d.ts:51510](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51510)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetWorld](ue_ue.MovieSceneSection.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[IsActive](ue_ue.MovieSceneSection.md#isactive)

#### Defined in

[ue/ue.d.ts:11803](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11803)

___

### IsLocked

▸ **IsLocked**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[IsLocked](ue_ue.MovieSceneSection.md#islocked)

#### Defined in

[ue/ue.d.ts:11804](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11804)

___

### SetBlendType

▸ **SetBlendType**(`InBlendType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBlendType` | [`EMovieSceneBlendType`](../enums/ue_ue.EMovieSceneBlendType.md) |

#### Returns

`void`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[SetBlendType](ue_ue.MovieSceneSection.md#setblendtype)

#### Defined in

[ue/ue.d.ts:11805](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11805)

___

### SetCompletionMode

▸ **SetCompletionMode**(`InCompletionMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InCompletionMode` | [`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md) |

#### Returns

`void`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[SetCompletionMode](ue_ue.MovieSceneSection.md#setcompletionmode)

#### Defined in

[ue/ue.d.ts:11806](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11806)

___

### SetIsActive

▸ **SetIsActive**(`bInIsActive`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInIsActive` | `boolean` |

#### Returns

`void`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[SetIsActive](ue_ue.MovieSceneSection.md#setisactive)

#### Defined in

[ue/ue.d.ts:11807](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11807)

___

### SetIsLocked

▸ **SetIsLocked**(`bInIsLocked`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInIsLocked` | `boolean` |

#### Returns

`void`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[SetIsLocked](ue_ue.MovieSceneSection.md#setislocked)

#### Defined in

[ue/ue.d.ts:11808](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11808)

___

### SetOverlapPriority

▸ **SetOverlapPriority**(`NewPriority`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPriority` | `number` |

#### Returns

`void`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[SetOverlapPriority](ue_ue.MovieSceneSection.md#setoverlappriority)

#### Defined in

[ue/ue.d.ts:11809](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11809)

___

### SetPostRollFrames

▸ **SetPostRollFrames**(`InPostRollFrames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPostRollFrames` | `number` |

#### Returns

`void`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[SetPostRollFrames](ue_ue.MovieSceneSection.md#setpostrollframes)

#### Defined in

[ue/ue.d.ts:11810](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11810)

___

### SetPreRollFrames

▸ **SetPreRollFrames**(`InPreRollFrames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPreRollFrames` | `number` |

#### Returns

`void`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[SetPreRollFrames](ue_ue.MovieSceneSection.md#setprerollframes)

#### Defined in

[ue/ue.d.ts:11811](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11811)

___

### SetRowIndex

▸ **SetRowIndex**(`NewRowIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRowIndex` | `number` |

#### Returns

`void`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[SetRowIndex](ue_ue.MovieSceneSection.md#setrowindex)

#### Defined in

[ue/ue.d.ts:11812](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11812)

___

### SetSequence

▸ **SetSequence**(`Sequence`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Sequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MovieSceneSequence`](ue_ue.MovieSceneSequence.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:51511](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51511)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneSubSection`](ue_ue.MovieSceneSubSection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneSubSection`](ue_ue.MovieSceneSubSection.md)

#### Overrides

[MovieSceneSection](ue_ue.MovieSceneSection.md).[Find](ue_ue.MovieSceneSection.md#find)

#### Defined in

[ue/ue.d.ts:51513](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51513)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneSubSection`](ue_ue.MovieSceneSubSection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneSubSection`](ue_ue.MovieSceneSubSection.md)

#### Overrides

[MovieSceneSection](ue_ue.MovieSceneSection.md).[Load](ue_ue.MovieSceneSection.md#load)

#### Defined in

[ue/ue.d.ts:51514](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51514)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneSection](ue_ue.MovieSceneSection.md).[StaticClass](ue_ue.MovieSceneSection.md#staticclass)

#### Defined in

[ue/ue.d.ts:51512](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51512)