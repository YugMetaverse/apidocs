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

#### Defined in

[ue/ue.d.ts:36802](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36802)

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

#### Defined in

[ue/ue.d.ts:36803](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36803)

## Properties

### ActorsToIgnore

• **ActorsToIgnore**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Defined in

[ue/ue.d.ts:36812](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36812)

___

### DrawDebugTime

• **DrawDebugTime**: `number`

#### Defined in

[ue/ue.d.ts:36816](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36816)

___

### DrawDebugType

• **DrawDebugType**: [`EDrawDebugTrace`](../enums/ue_ue.EDrawDebugTrace.md)

#### Defined in

[ue/ue.d.ts:36815](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36815)

___

### LaunchVelocity

• **LaunchVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:36805](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36805)

___

### MaxSimTime

• **MaxSimTime**: `number`

#### Defined in

[ue/ue.d.ts:36808](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36808)

___

### ObjectTypes

• **ObjectTypes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EObjectTypeQuery`](../enums/ue_ue.EObjectTypeQuery.md)\>

#### Defined in

[ue/ue.d.ts:36811](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36811)

___

### OverrideGravityZ

• **OverrideGravityZ**: `number`

#### Defined in

[ue/ue.d.ts:36814](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36814)

___

### ProjectileRadius

• **ProjectileRadius**: `number`

#### Defined in

[ue/ue.d.ts:36807](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36807)

___

### SimFrequency

• **SimFrequency**: `number`

#### Defined in

[ue/ue.d.ts:36813](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36813)

___

### StartLocation

• **StartLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:36804](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36804)

___

### TraceChannel

• **TraceChannel**: [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Defined in

[ue/ue.d.ts:36810](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36810)

___

### \_\_tid\_PredictProjectilePathParams\_\_

• `Private` **\_\_tid\_PredictProjectilePathParams\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:36823](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36823)

___

### bTraceComplex

• **bTraceComplex**: `boolean`

#### Defined in

[ue/ue.d.ts:36817](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36817)

___

### bTraceWithChannel

• **bTraceWithChannel**: `boolean`

#### Defined in

[ue/ue.d.ts:36809](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36809)

___

### bTraceWithCollision

• **bTraceWithCollision**: `boolean`

#### Defined in

[ue/ue.d.ts:36806](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36806)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:36821](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36821)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:36822](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36822)
