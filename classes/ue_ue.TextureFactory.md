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

#### Defined in

[ue/ue.d.ts:59375](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59375)

## Properties

### AlphaCoverageThresholds

• **AlphaCoverageThresholds**: [`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue.d.ts:59393](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59393)

___

### AssetImportTask

• **AssetImportTask**: [`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[AssetImportTask](ue_ue.Factory.md#assetimporttask)

#### Defined in

[ue/ue.d.ts:15338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15338)

___

### AutomatedImportData

• **AutomatedImportData**: [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[AutomatedImportData](ue_ue.Factory.md#automatedimportdata)

#### Defined in

[ue/ue.d.ts:15337](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15337)

___

### Blending

• **Blending**: [`EBlendMode`](../enums/ue_ue.EBlendMode.md)

#### Defined in

[ue/ue.d.ts:59388](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59388)

___

### CompressionSettings

• **CompressionSettings**: [`TextureCompressionSettings`](../enums/ue_ue.TextureCompressionSettings.md)

#### Defined in

[ue/ue.d.ts:59379](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59379)

___

### ContextClass

• **ContextClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[ContextClass](ue_ue.Factory.md#contextclass)

#### Defined in

[ue/ue.d.ts:15331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15331)

___

### Formats

• **Formats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Factory](ue_ue.Factory.md).[Formats](ue_ue.Factory.md#formats)

#### Defined in

[ue/ue.d.ts:15332](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15332)

___

### ImportPriority

• **ImportPriority**: `number`

#### Inherited from

[Factory](ue_ue.Factory.md).[ImportPriority](ue_ue.Factory.md#importpriority)

#### Defined in

[ue/ue.d.ts:15336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15336)

___

### LODGroup

• **LODGroup**: [`TextureGroup`](../enums/ue_ue.TextureGroup.md)

#### Defined in

[ue/ue.d.ts:59391](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59391)

___

### MipGenSettings

• **MipGenSettings**: [`TextureMipGenSettings`](../enums/ue_ue.TextureMipGenSettings.md)

#### Defined in

[ue/ue.d.ts:59390](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59390)

___

### NoAlpha

• **NoAlpha**: `boolean`

#### Defined in

[ue/ue.d.ts:59377](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59377)

___

### NoCompression

• **NoCompression**: `boolean`

#### Defined in

[ue/ue.d.ts:59376](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59376)

___

### OverwriteYesOrNoToAllState

• **OverwriteYesOrNoToAllState**: `number`

#### Inherited from

[Factory](ue_ue.Factory.md).[OverwriteYesOrNoToAllState](ue_ue.Factory.md#overwriteyesornotoallstate)

#### Defined in

[ue/ue.d.ts:15339](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15339)

___

### ShadingModel

• **ShadingModel**: [`EMaterialShadingModel`](../enums/ue_ue.EMaterialShadingModel.md)

#### Defined in

[ue/ue.d.ts:59389](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59389)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[SupportedClass](ue_ue.Factory.md#supportedclass)

#### Defined in

[ue/ue.d.ts:15330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15330)

___

### \_\_tid\_Factory\_\_

• **\_\_tid\_Factory\_\_**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[__tid_Factory__](ue_ue.Factory.md#__tid_factory__)

#### Defined in

[ue/ue.d.ts:15346](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15346)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[__tid_Object__](ue_ue.Factory.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_TextureFactory\_\_

• **\_\_tid\_TextureFactory\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:59401](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59401)

___

### bAlphaToEmissive

• **bAlphaToEmissive**: `boolean`

#### Defined in

[ue/ue.d.ts:59384](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59384)

___

### bAlphaToOpacity

• **bAlphaToOpacity**: `boolean`

#### Defined in

[ue/ue.d.ts:59385](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59385)

___

### bAlphaToOpacityMask

• **bAlphaToOpacityMask**: `boolean`

#### Defined in

[ue/ue.d.ts:59386](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59386)

___

### bAlphaToRoughness

• **bAlphaToRoughness**: `boolean`

#### Defined in

[ue/ue.d.ts:59383](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59383)

___

### bCreateMaterial

• **bCreateMaterial**: `boolean`

#### Defined in

[ue/ue.d.ts:59380](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59380)

___

### bCreateNew

• **bCreateNew**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[bCreateNew](ue_ue.Factory.md#bcreatenew)

#### Defined in

[ue/ue.d.ts:15329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15329)

___

### bDeferCompression

• **bDeferCompression**: `boolean`

#### Defined in

[ue/ue.d.ts:59378](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59378)

___

### bDitherMipMapAlpha

• **bDitherMipMapAlpha**: `boolean`

#### Defined in

[ue/ue.d.ts:59392](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59392)

___

### bEditAfterNew

• **bEditAfterNew**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[bEditAfterNew](ue_ue.Factory.md#beditafternew)

#### Defined in

[ue/ue.d.ts:15333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15333)

___

### bEditorImport

• **bEditorImport**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[bEditorImport](ue_ue.Factory.md#beditorimport)

#### Defined in

[ue/ue.d.ts:15334](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15334)

___

### bFlipNormalMapGreenChannel

• **bFlipNormalMapGreenChannel**: `boolean`

#### Defined in

[ue/ue.d.ts:59395](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59395)

___

### bPreserveBorder

• **bPreserveBorder**: `boolean`

#### Defined in

[ue/ue.d.ts:59394](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59394)

___

### bRGBToBaseColor

• **bRGBToBaseColor**: `boolean`

#### Defined in

[ue/ue.d.ts:59381](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59381)

___

### bRGBToEmissive

• **bRGBToEmissive**: `boolean`

#### Defined in

[ue/ue.d.ts:59382](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59382)

___

### bText

• **bText**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[bText](ue_ue.Factory.md#btext)

#### Defined in

[ue/ue.d.ts:15335](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15335)

___

### bTwoSided

• **bTwoSided**: `boolean`

#### Defined in

[ue/ue.d.ts:59387](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59387)

___

### bUsingExistingSettings

• **bUsingExistingSettings**: `boolean`

#### Defined in

[ue/ue.d.ts:59396](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59396)

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

[Factory](ue_ue.Factory.md).[ExecuteUbergraph](ue_ue.Factory.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[GetClass](ue_ue.Factory.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Factory](ue_ue.Factory.md).[GetName](ue_ue.Factory.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[GetOuter](ue_ue.Factory.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[GetWorld](ue_ue.Factory.md#getworld)

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

[Factory](ue_ue.Factory.md).[ScriptFactoryCanImport](ue_ue.Factory.md#scriptfactorycanimport)

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

[Factory](ue_ue.Factory.md).[ScriptFactoryCreateFile](ue_ue.Factory.md#scriptfactorycreatefile)

#### Defined in

[ue/ue.d.ts:15341](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15341)

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

#### Defined in

[ue/ue.d.ts:59398](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59398)

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

#### Defined in

[ue/ue.d.ts:59399](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59399)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Factory](ue_ue.Factory.md).[StaticClass](ue_ue.Factory.md#staticclass)

#### Defined in

[ue/ue.d.ts:59397](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59397)
