[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FbxMeshImportData

# Class: FbxMeshImportData

[ue/ue](../modules/ue_ue.md).FbxMeshImportData

## Hierarchy

- [`FbxAssetImportData`](ue_ue.FbxAssetImportData.md)

  ↳ **`FbxMeshImportData`**

  ↳↳ [`FbxStaticMeshImportData`](ue_ue.FbxStaticMeshImportData.md)

  ↳↳ [`FbxSkeletalMeshImportData`](ue_ue.FbxSkeletalMeshImportData.md)

## Table of contents

### Constructors

- [constructor](ue_ue.FbxMeshImportData.md#constructor)

### Properties

- [FbxSceneImportDataReference](ue_ue.FbxMeshImportData.md#fbxsceneimportdatareference)
- [ImportMaterialOriginalNameData](ue_ue.FbxMeshImportData.md#importmaterialoriginalnamedata)
- [ImportMeshLodData](ue_ue.FbxMeshImportData.md#importmeshloddata)
- [ImportRotation](ue_ue.FbxMeshImportData.md#importrotation)
- [ImportTranslation](ue_ue.FbxMeshImportData.md#importtranslation)
- [ImportUniformScale](ue_ue.FbxMeshImportData.md#importuniformscale)
- [NormalGenerationMethod](ue_ue.FbxMeshImportData.md#normalgenerationmethod)
- [NormalImportMethod](ue_ue.FbxMeshImportData.md#normalimportmethod)
- [SourceData](ue_ue.FbxMeshImportData.md#sourcedata)
- [SourceFilePath](ue_ue.FbxMeshImportData.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.FbxMeshImportData.md#sourcefiletimestamp)
- [\_\_tid\_AssetImportData\_\_](ue_ue.FbxMeshImportData.md#__tid_assetimportdata__)
- [\_\_tid\_FbxAssetImportData\_\_](ue_ue.FbxMeshImportData.md#__tid_fbxassetimportdata__)
- [\_\_tid\_FbxMeshImportData\_\_](ue_ue.FbxMeshImportData.md#__tid_fbxmeshimportdata__)
- [\_\_tid\_Object\_\_](ue_ue.FbxMeshImportData.md#__tid_object__)
- [bBakePivotInVertex](ue_ue.FbxMeshImportData.md#bbakepivotinvertex)
- [bComputeWeightedNormals](ue_ue.FbxMeshImportData.md#bcomputeweightednormals)
- [bConvertScene](ue_ue.FbxMeshImportData.md#bconvertscene)
- [bConvertSceneUnit](ue_ue.FbxMeshImportData.md#bconvertsceneunit)
- [bForceFrontXAxis](ue_ue.FbxMeshImportData.md#bforcefrontxaxis)
- [bImportAsScene](ue_ue.FbxMeshImportData.md#bimportasscene)
- [bImportMeshLODs](ue_ue.FbxMeshImportData.md#bimportmeshlods)
- [bReorderMaterialToFbxOrder](ue_ue.FbxMeshImportData.md#breordermaterialtofbxorder)
- [bTransformVertexToAbsolute](ue_ue.FbxMeshImportData.md#btransformvertextoabsolute)

### Methods

- [CreateDefaultSubobject](ue_ue.FbxMeshImportData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.FbxMeshImportData.md#executeubergraph)
- [GetClass](ue_ue.FbxMeshImportData.md#getclass)
- [GetName](ue_ue.FbxMeshImportData.md#getname)
- [GetOuter](ue_ue.FbxMeshImportData.md#getouter)
- [GetWorld](ue_ue.FbxMeshImportData.md#getworld)
- [K2\_ExtractFilenames](ue_ue.FbxMeshImportData.md#k2_extractfilenames)
- [K2\_GetFirstFilename](ue_ue.FbxMeshImportData.md#k2_getfirstfilename)
- [Find](ue_ue.FbxMeshImportData.md#find)
- [Load](ue_ue.FbxMeshImportData.md#load)
- [StaticClass](ue_ue.FbxMeshImportData.md#staticclass)

## Constructors

### constructor

• **new FbxMeshImportData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[constructor](ue_ue.FbxAssetImportData.md#constructor)

## Properties

### FbxSceneImportDataReference

• **FbxSceneImportDataReference**: [`FbxSceneImportData`](ue_ue.FbxSceneImportData.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[FbxSceneImportDataReference](ue_ue.FbxAssetImportData.md#fbxsceneimportdatareference)

___

### ImportMaterialOriginalNameData

• **ImportMaterialOriginalNameData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ImportMeshLodData

• **ImportMeshLodData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ImportMeshLodSectionsData`](ue_ue.ImportMeshLodSectionsData.md)\>

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

### NormalGenerationMethod

• **NormalGenerationMethod**: [`EFBXNormalGenerationMethod`](../enums/ue_ue.EFBXNormalGenerationMethod.md)

___

### NormalImportMethod

• **NormalImportMethod**: [`EFBXNormalImportMethod`](../enums/ue_ue.EFBXNormalImportMethod.md)

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

### \_\_tid\_FbxMeshImportData\_\_

• **\_\_tid\_FbxMeshImportData\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[__tid_Object__](ue_ue.FbxAssetImportData.md#__tid_object__)

___

### bBakePivotInVertex

• **bBakePivotInVertex**: `boolean`

___

### bComputeWeightedNormals

• **bComputeWeightedNormals**: `boolean`

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

### bImportMeshLODs

• **bImportMeshLODs**: `boolean`

___

### bReorderMaterialToFbxOrder

• **bReorderMaterialToFbxOrder**: `boolean`

___

### bTransformVertexToAbsolute

• **bTransformVertexToAbsolute**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FbxMeshImportData`](ue_ue.FbxMeshImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FbxMeshImportData`](ue_ue.FbxMeshImportData.md)

#### Overrides

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[Find](ue_ue.FbxAssetImportData.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`FbxMeshImportData`](ue_ue.FbxMeshImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FbxMeshImportData`](ue_ue.FbxMeshImportData.md)

#### Overrides

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[Load](ue_ue.FbxAssetImportData.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[StaticClass](ue_ue.FbxAssetImportData.md#staticclass)
