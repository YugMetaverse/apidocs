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

#### Defined in

[ue/ue.d.ts:26675](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26675)

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

#### Defined in

[ue/ue.d.ts:26676](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26676)

## Properties

### Breakings

• **Breakings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SolverBreakingData`](ue_ue.SolverBreakingData.md)\>

#### Defined in

[ue/ue.d.ts:26682](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26682)

___

### Collisions

• **Collisions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SolverCollisionData`](ue_ue.SolverCollisionData.md)\>

#### Defined in

[ue/ue.d.ts:26681](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26681)

___

### DisabledFlags

• **DisabledFlags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`boolean`\>

#### Defined in

[ue/ue.d.ts:26680](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26680)

___

### PreviousTransformIndices

• **PreviousTransformIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:26679](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26679)

___

### Timestamp

• **Timestamp**: `number`

#### Defined in

[ue/ue.d.ts:26684](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26684)

___

### Trailings

• **Trailings**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`SolverTrailingData`](ue_ue.SolverTrailingData.md)\>

#### Defined in

[ue/ue.d.ts:26683](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26683)

___

### TransformIndices

• **TransformIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:26678](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26678)

___

### Transforms

• **Transforms**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\>

#### Defined in

[ue/ue.d.ts:26677](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26677)

___

### \_\_tid\_RecordedFrame\_\_

• `Private` **\_\_tid\_RecordedFrame\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:26690](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26690)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:26688](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26688)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:26689](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26689)
