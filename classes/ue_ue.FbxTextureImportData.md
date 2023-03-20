[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FbxTextureImportData

# Class: FbxTextureImportData

[ue/ue](../modules/ue_ue.md).FbxTextureImportData

## Hierarchy

- [`FbxAssetImportData`](ue_ue.FbxAssetImportData.md)

  ↳ **`FbxTextureImportData`**

## Table of contents

### Constructors

- [constructor](ue_ue.FbxTextureImportData.md#constructor)

### Properties

- [BaseColorName](ue_ue.FbxTextureImportData.md#basecolorname)
- [BaseDiffuseTextureName](ue_ue.FbxTextureImportData.md#basediffusetexturename)
- [BaseEmissiveColorName](ue_ue.FbxTextureImportData.md#baseemissivecolorname)
- [BaseEmmisiveTextureName](ue_ue.FbxTextureImportData.md#baseemmisivetexturename)
- [BaseMaterialName](ue_ue.FbxTextureImportData.md#basematerialname)
- [BaseNormalTextureName](ue_ue.FbxTextureImportData.md#basenormaltexturename)
- [BaseSpecularTextureName](ue_ue.FbxTextureImportData.md#basespeculartexturename)
- [FbxSceneImportDataReference](ue_ue.FbxTextureImportData.md#fbxsceneimportdatareference)
- [ImportRotation](ue_ue.FbxTextureImportData.md#importrotation)
- [ImportTranslation](ue_ue.FbxTextureImportData.md#importtranslation)
- [ImportUniformScale](ue_ue.FbxTextureImportData.md#importuniformscale)
- [MaterialSearchLocation](ue_ue.FbxTextureImportData.md#materialsearchlocation)
- [SourceData](ue_ue.FbxTextureImportData.md#sourcedata)
- [SourceFilePath](ue_ue.FbxTextureImportData.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.FbxTextureImportData.md#sourcefiletimestamp)
- [\_\_tid\_AssetImportData\_\_](ue_ue.FbxTextureImportData.md#__tid_assetimportdata__)
- [\_\_tid\_FbxAssetImportData\_\_](ue_ue.FbxTextureImportData.md#__tid_fbxassetimportdata__)
- [\_\_tid\_FbxTextureImportData\_\_](ue_ue.FbxTextureImportData.md#__tid_fbxtextureimportdata__)
- [\_\_tid\_Object\_\_](ue_ue.FbxTextureImportData.md#__tid_object__)
- [bConvertScene](ue_ue.FbxTextureImportData.md#bconvertscene)
- [bConvertSceneUnit](ue_ue.FbxTextureImportData.md#bconvertsceneunit)
- [bForceFrontXAxis](ue_ue.FbxTextureImportData.md#bforcefrontxaxis)
- [bImportAsScene](ue_ue.FbxTextureImportData.md#bimportasscene)
- [bInvertNormalMaps](ue_ue.FbxTextureImportData.md#binvertnormalmaps)

### Methods

- [CreateDefaultSubobject](ue_ue.FbxTextureImportData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.FbxTextureImportData.md#executeubergraph)
- [GetClass](ue_ue.FbxTextureImportData.md#getclass)
- [GetName](ue_ue.FbxTextureImportData.md#getname)
- [GetOuter](ue_ue.FbxTextureImportData.md#getouter)
- [GetWorld](ue_ue.FbxTextureImportData.md#getworld)
- [K2\_ExtractFilenames](ue_ue.FbxTextureImportData.md#k2_extractfilenames)
- [K2\_GetFirstFilename](ue_ue.FbxTextureImportData.md#k2_getfirstfilename)
- [Find](ue_ue.FbxTextureImportData.md#find)
- [Load](ue_ue.FbxTextureImportData.md#load)
- [StaticClass](ue_ue.FbxTextureImportData.md#staticclass)

## Constructors

### constructor

• **new FbxTextureImportData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[constructor](ue_ue.FbxAssetImportData.md#constructor)

## Properties

### BaseColorName

• **BaseColorName**: `string`

___

### BaseDiffuseTextureName

• **BaseDiffuseTextureName**: `string`

___

### BaseEmissiveColorName

• **BaseEmissiveColorName**: `string`

___

### BaseEmmisiveTextureName

• **BaseEmmisiveTextureName**: `string`

___

### BaseMaterialName

• **BaseMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### BaseNormalTextureName

• **BaseNormalTextureName**: `string`

___

### BaseSpecularTextureName

• **BaseSpecularTextureName**: `string`

___

### FbxSceneImportDataReference

• **FbxSceneImportDataReference**: [`FbxSceneImportData`](ue_ue.FbxSceneImportData.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[FbxSceneImportDataReference](ue_ue.FbxAssetImportData.md#fbxsceneimportdatareference)

___

### ImportRotation

• **ImportRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[ImportRotation](ue_ue.FbxAssetImportData.md#importrotation)

___

### ImportTranslation

• **ImportTranslation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[ImportTranslation](ue_ue.FbxAssetImportData.md#importtranslation)

___

### ImportUniformScale

• **ImportUniformScale**: `number`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[ImportUniformScale](ue_ue.FbxAssetImportData.md#importuniformscale)

___

### MaterialSearchLocation

• **MaterialSearchLocation**: [`EMaterialSearchLocation`](../enums/ue_ue.EMaterialSearchLocation.md)

___

### SourceData

• **SourceData**: [`AssetImportInfo`](ue_ue.AssetImportInfo.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[SourceData](ue_ue.FbxAssetImportData.md#sourcedata)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[SourceFilePath](ue_ue.FbxAssetImportData.md#sourcefilepath)

___

### SourceFileTimestamp

• **SourceFileTimestamp**: `string`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[SourceFileTimestamp](ue_ue.FbxAssetImportData.md#sourcefiletimestamp)

___

### \_\_tid\_AssetImportData\_\_

• **\_\_tid\_AssetImportData\_\_**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[__tid_AssetImportData__](ue_ue.FbxAssetImportData.md#__tid_assetimportdata__)

___

### \_\_tid\_FbxAssetImportData\_\_

• **\_\_tid\_FbxAssetImportData\_\_**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[__tid_FbxAssetImportData__](ue_ue.FbxAssetImportData.md#__tid_fbxassetimportdata__)

___

### \_\_tid\_FbxTextureImportData\_\_

• **\_\_tid\_FbxTextureImportData\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[__tid_Object__](ue_ue.FbxAssetImportData.md#__tid_object__)

___

### bConvertScene

• **bConvertScene**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[bConvertScene](ue_ue.FbxAssetImportData.md#bconvertscene)

___

### bConvertSceneUnit

• **bConvertSceneUnit**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[bConvertSceneUnit](ue_ue.FbxAssetImportData.md#bconvertsceneunit)

___

### bForceFrontXAxis

• **bForceFrontXAxis**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[bForceFrontXAxis](ue_ue.FbxAssetImportData.md#bforcefrontxaxis)

___

### bImportAsScene

• **bImportAsScene**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[bImportAsScene](ue_ue.FbxAssetImportData.md#bimportasscene)

___

### bInvertNormalMaps

• **bInvertNormalMaps**: `boolean`

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

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[CreateDefaultSubobject](ue_ue.FbxAssetImportData.md#createdefaultsubobject)

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

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[ExecuteUbergraph](ue_ue.FbxAssetImportData.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[GetClass](ue_ue.FbxAssetImportData.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[GetName](ue_ue.FbxAssetImportData.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[GetOuter](ue_ue.FbxAssetImportData.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[GetWorld](ue_ue.FbxAssetImportData.md#getworld)

___

### K2\_ExtractFilenames

▸ **K2_ExtractFilenames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[K2_ExtractFilenames](ue_ue.FbxAssetImportData.md#k2_extractfilenames)

___

### K2\_GetFirstFilename

▸ **K2_GetFirstFilename**(): `string`

#### Returns

`string`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[K2_GetFirstFilename](ue_ue.FbxAssetImportData.md#k2_getfirstfilename)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FbxTextureImportData`](ue_ue.FbxTextureImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FbxTextureImportData`](ue_ue.FbxTextureImportData.md)

#### Overrides

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[Find](ue_ue.FbxAssetImportData.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`FbxTextureImportData`](ue_ue.FbxTextureImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FbxTextureImportData`](ue_ue.FbxTextureImportData.md)

#### Overrides

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[Load](ue_ue.FbxAssetImportData.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[StaticClass](ue_ue.FbxAssetImportData.md#staticclass)
