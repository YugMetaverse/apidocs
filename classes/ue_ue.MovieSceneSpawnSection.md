[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneSpawnSection

# Class: MovieSceneSpawnSection

[ue/ue](../modules/ue_ue.md).MovieSceneSpawnSection

## Hierarchy

- [`MovieSceneBoolSection`](ue_ue.MovieSceneBoolSection.md)

  ↳ **`MovieSceneSpawnSection`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneSpawnSection.md#constructor)

### Properties

- [BlendType](ue_ue.MovieSceneSpawnSection.md#blendtype)
- [BoolCurve](ue_ue.MovieSceneSpawnSection.md#boolcurve)
- [DefaultValue](ue_ue.MovieSceneSpawnSection.md#defaultvalue)
- [Easing](ue_ue.MovieSceneSpawnSection.md#easing)
- [EndTime](ue_ue.MovieSceneSpawnSection.md#endtime)
- [EvalOptions](ue_ue.MovieSceneSpawnSection.md#evaloptions)
- [OverlapPriority](ue_ue.MovieSceneSpawnSection.md#overlappriority)
- [PostRollFrames](ue_ue.MovieSceneSpawnSection.md#postrollframes)
- [PostRollTime](ue_ue.MovieSceneSpawnSection.md#postrolltime)
- [PreRollFrames](ue_ue.MovieSceneSpawnSection.md#prerollframes)
- [PreRollTime](ue_ue.MovieSceneSpawnSection.md#prerolltime)
- [RowIndex](ue_ue.MovieSceneSpawnSection.md#rowindex)
- [SectionRange](ue_ue.MovieSceneSpawnSection.md#sectionrange)
- [Signature](ue_ue.MovieSceneSpawnSection.md#signature)
- [StartTime](ue_ue.MovieSceneSpawnSection.md#starttime)
- [TimecodeSource](ue_ue.MovieSceneSpawnSection.md#timecodesource)
- [\_\_tid\_MovieSceneBoolSection\_\_](ue_ue.MovieSceneSpawnSection.md#__tid_moviesceneboolsection__)
- [\_\_tid\_MovieSceneSection\_\_](ue_ue.MovieSceneSpawnSection.md#__tid_moviescenesection__)
- [\_\_tid\_MovieSceneSignedObject\_\_](ue_ue.MovieSceneSpawnSection.md#__tid_moviescenesignedobject__)
- [\_\_tid\_MovieSceneSpawnSection\_\_](ue_ue.MovieSceneSpawnSection.md#__tid_moviescenespawnsection__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneSpawnSection.md#__tid_object__)
- [bIsActive](ue_ue.MovieSceneSpawnSection.md#bisactive)
- [bIsExternallyInverted](ue_ue.MovieSceneSpawnSection.md#bisexternallyinverted)
- [bIsInfinite](ue_ue.MovieSceneSpawnSection.md#bisinfinite)
- [bIsLocked](ue_ue.MovieSceneSpawnSection.md#bislocked)
- [bSupportsInfiniteRange](ue_ue.MovieSceneSpawnSection.md#bsupportsinfiniterange)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneSpawnSection.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneSpawnSection.md#executeubergraph)
- [GetBlendType](ue_ue.MovieSceneSpawnSection.md#getblendtype)
- [GetClass](ue_ue.MovieSceneSpawnSection.md#getclass)
- [GetCompletionMode](ue_ue.MovieSceneSpawnSection.md#getcompletionmode)
- [GetName](ue_ue.MovieSceneSpawnSection.md#getname)
- [GetOuter](ue_ue.MovieSceneSpawnSection.md#getouter)
- [GetOverlapPriority](ue_ue.MovieSceneSpawnSection.md#getoverlappriority)
- [GetPostRollFrames](ue_ue.MovieSceneSpawnSection.md#getpostrollframes)
- [GetPreRollFrames](ue_ue.MovieSceneSpawnSection.md#getprerollframes)
- [GetRowIndex](ue_ue.MovieSceneSpawnSection.md#getrowindex)
- [GetWorld](ue_ue.MovieSceneSpawnSection.md#getworld)
- [IsActive](ue_ue.MovieSceneSpawnSection.md#isactive)
- [IsLocked](ue_ue.MovieSceneSpawnSection.md#islocked)
- [SetBlendType](ue_ue.MovieSceneSpawnSection.md#setblendtype)
- [SetCompletionMode](ue_ue.MovieSceneSpawnSection.md#setcompletionmode)
- [SetIsActive](ue_ue.MovieSceneSpawnSection.md#setisactive)
- [SetIsLocked](ue_ue.MovieSceneSpawnSection.md#setislocked)
- [SetOverlapPriority](ue_ue.MovieSceneSpawnSection.md#setoverlappriority)
- [SetPostRollFrames](ue_ue.MovieSceneSpawnSection.md#setpostrollframes)
- [SetPreRollFrames](ue_ue.MovieSceneSpawnSection.md#setprerollframes)
- [SetRowIndex](ue_ue.MovieSceneSpawnSection.md#setrowindex)
- [Find](ue_ue.MovieSceneSpawnSection.md#find)
- [Load](ue_ue.MovieSceneSpawnSection.md#load)
- [StaticClass](ue_ue.MovieSceneSpawnSection.md#staticclass)

## Constructors

### constructor

• **new MovieSceneSpawnSection**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[constructor](ue_ue.MovieSceneBoolSection.md#constructor)

## Properties

### BlendType

• **BlendType**: [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[BlendType](ue_ue.MovieSceneBoolSection.md#blendtype)

___

### BoolCurve

• **BoolCurve**: [`MovieSceneBoolChannel`](ue_ue.MovieSceneBoolChannel.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[BoolCurve](ue_ue.MovieSceneBoolSection.md#boolcurve)

___

### DefaultValue

• **DefaultValue**: `boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[DefaultValue](ue_ue.MovieSceneBoolSection.md#defaultvalue)

___

### Easing

• **Easing**: [`MovieSceneEasingSettings`](ue_ue.MovieSceneEasingSettings.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[Easing](ue_ue.MovieSceneBoolSection.md#easing)

___

### EndTime

• **EndTime**: `number`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[EndTime](ue_ue.MovieSceneBoolSection.md#endtime)

___

### EvalOptions

• **EvalOptions**: [`MovieSceneSectionEvalOptions`](ue_ue.MovieSceneSectionEvalOptions.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[EvalOptions](ue_ue.MovieSceneBoolSection.md#evaloptions)

___

### OverlapPriority

• **OverlapPriority**: `number`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[OverlapPriority](ue_ue.MovieSceneBoolSection.md#overlappriority)

___

### PostRollFrames

• **PostRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[PostRollFrames](ue_ue.MovieSceneBoolSection.md#postrollframes)

___

### PostRollTime

• **PostRollTime**: `number`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[PostRollTime](ue_ue.MovieSceneBoolSection.md#postrolltime)

___

### PreRollFrames

• **PreRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[PreRollFrames](ue_ue.MovieSceneBoolSection.md#prerollframes)

___

### PreRollTime

• **PreRollTime**: `number`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[PreRollTime](ue_ue.MovieSceneBoolSection.md#prerolltime)

___

### RowIndex

• **RowIndex**: `number`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[RowIndex](ue_ue.MovieSceneBoolSection.md#rowindex)

___

### SectionRange

• **SectionRange**: [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[SectionRange](ue_ue.MovieSceneBoolSection.md#sectionrange)

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[Signature](ue_ue.MovieSceneBoolSection.md#signature)

___

### StartTime

• **StartTime**: `number`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[StartTime](ue_ue.MovieSceneBoolSection.md#starttime)

___

### TimecodeSource

• **TimecodeSource**: [`MovieSceneTimecodeSource`](ue_ue.MovieSceneTimecodeSource.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[TimecodeSource](ue_ue.MovieSceneBoolSection.md#timecodesource)

___

### \_\_tid\_MovieSceneBoolSection\_\_

• **\_\_tid\_MovieSceneBoolSection\_\_**: `boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[__tid_MovieSceneBoolSection__](ue_ue.MovieSceneBoolSection.md#__tid_moviesceneboolsection__)

___

### \_\_tid\_MovieSceneSection\_\_

• **\_\_tid\_MovieSceneSection\_\_**: `boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[__tid_MovieSceneSection__](ue_ue.MovieSceneBoolSection.md#__tid_moviescenesection__)

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneBoolSection.md#__tid_moviescenesignedobject__)

___

### \_\_tid\_MovieSceneSpawnSection\_\_

• **\_\_tid\_MovieSceneSpawnSection\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[__tid_Object__](ue_ue.MovieSceneBoolSection.md#__tid_object__)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[bIsActive](ue_ue.MovieSceneBoolSection.md#bisactive)

___

### bIsExternallyInverted

• **bIsExternallyInverted**: `boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[bIsExternallyInverted](ue_ue.MovieSceneBoolSection.md#bisexternallyinverted)

___

### bIsInfinite

• **bIsInfinite**: `boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[bIsInfinite](ue_ue.MovieSceneBoolSection.md#bisinfinite)

___

### bIsLocked

• **bIsLocked**: `boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[bIsLocked](ue_ue.MovieSceneBoolSection.md#bislocked)

___

### bSupportsInfiniteRange

• **bSupportsInfiniteRange**: `boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[bSupportsInfiniteRange](ue_ue.MovieSceneBoolSection.md#bsupportsinfiniterange)

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

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[CreateDefaultSubobject](ue_ue.MovieSceneBoolSection.md#createdefaultsubobject)

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

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[ExecuteUbergraph](ue_ue.MovieSceneBoolSection.md#executeubergraph)

___

### GetBlendType

▸ **GetBlendType**(): [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Returns

[`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[GetBlendType](ue_ue.MovieSceneBoolSection.md#getblendtype)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[GetClass](ue_ue.MovieSceneBoolSection.md#getclass)

___

### GetCompletionMode

▸ **GetCompletionMode**(): [`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Returns

[`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[GetCompletionMode](ue_ue.MovieSceneBoolSection.md#getcompletionmode)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[GetName](ue_ue.MovieSceneBoolSection.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[GetOuter](ue_ue.MovieSceneBoolSection.md#getouter)

___

### GetOverlapPriority

▸ **GetOverlapPriority**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[GetOverlapPriority](ue_ue.MovieSceneBoolSection.md#getoverlappriority)

___

### GetPostRollFrames

▸ **GetPostRollFrames**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[GetPostRollFrames](ue_ue.MovieSceneBoolSection.md#getpostrollframes)

___

### GetPreRollFrames

▸ **GetPreRollFrames**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[GetPreRollFrames](ue_ue.MovieSceneBoolSection.md#getprerollframes)

___

### GetRowIndex

▸ **GetRowIndex**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[GetRowIndex](ue_ue.MovieSceneBoolSection.md#getrowindex)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[GetWorld](ue_ue.MovieSceneBoolSection.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[IsActive](ue_ue.MovieSceneBoolSection.md#isactive)

___

### IsLocked

▸ **IsLocked**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[IsLocked](ue_ue.MovieSceneBoolSection.md#islocked)

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

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[SetBlendType](ue_ue.MovieSceneBoolSection.md#setblendtype)

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

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[SetCompletionMode](ue_ue.MovieSceneBoolSection.md#setcompletionmode)

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

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[SetIsActive](ue_ue.MovieSceneBoolSection.md#setisactive)

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

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[SetIsLocked](ue_ue.MovieSceneBoolSection.md#setislocked)

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

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[SetOverlapPriority](ue_ue.MovieSceneBoolSection.md#setoverlappriority)

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

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[SetPostRollFrames](ue_ue.MovieSceneBoolSection.md#setpostrollframes)

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

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[SetPreRollFrames](ue_ue.MovieSceneBoolSection.md#setprerollframes)

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

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[SetRowIndex](ue_ue.MovieSceneBoolSection.md#setrowindex)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneSpawnSection`](ue_ue.MovieSceneSpawnSection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneSpawnSection`](ue_ue.MovieSceneSpawnSection.md)

#### Overrides

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[Find](ue_ue.MovieSceneBoolSection.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneSpawnSection`](ue_ue.MovieSceneSpawnSection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneSpawnSection`](ue_ue.MovieSceneSpawnSection.md)

#### Overrides

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[Load](ue_ue.MovieSceneBoolSection.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[StaticClass](ue_ue.MovieSceneBoolSection.md#staticclass)
