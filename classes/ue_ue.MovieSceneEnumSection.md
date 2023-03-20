[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneEnumSection

# Class: MovieSceneEnumSection

[ue/ue](../modules/ue_ue.md).MovieSceneEnumSection

## Hierarchy

- [`MovieSceneSection`](ue_ue.MovieSceneSection.md)

  ↳ **`MovieSceneEnumSection`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneEnumSection.md#constructor)

### Properties

- [BlendType](ue_ue.MovieSceneEnumSection.md#blendtype)
- [Easing](ue_ue.MovieSceneEnumSection.md#easing)
- [EndTime](ue_ue.MovieSceneEnumSection.md#endtime)
- [EnumCurve](ue_ue.MovieSceneEnumSection.md#enumcurve)
- [EvalOptions](ue_ue.MovieSceneEnumSection.md#evaloptions)
- [OverlapPriority](ue_ue.MovieSceneEnumSection.md#overlappriority)
- [PostRollFrames](ue_ue.MovieSceneEnumSection.md#postrollframes)
- [PostRollTime](ue_ue.MovieSceneEnumSection.md#postrolltime)
- [PreRollFrames](ue_ue.MovieSceneEnumSection.md#prerollframes)
- [PreRollTime](ue_ue.MovieSceneEnumSection.md#prerolltime)
- [RowIndex](ue_ue.MovieSceneEnumSection.md#rowindex)
- [SectionRange](ue_ue.MovieSceneEnumSection.md#sectionrange)
- [Signature](ue_ue.MovieSceneEnumSection.md#signature)
- [StartTime](ue_ue.MovieSceneEnumSection.md#starttime)
- [TimecodeSource](ue_ue.MovieSceneEnumSection.md#timecodesource)
- [\_\_tid\_MovieSceneEnumSection\_\_](ue_ue.MovieSceneEnumSection.md#__tid_moviesceneenumsection__)
- [\_\_tid\_MovieSceneSection\_\_](ue_ue.MovieSceneEnumSection.md#__tid_moviescenesection__)
- [\_\_tid\_MovieSceneSignedObject\_\_](ue_ue.MovieSceneEnumSection.md#__tid_moviescenesignedobject__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneEnumSection.md#__tid_object__)
- [bIsActive](ue_ue.MovieSceneEnumSection.md#bisactive)
- [bIsInfinite](ue_ue.MovieSceneEnumSection.md#bisinfinite)
- [bIsLocked](ue_ue.MovieSceneEnumSection.md#bislocked)
- [bSupportsInfiniteRange](ue_ue.MovieSceneEnumSection.md#bsupportsinfiniterange)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneEnumSection.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneEnumSection.md#executeubergraph)
- [GetBlendType](ue_ue.MovieSceneEnumSection.md#getblendtype)
- [GetClass](ue_ue.MovieSceneEnumSection.md#getclass)
- [GetCompletionMode](ue_ue.MovieSceneEnumSection.md#getcompletionmode)
- [GetName](ue_ue.MovieSceneEnumSection.md#getname)
- [GetOuter](ue_ue.MovieSceneEnumSection.md#getouter)
- [GetOverlapPriority](ue_ue.MovieSceneEnumSection.md#getoverlappriority)
- [GetPostRollFrames](ue_ue.MovieSceneEnumSection.md#getpostrollframes)
- [GetPreRollFrames](ue_ue.MovieSceneEnumSection.md#getprerollframes)
- [GetRowIndex](ue_ue.MovieSceneEnumSection.md#getrowindex)
- [GetWorld](ue_ue.MovieSceneEnumSection.md#getworld)
- [IsActive](ue_ue.MovieSceneEnumSection.md#isactive)
- [IsLocked](ue_ue.MovieSceneEnumSection.md#islocked)
- [SetBlendType](ue_ue.MovieSceneEnumSection.md#setblendtype)
- [SetCompletionMode](ue_ue.MovieSceneEnumSection.md#setcompletionmode)
- [SetIsActive](ue_ue.MovieSceneEnumSection.md#setisactive)
- [SetIsLocked](ue_ue.MovieSceneEnumSection.md#setislocked)
- [SetOverlapPriority](ue_ue.MovieSceneEnumSection.md#setoverlappriority)
- [SetPostRollFrames](ue_ue.MovieSceneEnumSection.md#setpostrollframes)
- [SetPreRollFrames](ue_ue.MovieSceneEnumSection.md#setprerollframes)
- [SetRowIndex](ue_ue.MovieSceneEnumSection.md#setrowindex)
- [Find](ue_ue.MovieSceneEnumSection.md#find)
- [Load](ue_ue.MovieSceneEnumSection.md#load)
- [StaticClass](ue_ue.MovieSceneEnumSection.md#staticclass)

## Constructors

### constructor

• **new MovieSceneEnumSection**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneSection](ue_ue.MovieSceneSection.md).[constructor](ue_ue.MovieSceneSection.md#constructor)

#### Defined in

[ue/ue.d.ts:51631](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L51631)

## Properties

### BlendType

• **BlendType**: [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[BlendType](ue_ue.MovieSceneSection.md#blendtype)

#### Defined in

[ue/ue.d.ts:11796](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11796)

___

### Easing

• **Easing**: [`MovieSceneEasingSettings`](ue_ue.MovieSceneEasingSettings.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[Easing](ue_ue.MovieSceneSection.md#easing)

#### Defined in

[ue/ue.d.ts:11781](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11781)

___

### EndTime

• **EndTime**: `number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[EndTime](ue_ue.MovieSceneSection.md#endtime)

#### Defined in

[ue/ue.d.ts:11791](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11791)

___

### EnumCurve

• **EnumCurve**: [`MovieSceneByteChannel`](ue_ue.MovieSceneByteChannel.md)

#### Defined in

[ue/ue.d.ts:51632](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L51632)

___

### EvalOptions

• **EvalOptions**: [`MovieSceneSectionEvalOptions`](ue_ue.MovieSceneSectionEvalOptions.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[EvalOptions](ue_ue.MovieSceneSection.md#evaloptions)

#### Defined in

[ue/ue.d.ts:11780](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11780)

___

### OverlapPriority

• **OverlapPriority**: `number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[OverlapPriority](ue_ue.MovieSceneSection.md#overlappriority)

#### Defined in

[ue/ue.d.ts:11787](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11787)

___

### PostRollFrames

• **PostRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[PostRollFrames](ue_ue.MovieSceneSection.md#postrollframes)

#### Defined in

[ue/ue.d.ts:11785](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11785)

___

### PostRollTime

• **PostRollTime**: `number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[PostRollTime](ue_ue.MovieSceneSection.md#postrolltime)

#### Defined in

[ue/ue.d.ts:11793](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11793)

___

### PreRollFrames

• **PreRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[PreRollFrames](ue_ue.MovieSceneSection.md#prerollframes)

#### Defined in

[ue/ue.d.ts:11784](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11784)

___

### PreRollTime

• **PreRollTime**: `number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[PreRollTime](ue_ue.MovieSceneSection.md#prerolltime)

#### Defined in

[ue/ue.d.ts:11792](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11792)

___

### RowIndex

• **RowIndex**: `number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[RowIndex](ue_ue.MovieSceneSection.md#rowindex)

#### Defined in

[ue/ue.d.ts:11786](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11786)

___

### SectionRange

• **SectionRange**: [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[SectionRange](ue_ue.MovieSceneSection.md#sectionrange)

#### Defined in

[ue/ue.d.ts:11782](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11782)

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[Signature](ue_ue.MovieSceneSection.md#signature)

#### Defined in

[ue/ue.d.ts:11034](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11034)

___

### StartTime

• **StartTime**: `number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[StartTime](ue_ue.MovieSceneSection.md#starttime)

#### Defined in

[ue/ue.d.ts:11790](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11790)

___

### TimecodeSource

• **TimecodeSource**: [`MovieSceneTimecodeSource`](ue_ue.MovieSceneTimecodeSource.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[TimecodeSource](ue_ue.MovieSceneSection.md#timecodesource)

#### Defined in

[ue/ue.d.ts:11783](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11783)

___

### \_\_tid\_MovieSceneEnumSection\_\_

• **\_\_tid\_MovieSceneEnumSection\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:51637](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L51637)

___

### \_\_tid\_MovieSceneSection\_\_

• **\_\_tid\_MovieSceneSection\_\_**: `boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[__tid_MovieSceneSection__](ue_ue.MovieSceneSection.md#__tid_moviescenesection__)

#### Defined in

[ue/ue.d.ts:11817](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11817)

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneSection.md#__tid_moviescenesignedobject__)

#### Defined in

[ue/ue.d.ts:11039](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11039)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[__tid_Object__](ue_ue.MovieSceneSection.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[bIsActive](ue_ue.MovieSceneSection.md#bisactive)

#### Defined in

[ue/ue.d.ts:11788](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11788)

___

### bIsInfinite

• **bIsInfinite**: `boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[bIsInfinite](ue_ue.MovieSceneSection.md#bisinfinite)

#### Defined in

[ue/ue.d.ts:11794](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11794)

___

### bIsLocked

• **bIsLocked**: `boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[bIsLocked](ue_ue.MovieSceneSection.md#bislocked)

#### Defined in

[ue/ue.d.ts:11789](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11789)

___

### bSupportsInfiniteRange

• **bSupportsInfiniteRange**: `boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[bSupportsInfiniteRange](ue_ue.MovieSceneSection.md#bsupportsinfiniterange)

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

[MovieSceneSection](ue_ue.MovieSceneSection.md).[CreateDefaultSubobject](ue_ue.MovieSceneSection.md#createdefaultsubobject)

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

[MovieSceneSection](ue_ue.MovieSceneSection.md).[ExecuteUbergraph](ue_ue.MovieSceneSection.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetBlendType

▸ **GetBlendType**(): [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Returns

[`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetBlendType](ue_ue.MovieSceneSection.md#getblendtype)

#### Defined in

[ue/ue.d.ts:11797](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11797)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetClass](ue_ue.MovieSceneSection.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetCompletionMode

▸ **GetCompletionMode**(): [`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Returns

[`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetCompletionMode](ue_ue.MovieSceneSection.md#getcompletionmode)

#### Defined in

[ue/ue.d.ts:11798](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11798)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetName](ue_ue.MovieSceneSection.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetOuter](ue_ue.MovieSceneSection.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetOverlapPriority

▸ **GetOverlapPriority**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetOverlapPriority](ue_ue.MovieSceneSection.md#getoverlappriority)

#### Defined in

[ue/ue.d.ts:11799](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11799)

___

### GetPostRollFrames

▸ **GetPostRollFrames**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetPostRollFrames](ue_ue.MovieSceneSection.md#getpostrollframes)

#### Defined in

[ue/ue.d.ts:11800](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11800)

___

### GetPreRollFrames

▸ **GetPreRollFrames**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetPreRollFrames](ue_ue.MovieSceneSection.md#getprerollframes)

#### Defined in

[ue/ue.d.ts:11801](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11801)

___

### GetRowIndex

▸ **GetRowIndex**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetRowIndex](ue_ue.MovieSceneSection.md#getrowindex)

#### Defined in

[ue/ue.d.ts:11802](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11802)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[GetWorld](ue_ue.MovieSceneSection.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[IsActive](ue_ue.MovieSceneSection.md#isactive)

#### Defined in

[ue/ue.d.ts:11803](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11803)

___

### IsLocked

▸ **IsLocked**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneSection](ue_ue.MovieSceneSection.md).[IsLocked](ue_ue.MovieSceneSection.md#islocked)

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

[MovieSceneSection](ue_ue.MovieSceneSection.md).[SetBlendType](ue_ue.MovieSceneSection.md#setblendtype)

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

[MovieSceneSection](ue_ue.MovieSceneSection.md).[SetCompletionMode](ue_ue.MovieSceneSection.md#setcompletionmode)

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

[MovieSceneSection](ue_ue.MovieSceneSection.md).[SetIsActive](ue_ue.MovieSceneSection.md#setisactive)

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

[MovieSceneSection](ue_ue.MovieSceneSection.md).[SetIsLocked](ue_ue.MovieSceneSection.md#setislocked)

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

[MovieSceneSection](ue_ue.MovieSceneSection.md).[SetOverlapPriority](ue_ue.MovieSceneSection.md#setoverlappriority)

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

[MovieSceneSection](ue_ue.MovieSceneSection.md).[SetPostRollFrames](ue_ue.MovieSceneSection.md#setpostrollframes)

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

[MovieSceneSection](ue_ue.MovieSceneSection.md).[SetPreRollFrames](ue_ue.MovieSceneSection.md#setprerollframes)

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

[MovieSceneSection](ue_ue.MovieSceneSection.md).[SetRowIndex](ue_ue.MovieSceneSection.md#setrowindex)

#### Defined in

[ue/ue.d.ts:11812](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11812)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneEnumSection`](ue_ue.MovieSceneEnumSection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneEnumSection`](ue_ue.MovieSceneEnumSection.md)

#### Overrides

[MovieSceneSection](ue_ue.MovieSceneSection.md).[Find](ue_ue.MovieSceneSection.md#find)

#### Defined in

[ue/ue.d.ts:51634](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L51634)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneEnumSection`](ue_ue.MovieSceneEnumSection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneEnumSection`](ue_ue.MovieSceneEnumSection.md)

#### Overrides

[MovieSceneSection](ue_ue.MovieSceneSection.md).[Load](ue_ue.MovieSceneSection.md#load)

#### Defined in

[ue/ue.d.ts:51635](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L51635)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneSection](ue_ue.MovieSceneSection.md).[StaticClass](ue_ue.MovieSceneSection.md#staticclass)

#### Defined in

[ue/ue.d.ts:51633](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L51633)
