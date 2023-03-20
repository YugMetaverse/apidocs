[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PredictProjectilePathParams

# Class: PredictProjectilePathParams

[ue/ue](../modules/ue_ue.md).PredictProjectilePathParams

## Table of contents

### Constructors

- [constructor](ue_ue.PredictProjectilePathParams.md#constructor)

### Properties

- [ActorsToIgnore](ue_ue.PredictProjectilePathParams.md#actorstoignore)
- [DrawDebugTime](ue_ue.PredictProjectilePathParams.md#drawdebugtime)
- [DrawDebugType](ue_ue.PredictProjectilePathParams.md#drawdebugtype)
- [LaunchVelocity](ue_ue.PredictProjectilePathParams.md#launchvelocity)
- [MaxSimTime](ue_ue.PredictProjectilePathParams.md#maxsimtime)
- [ObjectTypes](ue_ue.PredictProjectilePathParams.md#objecttypes)
- [OverrideGravityZ](ue_ue.PredictProjectilePathParams.md#overridegravityz)
- [ProjectileRadius](ue_ue.PredictProjectilePathParams.md#projectileradius)
- [SimFrequency](ue_ue.PredictProjectilePathParams.md#simfrequency)
- [StartLocation](ue_ue.PredictProjectilePathParams.md#startlocation)
- [TraceChannel](ue_ue.PredictProjectilePathParams.md#tracechannel)
- [\_\_tid\_PredictProjectilePathParams\_\_](ue_ue.PredictProjectilePathParams.md#__tid_predictprojectilepathparams__)
- [bTraceComplex](ue_ue.PredictProjectilePathParams.md#btracecomplex)
- [bTraceWithChannel](ue_ue.PredictProjectilePathParams.md#btracewithchannel)
- [bTraceWithCollision](ue_ue.PredictProjectilePathParams.md#btracewithcollision)

### Methods

- [StaticClass](ue_ue.PredictProjectilePathParams.md#staticclass)
- [StaticStruct](ue_ue.PredictProjectilePathParams.md#staticstruct)

## Constructors

### constructor

• **new PredictProjectilePathParams**()

• **new PredictProjectilePathParams**(`StartLocation`, `LaunchVelocity`, `bTraceWithCollision`, `ProjectileRadius`, `MaxSimTime`, `bTraceWithChannel`, `TraceChannel`, `ObjectTypes`, `ActorsToIgnore`, `SimFrequency`, `OverrideGravityZ`, `DrawDebugType`, `DrawDebugTime`, `bTraceComplex`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `StartLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `LaunchVelocity` | [`Vector`](ue_ue_s.Vector.md) |
| `bTraceWithCollision` | `boolean` |
| `ProjectileRadius` | `number` |
| `MaxSimTime` | `number` |
| `bTraceWithChannel` | `boolean` |
| `TraceChannel` | [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md) |
| `ObjectTypes` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EObjectTypeQuery`](../enums/ue_ue.EObjectTypeQuery.md)\> |
| `ActorsToIgnore` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\> |
| `SimFrequency` | `number` |
| `OverrideGravityZ` | `number` |
| `DrawDebugType` | [`EDrawDebugTrace`](../enums/ue_ue.EDrawDebugTrace.md) |
| `DrawDebugTime` | `number` |
| `bTraceComplex` | `boolean` |

## Properties

### ActorsToIgnore

• **ActorsToIgnore**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

___

### DrawDebugTime

• **DrawDebugTime**: `number`

___

### DrawDebugType

• **DrawDebugType**: [`EDrawDebugTrace`](../enums/ue_ue.EDrawDebugTrace.md)

___

### LaunchVelocity

• **LaunchVelocity**: [`Vector`](ue_ue_s.Vector.md)

___

### MaxSimTime

• **MaxSimTime**: `number`

___

### ObjectTypes

• **ObjectTypes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EObjectTypeQuery`](../enums/ue_ue.EObjectTypeQuery.md)\>

___

### OverrideGravityZ

• **OverrideGravityZ**: `number`

___

### ProjectileRadius

• **ProjectileRadius**: `number`

___

### SimFrequency

• **SimFrequency**: `number`

___

### StartLocation

• **StartLocation**: [`Vector`](ue_ue_s.Vector.md)

___

### TraceChannel

• **TraceChannel**: [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

___

### \_\_tid\_PredictProjectilePathParams\_\_

• `Private` **\_\_tid\_PredictProjectilePathParams\_\_**: `boolean`

___

### bTraceComplex

• **bTraceComplex**: `boolean`

___

### bTraceWithChannel

• **bTraceWithChannel**: `boolean`

___

### bTraceWithCollision

• **bTraceWithCollision**: `boolean`

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
