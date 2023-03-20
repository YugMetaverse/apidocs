[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FbxSkeletalMeshImportData

# Class: FbxSkeletalMeshImportData

[ue/ue](../modules/ue_ue.md).FbxSkeletalMeshImportData

## Hierarchy

- [`FbxMeshImportData`](ue_ue.FbxMeshImportData.md)

  ↳ **`FbxSkeletalMeshImportData`**

## Table of contents

### Constructors

- [constructor](ue_ue.FbxSkeletalMeshImportData.md#constructor)

### Properties

- [FbxSceneImportDataReference](ue_ue.FbxSkeletalMeshImportData.md#fbxsceneimportdatareference)
- [ImportContentType](ue_ue.FbxSkeletalMeshImportData.md#importcontenttype)
- [ImportMaterialOriginalNameData](ue_ue.FbxSkeletalMeshImportData.md#importmaterialoriginalnamedata)
- [ImportMeshLodData](ue_ue.FbxSkeletalMeshImportData.md#importmeshloddata)
- [ImportRotation](ue_ue.FbxSkeletalMeshImportData.md#importrotation)
- [ImportTranslation](ue_ue.FbxSkeletalMeshImportData.md#importtranslation)
- [ImportUniformScale](ue_ue.FbxSkeletalMeshImportData.md#importuniformscale)
- [LastImportContentType](ue_ue.FbxSkeletalMeshImportData.md#lastimportcontenttype)
- [NormalGenerationMethod](ue_ue.FbxSkeletalMeshImportData.md#normalgenerationmethod)
- [NormalImportMethod](ue_ue.FbxSkeletalMeshImportData.md#normalimportmethod)
- [SourceData](ue_ue.FbxSkeletalMeshImportData.md#sourcedata)
- [SourceFilePath](ue_ue.FbxSkeletalMeshImportData.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.FbxSkeletalMeshImportData.md#sourcefiletimestamp)
- [ThresholdPosition](ue_ue.FbxSkeletalMeshImportData.md#thresholdposition)
- [ThresholdTangentNormal](ue_ue.FbxSkeletalMeshImportData.md#thresholdtangentnormal)
- [ThresholdUV](ue_ue.FbxSkeletalMeshImportData.md#thresholduv)
- [VertexColorImportOption](ue_ue.FbxSkeletalMeshImportData.md#vertexcolorimportoption)
- [VertexOverrideColor](ue_ue.FbxSkeletalMeshImportData.md#vertexoverridecolor)
- [\_\_tid\_AssetImportData\_\_](ue_ue.FbxSkeletalMeshImportData.md#__tid_assetimportdata__)
- [\_\_tid\_FbxAssetImportData\_\_](ue_ue.FbxSkeletalMeshImportData.md#__tid_fbxassetimportdata__)
- [\_\_tid\_FbxMeshImportData\_\_](ue_ue.FbxSkeletalMeshImportData.md#__tid_fbxmeshimportdata__)
- [\_\_tid\_FbxSkeletalMeshImportData\_\_](ue_ue.FbxSkeletalMeshImportData.md#__tid_fbxskeletalmeshimportdata__)
- [\_\_tid\_Object\_\_](ue_ue.FbxSkeletalMeshImportData.md#__tid_object__)
- [bBakePivotInVertex](ue_ue.FbxSkeletalMeshImportData.md#bbakepivotinvertex)
- [bComputeWeightedNormals](ue_ue.FbxSkeletalMeshImportData.md#bcomputeweightednormals)
- [bConvertScene](ue_ue.FbxSkeletalMeshImportData.md#bconvertscene)
- [bConvertSceneUnit](ue_ue.FbxSkeletalMeshImportData.md#bconvertsceneunit)
- [bForceFrontXAxis](ue_ue.FbxSkeletalMeshImportData.md#bforcefrontxaxis)
- [bImportAsScene](ue_ue.FbxSkeletalMeshImportData.md#bimportasscene)
- [bImportMeshLODs](ue_ue.FbxSkeletalMeshImportData.md#bimportmeshlods)
- [bImportMeshesInBoneHierarchy](ue_ue.FbxSkeletalMeshImportData.md#bimportmeshesinbonehierarchy)
- [bImportMorphTargets](ue_ue.FbxSkeletalMeshImportData.md#bimportmorphtargets)
- [bPreserveSmoothingGroups](ue_ue.FbxSkeletalMeshImportData.md#bpreservesmoothinggroups)
- [bReorderMaterialToFbxOrder](ue_ue.FbxSkeletalMeshImportData.md#breordermaterialtofbxorder)
- [bTransformVertexToAbsolute](ue_ue.FbxSkeletalMeshImportData.md#btransformvertextoabsolute)
- [bUpdateSkeletonReferencePose](ue_ue.FbxSkeletalMeshImportData.md#bupdateskeletonreferencepose)
- [bUseT0AsRefPose](ue_ue.FbxSkeletalMeshImportData.md#buset0asrefpose)

### Methods

- [CreateDefaultSubobject](ue_ue.FbxSkeletalMeshImportData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.FbxSkeletalMeshImportData.md#executeubergraph)
- [GetClass](ue_ue.FbxSkeletalMeshImportData.md#getclass)
- [GetName](ue_ue.FbxSkeletalMeshImportData.md#getname)
- [GetOuter](ue_ue.FbxSkeletalMeshImportData.md#getouter)
- [GetWorld](ue_ue.FbxSkeletalMeshImportData.md#getworld)
- [K2\_ExtractFilenames](ue_ue.FbxSkeletalMeshImportData.md#k2_extractfilenames)
- [K2\_GetFirstFilename](ue_ue.FbxSkeletalMeshImportData.md#k2_getfirstfilename)
- [Find](ue_ue.FbxSkeletalMeshImportData.md#find)
- [Load](ue_ue.FbxSkeletalMeshImportData.md#load)
- [StaticClass](ue_ue.FbxSkeletalMeshImportData.md#staticclass)

## Constructors

### constructor

• **new FbxSkeletalMeshImportData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[constructor](ue_ue.FbxMeshImportData.md#constructor)

## Properties

### FbxSceneImportDataReference

• **FbxSceneImportDataReference**: [`FbxSceneImportData`](ue_ue.FbxSceneImportData.md)

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[FbxSceneImportDataReference](ue_ue.FbxMeshImportData.md#fbxsceneimportdatareference)

___

### ImportContentType

• **ImportContentType**: [`EFBXImportContentType`](../enums/ue_ue.EFBXImportContentType.md)

___

### ImportMaterialOriginalNameData

• **ImportMaterialOriginalNameData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[ImportMaterialOriginalNameData](ue_ue.FbxMeshImportData.md#importmaterialoriginalnamedata)

___

### ImportMeshLodData

• **ImportMeshLodData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ImportMeshLodSectionsData`](ue_ue.ImportMeshLodSectionsData.md)\>

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[ImportMeshLodData](ue_ue.FbxMeshImportData.md#importmeshloddata)

___

### ImportRotation

• **ImportRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[ImportRotation](ue_ue.FbxMeshImportData.md#importrotation)

___

### ImportTranslation

• **ImportTranslation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[ImportTranslation](ue_ue.FbxMeshImportData.md#importtranslation)

___

### ImportUniformScale

• **ImportUniformScale**: `number`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[ImportUniformScale](ue_ue.FbxMeshImportData.md#importuniformscale)

___

### LastImportContentType

• **LastImportContentType**: [`EFBXImportContentType`](../enums/ue_ue.EFBXImportContentType.md)

___

### NormalGenerationMethod

• **NormalGenerationMethod**: [`EFBXNormalGenerationMethod`](../enums/ue_ue.EFBXNormalGenerationMethod.md)

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[NormalGenerationMethod](ue_ue.FbxMeshImportData.md#normalgenerationmethod)

___

### NormalImportMethod

• **NormalImportMethod**: [`EFBXNormalImportMethod`](../enums/ue_ue.EFBXNormalImportMethod.md)

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[NormalImportMethod](ue_ue.FbxMeshImportData.md#normalimportmethod)

___

### SourceData

• **SourceData**: [`AssetImportInfo`](ue_ue.AssetImportInfo.md)

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[SourceData](ue_ue.FbxMeshImportData.md#sourcedata)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[SourceFilePath](ue_ue.FbxMeshImportData.md#sourcefilepath)

___

### SourceFileTimestamp

• **SourceFileTimestamp**: `string`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[SourceFileTimestamp](ue_ue.FbxMeshImportData.md#sourcefiletimestamp)

___

### ThresholdPosition

• **ThresholdPosition**: `number`

___

### ThresholdTangentNormal

• **ThresholdTangentNormal**: `number`

___

### ThresholdUV

• **ThresholdUV**: `number`

___

### VertexColorImportOption

• **VertexColorImportOption**: [`EVertexColorImportOption`](../enums/ue_ue.EVertexColorImportOption.md)

___

### VertexOverrideColor

• **VertexOverrideColor**: [`Color`](ue_ue_s.Color.md)

___

### \_\_tid\_AssetImportData\_\_

• **\_\_tid\_AssetImportData\_\_**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[__tid_AssetImportData__](ue_ue.FbxMeshImportData.md#__tid_assetimportdata__)

___

### \_\_tid\_FbxAssetImportData\_\_

• **\_\_tid\_FbxAssetImportData\_\_**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[__tid_FbxAssetImportData__](ue_ue.FbxMeshImportData.md#__tid_fbxassetimportdata__)

___

### \_\_tid\_FbxMeshImportData\_\_

• **\_\_tid\_FbxMeshImportData\_\_**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[__tid_FbxMeshImportData__](ue_ue.FbxMeshImportData.md#__tid_fbxmeshimportdata__)

___

### \_\_tid\_FbxSkeletalMeshImportData\_\_

• **\_\_tid\_FbxSkeletalMeshImportData\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[__tid_Object__](ue_ue.FbxMeshImportData.md#__tid_object__)

___

### bBakePivotInVertex

• **bBakePivotInVertex**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[bBakePivotInVertex](ue_ue.FbxMeshImportData.md#bbakepivotinvertex)

___

### bComputeWeightedNormals

• **bComputeWeightedNormals**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[bComputeWeightedNormals](ue_ue.FbxMeshImportData.md#bcomputeweightednormals)

___

### bConvertScene

• **bConvertScene**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[bConvertScene](ue_ue.FbxMeshImportData.md#bconvertscene)

___

### bConvertSceneUnit

• **bConvertSceneUnit**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[bConvertSceneUnit](ue_ue.FbxMeshImportData.md#bconvertsceneunit)

___

### bForceFrontXAxis

• **bForceFrontXAxis**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[bForceFrontXAxis](ue_ue.FbxMeshImportData.md#bforcefrontxaxis)

___

### bImportAsScene

• **bImportAsScene**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[bImportAsScene](ue_ue.FbxMeshImportData.md#bimportasscene)

___

### bImportMeshLODs

• **bImportMeshLODs**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[bImportMeshLODs](ue_ue.FbxMeshImportData.md#bimportmeshlods)

___

### bImportMeshesInBoneHierarchy

• **bImportMeshesInBoneHierarchy**: `boolean`

___

### bImportMorphTargets

• **bImportMorphTargets**: `boolean`

___

### bPreserveSmoothingGroups

• **bPreserveSmoothingGroups**: `boolean`

___

### bReorderMaterialToFbxOrder

• **bReorderMaterialToFbxOrder**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[bReorderMaterialToFbxOrder](ue_ue.FbxMeshImportData.md#breordermaterialtofbxorder)

___

### bTransformVertexToAbsolute

• **bTransformVertexToAbsolute**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[bTransformVertexToAbsolute](ue_ue.FbxMeshImportData.md#btransformvertextoabsolute)

___

### bUpdateSkeletonReferencePose

• **bUpdateSkeletonReferencePose**: `boolean`

___

### bUseT0AsRefPose

• **bUseT0AsRefPose**: `boolean`

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

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[CreateDefaultSubobject](ue_ue.FbxMeshImportData.md#createdefaultsubobject)

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

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[ExecuteUbergraph](ue_ue.FbxMeshImportData.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[GetClass](ue_ue.FbxMeshImportData.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[GetName](ue_ue.FbxMeshImportData.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[GetOuter](ue_ue.FbxMeshImportData.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[GetWorld](ue_ue.FbxMeshImportData.md#getworld)

___

### K2\_ExtractFilenames

▸ **K2_ExtractFilenames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[K2_ExtractFilenames](ue_ue.FbxMeshImportData.md#k2_extractfilenames)

___

### K2\_GetFirstFilename

▸ **K2_GetFirstFilename**(): `string`

#### Returns

`string`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[K2_GetFirstFilename](ue_ue.FbxMeshImportData.md#k2_getfirstfilename)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FbxSkeletalMeshImportData`](ue_ue.FbxSkeletalMeshImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FbxSkeletalMeshImportData`](ue_ue.FbxSkeletalMeshImportData.md)

#### Overrides

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[Find](ue_ue.FbxMeshImportData.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`FbxSkeletalMeshImportData`](ue_ue.FbxSkeletalMeshImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FbxSkeletalMeshImportData`](ue_ue.FbxSkeletalMeshImportData.md)

#### Overrides

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[Load](ue_ue.FbxMeshImportData.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[StaticClass](ue_ue.FbxMeshImportData.md#staticclass)
