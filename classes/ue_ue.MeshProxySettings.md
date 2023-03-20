[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MeshProxySettings

# Class: MeshProxySettings

[ue/ue](../modules/ue_ue.md).MeshProxySettings

## Table of contents

### Constructors

- [constructor](ue_ue.MeshProxySettings.md#constructor)

### Properties

- [HardAngleThreshold](ue_ue.MeshProxySettings.md#hardanglethreshold)
- [LandscapeCullingPrecision](ue_ue.MeshProxySettings.md#landscapecullingprecision)
- [LightMapResolution](ue_ue.MeshProxySettings.md#lightmapresolution)
- [MaterialSettings](ue_ue.MeshProxySettings.md#materialsettings)
- [MaxRayCastDist](ue_ue.MeshProxySettings.md#maxraycastdist)
- [MergeDistance](ue_ue.MeshProxySettings.md#mergedistance)
- [NormalCalculationMethod](ue_ue.MeshProxySettings.md#normalcalculationmethod)
- [ScreenSize](ue_ue.MeshProxySettings.md#screensize)
- [TextureHeight](ue_ue.MeshProxySettings.md#textureheight)
- [TextureWidth](ue_ue.MeshProxySettings.md#texturewidth)
- [UnresolvedGeometryColor](ue_ue.MeshProxySettings.md#unresolvedgeometrycolor)
- [VoxelSize](ue_ue.MeshProxySettings.md#voxelsize)
- [\_\_tid\_MeshProxySettings\_\_](ue_ue.MeshProxySettings.md#__tid_meshproxysettings__)
- [bAllowAdjacency](ue_ue.MeshProxySettings.md#ballowadjacency)
- [bAllowDistanceField](ue_ue.MeshProxySettings.md#ballowdistancefield)
- [bAllowVertexColors](ue_ue.MeshProxySettings.md#ballowvertexcolors)
- [bBakeVertexData](ue_ue.MeshProxySettings.md#bbakevertexdata)
- [bCalculateCorrectLODModel](ue_ue.MeshProxySettings.md#bcalculatecorrectlodmodel)
- [bComputeLightMapResolution](ue_ue.MeshProxySettings.md#bcomputelightmapresolution)
- [bCreateCollision](ue_ue.MeshProxySettings.md#bcreatecollision)
- [bExportMetallicMap](ue_ue.MeshProxySettings.md#bexportmetallicmap)
- [bExportNormalMap](ue_ue.MeshProxySettings.md#bexportnormalmap)
- [bExportRoughnessMap](ue_ue.MeshProxySettings.md#bexportroughnessmap)
- [bExportSpecularMap](ue_ue.MeshProxySettings.md#bexportspecularmap)
- [bGenerateLightmapUVs](ue_ue.MeshProxySettings.md#bgeneratelightmapuvs)
- [bOverrideTransferDistance](ue_ue.MeshProxySettings.md#boverridetransferdistance)
- [bOverrideVoxelSize](ue_ue.MeshProxySettings.md#boverridevoxelsize)
- [bRecalculateNormals](ue_ue.MeshProxySettings.md#brecalculatenormals)
- [bReuseMeshLightmapUVs](ue_ue.MeshProxySettings.md#breusemeshlightmapuvs)
- [bUseHardAngleThreshold](ue_ue.MeshProxySettings.md#busehardanglethreshold)
- [bUseLandscapeCulling](ue_ue.MeshProxySettings.md#buselandscapeculling)

### Methods

- [StaticClass](ue_ue.MeshProxySettings.md#staticclass)
- [StaticStruct](ue_ue.MeshProxySettings.md#staticstruct)

## Constructors

### constructor

• **new MeshProxySettings**()

• **new MeshProxySettings**(`ScreenSize`, `VoxelSize`, `MaterialSettings`, `TextureWidth`, `TextureHeight`, `bExportNormalMap`, `bExportMetallicMap`, `bExportRoughnessMap`, `bExportSpecularMap`, `bBakeVertexData`, `MergeDistance`, `UnresolvedGeometryColor`, `MaxRayCastDist`, `HardAngleThreshold`, `LightMapResolution`, `NormalCalculationMethod`, `LandscapeCullingPrecision`, `bCalculateCorrectLODModel`, `bOverrideVoxelSize`, `bOverrideTransferDistance`, `bUseHardAngleThreshold`, `bComputeLightMapResolution`, `bRecalculateNormals`, `bUseLandscapeCulling`, `bAllowAdjacency`, `bAllowDistanceField`, `bReuseMeshLightmapUVs`, `bCreateCollision`, `bAllowVertexColors`, `bGenerateLightmapUVs`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ScreenSize` | `number` |
| `VoxelSize` | `number` |
| `MaterialSettings` | [`MaterialProxySettings`](ue_ue.MaterialProxySettings.md) |
| `TextureWidth` | `number` |
| `TextureHeight` | `number` |
| `bExportNormalMap` | `boolean` |
| `bExportMetallicMap` | `boolean` |
| `bExportRoughnessMap` | `boolean` |
| `bExportSpecularMap` | `boolean` |
| `bBakeVertexData` | `boolean` |
| `MergeDistance` | `number` |
| `UnresolvedGeometryColor` | [`Color`](ue_ue_s.Color.md) |
| `MaxRayCastDist` | `number` |
| `HardAngleThreshold` | `number` |
| `LightMapResolution` | `number` |
| `NormalCalculationMethod` | [`EProxyNormalComputationMethod`](../enums/ue_ue.EProxyNormalComputationMethod.md) |
| `LandscapeCullingPrecision` | [`ELandscapeCullingPrecision`](../enums/ue_ue.ELandscapeCullingPrecision.md) |
| `bCalculateCorrectLODModel` | `boolean` |
| `bOverrideVoxelSize` | `boolean` |
| `bOverrideTransferDistance` | `boolean` |
| `bUseHardAngleThreshold` | `boolean` |
| `bComputeLightMapResolution` | `boolean` |
| `bRecalculateNormals` | `boolean` |
| `bUseLandscapeCulling` | `boolean` |
| `bAllowAdjacency` | `boolean` |
| `bAllowDistanceField` | `boolean` |
| `bReuseMeshLightmapUVs` | `boolean` |
| `bCreateCollision` | `boolean` |
| `bAllowVertexColors` | `boolean` |
| `bGenerateLightmapUVs` | `boolean` |

## Properties

### HardAngleThreshold

• **HardAngleThreshold**: `number`

___

### LandscapeCullingPrecision

• **LandscapeCullingPrecision**: [`ELandscapeCullingPrecision`](../enums/ue_ue.ELandscapeCullingPrecision.md)

___

### LightMapResolution

• **LightMapResolution**: `number`

___

### MaterialSettings

• **MaterialSettings**: [`MaterialProxySettings`](ue_ue.MaterialProxySettings.md)

___

### MaxRayCastDist

• **MaxRayCastDist**: `number`

___

### MergeDistance

• **MergeDistance**: `number`

___

### NormalCalculationMethod

• **NormalCalculationMethod**: [`EProxyNormalComputationMethod`](../enums/ue_ue.EProxyNormalComputationMethod.md)

___

### ScreenSize

• **ScreenSize**: `number`

___

### TextureHeight

• **TextureHeight**: `number`

___

### TextureWidth

• **TextureWidth**: `number`

___

### UnresolvedGeometryColor

• **UnresolvedGeometryColor**: [`Color`](ue_ue_s.Color.md)

___

### VoxelSize

• **VoxelSize**: `number`

___

### \_\_tid\_MeshProxySettings\_\_

• `Private` **\_\_tid\_MeshProxySettings\_\_**: `boolean`

___

### bAllowAdjacency

• **bAllowAdjacency**: `boolean`

___

### bAllowDistanceField

• **bAllowDistanceField**: `boolean`

___

### bAllowVertexColors

• **bAllowVertexColors**: `boolean`

___

### bBakeVertexData

• **bBakeVertexData**: `boolean`

___

### bCalculateCorrectLODModel

• **bCalculateCorrectLODModel**: `boolean`

___

### bComputeLightMapResolution

• **bComputeLightMapResolution**: `boolean`

___

### bCreateCollision

• **bCreateCollision**: `boolean`

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

### bGenerateLightmapUVs

• **bGenerateLightmapUVs**: `boolean`

___

### bOverrideTransferDistance

• **bOverrideTransferDistance**: `boolean`

___

### bOverrideVoxelSize

• **bOverrideVoxelSize**: `boolean`

___

### bRecalculateNormals

• **bRecalculateNormals**: `boolean`

___

### bReuseMeshLightmapUVs

• **bReuseMeshLightmapUVs**: `boolean`

___

### bUseHardAngleThreshold

• **bUseHardAngleThreshold**: `boolean`

___

### bUseLandscapeCulling

• **bUseLandscapeCulling**: `boolean`

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
