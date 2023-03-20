[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VideoCaptureProtocol

# Class: VideoCaptureProtocol

[ue/ue](../modules/ue_ue.md).VideoCaptureProtocol

## Hierarchy

- [`FrameGrabberProtocol`](ue_ue.FrameGrabberProtocol.md)

  ↳ **`VideoCaptureProtocol`**

## Table of contents

### Constructors

- [constructor](ue_ue.VideoCaptureProtocol.md#constructor)

### Properties

- [CompressionQuality](ue_ue.VideoCaptureProtocol.md#compressionquality)
- [State](ue_ue.VideoCaptureProtocol.md#state)
- [\_\_tid\_FrameGrabberProtocol\_\_](ue_ue.VideoCaptureProtocol.md#__tid_framegrabberprotocol__)
- [\_\_tid\_MovieSceneCaptureProtocolBase\_\_](ue_ue.VideoCaptureProtocol.md#__tid_moviescenecaptureprotocolbase__)
- [\_\_tid\_MovieSceneImageCaptureProtocolBase\_\_](ue_ue.VideoCaptureProtocol.md#__tid_moviesceneimagecaptureprotocolbase__)
- [\_\_tid\_Object\_\_](ue_ue.VideoCaptureProtocol.md#__tid_object__)
- [\_\_tid\_VideoCaptureProtocol\_\_](ue_ue.VideoCaptureProtocol.md#__tid_videocaptureprotocol__)
- [bUseCompression](ue_ue.VideoCaptureProtocol.md#busecompression)

### Methods

- [CreateDefaultSubobject](ue_ue.VideoCaptureProtocol.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.VideoCaptureProtocol.md#executeubergraph)
- [GetClass](ue_ue.VideoCaptureProtocol.md#getclass)
- [GetName](ue_ue.VideoCaptureProtocol.md#getname)
- [GetOuter](ue_ue.VideoCaptureProtocol.md#getouter)
- [GetState](ue_ue.VideoCaptureProtocol.md#getstate)
- [GetWorld](ue_ue.VideoCaptureProtocol.md#getworld)
- [IsCapturing](ue_ue.VideoCaptureProtocol.md#iscapturing)
- [Find](ue_ue.VideoCaptureProtocol.md#find)
- [Load](ue_ue.VideoCaptureProtocol.md#load)
- [StaticClass](ue_ue.VideoCaptureProtocol.md#staticclass)

## Constructors

### constructor

• **new VideoCaptureProtocol**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[constructor](ue_ue.FrameGrabberProtocol.md#constructor)

## Properties

### CompressionQuality

• **CompressionQuality**: `number`

___

### State

• **State**: [`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[State](ue_ue.FrameGrabberProtocol.md#state)

___

### \_\_tid\_FrameGrabberProtocol\_\_

• **\_\_tid\_FrameGrabberProtocol\_\_**: `boolean`

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[__tid_FrameGrabberProtocol__](ue_ue.FrameGrabberProtocol.md#__tid_framegrabberprotocol__)

___

### \_\_tid\_MovieSceneCaptureProtocolBase\_\_

• **\_\_tid\_MovieSceneCaptureProtocolBase\_\_**: `boolean`

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[__tid_MovieSceneCaptureProtocolBase__](ue_ue.FrameGrabberProtocol.md#__tid_moviescenecaptureprotocolbase__)

___

### \_\_tid\_MovieSceneImageCaptureProtocolBase\_\_

• **\_\_tid\_MovieSceneImageCaptureProtocolBase\_\_**: `boolean`

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[__tid_MovieSceneImageCaptureProtocolBase__](ue_ue.FrameGrabberProtocol.md#__tid_moviesceneimagecaptureprotocolbase__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[__tid_Object__](ue_ue.FrameGrabberProtocol.md#__tid_object__)

___

### \_\_tid\_VideoCaptureProtocol\_\_

• **\_\_tid\_VideoCaptureProtocol\_\_**: `boolean`

___

### bUseCompression

• **bUseCompression**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[GetClass](ue_ue.FrameGrabberProtocol.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[GetName](ue_ue.FrameGrabberProtocol.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[GetOuter](ue_ue.FrameGrabberProtocol.md#getouter)

___

### GetState

▸ **GetState**(): [`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Returns

[`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[GetState](ue_ue.FrameGrabberProtocol.md#getstate)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[GetWorld](ue_ue.FrameGrabberProtocol.md#getworld)

___

### IsCapturing

▸ **IsCapturing**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[IsCapturing](ue_ue.FrameGrabberProtocol.md#iscapturing)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`VideoCaptureProtocol`](ue_ue.VideoCaptureProtocol.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`VideoCaptureProtocol`](ue_ue.VideoCaptureProtocol.md)

#### Overrides

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[Find](ue_ue.FrameGrabberProtocol.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`VideoCaptureProtocol`](ue_ue.VideoCaptureProtocol.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`VideoCaptureProtocol`](ue_ue.VideoCaptureProtocol.md)

#### Overrides

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[Load](ue_ue.FrameGrabberProtocol.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FrameGrabberProtocol](ue_ue.FrameGrabberProtocol.md).[StaticClass](ue_ue.FrameGrabberProtocol.md#staticclass)
