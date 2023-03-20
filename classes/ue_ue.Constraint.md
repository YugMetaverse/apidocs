[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Constraint

# Class: Constraint

[ue/ue](../modules/ue_ue.md).Constraint

## Table of contents

### Constructors

- [constructor](ue_ue.Constraint.md#constructor)

### Properties

- [OffsetOption](ue_ue.Constraint.md#offsetoption)
- [PerAxis](ue_ue.Constraint.md#peraxis)
- [TargetBone](ue_ue.Constraint.md#targetbone)
- [TransformType](ue_ue.Constraint.md#transformtype)
- [\_\_tid\_Constraint\_\_](ue_ue.Constraint.md#__tid_constraint__)

### Methods

- [StaticClass](ue_ue.Constraint.md#staticclass)
- [StaticStruct](ue_ue.Constraint.md#staticstruct)

## Constructors

### constructor

• **new Constraint**()

• **new Constraint**(`TargetBone`, `OffsetOption`, `TransformType`, `PerAxis`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `OffsetOption` | [`EConstraintOffsetOption`](../enums/ue_ue.EConstraintOffsetOption.md) |
| `TransformType` | [`ETransformConstraintType`](../enums/ue_ue.ETransformConstraintType.md) |
| `PerAxis` | [`FilterOptionPerAxis`](ue_ue.FilterOptionPerAxis.md) |

## Properties

### OffsetOption

• **OffsetOption**: [`EConstraintOffsetOption`](../enums/ue_ue.EConstraintOffsetOption.md)

___

### PerAxis

• **PerAxis**: [`FilterOptionPerAxis`](ue_ue.FilterOptionPerAxis.md)

___

### TargetBone

• **TargetBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### TransformType

• **TransformType**: [`ETransformConstraintType`](../enums/ue_ue.ETransformConstraintType.md)

___

### \_\_tid\_Constraint\_\_

• `Private` **\_\_tid\_Constraint\_\_**: `boolean`

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
