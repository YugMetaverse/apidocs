[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GPUSpriteEmitterInfo

# Class: GPUSpriteEmitterInfo

[ue/ue](../modules/ue_ue.md).GPUSpriteEmitterInfo

## Table of contents

### Constructors

- [constructor](ue_ue.GPUSpriteEmitterInfo.md#constructor)

### Properties

- [CollisionMode](ue_ue.GPUSpriteEmitterInfo.md#collisionmode)
- [ConstantAcceleration](ue_ue.GPUSpriteEmitterInfo.md#constantacceleration)
- [DragCoefficient](ue_ue.GPUSpriteEmitterInfo.md#dragcoefficient)
- [DynamicAlpha](ue_ue.GPUSpriteEmitterInfo.md#dynamicalpha)
- [DynamicAlphaScale](ue_ue.GPUSpriteEmitterInfo.md#dynamicalphascale)
- [DynamicColor](ue_ue.GPUSpriteEmitterInfo.md#dynamiccolor)
- [DynamicColorScale](ue_ue.GPUSpriteEmitterInfo.md#dynamiccolorscale)
- [InvMaxSize](ue_ue.GPUSpriteEmitterInfo.md#invmaxsize)
- [InvRotationRateScale](ue_ue.GPUSpriteEmitterInfo.md#invrotationratescale)
- [LocalVectorField](ue_ue.GPUSpriteEmitterInfo.md#localvectorfield)
- [LockAxisFlag](ue_ue.GPUSpriteEmitterInfo.md#lockaxisflag)
- [MaxFacingCameraBlendDistance](ue_ue.GPUSpriteEmitterInfo.md#maxfacingcamerablenddistance)
- [MaxLifetime](ue_ue.GPUSpriteEmitterInfo.md#maxlifetime)
- [MaxParticleCount](ue_ue.GPUSpriteEmitterInfo.md#maxparticlecount)
- [MinFacingCameraBlendDistance](ue_ue.GPUSpriteEmitterInfo.md#minfacingcamerablenddistance)
- [OrbitOffsetBase](ue_ue.GPUSpriteEmitterInfo.md#orbitoffsetbase)
- [OrbitOffsetRange](ue_ue.GPUSpriteEmitterInfo.md#orbitoffsetrange)
- [PointAttractorPosition](ue_ue.GPUSpriteEmitterInfo.md#pointattractorposition)
- [PointAttractorRadiusSq](ue_ue.GPUSpriteEmitterInfo.md#pointattractorradiussq)
- [PointAttractorStrength](ue_ue.GPUSpriteEmitterInfo.md#pointattractorstrength)
- [RequiredModule](ue_ue.GPUSpriteEmitterInfo.md#requiredmodule)
- [Resilience](ue_ue.GPUSpriteEmitterInfo.md#resilience)
- [ScreenAlignment](ue_ue.GPUSpriteEmitterInfo.md#screenalignment)
- [SpawnModule](ue_ue.GPUSpriteEmitterInfo.md#spawnmodule)
- [SpawnModules](ue_ue.GPUSpriteEmitterInfo.md#spawnmodules)
- [SpawnPerUnitModule](ue_ue.GPUSpriteEmitterInfo.md#spawnperunitmodule)
- [VectorFieldScale](ue_ue.GPUSpriteEmitterInfo.md#vectorfieldscale)
- [\_\_tid\_GPUSpriteEmitterInfo\_\_](ue_ue.GPUSpriteEmitterInfo.md#__tid_gpuspriteemitterinfo__)
- [bEnableCollision](ue_ue.GPUSpriteEmitterInfo.md#benablecollision)
- [bRemoveHMDRoll](ue_ue.GPUSpriteEmitterInfo.md#bremovehmdroll)

### Methods

- [StaticClass](ue_ue.GPUSpriteEmitterInfo.md#staticclass)
- [StaticStruct](ue_ue.GPUSpriteEmitterInfo.md#staticstruct)

## Constructors

### constructor

• **new GPUSpriteEmitterInfo**()

• **new GPUSpriteEmitterInfo**(`RequiredModule`, `SpawnModule`, `SpawnPerUnitModule`, `SpawnModules`, `LocalVectorField`, `VectorFieldScale`, `DragCoefficient`, `PointAttractorStrength`, `Resilience`, `ConstantAcceleration`, `PointAttractorPosition`, `PointAttractorRadiusSq`, `OrbitOffsetBase`, `OrbitOffsetRange`, `InvMaxSize`, `InvRotationRateScale`, `MaxLifetime`, `MaxParticleCount`, `ScreenAlignment`, `LockAxisFlag`, `bEnableCollision`, `CollisionMode`, `bRemoveHMDRoll`, `MinFacingCameraBlendDistance`, `MaxFacingCameraBlendDistance`, `DynamicColor`, `DynamicAlpha`, `DynamicColorScale`, `DynamicAlphaScale`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `RequiredModule` | [`ParticleModuleRequired`](ue_ue.ParticleModuleRequired.md) |
| `SpawnModule` | [`ParticleModuleSpawn`](ue_ue.ParticleModuleSpawn.md) |
| `SpawnPerUnitModule` | [`ParticleModuleSpawnPerUnit`](ue_ue.ParticleModuleSpawnPerUnit.md) |
| `SpawnModules` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleModule`](ue_ue.ParticleModule.md)\> |
| `LocalVectorField` | [`GPUSpriteLocalVectorFieldInfo`](ue_ue.GPUSpriteLocalVectorFieldInfo.md) |
| `VectorFieldScale` | [`FloatDistribution`](ue_ue.FloatDistribution.md) |
| `DragCoefficient` | [`FloatDistribution`](ue_ue.FloatDistribution.md) |
| `PointAttractorStrength` | [`FloatDistribution`](ue_ue.FloatDistribution.md) |
| `Resilience` | [`FloatDistribution`](ue_ue.FloatDistribution.md) |
| `ConstantAcceleration` | [`Vector`](ue_ue_s.Vector.md) |
| `PointAttractorPosition` | [`Vector`](ue_ue_s.Vector.md) |
| `PointAttractorRadiusSq` | `number` |
| `OrbitOffsetBase` | [`Vector`](ue_ue_s.Vector.md) |
| `OrbitOffsetRange` | [`Vector`](ue_ue_s.Vector.md) |
| `InvMaxSize` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `InvRotationRateScale` | `number` |
| `MaxLifetime` | `number` |
| `MaxParticleCount` | `number` |
| `ScreenAlignment` | [`EParticleScreenAlignment`](../enums/ue_ue.EParticleScreenAlignment.md) |
| `LockAxisFlag` | [`EParticleAxisLock`](../enums/ue_ue.EParticleAxisLock.md) |
| `bEnableCollision` | `boolean` |
| `CollisionMode` | [`EParticleCollisionMode`](../enums/ue_ue.EParticleCollisionMode.md) |
| `bRemoveHMDRoll` | `boolean` |
| `MinFacingCameraBlendDistance` | `number` |
| `MaxFacingCameraBlendDistance` | `number` |
| `DynamicColor` | [`RawDistributionVector`](ue_ue.RawDistributionVector.md) |
| `DynamicAlpha` | [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md) |
| `DynamicColorScale` | [`RawDistributionVector`](ue_ue.RawDistributionVector.md) |
| `DynamicAlphaScale` | [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md) |

## Properties

### CollisionMode

• **CollisionMode**: [`EParticleCollisionMode`](../enums/ue_ue.EParticleCollisionMode.md)

___

### ConstantAcceleration

• **ConstantAcceleration**: [`Vector`](ue_ue_s.Vector.md)

___

### DragCoefficient

• **DragCoefficient**: [`FloatDistribution`](ue_ue.FloatDistribution.md)

___

### DynamicAlpha

• **DynamicAlpha**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

___

### DynamicAlphaScale

• **DynamicAlphaScale**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

___

### DynamicColor

• **DynamicColor**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

___

### DynamicColorScale

• **DynamicColorScale**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

___

### InvMaxSize

• **InvMaxSize**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### InvRotationRateScale

• **InvRotationRateScale**: `number`

___

### LocalVectorField

• **LocalVectorField**: [`GPUSpriteLocalVectorFieldInfo`](ue_ue.GPUSpriteLocalVectorFieldInfo.md)

___

### LockAxisFlag

• **LockAxisFlag**: [`EParticleAxisLock`](../enums/ue_ue.EParticleAxisLock.md)

___

### MaxFacingCameraBlendDistance

• **MaxFacingCameraBlendDistance**: `number`

___

### MaxLifetime

• **MaxLifetime**: `number`

___

### MaxParticleCount

• **MaxParticleCount**: `number`

___

### MinFacingCameraBlendDistance

• **MinFacingCameraBlendDistance**: `number`

___

### OrbitOffsetBase

• **OrbitOffsetBase**: [`Vector`](ue_ue_s.Vector.md)

___

### OrbitOffsetRange

• **OrbitOffsetRange**: [`Vector`](ue_ue_s.Vector.md)

___

### PointAttractorPosition

• **PointAttractorPosition**: [`Vector`](ue_ue_s.Vector.md)

___

### PointAttractorRadiusSq

• **PointAttractorRadiusSq**: `number`

___

### PointAttractorStrength

• **PointAttractorStrength**: [`FloatDistribution`](ue_ue.FloatDistribution.md)

___

### RequiredModule

• **RequiredModule**: [`ParticleModuleRequired`](ue_ue.ParticleModuleRequired.md)

___

### Resilience

• **Resilience**: [`FloatDistribution`](ue_ue.FloatDistribution.md)

___

### ScreenAlignment

• **ScreenAlignment**: [`EParticleScreenAlignment`](../enums/ue_ue.EParticleScreenAlignment.md)

___

### SpawnModule

• **SpawnModule**: [`ParticleModuleSpawn`](ue_ue.ParticleModuleSpawn.md)

___

### SpawnModules

• **SpawnModules**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleModule`](ue_ue.ParticleModule.md)\>

___

### SpawnPerUnitModule

• **SpawnPerUnitModule**: [`ParticleModuleSpawnPerUnit`](ue_ue.ParticleModuleSpawnPerUnit.md)

___

### VectorFieldScale

• **VectorFieldScale**: [`FloatDistribution`](ue_ue.FloatDistribution.md)

___

### \_\_tid\_GPUSpriteEmitterInfo\_\_

• `Private` **\_\_tid\_GPUSpriteEmitterInfo\_\_**: `boolean`

___

### bEnableCollision

• **bEnableCollision**: `boolean`

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
