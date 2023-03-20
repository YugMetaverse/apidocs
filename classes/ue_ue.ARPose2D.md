[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARPose2D

# Class: ARPose2D

[ue/ue](../modules/ue_ue.md).ARPose2D

## Table of contents

### Constructors

- [constructor](ue_ue.ARPose2D.md#constructor)

### Properties

- [IsJointTracked](ue_ue.ARPose2D.md#isjointtracked)
- [JointLocations](ue_ue.ARPose2D.md#jointlocations)
- [SkeletonDefinition](ue_ue.ARPose2D.md#skeletondefinition)
- [\_\_tid\_ARPose2D\_\_](ue_ue.ARPose2D.md#__tid_arpose2d__)

### Methods

- [StaticClass](ue_ue.ARPose2D.md#staticclass)
- [StaticStruct](ue_ue.ARPose2D.md#staticstruct)

## Constructors

### constructor

• **new ARPose2D**()

• **new ARPose2D**(`SkeletonDefinition`, `JointLocations`, `IsJointTracked`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SkeletonDefinition` | [`ARSkeletonDefinition`](ue_ue.ARSkeletonDefinition.md) |
| `JointLocations` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\> |
| `IsJointTracked` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`boolean`\> |

## Properties

### IsJointTracked

• **IsJointTracked**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`boolean`\>

___

### JointLocations

• **JointLocations**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\>

___

### SkeletonDefinition

• **SkeletonDefinition**: [`ARSkeletonDefinition`](ue_ue.ARSkeletonDefinition.md)

___

### \_\_tid\_ARPose2D\_\_

• `Private` **\_\_tid\_ARPose2D\_\_**: `boolean`

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
