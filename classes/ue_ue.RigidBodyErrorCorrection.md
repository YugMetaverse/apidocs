[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / RigidBodyErrorCorrection

# Class: RigidBodyErrorCorrection

[ue/ue](../modules/ue_ue.md).RigidBodyErrorCorrection

## Table of contents

### Constructors

- [constructor](ue_ue.RigidBodyErrorCorrection.md#constructor)

### Properties

- [AngleLerp](ue_ue.RigidBodyErrorCorrection.md#anglelerp)
- [AngularVelocityCoefficient](ue_ue.RigidBodyErrorCorrection.md#angularvelocitycoefficient)
- [ErrorAccumulationDistanceSq](ue_ue.RigidBodyErrorCorrection.md#erroraccumulationdistancesq)
- [ErrorAccumulationSeconds](ue_ue.RigidBodyErrorCorrection.md#erroraccumulationseconds)
- [ErrorAccumulationSimilarity](ue_ue.RigidBodyErrorCorrection.md#erroraccumulationsimilarity)
- [ErrorPerAngularDifference](ue_ue.RigidBodyErrorCorrection.md#errorperangulardifference)
- [ErrorPerLinearDifference](ue_ue.RigidBodyErrorCorrection.md#errorperlineardifference)
- [LinearVelocityCoefficient](ue_ue.RigidBodyErrorCorrection.md#linearvelocitycoefficient)
- [MaxLinearHardSnapDistance](ue_ue.RigidBodyErrorCorrection.md#maxlinearhardsnapdistance)
- [MaxRestoredStateError](ue_ue.RigidBodyErrorCorrection.md#maxrestoredstateerror)
- [PingExtrapolation](ue_ue.RigidBodyErrorCorrection.md#pingextrapolation)
- [PingLimit](ue_ue.RigidBodyErrorCorrection.md#pinglimit)
- [PositionLerp](ue_ue.RigidBodyErrorCorrection.md#positionlerp)
- [\_\_tid\_RigidBodyErrorCorrection\_\_](ue_ue.RigidBodyErrorCorrection.md#__tid_rigidbodyerrorcorrection__)

### Methods

- [StaticClass](ue_ue.RigidBodyErrorCorrection.md#staticclass)
- [StaticStruct](ue_ue.RigidBodyErrorCorrection.md#staticstruct)

## Constructors

### constructor

• **new RigidBodyErrorCorrection**()

• **new RigidBodyErrorCorrection**(`PingExtrapolation`, `PingLimit`, `ErrorPerLinearDifference`, `ErrorPerAngularDifference`, `MaxRestoredStateError`, `MaxLinearHardSnapDistance`, `PositionLerp`, `AngleLerp`, `LinearVelocityCoefficient`, `AngularVelocityCoefficient`, `ErrorAccumulationSeconds`, `ErrorAccumulationDistanceSq`, `ErrorAccumulationSimilarity`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PingExtrapolation` | `number` |
| `PingLimit` | `number` |
| `ErrorPerLinearDifference` | `number` |
| `ErrorPerAngularDifference` | `number` |
| `MaxRestoredStateError` | `number` |
| `MaxLinearHardSnapDistance` | `number` |
| `PositionLerp` | `number` |
| `AngleLerp` | `number` |
| `LinearVelocityCoefficient` | `number` |
| `AngularVelocityCoefficient` | `number` |
| `ErrorAccumulationSeconds` | `number` |
| `ErrorAccumulationDistanceSq` | `number` |
| `ErrorAccumulationSimilarity` | `number` |

## Properties

### AngleLerp

• **AngleLerp**: `number`

___

### AngularVelocityCoefficient

• **AngularVelocityCoefficient**: `number`

___

### ErrorAccumulationDistanceSq

• **ErrorAccumulationDistanceSq**: `number`

___

### ErrorAccumulationSeconds

• **ErrorAccumulationSeconds**: `number`

___

### ErrorAccumulationSimilarity

• **ErrorAccumulationSimilarity**: `number`

___

### ErrorPerAngularDifference

• **ErrorPerAngularDifference**: `number`

___

### ErrorPerLinearDifference

• **ErrorPerLinearDifference**: `number`

___

### LinearVelocityCoefficient

• **LinearVelocityCoefficient**: `number`

___

### MaxLinearHardSnapDistance

• **MaxLinearHardSnapDistance**: `number`

___

### MaxRestoredStateError

• **MaxRestoredStateError**: `number`

___

### PingExtrapolation

• **PingExtrapolation**: `number`

___

### PingLimit

• **PingLimit**: `number`

___

### PositionLerp

• **PositionLerp**: `number`

___

### \_\_tid\_RigidBodyErrorCorrection\_\_

• `Private` **\_\_tid\_RigidBodyErrorCorrection\_\_**: `boolean`

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
