[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CanvasRenderTarget2D

# Class: CanvasRenderTarget2D

[ue/ue](../modules/ue_ue.md).CanvasRenderTarget2D

## Hierarchy

- [`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)

  ↳ **`CanvasRenderTarget2D`**

## Table of contents

### Constructors

- [constructor](ue_ue.CanvasRenderTarget2D.md#constructor)

### Properties

- [AddressX](ue_ue.CanvasRenderTarget2D.md#addressx)
- [AddressY](ue_ue.CanvasRenderTarget2D.md#addressy)
- [AdjustBrightness](ue_ue.CanvasRenderTarget2D.md#adjustbrightness)
- [AdjustBrightnessCurve](ue_ue.CanvasRenderTarget2D.md#adjustbrightnesscurve)
- [AdjustHue](ue_ue.CanvasRenderTarget2D.md#adjusthue)
- [AdjustMaxAlpha](ue_ue.CanvasRenderTarget2D.md#adjustmaxalpha)
- [AdjustMinAlpha](ue_ue.CanvasRenderTarget2D.md#adjustminalpha)
- [AdjustRGBCurve](ue_ue.CanvasRenderTarget2D.md#adjustrgbcurve)
- [AdjustSaturation](ue_ue.CanvasRenderTarget2D.md#adjustsaturation)
- [AdjustVibrance](ue_ue.CanvasRenderTarget2D.md#adjustvibrance)
- [AlphaCoverageThresholds](ue_ue.CanvasRenderTarget2D.md#alphacoveragethresholds)
- [AssetImportData](ue_ue.CanvasRenderTarget2D.md#assetimportdata)
- [AssetUserData](ue_ue.CanvasRenderTarget2D.md#assetuserdata)
- [CachedCombinedLODBias](ue_ue.CanvasRenderTarget2D.md#cachedcombinedlodbias)
- [CachedNumResidentLODs](ue_ue.CanvasRenderTarget2D.md#cachednumresidentlods)
- [ChromaKeyColor](ue_ue.CanvasRenderTarget2D.md#chromakeycolor)
- [ChromaKeyThreshold](ue_ue.CanvasRenderTarget2D.md#chromakeythreshold)
- [ClearColor](ue_ue.CanvasRenderTarget2D.md#clearcolor)
- [CompositePower](ue_ue.CanvasRenderTarget2D.md#compositepower)
- [CompositeTexture](ue_ue.CanvasRenderTarget2D.md#compositetexture)
- [CompositeTextureMode](ue_ue.CanvasRenderTarget2D.md#compositetexturemode)
- [CompressionNoAlpha](ue_ue.CanvasRenderTarget2D.md#compressionnoalpha)
- [CompressionNone](ue_ue.CanvasRenderTarget2D.md#compressionnone)
- [CompressionQuality](ue_ue.CanvasRenderTarget2D.md#compressionquality)
- [CompressionSettings](ue_ue.CanvasRenderTarget2D.md#compressionsettings)
- [CompressionYCoCg](ue_ue.CanvasRenderTarget2D.md#compressionycocg)
- [DeferCompression](ue_ue.CanvasRenderTarget2D.md#defercompression)
- [Filter](ue_ue.CanvasRenderTarget2D.md#filter)
- [ForceMipLevelsToBeResidentTimestamp](ue_ue.CanvasRenderTarget2D.md#forcemiplevelstoberesidenttimestamp)
- [LODBias](ue_ue.CanvasRenderTarget2D.md#lodbias)
- [LODGroup](ue_ue.CanvasRenderTarget2D.md#lodgroup)
- [LayerFormatSettings](ue_ue.CanvasRenderTarget2D.md#layerformatsettings)
- [LightingGuid](ue_ue.CanvasRenderTarget2D.md#lightingguid)
- [LossyCompressionAmount](ue_ue.CanvasRenderTarget2D.md#lossycompressionamount)
- [MaxTextureSize](ue_ue.CanvasRenderTarget2D.md#maxtexturesize)
- [MipGenSettings](ue_ue.CanvasRenderTarget2D.md#mipgensettings)
- [MipLoadOptions](ue_ue.CanvasRenderTarget2D.md#miploadoptions)
- [MipsAddressU](ue_ue.CanvasRenderTarget2D.md#mipsaddressu)
- [MipsAddressV](ue_ue.CanvasRenderTarget2D.md#mipsaddressv)
- [MipsSamplerFilter](ue_ue.CanvasRenderTarget2D.md#mipssamplerfilter)
- [NeverStream](ue_ue.CanvasRenderTarget2D.md#neverstream)
- [NumCinematicMipLevels](ue_ue.CanvasRenderTarget2D.md#numcinematicmiplevels)
- [OnCanvasRenderTargetUpdate](ue_ue.CanvasRenderTarget2D.md#oncanvasrendertargetupdate)
- [OverrideFormat](ue_ue.CanvasRenderTarget2D.md#overrideformat)
- [PaddingColor](ue_ue.CanvasRenderTarget2D.md#paddingcolor)
- [PowerOfTwoMode](ue_ue.CanvasRenderTarget2D.md#poweroftwomode)
- [RenderTargetFormat](ue_ue.CanvasRenderTarget2D.md#rendertargetformat)
- [SRGB](ue_ue.CanvasRenderTarget2D.md#srgb)
- [SizeX](ue_ue.CanvasRenderTarget2D.md#sizex)
- [SizeY](ue_ue.CanvasRenderTarget2D.md#sizey)
- [Source](ue_ue.CanvasRenderTarget2D.md#source)
- [SourceFilePath](ue_ue.CanvasRenderTarget2D.md#sourcefilepath)
- [StreamingIndex](ue_ue.CanvasRenderTarget2D.md#streamingindex)
- [TargetGamma](ue_ue.CanvasRenderTarget2D.md#targetgamma)
- [VirtualTextureStreaming](ue_ue.CanvasRenderTarget2D.md#virtualtexturestreaming)
- [World](ue_ue.CanvasRenderTarget2D.md#world)
- [\_\_tid\_CanvasRenderTarget2D\_\_](ue_ue.CanvasRenderTarget2D.md#__tid_canvasrendertarget2d__)
- [\_\_tid\_Object\_\_](ue_ue.CanvasRenderTarget2D.md#__tid_object__)
- [\_\_tid\_StreamableRenderAsset\_\_](ue_ue.CanvasRenderTarget2D.md#__tid_streamablerenderasset__)
- [\_\_tid\_TextureRenderTarget2D\_\_](ue_ue.CanvasRenderTarget2D.md#__tid_texturerendertarget2d__)
- [\_\_tid\_TextureRenderTarget\_\_](ue_ue.CanvasRenderTarget2D.md#__tid_texturerendertarget__)
- [\_\_tid\_Texture\_\_](ue_ue.CanvasRenderTarget2D.md#__tid_texture__)
- [bAsyncResourceReleaseHasBeenStarted](ue_ue.CanvasRenderTarget2D.md#basyncresourcereleasehasbeenstarted)
- [bAutoGenerateMips](ue_ue.CanvasRenderTarget2D.md#bautogeneratemips)
- [bCachedReadyForStreaming](ue_ue.CanvasRenderTarget2D.md#bcachedreadyforstreaming)
- [bChromaKeyTexture](ue_ue.CanvasRenderTarget2D.md#bchromakeytexture)
- [bDitherMipMapAlpha](ue_ue.CanvasRenderTarget2D.md#bdithermipmapalpha)
- [bFlipGreenChannel](ue_ue.CanvasRenderTarget2D.md#bflipgreenchannel)
- [bForceLinearGamma](ue_ue.CanvasRenderTarget2D.md#bforcelineargamma)
- [bForceMiplevelsToBeResident](ue_ue.CanvasRenderTarget2D.md#bforcemiplevelstoberesident)
- [bForcePVRTC4](ue_ue.CanvasRenderTarget2D.md#bforcepvrtc4)
- [bGPUSharedFlag](ue_ue.CanvasRenderTarget2D.md#bgpusharedflag)
- [bGlobalForceMipLevelsToBeResident](ue_ue.CanvasRenderTarget2D.md#bglobalforcemiplevelstoberesident)
- [bHDR](ue_ue.CanvasRenderTarget2D.md#bhdr)
- [bHasStreamingUpdatePending](ue_ue.CanvasRenderTarget2D.md#bhasstreamingupdatepending)
- [bIgnoreStreamingMipBias](ue_ue.CanvasRenderTarget2D.md#bignorestreamingmipbias)
- [bIsStreamable](ue_ue.CanvasRenderTarget2D.md#bisstreamable)
- [bNoTiling](ue_ue.CanvasRenderTarget2D.md#bnotiling)
- [bPreserveBorder](ue_ue.CanvasRenderTarget2D.md#bpreserveborder)
- [bShouldClearRenderTargetOnReceiveUpdate](ue_ue.CanvasRenderTarget2D.md#bshouldclearrendertargetonreceiveupdate)
- [bUseCinematicMipLevels](ue_ue.CanvasRenderTarget2D.md#busecinematicmiplevels)
- [bUseLegacyGamma](ue_ue.CanvasRenderTarget2D.md#buselegacygamma)

### Methods

- [CreateDefaultSubobject](ue_ue.CanvasRenderTarget2D.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.CanvasRenderTarget2D.md#executeubergraph)
- [GetClass](ue_ue.CanvasRenderTarget2D.md#getclass)
- [GetName](ue_ue.CanvasRenderTarget2D.md#getname)
- [GetOuter](ue_ue.CanvasRenderTarget2D.md#getouter)
- [GetSize](ue_ue.CanvasRenderTarget2D.md#getsize)
- [GetWorld](ue_ue.CanvasRenderTarget2D.md#getworld)
- [ReceiveUpdate](ue_ue.CanvasRenderTarget2D.md#receiveupdate)
- [UpdateResource](ue_ue.CanvasRenderTarget2D.md#updateresource)
- [CreateCanvasRenderTarget2D](ue_ue.CanvasRenderTarget2D.md#createcanvasrendertarget2d)
- [Find](ue_ue.CanvasRenderTarget2D.md#find)
- [Load](ue_ue.CanvasRenderTarget2D.md#load)
- [StaticClass](ue_ue.CanvasRenderTarget2D.md#staticclass)

## Constructors

### constructor

• **new CanvasRenderTarget2D**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[constructor](ue_ue.TextureRenderTarget2D.md#constructor)

## Properties

### AddressX

• **AddressX**: [`TextureAddress`](../enums/ue_ue.TextureAddress.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[AddressX](ue_ue.TextureRenderTarget2D.md#addressx)

___

### AddressY

• **AddressY**: [`TextureAddress`](../enums/ue_ue.TextureAddress.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[AddressY](ue_ue.TextureRenderTarget2D.md#addressy)

___

### AdjustBrightness

• **AdjustBrightness**: `number`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[AdjustBrightness](ue_ue.TextureRenderTarget2D.md#adjustbrightness)

___

### AdjustBrightnessCurve

• **AdjustBrightnessCurve**: `number`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[AdjustBrightnessCurve](ue_ue.TextureRenderTarget2D.md#adjustbrightnesscurve)

___

### AdjustHue

• **AdjustHue**: `number`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[AdjustHue](ue_ue.TextureRenderTarget2D.md#adjusthue)

___

### AdjustMaxAlpha

• **AdjustMaxAlpha**: `number`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[AdjustMaxAlpha](ue_ue.TextureRenderTarget2D.md#adjustmaxalpha)

___

### AdjustMinAlpha

• **AdjustMinAlpha**: `number`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[AdjustMinAlpha](ue_ue.TextureRenderTarget2D.md#adjustminalpha)

___

### AdjustRGBCurve

• **AdjustRGBCurve**: `number`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[AdjustRGBCurve](ue_ue.TextureRenderTarget2D.md#adjustrgbcurve)

___

### AdjustSaturation

• **AdjustSaturation**: `number`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[AdjustSaturation](ue_ue.TextureRenderTarget2D.md#adjustsaturation)

___

### AdjustVibrance

• **AdjustVibrance**: `number`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[AdjustVibrance](ue_ue.TextureRenderTarget2D.md#adjustvibrance)

___

### AlphaCoverageThresholds

• **AlphaCoverageThresholds**: [`Vector4`](ue_ue_s.Vector4.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[AlphaCoverageThresholds](ue_ue.TextureRenderTarget2D.md#alphacoveragethresholds)

___

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[AssetImportData](ue_ue.TextureRenderTarget2D.md#assetimportdata)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[AssetUserData](ue_ue.TextureRenderTarget2D.md#assetuserdata)

___

### CachedCombinedLODBias

• **CachedCombinedLODBias**: `number`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[CachedCombinedLODBias](ue_ue.TextureRenderTarget2D.md#cachedcombinedlodbias)

___

### CachedNumResidentLODs

• **CachedNumResidentLODs**: `number`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[CachedNumResidentLODs](ue_ue.TextureRenderTarget2D.md#cachednumresidentlods)

___

### ChromaKeyColor

• **ChromaKeyColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[ChromaKeyColor](ue_ue.TextureRenderTarget2D.md#chromakeycolor)

___

### ChromaKeyThreshold

• **ChromaKeyThreshold**: `number`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[ChromaKeyThreshold](ue_ue.TextureRenderTarget2D.md#chromakeythreshold)

___

### ClearColor

• **ClearColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[ClearColor](ue_ue.TextureRenderTarget2D.md#clearcolor)

___

### CompositePower

• **CompositePower**: `number`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[CompositePower](ue_ue.TextureRenderTarget2D.md#compositepower)

___

### CompositeTexture

• **CompositeTexture**: [`Texture`](ue_ue.Texture.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[CompositeTexture](ue_ue.TextureRenderTarget2D.md#compositetexture)

___

### CompositeTextureMode

• **CompositeTextureMode**: [`ECompositeTextureMode`](../enums/ue_ue.ECompositeTextureMode.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[CompositeTextureMode](ue_ue.TextureRenderTarget2D.md#compositetexturemode)

___

### CompressionNoAlpha

• **CompressionNoAlpha**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[CompressionNoAlpha](ue_ue.TextureRenderTarget2D.md#compressionnoalpha)

___

### CompressionNone

• **CompressionNone**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[CompressionNone](ue_ue.TextureRenderTarget2D.md#compressionnone)

___

### CompressionQuality

• **CompressionQuality**: [`ETextureCompressionQuality`](../enums/ue_ue.ETextureCompressionQuality.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[CompressionQuality](ue_ue.TextureRenderTarget2D.md#compressionquality)

___

### CompressionSettings

• **CompressionSettings**: [`TextureCompressionSettings`](../enums/ue_ue.TextureCompressionSettings.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[CompressionSettings](ue_ue.TextureRenderTarget2D.md#compressionsettings)

___

### CompressionYCoCg

• **CompressionYCoCg**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[CompressionYCoCg](ue_ue.TextureRenderTarget2D.md#compressionycocg)

___

### DeferCompression

• **DeferCompression**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[DeferCompression](ue_ue.TextureRenderTarget2D.md#defercompression)

___

### Filter

• **Filter**: [`TextureFilter`](../enums/ue_ue.TextureFilter.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[Filter](ue_ue.TextureRenderTarget2D.md#filter)

___

### ForceMipLevelsToBeResidentTimestamp

• **ForceMipLevelsToBeResidentTimestamp**: `number`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[ForceMipLevelsToBeResidentTimestamp](ue_ue.TextureRenderTarget2D.md#forcemiplevelstoberesidenttimestamp)

___

### LODBias

• **LODBias**: `number`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[LODBias](ue_ue.TextureRenderTarget2D.md#lodbias)

___

### LODGroup

• **LODGroup**: [`TextureGroup`](../enums/ue_ue.TextureGroup.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[LODGroup](ue_ue.TextureRenderTarget2D.md#lodgroup)

___

### LayerFormatSettings

• **LayerFormatSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TextureFormatSettings`](ue_ue.TextureFormatSettings.md)\>

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[LayerFormatSettings](ue_ue.TextureRenderTarget2D.md#layerformatsettings)

___

### LightingGuid

• **LightingGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[LightingGuid](ue_ue.TextureRenderTarget2D.md#lightingguid)

___

### LossyCompressionAmount

• **LossyCompressionAmount**: [`ETextureLossyCompressionAmount`](../enums/ue_ue.ETextureLossyCompressionAmount.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[LossyCompressionAmount](ue_ue.TextureRenderTarget2D.md#lossycompressionamount)

___

### MaxTextureSize

• **MaxTextureSize**: `number`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[MaxTextureSize](ue_ue.TextureRenderTarget2D.md#maxtexturesize)

___

### MipGenSettings

• **MipGenSettings**: [`TextureMipGenSettings`](../enums/ue_ue.TextureMipGenSettings.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[MipGenSettings](ue_ue.TextureRenderTarget2D.md#mipgensettings)

___

### MipLoadOptions

• **MipLoadOptions**: [`ETextureMipLoadOptions`](../enums/ue_ue.ETextureMipLoadOptions.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[MipLoadOptions](ue_ue.TextureRenderTarget2D.md#miploadoptions)

___

### MipsAddressU

• **MipsAddressU**: [`TextureAddress`](../enums/ue_ue.TextureAddress.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[MipsAddressU](ue_ue.TextureRenderTarget2D.md#mipsaddressu)

___

### MipsAddressV

• **MipsAddressV**: [`TextureAddress`](../enums/ue_ue.TextureAddress.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[MipsAddressV](ue_ue.TextureRenderTarget2D.md#mipsaddressv)

___

### MipsSamplerFilter

• **MipsSamplerFilter**: [`TextureFilter`](../enums/ue_ue.TextureFilter.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[MipsSamplerFilter](ue_ue.TextureRenderTarget2D.md#mipssamplerfilter)

___

### NeverStream

• **NeverStream**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[NeverStream](ue_ue.TextureRenderTarget2D.md#neverstream)

___

### NumCinematicMipLevels

• **NumCinematicMipLevels**: `number`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[NumCinematicMipLevels](ue_ue.TextureRenderTarget2D.md#numcinematicmiplevels)

___

### OnCanvasRenderTargetUpdate

• **OnCanvasRenderTargetUpdate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Canvas`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Canvas`](ue_ue.Canvas.md)\>, `Width`: `number`, `Height`: `number`) => `void`\>

___

### OverrideFormat

• **OverrideFormat**: [`EPixelFormat`](../enums/ue_ue.EPixelFormat.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[OverrideFormat](ue_ue.TextureRenderTarget2D.md#overrideformat)

___

### PaddingColor

• **PaddingColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[PaddingColor](ue_ue.TextureRenderTarget2D.md#paddingcolor)

___

### PowerOfTwoMode

• **PowerOfTwoMode**: [`ETexturePowerOfTwoSetting`](../enums/ue_ue.ETexturePowerOfTwoSetting.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[PowerOfTwoMode](ue_ue.TextureRenderTarget2D.md#poweroftwomode)

___

### RenderTargetFormat

• **RenderTargetFormat**: [`ETextureRenderTargetFormat`](../enums/ue_ue.ETextureRenderTargetFormat.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[RenderTargetFormat](ue_ue.TextureRenderTarget2D.md#rendertargetformat)

___

### SRGB

• **SRGB**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[SRGB](ue_ue.TextureRenderTarget2D.md#srgb)

___

### SizeX

• **SizeX**: `number`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[SizeX](ue_ue.TextureRenderTarget2D.md#sizex)

___

### SizeY

• **SizeY**: `number`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[SizeY](ue_ue.TextureRenderTarget2D.md#sizey)

___

### Source

• **Source**: [`TextureSource`](ue_ue.TextureSource.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[Source](ue_ue.TextureRenderTarget2D.md#source)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[SourceFilePath](ue_ue.TextureRenderTarget2D.md#sourcefilepath)

___

### StreamingIndex

• **StreamingIndex**: `number`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[StreamingIndex](ue_ue.TextureRenderTarget2D.md#streamingindex)

___

### TargetGamma

• **TargetGamma**: `number`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[TargetGamma](ue_ue.TextureRenderTarget2D.md#targetgamma)

___

### VirtualTextureStreaming

• **VirtualTextureStreaming**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[VirtualTextureStreaming](ue_ue.TextureRenderTarget2D.md#virtualtexturestreaming)

___

### World

• **World**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`World`](ue_ue.World.md)\>

___

### \_\_tid\_CanvasRenderTarget2D\_\_

• **\_\_tid\_CanvasRenderTarget2D\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[__tid_Object__](ue_ue.TextureRenderTarget2D.md#__tid_object__)

___

### \_\_tid\_StreamableRenderAsset\_\_

• **\_\_tid\_StreamableRenderAsset\_\_**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[__tid_StreamableRenderAsset__](ue_ue.TextureRenderTarget2D.md#__tid_streamablerenderasset__)

___

### \_\_tid\_TextureRenderTarget2D\_\_

• **\_\_tid\_TextureRenderTarget2D\_\_**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[__tid_TextureRenderTarget2D__](ue_ue.TextureRenderTarget2D.md#__tid_texturerendertarget2d__)

___

### \_\_tid\_TextureRenderTarget\_\_

• **\_\_tid\_TextureRenderTarget\_\_**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[__tid_TextureRenderTarget__](ue_ue.TextureRenderTarget2D.md#__tid_texturerendertarget__)

___

### \_\_tid\_Texture\_\_

• **\_\_tid\_Texture\_\_**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[__tid_Texture__](ue_ue.TextureRenderTarget2D.md#__tid_texture__)

___

### bAsyncResourceReleaseHasBeenStarted

• **bAsyncResourceReleaseHasBeenStarted**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[bAsyncResourceReleaseHasBeenStarted](ue_ue.TextureRenderTarget2D.md#basyncresourcereleasehasbeenstarted)

___

### bAutoGenerateMips

• **bAutoGenerateMips**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[bAutoGenerateMips](ue_ue.TextureRenderTarget2D.md#bautogeneratemips)

___

### bCachedReadyForStreaming

• **bCachedReadyForStreaming**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[bCachedReadyForStreaming](ue_ue.TextureRenderTarget2D.md#bcachedreadyforstreaming)

___

### bChromaKeyTexture

• **bChromaKeyTexture**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[bChromaKeyTexture](ue_ue.TextureRenderTarget2D.md#bchromakeytexture)

___

### bDitherMipMapAlpha

• **bDitherMipMapAlpha**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[bDitherMipMapAlpha](ue_ue.TextureRenderTarget2D.md#bdithermipmapalpha)

___

### bFlipGreenChannel

• **bFlipGreenChannel**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[bFlipGreenChannel](ue_ue.TextureRenderTarget2D.md#bflipgreenchannel)

___

### bForceLinearGamma

• **bForceLinearGamma**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[bForceLinearGamma](ue_ue.TextureRenderTarget2D.md#bforcelineargamma)

___

### bForceMiplevelsToBeResident

• **bForceMiplevelsToBeResident**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[bForceMiplevelsToBeResident](ue_ue.TextureRenderTarget2D.md#bforcemiplevelstoberesident)

___

### bForcePVRTC4

• **bForcePVRTC4**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[bForcePVRTC4](ue_ue.TextureRenderTarget2D.md#bforcepvrtc4)

___

### bGPUSharedFlag

• **bGPUSharedFlag**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[bGPUSharedFlag](ue_ue.TextureRenderTarget2D.md#bgpusharedflag)

___

### bGlobalForceMipLevelsToBeResident

• **bGlobalForceMipLevelsToBeResident**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[bGlobalForceMipLevelsToBeResident](ue_ue.TextureRenderTarget2D.md#bglobalforcemiplevelstoberesident)

___

### bHDR

• **bHDR**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[bHDR](ue_ue.TextureRenderTarget2D.md#bhdr)

___

### bHasStreamingUpdatePending

• **bHasStreamingUpdatePending**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[bHasStreamingUpdatePending](ue_ue.TextureRenderTarget2D.md#bhasstreamingupdatepending)

___

### bIgnoreStreamingMipBias

• **bIgnoreStreamingMipBias**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[bIgnoreStreamingMipBias](ue_ue.TextureRenderTarget2D.md#bignorestreamingmipbias)

___

### bIsStreamable

• **bIsStreamable**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[bIsStreamable](ue_ue.TextureRenderTarget2D.md#bisstreamable)

___

### bNoTiling

• **bNoTiling**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[bNoTiling](ue_ue.TextureRenderTarget2D.md#bnotiling)

___

### bPreserveBorder

• **bPreserveBorder**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[bPreserveBorder](ue_ue.TextureRenderTarget2D.md#bpreserveborder)

___

### bShouldClearRenderTargetOnReceiveUpdate

• **bShouldClearRenderTargetOnReceiveUpdate**: `boolean`

___

### bUseCinematicMipLevels

• **bUseCinematicMipLevels**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[bUseCinematicMipLevels](ue_ue.TextureRenderTarget2D.md#busecinematicmiplevels)

___

### bUseLegacyGamma

• **bUseLegacyGamma**: `boolean`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[bUseLegacyGamma](ue_ue.TextureRenderTarget2D.md#buselegacygamma)

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

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[CreateDefaultSubobject](ue_ue.TextureRenderTarget2D.md#createdefaultsubobject)

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

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[ExecuteUbergraph](ue_ue.TextureRenderTarget2D.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[GetClass](ue_ue.TextureRenderTarget2D.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[GetName](ue_ue.TextureRenderTarget2D.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[GetOuter](ue_ue.TextureRenderTarget2D.md#getouter)

___

### GetSize

▸ **GetSize**(`Width`, `Height`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Width` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `Height` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[GetWorld](ue_ue.TextureRenderTarget2D.md#getworld)

___

### ReceiveUpdate

▸ **ReceiveUpdate**(`Canvas`, `Width`, `Height`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Canvas` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Canvas`](ue_ue.Canvas.md)\> |
| `Width` | `number` |
| `Height` | `number` |

#### Returns

`void`

___

### UpdateResource

▸ **UpdateResource**(): `void`

#### Returns

`void`

___

### CreateCanvasRenderTarget2D

▸ `Static` **CreateCanvasRenderTarget2D**(`WorldContextObject`, `CanvasRenderTarget2DClass`, `Width?`, `Height?`): [`CanvasRenderTarget2D`](ue_ue.CanvasRenderTarget2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `CanvasRenderTarget2DClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `Width?` | `number` |
| `Height?` | `number` |

#### Returns

[`CanvasRenderTarget2D`](ue_ue.CanvasRenderTarget2D.md)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CanvasRenderTarget2D`](ue_ue.CanvasRenderTarget2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CanvasRenderTarget2D`](ue_ue.CanvasRenderTarget2D.md)

#### Overrides

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[Find](ue_ue.TextureRenderTarget2D.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`CanvasRenderTarget2D`](ue_ue.CanvasRenderTarget2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CanvasRenderTarget2D`](ue_ue.CanvasRenderTarget2D.md)

#### Overrides

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[Load](ue_ue.TextureRenderTarget2D.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[TextureRenderTarget2D](ue_ue.TextureRenderTarget2D.md).[StaticClass](ue_ue.TextureRenderTarget2D.md#staticclass)
