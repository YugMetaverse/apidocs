[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VehicleEngineData

# Class: VehicleEngineData

[ue/ue](../modules/ue_ue.md).VehicleEngineData

## Table of contents

### Constructors

- [constructor](ue_ue.VehicleEngineData.md#constructor)

### Properties

- [DampingRateFullThrottle](ue_ue.VehicleEngineData.md#dampingratefullthrottle)
- [DampingRateZeroThrottleClutchDisengaged](ue_ue.VehicleEngineData.md#dampingratezerothrottleclutchdisengaged)
- [DampingRateZeroThrottleClutchEngaged](ue_ue.VehicleEngineData.md#dampingratezerothrottleclutchengaged)
- [MOI](ue_ue.VehicleEngineData.md#moi)
- [MaxRPM](ue_ue.VehicleEngineData.md#maxrpm)
- [TorqueCurve](ue_ue.VehicleEngineData.md#torquecurve)
- [\_\_tid\_VehicleEngineData\_\_](ue_ue.VehicleEngineData.md#__tid_vehicleenginedata__)

### Methods

- [StaticClass](ue_ue.VehicleEngineData.md#staticclass)
- [StaticStruct](ue_ue.VehicleEngineData.md#staticstruct)

## Constructors

### constructor

• **new VehicleEngineData**()

• **new VehicleEngineData**(`TorqueCurve`, `MaxRPM`, `MOI`, `DampingRateFullThrottle`, `DampingRateZeroThrottleClutchEngaged`, `DampingRateZeroThrottleClutchDisengaged`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TorqueCurve` | [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md) |
| `MaxRPM` | `number` |
| `MOI` | `number` |
| `DampingRateFullThrottle` | `number` |
| `DampingRateZeroThrottleClutchEngaged` | `number` |
| `DampingRateZeroThrottleClutchDisengaged` | `number` |

## Properties

### DampingRateFullThrottle

• **DampingRateFullThrottle**: `number`

___

### DampingRateZeroThrottleClutchDisengaged

• **DampingRateZeroThrottleClutchDisengaged**: `number`

___

### DampingRateZeroThrottleClutchEngaged

• **DampingRateZeroThrottleClutchEngaged**: `number`

___

### MOI

• **MOI**: `number`

___

### MaxRPM

• **MaxRPM**: `number`

___

### TorqueCurve

• **TorqueCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

___

### \_\_tid\_VehicleEngineData\_\_

• `Private` **\_\_tid\_VehicleEngineData\_\_**: `boolean`

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
