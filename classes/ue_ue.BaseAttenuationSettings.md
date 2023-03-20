[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BaseAttenuationSettings

# Class: BaseAttenuationSettings

[ue/ue](../modules/ue_ue.md).BaseAttenuationSettings

## Hierarchy

- **`BaseAttenuationSettings`**

  ↳ [`SoundAttenuationSettings`](ue_ue.SoundAttenuationSettings.md)

  ↳ [`ForceFeedbackAttenuationSettings`](ue_ue.ForceFeedbackAttenuationSettings.md)

## Table of contents

### Constructors

- [constructor](ue_ue.BaseAttenuationSettings.md#constructor)

### Properties

- [AttenuationShape](ue_ue.BaseAttenuationSettings.md#attenuationshape)
- [AttenuationShapeExtents](ue_ue.BaseAttenuationSettings.md#attenuationshapeextents)
- [ConeOffset](ue_ue.BaseAttenuationSettings.md#coneoffset)
- [CustomAttenuationCurve](ue_ue.BaseAttenuationSettings.md#customattenuationcurve)
- [DistanceAlgorithm](ue_ue.BaseAttenuationSettings.md#distancealgorithm)
- [FalloffDistance](ue_ue.BaseAttenuationSettings.md#falloffdistance)
- [\_\_tid\_BaseAttenuationSettings\_\_](ue_ue.BaseAttenuationSettings.md#__tid_baseattenuationsettings__)
- [dBAttenuationAtMax](ue_ue.BaseAttenuationSettings.md#dbattenuationatmax)

### Methods

- [StaticClass](ue_ue.BaseAttenuationSettings.md#staticclass)
- [StaticStruct](ue_ue.BaseAttenuationSettings.md#staticstruct)

## Constructors

### constructor

• **new BaseAttenuationSettings**()

• **new BaseAttenuationSettings**(`DistanceAlgorithm`, `AttenuationShape`, `dBAttenuationAtMax`, `AttenuationShapeExtents`, `ConeOffset`, `FalloffDistance`, `CustomAttenuationCurve`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `DistanceAlgorithm` | [`EAttenuationDistanceModel`](../enums/ue_ue.EAttenuationDistanceModel.md) |
| `AttenuationShape` | [`EAttenuationShape`](../enums/ue_ue.EAttenuationShape.md) |
| `dBAttenuationAtMax` | `number` |
| `AttenuationShapeExtents` | [`Vector`](ue_ue_s.Vector.md) |
| `ConeOffset` | `number` |
| `FalloffDistance` | `number` |
| `CustomAttenuationCurve` | [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md) |

## Properties

### AttenuationShape

• **AttenuationShape**: [`EAttenuationShape`](../enums/ue_ue.EAttenuationShape.md)

___

### AttenuationShapeExtents

• **AttenuationShapeExtents**: [`Vector`](ue_ue_s.Vector.md)

___

### ConeOffset

• **ConeOffset**: `number`

___

### CustomAttenuationCurve

• **CustomAttenuationCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

___

### DistanceAlgorithm

• **DistanceAlgorithm**: [`EAttenuationDistanceModel`](../enums/ue_ue.EAttenuationDistanceModel.md)

___

### FalloffDistance

• **FalloffDistance**: `number`

___

### \_\_tid\_BaseAttenuationSettings\_\_

• `Private` **\_\_tid\_BaseAttenuationSettings\_\_**: `boolean`

___

### dBAttenuationAtMax

• **dBAttenuationAtMax**: `number`

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
