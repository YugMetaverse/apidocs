[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARTraceResult

# Class: ARTraceResult

[ue/ue](../modules/ue_ue.md).ARTraceResult

## Table of contents

### Constructors

- [constructor](ue_ue.ARTraceResult.md#constructor)

### Properties

- [DistanceFromCamera](ue_ue.ARTraceResult.md#distancefromcamera)
- [LocalToTrackingTransform](ue_ue.ARTraceResult.md#localtotrackingtransform)
- [TraceChannel](ue_ue.ARTraceResult.md#tracechannel)
- [TrackedGeometry](ue_ue.ARTraceResult.md#trackedgeometry)
- [\_\_tid\_ARTraceResult\_\_](ue_ue.ARTraceResult.md#__tid_artraceresult__)

### Methods

- [StaticClass](ue_ue.ARTraceResult.md#staticclass)
- [StaticStruct](ue_ue.ARTraceResult.md#staticstruct)

## Constructors

### constructor

• **new ARTraceResult**()

• **new ARTraceResult**(`DistanceFromCamera`, `TraceChannel`, `LocalToTrackingTransform`, `TrackedGeometry`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `DistanceFromCamera` | `number` |
| `TraceChannel` | [`EARLineTraceChannels`](../enums/ue_ue.EARLineTraceChannels.md) |
| `LocalToTrackingTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `TrackedGeometry` | [`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md) |

## Properties

### DistanceFromCamera

• **DistanceFromCamera**: `number`

___

### LocalToTrackingTransform

• **LocalToTrackingTransform**: [`Transform`](ue_ue_s.Transform.md)

___

### TraceChannel

• **TraceChannel**: [`EARLineTraceChannels`](../enums/ue_ue.EARLineTraceChannels.md)

___

### TrackedGeometry

• **TrackedGeometry**: [`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)

___

### \_\_tid\_ARTraceResult\_\_

• `Private` **\_\_tid\_ARTraceResult\_\_**: `boolean`

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
