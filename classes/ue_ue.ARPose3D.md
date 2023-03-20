[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARPose3D

# Class: ARPose3D

[ue/ue](../modules/ue_ue.md).ARPose3D

## Table of contents

### Constructors

- [constructor](ue_ue.ARPose3D.md#constructor)

### Properties

- [IsJointTracked](ue_ue.ARPose3D.md#isjointtracked)
- [JointTransformSpace](ue_ue.ARPose3D.md#jointtransformspace)
- [JointTransforms](ue_ue.ARPose3D.md#jointtransforms)
- [SkeletonDefinition](ue_ue.ARPose3D.md#skeletondefinition)
- [\_\_tid\_ARPose3D\_\_](ue_ue.ARPose3D.md#__tid_arpose3d__)

### Methods

- [StaticClass](ue_ue.ARPose3D.md#staticclass)
- [StaticStruct](ue_ue.ARPose3D.md#staticstruct)

## Constructors

### constructor

• **new ARPose3D**()

• **new ARPose3D**(`SkeletonDefinition`, `JointTransforms`, `IsJointTracked`, `JointTransformSpace`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SkeletonDefinition` | [`ARSkeletonDefinition`](ue_ue.ARSkeletonDefinition.md) |
| `JointTransforms` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\> |
| `IsJointTracked` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`boolean`\> |
| `JointTransformSpace` | [`EARJointTransformSpace`](../enums/ue_ue.EARJointTransformSpace.md) |

## Properties

### IsJointTracked

• **IsJointTracked**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`boolean`\>

___

### JointTransformSpace

• **JointTransformSpace**: [`EARJointTransformSpace`](../enums/ue_ue.EARJointTransformSpace.md)

___

### JointTransforms

• **JointTransforms**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\>

___

### SkeletonDefinition

• **SkeletonDefinition**: [`ARSkeletonDefinition`](ue_ue.ARSkeletonDefinition.md)

___

### \_\_tid\_ARPose3D\_\_

• `Private` **\_\_tid\_ARPose3D\_\_**: `boolean`

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
