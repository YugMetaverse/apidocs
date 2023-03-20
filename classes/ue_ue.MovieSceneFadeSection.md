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

## Properties

### BlendType

• **BlendType**: [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[BlendType](ue_ue.MovieSceneFloatSection.md#blendtype)

___

### Easing

• **Easing**: [`MovieSceneEasingSettings`](ue_ue.MovieSceneEasingSettings.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[Easing](ue_ue.MovieSceneFloatSection.md#easing)

___

### EndTime

• **EndTime**: `number`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[EndTime](ue_ue.MovieSceneFloatSection.md#endtime)

___

### EvalOptions

• **EvalOptions**: [`MovieSceneSectionEvalOptions`](ue_ue.MovieSceneSectionEvalOptions.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[EvalOptions](ue_ue.MovieSceneFloatSection.md#evaloptions)

___

### FadeColor

• **FadeColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### FloatCurve

• **FloatCurve**: [`MovieSceneFloatChannel`](ue_ue.MovieSceneFloatChannel.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[FloatCurve](ue_ue.MovieSceneFloatSection.md#floatcurve)

___

### OverlapPriority

• **OverlapPriority**: `number`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[OverlapPriority](ue_ue.MovieSceneFloatSection.md#overlappriority)

___

### PostRollFrames

• **PostRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[PostRollFrames](ue_ue.MovieSceneFloatSection.md#postrollframes)

___

### PostRollTime

• **PostRollTime**: `number`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[PostRollTime](ue_ue.MovieSceneFloatSection.md#postrolltime)

___

### PreRollFrames

• **PreRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[PreRollFrames](ue_ue.MovieSceneFloatSection.md#prerollframes)

___

### PreRollTime

• **PreRollTime**: `number`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[PreRollTime](ue_ue.MovieSceneFloatSection.md#prerolltime)

___

### RowIndex

• **RowIndex**: `number`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[RowIndex](ue_ue.MovieSceneFloatSection.md#rowindex)

___

### SectionRange

• **SectionRange**: [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[SectionRange](ue_ue.MovieSceneFloatSection.md#sectionrange)

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[Signature](ue_ue.MovieSceneFloatSection.md#signature)

___

### StartTime

• **StartTime**: `number`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[StartTime](ue_ue.MovieSceneFloatSection.md#starttime)

___

### TimecodeSource

• **TimecodeSource**: [`MovieSceneTimecodeSource`](ue_ue.MovieSceneTimecodeSource.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[TimecodeSource](ue_ue.MovieSceneFloatSection.md#timecodesource)

___

### \_\_tid\_MovieSceneFadeSection\_\_

• **\_\_tid\_MovieSceneFadeSection\_\_**: `boolean`

___

### \_\_tid\_MovieSceneFloatSection\_\_

• **\_\_tid\_MovieSceneFloatSection\_\_**: `boolean`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[__tid_MovieSceneFloatSection__](ue_ue.MovieSceneFloatSection.md#__tid_moviescenefloatsection__)

___

### \_\_tid\_MovieSceneSection\_\_

• **\_\_tid\_MovieSceneSection\_\_**: `boolean`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[__tid_MovieSceneSection__](ue_ue.MovieSceneFloatSection.md#__tid_moviescenesection__)

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneFloatSection.md#__tid_moviescenesignedobject__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[__tid_Object__](ue_ue.MovieSceneFloatSection.md#__tid_object__)

___

### bFadeAudio

• **bFadeAudio**: `boolean`

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[bIsActive](ue_ue.MovieSceneFloatSection.md#bisactive)

___

### bIsInfinite

• **bIsInfinite**: `boolean`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[bIsInfinite](ue_ue.MovieSceneFloatSection.md#bisinfinite)

___

### bIsLocked

• **bIsLocked**: `boolean`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[bIsLocked](ue_ue.MovieSceneFloatSection.md#bislocked)

___

### bSupportsInfiniteRange

• **bSupportsInfiniteRange**: `boolean`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[bSupportsInfiniteRange](ue_ue.MovieSceneFloatSection.md#bsupportsinfiniterange)

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

___

### GetBlendType

▸ **GetBlendType**(): [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Returns

[`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[GetBlendType](ue_ue.MovieSceneFloatSection.md#getblendtype)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[GetClass](ue_ue.MovieSceneFloatSection.md#getclass)

___

### GetCompletionMode

▸ **GetCompletionMode**(): [`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Returns

[`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[GetCompletionMode](ue_ue.MovieSceneFloatSection.md#getcompletionmode)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[GetName](ue_ue.MovieSceneFloatSection.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[GetOuter](ue_ue.MovieSceneFloatSection.md#getouter)

___

### GetOverlapPriority

▸ **GetOverlapPriority**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[GetOverlapPriority](ue_ue.MovieSceneFloatSection.md#getoverlappriority)

___

### GetPostRollFrames

▸ **GetPostRollFrames**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[GetPostRollFrames](ue_ue.MovieSceneFloatSection.md#getpostrollframes)

___

### GetPreRollFrames

▸ **GetPreRollFrames**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[GetPreRollFrames](ue_ue.MovieSceneFloatSection.md#getprerollframes)

___

### GetRowIndex

▸ **GetRowIndex**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[GetRowIndex](ue_ue.MovieSceneFloatSection.md#getrowindex)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[GetWorld](ue_ue.MovieSceneFloatSection.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[IsActive](ue_ue.MovieSceneFloatSection.md#isactive)

___

### IsLocked

▸ **IsLocked**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[IsLocked](ue_ue.MovieSceneFloatSection.md#islocked)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneFloatSection](ue_ue.MovieSceneFloatSection.md).[StaticClass](ue_ue.MovieSceneFloatSection.md#staticclass)
