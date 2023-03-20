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

#### Defined in

[ue/ue.d.ts:8712](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8712)

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

#### Defined in

[ue/ue.d.ts:8713](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8713)

## Properties

### DiffuseBoost

• **DiffuseBoost**: `number`

#### Defined in

[ue/ue.d.ts:8722](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8722)

___

### DirectIlluminationOcclusionFraction

• **DirectIlluminationOcclusionFraction**: `number`

#### Defined in

[ue/ue.d.ts:8733](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8733)

___

### EmissiveBoost

• **EmissiveBoost**: `number`

#### Defined in

[ue/ue.d.ts:8721](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8721)

___

### EnvironmentColor

• **EnvironmentColor**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:8719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8719)

___

### EnvironmentIntensity

• **EnvironmentIntensity**: `number`

#### Defined in

[ue/ue.d.ts:8720](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8720)

___

### FullyOccludedSamplesFraction

• **FullyOccludedSamplesFraction**: `number`

#### Defined in

[ue/ue.d.ts:8736](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8736)

___

### IndirectIlluminationOcclusionFraction

• **IndirectIlluminationOcclusionFraction**: `number`

#### Defined in

[ue/ue.d.ts:8734](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8734)

___

### IndirectLightingQuality

• **IndirectLightingQuality**: `number`

#### Defined in

[ue/ue.d.ts:8717](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8717)

___

### IndirectLightingSmoothness

• **IndirectLightingSmoothness**: `number`

#### Defined in

[ue/ue.d.ts:8718](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8718)

___

### MaxOcclusionDistance

• **MaxOcclusionDistance**: `number`

#### Defined in

[ue/ue.d.ts:8737](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8737)

___

### NumIndirectLightingBounces

• **NumIndirectLightingBounces**: `number`

#### Defined in

[ue/ue.d.ts:8715](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8715)

___

### NumSkyLightingBounces

• **NumSkyLightingBounces**: `number`

#### Defined in

[ue/ue.d.ts:8716](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8716)

___

### OcclusionExponent

• **OcclusionExponent**: `number`

#### Defined in

[ue/ue.d.ts:8735](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8735)

___

### StaticLightingLevelScale

• **StaticLightingLevelScale**: `number`

#### Defined in

[ue/ue.d.ts:8714](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8714)

___

### VolumeLightSamplePlacementScale

• **VolumeLightSamplePlacementScale**: `number`

#### Defined in

[ue/ue.d.ts:8732](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8732)

___

### VolumeLightingMethod

• **VolumeLightingMethod**: [`EVolumeLightingMethod`](../enums/ue_ue.EVolumeLightingMethod.md)

#### Defined in

[ue/ue.d.ts:8723](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8723)

___

### VolumetricLightmapDetailCellSize

• **VolumetricLightmapDetailCellSize**: `number`

#### Defined in

[ue/ue.d.ts:8729](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8729)

___

### VolumetricLightmapMaximumBrickMemoryMb

• **VolumetricLightmapMaximumBrickMemoryMb**: `number`

#### Defined in

[ue/ue.d.ts:8730](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8730)

___

### VolumetricLightmapSphericalHarmonicSmoothing

• **VolumetricLightmapSphericalHarmonicSmoothing**: `number`

#### Defined in

[ue/ue.d.ts:8731](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8731)

___

### \_\_tid\_LightmassWorldInfoSettings\_\_

• `Private` **\_\_tid\_LightmassWorldInfoSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:8743](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8743)

___

### bCompressLightmaps

• **bCompressLightmaps**: `boolean`

#### Defined in

[ue/ue.d.ts:8728](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8728)

___

### bGenerateAmbientOcclusionMaterialMask

• **bGenerateAmbientOcclusionMaterialMask**: `boolean`

#### Defined in

[ue/ue.d.ts:8725](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8725)

___

### bUseAmbientOcclusion

• **bUseAmbientOcclusion**: `boolean`

#### Defined in

[ue/ue.d.ts:8724](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8724)

___

### bVisualizeAmbientOcclusion

• **bVisualizeAmbientOcclusion**: `boolean`

#### Defined in

[ue/ue.d.ts:8727](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8727)

___

### bVisualizeMaterialDiffuse

• **bVisualizeMaterialDiffuse**: `boolean`

#### Defined in

[ue/ue.d.ts:8726](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8726)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:8741](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8741)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:8742](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8742)
