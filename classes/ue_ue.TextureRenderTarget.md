[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TextureRenderTarget

# Class: TextureRenderTarget

[ue/ue](../modules/ue_ue.md).TextureRenderTarget

## Hierarchy

- [`Texture`](ue_ue.Texture.md)

  ↳ **`TextureRenderTarget`**

  ↳↳ [`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)

  ↳↳ [`TextureRenderTargetCube`](ue_ue.TextureRenderTargetCube.md)

## Table of contents

### Constructors

- [constructor](ue_ue.TextureRenderTarget.md#constructor)

### Properties

- [AdjustBrightness](ue_ue.TextureRenderTarget.md#adjustbrightness)
- [AdjustBrightnessCurve](ue_ue.TextureRenderTarget.md#adjustbrightnesscurve)
- [AdjustHue](ue_ue.TextureRenderTarget.md#adjusthue)
- [AdjustMaxAlpha](ue_ue.TextureRenderTarget.md#adjustmaxalpha)
- [AdjustMinAlpha](ue_ue.TextureRenderTarget.md#adjustminalpha)
- [AdjustRGBCurve](ue_ue.TextureRenderTarget.md#adjustrgbcurve)
- [AdjustSaturation](ue_ue.TextureRenderTarget.md#adjustsaturation)
- [AdjustVibrance](ue_ue.TextureRenderTarget.md#adjustvibrance)
- [AlphaCoverageThresholds](ue_ue.TextureRenderTarget.md#alphacoveragethresholds)
- [AssetImportData](ue_ue.TextureRenderTarget.md#assetimportdata)
- [AssetUserData](ue_ue.TextureRenderTarget.md#assetuserdata)
- [CachedCombinedLODBias](ue_ue.TextureRenderTarget.md#cachedcombinedlodbias)
- [CachedNumResidentLODs](ue_ue.TextureRenderTarget.md#cachednumresidentlods)
- [ChromaKeyColor](ue_ue.TextureRenderTarget.md#chromakeycolor)
- [ChromaKeyThreshold](ue_ue.TextureRenderTarget.md#chromakeythreshold)
- [CompositePower](ue_ue.TextureRenderTarget.md#compositepower)
- [CompositeTexture](ue_ue.TextureRenderTarget.md#compositetexture)
- [CompositeTextureMode](ue_ue.TextureRenderTarget.md#compositetexturemode)
- [CompressionNoAlpha](ue_ue.TextureRenderTarget.md#compressionnoalpha)
- [CompressionNone](ue_ue.TextureRenderTarget.md#compressionnone)
- [CompressionQuality](ue_ue.TextureRenderTarget.md#compressionquality)
- [CompressionSettings](ue_ue.TextureRenderTarget.md#compressionsettings)
- [CompressionYCoCg](ue_ue.TextureRenderTarget.md#compressionycocg)
- [DeferCompression](ue_ue.TextureRenderTarget.md#defercompression)
- [Filter](ue_ue.TextureRenderTarget.md#filter)
- [ForceMipLevelsToBeResidentTimestamp](ue_ue.TextureRenderTarget.md#forcemiplevelstoberesidenttimestamp)
- [LODBias](ue_ue.TextureRenderTarget.md#lodbias)
- [LODGroup](ue_ue.TextureRenderTarget.md#lodgroup)
- [LayerFormatSettings](ue_ue.TextureRenderTarget.md#layerformatsettings)
- [LightingGuid](ue_ue.TextureRenderTarget.md#lightingguid)
- [LossyCompressionAmount](ue_ue.TextureRenderTarget.md#lossycompressionamount)
- [MaxTextureSize](ue_ue.TextureRenderTarget.md#maxtexturesize)
- [MipGenSettings](ue_ue.TextureRenderTarget.md#mipgensettings)
- [MipLoadOptions](ue_ue.TextureRenderTarget.md#miploadoptions)
- [NeverStream](ue_ue.TextureRenderTarget.md#neverstream)
- [NumCinematicMipLevels](ue_ue.TextureRenderTarget.md#numcinematicmiplevels)
- [PaddingColor](ue_ue.TextureRenderTarget.md#paddingcolor)
- [PowerOfTwoMode](ue_ue.TextureRenderTarget.md#poweroftwomode)
- [SRGB](ue_ue.TextureRenderTarget.md#srgb)
- [Source](ue_ue.TextureRenderTarget.md#source)
- [SourceFilePath](ue_ue.TextureRenderTarget.md#sourcefilepath)
- [StreamingIndex](ue_ue.TextureRenderTarget.md#streamingindex)
- [TargetGamma](ue_ue.TextureRenderTarget.md#targetgamma)
- [VirtualTextureStreaming](ue_ue.TextureRenderTarget.md#virtualtexturestreaming)
- [\_\_tid\_Object\_\_](ue_ue.TextureRenderTarget.md#__tid_object__)
- [\_\_tid\_StreamableRenderAsset\_\_](ue_ue.TextureRenderTarget.md#__tid_streamablerenderasset__)
- [\_\_tid\_TextureRenderTarget\_\_](ue_ue.TextureRenderTarget.md#__tid_texturerendertarget__)
- [\_\_tid\_Texture\_\_](ue_ue.TextureRenderTarget.md#__tid_texture__)
- [bAsyncResourceReleaseHasBeenStarted](ue_ue.TextureRenderTarget.md#basyncresourcereleasehasbeenstarted)
- [bCachedReadyForStreaming](ue_ue.TextureRenderTarget.md#bcachedreadyforstreaming)
- [bChromaKeyTexture](ue_ue.TextureRenderTarget.md#bchromakeytexture)
- [bDitherMipMapAlpha](ue_ue.TextureRenderTarget.md#bdithermipmapalpha)
- [bFlipGreenChannel](ue_ue.TextureRenderTarget.md#bflipgreenchannel)
- [bForceMiplevelsToBeResident](ue_ue.TextureRenderTarget.md#bforcemiplevelstoberesident)
- [bForcePVRTC4](ue_ue.TextureRenderTarget.md#bforcepvrtc4)
- [bGlobalForceMipLevelsToBeResident](ue_ue.TextureRenderTarget.md#bglobalforcemiplevelstoberesident)
- [bHasStreamingUpdatePending](ue_ue.TextureRenderTarget.md#bhasstreamingupdatepending)
- [bIgnoreStreamingMipBias](ue_ue.TextureRenderTarget.md#bignorestreamingmipbias)
- [bIsStreamable](ue_ue.TextureRenderTarget.md#bisstreamable)
- [bNoTiling](ue_ue.TextureRenderTarget.md#bnotiling)
- [bPreserveBorder](ue_ue.TextureRenderTarget.md#bpreserveborder)
- [bUseCinematicMipLevels](ue_ue.TextureRenderTarget.md#busecinematicmiplevels)
- [bUseLegacyGamma](ue_ue.TextureRenderTarget.md#buselegacygamma)

### Methods

- [CreateDefaultSubobject](ue_ue.TextureRenderTarget.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TextureRenderTarget.md#executeubergraph)
- [GetClass](ue_ue.TextureRenderTarget.md#getclass)
- [GetName](ue_ue.TextureRenderTarget.md#getname)
- [GetOuter](ue_ue.TextureRenderTarget.md#getouter)
- [GetWorld](ue_ue.TextureRenderTarget.md#getworld)
- [Find](ue_ue.TextureRenderTarget.md#find)
- [Load](ue_ue.TextureRenderTarget.md#load)
- [StaticClass](ue_ue.TextureRenderTarget.md#staticclass)

## Constructors

### constructor

• **new TextureRenderTarget**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[Texture](ue_ue.Texture.md).[SourceFilePath](ue_ue.Texture.md#sourcefilepath)

___

### StreamingIndex

• **StreamingIndex**: `number`

#### Inherited from

[Texture](ue_ue.Texture.md).[StreamingIndex](ue_ue.Texture.md#streamingindex)

___

### TargetGamma

• **TargetGamma**: `number`

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

### \_\_tid\_TextureRenderTarget\_\_

• **\_\_tid\_TextureRenderTarget\_\_**: `boolean`

___

### \_\_tid\_Texture\_\_

• **\_\_tid\_Texture\_\_**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[__tid_Texture__](ue_ue.Texture.md#__tid_texture__)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TextureRenderTarget`](ue_ue.TextureRenderTarget.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TextureRenderTarget`](ue_ue.TextureRenderTarget.md)

#### Overrides

[Texture](ue_ue.Texture.md).[Find](ue_ue.Texture.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TextureRenderTarget`](ue_ue.TextureRenderTarget.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TextureRenderTarget`](ue_ue.TextureRenderTarget.md)

#### Overrides

[Texture](ue_ue.Texture.md).[Load](ue_ue.Texture.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Texture](ue_ue.Texture.md).[StaticClass](ue_ue.Texture.md#staticclass)
