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

## Properties

### DistanceMethod

• **DistanceMethod**: [`ERBFDistanceMethod`](../enums/ue_ue.ERBFDistanceMethod.md)

___

### Function

• **Function**: [`ERBFFunctionType`](../enums/ue_ue.ERBFFunctionType.md)

___

### MedianMax

• **MedianMax**: `number`

___

### MedianMin

• **MedianMin**: `number`

___

### MedianReference

• **MedianReference**: [`Vector`](ue_ue_s.Vector.md)

___

### NormalizeMethod

• **NormalizeMethod**: [`ERBFNormalizeMethod`](../enums/ue_ue.ERBFNormalizeMethod.md)

___

### Radius

• **Radius**: `number`

___

### TargetDimensions

• **TargetDimensions**: `number`

___

### TwistAxis

• **TwistAxis**: [`EBoneAxis`](../enums/ue_ue.EBoneAxis.md)

___

### WeightThreshold

• **WeightThreshold**: `number`

___

### \_\_tid\_RBFParams\_\_

• `Private` **\_\_tid\_RBFParams\_\_**: `boolean`

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
