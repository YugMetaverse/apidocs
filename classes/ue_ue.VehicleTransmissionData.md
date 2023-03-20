[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VehicleTransmissionData

# Class: VehicleTransmissionData

[ue/ue](../modules/ue_ue.md).VehicleTransmissionData

## Table of contents

### Constructors

- [constructor](ue_ue.VehicleTransmissionData.md#constructor)

### Properties

- [ClutchStrength](ue_ue.VehicleTransmissionData.md#clutchstrength)
- [FinalRatio](ue_ue.VehicleTransmissionData.md#finalratio)
- [ForwardGears](ue_ue.VehicleTransmissionData.md#forwardgears)
- [GearAutoBoxLatency](ue_ue.VehicleTransmissionData.md#gearautoboxlatency)
- [GearSwitchTime](ue_ue.VehicleTransmissionData.md#gearswitchtime)
- [NeutralGearUpRatio](ue_ue.VehicleTransmissionData.md#neutralgearupratio)
- [ReverseGearRatio](ue_ue.VehicleTransmissionData.md#reversegearratio)
- [\_\_tid\_VehicleTransmissionData\_\_](ue_ue.VehicleTransmissionData.md#__tid_vehicletransmissiondata__)
- [bUseGearAutoBox](ue_ue.VehicleTransmissionData.md#busegearautobox)

### Methods

- [StaticClass](ue_ue.VehicleTransmissionData.md#staticclass)
- [StaticStruct](ue_ue.VehicleTransmissionData.md#staticstruct)

## Constructors

### constructor

• **new VehicleTransmissionData**()

• **new VehicleTransmissionData**(`bUseGearAutoBox`, `GearSwitchTime`, `GearAutoBoxLatency`, `FinalRatio`, `ForwardGears`, `ReverseGearRatio`, `NeutralGearUpRatio`, `ClutchStrength`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `bUseGearAutoBox` | `boolean` |
| `GearSwitchTime` | `number` |
| `GearAutoBoxLatency` | `number` |
| `FinalRatio` | `number` |
| `ForwardGears` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VehicleGearData`](ue_ue.VehicleGearData.md)\> |
| `ReverseGearRatio` | `number` |
| `NeutralGearUpRatio` | `number` |
| `ClutchStrength` | `number` |

## Properties

### ClutchStrength

• **ClutchStrength**: `number`

___

### FinalRatio

• **FinalRatio**: `number`

___

### ForwardGears

• **ForwardGears**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VehicleGearData`](ue_ue.VehicleGearData.md)\>

___

### GearAutoBoxLatency

• **GearAutoBoxLatency**: `number`

___

### GearSwitchTime

• **GearSwitchTime**: `number`

___

### NeutralGearUpRatio

• **NeutralGearUpRatio**: `number`

___

### ReverseGearRatio

• **ReverseGearRatio**: `number`

___

### \_\_tid\_VehicleTransmissionData\_\_

• `Private` **\_\_tid\_VehicleTransmissionData\_\_**: `boolean`

___

### bUseGearAutoBox

• **bUseGearAutoBox**: `boolean`

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
