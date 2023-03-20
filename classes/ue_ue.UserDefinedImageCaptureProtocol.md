[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UserDefinedImageCaptureProtocol

# Class: UserDefinedImageCaptureProtocol

[ue/ue](../modules/ue_ue.md).UserDefinedImageCaptureProtocol

## Hierarchy

- [`UserDefinedCaptureProtocol`](ue_ue.UserDefinedCaptureProtocol.md)

  ↳ **`UserDefinedImageCaptureProtocol`**

## Table of contents

### Constructors

- [constructor](ue_ue.UserDefinedImageCaptureProtocol.md#constructor)

### Properties

- [CompressionQuality](ue_ue.UserDefinedImageCaptureProtocol.md#compressionquality)
- [Format](ue_ue.UserDefinedImageCaptureProtocol.md#format)
- [State](ue_ue.UserDefinedImageCaptureProtocol.md#state)
- [World](ue_ue.UserDefinedImageCaptureProtocol.md#world)
- [\_\_tid\_MovieSceneCaptureProtocolBase\_\_](ue_ue.UserDefinedImageCaptureProtocol.md#__tid_moviescenecaptureprotocolbase__)
- [\_\_tid\_MovieSceneImageCaptureProtocolBase\_\_](ue_ue.UserDefinedImageCaptureProtocol.md#__tid_moviesceneimagecaptureprotocolbase__)
- [\_\_tid\_Object\_\_](ue_ue.UserDefinedImageCaptureProtocol.md#__tid_object__)
- [\_\_tid\_UserDefinedCaptureProtocol\_\_](ue_ue.UserDefinedImageCaptureProtocol.md#__tid_userdefinedcaptureprotocol__)
- [\_\_tid\_UserDefinedImageCaptureProtocol\_\_](ue_ue.UserDefinedImageCaptureProtocol.md#__tid_userdefinedimagecaptureprotocol__)
- [bEnableCompression](ue_ue.UserDefinedImageCaptureProtocol.md#benablecompression)

### Methods

- [CreateDefaultSubobject](ue_ue.UserDefinedImageCaptureProtocol.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UserDefinedImageCaptureProtocol.md#executeubergraph)
- [GenerateFilename](ue_ue.UserDefinedImageCaptureProtocol.md#generatefilename)
- [GenerateFilenameForBuffer](ue_ue.UserDefinedImageCaptureProtocol.md#generatefilenameforbuffer)
- [GenerateFilenameForCurrentFrame](ue_ue.UserDefinedImageCaptureProtocol.md#generatefilenameforcurrentframe)
- [GetClass](ue_ue.UserDefinedImageCaptureProtocol.md#getclass)
- [GetCurrentFrameMetrics](ue_ue.UserDefinedImageCaptureProtocol.md#getcurrentframemetrics)
- [GetName](ue_ue.UserDefinedImageCaptureProtocol.md#getname)
- [GetOuter](ue_ue.UserDefinedImageCaptureProtocol.md#getouter)
- [GetState](ue_ue.UserDefinedImageCaptureProtocol.md#getstate)
- [GetWorld](ue_ue.UserDefinedImageCaptureProtocol.md#getworld)
- [IsCapturing](ue_ue.UserDefinedImageCaptureProtocol.md#iscapturing)
- [OnBeginFinalize](ue_ue.UserDefinedImageCaptureProtocol.md#onbeginfinalize)
- [OnCanFinalize](ue_ue.UserDefinedImageCaptureProtocol.md#oncanfinalize)
- [OnCaptureFrame](ue_ue.UserDefinedImageCaptureProtocol.md#oncaptureframe)
- [OnFinalize](ue_ue.UserDefinedImageCaptureProtocol.md#onfinalize)
- [OnPauseCapture](ue_ue.UserDefinedImageCaptureProtocol.md#onpausecapture)
- [OnPixelsReceived](ue_ue.UserDefinedImageCaptureProtocol.md#onpixelsreceived)
- [OnPreTick](ue_ue.UserDefinedImageCaptureProtocol.md#onpretick)
- [OnSetup](ue_ue.UserDefinedImageCaptureProtocol.md#onsetup)
- [OnStartCapture](ue_ue.UserDefinedImageCaptureProtocol.md#onstartcapture)
- [OnTick](ue_ue.UserDefinedImageCaptureProtocol.md#ontick)
- [OnWarmUp](ue_ue.UserDefinedImageCaptureProtocol.md#onwarmup)
- [ResolveBuffer](ue_ue.UserDefinedImageCaptureProtocol.md#resolvebuffer)
- [StartCapturingFinalPixels](ue_ue.UserDefinedImageCaptureProtocol.md#startcapturingfinalpixels)
- [StopCapturingFinalPixels](ue_ue.UserDefinedImageCaptureProtocol.md#stopcapturingfinalpixels)
- [WriteImageToDisk](ue_ue.UserDefinedImageCaptureProtocol.md#writeimagetodisk)
- [Find](ue_ue.UserDefinedImageCaptureProtocol.md#find)
- [Load](ue_ue.UserDefinedImageCaptureProtocol.md#load)
- [StaticClass](ue_ue.UserDefinedImageCaptureProtocol.md#staticclass)

## Constructors

### constructor

• **new UserDefinedImageCaptureProtocol**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[constructor](ue_ue.UserDefinedCaptureProtocol.md#constructor)

#### Defined in

[ue/ue.d.ts:64868](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64868)

## Properties

### CompressionQuality

• **CompressionQuality**: `number`

#### Defined in

[ue/ue.d.ts:64871](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64871)

___

### Format

• **Format**: [`EDesiredImageFormat`](../enums/ue_ue.EDesiredImageFormat.md)

#### Defined in

[ue/ue.d.ts:64869](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64869)

___

### State

• **State**: [`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[State](ue_ue.UserDefinedCaptureProtocol.md#state)

#### Defined in

[ue/ue.d.ts:22538](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22538)

___

### World

• **World**: [`World`](ue_ue.World.md)

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[World](ue_ue.UserDefinedCaptureProtocol.md#world)

#### Defined in

[ue/ue.d.ts:64831](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64831)

___

### \_\_tid\_MovieSceneCaptureProtocolBase\_\_

• **\_\_tid\_MovieSceneCaptureProtocolBase\_\_**: `boolean`

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[__tid_MovieSceneCaptureProtocolBase__](ue_ue.UserDefinedCaptureProtocol.md#__tid_moviescenecaptureprotocolbase__)

#### Defined in

[ue/ue.d.ts:22545](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22545)

___

### \_\_tid\_MovieSceneImageCaptureProtocolBase\_\_

• **\_\_tid\_MovieSceneImageCaptureProtocolBase\_\_**: `boolean`

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[__tid_MovieSceneImageCaptureProtocolBase__](ue_ue.UserDefinedCaptureProtocol.md#__tid_moviesceneimagecaptureprotocolbase__)

#### Defined in

[ue/ue.d.ts:22554](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22554)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[__tid_Object__](ue_ue.UserDefinedCaptureProtocol.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_UserDefinedCaptureProtocol\_\_

• **\_\_tid\_UserDefinedCaptureProtocol\_\_**: `boolean`

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[__tid_UserDefinedCaptureProtocol__](ue_ue.UserDefinedCaptureProtocol.md#__tid_userdefinedcaptureprotocol__)

#### Defined in

[ue/ue.d.ts:64852](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64852)

___

### \_\_tid\_UserDefinedImageCaptureProtocol\_\_

• **\_\_tid\_UserDefinedImageCaptureProtocol\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:64879](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64879)

___

### bEnableCompression

• **bEnableCompression**: `boolean`

#### Defined in

[ue/ue.d.ts:64870](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64870)

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

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[CreateDefaultSubobject](ue_ue.UserDefinedCaptureProtocol.md#createdefaultsubobject)

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

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[ExecuteUbergraph](ue_ue.UserDefinedCaptureProtocol.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GenerateFilename

▸ **GenerateFilename**(`InFrameMetrics`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFrameMetrics` | [`FrameMetrics`](ue_ue.FrameMetrics.md) |

#### Returns

`string`

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[GenerateFilename](ue_ue.UserDefinedCaptureProtocol.md#generatefilename)

#### Defined in

[ue/ue.d.ts:64832](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64832)

___

### GenerateFilenameForBuffer

▸ **GenerateFilenameForBuffer**(`Buffer`, `StreamID`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Buffer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |
| `StreamID` | [`CapturedPixelsID`](ue_ue.CapturedPixelsID.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:64872](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64872)

___

### GenerateFilenameForCurrentFrame

▸ **GenerateFilenameForCurrentFrame**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:64873](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64873)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[GetClass](ue_ue.UserDefinedCaptureProtocol.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetCurrentFrameMetrics

▸ **GetCurrentFrameMetrics**(): [`FrameMetrics`](ue_ue.FrameMetrics.md)

#### Returns

[`FrameMetrics`](ue_ue.FrameMetrics.md)

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[GetCurrentFrameMetrics](ue_ue.UserDefinedCaptureProtocol.md#getcurrentframemetrics)

#### Defined in

[ue/ue.d.ts:64833](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64833)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[GetName](ue_ue.UserDefinedCaptureProtocol.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[GetOuter](ue_ue.UserDefinedCaptureProtocol.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetState

▸ **GetState**(): [`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Returns

[`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[GetState](ue_ue.UserDefinedCaptureProtocol.md#getstate)

#### Defined in

[ue/ue.d.ts:22539](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22539)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[GetWorld](ue_ue.UserDefinedCaptureProtocol.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsCapturing

▸ **IsCapturing**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[IsCapturing](ue_ue.UserDefinedCaptureProtocol.md#iscapturing)

#### Defined in

[ue/ue.d.ts:22540](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22540)

___

### OnBeginFinalize

▸ **OnBeginFinalize**(): `void`

#### Returns

`void`

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[OnBeginFinalize](ue_ue.UserDefinedCaptureProtocol.md#onbeginfinalize)

#### Defined in

[ue/ue.d.ts:64834](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64834)

___

### OnCanFinalize

▸ **OnCanFinalize**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[OnCanFinalize](ue_ue.UserDefinedCaptureProtocol.md#oncanfinalize)

#### Defined in

[ue/ue.d.ts:64835](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64835)

___

### OnCaptureFrame

▸ **OnCaptureFrame**(): `void`

#### Returns

`void`

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[OnCaptureFrame](ue_ue.UserDefinedCaptureProtocol.md#oncaptureframe)

#### Defined in

[ue/ue.d.ts:64836](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64836)

___

### OnFinalize

▸ **OnFinalize**(): `void`

#### Returns

`void`

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[OnFinalize](ue_ue.UserDefinedCaptureProtocol.md#onfinalize)

#### Defined in

[ue/ue.d.ts:64837](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64837)

___

### OnPauseCapture

▸ **OnPauseCapture**(): `void`

#### Returns

`void`

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[OnPauseCapture](ue_ue.UserDefinedCaptureProtocol.md#onpausecapture)

#### Defined in

[ue/ue.d.ts:64838](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64838)

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

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[OnPixelsReceived](ue_ue.UserDefinedCaptureProtocol.md#onpixelsreceived)

#### Defined in

[ue/ue.d.ts:64839](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64839)

___

### OnPreTick

▸ **OnPreTick**(): `void`

#### Returns

`void`

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[OnPreTick](ue_ue.UserDefinedCaptureProtocol.md#onpretick)

#### Defined in

[ue/ue.d.ts:64840](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64840)

___

### OnSetup

▸ **OnSetup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[OnSetup](ue_ue.UserDefinedCaptureProtocol.md#onsetup)

#### Defined in

[ue/ue.d.ts:64841](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64841)

___

### OnStartCapture

▸ **OnStartCapture**(): `void`

#### Returns

`void`

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[OnStartCapture](ue_ue.UserDefinedCaptureProtocol.md#onstartcapture)

#### Defined in

[ue/ue.d.ts:64842](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64842)

___

### OnTick

▸ **OnTick**(): `void`

#### Returns

`void`

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[OnTick](ue_ue.UserDefinedCaptureProtocol.md#ontick)

#### Defined in

[ue/ue.d.ts:64843](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64843)

___

### OnWarmUp

▸ **OnWarmUp**(): `void`

#### Returns

`void`

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[OnWarmUp](ue_ue.UserDefinedCaptureProtocol.md#onwarmup)

#### Defined in

[ue/ue.d.ts:64844](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64844)

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

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[ResolveBuffer](ue_ue.UserDefinedCaptureProtocol.md#resolvebuffer)

#### Defined in

[ue/ue.d.ts:64845](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64845)

___

### StartCapturingFinalPixels

▸ **StartCapturingFinalPixels**(`StreamID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StreamID` | [`CapturedPixelsID`](ue_ue.CapturedPixelsID.md) |

#### Returns

`void`

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[StartCapturingFinalPixels](ue_ue.UserDefinedCaptureProtocol.md#startcapturingfinalpixels)

#### Defined in

[ue/ue.d.ts:64846](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64846)

___

### StopCapturingFinalPixels

▸ **StopCapturingFinalPixels**(): `void`

#### Returns

`void`

#### Inherited from

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[StopCapturingFinalPixels](ue_ue.UserDefinedCaptureProtocol.md#stopcapturingfinalpixels)

#### Defined in

[ue/ue.d.ts:64847](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64847)

___

### WriteImageToDisk

▸ **WriteImageToDisk**(`PixelData`, `StreamID`, `FrameMetrics`, `bCopyImageData?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PixelData` | [`CapturedPixels`](ue_ue.CapturedPixels.md) |
| `StreamID` | [`CapturedPixelsID`](ue_ue.CapturedPixelsID.md) |
| `FrameMetrics` | [`FrameMetrics`](ue_ue.FrameMetrics.md) |
| `bCopyImageData?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:64874](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64874)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UserDefinedImageCaptureProtocol`](ue_ue.UserDefinedImageCaptureProtocol.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UserDefinedImageCaptureProtocol`](ue_ue.UserDefinedImageCaptureProtocol.md)

#### Overrides

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[Find](ue_ue.UserDefinedCaptureProtocol.md#find)

#### Defined in

[ue/ue.d.ts:64876](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64876)

___

### Load

▸ `Static` **Load**(`InName`): [`UserDefinedImageCaptureProtocol`](ue_ue.UserDefinedImageCaptureProtocol.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UserDefinedImageCaptureProtocol`](ue_ue.UserDefinedImageCaptureProtocol.md)

#### Overrides

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[Load](ue_ue.UserDefinedCaptureProtocol.md#load)

#### Defined in

[ue/ue.d.ts:64877](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64877)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[UserDefinedCaptureProtocol](ue_ue.UserDefinedCaptureProtocol.md).[StaticClass](ue_ue.UserDefinedCaptureProtocol.md#staticclass)

#### Defined in

[ue/ue.d.ts:64875](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64875)
