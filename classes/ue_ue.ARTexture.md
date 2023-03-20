[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARTexture

# Class: ARTexture

[ue/ue](../modules/ue_ue.md).ARTexture

## Hierarchy

- [`Texture`](ue_ue.Texture.md)

  ↳ **`ARTexture`**

  ↳↳ [`ARTextureCameraImage`](ue_ue.ARTextureCameraImage.md)

  ↳↳ [`ARTextureCameraDepth`](ue_ue.ARTextureCameraDepth.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ARTexture.md#constructor)

### Properties

- [AdjustBrightness](ue_ue.ARTexture.md#adjustbrightness)
- [AdjustBrightnessCurve](ue_ue.ARTexture.md#adjustbrightnesscurve)
- [AdjustHue](ue_ue.ARTexture.md#adjusthue)
- [AdjustMaxAlpha](ue_ue.ARTexture.md#adjustmaxalpha)
- [AdjustMinAlpha](ue_ue.ARTexture.md#adjustminalpha)
- [AdjustRGBCurve](ue_ue.ARTexture.md#adjustrgbcurve)
- [AdjustSaturation](ue_ue.ARTexture.md#adjustsaturation)
- [AdjustVibrance](ue_ue.ARTexture.md#adjustvibrance)
- [AlphaCoverageThresholds](ue_ue.ARTexture.md#alphacoveragethresholds)
- [AssetImportData](ue_ue.ARTexture.md#assetimportdata)
- [AssetUserData](ue_ue.ARTexture.md#assetuserdata)
- [CachedCombinedLODBias](ue_ue.ARTexture.md#cachedcombinedlodbias)
- [CachedNumResidentLODs](ue_ue.ARTexture.md#cachednumresidentlods)
- [ChromaKeyColor](ue_ue.ARTexture.md#chromakeycolor)
- [ChromaKeyThreshold](ue_ue.ARTexture.md#chromakeythreshold)
- [CompositePower](ue_ue.ARTexture.md#compositepower)
- [CompositeTexture](ue_ue.ARTexture.md#compositetexture)
- [CompositeTextureMode](ue_ue.ARTexture.md#compositetexturemode)
- [CompressionNoAlpha](ue_ue.ARTexture.md#compressionnoalpha)
- [CompressionNone](ue_ue.ARTexture.md#compressionnone)
- [CompressionQuality](ue_ue.ARTexture.md#compressionquality)
- [CompressionSettings](ue_ue.ARTexture.md#compressionsettings)
- [CompressionYCoCg](ue_ue.ARTexture.md#compressionycocg)
- [DeferCompression](ue_ue.ARTexture.md#defercompression)
- [ExternalTextureGuid](ue_ue.ARTexture.md#externaltextureguid)
- [Filter](ue_ue.ARTexture.md#filter)
- [ForceMipLevelsToBeResidentTimestamp](ue_ue.ARTexture.md#forcemiplevelstoberesidenttimestamp)
- [LODBias](ue_ue.ARTexture.md#lodbias)
- [LODGroup](ue_ue.ARTexture.md#lodgroup)
- [LayerFormatSettings](ue_ue.ARTexture.md#layerformatsettings)
- [LightingGuid](ue_ue.ARTexture.md#lightingguid)
- [LossyCompressionAmount](ue_ue.ARTexture.md#lossycompressionamount)
- [MaxTextureSize](ue_ue.ARTexture.md#maxtexturesize)
- [MipGenSettings](ue_ue.ARTexture.md#mipgensettings)
- [MipLoadOptions](ue_ue.ARTexture.md#miploadoptions)
- [NeverStream](ue_ue.ARTexture.md#neverstream)
- [NumCinematicMipLevels](ue_ue.ARTexture.md#numcinematicmiplevels)
- [PaddingColor](ue_ue.ARTexture.md#paddingcolor)
- [PowerOfTwoMode](ue_ue.ARTexture.md#poweroftwomode)
- [SRGB](ue_ue.ARTexture.md#srgb)
- [Size](ue_ue.ARTexture.md#size)
- [Source](ue_ue.ARTexture.md#source)
- [SourceFilePath](ue_ue.ARTexture.md#sourcefilepath)
- [StreamingIndex](ue_ue.ARTexture.md#streamingindex)
- [TextureType](ue_ue.ARTexture.md#texturetype)
- [Timestamp](ue_ue.ARTexture.md#timestamp)
- [VirtualTextureStreaming](ue_ue.ARTexture.md#virtualtexturestreaming)
- [\_\_tid\_ARTexture\_\_](ue_ue.ARTexture.md#__tid_artexture__)
- [\_\_tid\_Object\_\_](ue_ue.ARTexture.md#__tid_object__)
- [\_\_tid\_StreamableRenderAsset\_\_](ue_ue.ARTexture.md#__tid_streamablerenderasset__)
- [\_\_tid\_Texture\_\_](ue_ue.ARTexture.md#__tid_texture__)
- [bAsyncResourceReleaseHasBeenStarted](ue_ue.ARTexture.md#basyncresourcereleasehasbeenstarted)
- [bCachedReadyForStreaming](ue_ue.ARTexture.md#bcachedreadyforstreaming)
- [bChromaKeyTexture](ue_ue.ARTexture.md#bchromakeytexture)
- [bDitherMipMapAlpha](ue_ue.ARTexture.md#bdithermipmapalpha)
- [bFlipGreenChannel](ue_ue.ARTexture.md#bflipgreenchannel)
- [bForceMiplevelsToBeResident](ue_ue.ARTexture.md#bforcemiplevelstoberesident)
- [bForcePVRTC4](ue_ue.ARTexture.md#bforcepvrtc4)
- [bGlobalForceMipLevelsToBeResident](ue_ue.ARTexture.md#bglobalforcemiplevelstoberesident)
- [bHasStreamingUpdatePending](ue_ue.ARTexture.md#bhasstreamingupdatepending)
- [bIgnoreStreamingMipBias](ue_ue.ARTexture.md#bignorestreamingmipbias)
- [bIsStreamable](ue_ue.ARTexture.md#bisstreamable)
- [bNoTiling](ue_ue.ARTexture.md#bnotiling)
- [bPreserveBorder](ue_ue.ARTexture.md#bpreserveborder)
- [bUseCinematicMipLevels](ue_ue.ARTexture.md#busecinematicmiplevels)
- [bUseLegacyGamma](ue_ue.ARTexture.md#buselegacygamma)

### Methods

- [CreateDefaultSubobject](ue_ue.ARTexture.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ARTexture.md#executeubergraph)
- [GetClass](ue_ue.ARTexture.md#getclass)
- [GetName](ue_ue.ARTexture.md#getname)
- [GetOuter](ue_ue.ARTexture.md#getouter)
- [GetWorld](ue_ue.ARTexture.md#getworld)
- [Find](ue_ue.ARTexture.md#find)
- [Load](ue_ue.ARTexture.md#load)
- [StaticClass](ue_ue.ARTexture.md#staticclass)

## Constructors

### constructor

• **new ARTexture**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### ExternalTextureGuid

• **ExternalTextureGuid**: [`Guid`](ue_ue_s.Guid.md)

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

### Size

• **Size**: [`Vector2D`](ue_ue_s.Vector2D.md)

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

### TextureType

• **TextureType**: [`EARTextureType`](../enums/ue_ue.EARTextureType.md)

___

### Timestamp

• **Timestamp**: `number`

___

### VirtualTextureStreaming

• **VirtualTextureStreaming**: `boolean`

#### Inherited from

[Texture](ue_ue.Texture.md).[VirtualTextureStreaming](ue_ue.Texture.md#virtualtexturestreaming)

___

### \_\_tid\_ARTexture\_\_

• **\_\_tid\_ARTexture\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ARTexture`](ue_ue.ARTexture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ARTexture`](ue_ue.ARTexture.md)

#### Overrides

[Texture](ue_ue.Texture.md).[Find](ue_ue.Texture.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ARTexture`](ue_ue.ARTexture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ARTexture`](ue_ue.ARTexture.md)

#### Overrides

[Texture](ue_ue.Texture.md).[Load](ue_ue.Texture.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Texture](ue_ue.Texture.md).[StaticClass](ue_ue.Texture.md#staticclass)
