[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneImageCaptureProtocolBase

# Class: MovieSceneImageCaptureProtocolBase

[ue/ue](../modules/ue_ue.md).MovieSceneImageCaptureProtocolBase

## Hierarchy

- [`MovieSceneCaptureProtocolBase`](ue_ue.MovieSceneCaptureProtocolBase.md)

  ↳ **`MovieSceneImageCaptureProtocolBase`**

  ↳↳ [`CompositionGraphCaptureProtocol`](ue_ue.CompositionGraphCaptureProtocol.md)

  ↳↳ [`FrameGrabberProtocol`](ue_ue.FrameGrabberProtocol.md)

  ↳↳ [`UserDefinedCaptureProtocol`](ue_ue.UserDefinedCaptureProtocol.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneImageCaptureProtocolBase.md#constructor)

### Properties

- [State](ue_ue.MovieSceneImageCaptureProtocolBase.md#state)
- [\_\_tid\_MovieSceneCaptureProtocolBase\_\_](ue_ue.MovieSceneImageCaptureProtocolBase.md#__tid_moviescenecaptureprotocolbase__)
- [\_\_tid\_MovieSceneImageCaptureProtocolBase\_\_](ue_ue.MovieSceneImageCaptureProtocolBase.md#__tid_moviesceneimagecaptureprotocolbase__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneImageCaptureProtocolBase.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneImageCaptureProtocolBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneImageCaptureProtocolBase.md#executeubergraph)
- [GetClass](ue_ue.MovieSceneImageCaptureProtocolBase.md#getclass)
- [GetName](ue_ue.MovieSceneImageCaptureProtocolBase.md#getname)
- [GetOuter](ue_ue.MovieSceneImageCaptureProtocolBase.md#getouter)
- [GetState](ue_ue.MovieSceneImageCaptureProtocolBase.md#getstate)
- [GetWorld](ue_ue.MovieSceneImageCaptureProtocolBase.md#getworld)
- [IsCapturing](ue_ue.MovieSceneImageCaptureProtocolBase.md#iscapturing)
- [Find](ue_ue.MovieSceneImageCaptureProtocolBase.md#find)
- [Load](ue_ue.MovieSceneImageCaptureProtocolBase.md#load)
- [StaticClass](ue_ue.MovieSceneImageCaptureProtocolBase.md#staticclass)

## Constructors

### constructor

• **new MovieSceneImageCaptureProtocolBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[constructor](ue_ue.MovieSceneCaptureProtocolBase.md#constructor)

#### Defined in

[ue/ue.d.ts:22549](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22549)

## Properties

### State

• **State**: [`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Inherited from

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[State](ue_ue.MovieSceneCaptureProtocolBase.md#state)

#### Defined in

[ue/ue.d.ts:22538](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22538)

___

### \_\_tid\_MovieSceneCaptureProtocolBase\_\_

• **\_\_tid\_MovieSceneCaptureProtocolBase\_\_**: `boolean`

#### Inherited from

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[__tid_MovieSceneCaptureProtocolBase__](ue_ue.MovieSceneCaptureProtocolBase.md#__tid_moviescenecaptureprotocolbase__)

#### Defined in

[ue/ue.d.ts:22545](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22545)

___

### \_\_tid\_MovieSceneImageCaptureProtocolBase\_\_

• **\_\_tid\_MovieSceneImageCaptureProtocolBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:22554](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22554)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[__tid_Object__](ue_ue.MovieSceneCaptureProtocolBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[CreateDefaultSubobject](ue_ue.MovieSceneCaptureProtocolBase.md#createdefaultsubobject)

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

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[ExecuteUbergraph](ue_ue.MovieSceneCaptureProtocolBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[GetClass](ue_ue.MovieSceneCaptureProtocolBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[GetName](ue_ue.MovieSceneCaptureProtocolBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[GetOuter](ue_ue.MovieSceneCaptureProtocolBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetState

▸ **GetState**(): [`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Returns

[`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Inherited from

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[GetState](ue_ue.MovieSceneCaptureProtocolBase.md#getstate)

#### Defined in

[ue/ue.d.ts:22539](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22539)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[GetWorld](ue_ue.MovieSceneCaptureProtocolBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsCapturing

▸ **IsCapturing**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[IsCapturing](ue_ue.MovieSceneCaptureProtocolBase.md#iscapturing)

#### Defined in

[ue/ue.d.ts:22540](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22540)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneImageCaptureProtocolBase`](ue_ue.MovieSceneImageCaptureProtocolBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneImageCaptureProtocolBase`](ue_ue.MovieSceneImageCaptureProtocolBase.md)

#### Overrides

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[Find](ue_ue.MovieSceneCaptureProtocolBase.md#find)

#### Defined in

[ue/ue.d.ts:22551](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22551)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneImageCaptureProtocolBase`](ue_ue.MovieSceneImageCaptureProtocolBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneImageCaptureProtocolBase`](ue_ue.MovieSceneImageCaptureProtocolBase.md)

#### Overrides

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[Load](ue_ue.MovieSceneCaptureProtocolBase.md#load)

#### Defined in

[ue/ue.d.ts:22552](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22552)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[StaticClass](ue_ue.MovieSceneCaptureProtocolBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:22550](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22550)
