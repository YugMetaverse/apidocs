[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ImageSequenceProtocol

# Class: ImageSequenceProtocol

[ue/ue](../modules/ue_ue.md).ImageSequenceProtocol

## Hierarchy

- [`FrameGrabberProtocol`](ue_ue.FrameGrabberProtocol.md)

  ↳ **`ImageSequenceProtocol`**

  ↳↳ [`CompressedImageSequenceProtocol`](ue_ue.CompressedImageSequenceProtocol.md)

  ↳↳ [`ImageSequenceProtocol_BMP`](ue_ue.ImageSequenceProtocol_BMP.md)

  ↳↳ [`ImageSequenceProtocol_EXR`](ue_ue.ImageSequenceProtocol_EXR.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ImageSequenceProtocol.md#constructor)

### Properties

- [State](ue_ue.ImageSequenceProtocol.md#state)
- [\_\_tid\_FrameGrabberProtocol\_\_](ue_ue.ImageSequenceProtocol.md#__tid_framegrabberprotocol__)
- [\_\_tid\_ImageSequenceProtocol\_\_](ue_ue.ImageSequenceProtocol.md#__tid_imagesequenceprotocol__)
- [\_\_tid\_MovieSceneCaptureProtocolBase\_\_](ue_ue.ImageSequenceProtocol.md#__tid_moviescenecaptureprotocolbase__)
- [\_\_tid\_MovieSceneImageCaptureProtocolBase\_\_](ue_ue.ImageSequenceProtocol.md#__tid_moviesceneimagecaptureprotocolbase__)
- [\_\_tid\_Object\_\_](ue_ue.ImageSequenceProtocol.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ImageSequenceProtocol.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ImageSequenceProtocol.md#executeubergraph)
- [GetClass](ue_ue.ImageSequenceProtocol.md#getclass)
- [GetName](ue_ue.ImageSequenceProtocol.md#getname)
- [GetOuter](ue_ue.ImageSequenceProtocol.md#getouter)
- [GetState](ue_ue.ImageSequenceProtocol.md#getstate)
- [GetWorld](ue_ue.ImageSequenceProtocol.md#getworld)
- [IsCapturing](ue_ue.ImageSequenceProtocol.md#iscapturing)
- [Find](ue_ue.ImageSequenceProtocol.md#find)
- [Load](ue_ue.ImageSequenceProtocol.md#load)
- [StaticClass](ue_ue.ImageSequenceProtocol.md#staticclass)

## Constructors

### constructor

• **new ImageSequenceProtocol**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[constructor](ue_ue.FrameGrabberProtocol.md#constructor)

#### Defined in

[ue/ue.d.ts:28511](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28511)

## Properties

### State

• **State**: [`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[State](ue_ue.FrameGrabberProtocol.md#state)

#### Defined in

[ue/ue.d.ts:22538](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22538)

___

### \_\_tid\_FrameGrabberProtocol\_\_

• **\_\_tid\_FrameGrabberProtocol\_\_**: `boolean`

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[__tid_FrameGrabberProtocol__](ue_ue.FrameGrabberProtocol.md#__tid_framegrabberprotocol__)

#### Defined in

[ue/ue.d.ts:28507](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28507)

___

### \_\_tid\_ImageSequenceProtocol\_\_

• **\_\_tid\_ImageSequenceProtocol\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:28516](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28516)

___

### \_\_tid\_MovieSceneCaptureProtocolBase\_\_

• **\_\_tid\_MovieSceneCaptureProtocolBase\_\_**: `boolean`

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[__tid_MovieSceneCaptureProtocolBase__](ue_ue.FrameGrabberProtocol.md#__tid_moviescenecaptureprotocolbase__)

#### Defined in

[ue/ue.d.ts:22545](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22545)

___

### \_\_tid\_MovieSceneImageCaptureProtocolBase\_\_

• **\_\_tid\_MovieSceneImageCaptureProtocolBase\_\_**: `boolean`

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[__tid_MovieSceneImageCaptureProtocolBase__](ue_ue.FrameGrabberProtocol.md#__tid_moviesceneimagecaptureprotocolbase__)

#### Defined in

[ue/ue.d.ts:22554](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22554)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[__tid_Object__](ue_ue.FrameGrabberProtocol.md#__tid_object__)

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

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[CreateDefaultSubobject](ue_ue.FrameGrabberProtocol.md#createdefaultsubobject)

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

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[ExecuteUbergraph](ue_ue.FrameGrabberProtocol.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[GetClass](ue_ue.FrameGrabberProtocol.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[GetName](ue_ue.FrameGrabberProtocol.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[GetOuter](ue_ue.FrameGrabberProtocol.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetState

▸ **GetState**(): [`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Returns

[`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[GetState](ue_ue.FrameGrabberProtocol.md#getstate)

#### Defined in

[ue/ue.d.ts:22539](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22539)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[GetWorld](ue_ue.FrameGrabberProtocol.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### IsCapturing

▸ **IsCapturing**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[IsCapturing](ue_ue.FrameGrabberProtocol.md#iscapturing)

#### Defined in

[ue/ue.d.ts:22540](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22540)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ImageSequenceProtocol`](ue_ue.ImageSequenceProtocol.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ImageSequenceProtocol`](ue_ue.ImageSequenceProtocol.md)

#### Overrides

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[Find](ue_ue.FrameGrabberProtocol.md#find)

#### Defined in

[ue/ue.d.ts:28513](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28513)

___

### Load

▸ `Static` **Load**(`InName`): [`ImageSequenceProtocol`](ue_ue.ImageSequenceProtocol.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ImageSequenceProtocol`](ue_ue.ImageSequenceProtocol.md)

#### Overrides

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[Load](ue_ue.FrameGrabberProtocol.md#load)

#### Defined in

[ue/ue.d.ts:28514](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28514)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[StaticClass](ue_ue.FrameGrabberProtocol.md#staticclass)

#### Defined in

[ue/ue.d.ts:28512](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28512)
