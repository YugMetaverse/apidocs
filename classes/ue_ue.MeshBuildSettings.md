[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MeshBuildSettings

# Class: MeshBuildSettings

[ue/ue](../modules/ue_ue.md).MeshBuildSettings

## Table of contents

### Constructors

- [constructor](ue_ue.MeshBuildSettings.md#constructor)

### Properties

- [BuildScale](ue_ue.MeshBuildSettings.md#buildscale)
- [BuildScale3D](ue_ue.MeshBuildSettings.md#buildscale3d)
- [DistanceFieldBias](ue_ue.MeshBuildSettings.md#distancefieldbias)
- [DistanceFieldReplacementMesh](ue_ue.MeshBuildSettings.md#distancefieldreplacementmesh)
- [DistanceFieldResolutionScale](ue_ue.MeshBuildSettings.md#distancefieldresolutionscale)
- [DstLightmapIndex](ue_ue.MeshBuildSettings.md#dstlightmapindex)
- [MinLightmapResolution](ue_ue.MeshBuildSettings.md#minlightmapresolution)
- [SrcLightmapIndex](ue_ue.MeshBuildSettings.md#srclightmapindex)
- [\_\_tid\_MeshBuildSettings\_\_](ue_ue.MeshBuildSettings.md#__tid_meshbuildsettings__)
- [bBuildAdjacencyBuffer](ue_ue.MeshBuildSettings.md#bbuildadjacencybuffer)
- [bBuildReversedIndexBuffer](ue_ue.MeshBuildSettings.md#bbuildreversedindexbuffer)
- [bComputeWeightedNormals](ue_ue.MeshBuildSettings.md#bcomputeweightednormals)
- [bGenerateDistanceFieldAsIfTwoSided](ue_ue.MeshBuildSettings.md#bgeneratedistancefieldasiftwosided)
- [bGenerateLightmapUVs](ue_ue.MeshBuildSettings.md#bgeneratelightmapuvs)
- [bRecomputeNormals](ue_ue.MeshBuildSettings.md#brecomputenormals)
- [bRecomputeTangents](ue_ue.MeshBuildSettings.md#brecomputetangents)
- [bRemoveDegenerates](ue_ue.MeshBuildSettings.md#bremovedegenerates)
- [bUseFullPrecisionUVs](ue_ue.MeshBuildSettings.md#busefullprecisionuvs)
- [bUseHighPrecisionTangentBasis](ue_ue.MeshBuildSettings.md#busehighprecisiontangentbasis)
- [bUseMikkTSpace](ue_ue.MeshBuildSettings.md#busemikktspace)

### Methods

- [StaticClass](ue_ue.MeshBuildSettings.md#staticclass)
- [StaticStruct](ue_ue.MeshBuildSettings.md#staticstruct)

## Constructors

### constructor

• **new MeshBuildSettings**()

• **new MeshBuildSettings**(`bUseMikkTSpace`, `bRecomputeNormals`, `bRecomputeTangents`, `bComputeWeightedNormals`, `bRemoveDegenerates`, `bBuildAdjacencyBuffer`, `bBuildReversedIndexBuffer`, `bUseHighPrecisionTangentBasis`, `bUseFullPrecisionUVs`, `bGenerateLightmapUVs`, `bGenerateDistanceFieldAsIfTwoSided`, `MinLightmapResolution`, `SrcLightmapIndex`, `DstLightmapIndex`, `BuildScale`, `BuildScale3D`, `DistanceFieldResolutionScale`, `DistanceFieldBias`, `DistanceFieldReplacementMesh`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `bUseMikkTSpace` | `boolean` |
| `bRecomputeNormals` | `boolean` |
| `bRecomputeTangents` | `boolean` |
| `bComputeWeightedNormals` | `boolean` |
| `bRemoveDegenerates` | `boolean` |
| `bBuildAdjacencyBuffer` | `boolean` |
| `bBuildReversedIndexBuffer` | `boolean` |
| `bUseHighPrecisionTangentBasis` | `boolean` |
| `bUseFullPrecisionUVs` | `boolean` |
| `bGenerateLightmapUVs` | `boolean` |
| `bGenerateDistanceFieldAsIfTwoSided` | `boolean` |
| `MinLightmapResolution` | `number` |
| `SrcLightmapIndex` | `number` |
| `DstLightmapIndex` | `number` |
| `BuildScale` | `number` |
| `BuildScale3D` | [`Vector`](ue_ue_s.Vector.md) |
| `DistanceFieldResolutionScale` | `number` |
| `DistanceFieldBias` | `number` |
| `DistanceFieldReplacementMesh` | [`StaticMesh`](ue_ue.StaticMesh.md) |

## Properties

### BuildScale

• **BuildScale**: `number`

___

### BuildScale3D

• **BuildScale3D**: [`Vector`](ue_ue_s.Vector.md)

___

### DistanceFieldBias

• **DistanceFieldBias**: `number`

___

### DistanceFieldReplacementMesh

• **DistanceFieldReplacementMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### DistanceFieldResolutionScale

• **DistanceFieldResolutionScale**: `number`

___

### DstLightmapIndex

• **DstLightmapIndex**: `number`

___

### MinLightmapResolution

• **MinLightmapResolution**: `number`

___

### SrcLightmapIndex

• **SrcLightmapIndex**: `number`

___

### \_\_tid\_MeshBuildSettings\_\_

• `Private` **\_\_tid\_MeshBuildSettings\_\_**: `boolean`

___

### bBuildAdjacencyBuffer

• **bBuildAdjacencyBuffer**: `boolean`

___

### bBuildReversedIndexBuffer

• **bBuildReversedIndexBuffer**: `boolean`

___

### bComputeWeightedNormals

• **bComputeWeightedNormals**: `boolean`

___

### bGenerateDistanceFieldAsIfTwoSided

• **bGenerateDistanceFieldAsIfTwoSided**: `boolean`

___

### bGenerateLightmapUVs

• **bGenerateLightmapUVs**: `boolean`

___

### bRecomputeNormals

• **bRecomputeNormals**: `boolean`

___

### bRecomputeTangents

• **bRecomputeTangents**: `boolean`

___

### bRemoveDegenerates

• **bRemoveDegenerates**: `boolean`

___

### bUseFullPrecisionUVs

• **bUseFullPrecisionUVs**: `boolean`

___

### bUseHighPrecisionTangentBasis

• **bUseHighPrecisionTangentBasis**: `boolean`

___

### bUseMikkTSpace

• **bUseMikkTSpace**: `boolean`

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
