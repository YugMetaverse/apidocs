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

#### Defined in

[ue/ue.d.ts:59844](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59844)

## Properties

### AdjustBrightness

• **AdjustBrightness**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AdjustBrightness](ue_ue.TextureRenderTarget.md#adjustbrightness)

#### Defined in

[ue/ue.d.ts:477](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L477)

___

### AdjustBrightnessCurve

• **AdjustBrightnessCurve**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AdjustBrightnessCurve](ue_ue.TextureRenderTarget.md#adjustbrightnesscurve)

#### Defined in

[ue/ue.d.ts:478](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L478)

___

### AdjustHue

• **AdjustHue**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AdjustHue](ue_ue.TextureRenderTarget.md#adjusthue)

#### Defined in

[ue/ue.d.ts:482](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L482)

___

### AdjustMaxAlpha

• **AdjustMaxAlpha**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AdjustMaxAlpha](ue_ue.TextureRenderTarget.md#adjustmaxalpha)

#### Defined in

[ue/ue.d.ts:484](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L484)

___

### AdjustMinAlpha

• **AdjustMinAlpha**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AdjustMinAlpha](ue_ue.TextureRenderTarget.md#adjustminalpha)

#### Defined in

[ue/ue.d.ts:483](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L483)

___

### AdjustRGBCurve

• **AdjustRGBCurve**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AdjustRGBCurve](ue_ue.TextureRenderTarget.md#adjustrgbcurve)

#### Defined in

[ue/ue.d.ts:481](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L481)

___

### AdjustSaturation

• **AdjustSaturation**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AdjustSaturation](ue_ue.TextureRenderTarget.md#adjustsaturation)

#### Defined in

[ue/ue.d.ts:480](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L480)

___

### AdjustVibrance

• **AdjustVibrance**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AdjustVibrance](ue_ue.TextureRenderTarget.md#adjustvibrance)

#### Defined in

[ue/ue.d.ts:479](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L479)

___

### AlphaCoverageThresholds

• **AlphaCoverageThresholds**: [`Vector4`](ue_ue_s.Vector4.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AlphaCoverageThresholds](ue_ue.TextureRenderTarget.md#alphacoveragethresholds)

#### Defined in

[ue/ue.d.ts:492](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L492)

___

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AssetImportData](ue_ue.TextureRenderTarget.md#assetimportdata)

#### Defined in

[ue/ue.d.ts:476](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L476)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[AssetUserData](ue_ue.TextureRenderTarget.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:517](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L517)

___

### CachedCombinedLODBias

• **CachedCombinedLODBias**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[CachedCombinedLODBias](ue_ue.TextureRenderTarget.md#cachedcombinedlodbias)

#### Defined in

[ue/ue.d.ts:387](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L387)

___

### CachedNumResidentLODs

• **CachedNumResidentLODs**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[CachedNumResidentLODs](ue_ue.TextureRenderTarget.md#cachednumresidentlods)

#### Defined in

[ue/ue.d.ts:388](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L388)

___

### ChromaKeyColor

• **ChromaKeyColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[ChromaKeyColor](ue_ue.TextureRenderTarget.md#chromakeycolor)

#### Defined in

[ue/ue.d.ts:500](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L500)

___

### ChromaKeyThreshold

• **ChromaKeyThreshold**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[ChromaKeyThreshold](ue_ue.TextureRenderTarget.md#chromakeythreshold)

#### Defined in

[ue/ue.d.ts:499](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L499)

___

### ClearColor

• **ClearColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:59846](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59846)

___

### CompositePower

• **CompositePower**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[CompositePower](ue_ue.TextureRenderTarget.md#compositepower)

#### Defined in

[ue/ue.d.ts:504](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L504)

___

### CompositeTexture

• **CompositeTexture**: [`Texture`](ue_ue.Texture.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[CompositeTexture](ue_ue.TextureRenderTarget.md#compositetexture)

#### Defined in

[ue/ue.d.ts:502](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L502)

___

### CompositeTextureMode

• **CompositeTextureMode**: [`ECompositeTextureMode`](../enums/ue_ue.ECompositeTextureMode.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[CompositeTextureMode](ue_ue.TextureRenderTarget.md#compositetexturemode)

#### Defined in

[ue/ue.d.ts:503](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L503)

___

### CompressionNoAlpha

• **CompressionNoAlpha**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[CompressionNoAlpha](ue_ue.TextureRenderTarget.md#compressionnoalpha)

#### Defined in

[ue/ue.d.ts:485](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L485)

___

### CompressionNone

• **CompressionNone**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[CompressionNone](ue_ue.TextureRenderTarget.md#compressionnone)

#### Defined in

[ue/ue.d.ts:486](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L486)

___

### CompressionQuality

• **CompressionQuality**: [`ETextureCompressionQuality`](../enums/ue_ue.ETextureCompressionQuality.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[CompressionQuality](ue_ue.TextureRenderTarget.md#compressionquality)

#### Defined in

[ue/ue.d.ts:490](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L490)

___

### CompressionSettings

• **CompressionSettings**: [`TextureCompressionSettings`](../enums/ue_ue.TextureCompressionSettings.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[CompressionSettings](ue_ue.TextureRenderTarget.md#compressionsettings)

#### Defined in

[ue/ue.d.ts:507](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L507)

___

### CompressionYCoCg

• **CompressionYCoCg**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[CompressionYCoCg](ue_ue.TextureRenderTarget.md#compressionycocg)

#### Defined in

[ue/ue.d.ts:515](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L515)

___

### DeferCompression

• **DeferCompression**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[DeferCompression](ue_ue.TextureRenderTarget.md#defercompression)

#### Defined in

[ue/ue.d.ts:487](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L487)

___

### Filter

• **Filter**: [`TextureFilter`](../enums/ue_ue.TextureFilter.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[Filter](ue_ue.TextureRenderTarget.md#filter)

#### Defined in

[ue/ue.d.ts:508](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L508)

___

### ForceMipLevelsToBeResidentTimestamp

• **ForceMipLevelsToBeResidentTimestamp**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[ForceMipLevelsToBeResidentTimestamp](ue_ue.TextureRenderTarget.md#forcemiplevelstoberesidenttimestamp)

#### Defined in

[ue/ue.d.ts:384](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L384)

___

### LODBias

• **LODBias**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[LODBias](ue_ue.TextureRenderTarget.md#lodbias)

#### Defined in

[ue/ue.d.ts:506](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L506)

___

### LODGroup

• **LODGroup**: [`TextureGroup`](../enums/ue_ue.TextureGroup.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[LODGroup](ue_ue.TextureRenderTarget.md#lodgroup)

#### Defined in

[ue/ue.d.ts:510](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L510)

___

### LayerFormatSettings

• **LayerFormatSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TextureFormatSettings`](ue_ue.TextureFormatSettings.md)\>

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[LayerFormatSettings](ue_ue.TextureRenderTarget.md#layerformatsettings)

#### Defined in

[ue/ue.d.ts:505](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L505)

___

### LightingGuid

• **LightingGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[LightingGuid](ue_ue.TextureRenderTarget.md#lightingguid)

#### Defined in

[ue/ue.d.ts:474](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L474)

___

### LossyCompressionAmount

• **LossyCompressionAmount**: [`ETextureLossyCompressionAmount`](../enums/ue_ue.ETextureLossyCompressionAmount.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[LossyCompressionAmount](ue_ue.TextureRenderTarget.md#lossycompressionamount)

#### Defined in

[ue/ue.d.ts:488](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L488)

___

### MaxTextureSize

• **MaxTextureSize**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[MaxTextureSize](ue_ue.TextureRenderTarget.md#maxtexturesize)

#### Defined in

[ue/ue.d.ts:489](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L489)

___

### MipGenSettings

• **MipGenSettings**: [`TextureMipGenSettings`](../enums/ue_ue.TextureMipGenSettings.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[MipGenSettings](ue_ue.TextureRenderTarget.md#mipgensettings)

#### Defined in

[ue/ue.d.ts:501](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L501)

___

### MipLoadOptions

• **MipLoadOptions**: [`ETextureMipLoadOptions`](../enums/ue_ue.ETextureMipLoadOptions.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[MipLoadOptions](ue_ue.TextureRenderTarget.md#miploadoptions)

#### Defined in

[ue/ue.d.ts:509](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L509)

___

### NeverStream

• **NeverStream**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[NeverStream](ue_ue.TextureRenderTarget.md#neverstream)

#### Defined in

[ue/ue.d.ts:390](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L390)

___

### NumCinematicMipLevels

• **NumCinematicMipLevels**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[NumCinematicMipLevels](ue_ue.TextureRenderTarget.md#numcinematicmiplevels)

#### Defined in

[ue/ue.d.ts:385](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L385)

___

### OverrideFormat

• **OverrideFormat**: [`EPixelFormat`](../enums/ue_ue.EPixelFormat.md)

#### Defined in

[ue/ue.d.ts:59847](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59847)

___

### PaddingColor

• **PaddingColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[PaddingColor](ue_ue.TextureRenderTarget.md#paddingcolor)

#### Defined in

[ue/ue.d.ts:497](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L497)

___

### PowerOfTwoMode

• **PowerOfTwoMode**: [`ETexturePowerOfTwoSetting`](../enums/ue_ue.ETexturePowerOfTwoSetting.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[PowerOfTwoMode](ue_ue.TextureRenderTarget.md#poweroftwomode)

#### Defined in

[ue/ue.d.ts:496](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L496)

___

### SRGB

• **SRGB**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[SRGB](ue_ue.TextureRenderTarget.md#srgb)

#### Defined in

[ue/ue.d.ts:511](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L511)

___

### SizeX

• **SizeX**: `number`

#### Defined in

[ue/ue.d.ts:59845](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59845)

___

### Source

• **Source**: [`TextureSource`](ue_ue.TextureSource.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[Source](ue_ue.TextureRenderTarget.md#source)

#### Defined in

[ue/ue.d.ts:473](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L473)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[SourceFilePath](ue_ue.TextureRenderTarget.md#sourcefilepath)

#### Defined in

[ue/ue.d.ts:475](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L475)

___

### StreamingIndex

• **StreamingIndex**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[StreamingIndex](ue_ue.TextureRenderTarget.md#streamingindex)

#### Defined in

[ue/ue.d.ts:386](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L386)

___

### TargetGamma

• **TargetGamma**: `number`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[TargetGamma](ue_ue.TextureRenderTarget.md#targetgamma)

#### Defined in

[ue/ue.d.ts:26187](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26187)

___

### VirtualTextureStreaming

• **VirtualTextureStreaming**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[VirtualTextureStreaming](ue_ue.TextureRenderTarget.md#virtualtexturestreaming)

#### Defined in

[ue/ue.d.ts:514](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L514)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[__tid_Object__](ue_ue.TextureRenderTarget.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_StreamableRenderAsset\_\_

• **\_\_tid\_StreamableRenderAsset\_\_**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[__tid_StreamableRenderAsset__](ue_ue.TextureRenderTarget.md#__tid_streamablerenderasset__)

#### Defined in

[ue/ue.d.ts:401](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L401)

___

### \_\_tid\_TextureRenderTargetCube\_\_

• **\_\_tid\_TextureRenderTargetCube\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:59854](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59854)

___

### \_\_tid\_TextureRenderTarget\_\_

• **\_\_tid\_TextureRenderTarget\_\_**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[__tid_TextureRenderTarget__](ue_ue.TextureRenderTarget.md#__tid_texturerendertarget__)

#### Defined in

[ue/ue.d.ts:26192](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26192)

___

### \_\_tid\_Texture\_\_

• **\_\_tid\_Texture\_\_**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[__tid_Texture__](ue_ue.TextureRenderTarget.md#__tid_texture__)

#### Defined in

[ue/ue.d.ts:522](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L522)

___

### bAsyncResourceReleaseHasBeenStarted

• **bAsyncResourceReleaseHasBeenStarted**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bAsyncResourceReleaseHasBeenStarted](ue_ue.TextureRenderTarget.md#basyncresourcereleasehasbeenstarted)

#### Defined in

[ue/ue.d.ts:516](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L516)

___

### bCachedReadyForStreaming

• **bCachedReadyForStreaming**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bCachedReadyForStreaming](ue_ue.TextureRenderTarget.md#bcachedreadyforstreaming)

#### Defined in

[ue/ue.d.ts:389](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L389)

___

### bChromaKeyTexture

• **bChromaKeyTexture**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bChromaKeyTexture](ue_ue.TextureRenderTarget.md#bchromakeytexture)

#### Defined in

[ue/ue.d.ts:498](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L498)

___

### bDitherMipMapAlpha

• **bDitherMipMapAlpha**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bDitherMipMapAlpha](ue_ue.TextureRenderTarget.md#bdithermipmapalpha)

#### Defined in

[ue/ue.d.ts:491](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L491)

___

### bFlipGreenChannel

• **bFlipGreenChannel**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bFlipGreenChannel](ue_ue.TextureRenderTarget.md#bflipgreenchannel)

#### Defined in

[ue/ue.d.ts:494](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L494)

___

### bForceLinearGamma

• **bForceLinearGamma**: `boolean`

#### Defined in

[ue/ue.d.ts:59849](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59849)

___

### bForceMiplevelsToBeResident

• **bForceMiplevelsToBeResident**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bForceMiplevelsToBeResident](ue_ue.TextureRenderTarget.md#bforcemiplevelstoberesident)

#### Defined in

[ue/ue.d.ts:394](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L394)

___

### bForcePVRTC4

• **bForcePVRTC4**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bForcePVRTC4](ue_ue.TextureRenderTarget.md#bforcepvrtc4)

#### Defined in

[ue/ue.d.ts:495](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L495)

___

### bGlobalForceMipLevelsToBeResident

• **bGlobalForceMipLevelsToBeResident**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bGlobalForceMipLevelsToBeResident](ue_ue.TextureRenderTarget.md#bglobalforcemiplevelstoberesident)

#### Defined in

[ue/ue.d.ts:391](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L391)

___

### bHDR

• **bHDR**: `boolean`

#### Defined in

[ue/ue.d.ts:59848](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59848)

___

### bHasStreamingUpdatePending

• **bHasStreamingUpdatePending**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bHasStreamingUpdatePending](ue_ue.TextureRenderTarget.md#bhasstreamingupdatepending)

#### Defined in

[ue/ue.d.ts:393](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L393)

___

### bIgnoreStreamingMipBias

• **bIgnoreStreamingMipBias**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bIgnoreStreamingMipBias](ue_ue.TextureRenderTarget.md#bignorestreamingmipbias)

#### Defined in

[ue/ue.d.ts:395](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L395)

___

### bIsStreamable

• **bIsStreamable**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bIsStreamable](ue_ue.TextureRenderTarget.md#bisstreamable)

#### Defined in

[ue/ue.d.ts:392](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L392)

___

### bNoTiling

• **bNoTiling**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bNoTiling](ue_ue.TextureRenderTarget.md#bnotiling)

#### Defined in

[ue/ue.d.ts:513](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L513)

___

### bPreserveBorder

• **bPreserveBorder**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bPreserveBorder](ue_ue.TextureRenderTarget.md#bpreserveborder)

#### Defined in

[ue/ue.d.ts:493](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L493)

___

### bUseCinematicMipLevels

• **bUseCinematicMipLevels**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bUseCinematicMipLevels](ue_ue.TextureRenderTarget.md#busecinematicmiplevels)

#### Defined in

[ue/ue.d.ts:396](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L396)

___

### bUseLegacyGamma

• **bUseLegacyGamma**: `boolean`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[bUseLegacyGamma](ue_ue.TextureRenderTarget.md#buselegacygamma)

#### Defined in

[ue/ue.d.ts:512](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L512)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[GetClass](ue_ue.TextureRenderTarget.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[GetName](ue_ue.TextureRenderTarget.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[GetOuter](ue_ue.TextureRenderTarget.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[GetWorld](ue_ue.TextureRenderTarget.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:59851](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59851)

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

#### Defined in

[ue/ue.d.ts:59852](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59852)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[TextureRenderTarget](ue_ue.TextureRenderTarget.md).[StaticClass](ue_ue.TextureRenderTarget.md#staticclass)

#### Defined in

[ue/ue.d.ts:59850](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59850)
