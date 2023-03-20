[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CompositionGraphCaptureProtocol

# Class: CompositionGraphCaptureProtocol

[ue/ue](../modules/ue_ue.md).CompositionGraphCaptureProtocol

## Hierarchy

- [`MovieSceneImageCaptureProtocolBase`](ue_ue.MovieSceneImageCaptureProtocolBase.md)

  ↳ **`CompositionGraphCaptureProtocol`**

## Table of contents

### Constructors

- [constructor](ue_ue.CompositionGraphCaptureProtocol.md#constructor)

### Properties

- [CaptureGamut](ue_ue.CompositionGraphCaptureProtocol.md#capturegamut)
- [HDRCompressionQuality](ue_ue.CompositionGraphCaptureProtocol.md#hdrcompressionquality)
- [IncludeRenderPasses](ue_ue.CompositionGraphCaptureProtocol.md#includerenderpasses)
- [PostProcessingMaterial](ue_ue.CompositionGraphCaptureProtocol.md#postprocessingmaterial)
- [PostProcessingMaterialPtr](ue_ue.CompositionGraphCaptureProtocol.md#postprocessingmaterialptr)
- [State](ue_ue.CompositionGraphCaptureProtocol.md#state)
- [\_\_tid\_CompositionGraphCaptureProtocol\_\_](ue_ue.CompositionGraphCaptureProtocol.md#__tid_compositiongraphcaptureprotocol__)
- [\_\_tid\_MovieSceneCaptureProtocolBase\_\_](ue_ue.CompositionGraphCaptureProtocol.md#__tid_moviescenecaptureprotocolbase__)
- [\_\_tid\_MovieSceneImageCaptureProtocolBase\_\_](ue_ue.CompositionGraphCaptureProtocol.md#__tid_moviesceneimagecaptureprotocolbase__)
- [\_\_tid\_Object\_\_](ue_ue.CompositionGraphCaptureProtocol.md#__tid_object__)
- [bCaptureFramesInHDR](ue_ue.CompositionGraphCaptureProtocol.md#bcaptureframesinhdr)
- [bDisableScreenPercentage](ue_ue.CompositionGraphCaptureProtocol.md#bdisablescreenpercentage)

### Methods

- [CreateDefaultSubobject](ue_ue.CompositionGraphCaptureProtocol.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.CompositionGraphCaptureProtocol.md#executeubergraph)
- [GetClass](ue_ue.CompositionGraphCaptureProtocol.md#getclass)
- [GetName](ue_ue.CompositionGraphCaptureProtocol.md#getname)
- [GetOuter](ue_ue.CompositionGraphCaptureProtocol.md#getouter)
- [GetState](ue_ue.CompositionGraphCaptureProtocol.md#getstate)
- [GetWorld](ue_ue.CompositionGraphCaptureProtocol.md#getworld)
- [IsCapturing](ue_ue.CompositionGraphCaptureProtocol.md#iscapturing)
- [Find](ue_ue.CompositionGraphCaptureProtocol.md#find)
- [Load](ue_ue.CompositionGraphCaptureProtocol.md#load)
- [StaticClass](ue_ue.CompositionGraphCaptureProtocol.md#staticclass)

## Constructors

### constructor

• **new CompositionGraphCaptureProtocol**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[constructor](ue_ue.MovieSceneImageCaptureProtocolBase.md#constructor)

#### Defined in

[ue/ue.d.ts:28477](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28477)

## Properties

### CaptureGamut

• **CaptureGamut**: [`EHDRCaptureGamut`](../enums/ue_ue.EHDRCaptureGamut.md)

#### Defined in

[ue/ue.d.ts:28481](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28481)

___

### HDRCompressionQuality

• **HDRCompressionQuality**: `number`

#### Defined in

[ue/ue.d.ts:28480](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28480)

___

### IncludeRenderPasses

• **IncludeRenderPasses**: [`CompositionGraphCapturePasses`](ue_ue.CompositionGraphCapturePasses.md)

#### Defined in

[ue/ue.d.ts:28478](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28478)

___

### PostProcessingMaterial

• **PostProcessingMaterial**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:28482](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28482)

___

### PostProcessingMaterialPtr

• **PostProcessingMaterialPtr**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:28484](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28484)

___

### State

• **State**: [`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[State](ue_ue.MovieSceneImageCaptureProtocolBase.md#state)

#### Defined in

[ue/ue.d.ts:22538](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22538)

___

### \_\_tid\_CompositionGraphCaptureProtocol\_\_

• **\_\_tid\_CompositionGraphCaptureProtocol\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:28489](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28489)

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

### bCaptureFramesInHDR

• **bCaptureFramesInHDR**: `boolean`

#### Defined in

[ue/ue.d.ts:28479](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28479)

___

### bDisableScreenPercentage

• **bDisableScreenPercentage**: `boolean`

#### Defined in

[ue/ue.d.ts:28483](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28483)

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

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[GetClass](ue_ue.MovieSceneImageCaptureProtocolBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CompositionGraphCaptureProtocol`](ue_ue.CompositionGraphCaptureProtocol.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CompositionGraphCaptureProtocol`](ue_ue.CompositionGraphCaptureProtocol.md)

#### Overrides

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[Find](ue_ue.MovieSceneImageCaptureProtocolBase.md#find)

#### Defined in

[ue/ue.d.ts:28486](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28486)

___

### Load

▸ `Static` **Load**(`InName`): [`CompositionGraphCaptureProtocol`](ue_ue.CompositionGraphCaptureProtocol.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CompositionGraphCaptureProtocol`](ue_ue.CompositionGraphCaptureProtocol.md)

#### Overrides

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[Load](ue_ue.MovieSceneImageCaptureProtocolBase.md#load)

#### Defined in

[ue/ue.d.ts:28487](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28487)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneImageCaptureProtocolBase](ue_ue.MovieSceneImageCaptureProtocolBase.md).[StaticClass](ue_ue.MovieSceneImageCaptureProtocolBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:28485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28485)
