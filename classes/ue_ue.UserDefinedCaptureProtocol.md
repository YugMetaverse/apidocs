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

#### Defined in

[ue/ue.d.ts:64830](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64830)

## Properties

### State

• **State**: [`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[State](ue_ue.MovieSceneImageCaptureProtocolBase.md#state)

#### Defined in

[ue/ue.d.ts:22538](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22538)

___

### World

• **World**: [`World`](ue_ue.World.md)

#### Defined in

[ue/ue.d.ts:64831](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64831)

___

### \_\_tid\_MovieSceneCaptureProtocolBase\_\_

• **\_\_tid\_MovieSceneCaptureProtocolBase\_\_**: `boolean`

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[__tid_MovieSceneCaptureProtocolBase__](ue_ue.MovieSceneImageCaptureProtocolBase.md#__tid_moviescenecaptureprotocolbase__)

#### Defined in

[ue/ue.d.ts:22545](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22545)

___

### \_\_tid\_MovieSceneImageCaptureProtocolBase\_\_

• **\_\_tid\_MovieSceneImageCaptureProtocolBase\_\_**: `boolean`

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[__tid_MovieSceneImageCaptureProtocolBase__](ue_ue.MovieSceneImageCaptureProtocolBase.md#__tid_moviesceneimagecaptureprotocolbase__)

#### Defined in

[ue/ue.d.ts:22554](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22554)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[__tid_Object__](ue_ue.MovieSceneImageCaptureProtocolBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_UserDefinedCaptureProtocol\_\_

• **\_\_tid\_UserDefinedCaptureProtocol\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:64852](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64852)

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

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[ExecuteUbergraph](ue_ue.MovieSceneImageCaptureProtocolBase.md#executeubergraph)

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

#### Defined in

[ue/ue.d.ts:64832](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64832)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[GetClass](ue_ue.MovieSceneImageCaptureProtocolBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetCurrentFrameMetrics

▸ **GetCurrentFrameMetrics**(): [`FrameMetrics`](ue_ue.FrameMetrics.md)

#### Returns

[`FrameMetrics`](ue_ue.FrameMetrics.md)

#### Defined in

[ue/ue.d.ts:64833](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64833)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[GetName](ue_ue.MovieSceneImageCaptureProtocolBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[GetOuter](ue_ue.MovieSceneImageCaptureProtocolBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetState

▸ **GetState**(): [`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Returns

[`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[GetState](ue_ue.MovieSceneImageCaptureProtocolBase.md#getstate)

#### Defined in

[ue/ue.d.ts:22539](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22539)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[GetWorld](ue_ue.MovieSceneImageCaptureProtocolBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsCapturing

▸ **IsCapturing**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[IsCapturing](ue_ue.MovieSceneImageCaptureProtocolBase.md#iscapturing)

#### Defined in

[ue/ue.d.ts:22540](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22540)

___

### OnBeginFinalize

▸ **OnBeginFinalize**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:64834](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64834)

___

### OnCanFinalize

▸ **OnCanFinalize**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:64835](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64835)

___

### OnCaptureFrame

▸ **OnCaptureFrame**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:64836](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64836)

___

### OnFinalize

▸ **OnFinalize**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:64837](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64837)

___

### OnPauseCapture

▸ **OnPauseCapture**(): `void`

#### Returns

`void`

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

#### Defined in

[ue/ue.d.ts:64839](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64839)

___

### OnPreTick

▸ **OnPreTick**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:64840](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64840)

___

### OnSetup

▸ **OnSetup**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:64841](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64841)

___

### OnStartCapture

▸ **OnStartCapture**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:64842](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64842)

___

### OnTick

▸ **OnTick**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:64843](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64843)

___

### OnWarmUp

▸ **OnWarmUp**(): `void`

#### Returns

`void`

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

#### Defined in

[ue/ue.d.ts:64846](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64846)

___

### StopCapturingFinalPixels

▸ **StopCapturingFinalPixels**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:64847](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64847)

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

#### Defined in

[ue/ue.d.ts:64849](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64849)

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

#### Defined in

[ue/ue.d.ts:64850](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64850)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[StaticClass](ue_ue.MovieSceneImageCaptureProtocolBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:64848](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64848)
