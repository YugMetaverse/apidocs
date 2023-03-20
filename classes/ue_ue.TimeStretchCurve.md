[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TimeStretchCurve

# Class: TimeStretchCurve

[ue/ue](../modules/ue_ue.md).TimeStretchCurve

## Table of contents

### Constructors

- [constructor](ue_ue.TimeStretchCurve.md#constructor)

### Properties

- [CurveValueMinPrecision](ue_ue.TimeStretchCurve.md#curvevalueminprecision)
- [Markers](ue_ue.TimeStretchCurve.md#markers)
- [SamplingRate](ue_ue.TimeStretchCurve.md#samplingrate)
- [Sum\_dT\_i\_by\_C\_i](ue_ue.TimeStretchCurve.md#sum_dt_i_by_c_i)
- [\_\_tid\_TimeStretchCurve\_\_](ue_ue.TimeStretchCurve.md#__tid_timestretchcurve__)

### Methods

- [StaticClass](ue_ue.TimeStretchCurve.md#staticclass)
- [StaticStruct](ue_ue.TimeStretchCurve.md#staticstruct)

## Constructors

### constructor

• **new TimeStretchCurve**()

• **new TimeStretchCurve**(`SamplingRate`, `CurveValueMinPrecision`, `Markers`, `Sum_dT_i_by_C_i`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SamplingRate` | `number` |
| `CurveValueMinPrecision` | `number` |
| `Markers` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimeStretchCurveMarker`](ue_ue.TimeStretchCurveMarker.md)\> |
| `Sum_dT_i_by_C_i` | [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<`number`\> |

## Properties

### CurveValueMinPrecision

• **CurveValueMinPrecision**: `number`

___

### Markers

• **Markers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimeStretchCurveMarker`](ue_ue.TimeStretchCurveMarker.md)\>

___

### SamplingRate

• **SamplingRate**: `number`

___

### Sum\_dT\_i\_by\_C\_i

• **Sum\_dT\_i\_by\_C\_i**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<`number`\>

___

### \_\_tid\_TimeStretchCurve\_\_

• `Private` **\_\_tid\_TimeStretchCurve\_\_**: `boolean`

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
