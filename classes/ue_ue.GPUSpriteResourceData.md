[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GPUSpriteResourceData

# Class: GPUSpriteResourceData

[ue/ue](../modules/ue_ue.md).GPUSpriteResourceData

## Table of contents

### Constructors

- [constructor](ue_ue.GPUSpriteResourceData.md#constructor)

### Properties

- [CameraMotionBlurAmount](ue_ue.GPUSpriteResourceData.md#cameramotionbluramount)
- [CollisionRadiusBias](ue_ue.GPUSpriteResourceData.md#collisionradiusbias)
- [CollisionRadiusScale](ue_ue.GPUSpriteResourceData.md#collisionradiusscale)
- [CollisionRandomDistribution](ue_ue.GPUSpriteResourceData.md#collisionrandomdistribution)
- [CollisionRandomSpread](ue_ue.GPUSpriteResourceData.md#collisionrandomspread)
- [CollisionTimeBias](ue_ue.GPUSpriteResourceData.md#collisiontimebias)
- [ColorBias](ue_ue.GPUSpriteResourceData.md#colorbias)
- [ColorScale](ue_ue.GPUSpriteResourceData.md#colorscale)
- [ConstantAcceleration](ue_ue.GPUSpriteResourceData.md#constantacceleration)
- [DragCoefficientBias](ue_ue.GPUSpriteResourceData.md#dragcoefficientbias)
- [DragCoefficientScale](ue_ue.GPUSpriteResourceData.md#dragcoefficientscale)
- [GlobalVectorFieldScale](ue_ue.GPUSpriteResourceData.md#globalvectorfieldscale)
- [GlobalVectorFieldTightness](ue_ue.GPUSpriteResourceData.md#globalvectorfieldtightness)
- [LockAxisFlag](ue_ue.GPUSpriteResourceData.md#lockaxisflag)
- [MaxFacingCameraBlendDistance](ue_ue.GPUSpriteResourceData.md#maxfacingcamerablenddistance)
- [MinFacingCameraBlendDistance](ue_ue.GPUSpriteResourceData.md#minfacingcamerablenddistance)
- [MiscBias](ue_ue.GPUSpriteResourceData.md#miscbias)
- [MiscScale](ue_ue.GPUSpriteResourceData.md#miscscale)
- [OneMinusFriction](ue_ue.GPUSpriteResourceData.md#oneminusfriction)
- [OrbitFrequencyBase](ue_ue.GPUSpriteResourceData.md#orbitfrequencybase)
- [OrbitFrequencyRange](ue_ue.GPUSpriteResourceData.md#orbitfrequencyrange)
- [OrbitOffsetBase](ue_ue.GPUSpriteResourceData.md#orbitoffsetbase)
- [OrbitOffsetRange](ue_ue.GPUSpriteResourceData.md#orbitoffsetrange)
- [OrbitPhaseBase](ue_ue.GPUSpriteResourceData.md#orbitphasebase)
- [OrbitPhaseRange](ue_ue.GPUSpriteResourceData.md#orbitphaserange)
- [PerParticleVectorFieldBias](ue_ue.GPUSpriteResourceData.md#perparticlevectorfieldbias)
- [PerParticleVectorFieldScale](ue_ue.GPUSpriteResourceData.md#perparticlevectorfieldscale)
- [PivotOffset](ue_ue.GPUSpriteResourceData.md#pivotoffset)
- [QuantizedColorSamples](ue_ue.GPUSpriteResourceData.md#quantizedcolorsamples)
- [QuantizedMiscSamples](ue_ue.GPUSpriteResourceData.md#quantizedmiscsamples)
- [QuantizedSimulationAttrSamples](ue_ue.GPUSpriteResourceData.md#quantizedsimulationattrsamples)
- [ResilienceBias](ue_ue.GPUSpriteResourceData.md#resiliencebias)
- [ResilienceScale](ue_ue.GPUSpriteResourceData.md#resiliencescale)
- [RotationRateScale](ue_ue.GPUSpriteResourceData.md#rotationratescale)
- [ScreenAlignment](ue_ue.GPUSpriteResourceData.md#screenalignment)
- [SimulationAttrCurveBias](ue_ue.GPUSpriteResourceData.md#simulationattrcurvebias)
- [SimulationAttrCurveScale](ue_ue.GPUSpriteResourceData.md#simulationattrcurvescale)
- [SizeBySpeed](ue_ue.GPUSpriteResourceData.md#sizebyspeed)
- [SubImageSize](ue_ue.GPUSpriteResourceData.md#subimagesize)
- [\_\_tid\_GPUSpriteResourceData\_\_](ue_ue.GPUSpriteResourceData.md#__tid_gpuspriteresourcedata__)
- [bRemoveHMDRoll](ue_ue.GPUSpriteResourceData.md#bremovehmdroll)

### Methods

- [StaticClass](ue_ue.GPUSpriteResourceData.md#staticclass)
- [StaticStruct](ue_ue.GPUSpriteResourceData.md#staticstruct)

## Constructors

### constructor

• **new GPUSpriteResourceData**()

• **new GPUSpriteResourceData**(`QuantizedColorSamples`, `QuantizedMiscSamples`, `QuantizedSimulationAttrSamples`, `ColorScale`, `ColorBias`, `MiscScale`, `MiscBias`, `SimulationAttrCurveScale`, `SimulationAttrCurveBias`, `SubImageSize`, `SizeBySpeed`, `ConstantAcceleration`, `OrbitOffsetBase`, `OrbitOffsetRange`, `OrbitFrequencyBase`, `OrbitFrequencyRange`, `OrbitPhaseBase`, `OrbitPhaseRange`, `GlobalVectorFieldScale`, `GlobalVectorFieldTightness`, `PerParticleVectorFieldScale`, `PerParticleVectorFieldBias`, `DragCoefficientScale`, `DragCoefficientBias`, `ResilienceScale`, `ResilienceBias`, `CollisionRadiusScale`, `CollisionRadiusBias`, `CollisionTimeBias`, `CollisionRandomSpread`, `CollisionRandomDistribution`, `OneMinusFriction`, `RotationRateScale`, `CameraMotionBlurAmount`, `ScreenAlignment`, `LockAxisFlag`, `PivotOffset`, `bRemoveHMDRoll`, `MinFacingCameraBlendDistance`, `MaxFacingCameraBlendDistance`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `QuantizedColorSamples` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Color`](ue_ue_s.Color.md)\> |
| `QuantizedMiscSamples` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Color`](ue_ue_s.Color.md)\> |
| `QuantizedSimulationAttrSamples` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Color`](ue_ue_s.Color.md)\> |
| `ColorScale` | [`Vector4`](ue_ue_s.Vector4.md) |
| `ColorBias` | [`Vector4`](ue_ue_s.Vector4.md) |
| `MiscScale` | [`Vector4`](ue_ue_s.Vector4.md) |
| `MiscBias` | [`Vector4`](ue_ue_s.Vector4.md) |
| `SimulationAttrCurveScale` | [`Vector4`](ue_ue_s.Vector4.md) |
| `SimulationAttrCurveBias` | [`Vector4`](ue_ue_s.Vector4.md) |
| `SubImageSize` | [`Vector4`](ue_ue_s.Vector4.md) |
| `SizeBySpeed` | [`Vector4`](ue_ue_s.Vector4.md) |
| `ConstantAcceleration` | [`Vector`](ue_ue_s.Vector.md) |
| `OrbitOffsetBase` | [`Vector`](ue_ue_s.Vector.md) |
| `OrbitOffsetRange` | [`Vector`](ue_ue_s.Vector.md) |
| `OrbitFrequencyBase` | [`Vector`](ue_ue_s.Vector.md) |
| `OrbitFrequencyRange` | [`Vector`](ue_ue_s.Vector.md) |
| `OrbitPhaseBase` | [`Vector`](ue_ue_s.Vector.md) |
| `OrbitPhaseRange` | [`Vector`](ue_ue_s.Vector.md) |
| `GlobalVectorFieldScale` | `number` |
| `GlobalVectorFieldTightness` | `number` |
| `PerParticleVectorFieldScale` | `number` |
| `PerParticleVectorFieldBias` | `number` |
| `DragCoefficientScale` | `number` |
| `DragCoefficientBias` | `number` |
| `ResilienceScale` | `number` |
| `ResilienceBias` | `number` |
| `CollisionRadiusScale` | `number` |
| `CollisionRadiusBias` | `number` |
| `CollisionTimeBias` | `number` |
| `CollisionRandomSpread` | `number` |
| `CollisionRandomDistribution` | `number` |
| `OneMinusFriction` | `number` |
| `RotationRateScale` | `number` |
| `CameraMotionBlurAmount` | `number` |
| `ScreenAlignment` | [`EParticleScreenAlignment`](../enums/ue_ue.EParticleScreenAlignment.md) |
| `LockAxisFlag` | [`EParticleAxisLock`](../enums/ue_ue.EParticleAxisLock.md) |
| `PivotOffset` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `bRemoveHMDRoll` | `boolean` |
| `MinFacingCameraBlendDistance` | `number` |
| `MaxFacingCameraBlendDistance` | `number` |

## Properties

### CameraMotionBlurAmount

• **CameraMotionBlurAmount**: `number`

___

### CollisionRadiusBias

• **CollisionRadiusBias**: `number`

___

### CollisionRadiusScale

• **CollisionRadiusScale**: `number`

___

### CollisionRandomDistribution

• **CollisionRandomDistribution**: `number`

___

### CollisionRandomSpread

• **CollisionRandomSpread**: `number`

___

### CollisionTimeBias

• **CollisionTimeBias**: `number`

___

### ColorBias

• **ColorBias**: [`Vector4`](ue_ue_s.Vector4.md)

___

### ColorScale

• **ColorScale**: [`Vector4`](ue_ue_s.Vector4.md)

___

### ConstantAcceleration

• **ConstantAcceleration**: [`Vector`](ue_ue_s.Vector.md)

___

### DragCoefficientBias

• **DragCoefficientBias**: `number`

___

### DragCoefficientScale

• **DragCoefficientScale**: `number`

___

### GlobalVectorFieldScale

• **GlobalVectorFieldScale**: `number`

___

### GlobalVectorFieldTightness

• **GlobalVectorFieldTightness**: `number`

___

### LockAxisFlag

• **LockAxisFlag**: [`EParticleAxisLock`](../enums/ue_ue.EParticleAxisLock.md)

___

### MaxFacingCameraBlendDistance

• **MaxFacingCameraBlendDistance**: `number`

___

### MinFacingCameraBlendDistance

• **MinFacingCameraBlendDistance**: `number`

___

### MiscBias

• **MiscBias**: [`Vector4`](ue_ue_s.Vector4.md)

___

### MiscScale

• **MiscScale**: [`Vector4`](ue_ue_s.Vector4.md)

___

### OneMinusFriction

• **OneMinusFriction**: `number`

___

### OrbitFrequencyBase

• **OrbitFrequencyBase**: [`Vector`](ue_ue_s.Vector.md)

___

### OrbitFrequencyRange

• **OrbitFrequencyRange**: [`Vector`](ue_ue_s.Vector.md)

___

### OrbitOffsetBase

• **OrbitOffsetBase**: [`Vector`](ue_ue_s.Vector.md)

___

### OrbitOffsetRange

• **OrbitOffsetRange**: [`Vector`](ue_ue_s.Vector.md)

___

### OrbitPhaseBase

• **OrbitPhaseBase**: [`Vector`](ue_ue_s.Vector.md)

___

### OrbitPhaseRange

• **OrbitPhaseRange**: [`Vector`](ue_ue_s.Vector.md)

___

### PerParticleVectorFieldBias

• **PerParticleVectorFieldBias**: `number`

___

### PerParticleVectorFieldScale

• **PerParticleVectorFieldScale**: `number`

___

### PivotOffset

• **PivotOffset**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### QuantizedColorSamples

• **QuantizedColorSamples**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Color`](ue_ue_s.Color.md)\>

___

### QuantizedMiscSamples

• **QuantizedMiscSamples**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Color`](ue_ue_s.Color.md)\>

___

### QuantizedSimulationAttrSamples

• **QuantizedSimulationAttrSamples**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Color`](ue_ue_s.Color.md)\>

___

### ResilienceBias

• **ResilienceBias**: `number`

___

### ResilienceScale

• **ResilienceScale**: `number`

___

### RotationRateScale

• **RotationRateScale**: `number`

___

### ScreenAlignment

• **ScreenAlignment**: [`EParticleScreenAlignment`](../enums/ue_ue.EParticleScreenAlignment.md)

___

### SimulationAttrCurveBias

• **SimulationAttrCurveBias**: [`Vector4`](ue_ue_s.Vector4.md)

___

### SimulationAttrCurveScale

• **SimulationAttrCurveScale**: [`Vector4`](ue_ue_s.Vector4.md)

___

### SizeBySpeed

• **SizeBySpeed**: [`Vector4`](ue_ue_s.Vector4.md)

___

### SubImageSize

• **SubImageSize**: [`Vector4`](ue_ue_s.Vector4.md)

___

### \_\_tid\_GPUSpriteResourceData\_\_

• `Private` **\_\_tid\_GPUSpriteResourceData\_\_**: `boolean`

___

### bRemoveHMDRoll

• **bRemoveHMDRoll**: `boolean`

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
