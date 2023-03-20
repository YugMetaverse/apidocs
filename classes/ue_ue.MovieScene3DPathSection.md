[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieScene3DPathSection

# Class: MovieScene3DPathSection

[ue/ue](../modules/ue_ue.md).MovieScene3DPathSection

## Hierarchy

- [`MovieScene3DConstraintSection`](ue_ue.MovieScene3DConstraintSection.md)

  ↳ **`MovieScene3DPathSection`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieScene3DPathSection.md#constructor)

### Properties

- [BlendType](ue_ue.MovieScene3DPathSection.md#blendtype)
- [ConstraintBindingID](ue_ue.MovieScene3DPathSection.md#constraintbindingid)
- [ConstraintId](ue_ue.MovieScene3DPathSection.md#constraintid)
- [Easing](ue_ue.MovieScene3DPathSection.md#easing)
- [EndTime](ue_ue.MovieScene3DPathSection.md#endtime)
- [EvalOptions](ue_ue.MovieScene3DPathSection.md#evaloptions)
- [FrontAxisEnum](ue_ue.MovieScene3DPathSection.md#frontaxisenum)
- [OverlapPriority](ue_ue.MovieScene3DPathSection.md#overlappriority)
- [PostRollFrames](ue_ue.MovieScene3DPathSection.md#postrollframes)
- [PostRollTime](ue_ue.MovieScene3DPathSection.md#postrolltime)
- [PreRollFrames](ue_ue.MovieScene3DPathSection.md#prerollframes)
- [PreRollTime](ue_ue.MovieScene3DPathSection.md#prerolltime)
- [RowIndex](ue_ue.MovieScene3DPathSection.md#rowindex)
- [SectionRange](ue_ue.MovieScene3DPathSection.md#sectionrange)
- [Signature](ue_ue.MovieScene3DPathSection.md#signature)
- [StartTime](ue_ue.MovieScene3DPathSection.md#starttime)
- [TimecodeSource](ue_ue.MovieScene3DPathSection.md#timecodesource)
- [TimingCurve](ue_ue.MovieScene3DPathSection.md#timingcurve)
- [UpAxisEnum](ue_ue.MovieScene3DPathSection.md#upaxisenum)
- [\_\_tid\_MovieScene3DConstraintSection\_\_](ue_ue.MovieScene3DPathSection.md#__tid_moviescene3dconstraintsection__)
- [\_\_tid\_MovieScene3DPathSection\_\_](ue_ue.MovieScene3DPathSection.md#__tid_moviescene3dpathsection__)
- [\_\_tid\_MovieSceneSection\_\_](ue_ue.MovieScene3DPathSection.md#__tid_moviescenesection__)
- [\_\_tid\_MovieSceneSignedObject\_\_](ue_ue.MovieScene3DPathSection.md#__tid_moviescenesignedobject__)
- [\_\_tid\_Object\_\_](ue_ue.MovieScene3DPathSection.md#__tid_object__)
- [bFollow](ue_ue.MovieScene3DPathSection.md#bfollow)
- [bForceUpright](ue_ue.MovieScene3DPathSection.md#bforceupright)
- [bIsActive](ue_ue.MovieScene3DPathSection.md#bisactive)
- [bIsInfinite](ue_ue.MovieScene3DPathSection.md#bisinfinite)
- [bIsLocked](ue_ue.MovieScene3DPathSection.md#bislocked)
- [bReverse](ue_ue.MovieScene3DPathSection.md#breverse)
- [bSupportsInfiniteRange](ue_ue.MovieScene3DPathSection.md#bsupportsinfiniterange)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieScene3DPathSection.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieScene3DPathSection.md#executeubergraph)
- [GetBlendType](ue_ue.MovieScene3DPathSection.md#getblendtype)
- [GetClass](ue_ue.MovieScene3DPathSection.md#getclass)
- [GetCompletionMode](ue_ue.MovieScene3DPathSection.md#getcompletionmode)
- [GetConstraintBindingID](ue_ue.MovieScene3DPathSection.md#getconstraintbindingid)
- [GetName](ue_ue.MovieScene3DPathSection.md#getname)
- [GetOuter](ue_ue.MovieScene3DPathSection.md#getouter)
- [GetOverlapPriority](ue_ue.MovieScene3DPathSection.md#getoverlappriority)
- [GetPostRollFrames](ue_ue.MovieScene3DPathSection.md#getpostrollframes)
- [GetPreRollFrames](ue_ue.MovieScene3DPathSection.md#getprerollframes)
- [GetRowIndex](ue_ue.MovieScene3DPathSection.md#getrowindex)
- [GetWorld](ue_ue.MovieScene3DPathSection.md#getworld)
- [IsActive](ue_ue.MovieScene3DPathSection.md#isactive)
- [IsLocked](ue_ue.MovieScene3DPathSection.md#islocked)
- [SetBlendType](ue_ue.MovieScene3DPathSection.md#setblendtype)
- [SetCompletionMode](ue_ue.MovieScene3DPathSection.md#setcompletionmode)
- [SetConstraintBindingID](ue_ue.MovieScene3DPathSection.md#setconstraintbindingid)
- [SetIsActive](ue_ue.MovieScene3DPathSection.md#setisactive)
- [SetIsLocked](ue_ue.MovieScene3DPathSection.md#setislocked)
- [SetOverlapPriority](ue_ue.MovieScene3DPathSection.md#setoverlappriority)
- [SetPostRollFrames](ue_ue.MovieScene3DPathSection.md#setpostrollframes)
- [SetPreRollFrames](ue_ue.MovieScene3DPathSection.md#setprerollframes)
- [SetRowIndex](ue_ue.MovieScene3DPathSection.md#setrowindex)
- [Find](ue_ue.MovieScene3DPathSection.md#find)
- [Load](ue_ue.MovieScene3DPathSection.md#load)
- [StaticClass](ue_ue.MovieScene3DPathSection.md#staticclass)

## Constructors

### constructor

• **new MovieScene3DPathSection**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[constructor](ue_ue.MovieScene3DConstraintSection.md#constructor)

## Properties

### BlendType

• **BlendType**: [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[BlendType](ue_ue.MovieScene3DConstraintSection.md#blendtype)

___

### ConstraintBindingID

• **ConstraintBindingID**: [`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md)

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[ConstraintBindingID](ue_ue.MovieScene3DConstraintSection.md#constraintbindingid)

___

### ConstraintId

• **ConstraintId**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[ConstraintId](ue_ue.MovieScene3DConstraintSection.md#constraintid)

___

### Easing

• **Easing**: [`MovieSceneEasingSettings`](ue_ue.MovieSceneEasingSettings.md)

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[Easing](ue_ue.MovieScene3DConstraintSection.md#easing)

___

### EndTime

• **EndTime**: `number`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[EndTime](ue_ue.MovieScene3DConstraintSection.md#endtime)

___

### EvalOptions

• **EvalOptions**: [`MovieSceneSectionEvalOptions`](ue_ue.MovieSceneSectionEvalOptions.md)

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[EvalOptions](ue_ue.MovieScene3DConstraintSection.md#evaloptions)

___

### FrontAxisEnum

• **FrontAxisEnum**: [`MovieScene3DPathSection_Axis`](../enums/ue_ue.MovieScene3DPathSection_Axis.md)

___

### OverlapPriority

• **OverlapPriority**: `number`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[OverlapPriority](ue_ue.MovieScene3DConstraintSection.md#overlappriority)

___

### PostRollFrames

• **PostRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[PostRollFrames](ue_ue.MovieScene3DConstraintSection.md#postrollframes)

___

### PostRollTime

• **PostRollTime**: `number`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[PostRollTime](ue_ue.MovieScene3DConstraintSection.md#postrolltime)

___

### PreRollFrames

• **PreRollFrames**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[PreRollFrames](ue_ue.MovieScene3DConstraintSection.md#prerollframes)

___

### PreRollTime

• **PreRollTime**: `number`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[PreRollTime](ue_ue.MovieScene3DConstraintSection.md#prerolltime)

___

### RowIndex

• **RowIndex**: `number`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[RowIndex](ue_ue.MovieScene3DConstraintSection.md#rowindex)

___

### SectionRange

• **SectionRange**: [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[SectionRange](ue_ue.MovieScene3DConstraintSection.md#sectionrange)

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[Signature](ue_ue.MovieScene3DConstraintSection.md#signature)

___

### StartTime

• **StartTime**: `number`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[StartTime](ue_ue.MovieScene3DConstraintSection.md#starttime)

___

### TimecodeSource

• **TimecodeSource**: [`MovieSceneTimecodeSource`](ue_ue.MovieSceneTimecodeSource.md)

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[TimecodeSource](ue_ue.MovieScene3DConstraintSection.md#timecodesource)

___

### TimingCurve

• **TimingCurve**: [`MovieSceneFloatChannel`](ue_ue.MovieSceneFloatChannel.md)

___

### UpAxisEnum

• **UpAxisEnum**: [`MovieScene3DPathSection_Axis`](../enums/ue_ue.MovieScene3DPathSection_Axis.md)

___

### \_\_tid\_MovieScene3DConstraintSection\_\_

• **\_\_tid\_MovieScene3DConstraintSection\_\_**: `boolean`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[__tid_MovieScene3DConstraintSection__](ue_ue.MovieScene3DConstraintSection.md#__tid_moviescene3dconstraintsection__)

___

### \_\_tid\_MovieScene3DPathSection\_\_

• **\_\_tid\_MovieScene3DPathSection\_\_**: `boolean`

___

### \_\_tid\_MovieSceneSection\_\_

• **\_\_tid\_MovieSceneSection\_\_**: `boolean`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[__tid_MovieSceneSection__](ue_ue.MovieScene3DConstraintSection.md#__tid_moviescenesection__)

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieScene3DConstraintSection.md#__tid_moviescenesignedobject__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[__tid_Object__](ue_ue.MovieScene3DConstraintSection.md#__tid_object__)

___

### bFollow

• **bFollow**: `boolean`

___

### bForceUpright

• **bForceUpright**: `boolean`

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[bIsActive](ue_ue.MovieScene3DConstraintSection.md#bisactive)

___

### bIsInfinite

• **bIsInfinite**: `boolean`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[bIsInfinite](ue_ue.MovieScene3DConstraintSection.md#bisinfinite)

___

### bIsLocked

• **bIsLocked**: `boolean`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[bIsLocked](ue_ue.MovieScene3DConstraintSection.md#bislocked)

___

### bReverse

• **bReverse**: `boolean`

___

### bSupportsInfiniteRange

• **bSupportsInfiniteRange**: `boolean`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[bSupportsInfiniteRange](ue_ue.MovieScene3DConstraintSection.md#bsupportsinfiniterange)

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

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[CreateDefaultSubobject](ue_ue.MovieScene3DConstraintSection.md#createdefaultsubobject)

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

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[ExecuteUbergraph](ue_ue.MovieScene3DConstraintSection.md#executeubergraph)

___

### GetBlendType

▸ **GetBlendType**(): [`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Returns

[`OptionalMovieSceneBlendType`](ue_ue.OptionalMovieSceneBlendType.md)

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[GetBlendType](ue_ue.MovieScene3DConstraintSection.md#getblendtype)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[GetClass](ue_ue.MovieScene3DConstraintSection.md#getclass)

___

### GetCompletionMode

▸ **GetCompletionMode**(): [`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Returns

[`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[GetCompletionMode](ue_ue.MovieScene3DConstraintSection.md#getcompletionmode)

___

### GetConstraintBindingID

▸ **GetConstraintBindingID**(): [`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md)

#### Returns

[`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md)

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[GetConstraintBindingID](ue_ue.MovieScene3DConstraintSection.md#getconstraintbindingid)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[GetName](ue_ue.MovieScene3DConstraintSection.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[GetOuter](ue_ue.MovieScene3DConstraintSection.md#getouter)

___

### GetOverlapPriority

▸ **GetOverlapPriority**(): `number`

#### Returns

`number`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[GetOverlapPriority](ue_ue.MovieScene3DConstraintSection.md#getoverlappriority)

___

### GetPostRollFrames

▸ **GetPostRollFrames**(): `number`

#### Returns

`number`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[GetPostRollFrames](ue_ue.MovieScene3DConstraintSection.md#getpostrollframes)

___

### GetPreRollFrames

▸ **GetPreRollFrames**(): `number`

#### Returns

`number`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[GetPreRollFrames](ue_ue.MovieScene3DConstraintSection.md#getprerollframes)

___

### GetRowIndex

▸ **GetRowIndex**(): `number`

#### Returns

`number`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[GetRowIndex](ue_ue.MovieScene3DConstraintSection.md#getrowindex)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[GetWorld](ue_ue.MovieScene3DConstraintSection.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[IsActive](ue_ue.MovieScene3DConstraintSection.md#isactive)

___

### IsLocked

▸ **IsLocked**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[IsLocked](ue_ue.MovieScene3DConstraintSection.md#islocked)

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

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[SetBlendType](ue_ue.MovieScene3DConstraintSection.md#setblendtype)

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

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[SetCompletionMode](ue_ue.MovieScene3DConstraintSection.md#setcompletionmode)

___

### SetConstraintBindingID

▸ **SetConstraintBindingID**(`InConstraintBindingID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InConstraintBindingID` | [`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md) |

#### Returns

`void`

#### Inherited from

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[SetConstraintBindingID](ue_ue.MovieScene3DConstraintSection.md#setconstraintbindingid)

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

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[SetIsActive](ue_ue.MovieScene3DConstraintSection.md#setisactive)

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

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[SetIsLocked](ue_ue.MovieScene3DConstraintSection.md#setislocked)

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

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[SetOverlapPriority](ue_ue.MovieScene3DConstraintSection.md#setoverlappriority)

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

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[SetPostRollFrames](ue_ue.MovieScene3DConstraintSection.md#setpostrollframes)

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

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[SetPreRollFrames](ue_ue.MovieScene3DConstraintSection.md#setprerollframes)

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

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[SetRowIndex](ue_ue.MovieScene3DConstraintSection.md#setrowindex)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieScene3DPathSection`](ue_ue.MovieScene3DPathSection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieScene3DPathSection`](ue_ue.MovieScene3DPathSection.md)

#### Overrides

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[Find](ue_ue.MovieScene3DConstraintSection.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieScene3DPathSection`](ue_ue.MovieScene3DPathSection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieScene3DPathSection`](ue_ue.MovieScene3DPathSection.md)

#### Overrides

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[Load](ue_ue.MovieScene3DConstraintSection.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieScene3DConstraintSection](ue_ue.MovieScene3DConstraintSection.md).[StaticClass](ue_ue.MovieScene3DConstraintSection.md#staticclass)
