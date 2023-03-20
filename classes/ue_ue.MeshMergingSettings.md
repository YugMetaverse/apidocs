[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MeshMergingSettings

# Class: MeshMergingSettings

[ue/ue](../modules/ue_ue.md).MeshMergingSettings

## Table of contents

### Constructors

- [constructor](ue_ue.MeshMergingSettings.md#constructor)

### Properties

- [ExportSpecificLOD](ue_ue.MeshMergingSettings.md#exportspecificlod)
- [GutterSize](ue_ue.MeshMergingSettings.md#guttersize)
- [LODSelectionType](ue_ue.MeshMergingSettings.md#lodselectiontype)
- [MaterialSettings](ue_ue.MeshMergingSettings.md#materialsettings)
- [MergedMaterialAtlasResolution](ue_ue.MeshMergingSettings.md#mergedmaterialatlasresolution)
- [OutputUVs](ue_ue.MeshMergingSettings.md#outputuvs)
- [SpecificLOD](ue_ue.MeshMergingSettings.md#specificlod)
- [TargetLightMapResolution](ue_ue.MeshMergingSettings.md#targetlightmapresolution)
- [\_\_tid\_MeshMergingSettings\_\_](ue_ue.MeshMergingSettings.md#__tid_meshmergingsettings__)
- [bAllowDistanceField](ue_ue.MeshMergingSettings.md#ballowdistancefield)
- [bBakeVertexDataToMesh](ue_ue.MeshMergingSettings.md#bbakevertexdatatomesh)
- [bCalculateCorrectLODModel](ue_ue.MeshMergingSettings.md#bcalculatecorrectlodmodel)
- [bComputedLightMapResolution](ue_ue.MeshMergingSettings.md#bcomputedlightmapresolution)
- [bCreateMergedMaterial](ue_ue.MeshMergingSettings.md#bcreatemergedmaterial)
- [bExportMetallicMap](ue_ue.MeshMergingSettings.md#bexportmetallicmap)
- [bExportNormalMap](ue_ue.MeshMergingSettings.md#bexportnormalmap)
- [bExportRoughnessMap](ue_ue.MeshMergingSettings.md#bexportroughnessmap)
- [bExportSpecularMap](ue_ue.MeshMergingSettings.md#bexportspecularmap)
- [bGenerateLightMapUV](ue_ue.MeshMergingSettings.md#bgeneratelightmapuv)
- [bImportVertexColors](ue_ue.MeshMergingSettings.md#bimportvertexcolors)
- [bIncludeImposters](ue_ue.MeshMergingSettings.md#bincludeimposters)
- [bMergeEquivalentMaterials](ue_ue.MeshMergingSettings.md#bmergeequivalentmaterials)
- [bMergeMaterials](ue_ue.MeshMergingSettings.md#bmergematerials)
- [bMergePhysicsData](ue_ue.MeshMergingSettings.md#bmergephysicsdata)
- [bPivotPointAtZero](ue_ue.MeshMergingSettings.md#bpivotpointatzero)
- [bReuseMeshLightmapUVs](ue_ue.MeshMergingSettings.md#breusemeshlightmapuvs)
- [bUseLandscapeCulling](ue_ue.MeshMergingSettings.md#buselandscapeculling)
- [bUseTextureBinning](ue_ue.MeshMergingSettings.md#busetexturebinning)
- [bUseVertexDataForBakingMaterial](ue_ue.MeshMergingSettings.md#busevertexdataforbakingmaterial)

### Methods

- [StaticClass](ue_ue.MeshMergingSettings.md#staticclass)
- [StaticStruct](ue_ue.MeshMergingSettings.md#staticstruct)

## Constructors

### constructor

• **new MeshMergingSettings**()

#### Defined in

[ue/ue.d.ts:9008](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9008)

• **new MeshMergingSettings**(`TargetLightMapResolution`, `OutputUVs`, `MaterialSettings`, `GutterSize`, `SpecificLOD`, `LODSelectionType`, `bGenerateLightMapUV`, `bComputedLightMapResolution`, `bPivotPointAtZero`, `bMergePhysicsData`, `bMergeMaterials`, `bCreateMergedMaterial`, `bBakeVertexDataToMesh`, `bUseVertexDataForBakingMaterial`, `bUseTextureBinning`, `bReuseMeshLightmapUVs`, `bMergeEquivalentMaterials`, `bUseLandscapeCulling`, `bIncludeImposters`, `bAllowDistanceField`, `bImportVertexColors`, `bCalculateCorrectLODModel`, `bExportNormalMap`, `bExportMetallicMap`, `bExportRoughnessMap`, `bExportSpecularMap`, `MergedMaterialAtlasResolution`, `ExportSpecificLOD`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetLightMapResolution` | `number` |
| `OutputUVs` | [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`EUVOutput`](../enums/ue_ue.EUVOutput.md)\> |
| `MaterialSettings` | [`MaterialProxySettings`](ue_ue.MaterialProxySettings.md) |
| `GutterSize` | `number` |
| `SpecificLOD` | `number` |
| `LODSelectionType` | [`EMeshLODSelectionType`](../enums/ue_ue.EMeshLODSelectionType.md) |
| `bGenerateLightMapUV` | `boolean` |
| `bComputedLightMapResolution` | `boolean` |
| `bPivotPointAtZero` | `boolean` |
| `bMergePhysicsData` | `boolean` |
| `bMergeMaterials` | `boolean` |
| `bCreateMergedMaterial` | `boolean` |
| `bBakeVertexDataToMesh` | `boolean` |
| `bUseVertexDataForBakingMaterial` | `boolean` |
| `bUseTextureBinning` | `boolean` |
| `bReuseMeshLightmapUVs` | `boolean` |
| `bMergeEquivalentMaterials` | `boolean` |
| `bUseLandscapeCulling` | `boolean` |
| `bIncludeImposters` | `boolean` |
| `bAllowDistanceField` | `boolean` |
| `bImportVertexColors` | `boolean` |
| `bCalculateCorrectLODModel` | `boolean` |
| `bExportNormalMap` | `boolean` |
| `bExportMetallicMap` | `boolean` |
| `bExportRoughnessMap` | `boolean` |
| `bExportSpecularMap` | `boolean` |
| `MergedMaterialAtlasResolution` | `number` |
| `ExportSpecificLOD` | `number` |

#### Defined in

[ue/ue.d.ts:9009](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9009)

## Properties

### ExportSpecificLOD

• **ExportSpecificLOD**: `number`

#### Defined in

[ue/ue.d.ts:9037](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9037)

___

### GutterSize

• **GutterSize**: `number`

#### Defined in

[ue/ue.d.ts:9013](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9013)

___

### LODSelectionType

• **LODSelectionType**: [`EMeshLODSelectionType`](../enums/ue_ue.EMeshLODSelectionType.md)

#### Defined in

[ue/ue.d.ts:9015](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9015)

___

### MaterialSettings

• **MaterialSettings**: [`MaterialProxySettings`](ue_ue.MaterialProxySettings.md)

#### Defined in

[ue/ue.d.ts:9012](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9012)

___

### MergedMaterialAtlasResolution

• **MergedMaterialAtlasResolution**: `number`

#### Defined in

[ue/ue.d.ts:9036](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9036)

___

### OutputUVs

• **OutputUVs**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`EUVOutput`](../enums/ue_ue.EUVOutput.md)\>

#### Defined in

[ue/ue.d.ts:9011](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9011)

___

### SpecificLOD

• **SpecificLOD**: `number`

#### Defined in

[ue/ue.d.ts:9014](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9014)

___

### TargetLightMapResolution

• **TargetLightMapResolution**: `number`

#### Defined in

[ue/ue.d.ts:9010](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9010)

___

### \_\_tid\_MeshMergingSettings\_\_

• `Private` **\_\_tid\_MeshMergingSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:9043](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9043)

___

### bAllowDistanceField

• **bAllowDistanceField**: `boolean`

#### Defined in

[ue/ue.d.ts:9029](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9029)

___

### bBakeVertexDataToMesh

• **bBakeVertexDataToMesh**: `boolean`

#### Defined in

[ue/ue.d.ts:9022](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9022)

___

### bCalculateCorrectLODModel

• **bCalculateCorrectLODModel**: `boolean`

#### Defined in

[ue/ue.d.ts:9031](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9031)

___

### bComputedLightMapResolution

• **bComputedLightMapResolution**: `boolean`

#### Defined in

[ue/ue.d.ts:9017](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9017)

___

### bCreateMergedMaterial

• **bCreateMergedMaterial**: `boolean`

#### Defined in

[ue/ue.d.ts:9021](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9021)

___

### bExportMetallicMap

• **bExportMetallicMap**: `boolean`

#### Defined in

[ue/ue.d.ts:9033](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9033)

___

### bExportNormalMap

• **bExportNormalMap**: `boolean`

#### Defined in

[ue/ue.d.ts:9032](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9032)

___

### bExportRoughnessMap

• **bExportRoughnessMap**: `boolean`

#### Defined in

[ue/ue.d.ts:9034](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9034)

___

### bExportSpecularMap

• **bExportSpecularMap**: `boolean`

#### Defined in

[ue/ue.d.ts:9035](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9035)

___

### bGenerateLightMapUV

• **bGenerateLightMapUV**: `boolean`

#### Defined in

[ue/ue.d.ts:9016](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9016)

___

### bImportVertexColors

• **bImportVertexColors**: `boolean`

#### Defined in

[ue/ue.d.ts:9030](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9030)

___

### bIncludeImposters

• **bIncludeImposters**: `boolean`

#### Defined in

[ue/ue.d.ts:9028](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9028)

___

### bMergeEquivalentMaterials

• **bMergeEquivalentMaterials**: `boolean`

#### Defined in

[ue/ue.d.ts:9026](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9026)

___

### bMergeMaterials

• **bMergeMaterials**: `boolean`

#### Defined in

[ue/ue.d.ts:9020](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9020)

___

### bMergePhysicsData

• **bMergePhysicsData**: `boolean`

#### Defined in

[ue/ue.d.ts:9019](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9019)

___

### bPivotPointAtZero

• **bPivotPointAtZero**: `boolean`

#### Defined in

[ue/ue.d.ts:9018](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9018)

___

### bReuseMeshLightmapUVs

• **bReuseMeshLightmapUVs**: `boolean`

#### Defined in

[ue/ue.d.ts:9025](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9025)

___

### bUseLandscapeCulling

• **bUseLandscapeCulling**: `boolean`

#### Defined in

[ue/ue.d.ts:9027](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9027)

___

### bUseTextureBinning

• **bUseTextureBinning**: `boolean`

#### Defined in

[ue/ue.d.ts:9024](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9024)

___

### bUseVertexDataForBakingMaterial

• **bUseVertexDataForBakingMaterial**: `boolean`

#### Defined in

[ue/ue.d.ts:9023](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9023)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:9041](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9041)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:9042](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9042)
