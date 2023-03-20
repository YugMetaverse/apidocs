[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PoseSnapshot

# Class: PoseSnapshot

[ue/ue](../modules/ue_ue.md).PoseSnapshot

## Table of contents

### Constructors

- [constructor](ue_ue.PoseSnapshot.md#constructor)

### Properties

- [BoneNames](ue_ue.PoseSnapshot.md#bonenames)
- [LocalTransforms](ue_ue.PoseSnapshot.md#localtransforms)
- [SkeletalMeshName](ue_ue.PoseSnapshot.md#skeletalmeshname)
- [SnapshotName](ue_ue.PoseSnapshot.md#snapshotname)
- [\_\_tid\_PoseSnapshot\_\_](ue_ue.PoseSnapshot.md#__tid_posesnapshot__)
- [bIsValid](ue_ue.PoseSnapshot.md#bisvalid)

### Methods

- [StaticClass](ue_ue.PoseSnapshot.md#staticclass)
- [StaticStruct](ue_ue.PoseSnapshot.md#staticstruct)

## Constructors

### constructor

• **new PoseSnapshot**()

• **new PoseSnapshot**(`LocalTransforms`, `BoneNames`, `SkeletalMeshName`, `SnapshotName`, `bIsValid`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `LocalTransforms` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\> |
| `BoneNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `SkeletalMeshName` | `string` |
| `SnapshotName` | `string` |
| `bIsValid` | `boolean` |

## Properties

### BoneNames

• **BoneNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### LocalTransforms

• **LocalTransforms**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\>

___

### SkeletalMeshName

• **SkeletalMeshName**: `string`

___

### SnapshotName

• **SnapshotName**: `string`

___

### \_\_tid\_PoseSnapshot\_\_

• `Private` **\_\_tid\_PoseSnapshot\_\_**: `boolean`

___

### bIsValid

• **bIsValid**: `boolean`

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
