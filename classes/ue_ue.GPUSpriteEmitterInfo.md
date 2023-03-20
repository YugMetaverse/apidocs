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

#### Defined in

[ue/ue.d.ts:56477](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56477)

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

#### Defined in

[ue/ue.d.ts:56478](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56478)

## Properties

### CollisionMode

• **CollisionMode**: [`EParticleCollisionMode`](../enums/ue_ue.EParticleCollisionMode.md)

#### Defined in

[ue/ue.d.ts:56500](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56500)

___

### ConstantAcceleration

• **ConstantAcceleration**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:56488](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56488)

___

### DragCoefficient

• **DragCoefficient**: [`FloatDistribution`](ue_ue.FloatDistribution.md)

#### Defined in

[ue/ue.d.ts:56485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56485)

___

### DynamicAlpha

• **DynamicAlpha**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

#### Defined in

[ue/ue.d.ts:56505](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56505)

___

### DynamicAlphaScale

• **DynamicAlphaScale**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

#### Defined in

[ue/ue.d.ts:56507](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56507)

___

### DynamicColor

• **DynamicColor**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

#### Defined in

[ue/ue.d.ts:56504](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56504)

___

### DynamicColorScale

• **DynamicColorScale**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

#### Defined in

[ue/ue.d.ts:56506](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56506)

___

### InvMaxSize

• **InvMaxSize**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:56493](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56493)

___

### InvRotationRateScale

• **InvRotationRateScale**: `number`

#### Defined in

[ue/ue.d.ts:56494](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56494)

___

### LocalVectorField

• **LocalVectorField**: [`GPUSpriteLocalVectorFieldInfo`](ue_ue.GPUSpriteLocalVectorFieldInfo.md)

#### Defined in

[ue/ue.d.ts:56483](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56483)

___

### LockAxisFlag

• **LockAxisFlag**: [`EParticleAxisLock`](../enums/ue_ue.EParticleAxisLock.md)

#### Defined in

[ue/ue.d.ts:56498](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56498)

___

### MaxFacingCameraBlendDistance

• **MaxFacingCameraBlendDistance**: `number`

#### Defined in

[ue/ue.d.ts:56503](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56503)

___

### MaxLifetime

• **MaxLifetime**: `number`

#### Defined in

[ue/ue.d.ts:56495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56495)

___

### MaxParticleCount

• **MaxParticleCount**: `number`

#### Defined in

[ue/ue.d.ts:56496](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56496)

___

### MinFacingCameraBlendDistance

• **MinFacingCameraBlendDistance**: `number`

#### Defined in

[ue/ue.d.ts:56502](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56502)

___

### OrbitOffsetBase

• **OrbitOffsetBase**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:56491](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56491)

___

### OrbitOffsetRange

• **OrbitOffsetRange**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:56492](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56492)

___

### PointAttractorPosition

• **PointAttractorPosition**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:56489](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56489)

___

### PointAttractorRadiusSq

• **PointAttractorRadiusSq**: `number`

#### Defined in

[ue/ue.d.ts:56490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56490)

___

### PointAttractorStrength

• **PointAttractorStrength**: [`FloatDistribution`](ue_ue.FloatDistribution.md)

#### Defined in

[ue/ue.d.ts:56486](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56486)

___

### RequiredModule

• **RequiredModule**: [`ParticleModuleRequired`](ue_ue.ParticleModuleRequired.md)

#### Defined in

[ue/ue.d.ts:56479](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56479)

___

### Resilience

• **Resilience**: [`FloatDistribution`](ue_ue.FloatDistribution.md)

#### Defined in

[ue/ue.d.ts:56487](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56487)

___

### ScreenAlignment

• **ScreenAlignment**: [`EParticleScreenAlignment`](../enums/ue_ue.EParticleScreenAlignment.md)

#### Defined in

[ue/ue.d.ts:56497](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56497)

___

### SpawnModule

• **SpawnModule**: [`ParticleModuleSpawn`](ue_ue.ParticleModuleSpawn.md)

#### Defined in

[ue/ue.d.ts:56480](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56480)

___

### SpawnModules

• **SpawnModules**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleModule`](ue_ue.ParticleModule.md)\>

#### Defined in

[ue/ue.d.ts:56482](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56482)

___

### SpawnPerUnitModule

• **SpawnPerUnitModule**: [`ParticleModuleSpawnPerUnit`](ue_ue.ParticleModuleSpawnPerUnit.md)

#### Defined in

[ue/ue.d.ts:56481](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56481)

___

### VectorFieldScale

• **VectorFieldScale**: [`FloatDistribution`](ue_ue.FloatDistribution.md)

#### Defined in

[ue/ue.d.ts:56484](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56484)

___

### \_\_tid\_GPUSpriteEmitterInfo\_\_

• `Private` **\_\_tid\_GPUSpriteEmitterInfo\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:56513](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56513)

___

### bEnableCollision

• **bEnableCollision**: `boolean`

#### Defined in

[ue/ue.d.ts:56499](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56499)

___

### bRemoveHMDRoll

• **bRemoveHMDRoll**: `boolean`

#### Defined in

[ue/ue.d.ts:56501](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56501)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:56511](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56511)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:56512](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56512)
