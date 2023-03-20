[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Texture2D

# Class: Texture2D

[ue/ue](../modules/ue_ue.md).Texture2D

## Hierarchy

- [`Texture`](ue_ue.Texture.md)

  ↳ **`Texture2D`**

  ↳↳ [`RuntimeVirtualTextureStreamingProxy`](ue_ue.RuntimeVirtualTextureStreamingProxy.md)

  ↳↳ [`CurveLinearColorAtlas`](ue_ue.CurveLinearColorAtlas.md)

  ↳↳ [`TextureLightProfile`](ue_ue.TextureLightProfile.md)

  ↳↳ [`LightMapTexture2D`](ue_ue.LightMapTexture2D.md)

  ↳↳ [`LightMapVirtualTexture2D`](ue_ue.LightMapVirtualTexture2D.md)

  ↳↳ [`ShadowMapTexture2D`](ue_ue.ShadowMapTexture2D.md)

## Table of contents

### Constructors

- [constructor](ue_ue.Texture2D.md#constructor)

### Properties

- [AddressX](ue_ue.Texture2D.md#addressx)
- [AddressY](ue_ue.Texture2D.md#addressy)
- [AdjustBrightness](ue_ue.Texture2D.md#adjustbrightness)
- [AdjustBrightnessCurve](ue_ue.Texture2D.md#adjustbrightnesscurve)
- [AdjustHue](ue_ue.Texture2D.md#adjusthue)
- [AdjustMaxAlpha](ue_ue.Texture2D.md#adjustmaxalpha)
- [AdjustMinAlpha](ue_ue.Texture2D.md#adjustminalpha)
- [AdjustRGBCurve](ue_ue.Texture2D.md#adjustrgbcurve)
- [AdjustSaturation](ue_ue.Texture2D.md#adjustsaturation)
- [AdjustVibrance](ue_ue.Texture2D.md#adjustvibrance)
- [AlphaCoverageThresholds](ue_ue.Texture2D.md#alphacoveragethresholds)
- [AssetImportData](ue_ue.Texture2D.md#assetimportdata)
- [AssetUserData](ue_ue.Texture2D.md#assetuserdata)
- [CachedCombinedLODBias](ue_ue.Texture2D.md#cachedcombinedlodbias)
- [CachedNumResidentLODs](ue_ue.Texture2D.md#cachednumresidentlods)
- [ChromaKeyColor](ue_ue.Texture2D.md#chromakeycolor)
- [ChromaKeyThreshold](ue_ue.Texture2D.md#chromakeythreshold)
- [CompositePower](ue_ue.Texture2D.md#compositepower)
- [CompositeTexture](ue_ue.Texture2D.md#compositetexture)
- [CompositeTextureMode](ue_ue.Texture2D.md#compositetexturemode)
- [CompressionNoAlpha](ue_ue.Texture2D.md#compressionnoalpha)
- [CompressionNone](ue_ue.Texture2D.md#compressionnone)
- [CompressionQuality](ue_ue.Texture2D.md#compressionquality)
- [CompressionSettings](ue_ue.Texture2D.md#compressionsettings)
- [CompressionYCoCg](ue_ue.Texture2D.md#compressionycocg)
- [DeferCompression](ue_ue.Texture2D.md#defercompression)
- [Filter](ue_ue.Texture2D.md#filter)
- [FirstResourceMemMip](ue_ue.Texture2D.md#firstresourcememmip)
- [ForceMipLevelsToBeResidentTimestamp](ue_ue.Texture2D.md#forcemiplevelstoberesidenttimestamp)
- [ImportedSize](ue_ue.Texture2D.md#importedsize)
- [LODBias](ue_ue.Texture2D.md#lodbias)
- [LODGroup](ue_ue.Texture2D.md#lodgroup)
- [LayerFormatSettings](ue_ue.Texture2D.md#layerformatsettings)
- [LevelIndex](ue_ue.Texture2D.md#levelindex)
- [LightingGuid](ue_ue.Texture2D.md#lightingguid)
- [LossyCompressionAmount](ue_ue.Texture2D.md#lossycompressionamount)
- [MaxTextureSize](ue_ue.Texture2D.md#maxtexturesize)
- [MipGenSettings](ue_ue.Texture2D.md#mipgensettings)
- [MipLoadOptions](ue_ue.Texture2D.md#miploadoptions)
- [NeverStream](ue_ue.Texture2D.md#neverstream)
- [NumCinematicMipLevels](ue_ue.Texture2D.md#numcinematicmiplevels)
- [PaddingColor](ue_ue.Texture2D.md#paddingcolor)
- [PowerOfTwoMode](ue_ue.Texture2D.md#poweroftwomode)
- [SRGB](ue_ue.Texture2D.md#srgb)
- [Source](ue_ue.Texture2D.md#source)
- [SourceFilePath](ue_ue.Texture2D.md#sourcefilepath)
- [StreamingIndex](ue_ue.Texture2D.md#streamingindex)
- [VirtualTextureStreaming](ue_ue.Texture2D.md#virtualtexturestreaming)
- [\_\_tid\_Object\_\_](ue_ue.Texture2D.md#__tid_object__)
- [\_\_tid\_StreamableRenderAsset\_\_](ue_ue.Texture2D.md#__tid_streamablerenderasset__)
- [\_\_tid\_Texture2D\_\_](ue_ue.Texture2D.md#__tid_texture2d__)
- [\_\_tid\_Texture\_\_](ue_ue.Texture2D.md#__tid_texture__)
- [bAsyncResourceReleaseHasBeenStarted](ue_ue.Texture2D.md#basyncresourcereleasehasbeenstarted)
- [bCachedReadyForStreaming](ue_ue.Texture2D.md#bcachedreadyforstreaming)
- [bChromaKeyTexture](ue_ue.Texture2D.md#bchromakeytexture)
- [bDitherMipMapAlpha](ue_ue.Texture2D.md#bdithermipmapalpha)
- [bFlipGreenChannel](ue_ue.Texture2D.md#bflipgreenchannel)
- [bForceMiplevelsToBeResident](ue_ue.Texture2D.md#bforcemiplevelstoberesident)
- [bForcePVRTC4](ue_ue.Texture2D.md#bforcepvrtc4)
- [bGlobalForceMipLevelsToBeResident](ue_ue.Texture2D.md#bglobalforcemiplevelstoberesident)
- [bHasBeenPaintedInEditor](ue_ue.Texture2D.md#bhasbeenpaintedineditor)
- [bHasStreamingUpdatePending](ue_ue.Texture2D.md#bhasstreamingupdatepending)
- [bIgnoreStreamingMipBias](ue_ue.Texture2D.md#bignorestreamingmipbias)
- [bIsStreamable](ue_ue.Texture2D.md#bisstreamable)
- [bNoTiling](ue_ue.Texture2D.md#bnotiling)
- [bPreserveBorder](ue_ue.Texture2D.md#bpreserveborder)
- [bTemporarilyDisableStreaming](ue_ue.Texture2D.md#btemporarilydisablestreaming)
- [bUseCinematicMipLevels](ue_ue.Texture2D.md#busecinematicmiplevels)
- [bUseLegacyGamma](ue_ue.Texture2D.md#buselegacygamma)

### Methods

- [Blueprint\_GetSizeX](ue_ue.Texture2D.md#blueprint_getsizex)
- [Blueprint\_GetSizeY](ue_ue.Texture2D.md#blueprint_getsizey)
- [CreateDefaultSubobject](ue_ue.Texture2D.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Texture2D.md#executeubergraph)
- [GetClass](ue_ue.Texture2D.md#getclass)
- [GetName](ue_ue.Texture2D.md#getname)
- [GetOuter](ue_ue.Texture2D.md#getouter)
- [GetWorld](ue_ue.Texture2D.md#getworld)
- [Find](ue_ue.Texture2D.md#find)
- [Load](ue_ue.Texture2D.md#load)
- [StaticClass](ue_ue.Texture2D.md#staticclass)

## Constructors

### constructor

• **new Texture2D**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Texture](ue_ue.Texture.md).[constructor](ue_ue.Texture.md#constructor)

#### Defined in

[ue/ue.d.ts:527](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L527)

## Properties

### AddressX

• **AddressX**: [`TextureAddress`](../enums/ue_ue.TextureAddress.md)

#### Defined in

[ue/ue.d.ts:532](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L532)

___

### AddressY

• **AddressY**: [`TextureAddress`](../enums/ue_ue.TextureAddress.md)

#### Defined in

[ue/ue.d.ts:533](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L533)

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

### FirstResourceMemMip

• **FirstResourceMemMip**: `number`

#### Defined in

[ue/ue.d.ts:529](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L529)

___

### ForceMipLevelsToBeResidentTimestamp

• **ForceMipLevelsToBeResidentTimestamp**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[ForceMipLevelsToBeResidentTimestamp](ue_ue.Texture.md#forcemiplevelstoberesidenttimestamp)

#### Defined in

[ue/ue.d.ts:384](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L384)

___

### ImportedSize

• **ImportedSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:534](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L534)

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

### LevelIndex

• **LevelIndex**: `number`

#### Defined in

[ue/ue.d.ts:528](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L528)

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

### \_\_tid\_Texture2D\_\_

• **\_\_tid\_Texture2D\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:541](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L541)

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

### bHasBeenPaintedInEditor

• **bHasBeenPaintedInEditor**: `boolean`

#### Defined in

[ue/ue.d.ts:531](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L531)

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

### bTemporarilyDisableStreaming

• **bTemporarilyDisableStreaming**: `boolean`

#### Defined in

[ue/ue.d.ts:530](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L530)

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

### Blueprint\_GetSizeX

▸ **Blueprint_GetSizeX**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:535](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L535)

___

### Blueprint\_GetSizeY

▸ **Blueprint_GetSizeY**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:536](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L536)

___

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

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[GetClass](ue_ue.Texture.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

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

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[GetWorld](ue_ue.Texture.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Texture2D`](ue_ue.Texture2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Texture2D`](ue_ue.Texture2D.md)

#### Overrides

[Texture](ue_ue.Texture.md).[Find](ue_ue.Texture.md#find)

#### Defined in

[ue/ue.d.ts:538](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L538)

___

### Load

▸ `Static` **Load**(`InName`): [`Texture2D`](ue_ue.Texture2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Texture2D`](ue_ue.Texture2D.md)

#### Overrides

[Texture](ue_ue.Texture.md).[Load](ue_ue.Texture.md#load)

#### Defined in

[ue/ue.d.ts:539](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L539)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Texture](ue_ue.Texture.md).[StaticClass](ue_ue.Texture.md#staticclass)

#### Defined in

[ue/ue.d.ts:537](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L537)
