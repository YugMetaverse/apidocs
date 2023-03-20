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

#### Defined in

[ue/ue.d.ts:59405](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59405)

## Properties

### AlphaCoverageThresholds

• **AlphaCoverageThresholds**: [`Vector4`](ue_ue_s.Vector4.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[AlphaCoverageThresholds](ue_ue.TextureFactory.md#alphacoveragethresholds)

#### Defined in

[ue/ue.d.ts:59393](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59393)

___

### AssetImportTask

• **AssetImportTask**: [`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[AssetImportTask](ue_ue.TextureFactory.md#assetimporttask)

#### Defined in

[ue/ue.d.ts:15338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15338)

___

### AutomatedImportData

• **AutomatedImportData**: [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[AutomatedImportData](ue_ue.TextureFactory.md#automatedimportdata)

#### Defined in

[ue/ue.d.ts:15337](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15337)

___

### Blending

• **Blending**: [`EBlendMode`](../enums/ue_ue.EBlendMode.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[Blending](ue_ue.TextureFactory.md#blending)

#### Defined in

[ue/ue.d.ts:59388](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59388)

___

### CompressionSettings

• **CompressionSettings**: [`TextureCompressionSettings`](../enums/ue_ue.TextureCompressionSettings.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[CompressionSettings](ue_ue.TextureFactory.md#compressionsettings)

#### Defined in

[ue/ue.d.ts:59379](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59379)

___

### ContextClass

• **ContextClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[ContextClass](ue_ue.TextureFactory.md#contextclass)

#### Defined in

[ue/ue.d.ts:15331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15331)

___

### Formats

• **Formats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[Formats](ue_ue.TextureFactory.md#formats)

#### Defined in

[ue/ue.d.ts:15332](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15332)

___

### ImportPriority

• **ImportPriority**: `number`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[ImportPriority](ue_ue.TextureFactory.md#importpriority)

#### Defined in

[ue/ue.d.ts:15336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15336)

___

### LODGroup

• **LODGroup**: [`TextureGroup`](../enums/ue_ue.TextureGroup.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[LODGroup](ue_ue.TextureFactory.md#lodgroup)

#### Defined in

[ue/ue.d.ts:59391](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59391)

___

### MipGenSettings

• **MipGenSettings**: [`TextureMipGenSettings`](../enums/ue_ue.TextureMipGenSettings.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[MipGenSettings](ue_ue.TextureFactory.md#mipgensettings)

#### Defined in

[ue/ue.d.ts:59390](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59390)

___

### NoAlpha

• **NoAlpha**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[NoAlpha](ue_ue.TextureFactory.md#noalpha)

#### Defined in

[ue/ue.d.ts:59377](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59377)

___

### NoCompression

• **NoCompression**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[NoCompression](ue_ue.TextureFactory.md#nocompression)

#### Defined in

[ue/ue.d.ts:59376](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59376)

___

### OverwriteYesOrNoToAllState

• **OverwriteYesOrNoToAllState**: `number`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[OverwriteYesOrNoToAllState](ue_ue.TextureFactory.md#overwriteyesornotoallstate)

#### Defined in

[ue/ue.d.ts:15339](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15339)

___

### ShadingModel

• **ShadingModel**: [`EMaterialShadingModel`](../enums/ue_ue.EMaterialShadingModel.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[ShadingModel](ue_ue.TextureFactory.md#shadingmodel)

#### Defined in

[ue/ue.d.ts:59389](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59389)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[SupportedClass](ue_ue.TextureFactory.md#supportedclass)

#### Defined in

[ue/ue.d.ts:15330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15330)

___

### \_\_tid\_Factory\_\_

• **\_\_tid\_Factory\_\_**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[__tid_Factory__](ue_ue.TextureFactory.md#__tid_factory__)

#### Defined in

[ue/ue.d.ts:15346](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15346)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[__tid_Object__](ue_ue.TextureFactory.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_ReimportTextureFactory\_\_

• **\_\_tid\_ReimportTextureFactory\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:59411](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59411)

___

### \_\_tid\_TextureFactory\_\_

• **\_\_tid\_TextureFactory\_\_**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[__tid_TextureFactory__](ue_ue.TextureFactory.md#__tid_texturefactory__)

#### Defined in

[ue/ue.d.ts:59401](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59401)

___

### bAlphaToEmissive

• **bAlphaToEmissive**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bAlphaToEmissive](ue_ue.TextureFactory.md#balphatoemissive)

#### Defined in

[ue/ue.d.ts:59384](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59384)

___

### bAlphaToOpacity

• **bAlphaToOpacity**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bAlphaToOpacity](ue_ue.TextureFactory.md#balphatoopacity)

#### Defined in

[ue/ue.d.ts:59385](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59385)

___

### bAlphaToOpacityMask

• **bAlphaToOpacityMask**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bAlphaToOpacityMask](ue_ue.TextureFactory.md#balphatoopacitymask)

#### Defined in

[ue/ue.d.ts:59386](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59386)

___

### bAlphaToRoughness

• **bAlphaToRoughness**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bAlphaToRoughness](ue_ue.TextureFactory.md#balphatoroughness)

#### Defined in

[ue/ue.d.ts:59383](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59383)

___

### bCreateMaterial

• **bCreateMaterial**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bCreateMaterial](ue_ue.TextureFactory.md#bcreatematerial)

#### Defined in

[ue/ue.d.ts:59380](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59380)

___

### bCreateNew

• **bCreateNew**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bCreateNew](ue_ue.TextureFactory.md#bcreatenew)

#### Defined in

[ue/ue.d.ts:15329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15329)

___

### bDeferCompression

• **bDeferCompression**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bDeferCompression](ue_ue.TextureFactory.md#bdefercompression)

#### Defined in

[ue/ue.d.ts:59378](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59378)

___

### bDitherMipMapAlpha

• **bDitherMipMapAlpha**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bDitherMipMapAlpha](ue_ue.TextureFactory.md#bdithermipmapalpha)

#### Defined in

[ue/ue.d.ts:59392](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59392)

___

### bEditAfterNew

• **bEditAfterNew**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bEditAfterNew](ue_ue.TextureFactory.md#beditafternew)

#### Defined in

[ue/ue.d.ts:15333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15333)

___

### bEditorImport

• **bEditorImport**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bEditorImport](ue_ue.TextureFactory.md#beditorimport)

#### Defined in

[ue/ue.d.ts:15334](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15334)

___

### bFlipNormalMapGreenChannel

• **bFlipNormalMapGreenChannel**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bFlipNormalMapGreenChannel](ue_ue.TextureFactory.md#bflipnormalmapgreenchannel)

#### Defined in

[ue/ue.d.ts:59395](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59395)

___

### bPreserveBorder

• **bPreserveBorder**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bPreserveBorder](ue_ue.TextureFactory.md#bpreserveborder)

#### Defined in

[ue/ue.d.ts:59394](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59394)

___

### bRGBToBaseColor

• **bRGBToBaseColor**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bRGBToBaseColor](ue_ue.TextureFactory.md#brgbtobasecolor)

#### Defined in

[ue/ue.d.ts:59381](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59381)

___

### bRGBToEmissive

• **bRGBToEmissive**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bRGBToEmissive](ue_ue.TextureFactory.md#brgbtoemissive)

#### Defined in

[ue/ue.d.ts:59382](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59382)

___

### bText

• **bText**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bText](ue_ue.TextureFactory.md#btext)

#### Defined in

[ue/ue.d.ts:15335](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15335)

___

### bTwoSided

• **bTwoSided**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bTwoSided](ue_ue.TextureFactory.md#btwosided)

#### Defined in

[ue/ue.d.ts:59387](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59387)

___

### bUsingExistingSettings

• **bUsingExistingSettings**: `boolean`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[bUsingExistingSettings](ue_ue.TextureFactory.md#busingexistingsettings)

#### Defined in

[ue/ue.d.ts:59396](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59396)

___

### pOriginalTex

• **pOriginalTex**: [`Texture`](ue_ue.Texture.md)

#### Defined in

[ue/ue.d.ts:59406](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59406)

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

[TextureFactory](ue_ue.TextureFactory.md).[ExecuteUbergraph](ue_ue.TextureFactory.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[GetClass](ue_ue.TextureFactory.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[GetName](ue_ue.TextureFactory.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[GetOuter](ue_ue.TextureFactory.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[TextureFactory](ue_ue.TextureFactory.md).[GetWorld](ue_ue.TextureFactory.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:15340](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15340)

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

#### Defined in

[ue/ue.d.ts:15341](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15341)

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

#### Defined in

[ue/ue.d.ts:59408](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59408)

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

#### Defined in

[ue/ue.d.ts:59409](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59409)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[TextureFactory](ue_ue.TextureFactory.md).[StaticClass](ue_ue.TextureFactory.md#staticclass)

#### Defined in

[ue/ue.d.ts:59407](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59407)