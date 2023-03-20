[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Texture

# Class: Texture

[ue/ue](../modules/ue_ue.md).Texture

## Hierarchy

- [`StreamableRenderAsset`](ue_ue.StreamableRenderAsset.md)

  ↳ **`Texture`**

  ↳↳ [`Texture2D`](ue_ue.Texture2D.md)

  ↳↳ [`TextureCube`](ue_ue.TextureCube.md)

  ↳↳ [`ARTexture`](ue_ue.ARTexture.md)

  ↳↳ [`Texture2DDynamic`](ue_ue.Texture2DDynamic.md)

  ↳↳ [`TextureRenderTarget`](ue_ue.TextureRenderTarget.md)

  ↳↳ [`VolumeTexture`](ue_ue.VolumeTexture.md)

  ↳↳ [`MediaTexture`](ue_ue.MediaTexture.md)

  ↳↳ [`Texture2DArray`](ue_ue.Texture2DArray.md)

## Table of contents

### Constructors

- [constructor](ue_ue.Texture.md#constructor)

### Properties

- [AdjustBrightness](ue_ue.Texture.md#adjustbrightness)
- [AdjustBrightnessCurve](ue_ue.Texture.md#adjustbrightnesscurve)
- [AdjustHue](ue_ue.Texture.md#adjusthue)
- [AdjustMaxAlpha](ue_ue.Texture.md#adjustmaxalpha)
- [AdjustMinAlpha](ue_ue.Texture.md#adjustminalpha)
- [AdjustRGBCurve](ue_ue.Texture.md#adjustrgbcurve)
- [AdjustSaturation](ue_ue.Texture.md#adjustsaturation)
- [AdjustVibrance](ue_ue.Texture.md#adjustvibrance)
- [AlphaCoverageThresholds](ue_ue.Texture.md#alphacoveragethresholds)
- [AssetImportData](ue_ue.Texture.md#assetimportdata)
- [AssetUserData](ue_ue.Texture.md#assetuserdata)
- [CachedCombinedLODBias](ue_ue.Texture.md#cachedcombinedlodbias)
- [CachedNumResidentLODs](ue_ue.Texture.md#cachednumresidentlods)
- [ChromaKeyColor](ue_ue.Texture.md#chromakeycolor)
- [ChromaKeyThreshold](ue_ue.Texture.md#chromakeythreshold)
- [CompositePower](ue_ue.Texture.md#compositepower)
- [CompositeTexture](ue_ue.Texture.md#compositetexture)
- [CompositeTextureMode](ue_ue.Texture.md#compositetexturemode)
- [CompressionNoAlpha](ue_ue.Texture.md#compressionnoalpha)
- [CompressionNone](ue_ue.Texture.md#compressionnone)
- [CompressionQuality](ue_ue.Texture.md#compressionquality)
- [CompressionSettings](ue_ue.Texture.md#compressionsettings)
- [CompressionYCoCg](ue_ue.Texture.md#compressionycocg)
- [DeferCompression](ue_ue.Texture.md#defercompression)
- [Filter](ue_ue.Texture.md#filter)
- [ForceMipLevelsToBeResidentTimestamp](ue_ue.Texture.md#forcemiplevelstoberesidenttimestamp)
- [LODBias](ue_ue.Texture.md#lodbias)
- [LODGroup](ue_ue.Texture.md#lodgroup)
- [LayerFormatSettings](ue_ue.Texture.md#layerformatsettings)
- [LightingGuid](ue_ue.Texture.md#lightingguid)
- [LossyCompressionAmount](ue_ue.Texture.md#lossycompressionamount)
- [MaxTextureSize](ue_ue.Texture.md#maxtexturesize)
- [MipGenSettings](ue_ue.Texture.md#mipgensettings)
- [MipLoadOptions](ue_ue.Texture.md#miploadoptions)
- [NeverStream](ue_ue.Texture.md#neverstream)
- [NumCinematicMipLevels](ue_ue.Texture.md#numcinematicmiplevels)
- [PaddingColor](ue_ue.Texture.md#paddingcolor)
- [PowerOfTwoMode](ue_ue.Texture.md#poweroftwomode)
- [SRGB](ue_ue.Texture.md#srgb)
- [Source](ue_ue.Texture.md#source)
- [SourceFilePath](ue_ue.Texture.md#sourcefilepath)
- [StreamingIndex](ue_ue.Texture.md#streamingindex)
- [VirtualTextureStreaming](ue_ue.Texture.md#virtualtexturestreaming)
- [\_\_tid\_Object\_\_](ue_ue.Texture.md#__tid_object__)
- [\_\_tid\_StreamableRenderAsset\_\_](ue_ue.Texture.md#__tid_streamablerenderasset__)
- [\_\_tid\_Texture\_\_](ue_ue.Texture.md#__tid_texture__)
- [bAsyncResourceReleaseHasBeenStarted](ue_ue.Texture.md#basyncresourcereleasehasbeenstarted)
- [bCachedReadyForStreaming](ue_ue.Texture.md#bcachedreadyforstreaming)
- [bChromaKeyTexture](ue_ue.Texture.md#bchromakeytexture)
- [bDitherMipMapAlpha](ue_ue.Texture.md#bdithermipmapalpha)
- [bFlipGreenChannel](ue_ue.Texture.md#bflipgreenchannel)
- [bForceMiplevelsToBeResident](ue_ue.Texture.md#bforcemiplevelstoberesident)
- [bForcePVRTC4](ue_ue.Texture.md#bforcepvrtc4)
- [bGlobalForceMipLevelsToBeResident](ue_ue.Texture.md#bglobalforcemiplevelstoberesident)
- [bHasStreamingUpdatePending](ue_ue.Texture.md#bhasstreamingupdatepending)
- [bIgnoreStreamingMipBias](ue_ue.Texture.md#bignorestreamingmipbias)
- [bIsStreamable](ue_ue.Texture.md#bisstreamable)
- [bNoTiling](ue_ue.Texture.md#bnotiling)
- [bPreserveBorder](ue_ue.Texture.md#bpreserveborder)
- [bUseCinematicMipLevels](ue_ue.Texture.md#busecinematicmiplevels)
- [bUseLegacyGamma](ue_ue.Texture.md#buselegacygamma)

### Methods

- [CreateDefaultSubobject](ue_ue.Texture.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Texture.md#executeubergraph)
- [GetClass](ue_ue.Texture.md#getclass)
- [GetName](ue_ue.Texture.md#getname)
- [GetOuter](ue_ue.Texture.md#getouter)
- [GetWorld](ue_ue.Texture.md#getworld)
- [Find](ue_ue.Texture.md#find)
- [Load](ue_ue.Texture.md#load)
- [StaticClass](ue_ue.Texture.md#staticclass)

## Constructors

### constructor

• **new Texture**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[constructor](ue_ue.StreamableRenderAsset.md#constructor)

## Properties

### AdjustBrightness

• **AdjustBrightness**: `number`

___

### AdjustBrightnessCurve

• **AdjustBrightnessCurve**: `number`

___

### AdjustHue

• **AdjustHue**: `number`

___

### AdjustMaxAlpha

• **AdjustMaxAlpha**: `number`

___

### AdjustMinAlpha

• **AdjustMinAlpha**: `number`

___

### AdjustRGBCurve

• **AdjustRGBCurve**: `number`

___

### AdjustSaturation

• **AdjustSaturation**: `number`

___

### AdjustVibrance

• **AdjustVibrance**: `number`

___

### AlphaCoverageThresholds

• **AlphaCoverageThresholds**: [`Vector4`](ue_ue_s.Vector4.md)

___

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

___

### CachedCombinedLODBias

• **CachedCombinedLODBias**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[CachedCombinedLODBias](ue_ue.StreamableRenderAsset.md#cachedcombinedlodbias)

___

### CachedNumResidentLODs

• **CachedNumResidentLODs**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[CachedNumResidentLODs](ue_ue.StreamableRenderAsset.md#cachednumresidentlods)

___

### ChromaKeyColor

• **ChromaKeyColor**: [`Color`](ue_ue_s.Color.md)

___

### ChromaKeyThreshold

• **ChromaKeyThreshold**: `number`

___

### CompositePower

• **CompositePower**: `number`

___

### CompositeTexture

• **CompositeTexture**: [`Texture`](ue_ue.Texture.md)

___

### CompositeTextureMode

• **CompositeTextureMode**: [`ECompositeTextureMode`](../enums/ue_ue.ECompositeTextureMode.md)

___

### CompressionNoAlpha

• **CompressionNoAlpha**: `boolean`

___

### CompressionNone

• **CompressionNone**: `boolean`

___

### CompressionQuality

• **CompressionQuality**: [`ETextureCompressionQuality`](../enums/ue_ue.ETextureCompressionQuality.md)

___

### CompressionSettings

• **CompressionSettings**: [`TextureCompressionSettings`](../enums/ue_ue.TextureCompressionSettings.md)

___

### CompressionYCoCg

• **CompressionYCoCg**: `boolean`

___

### DeferCompression

• **DeferCompression**: `boolean`

___

### Filter

• **Filter**: [`TextureFilter`](../enums/ue_ue.TextureFilter.md)

___

### ForceMipLevelsToBeResidentTimestamp

• **ForceMipLevelsToBeResidentTimestamp**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[ForceMipLevelsToBeResidentTimestamp](ue_ue.StreamableRenderAsset.md#forcemiplevelstoberesidenttimestamp)

___

### LODBias

• **LODBias**: `number`

___

### LODGroup

• **LODGroup**: [`TextureGroup`](../enums/ue_ue.TextureGroup.md)

___

### LayerFormatSettings

• **LayerFormatSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TextureFormatSettings`](ue_ue.TextureFormatSettings.md)\>

___

### LightingGuid

• **LightingGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### LossyCompressionAmount

• **LossyCompressionAmount**: [`ETextureLossyCompressionAmount`](../enums/ue_ue.ETextureLossyCompressionAmount.md)

___

### MaxTextureSize

• **MaxTextureSize**: `number`

___

### MipGenSettings

• **MipGenSettings**: [`TextureMipGenSettings`](../enums/ue_ue.TextureMipGenSettings.md)

___

### MipLoadOptions

• **MipLoadOptions**: [`ETextureMipLoadOptions`](../enums/ue_ue.ETextureMipLoadOptions.md)

___

### NeverStream

• **NeverStream**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[NeverStream](ue_ue.StreamableRenderAsset.md#neverstream)

___

### NumCinematicMipLevels

• **NumCinematicMipLevels**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[NumCinematicMipLevels](ue_ue.StreamableRenderAsset.md#numcinematicmiplevels)

___

### PaddingColor

• **PaddingColor**: [`Color`](ue_ue_s.Color.md)

___

### PowerOfTwoMode

• **PowerOfTwoMode**: [`ETexturePowerOfTwoSetting`](../enums/ue_ue.ETexturePowerOfTwoSetting.md)

___

### SRGB

• **SRGB**: `boolean`

___

### Source

• **Source**: [`TextureSource`](ue_ue.TextureSource.md)

___

### SourceFilePath

• **SourceFilePath**: `string`

___

### StreamingIndex

• **StreamingIndex**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[StreamingIndex](ue_ue.StreamableRenderAsset.md#streamingindex)

___

### VirtualTextureStreaming

• **VirtualTextureStreaming**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[__tid_Object__](ue_ue.StreamableRenderAsset.md#__tid_object__)

___

### \_\_tid\_StreamableRenderAsset\_\_

• **\_\_tid\_StreamableRenderAsset\_\_**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[__tid_StreamableRenderAsset__](ue_ue.StreamableRenderAsset.md#__tid_streamablerenderasset__)

___

### \_\_tid\_Texture\_\_

• **\_\_tid\_Texture\_\_**: `boolean`

___

### bAsyncResourceReleaseHasBeenStarted

• **bAsyncResourceReleaseHasBeenStarted**: `boolean`

___

### bCachedReadyForStreaming

• **bCachedReadyForStreaming**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bCachedReadyForStreaming](ue_ue.StreamableRenderAsset.md#bcachedreadyforstreaming)

___

### bChromaKeyTexture

• **bChromaKeyTexture**: `boolean`

___

### bDitherMipMapAlpha

• **bDitherMipMapAlpha**: `boolean`

___

### bFlipGreenChannel

• **bFlipGreenChannel**: `boolean`

___

### bForceMiplevelsToBeResident

• **bForceMiplevelsToBeResident**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bForceMiplevelsToBeResident](ue_ue.StreamableRenderAsset.md#bforcemiplevelstoberesident)

___

### bForcePVRTC4

• **bForcePVRTC4**: `boolean`

___

### bGlobalForceMipLevelsToBeResident

• **bGlobalForceMipLevelsToBeResident**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bGlobalForceMipLevelsToBeResident](ue_ue.StreamableRenderAsset.md#bglobalforcemiplevelstoberesident)

___

### bHasStreamingUpdatePending

• **bHasStreamingUpdatePending**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bHasStreamingUpdatePending](ue_ue.StreamableRenderAsset.md#bhasstreamingupdatepending)

___

### bIgnoreStreamingMipBias

• **bIgnoreStreamingMipBias**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bIgnoreStreamingMipBias](ue_ue.StreamableRenderAsset.md#bignorestreamingmipbias)

___

### bIsStreamable

• **bIsStreamable**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bIsStreamable](ue_ue.StreamableRenderAsset.md#bisstreamable)

___

### bNoTiling

• **bNoTiling**: `boolean`

___

### bPreserveBorder

• **bPreserveBorder**: `boolean`

___

### bUseCinematicMipLevels

• **bUseCinematicMipLevels**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bUseCinematicMipLevels](ue_ue.StreamableRenderAsset.md#busecinematicmiplevels)

___

### bUseLegacyGamma

• **bUseLegacyGamma**: `boolean`

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

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[CreateDefaultSubobject](ue_ue.StreamableRenderAsset.md#createdefaultsubobject)

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

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[ExecuteUbergraph](ue_ue.StreamableRenderAsset.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[GetClass](ue_ue.StreamableRenderAsset.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[GetName](ue_ue.StreamableRenderAsset.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[GetOuter](ue_ue.StreamableRenderAsset.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[GetWorld](ue_ue.StreamableRenderAsset.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Texture`](ue_ue.Texture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Texture`](ue_ue.Texture.md)

#### Overrides

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[Find](ue_ue.StreamableRenderAsset.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`Texture`](ue_ue.Texture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Texture`](ue_ue.Texture.md)

#### Overrides

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[Load](ue_ue.StreamableRenderAsset.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[StaticClass](ue_ue.StreamableRenderAsset.md#staticclass)
