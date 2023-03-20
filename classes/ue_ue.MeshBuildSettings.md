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

#### Defined in

[ue/ue.d.ts:7718](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7718)

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

#### Defined in

[ue/ue.d.ts:7719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7719)

## Properties

### BuildScale

• **BuildScale**: `number`

#### Defined in

[ue/ue.d.ts:7734](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7734)

___

### BuildScale3D

• **BuildScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:7735](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7735)

___

### DistanceFieldBias

• **DistanceFieldBias**: `number`

#### Defined in

[ue/ue.d.ts:7737](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7737)

___

### DistanceFieldReplacementMesh

• **DistanceFieldReplacementMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:7738](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7738)

___

### DistanceFieldResolutionScale

• **DistanceFieldResolutionScale**: `number`

#### Defined in

[ue/ue.d.ts:7736](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7736)

___

### DstLightmapIndex

• **DstLightmapIndex**: `number`

#### Defined in

[ue/ue.d.ts:7733](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7733)

___

### MinLightmapResolution

• **MinLightmapResolution**: `number`

#### Defined in

[ue/ue.d.ts:7731](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7731)

___

### SrcLightmapIndex

• **SrcLightmapIndex**: `number`

#### Defined in

[ue/ue.d.ts:7732](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7732)

___

### \_\_tid\_MeshBuildSettings\_\_

• `Private` **\_\_tid\_MeshBuildSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:7744](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7744)

___

### bBuildAdjacencyBuffer

• **bBuildAdjacencyBuffer**: `boolean`

#### Defined in

[ue/ue.d.ts:7725](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7725)

___

### bBuildReversedIndexBuffer

• **bBuildReversedIndexBuffer**: `boolean`

#### Defined in

[ue/ue.d.ts:7726](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7726)

___

### bComputeWeightedNormals

• **bComputeWeightedNormals**: `boolean`

#### Defined in

[ue/ue.d.ts:7723](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7723)

___

### bGenerateDistanceFieldAsIfTwoSided

• **bGenerateDistanceFieldAsIfTwoSided**: `boolean`

#### Defined in

[ue/ue.d.ts:7730](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7730)

___

### bGenerateLightmapUVs

• **bGenerateLightmapUVs**: `boolean`

#### Defined in

[ue/ue.d.ts:7729](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7729)

___

### bRecomputeNormals

• **bRecomputeNormals**: `boolean`

#### Defined in

[ue/ue.d.ts:7721](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7721)

___

### bRecomputeTangents

• **bRecomputeTangents**: `boolean`

#### Defined in

[ue/ue.d.ts:7722](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7722)

___

### bRemoveDegenerates

• **bRemoveDegenerates**: `boolean`

#### Defined in

[ue/ue.d.ts:7724](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7724)

___

### bUseFullPrecisionUVs

• **bUseFullPrecisionUVs**: `boolean`

#### Defined in

[ue/ue.d.ts:7728](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7728)

___

### bUseHighPrecisionTangentBasis

• **bUseHighPrecisionTangentBasis**: `boolean`

#### Defined in

[ue/ue.d.ts:7727](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7727)

___

### bUseMikkTSpace

• **bUseMikkTSpace**: `boolean`

#### Defined in

[ue/ue.d.ts:7720](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7720)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:7742](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7742)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:7743](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7743)
