[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UserDefinedCaptureProtocol

# Class: UserDefinedCaptureProtocol

[ue/ue](../modules/ue_ue.md).UserDefinedCaptureProtocol

## Hierarchy

- [`MovieSceneImageCaptureProtocolBase`](ue_ue.MovieSceneImageCaptureProtocolBase.md)

  ↳ **`UserDefinedCaptureProtocol`**

  ↳↳ [`UserDefinedImageCaptureProtocol`](ue_ue.UserDefinedImageCaptureProtocol.md)

## Table of contents

### Constructors

- [constructor](ue_ue.UserDefinedCaptureProtocol.md#constructor)

### Properties

- [State](ue_ue.UserDefinedCaptureProtocol.md#state)
- [World](ue_ue.UserDefinedCaptureProtocol.md#world)
- [\_\_tid\_MovieSceneCaptureProtocolBase\_\_](ue_ue.UserDefinedCaptureProtocol.md#__tid_moviescenecaptureprotocolbase__)
- [\_\_tid\_MovieSceneImageCaptureProtocolBase\_\_](ue_ue.UserDefinedCaptureProtocol.md#__tid_moviesceneimagecaptureprotocolbase__)
- [\_\_tid\_Object\_\_](ue_ue.UserDefinedCaptureProtocol.md#__tid_object__)
- [\_\_tid\_UserDefinedCaptureProtocol\_\_](ue_ue.UserDefinedCaptureProtocol.md#__tid_userdefinedcaptureprotocol__)

### Methods

- [CreateDefaultSubobject](ue_ue.UserDefinedCaptureProtocol.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UserDefinedCaptureProtocol.md#executeubergraph)
- [GenerateFilename](ue_ue.UserDefinedCaptureProtocol.md#generatefilename)
- [GetClass](ue_ue.UserDefinedCaptureProtocol.md#getclass)
- [GetCurrentFrameMetrics](ue_ue.UserDefinedCaptureProtocol.md#getcurrentframemetrics)
- [GetName](ue_ue.UserDefinedCaptureProtocol.md#getname)
- [GetOuter](ue_ue.UserDefinedCaptureProtocol.md#getouter)
- [GetState](ue_ue.UserDefinedCaptureProtocol.md#getstate)
- [GetWorld](ue_ue.UserDefinedCaptureProtocol.md#getworld)
- [IsCapturing](ue_ue.UserDefinedCaptureProtocol.md#iscapturing)
- [OnBeginFinalize](ue_ue.UserDefinedCaptureProtocol.md#onbeginfinalize)
- [OnCanFinalize](ue_ue.UserDefinedCaptureProtocol.md#oncanfinalize)
- [OnCaptureFrame](ue_ue.UserDefinedCaptureProtocol.md#oncaptureframe)
- [OnFinalize](ue_ue.UserDefinedCaptureProtocol.md#onfinalize)
- [OnPauseCapture](ue_ue.UserDefinedCaptureProtocol.md#onpausecapture)
- [OnPixelsReceived](ue_ue.UserDefinedCaptureProtocol.md#onpixelsreceived)
- [OnPreTick](ue_ue.UserDefinedCaptureProtocol.md#onpretick)
- [OnSetup](ue_ue.UserDefinedCaptureProtocol.md#onsetup)
- [OnStartCapture](ue_ue.UserDefinedCaptureProtocol.md#onstartcapture)
- [OnTick](ue_ue.UserDefinedCaptureProtocol.md#ontick)
- [OnWarmUp](ue_ue.UserDefinedCaptureProtocol.md#onwarmup)
- [ResolveBuffer](ue_ue.UserDefinedCaptureProtocol.md#resolvebuffer)
- [StartCapturingFinalPixels](ue_ue.UserDefinedCaptureProtocol.md#startcapturingfinalpixels)
- [StopCapturingFinalPixels](ue_ue.UserDefinedCaptureProtocol.md#stopcapturingfinalpixels)
- [Find](ue_ue.UserDefinedCaptureProtocol.md#find)
- [Load](ue_ue.UserDefinedCaptureProtocol.md#load)
- [StaticClass](ue_ue.UserDefinedCaptureProtocol.md#staticclass)

## Constructors

### constructor

• **new UserDefinedCaptureProtocol**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[constructor](ue_ue.MovieSceneImageCaptureProtocolBase.md#constructor)

## Properties

### State

• **State**: [`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[State](ue_ue.MovieSceneImageCaptureProtocolBase.md#state)

___

### World

• **World**: [`World`](ue_ue.World.md)

___

### \_\_tid\_MovieSceneCaptureProtocolBase\_\_

• **\_\_tid\_MovieSceneCaptureProtocolBase\_\_**: `boolean`

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[__tid_MovieSceneCaptureProtocolBase__](ue_ue.MovieSceneImageCaptureProtocolBase.md#__tid_moviescenecaptureprotocolbase__)

___

### \_\_tid\_MovieSceneImageCaptureProtocolBase\_\_

• **\_\_tid\_MovieSceneImageCaptureProtocolBase\_\_**: `boolean`

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[__tid_MovieSceneImageCaptureProtocolBase__](ue_ue.MovieSceneImageCaptureProtocolBase.md#__tid_moviesceneimagecaptureprotocolbase__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[__tid_Object__](ue_ue.MovieSceneImageCaptureProtocolBase.md#__tid_object__)

___

### \_\_tid\_UserDefinedCaptureProtocol\_\_

• **\_\_tid\_UserDefinedCaptureProtocol\_\_**: `boolean`

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

___

### GenerateFilename

▸ **GenerateFilename**(`InFrameMetrics`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFrameMetrics` | [`FrameMetrics`](ue_ue.FrameMetrics.md) |

#### Returns

`string`

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[GetClass](ue_ue.MovieSceneImageCaptureProtocolBase.md#getclass)

___

### GetCurrentFrameMetrics

▸ **GetCurrentFrameMetrics**(): [`FrameMetrics`](ue_ue.FrameMetrics.md)

#### Returns

[`FrameMetrics`](ue_ue.FrameMetrics.md)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[GetName](ue_ue.MovieSceneImageCaptureProtocolBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[GetOuter](ue_ue.MovieSceneImageCaptureProtocolBase.md#getouter)

___

### GetState

▸ **GetState**(): [`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Returns

[`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[GetState](ue_ue.MovieSceneImageCaptureProtocolBase.md#getstate)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[GetWorld](ue_ue.MovieSceneImageCaptureProtocolBase.md#getworld)

___

### IsCapturing

▸ **IsCapturing**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[IsCapturing](ue_ue.MovieSceneImageCaptureProtocolBase.md#iscapturing)

___

### OnBeginFinalize

▸ **OnBeginFinalize**(): `void`

#### Returns

`void`

___

### OnCanFinalize

▸ **OnCanFinalize**(): `boolean`

#### Returns

`boolean`

___

### OnCaptureFrame

▸ **OnCaptureFrame**(): `void`

#### Returns

`void`

___

### OnFinalize

▸ **OnFinalize**(): `void`

#### Returns

`void`

___

### OnPauseCapture

▸ **OnPauseCapture**(): `void`

#### Returns

`void`

___

### OnPixelsReceived

▸ **OnPixelsReceived**(`Pixels`, `ID`, `FrameMetrics`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Pixels` | [`CapturedPixels`](ue_ue.CapturedPixels.md) |
| `ID` | [`CapturedPixelsID`](ue_ue.CapturedPixelsID.md) |
| `FrameMetrics` | [`FrameMetrics`](ue_ue.FrameMetrics.md) |

#### Returns

`void`

___

### OnPreTick

▸ **OnPreTick**(): `void`

#### Returns

`void`

___

### OnSetup

▸ **OnSetup**(): `boolean`

#### Returns

`boolean`

___

### OnStartCapture

▸ **OnStartCapture**(): `void`

#### Returns

`void`

___

### OnTick

▸ **OnTick**(): `void`

#### Returns

`void`

___

### OnWarmUp

▸ **OnWarmUp**(): `void`

#### Returns

`void`

___

### ResolveBuffer

▸ **ResolveBuffer**(`Buffer`, `BufferID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Buffer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |
| `BufferID` | [`CapturedPixelsID`](ue_ue.CapturedPixelsID.md) |

#### Returns

`void`

___

### StartCapturingFinalPixels

▸ **StartCapturingFinalPixels**(`StreamID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StreamID` | [`CapturedPixelsID`](ue_ue.CapturedPixelsID.md) |

#### Returns

`void`

___

### StopCapturingFinalPixels

▸ **StopCapturingFinalPixels**(): `void`

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UserDefinedCaptureProtocol`](ue_ue.UserDefinedCaptureProtocol.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UserDefinedCaptureProtocol`](ue_ue.UserDefinedCaptureProtocol.md)

#### Overrides

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[Find](ue_ue.MovieSceneImageCaptureProtocolBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`UserDefinedCaptureProtocol`](ue_ue.UserDefinedCaptureProtocol.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UserDefinedCaptureProtocol`](ue_ue.UserDefinedCaptureProtocol.md)

#### Overrides

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[Load](ue_ue.MovieSceneImageCaptureProtocolBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[StaticClass](ue_ue.MovieSceneImageCaptureProtocolBase.md#staticclass)
