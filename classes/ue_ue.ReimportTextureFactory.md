[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ReimportTextureFactory

# Class: ReimportTextureFactory

[ue/ue](../modules/ue_ue.md).ReimportTextureFactory

## Hierarchy

- [`TextureFactory`](ue_ue.TextureFactory.md)

  ↳ **`ReimportTextureFactory`**

## Table of contents

### Constructors

- [constructor](ue_ue.ReimportTextureFactory.md#constructor)

### Properties

- [AlphaCoverageThresholds](ue_ue.ReimportTextureFactory.md#alphacoveragethresholds)
- [AssetImportTask](ue_ue.ReimportTextureFactory.md#assetimporttask)
- [AutomatedImportData](ue_ue.ReimportTextureFactory.md#automatedimportdata)
- [Blending](ue_ue.ReimportTextureFactory.md#blending)
- [CompressionSettings](ue_ue.ReimportTextureFactory.md#compressionsettings)
- [ContextClass](ue_ue.ReimportTextureFactory.md#contextclass)
- [Formats](ue_ue.ReimportTextureFactory.md#formats)
- [ImportPriority](ue_ue.ReimportTextureFactory.md#importpriority)
- [LODGroup](ue_ue.ReimportTextureFactory.md#lodgroup)
- [MipGenSettings](ue_ue.ReimportTextureFactory.md#mipgensettings)
- [NoAlpha](ue_ue.ReimportTextureFactory.md#noalpha)
- [NoCompression](ue_ue.ReimportTextureFactory.md#nocompression)
- [OverwriteYesOrNoToAllState](ue_ue.ReimportTextureFactory.md#overwriteyesornotoallstate)
- [ShadingModel](ue_ue.ReimportTextureFactory.md#shadingmodel)
- [SupportedClass](ue_ue.ReimportTextureFactory.md#supportedclass)
- [\_\_tid\_Factory\_\_](ue_ue.ReimportTextureFactory.md#__tid_factory__)
- [\_\_tid\_Object\_\_](ue_ue.ReimportTextureFactory.md#__tid_object__)
- [\_\_tid\_ReimportTextureFactory\_\_](ue_ue.ReimportTextureFactory.md#__tid_reimporttexturefactory__)
- [\_\_tid\_TextureFactory\_\_](ue_ue.ReimportTextureFactory.md#__tid_texturefactory__)
- [bAlphaToEmissive](ue_ue.ReimportTextureFactory.md#balphatoemissive)
- [bAlphaToOpacity](ue_ue.ReimportTextureFactory.md#balphatoopacity)
- [bAlphaToOpacityMask](ue_ue.ReimportTextureFactory.md#balphatoopacitymask)
- [bAlphaToRoughness](ue_ue.ReimportTextureFactory.md#balphatoroughness)
- [bCreateMaterial](ue_ue.ReimportTextureFactory.md#bcreatematerial)
- [bCreateNew](ue_ue.ReimportTextureFactory.md#bcreatenew)
- [bDeferCompression](ue_ue.ReimportTextureFactory.md#bdefercompression)
- [bDitherMipMapAlpha](ue_ue.ReimportTextureFactory.md#bdithermipmapalpha)
- [bEditAfterNew](ue_ue.ReimportTextureFactory.md#beditafternew)
- [bEditorImport](ue_ue.ReimportTextureFactory.md#beditorimport)
- [bFlipNormalMapGreenChannel](ue_ue.ReimportTextureFactory.md#bflipnormalmapgreenchannel)
- [bPreserveBorder](ue_ue.ReimportTextureFactory.md#bpreserveborder)
- [bRGBToBaseColor](ue_ue.ReimportTextureFactory.md#brgbtobasecolor)
- [bRGBToEmissive](ue_ue.ReimportTextureFactory.md#brgbtoemissive)
- [bText](ue_ue.ReimportTextureFactory.md#btext)
- [bTwoSided](ue_ue.ReimportTextureFactory.md#btwosided)
- [bUsingExistingSettings](ue_ue.ReimportTextureFactory.md#busingexistingsettings)
- [pOriginalTex](ue_ue.ReimportTextureFactory.md#poriginaltex)

### Methods

- [CreateDefaultSubobject](ue_ue.ReimportTextureFactory.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ReimportTextureFactory.md#executeubergraph)
- [GetClass](ue_ue.ReimportTextureFactory.md#getclass)
- [GetName](ue_ue.ReimportTextureFactory.md#getname)
- [GetOuter](ue_ue.ReimportTextureFactory.md#getouter)
- [GetWorld](ue_ue.ReimportTextureFactory.md#getworld)
- [ScriptFactoryCanImport](ue_ue.ReimportTextureFactory.md#scriptfactorycanimport)
- [ScriptFactoryCreateFile](ue_ue.ReimportTextureFactory.md#scriptfactorycreatefile)
- [Find](ue_ue.ReimportTextureFactory.md#find)
- [Load](ue_ue.ReimportTextureFactory.md#load)
- [StaticClass](ue_ue.ReimportTextureFactory.md#staticclass)

## Constructors

### constructor

• **new ReimportTextureFactory**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[TextureFactory](ue_ue.TextureFactory.md).[constructor](ue_ue.TextureFactory.md#constructor)

## Properties

### AlphaCoverageThresholds

• **AlphaCoverageThresholds**: [`Vector4`](ue_ue_s.Vector4.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[AlphaCoverageThresholds](ue_ue.TextureFactory.md#alphacoveragethresholds)

___

### AssetImportTask

• **AssetImportTask**: [`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[AssetImportTask](ue_ue.TextureFactory.md#assetimporttask)

___

### AutomatedImportData

• **AutomatedImportData**: [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[AutomatedImportData](ue_ue.TextureFactory.md#automatedimportdata)

___

### Blending

• **Blending**: [`EBlendMode`](../enums/ue_ue.EBlendMode.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[Blending](ue_ue.TextureFactory.md#blending)

___

### CompressionSettings

• **CompressionSettings**: [`TextureCompressionSettings`](../enums/ue_ue.TextureCompressionSettings.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[CompressionSettings](ue_ue.TextureFactory.md#compressionsettings)

___

### ContextClass

• **ContextClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[ContextClass](ue_ue.TextureFactory.md#contextclass)

___

### Formats

• **Formats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[Formats](ue_ue.TextureFactory.md#formats)

___

### ImportPriority

• **ImportPriority**: `number`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[ImportPriority](ue_ue.TextureFactory.md#importpriority)

___

### LODGroup

• **LODGroup**: [`TextureGroup`](../enums/ue_ue.TextureGroup.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[LODGroup](ue_ue.TextureFactory.md#lodgroup)

___

### MipGenSettings

• **MipGenSettings**: [`TextureMipGenSettings`](../enums/ue_ue.TextureMipGenSettings.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[MipGenSettings](ue_ue.TextureFactory.md#mipgensettings)

___

### NoAlpha

• **NoAlpha**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[NoAlpha](ue_ue.TextureFactory.md#noalpha)

___

### NoCompression

• **NoCompression**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[NoCompression](ue_ue.TextureFactory.md#nocompression)

___

### OverwriteYesOrNoToAllState

• **OverwriteYesOrNoToAllState**: `number`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[OverwriteYesOrNoToAllState](ue_ue.TextureFactory.md#overwriteyesornotoallstate)

___

### ShadingModel

• **ShadingModel**: [`EMaterialShadingModel`](../enums/ue_ue.EMaterialShadingModel.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[ShadingModel](ue_ue.TextureFactory.md#shadingmodel)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[SupportedClass](ue_ue.TextureFactory.md#supportedclass)

___

### \_\_tid\_Factory\_\_

• **\_\_tid\_Factory\_\_**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[__tid_Factory__](ue_ue.TextureFactory.md#__tid_factory__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[__tid_Object__](ue_ue.TextureFactory.md#__tid_object__)

___

### \_\_tid\_ReimportTextureFactory\_\_

• **\_\_tid\_ReimportTextureFactory\_\_**: `boolean`

___

### \_\_tid\_TextureFactory\_\_

• **\_\_tid\_TextureFactory\_\_**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[__tid_TextureFactory__](ue_ue.TextureFactory.md#__tid_texturefactory__)

___

### bAlphaToEmissive

• **bAlphaToEmissive**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bAlphaToEmissive](ue_ue.TextureFactory.md#balphatoemissive)

___

### bAlphaToOpacity

• **bAlphaToOpacity**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bAlphaToOpacity](ue_ue.TextureFactory.md#balphatoopacity)

___

### bAlphaToOpacityMask

• **bAlphaToOpacityMask**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bAlphaToOpacityMask](ue_ue.TextureFactory.md#balphatoopacitymask)

___

### bAlphaToRoughness

• **bAlphaToRoughness**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bAlphaToRoughness](ue_ue.TextureFactory.md#balphatoroughness)

___

### bCreateMaterial

• **bCreateMaterial**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bCreateMaterial](ue_ue.TextureFactory.md#bcreatematerial)

___

### bCreateNew

• **bCreateNew**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bCreateNew](ue_ue.TextureFactory.md#bcreatenew)

___

### bDeferCompression

• **bDeferCompression**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bDeferCompression](ue_ue.TextureFactory.md#bdefercompression)

___

### bDitherMipMapAlpha

• **bDitherMipMapAlpha**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bDitherMipMapAlpha](ue_ue.TextureFactory.md#bdithermipmapalpha)

___

### bEditAfterNew

• **bEditAfterNew**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bEditAfterNew](ue_ue.TextureFactory.md#beditafternew)

___

### bEditorImport

• **bEditorImport**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bEditorImport](ue_ue.TextureFactory.md#beditorimport)

___

### bFlipNormalMapGreenChannel

• **bFlipNormalMapGreenChannel**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bFlipNormalMapGreenChannel](ue_ue.TextureFactory.md#bflipnormalmapgreenchannel)

___

### bPreserveBorder

• **bPreserveBorder**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bPreserveBorder](ue_ue.TextureFactory.md#bpreserveborder)

___

### bRGBToBaseColor

• **bRGBToBaseColor**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bRGBToBaseColor](ue_ue.TextureFactory.md#brgbtobasecolor)

___

### bRGBToEmissive

• **bRGBToEmissive**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bRGBToEmissive](ue_ue.TextureFactory.md#brgbtoemissive)

___

### bText

• **bText**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bText](ue_ue.TextureFactory.md#btext)

___

### bTwoSided

• **bTwoSided**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bTwoSided](ue_ue.TextureFactory.md#btwosided)

___

### bUsingExistingSettings

• **bUsingExistingSettings**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bUsingExistingSettings](ue_ue.TextureFactory.md#busingexistingsettings)

___

### pOriginalTex

• **pOriginalTex**: [`Texture`](ue_ue.Texture.md)

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

[TextureFactory](ue_ue.TextureFactory.md).[CreateDefaultSubobject](ue_ue.TextureFactory.md#createdefaultsubobject)

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

[TextureFactory](ue_ue.TextureFactory.md).[ExecuteUbergraph](ue_ue.TextureFactory.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[GetClass](ue_ue.TextureFactory.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[GetName](ue_ue.TextureFactory.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[GetOuter](ue_ue.TextureFactory.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[GetWorld](ue_ue.TextureFactory.md#getworld)

___

### ScriptFactoryCanImport

▸ **ScriptFactoryCanImport**(`Filename`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Filename` | `string` |

#### Returns

`boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[ScriptFactoryCanImport](ue_ue.TextureFactory.md#scriptfactorycanimport)

___

### ScriptFactoryCreateFile

▸ **ScriptFactoryCreateFile**(`InTask`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTask` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AssetImportTask`](ue_ue.AssetImportTask.md)\> |

#### Returns

`boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[ScriptFactoryCreateFile](ue_ue.TextureFactory.md#scriptfactorycreatefile)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ReimportTextureFactory`](ue_ue.ReimportTextureFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ReimportTextureFactory`](ue_ue.ReimportTextureFactory.md)

#### Overrides

[TextureFactory](ue_ue.TextureFactory.md).[Find](ue_ue.TextureFactory.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ReimportTextureFactory`](ue_ue.ReimportTextureFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ReimportTextureFactory`](ue_ue.ReimportTextureFactory.md)

#### Overrides

[TextureFactory](ue_ue.TextureFactory.md).[Load](ue_ue.TextureFactory.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[TextureFactory](ue_ue.TextureFactory.md).[StaticClass](ue_ue.TextureFactory.md#staticclass)
