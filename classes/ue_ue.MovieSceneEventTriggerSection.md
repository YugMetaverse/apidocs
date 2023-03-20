[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneEventTriggerSection

# Class: MovieSceneEventTriggerSection

[ue/ue](../modules/ue_ue.md).MovieSceneEventTriggerSection

## Hierarchy

- [`MovieSceneEventSectionBase`](ue_ue.MovieSceneEventSectionBase.md)

  ↳ **`MovieSceneEventTriggerSection`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneEventTriggerSection.md#constructor)

### Properties

- [BlendType](ue_ue.MovieSceneEventTriggerSection.md#blendtype)
- [DirectorBlueprint](ue_ue.MovieSceneEventTriggerSection.md#directorblueprint)
- [Easing](ue_ue.MovieSceneEventTriggerSection.md#easing)
- [EndTime](ue_ue.MovieSceneEventTriggerSection.md#endtime)
- [EvalOptions](ue_ue.MovieSceneEventTriggerSection.md#evaloptions)
- [EventChannel](ue_ue.MovieSceneEventTriggerSection.md#eventchannel)
- [OverlapPriority](ue_ue.MovieSceneEventTriggerSection.md#overlappriority)
- [PostRollFrames](ue_ue.MovieSceneEventTriggerSection.md#postrollframes)
- [PostRollTime](ue_ue.MovieSceneEventTriggerSection.md#postrolltime)
- [PreRollFrames](ue_ue.MovieSceneEventTriggerSection.md#prerollframes)
- [PreRollTime](ue_ue.MovieSceneEventTriggerSection.md#prerolltime)
- [RowIndex](ue_ue.MovieSceneEventTriggerSection.md#rowindex)
- [SectionRange](ue_ue.MovieSceneEventTriggerSection.md#sectionrange)
- [Signature](ue_ue.MovieSceneEventTriggerSection.md#signature)
- [StartTime](ue_ue.MovieSceneEventTriggerSection.md#starttime)
- [TimecodeSource](ue_ue.MovieSceneEventTriggerSection.md#timecodesource)
- [\_\_tid\_MovieSceneEventSectionBase\_\_](ue_ue.MovieSceneEventTriggerSection.md#__tid_moviesceneeventsectionbase__)
- [\_\_tid\_MovieSceneEventTriggerSection\_\_](ue_ue.MovieSceneEventTriggerSection.md#__tid_moviesceneeventtriggersection__)
- [\_\_tid\_MovieSceneSection\_\_](ue_ue.MovieSceneEventTriggerSection.md#__tid_moviescenesection__)
- [\_\_tid\_MovieSceneSignedObject\_\_](ue_ue.MovieSceneEventTriggerSection.md#__tid_moviescenesignedobject__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneEventTriggerSection.md#__tid_object__)
- [bIsActive](ue_ue.MovieSceneEventTriggerSection.md#bisactive)
- [bIsInfinite](ue_ue.MovieSceneEventTriggerSection.md#bisinfinite)
- [bIsLocked](ue_ue.MovieSceneEventTriggerSection.md#bislocked)
- [bSupportsInfiniteRange](ue_ue.MovieSceneEventTriggerSection.md#bsupportsinfiniterange)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneEventTriggerSection.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneEventTriggerSection.md#executeubergraph)
- [GetBlendType](ue_ue.MovieSceneEventTriggerSection.md#getblendtype)
- [GetClass](ue_ue.MovieSceneEventTriggerSection.md#getclass)
- [GetCompletionMode](ue_ue.MovieSceneEventTriggerSection.md#getcompletionmode)
- [GetName](ue_ue.MovieSceneEventTriggerSection.md#getname)
- [GetOuter](ue_ue.MovieSceneEventTriggerSection.md#getouter)
- [GetOverlapPriority](ue_ue.MovieSceneEventTriggerSection.md#getoverlappriority)
- [GetPostRollFrames](ue_ue.MovieSceneEventTriggerSection.md#getpostrollframes)
- [GetPreRollFrames](ue_ue.MovieSceneEventTriggerSection.md#getprerollframes)
- [GetRowIndex](ue_ue.MovieSceneEventTriggerSection.md#getrowindex)
- [GetWorld](ue_ue.MovieSceneEventTriggerSection.md#getworld)
- [IsActive](ue_ue.MovieSceneEventTriggerSection.md#isactive)
- [IsLocked](ue_ue.MovieSceneEventTriggerSection.md#islocked)
- [SetBlendType](ue_ue.MovieSceneEventTriggerSection.md#setblendtype)
- [SetCompletionMode](ue_ue.MovieSceneEventTriggerSection.md#setcompletionmode)
- [SetIsActive](ue_ue.MovieSceneEventTriggerSection.md#setisactive)
- [SetIsLocked](ue_ue.MovieSceneEventTriggerSection.md#setislocked)
- [SetOverlapPriority](ue_ue.MovieSceneEventTriggerSection.md#setoverlappriority)
- [SetPostRollFrames](ue_ue.MovieSceneEventTriggerSection.md#setpostrollframes)
- [SetPreRollFrames](ue_ue.MovieSceneEventTriggerSection.md#setprerollframes)
- [SetRowIndex](ue_ue.MovieSceneEventTriggerSection.md#setrowindex)
- [Find](ue_ue.MovieSceneEventTriggerSection.md#find)
- [Load](ue_ue.MovieSceneEventTriggerSection.md#load)
- [StaticClass](ue_ue.MovieSceneEventTriggerSection.md#staticclass)

## Constructors

### constructor

• **new MovieSceneEventTriggerSection**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[constructor](ue_ue.MovieSceneEventSectionBase.md#constructor)

## Properties

### BlendType

• **BlendType**: [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[BlendType](ue_ue.MovieSceneEventSectionBase.md#blendtype)

___

### DirectorBlueprint

• **DirectorBlueprint**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Blueprint`](ue_ue.Blueprint.md)\>

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[DirectorBlueprint](ue_ue.MovieSceneEventSectionBase.md#directorblueprint)

___

### Easing

• **Easing**: [`MovieSceneEasingSettings`](ue_ue.MovieSceneEasingSettings.md)

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[Easing](ue_ue.MovieSceneEventSectionBase.md#easing)

___

### EndTime

• **EndTime**: `number`

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[EndTime](ue_ue.MovieSceneEventSectionBase.md#endtime)

___

### EvalOptions

• **EvalOptions**: [`MovieSceneSectionEvalOptions`](ue_ue.MovieSceneSectionEvalOptions.md)

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[EvalOptions](ue_ue.MovieSceneEventSectionBase.md#evaloptions)

___

### EventChannel

• **EventChannel**: [`MovieSceneEventChannel`](ue_ue.MovieSceneEventChannel.md)

___

### OverlapPriority

• **OverlapPriority**: `number`

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[OverlapPriority](ue_ue.MovieSceneEventSectionBase.md#overlappriority)

___

### PostRollFrames

• **PostRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[PostRollFrames](ue_ue.MovieSceneEventSectionBase.md#postrollframes)

___

### PostRollTime

• **PostRollTime**: `number`

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[PostRollTime](ue_ue.MovieSceneEventSectionBase.md#postrolltime)

___

### PreRollFrames

• **PreRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[PreRollFrames](ue_ue.MovieSceneEventSectionBase.md#prerollframes)

___

### PreRollTime

• **PreRollTime**: `number`

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[PreRollTime](ue_ue.MovieSceneEventSectionBase.md#prerolltime)

___

### RowIndex

• **RowIndex**: `number`

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[RowIndex](ue_ue.MovieSceneEventSectionBase.md#rowindex)

___

### SectionRange

• **SectionRange**: [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[SectionRange](ue_ue.MovieSceneEventSectionBase.md#sectionrange)

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[Signature](ue_ue.MovieSceneEventSectionBase.md#signature)

___

### StartTime

• **StartTime**: `number`

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[StartTime](ue_ue.MovieSceneEventSectionBase.md#starttime)

___

### TimecodeSource

• **TimecodeSource**: [`MovieSceneTimecodeSource`](ue_ue.MovieSceneTimecodeSource.md)

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[TimecodeSource](ue_ue.MovieSceneEventSectionBase.md#timecodesource)

___

### \_\_tid\_MovieSceneEventSectionBase\_\_

• **\_\_tid\_MovieSceneEventSectionBase\_\_**: `boolean`

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[__tid_MovieSceneEventSectionBase__](ue_ue.MovieSceneEventSectionBase.md#__tid_moviesceneeventsectionbase__)

___

### \_\_tid\_MovieSceneEventTriggerSection\_\_

• **\_\_tid\_MovieSceneEventTriggerSection\_\_**: `boolean`

___

### \_\_tid\_MovieSceneSection\_\_

• **\_\_tid\_MovieSceneSection\_\_**: `boolean`

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[__tid_MovieSceneSection__](ue_ue.MovieSceneEventSectionBase.md#__tid_moviescenesection__)

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneEventSectionBase.md#__tid_moviescenesignedobject__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[__tid_Object__](ue_ue.MovieSceneEventSectionBase.md#__tid_object__)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[bIsActive](ue_ue.MovieSceneEventSectionBase.md#bisactive)

___

### bIsInfinite

• **bIsInfinite**: `boolean`

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[bIsInfinite](ue_ue.MovieSceneEventSectionBase.md#bisinfinite)

___

### bIsLocked

• **bIsLocked**: `boolean`

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[bIsLocked](ue_ue.MovieSceneEventSectionBase.md#bislocked)

___

### bSupportsInfiniteRange

• **bSupportsInfiniteRange**: `boolean`

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[bSupportsInfiniteRange](ue_ue.MovieSceneEventSectionBase.md#bsupportsinfiniterange)

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

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[CreateDefaultSubobject](ue_ue.MovieSceneEventSectionBase.md#createdefaultsubobject)

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

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[ExecuteUbergraph](ue_ue.MovieSceneEventSectionBase.md#executeubergraph)

___

### GetBlendType

▸ **GetBlendType**(): [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Returns

[`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[GetBlendType](ue_ue.MovieSceneEventSectionBase.md#getblendtype)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[GetClass](ue_ue.MovieSceneEventSectionBase.md#getclass)

___

### GetCompletionMode

▸ **GetCompletionMode**(): [`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Returns

[`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[GetCompletionMode](ue_ue.MovieSceneEventSectionBase.md#getcompletionmode)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[GetName](ue_ue.MovieSceneEventSectionBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[GetOuter](ue_ue.MovieSceneEventSectionBase.md#getouter)

___

### GetOverlapPriority

▸ **GetOverlapPriority**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[GetOverlapPriority](ue_ue.MovieSceneEventSectionBase.md#getoverlappriority)

___

### GetPostRollFrames

▸ **GetPostRollFrames**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[GetPostRollFrames](ue_ue.MovieSceneEventSectionBase.md#getpostrollframes)

___

### GetPreRollFrames

▸ **GetPreRollFrames**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[GetPreRollFrames](ue_ue.MovieSceneEventSectionBase.md#getprerollframes)

___

### GetRowIndex

▸ **GetRowIndex**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[GetRowIndex](ue_ue.MovieSceneEventSectionBase.md#getrowindex)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[GetWorld](ue_ue.MovieSceneEventSectionBase.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[IsActive](ue_ue.MovieSceneEventSectionBase.md#isactive)

___

### IsLocked

▸ **IsLocked**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[IsLocked](ue_ue.MovieSceneEventSectionBase.md#islocked)

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

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[SetBlendType](ue_ue.MovieSceneEventSectionBase.md#setblendtype)

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

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[SetCompletionMode](ue_ue.MovieSceneEventSectionBase.md#setcompletionmode)

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

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[SetIsActive](ue_ue.MovieSceneEventSectionBase.md#setisactive)

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

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[SetIsLocked](ue_ue.MovieSceneEventSectionBase.md#setislocked)

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

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[SetOverlapPriority](ue_ue.MovieSceneEventSectionBase.md#setoverlappriority)

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

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[SetPostRollFrames](ue_ue.MovieSceneEventSectionBase.md#setpostrollframes)

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

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[SetPreRollFrames](ue_ue.MovieSceneEventSectionBase.md#setprerollframes)

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

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[SetRowIndex](ue_ue.MovieSceneEventSectionBase.md#setrowindex)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneEventTriggerSection`](ue_ue.MovieSceneEventTriggerSection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneEventTriggerSection`](ue_ue.MovieSceneEventTriggerSection.md)

#### Overrides

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[Find](ue_ue.MovieSceneEventSectionBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneEventTriggerSection`](ue_ue.MovieSceneEventTriggerSection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneEventTriggerSection`](ue_ue.MovieSceneEventTriggerSection.md)

#### Overrides

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[Load](ue_ue.MovieSceneEventSectionBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneEventSectionBase](ue_ue.MovieSceneEventSectionBase.md).[StaticClass](ue_ue.MovieSceneEventSectionBase.md#staticclass)
