[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VolumeTexture

# Class: VolumeTexture

[ue/ue](../modules/ue_ue.md).VolumeTexture

## Hierarchy

- [`Texture`](ue_ue.Texture.md)

  ↳ **`VolumeTexture`**

## Table of contents

### Constructors

- [constructor](ue_ue.VolumeTexture.md#constructor)

### Properties

- [AdjustBrightness](ue_ue.VolumeTexture.md#adjustbrightness)
- [AdjustBrightnessCurve](ue_ue.VolumeTexture.md#adjustbrightnesscurve)
- [AdjustHue](ue_ue.VolumeTexture.md#adjusthue)
- [AdjustMaxAlpha](ue_ue.VolumeTexture.md#adjustmaxalpha)
- [AdjustMinAlpha](ue_ue.VolumeTexture.md#adjustminalpha)
- [AdjustRGBCurve](ue_ue.VolumeTexture.md#adjustrgbcurve)
- [AdjustSaturation](ue_ue.VolumeTexture.md#adjustsaturation)
- [AdjustVibrance](ue_ue.VolumeTexture.md#adjustvibrance)
- [AlphaCoverageThresholds](ue_ue.VolumeTexture.md#alphacoveragethresholds)
- [AssetImportData](ue_ue.VolumeTexture.md#assetimportdata)
- [AssetUserData](ue_ue.VolumeTexture.md#assetuserdata)
- [CachedCombinedLODBias](ue_ue.VolumeTexture.md#cachedcombinedlodbias)
- [CachedNumResidentLODs](ue_ue.VolumeTexture.md#cachednumresidentlods)
- [ChromaKeyColor](ue_ue.VolumeTexture.md#chromakeycolor)
- [ChromaKeyThreshold](ue_ue.VolumeTexture.md#chromakeythreshold)
- [CompositePower](ue_ue.VolumeTexture.md#compositepower)
- [CompositeTexture](ue_ue.VolumeTexture.md#compositetexture)
- [CompositeTextureMode](ue_ue.VolumeTexture.md#compositetexturemode)
- [CompressionNoAlpha](ue_ue.VolumeTexture.md#compressionnoalpha)
- [CompressionNone](ue_ue.VolumeTexture.md#compressionnone)
- [CompressionQuality](ue_ue.VolumeTexture.md#compressionquality)
- [CompressionSettings](ue_ue.VolumeTexture.md#compressionsettings)
- [CompressionYCoCg](ue_ue.VolumeTexture.md#compressionycocg)
- [DeferCompression](ue_ue.VolumeTexture.md#defercompression)
- [Filter](ue_ue.VolumeTexture.md#filter)
- [ForceMipLevelsToBeResidentTimestamp](ue_ue.VolumeTexture.md#forcemiplevelstoberesidenttimestamp)
- [LODBias](ue_ue.VolumeTexture.md#lodbias)
- [LODGroup](ue_ue.VolumeTexture.md#lodgroup)
- [LayerFormatSettings](ue_ue.VolumeTexture.md#layerformatsettings)
- [LightingGuid](ue_ue.VolumeTexture.md#lightingguid)
- [LossyCompressionAmount](ue_ue.VolumeTexture.md#lossycompressionamount)
- [MaxTextureSize](ue_ue.VolumeTexture.md#maxtexturesize)
- [MipGenSettings](ue_ue.VolumeTexture.md#mipgensettings)
- [MipLoadOptions](ue_ue.VolumeTexture.md#miploadoptions)
- [NeverStream](ue_ue.VolumeTexture.md#neverstream)
- [NumCinematicMipLevels](ue_ue.VolumeTexture.md#numcinematicmiplevels)
- [PaddingColor](ue_ue.VolumeTexture.md#paddingcolor)
- [PowerOfTwoMode](ue_ue.VolumeTexture.md#poweroftwomode)
- [SRGB](ue_ue.VolumeTexture.md#srgb)
- [Source](ue_ue.VolumeTexture.md#source)
- [Source2DTexture](ue_ue.VolumeTexture.md#source2dtexture)
- [Source2DTileSizeX](ue_ue.VolumeTexture.md#source2dtilesizex)
- [Source2DTileSizeY](ue_ue.VolumeTexture.md#source2dtilesizey)
- [SourceFilePath](ue_ue.VolumeTexture.md#sourcefilepath)
- [SourceLightingGuid](ue_ue.VolumeTexture.md#sourcelightingguid)
- [StreamingIndex](ue_ue.VolumeTexture.md#streamingindex)
- [VirtualTextureStreaming](ue_ue.VolumeTexture.md#virtualtexturestreaming)
- [\_\_tid\_Object\_\_](ue_ue.VolumeTexture.md#__tid_object__)
- [\_\_tid\_StreamableRenderAsset\_\_](ue_ue.VolumeTexture.md#__tid_streamablerenderasset__)
- [\_\_tid\_Texture\_\_](ue_ue.VolumeTexture.md#__tid_texture__)
- [\_\_tid\_VolumeTexture\_\_](ue_ue.VolumeTexture.md#__tid_volumetexture__)
- [bAsyncResourceReleaseHasBeenStarted](ue_ue.VolumeTexture.md#basyncresourcereleasehasbeenstarted)
- [bCachedReadyForStreaming](ue_ue.VolumeTexture.md#bcachedreadyforstreaming)
- [bChromaKeyTexture](ue_ue.VolumeTexture.md#bchromakeytexture)
- [bDitherMipMapAlpha](ue_ue.VolumeTexture.md#bdithermipmapalpha)
- [bFlipGreenChannel](ue_ue.VolumeTexture.md#bflipgreenchannel)
- [bForceMiplevelsToBeResident](ue_ue.VolumeTexture.md#bforcemiplevelstoberesident)
- [bForcePVRTC4](ue_ue.VolumeTexture.md#bforcepvrtc4)
- [bGlobalForceMipLevelsToBeResident](ue_ue.VolumeTexture.md#bglobalforcemiplevelstoberesident)
- [bHasStreamingUpdatePending](ue_ue.VolumeTexture.md#bhasstreamingupdatepending)
- [bIgnoreStreamingMipBias](ue_ue.VolumeTexture.md#bignorestreamingmipbias)
- [bIsStreamable](ue_ue.VolumeTexture.md#bisstreamable)
- [bNoTiling](ue_ue.VolumeTexture.md#bnotiling)
- [bPreserveBorder](ue_ue.VolumeTexture.md#bpreserveborder)
- [bUseCinematicMipLevels](ue_ue.VolumeTexture.md#busecinematicmiplevels)
- [bUseLegacyGamma](ue_ue.VolumeTexture.md#buselegacygamma)

### Methods

- [CreateDefaultSubobject](ue_ue.VolumeTexture.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.VolumeTexture.md#executeubergraph)
- [GetClass](ue_ue.VolumeTexture.md#getclass)
- [GetName](ue_ue.VolumeTexture.md#getname)
- [GetOuter](ue_ue.VolumeTexture.md#getouter)
- [GetWorld](ue_ue.VolumeTexture.md#getworld)
- [Find](ue_ue.VolumeTexture.md#find)
- [Load](ue_ue.VolumeTexture.md#load)
- [StaticClass](ue_ue.VolumeTexture.md#staticclass)

## Constructors

### constructor

• **new VolumeTexture**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Texture](ue_ue.Texture.md).[constructor](ue_ue.Texture.md#constructor)

## Properties

### AdjustBrightness

• **AdjustBrightness**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[AdjustBrightness](ue_ue.Texture.md#adjustbrightness)

___

### AdjustBrightnessCurve

• **AdjustBrightnessCurve**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[AdjustBrightnessCurve](ue_ue.Texture.md#adjustbrightnesscurve)

___

### AdjustHue

• **AdjustHue**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[AdjustHue](ue_ue.Texture.md#adjusthue)

___

### AdjustMaxAlpha

• **AdjustMaxAlpha**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[AdjustMaxAlpha](ue_ue.Texture.md#adjustmaxalpha)

___

### AdjustMinAlpha

• **AdjustMinAlpha**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[AdjustMinAlpha](ue_ue.Texture.md#adjustminalpha)

___

### AdjustRGBCurve

• **AdjustRGBCurve**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[AdjustRGBCurve](ue_ue.Texture.md#adjustrgbcurve)

___

### AdjustSaturation

• **AdjustSaturation**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[AdjustSaturation](ue_ue.Texture.md#adjustsaturation)

___

### AdjustVibrance

• **AdjustVibrance**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[AdjustVibrance](ue_ue.Texture.md#adjustvibrance)

___

### AlphaCoverageThresholds

• **AlphaCoverageThresholds**: [`Vector4`](ue_ue_s.Vector4.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[AlphaCoverageThresholds](ue_ue.Texture.md#alphacoveragethresholds)

___

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[AssetImportData](ue_ue.Texture.md#assetimportdata)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[Texture](ue_ue.Texture.md).[AssetUserData](ue_ue.Texture.md#assetuserdata)

___

### CachedCombinedLODBias

• **CachedCombinedLODBias**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[CachedCombinedLODBias](ue_ue.Texture.md#cachedcombinedlodbias)

___

### CachedNumResidentLODs

• **CachedNumResidentLODs**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[CachedNumResidentLODs](ue_ue.Texture.md#cachednumresidentlods)

___

### ChromaKeyColor

• **ChromaKeyColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[ChromaKeyColor](ue_ue.Texture.md#chromakeycolor)

___

### ChromaKeyThreshold

• **ChromaKeyThreshold**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[ChromaKeyThreshold](ue_ue.Texture.md#chromakeythreshold)

___

### CompositePower

• **CompositePower**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[CompositePower](ue_ue.Texture.md#compositepower)

___

### CompositeTexture

• **CompositeTexture**: [`Texture`](ue_ue.Texture.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[CompositeTexture](ue_ue.Texture.md#compositetexture)

___

### CompositeTextureMode

• **CompositeTextureMode**: [`ECompositeTextureMode`](../enums/ue_ue.ECompositeTextureMode.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[CompositeTextureMode](ue_ue.Texture.md#compositetexturemode)

___

### CompressionNoAlpha

• **CompressionNoAlpha**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[CompressionNoAlpha](ue_ue.Texture.md#compressionnoalpha)

___

### CompressionNone

• **CompressionNone**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[CompressionNone](ue_ue.Texture.md#compressionnone)

___

### CompressionQuality

• **CompressionQuality**: [`ETextureCompressionQuality`](../enums/ue_ue.ETextureCompressionQuality.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[CompressionQuality](ue_ue.Texture.md#compressionquality)

___

### CompressionSettings

• **CompressionSettings**: [`TextureCompressionSettings`](../enums/ue_ue.TextureCompressionSettings.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[CompressionSettings](ue_ue.Texture.md#compressionsettings)

___

### CompressionYCoCg

• **CompressionYCoCg**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[CompressionYCoCg](ue_ue.Texture.md#compressionycocg)

___

### DeferCompression

• **DeferCompression**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[DeferCompression](ue_ue.Texture.md#defercompression)

___

### Filter

• **Filter**: [`TextureFilter`](../enums/ue_ue.TextureFilter.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[Filter](ue_ue.Texture.md#filter)

___

### ForceMipLevelsToBeResidentTimestamp

• **ForceMipLevelsToBeResidentTimestamp**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[ForceMipLevelsToBeResidentTimestamp](ue_ue.Texture.md#forcemiplevelstoberesidenttimestamp)

___

### LODBias

• **LODBias**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[LODBias](ue_ue.Texture.md#lodbias)

___

### LODGroup

• **LODGroup**: [`TextureGroup`](../enums/ue_ue.TextureGroup.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[LODGroup](ue_ue.Texture.md#lodgroup)

___

### LayerFormatSettings

• **LayerFormatSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TextureFormatSettings`](ue_ue.TextureFormatSettings.md)\>

#### Inherited from

[Texture](ue_ue.Texture.md).[LayerFormatSettings](ue_ue.Texture.md#layerformatsettings)

___

### LightingGuid

• **LightingGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[LightingGuid](ue_ue.Texture.md#lightingguid)

___

### LossyCompressionAmount

• **LossyCompressionAmount**: [`ETextureLossyCompressionAmount`](../enums/ue_ue.ETextureLossyCompressionAmount.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[LossyCompressionAmount](ue_ue.Texture.md#lossycompressionamount)

___

### MaxTextureSize

• **MaxTextureSize**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[MaxTextureSize](ue_ue.Texture.md#maxtexturesize)

___

### MipGenSettings

• **MipGenSettings**: [`TextureMipGenSettings`](../enums/ue_ue.TextureMipGenSettings.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[MipGenSettings](ue_ue.Texture.md#mipgensettings)

___

### MipLoadOptions

• **MipLoadOptions**: [`ETextureMipLoadOptions`](../enums/ue_ue.ETextureMipLoadOptions.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[MipLoadOptions](ue_ue.Texture.md#miploadoptions)

___

### NeverStream

• **NeverStream**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[NeverStream](ue_ue.Texture.md#neverstream)

___

### NumCinematicMipLevels

• **NumCinematicMipLevels**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[NumCinematicMipLevels](ue_ue.Texture.md#numcinematicmiplevels)

___

### PaddingColor

• **PaddingColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[PaddingColor](ue_ue.Texture.md#paddingcolor)

___

### PowerOfTwoMode

• **PowerOfTwoMode**: [`ETexturePowerOfTwoSetting`](../enums/ue_ue.ETexturePowerOfTwoSetting.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[PowerOfTwoMode](ue_ue.Texture.md#poweroftwomode)

___

### SRGB

• **SRGB**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[SRGB](ue_ue.Texture.md#srgb)

___

### Source

• **Source**: [`TextureSource`](ue_ue.TextureSource.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[Source](ue_ue.Texture.md#source)

___

### Source2DTexture

• **Source2DTexture**: [`Texture2D`](ue_ue.Texture2D.md)

___

### Source2DTileSizeX

• **Source2DTileSizeX**: `number`

___

### Source2DTileSizeY

• **Source2DTileSizeY**: `number`

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[Texture](ue_ue.Texture.md).[SourceFilePath](ue_ue.Texture.md#sourcefilepath)

___

### SourceLightingGuid

• **SourceLightingGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### StreamingIndex

• **StreamingIndex**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[StreamingIndex](ue_ue.Texture.md#streamingindex)

___

### VirtualTextureStreaming

• **VirtualTextureStreaming**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[VirtualTextureStreaming](ue_ue.Texture.md#virtualtexturestreaming)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[__tid_Object__](ue_ue.Texture.md#__tid_object__)

___

### \_\_tid\_StreamableRenderAsset\_\_

• **\_\_tid\_StreamableRenderAsset\_\_**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[__tid_StreamableRenderAsset__](ue_ue.Texture.md#__tid_streamablerenderasset__)

___

### \_\_tid\_Texture\_\_

• **\_\_tid\_Texture\_\_**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[__tid_Texture__](ue_ue.Texture.md#__tid_texture__)

___

### \_\_tid\_VolumeTexture\_\_

• **\_\_tid\_VolumeTexture\_\_**: `boolean`

___

### bAsyncResourceReleaseHasBeenStarted

• **bAsyncResourceReleaseHasBeenStarted**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bAsyncResourceReleaseHasBeenStarted](ue_ue.Texture.md#basyncresourcereleasehasbeenstarted)

___

### bCachedReadyForStreaming

• **bCachedReadyForStreaming**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bCachedReadyForStreaming](ue_ue.Texture.md#bcachedreadyforstreaming)

___

### bChromaKeyTexture

• **bChromaKeyTexture**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bChromaKeyTexture](ue_ue.Texture.md#bchromakeytexture)

___

### bDitherMipMapAlpha

• **bDitherMipMapAlpha**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bDitherMipMapAlpha](ue_ue.Texture.md#bdithermipmapalpha)

___

### bFlipGreenChannel

• **bFlipGreenChannel**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bFlipGreenChannel](ue_ue.Texture.md#bflipgreenchannel)

___

### bForceMiplevelsToBeResident

• **bForceMiplevelsToBeResident**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bForceMiplevelsToBeResident](ue_ue.Texture.md#bforcemiplevelstoberesident)

___

### bForcePVRTC4

• **bForcePVRTC4**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bForcePVRTC4](ue_ue.Texture.md#bforcepvrtc4)

___

### bGlobalForceMipLevelsToBeResident

• **bGlobalForceMipLevelsToBeResident**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bGlobalForceMipLevelsToBeResident](ue_ue.Texture.md#bglobalforcemiplevelstoberesident)

___

### bHasStreamingUpdatePending

• **bHasStreamingUpdatePending**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bHasStreamingUpdatePending](ue_ue.Texture.md#bhasstreamingupdatepending)

___

### bIgnoreStreamingMipBias

• **bIgnoreStreamingMipBias**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bIgnoreStreamingMipBias](ue_ue.Texture.md#bignorestreamingmipbias)

___

### bIsStreamable

• **bIsStreamable**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bIsStreamable](ue_ue.Texture.md#bisstreamable)

___

### bNoTiling

• **bNoTiling**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bNoTiling](ue_ue.Texture.md#bnotiling)

___

### bPreserveBorder

• **bPreserveBorder**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bPreserveBorder](ue_ue.Texture.md#bpreserveborder)

___

### bUseCinematicMipLevels

• **bUseCinematicMipLevels**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bUseCinematicMipLevels](ue_ue.Texture.md#busecinematicmiplevels)

___

### bUseLegacyGamma

• **bUseLegacyGamma**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[bUseLegacyGamma](ue_ue.Texture.md#buselegacygamma)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[GetClass](ue_ue.Texture.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Texture](ue_ue.Texture.md).[GetName](ue_ue.Texture.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[GetOuter](ue_ue.Texture.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Texture](ue_ue.Texture.md).[GetWorld](ue_ue.Texture.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`VolumeTexture`](ue_ue.VolumeTexture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`VolumeTexture`](ue_ue.VolumeTexture.md)

#### Overrides

[Texture](ue_ue.Texture.md).[Find](ue_ue.Texture.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`VolumeTexture`](ue_ue.VolumeTexture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`VolumeTexture`](ue_ue.VolumeTexture.md)

#### Overrides

[Texture](ue_ue.Texture.md).[Load](ue_ue.Texture.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Texture](ue_ue.Texture.md).[StaticClass](ue_ue.Texture.md#staticclass)
