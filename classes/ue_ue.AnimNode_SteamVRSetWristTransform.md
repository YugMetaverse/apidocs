[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_SteamVRSetWristTransform

# Class: AnimNode\_SteamVRSetWristTransform

[ue/ue](../modules/ue_ue.md).AnimNode_SteamVRSetWristTransform

## Hierarchy

- [`AnimNode_Base`](ue_ue.AnimNode_Base.md)

  ↳ **`AnimNode_SteamVRSetWristTransform`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_SteamVRSetWristTransform.md#constructor)

### Properties

- [HandSkeleton](ue_ue.AnimNode_SteamVRSetWristTransform.md#handskeleton)
- [ReferencePose](ue_ue.AnimNode_SteamVRSetWristTransform.md#referencepose)
- [TargetPose](ue_ue.AnimNode_SteamVRSetWristTransform.md#targetpose)
- [\_\_tid\_AnimNode\_SteamVRSetWristTransform\_\_](ue_ue.AnimNode_SteamVRSetWristTransform.md#__tid_animnode_steamvrsetwristtransform__)

### Methods

- [StaticClass](ue_ue.AnimNode_SteamVRSetWristTransform.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_SteamVRSetWristTransform.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_SteamVRSetWristTransform**()

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[constructor](ue_ue.AnimNode_Base.md#constructor)

• **new AnimNode_SteamVRSetWristTransform**(`ReferencePose`, `HandSkeleton`, `TargetPose`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ReferencePose` | [`PoseLink`](ue_ue.PoseLink.md) |
| `HandSkeleton` | [`EHandSkeleton`](../enums/ue_ue.EHandSkeleton.md) |
| `TargetPose` | [`PoseLink`](ue_ue.PoseLink.md) |

#### Overrides

UE.AnimNode\_Base.constructor

## Properties

### HandSkeleton

• **HandSkeleton**: [`EHandSkeleton`](../enums/ue_ue.EHandSkeleton.md)

___

### ReferencePose

• **ReferencePose**: [`PoseLink`](ue_ue.PoseLink.md)

___

### TargetPose

• **TargetPose**: [`PoseLink`](ue_ue.PoseLink.md)

___

### \_\_tid\_AnimNode\_SteamVRSetWristTransform\_\_

• `Private` **\_\_tid\_AnimNode\_SteamVRSetWristTransform\_\_**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticClass](ue_ue.AnimNode_Base.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticStruct](ue_ue.AnimNode_Base.md#staticstruct)
