[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MediaTexture

# Class: MediaTexture

[ue/ue](../modules/ue_ue.md).MediaTexture

## Hierarchy

- [`Texture`](ue_ue.Texture.md)

  ↳ **`MediaTexture`**

## Table of contents

### Constructors

- [constructor](ue_ue.MediaTexture.md#constructor)

### Properties

- [AddressX](ue_ue.MediaTexture.md#addressx)
- [AddressY](ue_ue.MediaTexture.md#addressy)
- [AdjustBrightness](ue_ue.MediaTexture.md#adjustbrightness)
- [AdjustBrightnessCurve](ue_ue.MediaTexture.md#adjustbrightnesscurve)
- [AdjustHue](ue_ue.MediaTexture.md#adjusthue)
- [AdjustMaxAlpha](ue_ue.MediaTexture.md#adjustmaxalpha)
- [AdjustMinAlpha](ue_ue.MediaTexture.md#adjustminalpha)
- [AdjustRGBCurve](ue_ue.MediaTexture.md#adjustrgbcurve)
- [AdjustSaturation](ue_ue.MediaTexture.md#adjustsaturation)
- [AdjustVibrance](ue_ue.MediaTexture.md#adjustvibrance)
- [AlphaCoverageThresholds](ue_ue.MediaTexture.md#alphacoveragethresholds)
- [AssetImportData](ue_ue.MediaTexture.md#assetimportdata)
- [AssetUserData](ue_ue.MediaTexture.md#assetuserdata)
- [AutoClear](ue_ue.MediaTexture.md#autoclear)
- [CachedCombinedLODBias](ue_ue.MediaTexture.md#cachedcombinedlodbias)
- [CachedNumResidentLODs](ue_ue.MediaTexture.md#cachednumresidentlods)
- [ChromaKeyColor](ue_ue.MediaTexture.md#chromakeycolor)
- [ChromaKeyThreshold](ue_ue.MediaTexture.md#chromakeythreshold)
- [ClearColor](ue_ue.MediaTexture.md#clearcolor)
- [CompositePower](ue_ue.MediaTexture.md#compositepower)
- [CompositeTexture](ue_ue.MediaTexture.md#compositetexture)
- [CompositeTextureMode](ue_ue.MediaTexture.md#compositetexturemode)
- [CompressionNoAlpha](ue_ue.MediaTexture.md#compressionnoalpha)
- [CompressionNone](ue_ue.MediaTexture.md#compressionnone)
- [CompressionQuality](ue_ue.MediaTexture.md#compressionquality)
- [CompressionSettings](ue_ue.MediaTexture.md#compressionsettings)
- [CompressionYCoCg](ue_ue.MediaTexture.md#compressionycocg)
- [DeferCompression](ue_ue.MediaTexture.md#defercompression)
- [Filter](ue_ue.MediaTexture.md#filter)
- [ForceMipLevelsToBeResidentTimestamp](ue_ue.MediaTexture.md#forcemiplevelstoberesidenttimestamp)
- [LODBias](ue_ue.MediaTexture.md#lodbias)
- [LODGroup](ue_ue.MediaTexture.md#lodgroup)
- [LayerFormatSettings](ue_ue.MediaTexture.md#layerformatsettings)
- [LightingGuid](ue_ue.MediaTexture.md#lightingguid)
- [LossyCompressionAmount](ue_ue.MediaTexture.md#lossycompressionamount)
- [MaxTextureSize](ue_ue.MediaTexture.md#maxtexturesize)
- [MediaPlayer](ue_ue.MediaTexture.md#mediaplayer)
- [MipGenSettings](ue_ue.MediaTexture.md#mipgensettings)
- [MipLoadOptions](ue_ue.MediaTexture.md#miploadoptions)
- [NeverStream](ue_ue.MediaTexture.md#neverstream)
- [NumCinematicMipLevels](ue_ue.MediaTexture.md#numcinematicmiplevels)
- [PaddingColor](ue_ue.MediaTexture.md#paddingcolor)
- [PowerOfTwoMode](ue_ue.MediaTexture.md#poweroftwomode)
- [SRGB](ue_ue.MediaTexture.md#srgb)
- [Source](ue_ue.MediaTexture.md#source)
- [SourceFilePath](ue_ue.MediaTexture.md#sourcefilepath)
- [StreamingIndex](ue_ue.MediaTexture.md#streamingindex)
- [VirtualTextureStreaming](ue_ue.MediaTexture.md#virtualtexturestreaming)
- [\_\_tid\_MediaTexture\_\_](ue_ue.MediaTexture.md#__tid_mediatexture__)
- [\_\_tid\_Object\_\_](ue_ue.MediaTexture.md#__tid_object__)
- [\_\_tid\_StreamableRenderAsset\_\_](ue_ue.MediaTexture.md#__tid_streamablerenderasset__)
- [\_\_tid\_Texture\_\_](ue_ue.MediaTexture.md#__tid_texture__)
- [bAsyncResourceReleaseHasBeenStarted](ue_ue.MediaTexture.md#basyncresourcereleasehasbeenstarted)
- [bCachedReadyForStreaming](ue_ue.MediaTexture.md#bcachedreadyforstreaming)
- [bChromaKeyTexture](ue_ue.MediaTexture.md#bchromakeytexture)
- [bDitherMipMapAlpha](ue_ue.MediaTexture.md#bdithermipmapalpha)
- [bFlipGreenChannel](ue_ue.MediaTexture.md#bflipgreenchannel)
- [bForceMiplevelsToBeResident](ue_ue.MediaTexture.md#bforcemiplevelstoberesident)
- [bForcePVRTC4](ue_ue.MediaTexture.md#bforcepvrtc4)
- [bGlobalForceMipLevelsToBeResident](ue_ue.MediaTexture.md#bglobalforcemiplevelstoberesident)
- [bHasStreamingUpdatePending](ue_ue.MediaTexture.md#bhasstreamingupdatepending)
- [bIgnoreStreamingMipBias](ue_ue.MediaTexture.md#bignorestreamingmipbias)
- [bIsStreamable](ue_ue.MediaTexture.md#bisstreamable)
- [bNoTiling](ue_ue.MediaTexture.md#bnotiling)
- [bPreserveBorder](ue_ue.MediaTexture.md#bpreserveborder)
- [bUseCinematicMipLevels](ue_ue.MediaTexture.md#busecinematicmiplevels)
- [bUseLegacyGamma](ue_ue.MediaTexture.md#buselegacygamma)

### Methods

- [CreateDefaultSubobject](ue_ue.MediaTexture.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MediaTexture.md#executeubergraph)
- [GetAspectRatio](ue_ue.MediaTexture.md#getaspectratio)
- [GetClass](ue_ue.MediaTexture.md#getclass)
- [GetHeight](ue_ue.MediaTexture.md#getheight)
- [GetMediaPlayer](ue_ue.MediaTexture.md#getmediaplayer)
- [GetName](ue_ue.MediaTexture.md#getname)
- [GetOuter](ue_ue.MediaTexture.md#getouter)
- [GetWidth](ue_ue.MediaTexture.md#getwidth)
- [GetWorld](ue_ue.MediaTexture.md#getworld)
- [SetMediaPlayer](ue_ue.MediaTexture.md#setmediaplayer)
- [Find](ue_ue.MediaTexture.md#find)
- [Load](ue_ue.MediaTexture.md#load)
- [StaticClass](ue_ue.MediaTexture.md#staticclass)

## Constructors

### constructor

• **new MediaTexture**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Texture](ue_ue.Texture.md).[constructor](ue_ue.Texture.md#constructor)

#### Defined in

[ue/ue.d.ts:50408](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50408)

## Properties

### AddressX

• **AddressX**: [`TextureAddress`](../enums/ue_ue.TextureAddress.md)

#### Defined in

[ue/ue.d.ts:50409](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50409)

___

### AddressY

• **AddressY**: [`TextureAddress`](../enums/ue_ue.TextureAddress.md)

#### Defined in

[ue/ue.d.ts:50410](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50410)

___

### AdjustBrightness

• **AdjustBrightness**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[AdjustBrightness](ue_ue.Texture.md#adjustbrightness)

#### Defined in

[ue/ue.d.ts:477](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L477)

___

### AdjustBrightnessCurve

• **AdjustBrightnessCurve**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[AdjustBrightnessCurve](ue_ue.Texture.md#adjustbrightnesscurve)

#### Defined in

[ue/ue.d.ts:478](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L478)

___

### AdjustHue

• **AdjustHue**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[AdjustHue](ue_ue.Texture.md#adjusthue)

#### Defined in

[ue/ue.d.ts:482](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L482)

___

### AdjustMaxAlpha

• **AdjustMaxAlpha**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[AdjustMaxAlpha](ue_ue.Texture.md#adjustmaxalpha)

#### Defined in

[ue/ue.d.ts:484](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L484)

___

### AdjustMinAlpha

• **AdjustMinAlpha**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[AdjustMinAlpha](ue_ue.Texture.md#adjustminalpha)

#### Defined in

[ue/ue.d.ts:483](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L483)

___

### AdjustRGBCurve

• **AdjustRGBCurve**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[AdjustRGBCurve](ue_ue.Texture.md#adjustrgbcurve)

#### Defined in

[ue/ue.d.ts:481](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L481)

___

### AdjustSaturation

• **AdjustSaturation**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[AdjustSaturation](ue_ue.Texture.md#adjustsaturation)

#### Defined in

[ue/ue.d.ts:480](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L480)

___

### AdjustVibrance

• **AdjustVibrance**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[AdjustVibrance](ue_ue.Texture.md#adjustvibrance)

#### Defined in

[ue/ue.d.ts:479](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L479)

___

### AlphaCoverageThresholds

• **AlphaCoverageThresholds**: [`Vector4`](ue_ue_s.Vector4.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[AlphaCoverageThresholds](ue_ue.Texture.md#alphacoveragethresholds)

#### Defined in

[ue/ue.d.ts:492](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L492)

___

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[AssetImportData](ue_ue.Texture.md#assetimportdata)

#### Defined in

[ue/ue.d.ts:476](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L476)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[Texture](ue_ue.Texture.md).[AssetUserData](ue_ue.Texture.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:517](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L517)

___

### AutoClear

• **AutoClear**: `boolean`

#### Defined in

[ue/ue.d.ts:50411](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50411)

___

### CachedCombinedLODBias

• **CachedCombinedLODBias**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[CachedCombinedLODBias](ue_ue.Texture.md#cachedcombinedlodbias)

#### Defined in

[ue/ue.d.ts:387](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L387)

___

### CachedNumResidentLODs

• **CachedNumResidentLODs**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[CachedNumResidentLODs](ue_ue.Texture.md#cachednumresidentlods)

#### Defined in

[ue/ue.d.ts:388](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L388)

___

### ChromaKeyColor

• **ChromaKeyColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[ChromaKeyColor](ue_ue.Texture.md#chromakeycolor)

#### Defined in

[ue/ue.d.ts:500](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L500)

___

### ChromaKeyThreshold

• **ChromaKeyThreshold**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[ChromaKeyThreshold](ue_ue.Texture.md#chromakeythreshold)

#### Defined in

[ue/ue.d.ts:499](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L499)

___

### ClearColor

• **ClearColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:50412](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50412)

___

### CompositePower

• **CompositePower**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[CompositePower](ue_ue.Texture.md#compositepower)

#### Defined in

[ue/ue.d.ts:504](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L504)

___

### CompositeTexture

• **CompositeTexture**: [`Texture`](ue_ue.Texture.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[CompositeTexture](ue_ue.Texture.md#compositetexture)

#### Defined in

[ue/ue.d.ts:502](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L502)

___

### CompositeTextureMode

• **CompositeTextureMode**: [`ECompositeTextureMode`](../enums/ue_ue.ECompositeTextureMode.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[CompositeTextureMode](ue_ue.Texture.md#compositetexturemode)

#### Defined in

[ue/ue.d.ts:503](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L503)

___

### CompressionNoAlpha

• **CompressionNoAlpha**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[CompressionNoAlpha](ue_ue.Texture.md#compressionnoalpha)

#### Defined in

[ue/ue.d.ts:485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L485)

___

### CompressionNone

• **CompressionNone**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[CompressionNone](ue_ue.Texture.md#compressionnone)

#### Defined in

[ue/ue.d.ts:486](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L486)

___

### CompressionQuality

• **CompressionQuality**: [`ETextureCompressionQuality`](../enums/ue_ue.ETextureCompressionQuality.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[CompressionQuality](ue_ue.Texture.md#compressionquality)

#### Defined in

[ue/ue.d.ts:490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L490)

___

### CompressionSettings

• **CompressionSettings**: [`TextureCompressionSettings`](../enums/ue_ue.TextureCompressionSettings.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[CompressionSettings](ue_ue.Texture.md#compressionsettings)

#### Defined in

[ue/ue.d.ts:507](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L507)

___

### CompressionYCoCg

• **CompressionYCoCg**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[CompressionYCoCg](ue_ue.Texture.md#compressionycocg)

#### Defined in

[ue/ue.d.ts:515](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L515)

___

### DeferCompression

• **DeferCompression**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[DeferCompression](ue_ue.Texture.md#defercompression)

#### Defined in

[ue/ue.d.ts:487](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L487)

___

### Filter

• **Filter**: [`TextureFilter`](../enums/ue_ue.TextureFilter.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[Filter](ue_ue.Texture.md#filter)

#### Defined in

[ue/ue.d.ts:508](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L508)

___

### ForceMipLevelsToBeResidentTimestamp

• **ForceMipLevelsToBeResidentTimestamp**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[ForceMipLevelsToBeResidentTimestamp](ue_ue.Texture.md#forcemiplevelstoberesidenttimestamp)

#### Defined in

[ue/ue.d.ts:384](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L384)

___

### LODBias

• **LODBias**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[LODBias](ue_ue.Texture.md#lodbias)

#### Defined in

[ue/ue.d.ts:506](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L506)

___

### LODGroup

• **LODGroup**: [`TextureGroup`](../enums/ue_ue.TextureGroup.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[LODGroup](ue_ue.Texture.md#lodgroup)

#### Defined in

[ue/ue.d.ts:510](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L510)

___

### LayerFormatSettings

• **LayerFormatSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TextureFormatSettings`](ue_ue.TextureFormatSettings.md)\>

#### Inherited from

[Texture](ue_ue.Texture.md).[LayerFormatSettings](ue_ue.Texture.md#layerformatsettings)

#### Defined in

[ue/ue.d.ts:505](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L505)

___

### LightingGuid

• **LightingGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[LightingGuid](ue_ue.Texture.md#lightingguid)

#### Defined in

[ue/ue.d.ts:474](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L474)

___

### LossyCompressionAmount

• **LossyCompressionAmount**: [`ETextureLossyCompressionAmount`](../enums/ue_ue.ETextureLossyCompressionAmount.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[LossyCompressionAmount](ue_ue.Texture.md#lossycompressionamount)

#### Defined in

[ue/ue.d.ts:488](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L488)

___

### MaxTextureSize

• **MaxTextureSize**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[MaxTextureSize](ue_ue.Texture.md#maxtexturesize)

#### Defined in

[ue/ue.d.ts:489](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L489)

___

### MediaPlayer

• **MediaPlayer**: [`MediaPlayer`](ue_ue.MediaPlayer.md)

#### Defined in

[ue/ue.d.ts:50413](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50413)

___

### MipGenSettings

• **MipGenSettings**: [`TextureMipGenSettings`](../enums/ue_ue.TextureMipGenSettings.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[MipGenSettings](ue_ue.Texture.md#mipgensettings)

#### Defined in

[ue/ue.d.ts:501](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L501)

___

### MipLoadOptions

• **MipLoadOptions**: [`ETextureMipLoadOptions`](../enums/ue_ue.ETextureMipLoadOptions.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[MipLoadOptions](ue_ue.Texture.md#miploadoptions)

#### Defined in

[ue/ue.d.ts:509](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L509)

___

### NeverStream

• **NeverStream**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[NeverStream](ue_ue.Texture.md#neverstream)

#### Defined in

[ue/ue.d.ts:390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L390)

___

### NumCinematicMipLevels

• **NumCinematicMipLevels**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[NumCinematicMipLevels](ue_ue.Texture.md#numcinematicmiplevels)

#### Defined in

[ue/ue.d.ts:385](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L385)

___

### PaddingColor

• **PaddingColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[PaddingColor](ue_ue.Texture.md#paddingcolor)

#### Defined in

[ue/ue.d.ts:497](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L497)

___

### PowerOfTwoMode

• **PowerOfTwoMode**: [`ETexturePowerOfTwoSetting`](../enums/ue_ue.ETexturePowerOfTwoSetting.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[PowerOfTwoMode](ue_ue.Texture.md#poweroftwomode)

#### Defined in

[ue/ue.d.ts:496](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L496)

___

### SRGB

• **SRGB**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[SRGB](ue_ue.Texture.md#srgb)

#### Defined in

[ue/ue.d.ts:511](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L511)

___

### Source

• **Source**: [`TextureSource`](ue_ue.TextureSource.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[Source](ue_ue.Texture.md#source)

#### Defined in

[ue/ue.d.ts:473](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L473)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[Texture](ue_ue.Texture.md).[SourceFilePath](ue_ue.Texture.md#sourcefilepath)

#### Defined in

[ue/ue.d.ts:475](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L475)

___

### StreamingIndex

• **StreamingIndex**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[StreamingIndex](ue_ue.Texture.md#streamingindex)

#### Defined in

[ue/ue.d.ts:386](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L386)

___

### VirtualTextureStreaming

• **VirtualTextureStreaming**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[VirtualTextureStreaming](ue_ue.Texture.md#virtualtexturestreaming)

#### Defined in

[ue/ue.d.ts:514](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L514)

___

### \_\_tid\_MediaTexture\_\_

• **\_\_tid\_MediaTexture\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:50423](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50423)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[__tid_Object__](ue_ue.Texture.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_StreamableRenderAsset\_\_

• **\_\_tid\_StreamableRenderAsset\_\_**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[__tid_StreamableRenderAsset__](ue_ue.Texture.md#__tid_streamablerenderasset__)

#### Defined in

[ue/ue.d.ts:401](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L401)

___

### \_\_tid\_Texture\_\_

• **\_\_tid\_Texture\_\_**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[__tid_Texture__](ue_ue.Texture.md#__tid_texture__)

#### Defined in

[ue/ue.d.ts:522](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L522)

___

### bAsyncResourceReleaseHasBeenStarted

• **bAsyncResourceReleaseHasBeenStarted**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bAsyncResourceReleaseHasBeenStarted](ue_ue.Texture.md#basyncresourcereleasehasbeenstarted)

#### Defined in

[ue/ue.d.ts:516](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L516)

___

### bCachedReadyForStreaming

• **bCachedReadyForStreaming**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bCachedReadyForStreaming](ue_ue.Texture.md#bcachedreadyforstreaming)

#### Defined in

[ue/ue.d.ts:389](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L389)

___

### bChromaKeyTexture

• **bChromaKeyTexture**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bChromaKeyTexture](ue_ue.Texture.md#bchromakeytexture)

#### Defined in

[ue/ue.d.ts:498](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L498)

___

### bDitherMipMapAlpha

• **bDitherMipMapAlpha**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bDitherMipMapAlpha](ue_ue.Texture.md#bdithermipmapalpha)

#### Defined in

[ue/ue.d.ts:491](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L491)

___

### bFlipGreenChannel

• **bFlipGreenChannel**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bFlipGreenChannel](ue_ue.Texture.md#bflipgreenchannel)

#### Defined in

[ue/ue.d.ts:494](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L494)

___

### bForceMiplevelsToBeResident

• **bForceMiplevelsToBeResident**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bForceMiplevelsToBeResident](ue_ue.Texture.md#bforcemiplevelstoberesident)

#### Defined in

[ue/ue.d.ts:394](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L394)

___

### bForcePVRTC4

• **bForcePVRTC4**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bForcePVRTC4](ue_ue.Texture.md#bforcepvrtc4)

#### Defined in

[ue/ue.d.ts:495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L495)

___

### bGlobalForceMipLevelsToBeResident

• **bGlobalForceMipLevelsToBeResident**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bGlobalForceMipLevelsToBeResident](ue_ue.Texture.md#bglobalforcemiplevelstoberesident)

#### Defined in

[ue/ue.d.ts:391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L391)

___

### bHasStreamingUpdatePending

• **bHasStreamingUpdatePending**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bHasStreamingUpdatePending](ue_ue.Texture.md#bhasstreamingupdatepending)

#### Defined in

[ue/ue.d.ts:393](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L393)

___

### bIgnoreStreamingMipBias

• **bIgnoreStreamingMipBias**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bIgnoreStreamingMipBias](ue_ue.Texture.md#bignorestreamingmipbias)

#### Defined in

[ue/ue.d.ts:395](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L395)

___

### bIsStreamable

• **bIsStreamable**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bIsStreamable](ue_ue.Texture.md#bisstreamable)

#### Defined in

[ue/ue.d.ts:392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L392)

___

### bNoTiling

• **bNoTiling**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bNoTiling](ue_ue.Texture.md#bnotiling)

#### Defined in

[ue/ue.d.ts:513](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L513)

___

### bPreserveBorder

• **bPreserveBorder**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bPreserveBorder](ue_ue.Texture.md#bpreserveborder)

#### Defined in

[ue/ue.d.ts:493](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L493)

___

### bUseCinematicMipLevels

• **bUseCinematicMipLevels**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bUseCinematicMipLevels](ue_ue.Texture.md#busecinematicmiplevels)

#### Defined in

[ue/ue.d.ts:396](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L396)

___

### bUseLegacyGamma

• **bUseLegacyGamma**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bUseLegacyGamma](ue_ue.Texture.md#buselegacygamma)

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

[Texture](ue_ue.Texture.md).[CreateDefaultSubobject](ue_ue.Texture.md#createdefaultsubobject)

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

[Texture](ue_ue.Texture.md).[ExecuteUbergraph](ue_ue.Texture.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetAspectRatio

▸ **GetAspectRatio**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:50414](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50414)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[GetClass](ue_ue.Texture.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetHeight

▸ **GetHeight**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:50415](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50415)

___

### GetMediaPlayer

▸ **GetMediaPlayer**(): [`MediaPlayer`](ue_ue.MediaPlayer.md)

#### Returns

[`MediaPlayer`](ue_ue.MediaPlayer.md)

#### Defined in

[ue/ue.d.ts:50416](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50416)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Texture](ue_ue.Texture.md).[GetName](ue_ue.Texture.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[GetOuter](ue_ue.Texture.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWidth

▸ **GetWidth**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:50417](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50417)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[GetWorld](ue_ue.Texture.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### SetMediaPlayer

▸ **SetMediaPlayer**(`NewMediaPlayer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewMediaPlayer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MediaPlayer`](ue_ue.MediaPlayer.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:50418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50418)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MediaTexture`](ue_ue.MediaTexture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MediaTexture`](ue_ue.MediaTexture.md)

#### Overrides

[Texture](ue_ue.Texture.md).[Find](ue_ue.Texture.md#find)

#### Defined in

[ue/ue.d.ts:50420](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50420)

___

### Load

▸ `Static` **Load**(`InName`): [`MediaTexture`](ue_ue.MediaTexture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MediaTexture`](ue_ue.MediaTexture.md)

#### Overrides

[Texture](ue_ue.Texture.md).[Load](ue_ue.Texture.md#load)

#### Defined in

[ue/ue.d.ts:50421](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50421)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Texture](ue_ue.Texture.md).[StaticClass](ue_ue.Texture.md#staticclass)

#### Defined in

[ue/ue.d.ts:50419](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50419)
