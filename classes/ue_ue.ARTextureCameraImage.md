[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARTextureCameraImage

# Class: ARTextureCameraImage

[ue/ue](../modules/ue_ue.md).ARTextureCameraImage

## Hierarchy

- [`ARTexture`](ue_ue.ARTexture.md)

  ↳ **`ARTextureCameraImage`**

## Table of contents

### Constructors

- [constructor](ue_ue.ARTextureCameraImage.md#constructor)

### Properties

- [AdjustBrightness](ue_ue.ARTextureCameraImage.md#adjustbrightness)
- [AdjustBrightnessCurve](ue_ue.ARTextureCameraImage.md#adjustbrightnesscurve)
- [AdjustHue](ue_ue.ARTextureCameraImage.md#adjusthue)
- [AdjustMaxAlpha](ue_ue.ARTextureCameraImage.md#adjustmaxalpha)
- [AdjustMinAlpha](ue_ue.ARTextureCameraImage.md#adjustminalpha)
- [AdjustRGBCurve](ue_ue.ARTextureCameraImage.md#adjustrgbcurve)
- [AdjustSaturation](ue_ue.ARTextureCameraImage.md#adjustsaturation)
- [AdjustVibrance](ue_ue.ARTextureCameraImage.md#adjustvibrance)
- [AlphaCoverageThresholds](ue_ue.ARTextureCameraImage.md#alphacoveragethresholds)
- [AssetImportData](ue_ue.ARTextureCameraImage.md#assetimportdata)
- [AssetUserData](ue_ue.ARTextureCameraImage.md#assetuserdata)
- [CachedCombinedLODBias](ue_ue.ARTextureCameraImage.md#cachedcombinedlodbias)
- [CachedNumResidentLODs](ue_ue.ARTextureCameraImage.md#cachednumresidentlods)
- [ChromaKeyColor](ue_ue.ARTextureCameraImage.md#chromakeycolor)
- [ChromaKeyThreshold](ue_ue.ARTextureCameraImage.md#chromakeythreshold)
- [CompositePower](ue_ue.ARTextureCameraImage.md#compositepower)
- [CompositeTexture](ue_ue.ARTextureCameraImage.md#compositetexture)
- [CompositeTextureMode](ue_ue.ARTextureCameraImage.md#compositetexturemode)
- [CompressionNoAlpha](ue_ue.ARTextureCameraImage.md#compressionnoalpha)
- [CompressionNone](ue_ue.ARTextureCameraImage.md#compressionnone)
- [CompressionQuality](ue_ue.ARTextureCameraImage.md#compressionquality)
- [CompressionSettings](ue_ue.ARTextureCameraImage.md#compressionsettings)
- [CompressionYCoCg](ue_ue.ARTextureCameraImage.md#compressionycocg)
- [DeferCompression](ue_ue.ARTextureCameraImage.md#defercompression)
- [ExternalTextureGuid](ue_ue.ARTextureCameraImage.md#externaltextureguid)
- [Filter](ue_ue.ARTextureCameraImage.md#filter)
- [ForceMipLevelsToBeResidentTimestamp](ue_ue.ARTextureCameraImage.md#forcemiplevelstoberesidenttimestamp)
- [LODBias](ue_ue.ARTextureCameraImage.md#lodbias)
- [LODGroup](ue_ue.ARTextureCameraImage.md#lodgroup)
- [LayerFormatSettings](ue_ue.ARTextureCameraImage.md#layerformatsettings)
- [LightingGuid](ue_ue.ARTextureCameraImage.md#lightingguid)
- [LossyCompressionAmount](ue_ue.ARTextureCameraImage.md#lossycompressionamount)
- [MaxTextureSize](ue_ue.ARTextureCameraImage.md#maxtexturesize)
- [MipGenSettings](ue_ue.ARTextureCameraImage.md#mipgensettings)
- [MipLoadOptions](ue_ue.ARTextureCameraImage.md#miploadoptions)
- [NeverStream](ue_ue.ARTextureCameraImage.md#neverstream)
- [NumCinematicMipLevels](ue_ue.ARTextureCameraImage.md#numcinematicmiplevels)
- [PaddingColor](ue_ue.ARTextureCameraImage.md#paddingcolor)
- [PowerOfTwoMode](ue_ue.ARTextureCameraImage.md#poweroftwomode)
- [SRGB](ue_ue.ARTextureCameraImage.md#srgb)
- [Size](ue_ue.ARTextureCameraImage.md#size)
- [Source](ue_ue.ARTextureCameraImage.md#source)
- [SourceFilePath](ue_ue.ARTextureCameraImage.md#sourcefilepath)
- [StreamingIndex](ue_ue.ARTextureCameraImage.md#streamingindex)
- [TextureType](ue_ue.ARTextureCameraImage.md#texturetype)
- [Timestamp](ue_ue.ARTextureCameraImage.md#timestamp)
- [VirtualTextureStreaming](ue_ue.ARTextureCameraImage.md#virtualtexturestreaming)
- [\_\_tid\_ARTextureCameraImage\_\_](ue_ue.ARTextureCameraImage.md#__tid_artexturecameraimage__)
- [\_\_tid\_ARTexture\_\_](ue_ue.ARTextureCameraImage.md#__tid_artexture__)
- [\_\_tid\_Object\_\_](ue_ue.ARTextureCameraImage.md#__tid_object__)
- [\_\_tid\_StreamableRenderAsset\_\_](ue_ue.ARTextureCameraImage.md#__tid_streamablerenderasset__)
- [\_\_tid\_Texture\_\_](ue_ue.ARTextureCameraImage.md#__tid_texture__)
- [bAsyncResourceReleaseHasBeenStarted](ue_ue.ARTextureCameraImage.md#basyncresourcereleasehasbeenstarted)
- [bCachedReadyForStreaming](ue_ue.ARTextureCameraImage.md#bcachedreadyforstreaming)
- [bChromaKeyTexture](ue_ue.ARTextureCameraImage.md#bchromakeytexture)
- [bDitherMipMapAlpha](ue_ue.ARTextureCameraImage.md#bdithermipmapalpha)
- [bFlipGreenChannel](ue_ue.ARTextureCameraImage.md#bflipgreenchannel)
- [bForceMiplevelsToBeResident](ue_ue.ARTextureCameraImage.md#bforcemiplevelstoberesident)
- [bForcePVRTC4](ue_ue.ARTextureCameraImage.md#bforcepvrtc4)
- [bGlobalForceMipLevelsToBeResident](ue_ue.ARTextureCameraImage.md#bglobalforcemiplevelstoberesident)
- [bHasStreamingUpdatePending](ue_ue.ARTextureCameraImage.md#bhasstreamingupdatepending)
- [bIgnoreStreamingMipBias](ue_ue.ARTextureCameraImage.md#bignorestreamingmipbias)
- [bIsStreamable](ue_ue.ARTextureCameraImage.md#bisstreamable)
- [bNoTiling](ue_ue.ARTextureCameraImage.md#bnotiling)
- [bPreserveBorder](ue_ue.ARTextureCameraImage.md#bpreserveborder)
- [bUseCinematicMipLevels](ue_ue.ARTextureCameraImage.md#busecinematicmiplevels)
- [bUseLegacyGamma](ue_ue.ARTextureCameraImage.md#buselegacygamma)

### Methods

- [CreateDefaultSubobject](ue_ue.ARTextureCameraImage.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ARTextureCameraImage.md#executeubergraph)
- [GetClass](ue_ue.ARTextureCameraImage.md#getclass)
- [GetName](ue_ue.ARTextureCameraImage.md#getname)
- [GetOuter](ue_ue.ARTextureCameraImage.md#getouter)
- [GetWorld](ue_ue.ARTextureCameraImage.md#getworld)
- [Find](ue_ue.ARTextureCameraImage.md#find)
- [Load](ue_ue.ARTextureCameraImage.md#load)
- [StaticClass](ue_ue.ARTextureCameraImage.md#staticclass)

## Constructors

### constructor

• **new ARTextureCameraImage**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ARTexture](ue_ue.ARTexture.md).[constructor](ue_ue.ARTexture.md#constructor)

#### Defined in

[ue/ue.d.ts:20941](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20941)

## Properties

### AdjustBrightness

• **AdjustBrightness**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AdjustBrightness](ue_ue.ARTexture.md#adjustbrightness)

#### Defined in

[ue/ue.d.ts:477](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L477)

___

### AdjustBrightnessCurve

• **AdjustBrightnessCurve**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AdjustBrightnessCurve](ue_ue.ARTexture.md#adjustbrightnesscurve)

#### Defined in

[ue/ue.d.ts:478](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L478)

___

### AdjustHue

• **AdjustHue**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AdjustHue](ue_ue.ARTexture.md#adjusthue)

#### Defined in

[ue/ue.d.ts:482](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L482)

___

### AdjustMaxAlpha

• **AdjustMaxAlpha**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AdjustMaxAlpha](ue_ue.ARTexture.md#adjustmaxalpha)

#### Defined in

[ue/ue.d.ts:484](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L484)

___

### AdjustMinAlpha

• **AdjustMinAlpha**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AdjustMinAlpha](ue_ue.ARTexture.md#adjustminalpha)

#### Defined in

[ue/ue.d.ts:483](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L483)

___

### AdjustRGBCurve

• **AdjustRGBCurve**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AdjustRGBCurve](ue_ue.ARTexture.md#adjustrgbcurve)

#### Defined in

[ue/ue.d.ts:481](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L481)

___

### AdjustSaturation

• **AdjustSaturation**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AdjustSaturation](ue_ue.ARTexture.md#adjustsaturation)

#### Defined in

[ue/ue.d.ts:480](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L480)

___

### AdjustVibrance

• **AdjustVibrance**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AdjustVibrance](ue_ue.ARTexture.md#adjustvibrance)

#### Defined in

[ue/ue.d.ts:479](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L479)

___

### AlphaCoverageThresholds

• **AlphaCoverageThresholds**: [`Vector4`](ue_ue_s.Vector4.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AlphaCoverageThresholds](ue_ue.ARTexture.md#alphacoveragethresholds)

#### Defined in

[ue/ue.d.ts:492](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L492)

___

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AssetImportData](ue_ue.ARTexture.md#assetimportdata)

#### Defined in

[ue/ue.d.ts:476](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L476)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[AssetUserData](ue_ue.ARTexture.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:517](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L517)

___

### CachedCombinedLODBias

• **CachedCombinedLODBias**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[CachedCombinedLODBias](ue_ue.ARTexture.md#cachedcombinedlodbias)

#### Defined in

[ue/ue.d.ts:387](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L387)

___

### CachedNumResidentLODs

• **CachedNumResidentLODs**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[CachedNumResidentLODs](ue_ue.ARTexture.md#cachednumresidentlods)

#### Defined in

[ue/ue.d.ts:388](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L388)

___

### ChromaKeyColor

• **ChromaKeyColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[ChromaKeyColor](ue_ue.ARTexture.md#chromakeycolor)

#### Defined in

[ue/ue.d.ts:500](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L500)

___

### ChromaKeyThreshold

• **ChromaKeyThreshold**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[ChromaKeyThreshold](ue_ue.ARTexture.md#chromakeythreshold)

#### Defined in

[ue/ue.d.ts:499](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L499)

___

### CompositePower

• **CompositePower**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[CompositePower](ue_ue.ARTexture.md#compositepower)

#### Defined in

[ue/ue.d.ts:504](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L504)

___

### CompositeTexture

• **CompositeTexture**: [`Texture`](ue_ue.Texture.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[CompositeTexture](ue_ue.ARTexture.md#compositetexture)

#### Defined in

[ue/ue.d.ts:502](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L502)

___

### CompositeTextureMode

• **CompositeTextureMode**: [`ECompositeTextureMode`](../enums/ue_ue.ECompositeTextureMode.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[CompositeTextureMode](ue_ue.ARTexture.md#compositetexturemode)

#### Defined in

[ue/ue.d.ts:503](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L503)

___

### CompressionNoAlpha

• **CompressionNoAlpha**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[CompressionNoAlpha](ue_ue.ARTexture.md#compressionnoalpha)

#### Defined in

[ue/ue.d.ts:485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L485)

___

### CompressionNone

• **CompressionNone**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[CompressionNone](ue_ue.ARTexture.md#compressionnone)

#### Defined in

[ue/ue.d.ts:486](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L486)

___

### CompressionQuality

• **CompressionQuality**: [`ETextureCompressionQuality`](../enums/ue_ue.ETextureCompressionQuality.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[CompressionQuality](ue_ue.ARTexture.md#compressionquality)

#### Defined in

[ue/ue.d.ts:490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L490)

___

### CompressionSettings

• **CompressionSettings**: [`TextureCompressionSettings`](../enums/ue_ue.TextureCompressionSettings.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[CompressionSettings](ue_ue.ARTexture.md#compressionsettings)

#### Defined in

[ue/ue.d.ts:507](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L507)

___

### CompressionYCoCg

• **CompressionYCoCg**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[CompressionYCoCg](ue_ue.ARTexture.md#compressionycocg)

#### Defined in

[ue/ue.d.ts:515](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L515)

___

### DeferCompression

• **DeferCompression**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[DeferCompression](ue_ue.ARTexture.md#defercompression)

#### Defined in

[ue/ue.d.ts:487](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L487)

___

### ExternalTextureGuid

• **ExternalTextureGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[ExternalTextureGuid](ue_ue.ARTexture.md#externaltextureguid)

#### Defined in

[ue/ue.d.ts:20931](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20931)

___

### Filter

• **Filter**: [`TextureFilter`](../enums/ue_ue.TextureFilter.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[Filter](ue_ue.ARTexture.md#filter)

#### Defined in

[ue/ue.d.ts:508](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L508)

___

### ForceMipLevelsToBeResidentTimestamp

• **ForceMipLevelsToBeResidentTimestamp**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[ForceMipLevelsToBeResidentTimestamp](ue_ue.ARTexture.md#forcemiplevelstoberesidenttimestamp)

#### Defined in

[ue/ue.d.ts:384](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L384)

___

### LODBias

• **LODBias**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[LODBias](ue_ue.ARTexture.md#lodbias)

#### Defined in

[ue/ue.d.ts:506](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L506)

___

### LODGroup

• **LODGroup**: [`TextureGroup`](../enums/ue_ue.TextureGroup.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[LODGroup](ue_ue.ARTexture.md#lodgroup)

#### Defined in

[ue/ue.d.ts:510](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L510)

___

### LayerFormatSettings

• **LayerFormatSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TextureFormatSettings`](ue_ue.TextureFormatSettings.md)\>

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[LayerFormatSettings](ue_ue.ARTexture.md#layerformatsettings)

#### Defined in

[ue/ue.d.ts:505](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L505)

___

### LightingGuid

• **LightingGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[LightingGuid](ue_ue.ARTexture.md#lightingguid)

#### Defined in

[ue/ue.d.ts:474](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L474)

___

### LossyCompressionAmount

• **LossyCompressionAmount**: [`ETextureLossyCompressionAmount`](../enums/ue_ue.ETextureLossyCompressionAmount.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[LossyCompressionAmount](ue_ue.ARTexture.md#lossycompressionamount)

#### Defined in

[ue/ue.d.ts:488](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L488)

___

### MaxTextureSize

• **MaxTextureSize**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[MaxTextureSize](ue_ue.ARTexture.md#maxtexturesize)

#### Defined in

[ue/ue.d.ts:489](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L489)

___

### MipGenSettings

• **MipGenSettings**: [`TextureMipGenSettings`](../enums/ue_ue.TextureMipGenSettings.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[MipGenSettings](ue_ue.ARTexture.md#mipgensettings)

#### Defined in

[ue/ue.d.ts:501](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L501)

___

### MipLoadOptions

• **MipLoadOptions**: [`ETextureMipLoadOptions`](../enums/ue_ue.ETextureMipLoadOptions.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[MipLoadOptions](ue_ue.ARTexture.md#miploadoptions)

#### Defined in

[ue/ue.d.ts:509](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L509)

___

### NeverStream

• **NeverStream**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[NeverStream](ue_ue.ARTexture.md#neverstream)

#### Defined in

[ue/ue.d.ts:390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L390)

___

### NumCinematicMipLevels

• **NumCinematicMipLevels**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[NumCinematicMipLevels](ue_ue.ARTexture.md#numcinematicmiplevels)

#### Defined in

[ue/ue.d.ts:385](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L385)

___

### PaddingColor

• **PaddingColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[PaddingColor](ue_ue.ARTexture.md#paddingcolor)

#### Defined in

[ue/ue.d.ts:497](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L497)

___

### PowerOfTwoMode

• **PowerOfTwoMode**: [`ETexturePowerOfTwoSetting`](../enums/ue_ue.ETexturePowerOfTwoSetting.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[PowerOfTwoMode](ue_ue.ARTexture.md#poweroftwomode)

#### Defined in

[ue/ue.d.ts:496](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L496)

___

### SRGB

• **SRGB**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[SRGB](ue_ue.ARTexture.md#srgb)

#### Defined in

[ue/ue.d.ts:511](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L511)

___

### Size

• **Size**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[Size](ue_ue.ARTexture.md#size)

#### Defined in

[ue/ue.d.ts:20932](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20932)

___

### Source

• **Source**: [`TextureSource`](ue_ue.TextureSource.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[Source](ue_ue.ARTexture.md#source)

#### Defined in

[ue/ue.d.ts:473](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L473)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[SourceFilePath](ue_ue.ARTexture.md#sourcefilepath)

#### Defined in

[ue/ue.d.ts:475](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L475)

___

### StreamingIndex

• **StreamingIndex**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[StreamingIndex](ue_ue.ARTexture.md#streamingindex)

#### Defined in

[ue/ue.d.ts:386](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L386)

___

### TextureType

• **TextureType**: [`EARTextureType`](../enums/ue_ue.EARTextureType.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[TextureType](ue_ue.ARTexture.md#texturetype)

#### Defined in

[ue/ue.d.ts:20929](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20929)

___

### Timestamp

• **Timestamp**: `number`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[Timestamp](ue_ue.ARTexture.md#timestamp)

#### Defined in

[ue/ue.d.ts:20930](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20930)

___

### VirtualTextureStreaming

• **VirtualTextureStreaming**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[VirtualTextureStreaming](ue_ue.ARTexture.md#virtualtexturestreaming)

#### Defined in

[ue/ue.d.ts:514](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L514)

___

### \_\_tid\_ARTextureCameraImage\_\_

• **\_\_tid\_ARTextureCameraImage\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:20946](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20946)

___

### \_\_tid\_ARTexture\_\_

• **\_\_tid\_ARTexture\_\_**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[__tid_ARTexture__](ue_ue.ARTexture.md#__tid_artexture__)

#### Defined in

[ue/ue.d.ts:20937](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20937)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[__tid_Object__](ue_ue.ARTexture.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_StreamableRenderAsset\_\_

• **\_\_tid\_StreamableRenderAsset\_\_**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[__tid_StreamableRenderAsset__](ue_ue.ARTexture.md#__tid_streamablerenderasset__)

#### Defined in

[ue/ue.d.ts:401](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L401)

___

### \_\_tid\_Texture\_\_

• **\_\_tid\_Texture\_\_**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[__tid_Texture__](ue_ue.ARTexture.md#__tid_texture__)

#### Defined in

[ue/ue.d.ts:522](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L522)

___

### bAsyncResourceReleaseHasBeenStarted

• **bAsyncResourceReleaseHasBeenStarted**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bAsyncResourceReleaseHasBeenStarted](ue_ue.ARTexture.md#basyncresourcereleasehasbeenstarted)

#### Defined in

[ue/ue.d.ts:516](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L516)

___

### bCachedReadyForStreaming

• **bCachedReadyForStreaming**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bCachedReadyForStreaming](ue_ue.ARTexture.md#bcachedreadyforstreaming)

#### Defined in

[ue/ue.d.ts:389](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L389)

___

### bChromaKeyTexture

• **bChromaKeyTexture**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bChromaKeyTexture](ue_ue.ARTexture.md#bchromakeytexture)

#### Defined in

[ue/ue.d.ts:498](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L498)

___

### bDitherMipMapAlpha

• **bDitherMipMapAlpha**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bDitherMipMapAlpha](ue_ue.ARTexture.md#bdithermipmapalpha)

#### Defined in

[ue/ue.d.ts:491](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L491)

___

### bFlipGreenChannel

• **bFlipGreenChannel**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bFlipGreenChannel](ue_ue.ARTexture.md#bflipgreenchannel)

#### Defined in

[ue/ue.d.ts:494](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L494)

___

### bForceMiplevelsToBeResident

• **bForceMiplevelsToBeResident**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bForceMiplevelsToBeResident](ue_ue.ARTexture.md#bforcemiplevelstoberesident)

#### Defined in

[ue/ue.d.ts:394](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L394)

___

### bForcePVRTC4

• **bForcePVRTC4**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bForcePVRTC4](ue_ue.ARTexture.md#bforcepvrtc4)

#### Defined in

[ue/ue.d.ts:495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L495)

___

### bGlobalForceMipLevelsToBeResident

• **bGlobalForceMipLevelsToBeResident**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bGlobalForceMipLevelsToBeResident](ue_ue.ARTexture.md#bglobalforcemiplevelstoberesident)

#### Defined in

[ue/ue.d.ts:391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L391)

___

### bHasStreamingUpdatePending

• **bHasStreamingUpdatePending**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bHasStreamingUpdatePending](ue_ue.ARTexture.md#bhasstreamingupdatepending)

#### Defined in

[ue/ue.d.ts:393](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L393)

___

### bIgnoreStreamingMipBias

• **bIgnoreStreamingMipBias**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bIgnoreStreamingMipBias](ue_ue.ARTexture.md#bignorestreamingmipbias)

#### Defined in

[ue/ue.d.ts:395](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L395)

___

### bIsStreamable

• **bIsStreamable**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bIsStreamable](ue_ue.ARTexture.md#bisstreamable)

#### Defined in

[ue/ue.d.ts:392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L392)

___

### bNoTiling

• **bNoTiling**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bNoTiling](ue_ue.ARTexture.md#bnotiling)

#### Defined in

[ue/ue.d.ts:513](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L513)

___

### bPreserveBorder

• **bPreserveBorder**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bPreserveBorder](ue_ue.ARTexture.md#bpreserveborder)

#### Defined in

[ue/ue.d.ts:493](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L493)

___

### bUseCinematicMipLevels

• **bUseCinematicMipLevels**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bUseCinematicMipLevels](ue_ue.ARTexture.md#busecinematicmiplevels)

#### Defined in

[ue/ue.d.ts:396](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L396)

___

### bUseLegacyGamma

• **bUseLegacyGamma**: `boolean`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[bUseLegacyGamma](ue_ue.ARTexture.md#buselegacygamma)

#### Defined in

[ue/ue.d.ts:512](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L512)

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

[ARTexture](ue_ue.ARTexture.md).[ExecuteUbergraph](ue_ue.ARTexture.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[GetClass](ue_ue.ARTexture.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[GetName](ue_ue.ARTexture.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[GetOuter](ue_ue.ARTexture.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ARTexture](ue_ue.ARTexture.md).[GetWorld](ue_ue.ARTexture.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ARTextureCameraImage`](ue_ue.ARTextureCameraImage.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ARTextureCameraImage`](ue_ue.ARTextureCameraImage.md)

#### Overrides

[ARTexture](ue_ue.ARTexture.md).[Find](ue_ue.ARTexture.md#find)

#### Defined in

[ue/ue.d.ts:20943](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20943)

___

### Load

▸ `Static` **Load**(`InName`): [`ARTextureCameraImage`](ue_ue.ARTextureCameraImage.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ARTextureCameraImage`](ue_ue.ARTextureCameraImage.md)

#### Overrides

[ARTexture](ue_ue.ARTexture.md).[Load](ue_ue.ARTexture.md#load)

#### Defined in

[ue/ue.d.ts:20944](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20944)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ARTexture](ue_ue.ARTexture.md).[StaticClass](ue_ue.ARTexture.md#staticclass)

#### Defined in

[ue/ue.d.ts:20942](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20942)
