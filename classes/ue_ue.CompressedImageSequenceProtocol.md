[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CompressedImageSequenceProtocol

# Class: CompressedImageSequenceProtocol

[ue/ue](../modules/ue_ue.md).CompressedImageSequenceProtocol

## Hierarchy

- [`ImageSequenceProtocol`](ue_ue.ImageSequenceProtocol.md)

  ↳ **`CompressedImageSequenceProtocol`**

  ↳↳ [`ImageSequenceProtocol_JPG`](ue_ue.ImageSequenceProtocol_JPG.md)

  ↳↳ [`ImageSequenceProtocol_PNG`](ue_ue.ImageSequenceProtocol_PNG.md)

## Table of contents

### Constructors

- [constructor](ue_ue.CompressedImageSequenceProtocol.md#constructor)

### Properties

- [CompressionQuality](ue_ue.CompressedImageSequenceProtocol.md#compressionquality)
- [State](ue_ue.CompressedImageSequenceProtocol.md#state)
- [\_\_tid\_CompressedImageSequenceProtocol\_\_](ue_ue.CompressedImageSequenceProtocol.md#__tid_compressedimagesequenceprotocol__)
- [\_\_tid\_FrameGrabberProtocol\_\_](ue_ue.CompressedImageSequenceProtocol.md#__tid_framegrabberprotocol__)
- [\_\_tid\_ImageSequenceProtocol\_\_](ue_ue.CompressedImageSequenceProtocol.md#__tid_imagesequenceprotocol__)
- [\_\_tid\_MovieSceneCaptureProtocolBase\_\_](ue_ue.CompressedImageSequenceProtocol.md#__tid_moviescenecaptureprotocolbase__)
- [\_\_tid\_MovieSceneImageCaptureProtocolBase\_\_](ue_ue.CompressedImageSequenceProtocol.md#__tid_moviesceneimagecaptureprotocolbase__)
- [\_\_tid\_Object\_\_](ue_ue.CompressedImageSequenceProtocol.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.CompressedImageSequenceProtocol.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.CompressedImageSequenceProtocol.md#executeubergraph)
- [GetClass](ue_ue.CompressedImageSequenceProtocol.md#getclass)
- [GetName](ue_ue.CompressedImageSequenceProtocol.md#getname)
- [GetOuter](ue_ue.CompressedImageSequenceProtocol.md#getouter)
- [GetState](ue_ue.CompressedImageSequenceProtocol.md#getstate)
- [GetWorld](ue_ue.CompressedImageSequenceProtocol.md#getworld)
- [IsCapturing](ue_ue.CompressedImageSequenceProtocol.md#iscapturing)
- [Find](ue_ue.CompressedImageSequenceProtocol.md#find)
- [Load](ue_ue.CompressedImageSequenceProtocol.md#load)
- [StaticClass](ue_ue.CompressedImageSequenceProtocol.md#staticclass)

## Constructors

### constructor

• **new CompressedImageSequenceProtocol**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ImageSequenceProtocol](ue_ue.ImageSequenceProtocol.md).[constructor](ue_ue.ImageSequenceProtocol.md#constructor)

## Properties

### CompressionQuality

• **CompressionQuality**: `number`

___

### State

• **State**: [`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Inherited from

[ImageSequenceProtocol](ue_ue.ImageSequenceProtocol.md).[State](ue_ue.ImageSequenceProtocol.md#state)

___

### \_\_tid\_CompressedImageSequenceProtocol\_\_

• **\_\_tid\_CompressedImageSequenceProtocol\_\_**: `boolean`

___

### \_\_tid\_FrameGrabberProtocol\_\_

• **\_\_tid\_FrameGrabberProtocol\_\_**: `boolean`

#### Inherited from

[ImageSequenceProtocol](ue_ue.ImageSequenceProtocol.md).[__tid_FrameGrabberProtocol__](ue_ue.ImageSequenceProtocol.md#__tid_framegrabberprotocol__)

___

### \_\_tid\_ImageSequenceProtocol\_\_

• **\_\_tid\_ImageSequenceProtocol\_\_**: `boolean`

#### Inherited from

[ImageSequenceProtocol](ue_ue.ImageSequenceProtocol.md).[__tid_ImageSequenceProtocol__](ue_ue.ImageSequenceProtocol.md#__tid_imagesequenceprotocol__)

___

### \_\_tid\_MovieSceneCaptureProtocolBase\_\_

• **\_\_tid\_MovieSceneCaptureProtocolBase\_\_**: `boolean`

#### Inherited from

[ImageSequenceProtocol](ue_ue.ImageSequenceProtocol.md).[__tid_MovieSceneCaptureProtocolBase__](ue_ue.ImageSequenceProtocol.md#__tid_moviescenecaptureprotocolbase__)

___

### \_\_tid\_MovieSceneImageCaptureProtocolBase\_\_

• **\_\_tid\_MovieSceneImageCaptureProtocolBase\_\_**: `boolean`

#### Inherited from

[ImageSequenceProtocol](ue_ue.ImageSequenceProtocol.md).[__tid_MovieSceneImageCaptureProtocolBase__](ue_ue.ImageSequenceProtocol.md#__tid_moviesceneimagecaptureprotocolbase__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ImageSequenceProtocol](ue_ue.ImageSequenceProtocol.md).[__tid_Object__](ue_ue.ImageSequenceProtocol.md#__tid_object__)

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

[ImageSequenceProtocol](ue_ue.ImageSequenceProtocol.md).[CreateDefaultSubobject](ue_ue.ImageSequenceProtocol.md#createdefaultsubobject)

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

[ImageSequenceProtocol](ue_ue.ImageSequenceProtocol.md).[ExecuteUbergraph](ue_ue.ImageSequenceProtocol.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ImageSequenceProtocol](ue_ue.ImageSequenceProtocol.md).[GetClass](ue_ue.ImageSequenceProtocol.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ImageSequenceProtocol](ue_ue.ImageSequenceProtocol.md).[GetName](ue_ue.ImageSequenceProtocol.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ImageSequenceProtocol](ue_ue.ImageSequenceProtocol.md).[GetOuter](ue_ue.ImageSequenceProtocol.md#getouter)

___

### GetState

▸ **GetState**(): [`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Returns

[`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Inherited from

[ImageSequenceProtocol](ue_ue.ImageSequenceProtocol.md).[GetState](ue_ue.ImageSequenceProtocol.md#getstate)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ImageSequenceProtocol](ue_ue.ImageSequenceProtocol.md).[GetWorld](ue_ue.ImageSequenceProtocol.md#getworld)

___

### IsCapturing

▸ **IsCapturing**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ImageSequenceProtocol](ue_ue.ImageSequenceProtocol.md).[IsCapturing](ue_ue.ImageSequenceProtocol.md#iscapturing)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CompressedImageSequenceProtocol`](ue_ue.CompressedImageSequenceProtocol.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CompressedImageSequenceProtocol`](ue_ue.CompressedImageSequenceProtocol.md)

#### Overrides

[ImageSequenceProtocol](ue_ue.ImageSequenceProtocol.md).[Find](ue_ue.ImageSequenceProtocol.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`CompressedImageSequenceProtocol`](ue_ue.CompressedImageSequenceProtocol.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CompressedImageSequenceProtocol`](ue_ue.CompressedImageSequenceProtocol.md)

#### Overrides

[ImageSequenceProtocol](ue_ue.ImageSequenceProtocol.md).[Load](ue_ue.ImageSequenceProtocol.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ImageSequenceProtocol](ue_ue.ImageSequenceProtocol.md).[StaticClass](ue_ue.ImageSequenceProtocol.md#staticclass)
