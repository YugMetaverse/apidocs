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

#### Defined in

[ue/ue.d.ts:52322](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L52322)

## Properties

### BlendType

• **BlendType**: [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[BlendType](ue_ue.MovieSceneBoolSection.md#blendtype)

#### Defined in

[ue/ue.d.ts:11796](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11796)

___

### BoolCurve

• **BoolCurve**: [`MovieSceneBoolChannel`](ue_ue.MovieSceneBoolChannel.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[BoolCurve](ue_ue.MovieSceneBoolSection.md#boolcurve)

#### Defined in

[ue/ue.d.ts:51290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L51290)

___

### DefaultValue

• **DefaultValue**: `boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[DefaultValue](ue_ue.MovieSceneBoolSection.md#defaultvalue)

#### Defined in

[ue/ue.d.ts:51289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L51289)

___

### Easing

• **Easing**: [`MovieSceneEasingSettings`](ue_ue.MovieSceneEasingSettings.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[Easing](ue_ue.MovieSceneBoolSection.md#easing)

#### Defined in

[ue/ue.d.ts:11781](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11781)

___

### EndTime

• **EndTime**: `number`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[EndTime](ue_ue.MovieSceneBoolSection.md#endtime)

#### Defined in

[ue/ue.d.ts:11791](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11791)

___

### EvalOptions

• **EvalOptions**: [`MovieSceneSectionEvalOptions`](ue_ue.MovieSceneSectionEvalOptions.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[EvalOptions](ue_ue.MovieSceneBoolSection.md#evaloptions)

#### Defined in

[ue/ue.d.ts:11780](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11780)

___

### OverlapPriority

• **OverlapPriority**: `number`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[OverlapPriority](ue_ue.MovieSceneBoolSection.md#overlappriority)

#### Defined in

[ue/ue.d.ts:11787](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11787)

___

### PostRollFrames

• **PostRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[PostRollFrames](ue_ue.MovieSceneBoolSection.md#postrollframes)

#### Defined in

[ue/ue.d.ts:11785](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11785)

___

### PostRollTime

• **PostRollTime**: `number`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[PostRollTime](ue_ue.MovieSceneBoolSection.md#postrolltime)

#### Defined in

[ue/ue.d.ts:11793](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11793)

___

### PreRollFrames

• **PreRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[PreRollFrames](ue_ue.MovieSceneBoolSection.md#prerollframes)

#### Defined in

[ue/ue.d.ts:11784](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11784)

___

### PreRollTime

• **PreRollTime**: `number`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[PreRollTime](ue_ue.MovieSceneBoolSection.md#prerolltime)

#### Defined in

[ue/ue.d.ts:11792](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11792)

___

### RowIndex

• **RowIndex**: `number`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[RowIndex](ue_ue.MovieSceneBoolSection.md#rowindex)

#### Defined in

[ue/ue.d.ts:11786](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11786)

___

### SectionRange

• **SectionRange**: [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[SectionRange](ue_ue.MovieSceneBoolSection.md#sectionrange)

#### Defined in

[ue/ue.d.ts:11782](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11782)

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[Signature](ue_ue.MovieSceneBoolSection.md#signature)

#### Defined in

[ue/ue.d.ts:11034](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11034)

___

### StartTime

• **StartTime**: `number`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[StartTime](ue_ue.MovieSceneBoolSection.md#starttime)

#### Defined in

[ue/ue.d.ts:11790](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11790)

___

### TimecodeSource

• **TimecodeSource**: [`MovieSceneTimecodeSource`](ue_ue.MovieSceneTimecodeSource.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[TimecodeSource](ue_ue.MovieSceneBoolSection.md#timecodesource)

#### Defined in

[ue/ue.d.ts:11783](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11783)

___

### \_\_tid\_MovieSceneBoolSection\_\_

• **\_\_tid\_MovieSceneBoolSection\_\_**: `boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[__tid_MovieSceneBoolSection__](ue_ue.MovieSceneBoolSection.md#__tid_moviesceneboolsection__)

#### Defined in

[ue/ue.d.ts:51296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L51296)

___

### \_\_tid\_MovieSceneSection\_\_

• **\_\_tid\_MovieSceneSection\_\_**: `boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[__tid_MovieSceneSection__](ue_ue.MovieSceneBoolSection.md#__tid_moviescenesection__)

#### Defined in

[ue/ue.d.ts:11817](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11817)

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneBoolSection.md#__tid_moviescenesignedobject__)

#### Defined in

[ue/ue.d.ts:11039](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11039)

___

### \_\_tid\_MovieSceneSpawnSection\_\_

• **\_\_tid\_MovieSceneSpawnSection\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:52327](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L52327)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[__tid_Object__](ue_ue.MovieSceneBoolSection.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[bIsActive](ue_ue.MovieSceneBoolSection.md#bisactive)

#### Defined in

[ue/ue.d.ts:11788](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11788)

___

### bIsExternallyInverted

• **bIsExternallyInverted**: `boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[bIsExternallyInverted](ue_ue.MovieSceneBoolSection.md#bisexternallyinverted)

#### Defined in

[ue/ue.d.ts:51291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L51291)

___

### bIsInfinite

• **bIsInfinite**: `boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[bIsInfinite](ue_ue.MovieSceneBoolSection.md#bisinfinite)

#### Defined in

[ue/ue.d.ts:11794](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11794)

___

### bIsLocked

• **bIsLocked**: `boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[bIsLocked](ue_ue.MovieSceneBoolSection.md#bislocked)

#### Defined in

[ue/ue.d.ts:11789](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11789)

___

### bSupportsInfiniteRange

• **bSupportsInfiniteRange**: `boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[bSupportsInfiniteRange](ue_ue.MovieSceneBoolSection.md#bsupportsinfiniterange)

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

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[CreateDefaultSubobject](ue_ue.MovieSceneBoolSection.md#createdefaultsubobject)

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

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[ExecuteUbergraph](ue_ue.MovieSceneBoolSection.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetBlendType

▸ **GetBlendType**(): [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Returns

[`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[GetBlendType](ue_ue.MovieSceneBoolSection.md#getblendtype)

#### Defined in

[ue/ue.d.ts:11797](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11797)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[GetClass](ue_ue.MovieSceneBoolSection.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetCompletionMode

▸ **GetCompletionMode**(): [`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Returns

[`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[GetCompletionMode](ue_ue.MovieSceneBoolSection.md#getcompletionmode)

#### Defined in

[ue/ue.d.ts:11798](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11798)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[GetName](ue_ue.MovieSceneBoolSection.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[GetOuter](ue_ue.MovieSceneBoolSection.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetOverlapPriority

▸ **GetOverlapPriority**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[GetOverlapPriority](ue_ue.MovieSceneBoolSection.md#getoverlappriority)

#### Defined in

[ue/ue.d.ts:11799](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11799)

___

### GetPostRollFrames

▸ **GetPostRollFrames**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[GetPostRollFrames](ue_ue.MovieSceneBoolSection.md#getpostrollframes)

#### Defined in

[ue/ue.d.ts:11800](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11800)

___

### GetPreRollFrames

▸ **GetPreRollFrames**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[GetPreRollFrames](ue_ue.MovieSceneBoolSection.md#getprerollframes)

#### Defined in

[ue/ue.d.ts:11801](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11801)

___

### GetRowIndex

▸ **GetRowIndex**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[GetRowIndex](ue_ue.MovieSceneBoolSection.md#getrowindex)

#### Defined in

[ue/ue.d.ts:11802](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11802)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[GetWorld](ue_ue.MovieSceneBoolSection.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[IsActive](ue_ue.MovieSceneBoolSection.md#isactive)

#### Defined in

[ue/ue.d.ts:11803](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11803)

___

### IsLocked

▸ **IsLocked**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[IsLocked](ue_ue.MovieSceneBoolSection.md#islocked)

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

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[SetBlendType](ue_ue.MovieSceneBoolSection.md#setblendtype)

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

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[SetCompletionMode](ue_ue.MovieSceneBoolSection.md#setcompletionmode)

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

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[SetIsActive](ue_ue.MovieSceneBoolSection.md#setisactive)

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

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[SetIsLocked](ue_ue.MovieSceneBoolSection.md#setislocked)

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

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[SetOverlapPriority](ue_ue.MovieSceneBoolSection.md#setoverlappriority)

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

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[SetPostRollFrames](ue_ue.MovieSceneBoolSection.md#setpostrollframes)

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

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[SetPreRollFrames](ue_ue.MovieSceneBoolSection.md#setprerollframes)

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

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[SetRowIndex](ue_ue.MovieSceneBoolSection.md#setrowindex)

#### Defined in

[ue/ue.d.ts:11812](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11812)

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

#### Defined in

[ue/ue.d.ts:52324](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L52324)

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

#### Defined in

[ue/ue.d.ts:52325](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L52325)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneBoolSection](ue_ue.MovieSceneBoolSection.md).[StaticClass](ue_ue.MovieSceneBoolSection.md#staticclass)

#### Defined in

[ue/ue.d.ts:52323](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L52323)
