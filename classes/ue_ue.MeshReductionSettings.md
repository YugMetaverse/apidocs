[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MeshReductionSettings

# Class: MeshReductionSettings

[ue/ue](../modules/ue_ue.md).MeshReductionSettings

## Table of contents

### Constructors

- [constructor](ue_ue.MeshReductionSettings.md#constructor)

### Properties

- [BaseLODModel](ue_ue.MeshReductionSettings.md#baselodmodel)
- [HardAngleThreshold](ue_ue.MeshReductionSettings.md#hardanglethreshold)
- [MaxDeviation](ue_ue.MeshReductionSettings.md#maxdeviation)
- [PercentTriangles](ue_ue.MeshReductionSettings.md#percenttriangles)
- [PercentVertices](ue_ue.MeshReductionSettings.md#percentvertices)
- [PixelError](ue_ue.MeshReductionSettings.md#pixelerror)
- [ShadingImportance](ue_ue.MeshReductionSettings.md#shadingimportance)
- [SilhouetteImportance](ue_ue.MeshReductionSettings.md#silhouetteimportance)
- [TerminationCriterion](ue_ue.MeshReductionSettings.md#terminationcriterion)
- [TextureImportance](ue_ue.MeshReductionSettings.md#textureimportance)
- [VertexColorImportance](ue_ue.MeshReductionSettings.md#vertexcolorimportance)
- [VisibilityAggressiveness](ue_ue.MeshReductionSettings.md#visibilityaggressiveness)
- [WeldingThreshold](ue_ue.MeshReductionSettings.md#weldingthreshold)
- [\_\_tid\_MeshReductionSettings\_\_](ue_ue.MeshReductionSettings.md#__tid_meshreductionsettings__)
- [bCullOccluded](ue_ue.MeshReductionSettings.md#bculloccluded)
- [bGenerateUniqueLightmapUVs](ue_ue.MeshReductionSettings.md#bgenerateuniquelightmapuvs)
- [bKeepSymmetry](ue_ue.MeshReductionSettings.md#bkeepsymmetry)
- [bRecalculateNormals](ue_ue.MeshReductionSettings.md#brecalculatenormals)
- [bVisibilityAided](ue_ue.MeshReductionSettings.md#bvisibilityaided)

### Methods

- [StaticClass](ue_ue.MeshReductionSettings.md#staticclass)
- [StaticStruct](ue_ue.MeshReductionSettings.md#staticstruct)

## Constructors

### constructor

• **new MeshReductionSettings**()

• **new MeshReductionSettings**(`PercentTriangles`, `PercentVertices`, `MaxDeviation`, `PixelError`, `WeldingThreshold`, `HardAngleThreshold`, `BaseLODModel`, `SilhouetteImportance`, `TextureImportance`, `ShadingImportance`, `bRecalculateNormals`, `bGenerateUniqueLightmapUVs`, `bKeepSymmetry`, `bVisibilityAided`, `bCullOccluded`, `TerminationCriterion`, `VisibilityAggressiveness`, `VertexColorImportance`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PercentTriangles` | `number` |
| `PercentVertices` | `number` |
| `MaxDeviation` | `number` |
| `PixelError` | `number` |
| `WeldingThreshold` | `number` |
| `HardAngleThreshold` | `number` |
| `BaseLODModel` | `number` |
| `SilhouetteImportance` | [`EMeshFeatureImportance`](../enums/ue_ue.EMeshFeatureImportance.md) |
| `TextureImportance` | [`EMeshFeatureImportance`](../enums/ue_ue.EMeshFeatureImportance.md) |
| `ShadingImportance` | [`EMeshFeatureImportance`](../enums/ue_ue.EMeshFeatureImportance.md) |
| `bRecalculateNormals` | `boolean` |
| `bGenerateUniqueLightmapUVs` | `boolean` |
| `bKeepSymmetry` | `boolean` |
| `bVisibilityAided` | `boolean` |
| `bCullOccluded` | `boolean` |
| `TerminationCriterion` | [`EStaticMeshReductionTerimationCriterion`](../enums/ue_ue.EStaticMeshReductionTerimationCriterion.md) |
| `VisibilityAggressiveness` | [`EMeshFeatureImportance`](../enums/ue_ue.EMeshFeatureImportance.md) |
| `VertexColorImportance` | [`EMeshFeatureImportance`](../enums/ue_ue.EMeshFeatureImportance.md) |

## Properties

### BaseLODModel

• **BaseLODModel**: `number`

___

### HardAngleThreshold

• **HardAngleThreshold**: `number`

___

### MaxDeviation

• **MaxDeviation**: `number`

___

### PercentTriangles

• **PercentTriangles**: `number`

___

### PercentVertices

• **PercentVertices**: `number`

___

### PixelError

• **PixelError**: `number`

___

### ShadingImportance

• **ShadingImportance**: [`EMeshFeatureImportance`](../enums/ue_ue.EMeshFeatureImportance.md)

___

### SilhouetteImportance

• **SilhouetteImportance**: [`EMeshFeatureImportance`](../enums/ue_ue.EMeshFeatureImportance.md)

___

### TerminationCriterion

• **TerminationCriterion**: [`EStaticMeshReductionTerimationCriterion`](../enums/ue_ue.EStaticMeshReductionTerimationCriterion.md)

___

### TextureImportance

• **TextureImportance**: [`EMeshFeatureImportance`](../enums/ue_ue.EMeshFeatureImportance.md)

___

### VertexColorImportance

• **VertexColorImportance**: [`EMeshFeatureImportance`](../enums/ue_ue.EMeshFeatureImportance.md)

___

### VisibilityAggressiveness

• **VisibilityAggressiveness**: [`EMeshFeatureImportance`](../enums/ue_ue.EMeshFeatureImportance.md)

___

### WeldingThreshold

• **WeldingThreshold**: `number`

___

### \_\_tid\_MeshReductionSettings\_\_

• `Private` **\_\_tid\_MeshReductionSettings\_\_**: `boolean`

___

### bCullOccluded

• **bCullOccluded**: `boolean`

___

### bGenerateUniqueLightmapUVs

• **bGenerateUniqueLightmapUVs**: `boolean`

___

### bKeepSymmetry

• **bKeepSymmetry**: `boolean`

___

### bRecalculateNormals

• **bRecalculateNormals**: `boolean`

___

### bVisibilityAided

• **bVisibilityAided**: `boolean`

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
