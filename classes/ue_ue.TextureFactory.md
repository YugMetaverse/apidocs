[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TextureFactory

# Class: TextureFactory

[ue/ue](../modules/ue_ue.md).TextureFactory

## Hierarchy

- [`Factory`](ue_ue.Factory.md)

  ↳ **`TextureFactory`**

  ↳↳ [`ReimportTextureFactory`](ue_ue.ReimportTextureFactory.md)

  ↳↳ [`TrueTypeFontFactory`](ue_ue.TrueTypeFontFactory.md)

## Table of contents

### Constructors

- [constructor](ue_ue.TextureFactory.md#constructor)

### Properties

- [AlphaCoverageThresholds](ue_ue.TextureFactory.md#alphacoveragethresholds)
- [AssetImportTask](ue_ue.TextureFactory.md#assetimporttask)
- [AutomatedImportData](ue_ue.TextureFactory.md#automatedimportdata)
- [Blending](ue_ue.TextureFactory.md#blending)
- [CompressionSettings](ue_ue.TextureFactory.md#compressionsettings)
- [ContextClass](ue_ue.TextureFactory.md#contextclass)
- [Formats](ue_ue.TextureFactory.md#formats)
- [ImportPriority](ue_ue.TextureFactory.md#importpriority)
- [LODGroup](ue_ue.TextureFactory.md#lodgroup)
- [MipGenSettings](ue_ue.TextureFactory.md#mipgensettings)
- [NoAlpha](ue_ue.TextureFactory.md#noalpha)
- [NoCompression](ue_ue.TextureFactory.md#nocompression)
- [OverwriteYesOrNoToAllState](ue_ue.TextureFactory.md#overwriteyesornotoallstate)
- [ShadingModel](ue_ue.TextureFactory.md#shadingmodel)
- [SupportedClass](ue_ue.TextureFactory.md#supportedclass)
- [\_\_tid\_Factory\_\_](ue_ue.TextureFactory.md#__tid_factory__)
- [\_\_tid\_Object\_\_](ue_ue.TextureFactory.md#__tid_object__)
- [\_\_tid\_TextureFactory\_\_](ue_ue.TextureFactory.md#__tid_texturefactory__)
- [bAlphaToEmissive](ue_ue.TextureFactory.md#balphatoemissive)
- [bAlphaToOpacity](ue_ue.TextureFactory.md#balphatoopacity)
- [bAlphaToOpacityMask](ue_ue.TextureFactory.md#balphatoopacitymask)
- [bAlphaToRoughness](ue_ue.TextureFactory.md#balphatoroughness)
- [bCreateMaterial](ue_ue.TextureFactory.md#bcreatematerial)
- [bCreateNew](ue_ue.TextureFactory.md#bcreatenew)
- [bDeferCompression](ue_ue.TextureFactory.md#bdefercompression)
- [bDitherMipMapAlpha](ue_ue.TextureFactory.md#bdithermipmapalpha)
- [bEditAfterNew](ue_ue.TextureFactory.md#beditafternew)
- [bEditorImport](ue_ue.TextureFactory.md#beditorimport)
- [bFlipNormalMapGreenChannel](ue_ue.TextureFactory.md#bflipnormalmapgreenchannel)
- [bPreserveBorder](ue_ue.TextureFactory.md#bpreserveborder)
- [bRGBToBaseColor](ue_ue.TextureFactory.md#brgbtobasecolor)
- [bRGBToEmissive](ue_ue.TextureFactory.md#brgbtoemissive)
- [bText](ue_ue.TextureFactory.md#btext)
- [bTwoSided](ue_ue.TextureFactory.md#btwosided)
- [bUsingExistingSettings](ue_ue.TextureFactory.md#busingexistingsettings)

### Methods

- [CreateDefaultSubobject](ue_ue.TextureFactory.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TextureFactory.md#executeubergraph)
- [GetClass](ue_ue.TextureFactory.md#getclass)
- [GetName](ue_ue.TextureFactory.md#getname)
- [GetOuter](ue_ue.TextureFactory.md#getouter)
- [GetWorld](ue_ue.TextureFactory.md#getworld)
- [ScriptFactoryCanImport](ue_ue.TextureFactory.md#scriptfactorycanimport)
- [ScriptFactoryCreateFile](ue_ue.TextureFactory.md#scriptfactorycreatefile)
- [Find](ue_ue.TextureFactory.md#find)
- [Load](ue_ue.TextureFactory.md#load)
- [StaticClass](ue_ue.TextureFactory.md#staticclass)

## Constructors

### constructor

• **new TextureFactory**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Factory](ue_ue.Factory.md).[constructor](ue_ue.Factory.md#constructor)

## Properties

### AlphaCoverageThresholds

• **AlphaCoverageThresholds**: [`Vector4`](ue_ue_s.Vector4.md)

___

### AssetImportTask

• **AssetImportTask**: [`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[AssetImportTask](ue_ue.Factory.md#assetimporttask)

___

### AutomatedImportData

• **AutomatedImportData**: [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[AutomatedImportData](ue_ue.Factory.md#automatedimportdata)

___

### Blending

• **Blending**: [`EBlendMode`](../enums/ue_ue.EBlendMode.md)

___

### CompressionSettings

• **CompressionSettings**: [`TextureCompressionSettings`](../enums/ue_ue.TextureCompressionSettings.md)

___

### ContextClass

• **ContextClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[ContextClass](ue_ue.Factory.md#contextclass)

___

### Formats

• **Formats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Factory](ue_ue.Factory.md).[Formats](ue_ue.Factory.md#formats)

___

### ImportPriority

• **ImportPriority**: `number`

#### Inherited from

[Factory](ue_ue.Factory.md).[ImportPriority](ue_ue.Factory.md#importpriority)

___

### LODGroup

• **LODGroup**: [`TextureGroup`](../enums/ue_ue.TextureGroup.md)

___

### MipGenSettings

• **MipGenSettings**: [`TextureMipGenSettings`](../enums/ue_ue.TextureMipGenSettings.md)

___

### NoAlpha

• **NoAlpha**: `boolean`

___

### NoCompression

• **NoCompression**: `boolean`

___

### OverwriteYesOrNoToAllState

• **OverwriteYesOrNoToAllState**: `number`

#### Inherited from

[Factory](ue_ue.Factory.md).[OverwriteYesOrNoToAllState](ue_ue.Factory.md#overwriteyesornotoallstate)

___

### ShadingModel

• **ShadingModel**: [`EMaterialShadingModel`](../enums/ue_ue.EMaterialShadingModel.md)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[SupportedClass](ue_ue.Factory.md#supportedclass)

___

### \_\_tid\_Factory\_\_

• **\_\_tid\_Factory\_\_**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[__tid_Factory__](ue_ue.Factory.md#__tid_factory__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[__tid_Object__](ue_ue.Factory.md#__tid_object__)

___

### \_\_tid\_TextureFactory\_\_

• **\_\_tid\_TextureFactory\_\_**: `boolean`

___

### bAlphaToEmissive

• **bAlphaToEmissive**: `boolean`

___

### bAlphaToOpacity

• **bAlphaToOpacity**: `boolean`

___

### bAlphaToOpacityMask

• **bAlphaToOpacityMask**: `boolean`

___

### bAlphaToRoughness

• **bAlphaToRoughness**: `boolean`

___

### bCreateMaterial

• **bCreateMaterial**: `boolean`

___

### bCreateNew

• **bCreateNew**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[bCreateNew](ue_ue.Factory.md#bcreatenew)

___

### bDeferCompression

• **bDeferCompression**: `boolean`

___

### bDitherMipMapAlpha

• **bDitherMipMapAlpha**: `boolean`

___

### bEditAfterNew

• **bEditAfterNew**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[bEditAfterNew](ue_ue.Factory.md#beditafternew)

___

### bEditorImport

• **bEditorImport**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[bEditorImport](ue_ue.Factory.md#beditorimport)

___

### bFlipNormalMapGreenChannel

• **bFlipNormalMapGreenChannel**: `boolean`

___

### bPreserveBorder

• **bPreserveBorder**: `boolean`

___

### bRGBToBaseColor

• **bRGBToBaseColor**: `boolean`

___

### bRGBToEmissive

• **bRGBToEmissive**: `boolean`

___

### bText

• **bText**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[bText](ue_ue.Factory.md#btext)

___

### bTwoSided

• **bTwoSided**: `boolean`

___

### bUsingExistingSettings

• **bUsingExistingSettings**: `boolean`

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

[Factory](ue_ue.Factory.md).[CreateDefaultSubobject](ue_ue.Factory.md#createdefaultsubobject)

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

[Factory](ue_ue.Factory.md).[ExecuteUbergraph](ue_ue.Factory.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[GetClass](ue_ue.Factory.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Factory](ue_ue.Factory.md).[GetName](ue_ue.Factory.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[GetOuter](ue_ue.Factory.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[GetWorld](ue_ue.Factory.md#getworld)

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

[Factory](ue_ue.Factory.md).[ScriptFactoryCanImport](ue_ue.Factory.md#scriptfactorycanimport)

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

[Factory](ue_ue.Factory.md).[ScriptFactoryCreateFile](ue_ue.Factory.md#scriptfactorycreatefile)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TextureFactory`](ue_ue.TextureFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TextureFactory`](ue_ue.TextureFactory.md)

#### Overrides

[Factory](ue_ue.Factory.md).[Find](ue_ue.Factory.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TextureFactory`](ue_ue.TextureFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TextureFactory`](ue_ue.TextureFactory.md)

#### Overrides

[Factory](ue_ue.Factory.md).[Load](ue_ue.Factory.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Factory](ue_ue.Factory.md).[StaticClass](ue_ue.Factory.md#staticclass)
