[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ForceFeedbackAttenuationSettings

# Class: ForceFeedbackAttenuationSettings

[ue/ue](../modules/ue_ue.md).ForceFeedbackAttenuationSettings

## Hierarchy

- [`BaseAttenuationSettings`](ue_ue.BaseAttenuationSettings.md)

  ↳ **`ForceFeedbackAttenuationSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.ForceFeedbackAttenuationSettings.md#constructor)

### Properties

- [AttenuationShape](ue_ue.ForceFeedbackAttenuationSettings.md#attenuationshape)
- [AttenuationShapeExtents](ue_ue.ForceFeedbackAttenuationSettings.md#attenuationshapeextents)
- [ConeOffset](ue_ue.ForceFeedbackAttenuationSettings.md#coneoffset)
- [CustomAttenuationCurve](ue_ue.ForceFeedbackAttenuationSettings.md#customattenuationcurve)
- [DistanceAlgorithm](ue_ue.ForceFeedbackAttenuationSettings.md#distancealgorithm)
- [FalloffDistance](ue_ue.ForceFeedbackAttenuationSettings.md#falloffdistance)
- [\_\_tid\_ForceFeedbackAttenuationSettings\_\_](ue_ue.ForceFeedbackAttenuationSettings.md#__tid_forcefeedbackattenuationsettings__)
- [dBAttenuationAtMax](ue_ue.ForceFeedbackAttenuationSettings.md#dbattenuationatmax)

### Methods

- [StaticClass](ue_ue.ForceFeedbackAttenuationSettings.md#staticclass)
- [StaticStruct](ue_ue.ForceFeedbackAttenuationSettings.md#staticstruct)

## Constructors

### constructor

• **new ForceFeedbackAttenuationSettings**()

#### Overrides

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[constructor](ue_ue.BaseAttenuationSettings.md#constructor)

#### Defined in

[ue/ue.d.ts:36159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36159)

## Properties

### AttenuationShape

• **AttenuationShape**: [`EAttenuationShape`](../enums/ue_ue.EAttenuationShape.md)

#### Inherited from

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[AttenuationShape](ue_ue.BaseAttenuationSettings.md#attenuationshape)

#### Defined in

[ue/ue.d.ts:9344](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9344)

___

### AttenuationShapeExtents

• **AttenuationShapeExtents**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[AttenuationShapeExtents](ue_ue.BaseAttenuationSettings.md#attenuationshapeextents)

#### Defined in

[ue/ue.d.ts:9346](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9346)

___

### ConeOffset

• **ConeOffset**: `number`

#### Inherited from

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[ConeOffset](ue_ue.BaseAttenuationSettings.md#coneoffset)

#### Defined in

[ue/ue.d.ts:9347](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9347)

___

### CustomAttenuationCurve

• **CustomAttenuationCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

#### Inherited from

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[CustomAttenuationCurve](ue_ue.BaseAttenuationSettings.md#customattenuationcurve)

#### Defined in

[ue/ue.d.ts:9349](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9349)

___

### DistanceAlgorithm

• **DistanceAlgorithm**: [`EAttenuationDistanceModel`](../enums/ue_ue.EAttenuationDistanceModel.md)

#### Inherited from

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[DistanceAlgorithm](ue_ue.BaseAttenuationSettings.md#distancealgorithm)

#### Defined in

[ue/ue.d.ts:9343](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9343)

___

### FalloffDistance

• **FalloffDistance**: `number`

#### Inherited from

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[FalloffDistance](ue_ue.BaseAttenuationSettings.md#falloffdistance)

#### Defined in

[ue/ue.d.ts:9348](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9348)

___

### \_\_tid\_ForceFeedbackAttenuationSettings\_\_

• `Private` **\_\_tid\_ForceFeedbackAttenuationSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:36165](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36165)

___

### dBAttenuationAtMax

• **dBAttenuationAtMax**: `number`

#### Inherited from

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[dBAttenuationAtMax](ue_ue.BaseAttenuationSettings.md#dbattenuationatmax)

#### Defined in

[ue/ue.d.ts:9345](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9345)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[StaticClass](ue_ue.BaseAttenuationSettings.md#staticclass)

#### Defined in

[ue/ue.d.ts:36163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36163)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[StaticStruct](ue_ue.BaseAttenuationSettings.md#staticstruct)

#### Defined in

[ue/ue.d.ts:36164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36164)
