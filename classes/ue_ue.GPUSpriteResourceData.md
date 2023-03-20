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

#### Defined in

[ue/ue.d.ts:56517](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56517)

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

#### Defined in

[ue/ue.d.ts:56518](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56518)

## Properties

### CameraMotionBlurAmount

• **CameraMotionBlurAmount**: `number`

#### Defined in

[ue/ue.d.ts:56552](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56552)

___

### CollisionRadiusBias

• **CollisionRadiusBias**: `number`

#### Defined in

[ue/ue.d.ts:56546](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56546)

___

### CollisionRadiusScale

• **CollisionRadiusScale**: `number`

#### Defined in

[ue/ue.d.ts:56545](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56545)

___

### CollisionRandomDistribution

• **CollisionRandomDistribution**: `number`

#### Defined in

[ue/ue.d.ts:56549](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56549)

___

### CollisionRandomSpread

• **CollisionRandomSpread**: `number`

#### Defined in

[ue/ue.d.ts:56548](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56548)

___

### CollisionTimeBias

• **CollisionTimeBias**: `number`

#### Defined in

[ue/ue.d.ts:56547](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56547)

___

### ColorBias

• **ColorBias**: [`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue.d.ts:56523](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56523)

___

### ColorScale

• **ColorScale**: [`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue.d.ts:56522](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56522)

___

### ConstantAcceleration

• **ConstantAcceleration**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:56530](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56530)

___

### DragCoefficientBias

• **DragCoefficientBias**: `number`

#### Defined in

[ue/ue.d.ts:56542](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56542)

___

### DragCoefficientScale

• **DragCoefficientScale**: `number`

#### Defined in

[ue/ue.d.ts:56541](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56541)

___

### GlobalVectorFieldScale

• **GlobalVectorFieldScale**: `number`

#### Defined in

[ue/ue.d.ts:56537](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56537)

___

### GlobalVectorFieldTightness

• **GlobalVectorFieldTightness**: `number`

#### Defined in

[ue/ue.d.ts:56538](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56538)

___

### LockAxisFlag

• **LockAxisFlag**: [`EParticleAxisLock`](../enums/ue_ue.EParticleAxisLock.md)

#### Defined in

[ue/ue.d.ts:56554](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56554)

___

### MaxFacingCameraBlendDistance

• **MaxFacingCameraBlendDistance**: `number`

#### Defined in

[ue/ue.d.ts:56558](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56558)

___

### MinFacingCameraBlendDistance

• **MinFacingCameraBlendDistance**: `number`

#### Defined in

[ue/ue.d.ts:56557](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56557)

___

### MiscBias

• **MiscBias**: [`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue.d.ts:56525](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56525)

___

### MiscScale

• **MiscScale**: [`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue.d.ts:56524](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56524)

___

### OneMinusFriction

• **OneMinusFriction**: `number`

#### Defined in

[ue/ue.d.ts:56550](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56550)

___

### OrbitFrequencyBase

• **OrbitFrequencyBase**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:56533](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56533)

___

### OrbitFrequencyRange

• **OrbitFrequencyRange**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:56534](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56534)

___

### OrbitOffsetBase

• **OrbitOffsetBase**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:56531](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56531)

___

### OrbitOffsetRange

• **OrbitOffsetRange**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:56532](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56532)

___

### OrbitPhaseBase

• **OrbitPhaseBase**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:56535](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56535)

___

### OrbitPhaseRange

• **OrbitPhaseRange**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:56536](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56536)

___

### PerParticleVectorFieldBias

• **PerParticleVectorFieldBias**: `number`

#### Defined in

[ue/ue.d.ts:56540](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56540)

___

### PerParticleVectorFieldScale

• **PerParticleVectorFieldScale**: `number`

#### Defined in

[ue/ue.d.ts:56539](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56539)

___

### PivotOffset

• **PivotOffset**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:56555](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56555)

___

### QuantizedColorSamples

• **QuantizedColorSamples**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Color`](ue_ue_s.Color.md)\>

#### Defined in

[ue/ue.d.ts:56519](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56519)

___

### QuantizedMiscSamples

• **QuantizedMiscSamples**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Color`](ue_ue_s.Color.md)\>

#### Defined in

[ue/ue.d.ts:56520](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56520)

___

### QuantizedSimulationAttrSamples

• **QuantizedSimulationAttrSamples**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Color`](ue_ue_s.Color.md)\>

#### Defined in

[ue/ue.d.ts:56521](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56521)

___

### ResilienceBias

• **ResilienceBias**: `number`

#### Defined in

[ue/ue.d.ts:56544](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56544)

___

### ResilienceScale

• **ResilienceScale**: `number`

#### Defined in

[ue/ue.d.ts:56543](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56543)

___

### RotationRateScale

• **RotationRateScale**: `number`

#### Defined in

[ue/ue.d.ts:56551](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56551)

___

### ScreenAlignment

• **ScreenAlignment**: [`EParticleScreenAlignment`](../enums/ue_ue.EParticleScreenAlignment.md)

#### Defined in

[ue/ue.d.ts:56553](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56553)

___

### SimulationAttrCurveBias

• **SimulationAttrCurveBias**: [`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue.d.ts:56527](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56527)

___

### SimulationAttrCurveScale

• **SimulationAttrCurveScale**: [`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue.d.ts:56526](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56526)

___

### SizeBySpeed

• **SizeBySpeed**: [`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue.d.ts:56529](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56529)

___

### SubImageSize

• **SubImageSize**: [`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue.d.ts:56528](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56528)

___

### \_\_tid\_GPUSpriteResourceData\_\_

• `Private` **\_\_tid\_GPUSpriteResourceData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:56564](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56564)

___

### bRemoveHMDRoll

• **bRemoveHMDRoll**: `boolean`

#### Defined in

[ue/ue.d.ts:56556](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56556)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:56562](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56562)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:56563](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56563)
