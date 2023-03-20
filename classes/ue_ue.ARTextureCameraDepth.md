[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARTextureCameraDepth

# Class: ARTextureCameraDepth

[ue/ue](../modules/ue_ue.md).ARTextureCameraDepth

## Hierarchy

- [`ARTexture`](ue_ue.ARTexture.md)

  ↳ **`ARTextureCameraDepth`**

## Table of contents

### Constructors

- [constructor](ue_ue.ARTextureCameraDepth.md#constructor)

### Properties

- [AdjustBrightness](ue_ue.ARTextureCameraDepth.md#adjustbrightness)
- [AdjustBrightnessCurve](ue_ue.ARTextureCameraDepth.md#adjustbrightnesscurve)
- [AdjustHue](ue_ue.ARTextureCameraDepth.md#adjusthue)
- [AdjustMaxAlpha](ue_ue.ARTextureCameraDepth.md#adjustmaxalpha)
- [AdjustMinAlpha](ue_ue.ARTextureCameraDepth.md#adjustminalpha)
- [AdjustRGBCurve](ue_ue.ARTextureCameraDepth.md#adjustrgbcurve)
- [AdjustSaturation](ue_ue.ARTextureCameraDepth.md#adjustsaturation)
- [AdjustVibrance](ue_ue.ARTextureCameraDepth.md#adjustvibrance)
- [AlphaCoverageThresholds](ue_ue.ARTextureCameraDepth.md#alphacoveragethresholds)
- [AssetImportData](ue_ue.ARTextureCameraDepth.md#assetimportdata)
- [AssetUserData](ue_ue.ARTextureCameraDepth.md#assetuserdata)
- [CachedCombinedLODBias](ue_ue.ARTextureCameraDepth.md#cachedcombinedlodbias)
- [CachedNumResidentLODs](ue_ue.ARTextureCameraDepth.md#cachednumresidentlods)
- [ChromaKeyColor](ue_ue.ARTextureCameraDepth.md#chromakeycolor)
- [ChromaKeyThreshold](ue_ue.ARTextureCameraDepth.md#chromakeythreshold)
- [CompositePower](ue_ue.ARTextureCameraDepth.md#compositepower)
- [CompositeTexture](ue_ue.ARTextureCameraDepth.md#compositetexture)
- [CompositeTextureMode](ue_ue.ARTextureCameraDepth.md#compositetexturemode)
- [CompressionNoAlpha](ue_ue.ARTextureCameraDepth.md#compressionnoalpha)
- [CompressionNone](ue_ue.ARTextureCameraDepth.md#compressionnone)
- [CompressionQuality](ue_ue.ARTextureCameraDepth.md#compressionquality)
- [CompressionSettings](ue_ue.ARTextureCameraDepth.md#compressionsettings)
- [CompressionYCoCg](ue_ue.ARTextureCameraDepth.md#compressionycocg)
- [DeferCompression](ue_ue.ARTextureCameraDepth.md#defercompression)
- [DepthAccuracy](ue_ue.ARTextureCameraDepth.md#depthaccuracy)
- [DepthQuality](ue_ue.ARTextureCameraDepth.md#depthquality)
- [ExternalTextureGuid](ue_ue.ARTextureCameraDepth.md#externaltextureguid)
- [Filter](ue_ue.ARTextureCameraDepth.md#filter)
- [ForceMipLevelsToBeResidentTimestamp](ue_ue.ARTextureCameraDepth.md#forcemiplevelstoberesidenttimestamp)
- [LODBias](ue_ue.ARTextureCameraDepth.md#lodbias)
- [LODGroup](ue_ue.ARTextureCameraDepth.md#lodgroup)
- [LayerFormatSettings](ue_ue.ARTextureCameraDepth.md#layerformatsettings)
- [LightingGuid](ue_ue.ARTextureCameraDepth.md#lightingguid)
- [LossyCompressionAmount](ue_ue.ARTextureCameraDepth.md#lossycompressionamount)
- [MaxTextureSize](ue_ue.ARTextureCameraDepth.md#maxtexturesize)
- [MipGenSettings](ue_ue.ARTextureCameraDepth.md#mipgensettings)
- [MipLoadOptions](ue_ue.ARTextureCameraDepth.md#miploadoptions)
- [NeverStream](ue_ue.ARTextureCameraDepth.md#neverstream)
- [NumCinematicMipLevels](ue_ue.ARTextureCameraDepth.md#numcinematicmiplevels)
- [PaddingColor](ue_ue.ARTextureCameraDepth.md#paddingcolor)
- [PowerOfTwoMode](ue_ue.ARTextureCameraDepth.md#poweroftwomode)
- [SRGB](ue_ue.ARTextureCameraDepth.md#srgb)
- [Size](ue_ue.ARTextureCameraDepth.md#size)
- [Source](ue_ue.ARTextureCameraDepth.md#source)
- [SourceFilePath](ue_ue.ARTextureCameraDepth.md#sourcefilepath)
- [StreamingIndex](ue_ue.ARTextureCameraDepth.md#streamingindex)
- [TextureType](ue_ue.ARTextureCameraDepth.md#texturetype)
- [Timestamp](ue_ue.ARTextureCameraDepth.md#timestamp)
- [VirtualTextureStreaming](ue_ue.ARTextureCameraDepth.md#virtualtexturestreaming)
- [\_\_tid\_ARTextureCameraDepth\_\_](ue_ue.ARTextureCameraDepth.md#__tid_artexturecameradepth__)
- [\_\_tid\_ARTexture\_\_](ue_ue.ARTextureCameraDepth.md#__tid_artexture__)
- [\_\_tid\_Object\_\_](ue_ue.ARTextureCameraDepth.md#__tid_object__)
- [\_\_tid\_StreamableRenderAsset\_\_](ue_ue.ARTextureCameraDepth.md#__tid_streamablerenderasset__)
- [\_\_tid\_Texture\_\_](ue_ue.ARTextureCameraDepth.md#__tid_texture__)
- [bAsyncResourceReleaseHasBeenStarted](ue_ue.ARTextureCameraDepth.md#basyncresourcereleasehasbeenstarted)
- [bCachedReadyForStreaming](ue_ue.ARTextureCameraDepth.md#bcachedreadyforstreaming)
- [bChromaKeyTexture](ue_ue.ARTextureCameraDepth.md#bchromakeytexture)
- [bDitherMipMapAlpha](ue_ue.ARTextureCameraDepth.md#bdithermipmapalpha)
- [bFlipGreenChannel](ue_ue.ARTextureCameraDepth.md#bflipgreenchannel)
- [bForceMiplevelsToBeResident](ue_ue.ARTextureCameraDepth.md#bforcemiplevelstoberesident)
- [bForcePVRTC4](ue_ue.ARTextureCameraDepth.md#bforcepvrtc4)
- [bGlobalForceMipLevelsToBeResident](ue_ue.ARTextureCameraDepth.md#bglobalforcemiplevelstoberesident)
- [bHasStreamingUpdatePending](ue_ue.ARTextureCameraDepth.md#bhasstreamingupdatepending)
- [bIgnoreStreamingMipBias](ue_ue.ARTextureCameraDepth.md#bignorestreamingmipbias)
- [bIsStreamable](ue_ue.ARTextureCameraDepth.md#bisstreamable)
- [bIsTemporallySmoothed](ue_ue.ARTextureCameraDepth.md#bistemporallysmoothed)
- [bNoTiling](ue_ue.ARTextureCameraDepth.md#bnotiling)
- [bPreserveBorder](ue_ue.ARTextureCameraDepth.md#bpreserveborder)
- [bUseCinematicMipLevels](ue_ue.ARTextureCameraDepth.md#busecinematicmiplevels)
- [bUseLegacyGamma](ue_ue.ARTextureCameraDepth.md#buselegacygamma)

### Methods

- [CreateDefaultSubobject](ue_ue.ARTextureCameraDepth.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ARTextureCameraDepth.md#executeubergraph)
- [GetClass](ue_ue.ARTextureCameraDepth.md#getclass)
- [GetName](ue_ue.ARTextureCameraDepth.md#getname)
- [GetOuter](ue_ue.ARTextureCameraDepth.md#getouter)
- [GetWorld](ue_ue.ARTextureCameraDepth.md#getworld)
- [Find](ue_ue.ARTextureCameraDepth.md#find)
- [Load](ue_ue.ARTextureCameraDepth.md#load)
- [StaticClass](ue_ue.ARTextureCameraDepth.md#staticclass)

## Constructors

### constructor

• **new ARTextureCameraDepth**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ARTexture](ue_ue.ARTexture.md).[constructor](ue_ue.ARTexture.md#constructor)

## Properties

### AdjustBrightness

• **AdjustBrightness**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AdjustBrightness](ue_ue.ARTexture.md#adjustbrightness)

___

### AdjustBrightnessCurve

• **AdjustBrightnessCurve**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AdjustBrightnessCurve](ue_ue.ARTexture.md#adjustbrightnesscurve)

___

### AdjustHue

• **AdjustHue**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AdjustHue](ue_ue.ARTexture.md#adjusthue)

___

### AdjustMaxAlpha

• **AdjustMaxAlpha**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AdjustMaxAlpha](ue_ue.ARTexture.md#adjustmaxalpha)

___

### AdjustMinAlpha

• **AdjustMinAlpha**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AdjustMinAlpha](ue_ue.ARTexture.md#adjustminalpha)

___

### AdjustRGBCurve

• **AdjustRGBCurve**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AdjustRGBCurve](ue_ue.ARTexture.md#adjustrgbcurve)

___

### AdjustSaturation

• **AdjustSaturation**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AdjustSaturation](ue_ue.ARTexture.md#adjustsaturation)

___

### AdjustVibrance

• **AdjustVibrance**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AdjustVibrance](ue_ue.ARTexture.md#adjustvibrance)

___

### AlphaCoverageThresholds

• **AlphaCoverageThresholds**: [`Vector4`](ue_ue_s.Vector4.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AlphaCoverageThresholds](ue_ue.ARTexture.md#alphacoveragethresholds)

___

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AssetImportData](ue_ue.ARTexture.md#assetimportdata)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AssetUserData](ue_ue.ARTexture.md#assetuserdata)

___

### CachedCombinedLODBias

• **CachedCombinedLODBias**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[CachedCombinedLODBias](ue_ue.ARTexture.md#cachedcombinedlodbias)

___

### CachedNumResidentLODs

• **CachedNumResidentLODs**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[CachedNumResidentLODs](ue_ue.ARTexture.md#cachednumresidentlods)

___

### ChromaKeyColor

• **ChromaKeyColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[ChromaKeyColor](ue_ue.ARTexture.md#chromakeycolor)

___

### ChromaKeyThreshold

• **ChromaKeyThreshold**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[ChromaKeyThreshold](ue_ue.ARTexture.md#chromakeythreshold)

___

### CompositePower

• **CompositePower**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[CompositePower](ue_ue.ARTexture.md#compositepower)

___

### CompositeTexture

• **CompositeTexture**: [`Texture`](ue_ue.Texture.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[CompositeTexture](ue_ue.ARTexture.md#compositetexture)

___

### CompositeTextureMode

• **CompositeTextureMode**: [`ECompositeTextureMode`](../enums/ue_ue.ECompositeTextureMode.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[CompositeTextureMode](ue_ue.ARTexture.md#compositetexturemode)

___

### CompressionNoAlpha

• **CompressionNoAlpha**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[CompressionNoAlpha](ue_ue.ARTexture.md#compressionnoalpha)

___

### CompressionNone

• **CompressionNone**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[CompressionNone](ue_ue.ARTexture.md#compressionnone)

___

### CompressionQuality

• **CompressionQuality**: [`ETextureCompressionQuality`](../enums/ue_ue.ETextureCompressionQuality.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[CompressionQuality](ue_ue.ARTexture.md#compressionquality)

___

### CompressionSettings

• **CompressionSettings**: [`TextureCompressionSettings`](../enums/ue_ue.TextureCompressionSettings.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[CompressionSettings](ue_ue.ARTexture.md#compressionsettings)

___

### CompressionYCoCg

• **CompressionYCoCg**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[CompressionYCoCg](ue_ue.ARTexture.md#compressionycocg)

___

### DeferCompression

• **DeferCompression**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[DeferCompression](ue_ue.ARTexture.md#defercompression)

___

### DepthAccuracy

• **DepthAccuracy**: [`EARDepthAccuracy`](../enums/ue_ue.EARDepthAccuracy.md)

___

### DepthQuality

• **DepthQuality**: [`EARDepthQuality`](../enums/ue_ue.EARDepthQuality.md)

___

### ExternalTextureGuid

• **ExternalTextureGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[ExternalTextureGuid](ue_ue.ARTexture.md#externaltextureguid)

___

### Filter

• **Filter**: [`TextureFilter`](../enums/ue_ue.TextureFilter.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[Filter](ue_ue.ARTexture.md#filter)

___

### ForceMipLevelsToBeResidentTimestamp

• **ForceMipLevelsToBeResidentTimestamp**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[ForceMipLevelsToBeResidentTimestamp](ue_ue.ARTexture.md#forcemiplevelstoberesidenttimestamp)

___

### LODBias

• **LODBias**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[LODBias](ue_ue.ARTexture.md#lodbias)

___

### LODGroup

• **LODGroup**: [`TextureGroup`](../enums/ue_ue.TextureGroup.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[LODGroup](ue_ue.ARTexture.md#lodgroup)

___

### LayerFormatSettings

• **LayerFormatSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TextureFormatSettings`](ue_ue.TextureFormatSettings.md)\>

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[LayerFormatSettings](ue_ue.ARTexture.md#layerformatsettings)

___

### LightingGuid

• **LightingGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[LightingGuid](ue_ue.ARTexture.md#lightingguid)

___

### LossyCompressionAmount

• **LossyCompressionAmount**: [`ETextureLossyCompressionAmount`](../enums/ue_ue.ETextureLossyCompressionAmount.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[LossyCompressionAmount](ue_ue.ARTexture.md#lossycompressionamount)

___

### MaxTextureSize

• **MaxTextureSize**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[MaxTextureSize](ue_ue.ARTexture.md#maxtexturesize)

___

### MipGenSettings

• **MipGenSettings**: [`TextureMipGenSettings`](../enums/ue_ue.TextureMipGenSettings.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[MipGenSettings](ue_ue.ARTexture.md#mipgensettings)

___

### MipLoadOptions

• **MipLoadOptions**: [`ETextureMipLoadOptions`](../enums/ue_ue.ETextureMipLoadOptions.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[MipLoadOptions](ue_ue.ARTexture.md#miploadoptions)

___

### NeverStream

• **NeverStream**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[NeverStream](ue_ue.ARTexture.md#neverstream)

___

### NumCinematicMipLevels

• **NumCinematicMipLevels**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[NumCinematicMipLevels](ue_ue.ARTexture.md#numcinematicmiplevels)

___

### PaddingColor

• **PaddingColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[PaddingColor](ue_ue.ARTexture.md#paddingcolor)

___

### PowerOfTwoMode

• **PowerOfTwoMode**: [`ETexturePowerOfTwoSetting`](../enums/ue_ue.ETexturePowerOfTwoSetting.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[PowerOfTwoMode](ue_ue.ARTexture.md#poweroftwomode)

___

### SRGB

• **SRGB**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[SRGB](ue_ue.ARTexture.md#srgb)

___

### Size

• **Size**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[Size](ue_ue.ARTexture.md#size)

___

### Source

• **Source**: [`TextureSource`](ue_ue.TextureSource.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[Source](ue_ue.ARTexture.md#source)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[SourceFilePath](ue_ue.ARTexture.md#sourcefilepath)

___

### StreamingIndex

• **StreamingIndex**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[StreamingIndex](ue_ue.ARTexture.md#streamingindex)

___

### TextureType

• **TextureType**: [`EARTextureType`](../enums/ue_ue.EARTextureType.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[TextureType](ue_ue.ARTexture.md#texturetype)

___

### Timestamp

• **Timestamp**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[Timestamp](ue_ue.ARTexture.md#timestamp)

___

### VirtualTextureStreaming

• **VirtualTextureStreaming**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[VirtualTextureStreaming](ue_ue.ARTexture.md#virtualtexturestreaming)

___

### \_\_tid\_ARTextureCameraDepth\_\_

• **\_\_tid\_ARTextureCameraDepth\_\_**: `boolean`

___

### \_\_tid\_ARTexture\_\_

• **\_\_tid\_ARTexture\_\_**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[__tid_ARTexture__](ue_ue.ARTexture.md#__tid_artexture__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[__tid_Object__](ue_ue.ARTexture.md#__tid_object__)

___

### \_\_tid\_StreamableRenderAsset\_\_

• **\_\_tid\_StreamableRenderAsset\_\_**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[__tid_StreamableRenderAsset__](ue_ue.ARTexture.md#__tid_streamablerenderasset__)

___

### \_\_tid\_Texture\_\_

• **\_\_tid\_Texture\_\_**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[__tid_Texture__](ue_ue.ARTexture.md#__tid_texture__)

___

### bAsyncResourceReleaseHasBeenStarted

• **bAsyncResourceReleaseHasBeenStarted**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bAsyncResourceReleaseHasBeenStarted](ue_ue.ARTexture.md#basyncresourcereleasehasbeenstarted)

___

### bCachedReadyForStreaming

• **bCachedReadyForStreaming**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bCachedReadyForStreaming](ue_ue.ARTexture.md#bcachedreadyforstreaming)

___

### bChromaKeyTexture

• **bChromaKeyTexture**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bChromaKeyTexture](ue_ue.ARTexture.md#bchromakeytexture)

___

### bDitherMipMapAlpha

• **bDitherMipMapAlpha**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bDitherMipMapAlpha](ue_ue.ARTexture.md#bdithermipmapalpha)

___

### bFlipGreenChannel

• **bFlipGreenChannel**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bFlipGreenChannel](ue_ue.ARTexture.md#bflipgreenchannel)

___

### bForceMiplevelsToBeResident

• **bForceMiplevelsToBeResident**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bForceMiplevelsToBeResident](ue_ue.ARTexture.md#bforcemiplevelstoberesident)

___

### bForcePVRTC4

• **bForcePVRTC4**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bForcePVRTC4](ue_ue.ARTexture.md#bforcepvrtc4)

___

### bGlobalForceMipLevelsToBeResident

• **bGlobalForceMipLevelsToBeResident**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bGlobalForceMipLevelsToBeResident](ue_ue.ARTexture.md#bglobalforcemiplevelstoberesident)

___

### bHasStreamingUpdatePending

• **bHasStreamingUpdatePending**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bHasStreamingUpdatePending](ue_ue.ARTexture.md#bhasstreamingupdatepending)

___

### bIgnoreStreamingMipBias

• **bIgnoreStreamingMipBias**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bIgnoreStreamingMipBias](ue_ue.ARTexture.md#bignorestreamingmipbias)

___

### bIsStreamable

• **bIsStreamable**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bIsStreamable](ue_ue.ARTexture.md#bisstreamable)

___

### bIsTemporallySmoothed

• **bIsTemporallySmoothed**: `boolean`

___

### bNoTiling

• **bNoTiling**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bNoTiling](ue_ue.ARTexture.md#bnotiling)

___

### bPreserveBorder

• **bPreserveBorder**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bPreserveBorder](ue_ue.ARTexture.md#bpreserveborder)

___

### bUseCinematicMipLevels

• **bUseCinematicMipLevels**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bUseCinematicMipLevels](ue_ue.ARTexture.md#busecinematicmiplevels)

___

### bUseLegacyGamma

• **bUseLegacyGamma**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bUseLegacyGamma](ue_ue.ARTexture.md#buselegacygamma)

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

[ARTexture](ue_ue.ARTexture.md).[CreateDefaultSubobject](ue_ue.ARTexture.md#createdefaultsubobject)

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

[ARTexture](ue_ue.ARTexture.md).[ExecuteUbergraph](ue_ue.ARTexture.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[GetClass](ue_ue.ARTexture.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[GetName](ue_ue.ARTexture.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[GetOuter](ue_ue.ARTexture.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[GetWorld](ue_ue.ARTexture.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ARTextureCameraDepth`](ue_ue.ARTextureCameraDepth.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ARTextureCameraDepth`](ue_ue.ARTextureCameraDepth.md)

#### Overrides

[ARTexture](ue_ue.ARTexture.md).[Find](ue_ue.ARTexture.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ARTextureCameraDepth`](ue_ue.ARTextureCameraDepth.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ARTextureCameraDepth`](ue_ue.ARTextureCameraDepth.md)

#### Overrides

[ARTexture](ue_ue.ARTexture.md).[Load](ue_ue.ARTexture.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ARTexture](ue_ue.ARTexture.md).[StaticClass](ue_ue.ARTexture.md#staticclass)
