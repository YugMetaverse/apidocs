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

#### Defined in

[ue/ue.d.ts:7750](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7750)

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

#### Defined in

[ue/ue.d.ts:7751](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7751)

## Properties

### BaseLODModel

• **BaseLODModel**: `number`

#### Defined in

[ue/ue.d.ts:7758](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7758)

___

### HardAngleThreshold

• **HardAngleThreshold**: `number`

#### Defined in

[ue/ue.d.ts:7757](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7757)

___

### MaxDeviation

• **MaxDeviation**: `number`

#### Defined in

[ue/ue.d.ts:7754](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7754)

___

### PercentTriangles

• **PercentTriangles**: `number`

#### Defined in

[ue/ue.d.ts:7752](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7752)

___

### PercentVertices

• **PercentVertices**: `number`

#### Defined in

[ue/ue.d.ts:7753](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7753)

___

### PixelError

• **PixelError**: `number`

#### Defined in

[ue/ue.d.ts:7755](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7755)

___

### ShadingImportance

• **ShadingImportance**: [`EMeshFeatureImportance`](../enums/ue_ue.EMeshFeatureImportance.md)

#### Defined in

[ue/ue.d.ts:7761](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7761)

___

### SilhouetteImportance

• **SilhouetteImportance**: [`EMeshFeatureImportance`](../enums/ue_ue.EMeshFeatureImportance.md)

#### Defined in

[ue/ue.d.ts:7759](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7759)

___

### TerminationCriterion

• **TerminationCriterion**: [`EStaticMeshReductionTerimationCriterion`](../enums/ue_ue.EStaticMeshReductionTerimationCriterion.md)

#### Defined in

[ue/ue.d.ts:7767](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7767)

___

### TextureImportance

• **TextureImportance**: [`EMeshFeatureImportance`](../enums/ue_ue.EMeshFeatureImportance.md)

#### Defined in

[ue/ue.d.ts:7760](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7760)

___

### VertexColorImportance

• **VertexColorImportance**: [`EMeshFeatureImportance`](../enums/ue_ue.EMeshFeatureImportance.md)

#### Defined in

[ue/ue.d.ts:7769](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7769)

___

### VisibilityAggressiveness

• **VisibilityAggressiveness**: [`EMeshFeatureImportance`](../enums/ue_ue.EMeshFeatureImportance.md)

#### Defined in

[ue/ue.d.ts:7768](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7768)

___

### WeldingThreshold

• **WeldingThreshold**: `number`

#### Defined in

[ue/ue.d.ts:7756](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7756)

___

### \_\_tid\_MeshReductionSettings\_\_

• `Private` **\_\_tid\_MeshReductionSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:7775](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7775)

___

### bCullOccluded

• **bCullOccluded**: `boolean`

#### Defined in

[ue/ue.d.ts:7766](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7766)

___

### bGenerateUniqueLightmapUVs

• **bGenerateUniqueLightmapUVs**: `boolean`

#### Defined in

[ue/ue.d.ts:7763](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7763)

___

### bKeepSymmetry

• **bKeepSymmetry**: `boolean`

#### Defined in

[ue/ue.d.ts:7764](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7764)

___

### bRecalculateNormals

• **bRecalculateNormals**: `boolean`

#### Defined in

[ue/ue.d.ts:7762](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7762)

___

### bVisibilityAided

• **bVisibilityAided**: `boolean`

#### Defined in

[ue/ue.d.ts:7765](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7765)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:7773](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7773)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:7774](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7774)
