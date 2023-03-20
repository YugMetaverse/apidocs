[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LightmassWorldInfoSettings

# Class: LightmassWorldInfoSettings

[ue/ue](../modules/ue_ue.md).LightmassWorldInfoSettings

## Table of contents

### Constructors

- [constructor](ue_ue.LightmassWorldInfoSettings.md#constructor)

### Properties

- [DiffuseBoost](ue_ue.LightmassWorldInfoSettings.md#diffuseboost)
- [DirectIlluminationOcclusionFraction](ue_ue.LightmassWorldInfoSettings.md#directilluminationocclusionfraction)
- [EmissiveBoost](ue_ue.LightmassWorldInfoSettings.md#emissiveboost)
- [EnvironmentColor](ue_ue.LightmassWorldInfoSettings.md#environmentcolor)
- [EnvironmentIntensity](ue_ue.LightmassWorldInfoSettings.md#environmentintensity)
- [FullyOccludedSamplesFraction](ue_ue.LightmassWorldInfoSettings.md#fullyoccludedsamplesfraction)
- [IndirectIlluminationOcclusionFraction](ue_ue.LightmassWorldInfoSettings.md#indirectilluminationocclusionfraction)
- [IndirectLightingQuality](ue_ue.LightmassWorldInfoSettings.md#indirectlightingquality)
- [IndirectLightingSmoothness](ue_ue.LightmassWorldInfoSettings.md#indirectlightingsmoothness)
- [MaxOcclusionDistance](ue_ue.LightmassWorldInfoSettings.md#maxocclusiondistance)
- [NumIndirectLightingBounces](ue_ue.LightmassWorldInfoSettings.md#numindirectlightingbounces)
- [NumSkyLightingBounces](ue_ue.LightmassWorldInfoSettings.md#numskylightingbounces)
- [OcclusionExponent](ue_ue.LightmassWorldInfoSettings.md#occlusionexponent)
- [StaticLightingLevelScale](ue_ue.LightmassWorldInfoSettings.md#staticlightinglevelscale)
- [VolumeLightSamplePlacementScale](ue_ue.LightmassWorldInfoSettings.md#volumelightsampleplacementscale)
- [VolumeLightingMethod](ue_ue.LightmassWorldInfoSettings.md#volumelightingmethod)
- [VolumetricLightmapDetailCellSize](ue_ue.LightmassWorldInfoSettings.md#volumetriclightmapdetailcellsize)
- [VolumetricLightmapMaximumBrickMemoryMb](ue_ue.LightmassWorldInfoSettings.md#volumetriclightmapmaximumbrickmemorymb)
- [VolumetricLightmapSphericalHarmonicSmoothing](ue_ue.LightmassWorldInfoSettings.md#volumetriclightmapsphericalharmonicsmoothing)
- [\_\_tid\_LightmassWorldInfoSettings\_\_](ue_ue.LightmassWorldInfoSettings.md#__tid_lightmassworldinfosettings__)
- [bCompressLightmaps](ue_ue.LightmassWorldInfoSettings.md#bcompresslightmaps)
- [bGenerateAmbientOcclusionMaterialMask](ue_ue.LightmassWorldInfoSettings.md#bgenerateambientocclusionmaterialmask)
- [bUseAmbientOcclusion](ue_ue.LightmassWorldInfoSettings.md#buseambientocclusion)
- [bVisualizeAmbientOcclusion](ue_ue.LightmassWorldInfoSettings.md#bvisualizeambientocclusion)
- [bVisualizeMaterialDiffuse](ue_ue.LightmassWorldInfoSettings.md#bvisualizematerialdiffuse)

### Methods

- [StaticClass](ue_ue.LightmassWorldInfoSettings.md#staticclass)
- [StaticStruct](ue_ue.LightmassWorldInfoSettings.md#staticstruct)

## Constructors

### constructor

• **new LightmassWorldInfoSettings**()

• **new LightmassWorldInfoSettings**(`StaticLightingLevelScale`, `NumIndirectLightingBounces`, `NumSkyLightingBounces`, `IndirectLightingQuality`, `IndirectLightingSmoothness`, `EnvironmentColor`, `EnvironmentIntensity`, `EmissiveBoost`, `DiffuseBoost`, `VolumeLightingMethod`, `bUseAmbientOcclusion`, `bGenerateAmbientOcclusionMaterialMask`, `bVisualizeMaterialDiffuse`, `bVisualizeAmbientOcclusion`, `bCompressLightmaps`, `VolumetricLightmapDetailCellSize`, `VolumetricLightmapMaximumBrickMemoryMb`, `VolumetricLightmapSphericalHarmonicSmoothing`, `VolumeLightSamplePlacementScale`, `DirectIlluminationOcclusionFraction`, `IndirectIlluminationOcclusionFraction`, `OcclusionExponent`, `FullyOccludedSamplesFraction`, `MaxOcclusionDistance`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `StaticLightingLevelScale` | `number` |
| `NumIndirectLightingBounces` | `number` |
| `NumSkyLightingBounces` | `number` |
| `IndirectLightingQuality` | `number` |
| `IndirectLightingSmoothness` | `number` |
| `EnvironmentColor` | [`Color`](ue_ue_s.Color.md) |
| `EnvironmentIntensity` | `number` |
| `EmissiveBoost` | `number` |
| `DiffuseBoost` | `number` |
| `VolumeLightingMethod` | [`EVolumeLightingMethod`](../enums/ue_ue.EVolumeLightingMethod.md) |
| `bUseAmbientOcclusion` | `boolean` |
| `bGenerateAmbientOcclusionMaterialMask` | `boolean` |
| `bVisualizeMaterialDiffuse` | `boolean` |
| `bVisualizeAmbientOcclusion` | `boolean` |
| `bCompressLightmaps` | `boolean` |
| `VolumetricLightmapDetailCellSize` | `number` |
| `VolumetricLightmapMaximumBrickMemoryMb` | `number` |
| `VolumetricLightmapSphericalHarmonicSmoothing` | `number` |
| `VolumeLightSamplePlacementScale` | `number` |
| `DirectIlluminationOcclusionFraction` | `number` |
| `IndirectIlluminationOcclusionFraction` | `number` |
| `OcclusionExponent` | `number` |
| `FullyOccludedSamplesFraction` | `number` |
| `MaxOcclusionDistance` | `number` |

## Properties

### DiffuseBoost

• **DiffuseBoost**: `number`

___

### DirectIlluminationOcclusionFraction

• **DirectIlluminationOcclusionFraction**: `number`

___

### EmissiveBoost

• **EmissiveBoost**: `number`

___

### EnvironmentColor

• **EnvironmentColor**: [`Color`](ue_ue_s.Color.md)

___

### EnvironmentIntensity

• **EnvironmentIntensity**: `number`

___

### FullyOccludedSamplesFraction

• **FullyOccludedSamplesFraction**: `number`

___

### IndirectIlluminationOcclusionFraction

• **IndirectIlluminationOcclusionFraction**: `number`

___

### IndirectLightingQuality

• **IndirectLightingQuality**: `number`

___

### IndirectLightingSmoothness

• **IndirectLightingSmoothness**: `number`

___

### MaxOcclusionDistance

• **MaxOcclusionDistance**: `number`

___

### NumIndirectLightingBounces

• **NumIndirectLightingBounces**: `number`

___

### NumSkyLightingBounces

• **NumSkyLightingBounces**: `number`

___

### OcclusionExponent

• **OcclusionExponent**: `number`

___

### StaticLightingLevelScale

• **StaticLightingLevelScale**: `number`

___

### VolumeLightSamplePlacementScale

• **VolumeLightSamplePlacementScale**: `number`

___

### VolumeLightingMethod

• **VolumeLightingMethod**: [`EVolumeLightingMethod`](../enums/ue_ue.EVolumeLightingMethod.md)

___

### VolumetricLightmapDetailCellSize

• **VolumetricLightmapDetailCellSize**: `number`

___

### VolumetricLightmapMaximumBrickMemoryMb

• **VolumetricLightmapMaximumBrickMemoryMb**: `number`

___

### VolumetricLightmapSphericalHarmonicSmoothing

• **VolumetricLightmapSphericalHarmonicSmoothing**: `number`

___

### \_\_tid\_LightmassWorldInfoSettings\_\_

• `Private` **\_\_tid\_LightmassWorldInfoSettings\_\_**: `boolean`

___

### bCompressLightmaps

• **bCompressLightmaps**: `boolean`

___

### bGenerateAmbientOcclusionMaterialMask

• **bGenerateAmbientOcclusionMaterialMask**: `boolean`

___

### bUseAmbientOcclusion

• **bUseAmbientOcclusion**: `boolean`

___

### bVisualizeAmbientOcclusion

• **bVisualizeAmbientOcclusion**: `boolean`

___

### bVisualizeMaterialDiffuse

• **bVisualizeMaterialDiffuse**: `boolean`

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
