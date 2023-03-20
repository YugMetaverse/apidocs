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

#### Defined in

[ue/ue.d.ts:9341](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9341)

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

#### Defined in

[ue/ue.d.ts:9342](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9342)

## Properties

### AttenuationShape

• **AttenuationShape**: [`EAttenuationShape`](../enums/ue_ue.EAttenuationShape.md)

#### Defined in

[ue/ue.d.ts:9344](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9344)

___

### AttenuationShapeExtents

• **AttenuationShapeExtents**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:9346](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9346)

___

### ConeOffset

• **ConeOffset**: `number`

#### Defined in

[ue/ue.d.ts:9347](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9347)

___

### CustomAttenuationCurve

• **CustomAttenuationCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

#### Defined in

[ue/ue.d.ts:9349](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9349)

___

### DistanceAlgorithm

• **DistanceAlgorithm**: [`EAttenuationDistanceModel`](../enums/ue_ue.EAttenuationDistanceModel.md)

#### Defined in

[ue/ue.d.ts:9343](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9343)

___

### FalloffDistance

• **FalloffDistance**: `number`

#### Defined in

[ue/ue.d.ts:9348](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9348)

___

### \_\_tid\_BaseAttenuationSettings\_\_

• `Private` **\_\_tid\_BaseAttenuationSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:9355](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9355)

___

### dBAttenuationAtMax

• **dBAttenuationAtMax**: `number`

#### Defined in

[ue/ue.d.ts:9345](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9345)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:9353](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9353)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:9354](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9354)
