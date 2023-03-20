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

## Properties

### ExportSpecificLOD

• **ExportSpecificLOD**: `number`

___

### GutterSize

• **GutterSize**: `number`

___

### LODSelectionType

• **LODSelectionType**: [`EMeshLODSelectionType`](../enums/ue_ue.EMeshLODSelectionType.md)

___

### MaterialSettings

• **MaterialSettings**: [`MaterialProxySettings`](ue_ue.MaterialProxySettings.md)

___

### MergedMaterialAtlasResolution

• **MergedMaterialAtlasResolution**: `number`

___

### OutputUVs

• **OutputUVs**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`EUVOutput`](../enums/ue_ue.EUVOutput.md)\>

___

### SpecificLOD

• **SpecificLOD**: `number`

___

### TargetLightMapResolution

• **TargetLightMapResolution**: `number`

___

### \_\_tid\_MeshMergingSettings\_\_

• `Private` **\_\_tid\_MeshMergingSettings\_\_**: `boolean`

___

### bAllowDistanceField

• **bAllowDistanceField**: `boolean`

___

### bBakeVertexDataToMesh

• **bBakeVertexDataToMesh**: `boolean`

___

### bCalculateCorrectLODModel

• **bCalculateCorrectLODModel**: `boolean`

___

### bComputedLightMapResolution

• **bComputedLightMapResolution**: `boolean`

___

### bCreateMergedMaterial

• **bCreateMergedMaterial**: `boolean`

___

### bExportMetallicMap

• **bExportMetallicMap**: `boolean`

___

### bExportNormalMap

• **bExportNormalMap**: `boolean`

___

### bExportRoughnessMap

• **bExportRoughnessMap**: `boolean`

___

### bExportSpecularMap

• **bExportSpecularMap**: `boolean`

___

### bGenerateLightMapUV

• **bGenerateLightMapUV**: `boolean`

___

### bImportVertexColors

• **bImportVertexColors**: `boolean`

___

### bIncludeImposters

• **bIncludeImposters**: `boolean`

___

### bMergeEquivalentMaterials

• **bMergeEquivalentMaterials**: `boolean`

___

### bMergeMaterials

• **bMergeMaterials**: `boolean`

___

### bMergePhysicsData

• **bMergePhysicsData**: `boolean`

___

### bPivotPointAtZero

• **bPivotPointAtZero**: `boolean`

___

### bReuseMeshLightmapUVs

• **bReuseMeshLightmapUVs**: `boolean`

___

### bUseLandscapeCulling

• **bUseLandscapeCulling**: `boolean`

___

### bUseTextureBinning

• **bUseTextureBinning**: `boolean`

___

### bUseVertexDataForBakingMaterial

• **bUseVertexDataForBakingMaterial**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
