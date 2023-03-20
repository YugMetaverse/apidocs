[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TextureRenderTargetCube

# Class: TextureRenderTargetCube

[ue/ue](../modules/ue_ue.md).TextureRenderTargetCube

## Hierarchy

- [`TextureRenderTarget`](ue_ue.TextureRenderTarget.md)

  ↳ **`TextureRenderTargetCube`**

## Table of contents

### Constructors

- [constructor](ue_ue.TextureRenderTargetCube.md#constructor)

### Properties

- [AdjustBrightness](ue_ue.TextureRenderTargetCube.md#adjustbrightness)
- [AdjustBrightnessCurve](ue_ue.TextureRenderTargetCube.md#adjustbrightnesscurve)
- [AdjustHue](ue_ue.TextureRenderTargetCube.md#adjusthue)
- [AdjustMaxAlpha](ue_ue.TextureRenderTargetCube.md#adjustmaxalpha)
- [AdjustMinAlpha](ue_ue.TextureRenderTargetCube.md#adjustminalpha)
- [AdjustRGBCurve](ue_ue.TextureRenderTargetCube.md#adjustrgbcurve)
- [AdjustSaturation](ue_ue.TextureRenderTargetCube.md#adjustsaturation)
- [AdjustVibrance](ue_ue.TextureRenderTargetCube.md#adjustvibrance)
- [AlphaCoverageThresholds](ue_ue.TextureRenderTargetCube.md#alphacoveragethresholds)
- [AssetImportData](ue_ue.TextureRenderTargetCube.md#assetimportdata)
- [AssetUserData](ue_ue.TextureRenderTargetCube.md#assetuserdata)
- [CachedCombinedLODBias](ue_ue.TextureRenderTargetCube.md#cachedcombinedlodbias)
- [CachedNumResidentLODs](ue_ue.TextureRenderTargetCube.md#cachednumresidentlods)
- [ChromaKeyColor](ue_ue.TextureRenderTargetCube.md#chromakeycolor)
- [ChromaKeyThreshold](ue_ue.TextureRenderTargetCube.md#chromakeythreshold)
- [ClearColor](ue_ue.TextureRenderTargetCube.md#clearcolor)
- [CompositePower](ue_ue.TextureRenderTargetCube.md#compositepower)
- [CompositeTexture](ue_ue.TextureRenderTargetCube.md#compositetexture)
- [CompositeTextureMode](ue_ue.TextureRenderTargetCube.md#compositetexturemode)
- [CompressionNoAlpha](ue_ue.TextureRenderTargetCube.md#compressionnoalpha)
- [CompressionNone](ue_ue.TextureRenderTargetCube.md#compressionnone)
- [CompressionQuality](ue_ue.TextureRenderTargetCube.md#compressionquality)
- [CompressionSettings](ue_ue.TextureRenderTargetCube.md#compressionsettings)
- [CompressionYCoCg](ue_ue.TextureRenderTargetCube.md#compressionycocg)
- [DeferCompression](ue_ue.TextureRenderTargetCube.md#defercompression)
- [Filter](ue_ue.TextureRenderTargetCube.md#filter)
- [ForceMipLevelsToBeResidentTimestamp](ue_ue.TextureRenderTargetCube.md#forcemiplevelstoberesidenttimestamp)
- [LODBias](ue_ue.TextureRenderTargetCube.md#lodbias)
- [LODGroup](ue_ue.TextureRenderTargetCube.md#lodgroup)
- [LayerFormatSettings](ue_ue.TextureRenderTargetCube.md#layerformatsettings)
- [LightingGuid](ue_ue.TextureRenderTargetCube.md#lightingguid)
- [LossyCompressionAmount](ue_ue.TextureRenderTargetCube.md#lossycompressionamount)
- [MaxTextureSize](ue_ue.TextureRenderTargetCube.md#maxtexturesize)
- [MipGenSettings](ue_ue.TextureRenderTargetCube.md#mipgensettings)
- [MipLoadOptions](ue_ue.TextureRenderTargetCube.md#miploadoptions)
- [NeverStream](ue_ue.TextureRenderTargetCube.md#neverstream)
- [NumCinematicMipLevels](ue_ue.TextureRenderTargetCube.md#numcinematicmiplevels)
- [OverrideFormat](ue_ue.TextureRenderTargetCube.md#overrideformat)
- [PaddingColor](ue_ue.TextureRenderTargetCube.md#paddingcolor)
- [PowerOfTwoMode](ue_ue.TextureRenderTargetCube.md#poweroftwomode)
- [SRGB](ue_ue.TextureRenderTargetCube.md#srgb)
- [SizeX](ue_ue.TextureRenderTargetCube.md#sizex)
- [Source](ue_ue.TextureRenderTargetCube.md#source)
- [SourceFilePath](ue_ue.TextureRenderTargetCube.md#sourcefilepath)
- [StreamingIndex](ue_ue.TextureRenderTargetCube.md#streamingindex)
- [TargetGamma](ue_ue.TextureRenderTargetCube.md#targetgamma)
- [VirtualTextureStreaming](ue_ue.TextureRenderTargetCube.md#virtualtexturestreaming)
- [\_\_tid\_Object\_\_](ue_ue.TextureRenderTargetCube.md#__tid_object__)
- [\_\_tid\_StreamableRenderAsset\_\_](ue_ue.TextureRenderTargetCube.md#__tid_streamablerenderasset__)
- [\_\_tid\_TextureRenderTargetCube\_\_](ue_ue.TextureRenderTargetCube.md#__tid_texturerendertargetcube__)
- [\_\_tid\_TextureRenderTarget\_\_](ue_ue.TextureRenderTargetCube.md#__tid_texturerendertarget__)
- [\_\_tid\_Texture\_\_](ue_ue.TextureRenderTargetCube.md#__tid_texture__)
- [bAsyncResourceReleaseHasBeenStarted](ue_ue.TextureRenderTargetCube.md#basyncresourcereleasehasbeenstarted)
- [bCachedReadyForStreaming](ue_ue.TextureRenderTargetCube.md#bcachedreadyforstreaming)
- [bChromaKeyTexture](ue_ue.TextureRenderTargetCube.md#bchromakeytexture)
- [bDitherMipMapAlpha](ue_ue.TextureRenderTargetCube.md#bdithermipmapalpha)
- [bFlipGreenChannel](ue_ue.TextureRenderTargetCube.md#bflipgreenchannel)
- [bForceLinearGamma](ue_ue.TextureRenderTargetCube.md#bforcelineargamma)
- [bForceMiplevelsToBeResident](ue_ue.TextureRenderTargetCube.md#bforcemiplevelstoberesident)
- [bForcePVRTC4](ue_ue.TextureRenderTargetCube.md#bforcepvrtc4)
- [bGlobalForceMipLevelsToBeResident](ue_ue.TextureRenderTargetCube.md#bglobalforcemiplevelstoberesident)
- [bHDR](ue_ue.TextureRenderTargetCube.md#bhdr)
- [bHasStreamingUpdatePending](ue_ue.TextureRenderTargetCube.md#bhasstreamingupdatepending)
- [bIgnoreStreamingMipBias](ue_ue.TextureRenderTargetCube.md#bignorestreamingmipbias)
- [bIsStreamable](ue_ue.TextureRenderTargetCube.md#bisstreamable)
- [bNoTiling](ue_ue.TextureRenderTargetCube.md#bnotiling)
- [bPreserveBorder](ue_ue.TextureRenderTargetCube.md#bpreserveborder)
- [bUseCinematicMipLevels](ue_ue.TextureRenderTargetCube.md#busecinematicmiplevels)
- [bUseLegacyGamma](ue_ue.TextureRenderTargetCube.md#buselegacygamma)

### Methods

- [CreateDefaultSubobject](ue_ue.TextureRenderTargetCube.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TextureRenderTargetCube.md#executeubergraph)
- [GetClass](ue_ue.TextureRenderTargetCube.md#getclass)
- [GetName](ue_ue.TextureRenderTargetCube.md#getname)
- [GetOuter](ue_ue.TextureRenderTargetCube.md#getouter)
- [GetWorld](ue_ue.TextureRenderTargetCube.md#getworld)
- [Find](ue_ue.TextureRenderTargetCube.md#find)
- [Load](ue_ue.TextureRenderTargetCube.md#load)
- [StaticClass](ue_ue.TextureRenderTargetCube.md#staticclass)

## Constructors

### constructor

• **new TextureRenderTargetCube**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[constructor](ue_ue.TextureRenderTarget.md#constructor)

## Properties

### AdjustBrightness

• **AdjustBrightness**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AdjustBrightness](ue_ue.TextureRenderTarget.md#adjustbrightness)

___

### AdjustBrightnessCurve

• **AdjustBrightnessCurve**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AdjustBrightnessCurve](ue_ue.TextureRenderTarget.md#adjustbrightnesscurve)

___

### AdjustHue

• **AdjustHue**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AdjustHue](ue_ue.TextureRenderTarget.md#adjusthue)

___

### AdjustMaxAlpha

• **AdjustMaxAlpha**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AdjustMaxAlpha](ue_ue.TextureRenderTarget.md#adjustmaxalpha)

___

### AdjustMinAlpha

• **AdjustMinAlpha**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AdjustMinAlpha](ue_ue.TextureRenderTarget.md#adjustminalpha)

___

### AdjustRGBCurve

• **AdjustRGBCurve**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AdjustRGBCurve](ue_ue.TextureRenderTarget.md#adjustrgbcurve)

___

### AdjustSaturation

• **AdjustSaturation**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AdjustSaturation](ue_ue.TextureRenderTarget.md#adjustsaturation)

___

### AdjustVibrance

• **AdjustVibrance**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AdjustVibrance](ue_ue.TextureRenderTarget.md#adjustvibrance)

___

### AlphaCoverageThresholds

• **AlphaCoverageThresholds**: [`Vector4`](ue_ue_s.Vector4.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AlphaCoverageThresholds](ue_ue.TextureRenderTarget.md#alphacoveragethresholds)

___

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AssetImportData](ue_ue.TextureRenderTarget.md#assetimportdata)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AssetUserData](ue_ue.TextureRenderTarget.md#assetuserdata)

___

### CachedCombinedLODBias

• **CachedCombinedLODBias**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[CachedCombinedLODBias](ue_ue.TextureRenderTarget.md#cachedcombinedlodbias)

___

### CachedNumResidentLODs

• **CachedNumResidentLODs**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[CachedNumResidentLODs](ue_ue.TextureRenderTarget.md#cachednumresidentlods)

___

### ChromaKeyColor

• **ChromaKeyColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[ChromaKeyColor](ue_ue.TextureRenderTarget.md#chromakeycolor)

___

### ChromaKeyThreshold

• **ChromaKeyThreshold**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[ChromaKeyThreshold](ue_ue.TextureRenderTarget.md#chromakeythreshold)

___

### ClearColor

• **ClearColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### CompositePower

• **CompositePower**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[CompositePower](ue_ue.TextureRenderTarget.md#compositepower)

___

### CompositeTexture

• **CompositeTexture**: [`Texture`](ue_ue.Texture.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[CompositeTexture](ue_ue.TextureRenderTarget.md#compositetexture)

___

### CompositeTextureMode

• **CompositeTextureMode**: [`ECompositeTextureMode`](../enums/ue_ue.ECompositeTextureMode.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[CompositeTextureMode](ue_ue.TextureRenderTarget.md#compositetexturemode)

___

### CompressionNoAlpha

• **CompressionNoAlpha**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[CompressionNoAlpha](ue_ue.TextureRenderTarget.md#compressionnoalpha)

___

### CompressionNone

• **CompressionNone**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[CompressionNone](ue_ue.TextureRenderTarget.md#compressionnone)

___

### CompressionQuality

• **CompressionQuality**: [`ETextureCompressionQuality`](../enums/ue_ue.ETextureCompressionQuality.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[CompressionQuality](ue_ue.TextureRenderTarget.md#compressionquality)

___

### CompressionSettings

• **CompressionSettings**: [`TextureCompressionSettings`](../enums/ue_ue.TextureCompressionSettings.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[CompressionSettings](ue_ue.TextureRenderTarget.md#compressionsettings)

___

### CompressionYCoCg

• **CompressionYCoCg**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[CompressionYCoCg](ue_ue.TextureRenderTarget.md#compressionycocg)

___

### DeferCompression

• **DeferCompression**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[DeferCompression](ue_ue.TextureRenderTarget.md#defercompression)

___

### Filter

• **Filter**: [`TextureFilter`](../enums/ue_ue.TextureFilter.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[Filter](ue_ue.TextureRenderTarget.md#filter)

___

### ForceMipLevelsToBeResidentTimestamp

• **ForceMipLevelsToBeResidentTimestamp**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[ForceMipLevelsToBeResidentTimestamp](ue_ue.TextureRenderTarget.md#forcemiplevelstoberesidenttimestamp)

___

### LODBias

• **LODBias**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[LODBias](ue_ue.TextureRenderTarget.md#lodbias)

___

### LODGroup

• **LODGroup**: [`TextureGroup`](../enums/ue_ue.TextureGroup.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[LODGroup](ue_ue.TextureRenderTarget.md#lodgroup)

___

### LayerFormatSettings

• **LayerFormatSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TextureFormatSettings`](ue_ue.TextureFormatSettings.md)\>

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[LayerFormatSettings](ue_ue.TextureRenderTarget.md#layerformatsettings)

___

### LightingGuid

• **LightingGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[LightingGuid](ue_ue.TextureRenderTarget.md#lightingguid)

___

### LossyCompressionAmount

• **LossyCompressionAmount**: [`ETextureLossyCompressionAmount`](../enums/ue_ue.ETextureLossyCompressionAmount.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[LossyCompressionAmount](ue_ue.TextureRenderTarget.md#lossycompressionamount)

___

### MaxTextureSize

• **MaxTextureSize**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[MaxTextureSize](ue_ue.TextureRenderTarget.md#maxtexturesize)

___

### MipGenSettings

• **MipGenSettings**: [`TextureMipGenSettings`](../enums/ue_ue.TextureMipGenSettings.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[MipGenSettings](ue_ue.TextureRenderTarget.md#mipgensettings)

___

### MipLoadOptions

• **MipLoadOptions**: [`ETextureMipLoadOptions`](../enums/ue_ue.ETextureMipLoadOptions.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[MipLoadOptions](ue_ue.TextureRenderTarget.md#miploadoptions)

___

### NeverStream

• **NeverStream**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[NeverStream](ue_ue.TextureRenderTarget.md#neverstream)

___

### NumCinematicMipLevels

• **NumCinematicMipLevels**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[NumCinematicMipLevels](ue_ue.TextureRenderTarget.md#numcinematicmiplevels)

___

### OverrideFormat

• **OverrideFormat**: [`EPixelFormat`](../enums/ue_ue.EPixelFormat.md)

___

### PaddingColor

• **PaddingColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[PaddingColor](ue_ue.TextureRenderTarget.md#paddingcolor)

___

### PowerOfTwoMode

• **PowerOfTwoMode**: [`ETexturePowerOfTwoSetting`](../enums/ue_ue.ETexturePowerOfTwoSetting.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[PowerOfTwoMode](ue_ue.TextureRenderTarget.md#poweroftwomode)

___

### SRGB

• **SRGB**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[SRGB](ue_ue.TextureRenderTarget.md#srgb)

___

### SizeX

• **SizeX**: `number`

___

### Source

• **Source**: [`TextureSource`](ue_ue.TextureSource.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[Source](ue_ue.TextureRenderTarget.md#source)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[SourceFilePath](ue_ue.TextureRenderTarget.md#sourcefilepath)

___

### StreamingIndex

• **StreamingIndex**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[StreamingIndex](ue_ue.TextureRenderTarget.md#streamingindex)

___

### TargetGamma

• **TargetGamma**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[TargetGamma](ue_ue.TextureRenderTarget.md#targetgamma)

___

### VirtualTextureStreaming

• **VirtualTextureStreaming**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[VirtualTextureStreaming](ue_ue.TextureRenderTarget.md#virtualtexturestreaming)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[__tid_Object__](ue_ue.TextureRenderTarget.md#__tid_object__)

___

### \_\_tid\_StreamableRenderAsset\_\_

• **\_\_tid\_StreamableRenderAsset\_\_**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[__tid_StreamableRenderAsset__](ue_ue.TextureRenderTarget.md#__tid_streamablerenderasset__)

___

### \_\_tid\_TextureRenderTargetCube\_\_

• **\_\_tid\_TextureRenderTargetCube\_\_**: `boolean`

___

### \_\_tid\_TextureRenderTarget\_\_

• **\_\_tid\_TextureRenderTarget\_\_**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[__tid_TextureRenderTarget__](ue_ue.TextureRenderTarget.md#__tid_texturerendertarget__)

___

### \_\_tid\_Texture\_\_

• **\_\_tid\_Texture\_\_**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[__tid_Texture__](ue_ue.TextureRenderTarget.md#__tid_texture__)

___

### bAsyncResourceReleaseHasBeenStarted

• **bAsyncResourceReleaseHasBeenStarted**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bAsyncResourceReleaseHasBeenStarted](ue_ue.TextureRenderTarget.md#basyncresourcereleasehasbeenstarted)

___

### bCachedReadyForStreaming

• **bCachedReadyForStreaming**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bCachedReadyForStreaming](ue_ue.TextureRenderTarget.md#bcachedreadyforstreaming)

___

### bChromaKeyTexture

• **bChromaKeyTexture**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bChromaKeyTexture](ue_ue.TextureRenderTarget.md#bchromakeytexture)

___

### bDitherMipMapAlpha

• **bDitherMipMapAlpha**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bDitherMipMapAlpha](ue_ue.TextureRenderTarget.md#bdithermipmapalpha)

___

### bFlipGreenChannel

• **bFlipGreenChannel**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bFlipGreenChannel](ue_ue.TextureRenderTarget.md#bflipgreenchannel)

___

### bForceLinearGamma

• **bForceLinearGamma**: `boolean`

___

### bForceMiplevelsToBeResident

• **bForceMiplevelsToBeResident**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bForceMiplevelsToBeResident](ue_ue.TextureRenderTarget.md#bforcemiplevelstoberesident)

___

### bForcePVRTC4

• **bForcePVRTC4**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bForcePVRTC4](ue_ue.TextureRenderTarget.md#bforcepvrtc4)

___

### bGlobalForceMipLevelsToBeResident

• **bGlobalForceMipLevelsToBeResident**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bGlobalForceMipLevelsToBeResident](ue_ue.TextureRenderTarget.md#bglobalforcemiplevelstoberesident)

___

### bHDR

• **bHDR**: `boolean`

___

### bHasStreamingUpdatePending

• **bHasStreamingUpdatePending**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bHasStreamingUpdatePending](ue_ue.TextureRenderTarget.md#bhasstreamingupdatepending)

___

### bIgnoreStreamingMipBias

• **bIgnoreStreamingMipBias**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bIgnoreStreamingMipBias](ue_ue.TextureRenderTarget.md#bignorestreamingmipbias)

___

### bIsStreamable

• **bIsStreamable**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bIsStreamable](ue_ue.TextureRenderTarget.md#bisstreamable)

___

### bNoTiling

• **bNoTiling**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bNoTiling](ue_ue.TextureRenderTarget.md#bnotiling)

___

### bPreserveBorder

• **bPreserveBorder**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bPreserveBorder](ue_ue.TextureRenderTarget.md#bpreserveborder)

___

### bUseCinematicMipLevels

• **bUseCinematicMipLevels**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bUseCinematicMipLevels](ue_ue.TextureRenderTarget.md#busecinematicmiplevels)

___

### bUseLegacyGamma

• **bUseLegacyGamma**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bUseLegacyGamma](ue_ue.TextureRenderTarget.md#buselegacygamma)

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

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[CreateDefaultSubobject](ue_ue.TextureRenderTarget.md#createdefaultsubobject)

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

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[ExecuteUbergraph](ue_ue.TextureRenderTarget.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[GetClass](ue_ue.TextureRenderTarget.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[GetName](ue_ue.TextureRenderTarget.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[GetOuter](ue_ue.TextureRenderTarget.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[GetWorld](ue_ue.TextureRenderTarget.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TextureRenderTargetCube`](ue_ue.TextureRenderTargetCube.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TextureRenderTargetCube`](ue_ue.TextureRenderTargetCube.md)

#### Overrides

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[Find](ue_ue.TextureRenderTarget.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TextureRenderTargetCube`](ue_ue.TextureRenderTargetCube.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TextureRenderTargetCube`](ue_ue.TextureRenderTargetCube.md)

#### Overrides

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[Load](ue_ue.TextureRenderTarget.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[StaticClass](ue_ue.TextureRenderTarget.md#staticclass)
