[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / RBFParams

# Class: RBFParams

[ue/ue](../modules/ue_ue.md).RBFParams

## Table of contents

### Constructors

- [constructor](ue_ue.RBFParams.md#constructor)

### Properties

- [DistanceMethod](ue_ue.RBFParams.md#distancemethod)
- [Function](ue_ue.RBFParams.md#function)
- [MedianMax](ue_ue.RBFParams.md#medianmax)
- [MedianMin](ue_ue.RBFParams.md#medianmin)
- [MedianReference](ue_ue.RBFParams.md#medianreference)
- [NormalizeMethod](ue_ue.RBFParams.md#normalizemethod)
- [Radius](ue_ue.RBFParams.md#radius)
- [TargetDimensions](ue_ue.RBFParams.md#targetdimensions)
- [TwistAxis](ue_ue.RBFParams.md#twistaxis)
- [WeightThreshold](ue_ue.RBFParams.md#weightthreshold)
- [\_\_tid\_RBFParams\_\_](ue_ue.RBFParams.md#__tid_rbfparams__)

### Methods

- [StaticClass](ue_ue.RBFParams.md#staticclass)
- [StaticStruct](ue_ue.RBFParams.md#staticstruct)

## Constructors

### constructor

• **new RBFParams**()

#### Defined in

[ue/ue.d.ts:19182](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19182)

• **new RBFParams**(`TargetDimensions`, `Radius`, `Function`, `DistanceMethod`, `TwistAxis`, `WeightThreshold`, `NormalizeMethod`, `MedianReference`, `MedianMin`, `MedianMax`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetDimensions` | `number` |
| `Radius` | `number` |
| `Function` | [`ERBFFunctionType`](../enums/ue_ue.ERBFFunctionType.md) |
| `DistanceMethod` | [`ERBFDistanceMethod`](../enums/ue_ue.ERBFDistanceMethod.md) |
| `TwistAxis` | [`EBoneAxis`](../enums/ue_ue.EBoneAxis.md) |
| `WeightThreshold` | `number` |
| `NormalizeMethod` | [`ERBFNormalizeMethod`](../enums/ue_ue.ERBFNormalizeMethod.md) |
| `MedianReference` | [`Vector`](ue_ue_s.Vector.md) |
| `MedianMin` | `number` |
| `MedianMax` | `number` |

#### Defined in

[ue/ue.d.ts:19183](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19183)

## Properties

### DistanceMethod

• **DistanceMethod**: [`ERBFDistanceMethod`](../enums/ue_ue.ERBFDistanceMethod.md)

#### Defined in

[ue/ue.d.ts:19187](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19187)

___

### Function

• **Function**: [`ERBFFunctionType`](../enums/ue_ue.ERBFFunctionType.md)

#### Defined in

[ue/ue.d.ts:19186](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19186)

___

### MedianMax

• **MedianMax**: `number`

#### Defined in

[ue/ue.d.ts:19193](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19193)

___

### MedianMin

• **MedianMin**: `number`

#### Defined in

[ue/ue.d.ts:19192](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19192)

___

### MedianReference

• **MedianReference**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:19191](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19191)

___

### NormalizeMethod

• **NormalizeMethod**: [`ERBFNormalizeMethod`](../enums/ue_ue.ERBFNormalizeMethod.md)

#### Defined in

[ue/ue.d.ts:19190](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19190)

___

### Radius

• **Radius**: `number`

#### Defined in

[ue/ue.d.ts:19185](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19185)

___

### TargetDimensions

• **TargetDimensions**: `number`

#### Defined in

[ue/ue.d.ts:19184](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19184)

___

### TwistAxis

• **TwistAxis**: [`EBoneAxis`](../enums/ue_ue.EBoneAxis.md)

#### Defined in

[ue/ue.d.ts:19188](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19188)

___

### WeightThreshold

• **WeightThreshold**: `number`

#### Defined in

[ue/ue.d.ts:19189](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19189)

___

### \_\_tid\_RBFParams\_\_

• `Private` **\_\_tid\_RBFParams\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:19199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19199)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:19197](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19197)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:19198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19198)
