[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FrameGrabberProtocol

# Class: FrameGrabberProtocol

[ue/ue](../modules/ue_ue.md).FrameGrabberProtocol

## Hierarchy

- [`MovieSceneImageCaptureProtocolBase`](ue_ue.MovieSceneImageCaptureProtocolBase.md)

  ↳ **`FrameGrabberProtocol`**

  ↳↳ [`ImageSequenceProtocol`](ue_ue.ImageSequenceProtocol.md)

  ↳↳ [`VideoCaptureProtocol`](ue_ue.VideoCaptureProtocol.md)

## Table of contents

### Constructors

- [constructor](ue_ue.FrameGrabberProtocol.md#constructor)

### Properties

- [State](ue_ue.FrameGrabberProtocol.md#state)
- [\_\_tid\_FrameGrabberProtocol\_\_](ue_ue.FrameGrabberProtocol.md#__tid_framegrabberprotocol__)
- [\_\_tid\_MovieSceneCaptureProtocolBase\_\_](ue_ue.FrameGrabberProtocol.md#__tid_moviescenecaptureprotocolbase__)
- [\_\_tid\_MovieSceneImageCaptureProtocolBase\_\_](ue_ue.FrameGrabberProtocol.md#__tid_moviesceneimagecaptureprotocolbase__)
- [\_\_tid\_Object\_\_](ue_ue.FrameGrabberProtocol.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.FrameGrabberProtocol.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.FrameGrabberProtocol.md#executeubergraph)
- [GetClass](ue_ue.FrameGrabberProtocol.md#getclass)
- [GetName](ue_ue.FrameGrabberProtocol.md#getname)
- [GetOuter](ue_ue.FrameGrabberProtocol.md#getouter)
- [GetState](ue_ue.FrameGrabberProtocol.md#getstate)
- [GetWorld](ue_ue.FrameGrabberProtocol.md#getworld)
- [IsCapturing](ue_ue.FrameGrabberProtocol.md#iscapturing)
- [Find](ue_ue.FrameGrabberProtocol.md#find)
- [Load](ue_ue.FrameGrabberProtocol.md#load)
- [StaticClass](ue_ue.FrameGrabberProtocol.md#staticclass)

## Constructors

### constructor

• **new FrameGrabberProtocol**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[constructor](ue_ue.MovieSceneImageCaptureProtocolBase.md#constructor)

#### Defined in

[ue/ue.d.ts:28502](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28502)

## Properties

### State

• **State**: [`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[State](ue_ue.MovieSceneImageCaptureProtocolBase.md#state)

#### Defined in

[ue/ue.d.ts:22538](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22538)

___

### \_\_tid\_FrameGrabberProtocol\_\_

• **\_\_tid\_FrameGrabberProtocol\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:28507](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28507)

___

### \_\_tid\_MovieSceneCaptureProtocolBase\_\_

• **\_\_tid\_MovieSceneCaptureProtocolBase\_\_**: `boolean`

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[__tid_MovieSceneCaptureProtocolBase__](ue_ue.MovieSceneImageCaptureProtocolBase.md#__tid_moviescenecaptureprotocolbase__)

#### Defined in

[ue/ue.d.ts:22545](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22545)

___

### \_\_tid\_MovieSceneImageCaptureProtocolBase\_\_

• **\_\_tid\_MovieSceneImageCaptureProtocolBase\_\_**: `boolean`

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[__tid_MovieSceneImageCaptureProtocolBase__](ue_ue.MovieSceneImageCaptureProtocolBase.md#__tid_moviesceneimagecaptureprotocolbase__)

#### Defined in

[ue/ue.d.ts:22554](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22554)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[__tid_Object__](ue_ue.MovieSceneImageCaptureProtocolBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[CreateDefaultSubobject](ue_ue.MovieSceneImageCaptureProtocolBase.md#createdefaultsubobject)

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

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[ExecuteUbergraph](ue_ue.MovieSceneImageCaptureProtocolBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[GetClass](ue_ue.MovieSceneImageCaptureProtocolBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[GetName](ue_ue.MovieSceneImageCaptureProtocolBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[GetOuter](ue_ue.MovieSceneImageCaptureProtocolBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetState

▸ **GetState**(): [`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Returns

[`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[GetState](ue_ue.MovieSceneImageCaptureProtocolBase.md#getstate)

#### Defined in

[ue/ue.d.ts:22539](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22539)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[GetWorld](ue_ue.MovieSceneImageCaptureProtocolBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### IsCapturing

▸ **IsCapturing**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[IsCapturing](ue_ue.MovieSceneImageCaptureProtocolBase.md#iscapturing)

#### Defined in

[ue/ue.d.ts:22540](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22540)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FrameGrabberProtocol`](ue_ue.FrameGrabberProtocol.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FrameGrabberProtocol`](ue_ue.FrameGrabberProtocol.md)

#### Overrides

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[Find](ue_ue.MovieSceneImageCaptureProtocolBase.md#find)

#### Defined in

[ue/ue.d.ts:28504](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28504)

___

### Load

▸ `Static` **Load**(`InName`): [`FrameGrabberProtocol`](ue_ue.FrameGrabberProtocol.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FrameGrabberProtocol`](ue_ue.FrameGrabberProtocol.md)

#### Overrides

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[Load](ue_ue.MovieSceneImageCaptureProtocolBase.md#load)

#### Defined in

[ue/ue.d.ts:28505](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28505)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[StaticClass](ue_ue.MovieSceneImageCaptureProtocolBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:28503](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28503)
