[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneAudioSection

# Class: MovieSceneAudioSection

[ue/ue](../modules/ue_ue.md).MovieSceneAudioSection

## Hierarchy

- [`MovieSceneSection`](ue_ue.MovieSceneSection.md)

  ↳ **`MovieSceneAudioSection`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneAudioSection.md#constructor)

### Properties

- [AttenuationSettings](ue_ue.MovieSceneAudioSection.md#attenuationsettings)
- [AudioDilationFactor](ue_ue.MovieSceneAudioSection.md#audiodilationfactor)
- [AudioStartTime](ue_ue.MovieSceneAudioSection.md#audiostarttime)
- [AudioVolume](ue_ue.MovieSceneAudioSection.md#audiovolume)
- [BlendType](ue_ue.MovieSceneAudioSection.md#blendtype)
- [Easing](ue_ue.MovieSceneAudioSection.md#easing)
- [EndTime](ue_ue.MovieSceneAudioSection.md#endtime)
- [EvalOptions](ue_ue.MovieSceneAudioSection.md#evaloptions)
- [OnAudioFinished](ue_ue.MovieSceneAudioSection.md#onaudiofinished)
- [OnAudioPlaybackPercent](ue_ue.MovieSceneAudioSection.md#onaudioplaybackpercent)
- [OnQueueSubtitles](ue_ue.MovieSceneAudioSection.md#onqueuesubtitles)
- [OverlapPriority](ue_ue.MovieSceneAudioSection.md#overlappriority)
- [PitchMultiplier](ue_ue.MovieSceneAudioSection.md#pitchmultiplier)
- [PostRollFrames](ue_ue.MovieSceneAudioSection.md#postrollframes)
- [PostRollTime](ue_ue.MovieSceneAudioSection.md#postrolltime)
- [PreRollFrames](ue_ue.MovieSceneAudioSection.md#prerollframes)
- [PreRollTime](ue_ue.MovieSceneAudioSection.md#prerolltime)
- [RowIndex](ue_ue.MovieSceneAudioSection.md#rowindex)
- [SectionRange](ue_ue.MovieSceneAudioSection.md#sectionrange)
- [Signature](ue_ue.MovieSceneAudioSection.md#signature)
- [Sound](ue_ue.MovieSceneAudioSection.md#sound)
- [SoundVolume](ue_ue.MovieSceneAudioSection.md#soundvolume)
- [StartFrameOffset](ue_ue.MovieSceneAudioSection.md#startframeoffset)
- [StartOffset](ue_ue.MovieSceneAudioSection.md#startoffset)
- [StartTime](ue_ue.MovieSceneAudioSection.md#starttime)
- [TimecodeSource](ue_ue.MovieSceneAudioSection.md#timecodesource)
- [\_\_tid\_MovieSceneAudioSection\_\_](ue_ue.MovieSceneAudioSection.md#__tid_moviesceneaudiosection__)
- [\_\_tid\_MovieSceneSection\_\_](ue_ue.MovieSceneAudioSection.md#__tid_moviescenesection__)
- [\_\_tid\_MovieSceneSignedObject\_\_](ue_ue.MovieSceneAudioSection.md#__tid_moviescenesignedobject__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneAudioSection.md#__tid_object__)
- [bIsActive](ue_ue.MovieSceneAudioSection.md#bisactive)
- [bIsInfinite](ue_ue.MovieSceneAudioSection.md#bisinfinite)
- [bIsLocked](ue_ue.MovieSceneAudioSection.md#bislocked)
- [bOverrideAttenuation](ue_ue.MovieSceneAudioSection.md#boverrideattenuation)
- [bSupportsInfiniteRange](ue_ue.MovieSceneAudioSection.md#bsupportsinfiniterange)
- [bSuppressSubtitles](ue_ue.MovieSceneAudioSection.md#bsuppresssubtitles)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneAudioSection.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneAudioSection.md#executeubergraph)
- [GetBlendType](ue_ue.MovieSceneAudioSection.md#getblendtype)
- [GetClass](ue_ue.MovieSceneAudioSection.md#getclass)
- [GetCompletionMode](ue_ue.MovieSceneAudioSection.md#getcompletionmode)
- [GetName](ue_ue.MovieSceneAudioSection.md#getname)
- [GetOuter](ue_ue.MovieSceneAudioSection.md#getouter)
- [GetOverlapPriority](ue_ue.MovieSceneAudioSection.md#getoverlappriority)
- [GetPostRollFrames](ue_ue.MovieSceneAudioSection.md#getpostrollframes)
- [GetPreRollFrames](ue_ue.MovieSceneAudioSection.md#getprerollframes)
- [GetRowIndex](ue_ue.MovieSceneAudioSection.md#getrowindex)
- [GetSound](ue_ue.MovieSceneAudioSection.md#getsound)
- [GetStartOffset](ue_ue.MovieSceneAudioSection.md#getstartoffset)
- [GetWorld](ue_ue.MovieSceneAudioSection.md#getworld)
- [IsActive](ue_ue.MovieSceneAudioSection.md#isactive)
- [IsLocked](ue_ue.MovieSceneAudioSection.md#islocked)
- [SetBlendType](ue_ue.MovieSceneAudioSection.md#setblendtype)
- [SetCompletionMode](ue_ue.MovieSceneAudioSection.md#setcompletionmode)
- [SetIsActive](ue_ue.MovieSceneAudioSection.md#setisactive)
- [SetIsLocked](ue_ue.MovieSceneAudioSection.md#setislocked)
- [SetOverlapPriority](ue_ue.MovieSceneAudioSection.md#setoverlappriority)
- [SetPostRollFrames](ue_ue.MovieSceneAudioSection.md#setpostrollframes)
- [SetPreRollFrames](ue_ue.MovieSceneAudioSection.md#setprerollframes)
- [SetRowIndex](ue_ue.MovieSceneAudioSection.md#setrowindex)
- [SetSound](ue_ue.MovieSceneAudioSection.md#setsound)
- [SetStartOffset](ue_ue.MovieSceneAudioSection.md#setstartoffset)
- [Find](ue_ue.MovieSceneAudioSection.md#find)
- [Load](ue_ue.MovieSceneAudioSection.md#load)
- [StaticClass](ue_ue.MovieSceneAudioSection.md#staticclass)

## Constructors

### constructor

• **new MovieSceneAudioSection**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneSection](ue_ue.MovieSceneSection.md).[constructor](ue_ue.MovieSceneSection.md#constructor)

## Properties

### AttenuationSettings

• **AttenuationSettings**: [`SoundAttenuation`](ue_ue.SoundAttenuation.md)

___

### AudioDilationFactor

• **AudioDilationFactor**: `number`

___

### AudioStartTime

• **AudioStartTime**: `number`

___

### AudioVolume

• **AudioVolume**: `number`

___

### BlendType

• **BlendType**: [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[BlendType](ue_ue.MovieSceneSection.md#blendtype)

___

### Easing

• **Easing**: [`MovieSceneEasingSettings`](ue_ue.MovieSceneEasingSettings.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[Easing](ue_ue.MovieSceneSection.md#easing)

___

### EndTime

• **EndTime**: `number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[EndTime](ue_ue.MovieSceneSection.md#endtime)

___

### EvalOptions

• **EvalOptions**: [`MovieSceneSectionEvalOptions`](ue_ue.MovieSceneSectionEvalOptions.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[EvalOptions](ue_ue.MovieSceneSection.md#evaloptions)

___

### OnAudioFinished

• **OnAudioFinished**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### OnAudioPlaybackPercent

• **OnAudioPlaybackPercent**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`PlayingSoundWave`: [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundWave`](ue_ue.SoundWave.md)\>, `PlaybackPercent`: `number`) => `void`\>

___

### OnQueueSubtitles

• **OnQueueSubtitles**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`Subtitles`: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SubtitleCue`](ue_ue.SubtitleCue.md)\>, `CueDuration`: `number`) => `void`\>

___

### OverlapPriority

• **OverlapPriority**: `number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[OverlapPriority](ue_ue.MovieSceneSection.md#overlappriority)

___

### PitchMultiplier

• **PitchMultiplier**: [`MovieSceneFloatChannel`](ue_ue.MovieSceneFloatChannel.md)

___

### PostRollFrames

• **PostRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[PostRollFrames](ue_ue.MovieSceneSection.md#postrollframes)

___

### PostRollTime

• **PostRollTime**: `number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[PostRollTime](ue_ue.MovieSceneSection.md#postrolltime)

___

### PreRollFrames

• **PreRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[PreRollFrames](ue_ue.MovieSceneSection.md#prerollframes)

___

### PreRollTime

• **PreRollTime**: `number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[PreRollTime](ue_ue.MovieSceneSection.md#prerolltime)

___

### RowIndex

• **RowIndex**: `number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[RowIndex](ue_ue.MovieSceneSection.md#rowindex)

___

### SectionRange

• **SectionRange**: [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[SectionRange](ue_ue.MovieSceneSection.md#sectionrange)

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[Signature](ue_ue.MovieSceneSection.md#signature)

___

### Sound

• **Sound**: [`SoundBase`](ue_ue.SoundBase.md)

___

### SoundVolume

• **SoundVolume**: [`MovieSceneFloatChannel`](ue_ue.MovieSceneFloatChannel.md)

___

### StartFrameOffset

• **StartFrameOffset**: [`FrameNumber`](ue_ue.FrameNumber.md)

___

### StartOffset

• **StartOffset**: `number`

___

### StartTime

• **StartTime**: `number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[StartTime](ue_ue.MovieSceneSection.md#starttime)

___

### TimecodeSource

• **TimecodeSource**: [`MovieSceneTimecodeSource`](ue_ue.MovieSceneTimecodeSource.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[TimecodeSource](ue_ue.MovieSceneSection.md#timecodesource)

___

### \_\_tid\_MovieSceneAudioSection\_\_

• **\_\_tid\_MovieSceneAudioSection\_\_**: `boolean`

___

### \_\_tid\_MovieSceneSection\_\_

• **\_\_tid\_MovieSceneSection\_\_**: `boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[__tid_MovieSceneSection__](ue_ue.MovieSceneSection.md#__tid_moviescenesection__)

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneSection.md#__tid_moviescenesignedobject__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[__tid_Object__](ue_ue.MovieSceneSection.md#__tid_object__)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[bIsActive](ue_ue.MovieSceneSection.md#bisactive)

___

### bIsInfinite

• **bIsInfinite**: `boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[bIsInfinite](ue_ue.MovieSceneSection.md#bisinfinite)

___

### bIsLocked

• **bIsLocked**: `boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[bIsLocked](ue_ue.MovieSceneSection.md#bislocked)

___

### bOverrideAttenuation

• **bOverrideAttenuation**: `boolean`

___

### bSupportsInfiniteRange

• **bSupportsInfiniteRange**: `boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[bSupportsInfiniteRange](ue_ue.MovieSceneSection.md#bsupportsinfiniterange)

___

### bSuppressSubtitles

• **bSuppressSubtitles**: `boolean`

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

___

### GetBlendType

▸ **GetBlendType**(): [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Returns

[`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetBlendType](ue_ue.MovieSceneSection.md#getblendtype)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetClass](ue_ue.MovieSceneSection.md#getclass)

___

### GetCompletionMode

▸ **GetCompletionMode**(): [`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Returns

[`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetCompletionMode](ue_ue.MovieSceneSection.md#getcompletionmode)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetName](ue_ue.MovieSceneSection.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetOuter](ue_ue.MovieSceneSection.md#getouter)

___

### GetOverlapPriority

▸ **GetOverlapPriority**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetOverlapPriority](ue_ue.MovieSceneSection.md#getoverlappriority)

___

### GetPostRollFrames

▸ **GetPostRollFrames**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetPostRollFrames](ue_ue.MovieSceneSection.md#getpostrollframes)

___

### GetPreRollFrames

▸ **GetPreRollFrames**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetPreRollFrames](ue_ue.MovieSceneSection.md#getprerollframes)

___

### GetRowIndex

▸ **GetRowIndex**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetRowIndex](ue_ue.MovieSceneSection.md#getrowindex)

___

### GetSound

▸ **GetSound**(): [`SoundBase`](ue_ue.SoundBase.md)

#### Returns

[`SoundBase`](ue_ue.SoundBase.md)

___

### GetStartOffset

▸ **GetStartOffset**(): [`FrameNumber`](ue_ue.FrameNumber.md)

#### Returns

[`FrameNumber`](ue_ue.FrameNumber.md)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetWorld](ue_ue.MovieSceneSection.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[IsActive](ue_ue.MovieSceneSection.md#isactive)

___

### IsLocked

▸ **IsLocked**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[IsLocked](ue_ue.MovieSceneSection.md#islocked)

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

___

### SetSound

▸ **SetSound**(`InSound`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSound` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundBase`](ue_ue.SoundBase.md)\> |

#### Returns

`void`

___

### SetStartOffset

▸ **SetStartOffset**(`InStartOffset`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InStartOffset` | [`FrameNumber`](ue_ue.FrameNumber.md) |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneAudioSection`](ue_ue.MovieSceneAudioSection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneAudioSection`](ue_ue.MovieSceneAudioSection.md)

#### Overrides

[MovieSceneSection](ue_ue.MovieSceneSection.md).[Find](ue_ue.MovieSceneSection.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneAudioSection`](ue_ue.MovieSceneAudioSection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneAudioSection`](ue_ue.MovieSceneAudioSection.md)

#### Overrides

[MovieSceneSection](ue_ue.MovieSceneSection.md).[Load](ue_ue.MovieSceneSection.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneSection](ue_ue.MovieSceneSection.md).[StaticClass](ue_ue.MovieSceneSection.md#staticclass)
