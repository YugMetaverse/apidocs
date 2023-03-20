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

#### Defined in

[ue/ue.d.ts:472](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L472)

## Properties

### AdjustBrightness

• **AdjustBrightness**: `number`

#### Defined in

[ue/ue.d.ts:477](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L477)

___

### AdjustBrightnessCurve

• **AdjustBrightnessCurve**: `number`

#### Defined in

[ue/ue.d.ts:478](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L478)

___

### AdjustHue

• **AdjustHue**: `number`

#### Defined in

[ue/ue.d.ts:482](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L482)

___

### AdjustMaxAlpha

• **AdjustMaxAlpha**: `number`

#### Defined in

[ue/ue.d.ts:484](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L484)

___

### AdjustMinAlpha

• **AdjustMinAlpha**: `number`

#### Defined in

[ue/ue.d.ts:483](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L483)

___

### AdjustRGBCurve

• **AdjustRGBCurve**: `number`

#### Defined in

[ue/ue.d.ts:481](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L481)

___

### AdjustSaturation

• **AdjustSaturation**: `number`

#### Defined in

[ue/ue.d.ts:480](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L480)

___

### AdjustVibrance

• **AdjustVibrance**: `number`

#### Defined in

[ue/ue.d.ts:479](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L479)

___

### AlphaCoverageThresholds

• **AlphaCoverageThresholds**: [`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue.d.ts:492](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L492)

___

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Defined in

[ue/ue.d.ts:476](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L476)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Defined in

[ue/ue.d.ts:517](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L517)

___

### CachedCombinedLODBias

• **CachedCombinedLODBias**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[CachedCombinedLODBias](ue_ue.StreamableRenderAsset.md#cachedcombinedlodbias)

#### Defined in

[ue/ue.d.ts:387](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L387)

___

### CachedNumResidentLODs

• **CachedNumResidentLODs**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[CachedNumResidentLODs](ue_ue.StreamableRenderAsset.md#cachednumresidentlods)

#### Defined in

[ue/ue.d.ts:388](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L388)

___

### ChromaKeyColor

• **ChromaKeyColor**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:500](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L500)

___

### ChromaKeyThreshold

• **ChromaKeyThreshold**: `number`

#### Defined in

[ue/ue.d.ts:499](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L499)

___

### CompositePower

• **CompositePower**: `number`

#### Defined in

[ue/ue.d.ts:504](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L504)

___

### CompositeTexture

• **CompositeTexture**: [`Texture`](ue_ue.Texture.md)

#### Defined in

[ue/ue.d.ts:502](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L502)

___

### CompositeTextureMode

• **CompositeTextureMode**: [`ECompositeTextureMode`](../enums/ue_ue.ECompositeTextureMode.md)

#### Defined in

[ue/ue.d.ts:503](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L503)

___

### CompressionNoAlpha

• **CompressionNoAlpha**: `boolean`

#### Defined in

[ue/ue.d.ts:485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L485)

___

### CompressionNone

• **CompressionNone**: `boolean`

#### Defined in

[ue/ue.d.ts:486](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L486)

___

### CompressionQuality

• **CompressionQuality**: [`ETextureCompressionQuality`](../enums/ue_ue.ETextureCompressionQuality.md)

#### Defined in

[ue/ue.d.ts:490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L490)

___

### CompressionSettings

• **CompressionSettings**: [`TextureCompressionSettings`](../enums/ue_ue.TextureCompressionSettings.md)

#### Defined in

[ue/ue.d.ts:507](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L507)

___

### CompressionYCoCg

• **CompressionYCoCg**: `boolean`

#### Defined in

[ue/ue.d.ts:515](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L515)

___

### DeferCompression

• **DeferCompression**: `boolean`

#### Defined in

[ue/ue.d.ts:487](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L487)

___

### Filter

• **Filter**: [`TextureFilter`](../enums/ue_ue.TextureFilter.md)

#### Defined in

[ue/ue.d.ts:508](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L508)

___

### ForceMipLevelsToBeResidentTimestamp

• **ForceMipLevelsToBeResidentTimestamp**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[ForceMipLevelsToBeResidentTimestamp](ue_ue.StreamableRenderAsset.md#forcemiplevelstoberesidenttimestamp)

#### Defined in

[ue/ue.d.ts:384](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L384)

___

### LODBias

• **LODBias**: `number`

#### Defined in

[ue/ue.d.ts:506](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L506)

___

### LODGroup

• **LODGroup**: [`TextureGroup`](../enums/ue_ue.TextureGroup.md)

#### Defined in

[ue/ue.d.ts:510](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L510)

___

### LayerFormatSettings

• **LayerFormatSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TextureFormatSettings`](ue_ue.TextureFormatSettings.md)\>

#### Defined in

[ue/ue.d.ts:505](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L505)

___

### LightingGuid

• **LightingGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:474](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L474)

___

### LossyCompressionAmount

• **LossyCompressionAmount**: [`ETextureLossyCompressionAmount`](../enums/ue_ue.ETextureLossyCompressionAmount.md)

#### Defined in

[ue/ue.d.ts:488](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L488)

___

### MaxTextureSize

• **MaxTextureSize**: `number`

#### Defined in

[ue/ue.d.ts:489](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L489)

___

### MipGenSettings

• **MipGenSettings**: [`TextureMipGenSettings`](../enums/ue_ue.TextureMipGenSettings.md)

#### Defined in

[ue/ue.d.ts:501](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L501)

___

### MipLoadOptions

• **MipLoadOptions**: [`ETextureMipLoadOptions`](../enums/ue_ue.ETextureMipLoadOptions.md)

#### Defined in

[ue/ue.d.ts:509](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L509)

___

### NeverStream

• **NeverStream**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[NeverStream](ue_ue.StreamableRenderAsset.md#neverstream)

#### Defined in

[ue/ue.d.ts:390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L390)

___

### NumCinematicMipLevels

• **NumCinematicMipLevels**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[NumCinematicMipLevels](ue_ue.StreamableRenderAsset.md#numcinematicmiplevels)

#### Defined in

[ue/ue.d.ts:385](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L385)

___

### PaddingColor

• **PaddingColor**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:497](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L497)

___

### PowerOfTwoMode

• **PowerOfTwoMode**: [`ETexturePowerOfTwoSetting`](../enums/ue_ue.ETexturePowerOfTwoSetting.md)

#### Defined in

[ue/ue.d.ts:496](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L496)

___

### SRGB

• **SRGB**: `boolean`

#### Defined in

[ue/ue.d.ts:511](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L511)

___

### Source

• **Source**: [`TextureSource`](ue_ue.TextureSource.md)

#### Defined in

[ue/ue.d.ts:473](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L473)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Defined in

[ue/ue.d.ts:475](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L475)

___

### StreamingIndex

• **StreamingIndex**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[StreamingIndex](ue_ue.StreamableRenderAsset.md#streamingindex)

#### Defined in

[ue/ue.d.ts:386](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L386)

___

### VirtualTextureStreaming

• **VirtualTextureStreaming**: `boolean`

#### Defined in

[ue/ue.d.ts:514](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L514)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[__tid_Object__](ue_ue.StreamableRenderAsset.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_StreamableRenderAsset\_\_

• **\_\_tid\_StreamableRenderAsset\_\_**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[__tid_StreamableRenderAsset__](ue_ue.StreamableRenderAsset.md#__tid_streamablerenderasset__)

#### Defined in

[ue/ue.d.ts:401](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L401)

___

### \_\_tid\_Texture\_\_

• **\_\_tid\_Texture\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:522](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L522)

___

### bAsyncResourceReleaseHasBeenStarted

• **bAsyncResourceReleaseHasBeenStarted**: `boolean`

#### Defined in

[ue/ue.d.ts:516](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L516)

___

### bCachedReadyForStreaming

• **bCachedReadyForStreaming**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bCachedReadyForStreaming](ue_ue.StreamableRenderAsset.md#bcachedreadyforstreaming)

#### Defined in

[ue/ue.d.ts:389](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L389)

___

### bChromaKeyTexture

• **bChromaKeyTexture**: `boolean`

#### Defined in

[ue/ue.d.ts:498](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L498)

___

### bDitherMipMapAlpha

• **bDitherMipMapAlpha**: `boolean`

#### Defined in

[ue/ue.d.ts:491](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L491)

___

### bFlipGreenChannel

• **bFlipGreenChannel**: `boolean`

#### Defined in

[ue/ue.d.ts:494](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L494)

___

### bForceMiplevelsToBeResident

• **bForceMiplevelsToBeResident**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bForceMiplevelsToBeResident](ue_ue.StreamableRenderAsset.md#bforcemiplevelstoberesident)

#### Defined in

[ue/ue.d.ts:394](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L394)

___

### bForcePVRTC4

• **bForcePVRTC4**: `boolean`

#### Defined in

[ue/ue.d.ts:495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L495)

___

### bGlobalForceMipLevelsToBeResident

• **bGlobalForceMipLevelsToBeResident**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bGlobalForceMipLevelsToBeResident](ue_ue.StreamableRenderAsset.md#bglobalforcemiplevelstoberesident)

#### Defined in

[ue/ue.d.ts:391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L391)

___

### bHasStreamingUpdatePending

• **bHasStreamingUpdatePending**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bHasStreamingUpdatePending](ue_ue.StreamableRenderAsset.md#bhasstreamingupdatepending)

#### Defined in

[ue/ue.d.ts:393](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L393)

___

### bIgnoreStreamingMipBias

• **bIgnoreStreamingMipBias**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bIgnoreStreamingMipBias](ue_ue.StreamableRenderAsset.md#bignorestreamingmipbias)

#### Defined in

[ue/ue.d.ts:395](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L395)

___

### bIsStreamable

• **bIsStreamable**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bIsStreamable](ue_ue.StreamableRenderAsset.md#bisstreamable)

#### Defined in

[ue/ue.d.ts:392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L392)

___

### bNoTiling

• **bNoTiling**: `boolean`

#### Defined in

[ue/ue.d.ts:513](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L513)

___

### bPreserveBorder

• **bPreserveBorder**: `boolean`

#### Defined in

[ue/ue.d.ts:493](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L493)

___

### bUseCinematicMipLevels

• **bUseCinematicMipLevels**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bUseCinematicMipLevels](ue_ue.StreamableRenderAsset.md#busecinematicmiplevels)

#### Defined in

[ue/ue.d.ts:396](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L396)

___

### bUseLegacyGamma

• **bUseLegacyGamma**: `boolean`

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

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[CreateDefaultSubobject](ue_ue.StreamableRenderAsset.md#createdefaultsubobject)

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

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[ExecuteUbergraph](ue_ue.StreamableRenderAsset.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[GetClass](ue_ue.StreamableRenderAsset.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[GetName](ue_ue.StreamableRenderAsset.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[GetOuter](ue_ue.StreamableRenderAsset.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[GetWorld](ue_ue.StreamableRenderAsset.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:519](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L519)

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

#### Defined in

[ue/ue.d.ts:520](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L520)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[StaticClass](ue_ue.StreamableRenderAsset.md#staticclass)

#### Defined in

[ue/ue.d.ts:518](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L518)
