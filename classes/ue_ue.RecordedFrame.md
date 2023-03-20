[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / RecordedFrame

# Class: RecordedFrame

[ue/ue](../modules/ue_ue.md).RecordedFrame

## Table of contents

### Constructors

- [constructor](ue_ue.RecordedFrame.md#constructor)

### Properties

- [Breakings](ue_ue.RecordedFrame.md#breakings)
- [Collisions](ue_ue.RecordedFrame.md#collisions)
- [DisabledFlags](ue_ue.RecordedFrame.md#disabledflags)
- [PreviousTransformIndices](ue_ue.RecordedFrame.md#previoustransformindices)
- [Timestamp](ue_ue.RecordedFrame.md#timestamp)
- [Trailings](ue_ue.RecordedFrame.md#trailings)
- [TransformIndices](ue_ue.RecordedFrame.md#transformindices)
- [Transforms](ue_ue.RecordedFrame.md#transforms)
- [\_\_tid\_RecordedFrame\_\_](ue_ue.RecordedFrame.md#__tid_recordedframe__)

### Methods

- [StaticClass](ue_ue.RecordedFrame.md#staticclass)
- [StaticStruct](ue_ue.RecordedFrame.md#staticstruct)

## Constructors

### constructor

• **new RecordedFrame**()

• **new RecordedFrame**(`Transforms`, `TransformIndices`, `PreviousTransformIndices`, `DisabledFlags`, `Collisions`, `Breakings`, `Trailings`, `Timestamp`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Transforms` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\> |
| `TransformIndices` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `PreviousTransformIndices` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `DisabledFlags` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`boolean`\> |
| `Collisions` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SolverCollisionData`](ue_ue.SolverCollisionData.md)\> |
| `Breakings` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SolverBreakingData`](ue_ue.SolverBreakingData.md)\> |
| `Trailings` | [`TSet`](../interfaces/ue_puerts.TSet.md)<[`SolverTrailingData`](ue_ue.SolverTrailingData.md)\> |
| `Timestamp` | `number` |

## Properties

### Breakings

• **Breakings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SolverBreakingData`](ue_ue.SolverBreakingData.md)\>

___

### Collisions

• **Collisions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SolverCollisionData`](ue_ue.SolverCollisionData.md)\>

___

### DisabledFlags

• **DisabledFlags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`boolean`\>

___

### PreviousTransformIndices

• **PreviousTransformIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### Timestamp

• **Timestamp**: `number`

___

### Trailings

• **Trailings**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`SolverTrailingData`](ue_ue.SolverTrailingData.md)\>

___

### TransformIndices

• **TransformIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### Transforms

• **Transforms**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\>

___

### \_\_tid\_RecordedFrame\_\_

• `Private` **\_\_tid\_RecordedFrame\_\_**: `boolean`

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
