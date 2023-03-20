[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneFadeSection

# Class: MovieSceneFadeSection

[ue/ue](../modules/ue_ue.md).MovieSceneFadeSection

## Hierarchy

- [`MovieSceneFloatSection`](ue_ue.MovieSceneFloatSection.md)

  ↳ **`MovieSceneFadeSection`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneFadeSection.md#constructor)

### Properties

- [BlendType](ue_ue.MovieSceneFadeSection.md#blendtype)
- [Easing](ue_ue.MovieSceneFadeSection.md#easing)
- [EndTime](ue_ue.MovieSceneFadeSection.md#endtime)
- [EvalOptions](ue_ue.MovieSceneFadeSection.md#evaloptions)
- [FadeColor](ue_ue.MovieSceneFadeSection.md#fadecolor)
- [FloatCurve](ue_ue.MovieSceneFadeSection.md#floatcurve)
- [OverlapPriority](ue_ue.MovieSceneFadeSection.md#overlappriority)
- [PostRollFrames](ue_ue.MovieSceneFadeSection.md#postrollframes)
- [PostRollTime](ue_ue.MovieSceneFadeSection.md#postrolltime)
- [PreRollFrames](ue_ue.MovieSceneFadeSection.md#prerollframes)
- [PreRollTime](ue_ue.MovieSceneFadeSection.md#prerolltime)
- [RowIndex](ue_ue.MovieSceneFadeSection.md#rowindex)
- [SectionRange](ue_ue.MovieSceneFadeSection.md#sectionrange)
- [Signature](ue_ue.MovieSceneFadeSection.md#signature)
- [StartTime](ue_ue.MovieSceneFadeSection.md#starttime)
- [TimecodeSource](ue_ue.MovieSceneFadeSection.md#timecodesource)
- [\_\_tid\_MovieSceneFadeSection\_\_](ue_ue.MovieSceneFadeSection.md#__tid_moviescenefadesection__)
- [\_\_tid\_MovieSceneFloatSection\_\_](ue_ue.MovieSceneFadeSection.md#__tid_moviescenefloatsection__)
- [\_\_tid\_MovieSceneSection\_\_](ue_ue.MovieSceneFadeSection.md#__tid_moviescenesection__)
- [\_\_tid\_MovieSceneSignedObject\_\_](ue_ue.MovieSceneFadeSection.md#__tid_moviescenesignedobject__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneFadeSection.md#__tid_object__)
- [bFadeAudio](ue_ue.MovieSceneFadeSection.md#bfadeaudio)
- [bIsActive](ue_ue.MovieSceneFadeSection.md#bisactive)
- [bIsInfinite](ue_ue.MovieSceneFadeSection.md#bisinfinite)
- [bIsLocked](ue_ue.MovieSceneFadeSection.md#bislocked)
- [bSupportsInfiniteRange](ue_ue.MovieSceneFadeSection.md#bsupportsinfiniterange)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneFadeSection.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneFadeSection.md#executeubergraph)
- [GetBlendType](ue_ue.MovieSceneFadeSection.md#getblendtype)
- [GetClass](ue_ue.MovieSceneFadeSection.md#getclass)
- [GetCompletionMode](ue_ue.MovieSceneFadeSection.md#getcompletionmode)
- [GetName](ue_ue.MovieSceneFadeSection.md#getname)
- [GetOuter](ue_ue.MovieSceneFadeSection.md#getouter)
- [GetOverlapPriority](ue_ue.MovieSceneFadeSection.md#getoverlappriority)
- [GetPostRollFrames](ue_ue.MovieSceneFadeSection.md#getpostrollframes)
- [GetPreRollFrames](ue_ue.MovieSceneFadeSection.md#getprerollframes)
- [GetRowIndex](ue_ue.MovieSceneFadeSection.md#getrowindex)
- [GetWorld](ue_ue.MovieSceneFadeSection.md#getworld)
- [IsActive](ue_ue.MovieSceneFadeSection.md#isactive)
- [IsLocked](ue_ue.MovieSceneFadeSection.md#islocked)
- [SetBlendType](ue_ue.MovieSceneFadeSection.md#setblendtype)
- [SetCompletionMode](ue_ue.MovieSceneFadeSection.md#setcompletionmode)
- [SetIsActive](ue_ue.MovieSceneFadeSection.md#setisactive)
- [SetIsLocked](ue_ue.MovieSceneFadeSection.md#setislocked)
- [SetOverlapPriority](ue_ue.MovieSceneFadeSection.md#setoverlappriority)
- [SetPostRollFrames](ue_ue.MovieSceneFadeSection.md#setpostrollframes)
- [SetPreRollFrames](ue_ue.MovieSceneFadeSection.md#setprerollframes)
- [SetRowIndex](ue_ue.MovieSceneFadeSection.md#setrowindex)
- [Find](ue_ue.MovieSceneFadeSection.md#find)
- [Load](ue_ue.MovieSceneFadeSection.md#load)
- [StaticClass](ue_ue.MovieSceneFadeSection.md#staticclass)

## Constructors

### constructor

• **new MovieSceneFadeSection**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[constructor](ue_ue.MovieSceneFloatSection.md#constructor)

#### Defined in

[ue/ue.d.ts:51854](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L51854)

## Properties

### BlendType

• **BlendType**: [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[BlendType](ue_ue.MovieSceneFloatSection.md#blendtype)

#### Defined in

[ue/ue.d.ts:11796](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11796)

___

### Easing

• **Easing**: [`MovieSceneEasingSettings`](ue_ue.MovieSceneEasingSettings.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[Easing](ue_ue.MovieSceneFloatSection.md#easing)

#### Defined in

[ue/ue.d.ts:11781](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11781)

___

### EndTime

• **EndTime**: `number`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[EndTime](ue_ue.MovieSceneFloatSection.md#endtime)

#### Defined in

[ue/ue.d.ts:11791](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11791)

___

### EvalOptions

• **EvalOptions**: [`MovieSceneSectionEvalOptions`](ue_ue.MovieSceneSectionEvalOptions.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[EvalOptions](ue_ue.MovieSceneFloatSection.md#evaloptions)

#### Defined in

[ue/ue.d.ts:11780](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11780)

___

### FadeColor

• **FadeColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:51855](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L51855)

___

### FloatCurve

• **FloatCurve**: [`MovieSceneFloatChannel`](ue_ue.MovieSceneFloatChannel.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[FloatCurve](ue_ue.MovieSceneFloatSection.md#floatcurve)

#### Defined in

[ue/ue.d.ts:51845](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L51845)

___

### OverlapPriority

• **OverlapPriority**: `number`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[OverlapPriority](ue_ue.MovieSceneFloatSection.md#overlappriority)

#### Defined in

[ue/ue.d.ts:11787](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11787)

___

### PostRollFrames

• **PostRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[PostRollFrames](ue_ue.MovieSceneFloatSection.md#postrollframes)

#### Defined in

[ue/ue.d.ts:11785](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11785)

___

### PostRollTime

• **PostRollTime**: `number`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[PostRollTime](ue_ue.MovieSceneFloatSection.md#postrolltime)

#### Defined in

[ue/ue.d.ts:11793](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11793)

___

### PreRollFrames

• **PreRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[PreRollFrames](ue_ue.MovieSceneFloatSection.md#prerollframes)

#### Defined in

[ue/ue.d.ts:11784](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11784)

___

### PreRollTime

• **PreRollTime**: `number`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[PreRollTime](ue_ue.MovieSceneFloatSection.md#prerolltime)

#### Defined in

[ue/ue.d.ts:11792](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11792)

___

### RowIndex

• **RowIndex**: `number`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[RowIndex](ue_ue.MovieSceneFloatSection.md#rowindex)

#### Defined in

[ue/ue.d.ts:11786](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11786)

___

### SectionRange

• **SectionRange**: [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[SectionRange](ue_ue.MovieSceneFloatSection.md#sectionrange)

#### Defined in

[ue/ue.d.ts:11782](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11782)

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[Signature](ue_ue.MovieSceneFloatSection.md#signature)

#### Defined in

[ue/ue.d.ts:11034](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11034)

___

### StartTime

• **StartTime**: `number`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[StartTime](ue_ue.MovieSceneFloatSection.md#starttime)

#### Defined in

[ue/ue.d.ts:11790](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11790)

___

### TimecodeSource

• **TimecodeSource**: [`MovieSceneTimecodeSource`](ue_ue.MovieSceneTimecodeSource.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[TimecodeSource](ue_ue.MovieSceneFloatSection.md#timecodesource)

#### Defined in

[ue/ue.d.ts:11783](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11783)

___

### \_\_tid\_MovieSceneFadeSection\_\_

• **\_\_tid\_MovieSceneFadeSection\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:51861](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L51861)

___

### \_\_tid\_MovieSceneFloatSection\_\_

• **\_\_tid\_MovieSceneFloatSection\_\_**: `boolean`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[__tid_MovieSceneFloatSection__](ue_ue.MovieSceneFloatSection.md#__tid_moviescenefloatsection__)

#### Defined in

[ue/ue.d.ts:51850](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L51850)

___

### \_\_tid\_MovieSceneSection\_\_

• **\_\_tid\_MovieSceneSection\_\_**: `boolean`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[__tid_MovieSceneSection__](ue_ue.MovieSceneFloatSection.md#__tid_moviescenesection__)

#### Defined in

[ue/ue.d.ts:11817](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11817)

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneFloatSection.md#__tid_moviescenesignedobject__)

#### Defined in

[ue/ue.d.ts:11039](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11039)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[__tid_Object__](ue_ue.MovieSceneFloatSection.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bFadeAudio

• **bFadeAudio**: `boolean`

#### Defined in

[ue/ue.d.ts:51856](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L51856)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[bIsActive](ue_ue.MovieSceneFloatSection.md#bisactive)

#### Defined in

[ue/ue.d.ts:11788](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11788)

___

### bIsInfinite

• **bIsInfinite**: `boolean`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[bIsInfinite](ue_ue.MovieSceneFloatSection.md#bisinfinite)

#### Defined in

[ue/ue.d.ts:11794](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11794)

___

### bIsLocked

• **bIsLocked**: `boolean`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[bIsLocked](ue_ue.MovieSceneFloatSection.md#bislocked)

#### Defined in

[ue/ue.d.ts:11789](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11789)

___

### bSupportsInfiniteRange

• **bSupportsInfiniteRange**: `boolean`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[bSupportsInfiniteRange](ue_ue.MovieSceneFloatSection.md#bsupportsinfiniterange)

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

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[CreateDefaultSubobject](ue_ue.MovieSceneFloatSection.md#createdefaultsubobject)

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

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[ExecuteUbergraph](ue_ue.MovieSceneFloatSection.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetBlendType

▸ **GetBlendType**(): [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Returns

[`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[GetBlendType](ue_ue.MovieSceneFloatSection.md#getblendtype)

#### Defined in

[ue/ue.d.ts:11797](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11797)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[GetClass](ue_ue.MovieSceneFloatSection.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetCompletionMode

▸ **GetCompletionMode**(): [`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Returns

[`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[GetCompletionMode](ue_ue.MovieSceneFloatSection.md#getcompletionmode)

#### Defined in

[ue/ue.d.ts:11798](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11798)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[GetName](ue_ue.MovieSceneFloatSection.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[GetOuter](ue_ue.MovieSceneFloatSection.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetOverlapPriority

▸ **GetOverlapPriority**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[GetOverlapPriority](ue_ue.MovieSceneFloatSection.md#getoverlappriority)

#### Defined in

[ue/ue.d.ts:11799](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11799)

___

### GetPostRollFrames

▸ **GetPostRollFrames**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[GetPostRollFrames](ue_ue.MovieSceneFloatSection.md#getpostrollframes)

#### Defined in

[ue/ue.d.ts:11800](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11800)

___

### GetPreRollFrames

▸ **GetPreRollFrames**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[GetPreRollFrames](ue_ue.MovieSceneFloatSection.md#getprerollframes)

#### Defined in

[ue/ue.d.ts:11801](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11801)

___

### GetRowIndex

▸ **GetRowIndex**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[GetRowIndex](ue_ue.MovieSceneFloatSection.md#getrowindex)

#### Defined in

[ue/ue.d.ts:11802](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11802)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[GetWorld](ue_ue.MovieSceneFloatSection.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[IsActive](ue_ue.MovieSceneFloatSection.md#isactive)

#### Defined in

[ue/ue.d.ts:11803](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11803)

___

### IsLocked

▸ **IsLocked**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[IsLocked](ue_ue.MovieSceneFloatSection.md#islocked)

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

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[SetBlendType](ue_ue.MovieSceneFloatSection.md#setblendtype)

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

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[SetCompletionMode](ue_ue.MovieSceneFloatSection.md#setcompletionmode)

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

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[SetIsActive](ue_ue.MovieSceneFloatSection.md#setisactive)

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

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[SetIsLocked](ue_ue.MovieSceneFloatSection.md#setislocked)

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

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[SetOverlapPriority](ue_ue.MovieSceneFloatSection.md#setoverlappriority)

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

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[SetPostRollFrames](ue_ue.MovieSceneFloatSection.md#setpostrollframes)

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

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[SetPreRollFrames](ue_ue.MovieSceneFloatSection.md#setprerollframes)

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

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[SetRowIndex](ue_ue.MovieSceneFloatSection.md#setrowindex)

#### Defined in

[ue/ue.d.ts:11812](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11812)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneFadeSection`](ue_ue.MovieSceneFadeSection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneFadeSection`](ue_ue.MovieSceneFadeSection.md)

#### Overrides

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[Find](ue_ue.MovieSceneFloatSection.md#find)

#### Defined in

[ue/ue.d.ts:51858](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L51858)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneFadeSection`](ue_ue.MovieSceneFadeSection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneFadeSection`](ue_ue.MovieSceneFadeSection.md)

#### Overrides

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[Load](ue_ue.MovieSceneFloatSection.md#load)

#### Defined in

[ue/ue.d.ts:51859](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L51859)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[StaticClass](ue_ue.MovieSceneFloatSection.md#staticclass)

#### Defined in

[ue/ue.d.ts:51857](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L51857)
