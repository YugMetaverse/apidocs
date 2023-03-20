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

#### Defined in

[ue/ue.d.ts:57554](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57554)

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

#### Defined in

[ue/ue.d.ts:57555](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57555)

## Properties

### AngleLerp

• **AngleLerp**: `number`

#### Defined in

[ue/ue.d.ts:57563](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57563)

___

### AngularVelocityCoefficient

• **AngularVelocityCoefficient**: `number`

#### Defined in

[ue/ue.d.ts:57565](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57565)

___

### ErrorAccumulationDistanceSq

• **ErrorAccumulationDistanceSq**: `number`

#### Defined in

[ue/ue.d.ts:57567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57567)

___

### ErrorAccumulationSeconds

• **ErrorAccumulationSeconds**: `number`

#### Defined in

[ue/ue.d.ts:57566](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57566)

___

### ErrorAccumulationSimilarity

• **ErrorAccumulationSimilarity**: `number`

#### Defined in

[ue/ue.d.ts:57568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57568)

___

### ErrorPerAngularDifference

• **ErrorPerAngularDifference**: `number`

#### Defined in

[ue/ue.d.ts:57559](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57559)

___

### ErrorPerLinearDifference

• **ErrorPerLinearDifference**: `number`

#### Defined in

[ue/ue.d.ts:57558](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57558)

___

### LinearVelocityCoefficient

• **LinearVelocityCoefficient**: `number`

#### Defined in

[ue/ue.d.ts:57564](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57564)

___

### MaxLinearHardSnapDistance

• **MaxLinearHardSnapDistance**: `number`

#### Defined in

[ue/ue.d.ts:57561](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57561)

___

### MaxRestoredStateError

• **MaxRestoredStateError**: `number`

#### Defined in

[ue/ue.d.ts:57560](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57560)

___

### PingExtrapolation

• **PingExtrapolation**: `number`

#### Defined in

[ue/ue.d.ts:57556](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57556)

___

### PingLimit

• **PingLimit**: `number`

#### Defined in

[ue/ue.d.ts:57557](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57557)

___

### PositionLerp

• **PositionLerp**: `number`

#### Defined in

[ue/ue.d.ts:57562](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57562)

___

### \_\_tid\_RigidBodyErrorCorrection\_\_

• `Private` **\_\_tid\_RigidBodyErrorCorrection\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:57574](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57574)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:57572](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57572)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:57573](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57573)
