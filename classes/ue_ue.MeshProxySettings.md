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

#### Defined in

[ue/ue.d.ts:8965](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8965)

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

#### Defined in

[ue/ue.d.ts:8966](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8966)

## Properties

### HardAngleThreshold

• **HardAngleThreshold**: `number`

#### Defined in

[ue/ue.d.ts:8980](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8980)

___

### LandscapeCullingPrecision

• **LandscapeCullingPrecision**: [`ELandscapeCullingPrecision`](../enums/ue_ue.ELandscapeCullingPrecision.md)

#### Defined in

[ue/ue.d.ts:8983](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8983)

___

### LightMapResolution

• **LightMapResolution**: `number`

#### Defined in

[ue/ue.d.ts:8981](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8981)

___

### MaterialSettings

• **MaterialSettings**: [`MaterialProxySettings`](ue_ue.MaterialProxySettings.md)

#### Defined in

[ue/ue.d.ts:8969](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8969)

___

### MaxRayCastDist

• **MaxRayCastDist**: `number`

#### Defined in

[ue/ue.d.ts:8979](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8979)

___

### MergeDistance

• **MergeDistance**: `number`

#### Defined in

[ue/ue.d.ts:8977](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8977)

___

### NormalCalculationMethod

• **NormalCalculationMethod**: [`EProxyNormalComputationMethod`](../enums/ue_ue.EProxyNormalComputationMethod.md)

#### Defined in

[ue/ue.d.ts:8982](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8982)

___

### ScreenSize

• **ScreenSize**: `number`

#### Defined in

[ue/ue.d.ts:8967](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8967)

___

### TextureHeight

• **TextureHeight**: `number`

#### Defined in

[ue/ue.d.ts:8971](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8971)

___

### TextureWidth

• **TextureWidth**: `number`

#### Defined in

[ue/ue.d.ts:8970](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8970)

___

### UnresolvedGeometryColor

• **UnresolvedGeometryColor**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:8978](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8978)

___

### VoxelSize

• **VoxelSize**: `number`

#### Defined in

[ue/ue.d.ts:8968](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8968)

___

### \_\_tid\_MeshProxySettings\_\_

• `Private` **\_\_tid\_MeshProxySettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:9002](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9002)

___

### bAllowAdjacency

• **bAllowAdjacency**: `boolean`

#### Defined in

[ue/ue.d.ts:8991](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8991)

___

### bAllowDistanceField

• **bAllowDistanceField**: `boolean`

#### Defined in

[ue/ue.d.ts:8992](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8992)

___

### bAllowVertexColors

• **bAllowVertexColors**: `boolean`

#### Defined in

[ue/ue.d.ts:8995](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8995)

___

### bBakeVertexData

• **bBakeVertexData**: `boolean`

#### Defined in

[ue/ue.d.ts:8976](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8976)

___

### bCalculateCorrectLODModel

• **bCalculateCorrectLODModel**: `boolean`

#### Defined in

[ue/ue.d.ts:8984](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8984)

___

### bComputeLightMapResolution

• **bComputeLightMapResolution**: `boolean`

#### Defined in

[ue/ue.d.ts:8988](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8988)

___

### bCreateCollision

• **bCreateCollision**: `boolean`

#### Defined in

[ue/ue.d.ts:8994](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8994)

___

### bExportMetallicMap

• **bExportMetallicMap**: `boolean`

#### Defined in

[ue/ue.d.ts:8973](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8973)

___

### bExportNormalMap

• **bExportNormalMap**: `boolean`

#### Defined in

[ue/ue.d.ts:8972](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8972)

___

### bExportRoughnessMap

• **bExportRoughnessMap**: `boolean`

#### Defined in

[ue/ue.d.ts:8974](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8974)

___

### bExportSpecularMap

• **bExportSpecularMap**: `boolean`

#### Defined in

[ue/ue.d.ts:8975](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8975)

___

### bGenerateLightmapUVs

• **bGenerateLightmapUVs**: `boolean`

#### Defined in

[ue/ue.d.ts:8996](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8996)

___

### bOverrideTransferDistance

• **bOverrideTransferDistance**: `boolean`

#### Defined in

[ue/ue.d.ts:8986](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8986)

___

### bOverrideVoxelSize

• **bOverrideVoxelSize**: `boolean`

#### Defined in

[ue/ue.d.ts:8985](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8985)

___

### bRecalculateNormals

• **bRecalculateNormals**: `boolean`

#### Defined in

[ue/ue.d.ts:8989](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8989)

___

### bReuseMeshLightmapUVs

• **bReuseMeshLightmapUVs**: `boolean`

#### Defined in

[ue/ue.d.ts:8993](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8993)

___

### bUseHardAngleThreshold

• **bUseHardAngleThreshold**: `boolean`

#### Defined in

[ue/ue.d.ts:8987](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8987)

___

### bUseLandscapeCulling

• **bUseLandscapeCulling**: `boolean`

#### Defined in

[ue/ue.d.ts:8990](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8990)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:9000](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9000)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:9001](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9001)
