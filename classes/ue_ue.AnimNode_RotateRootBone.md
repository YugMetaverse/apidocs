[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_RotateRootBone

# Class: AnimNode\_RotateRootBone

[ue/ue](../modules/ue_ue.md).AnimNode_RotateRootBone

## Hierarchy

- [`AnimNode_Base`](ue_ue.AnimNode_Base.md)

  ↳ **`AnimNode_RotateRootBone`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_RotateRootBone.md#constructor)

### Properties

- [BasePose](ue_ue.AnimNode_RotateRootBone.md#basepose)
- [MeshToComponent](ue_ue.AnimNode_RotateRootBone.md#meshtocomponent)
- [Pitch](ue_ue.AnimNode_RotateRootBone.md#pitch)
- [PitchScaleBiasClamp](ue_ue.AnimNode_RotateRootBone.md#pitchscalebiasclamp)
- [Yaw](ue_ue.AnimNode_RotateRootBone.md#yaw)
- [YawScaleBiasClamp](ue_ue.AnimNode_RotateRootBone.md#yawscalebiasclamp)
- [\_\_tid\_AnimNode\_RotateRootBone\_\_](ue_ue.AnimNode_RotateRootBone.md#__tid_animnode_rotaterootbone__)

### Methods

- [StaticClass](ue_ue.AnimNode_RotateRootBone.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_RotateRootBone.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_RotateRootBone**()

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[constructor](ue_ue.AnimNode_Base.md#constructor)

• **new AnimNode_RotateRootBone**(`BasePose`, `Pitch`, `Yaw`, `PitchScaleBiasClamp`, `YawScaleBiasClamp`, `MeshToComponent`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BasePose` | [`PoseLink`](ue_ue.PoseLink.md) |
| `Pitch` | `number` |
| `Yaw` | `number` |
| `PitchScaleBiasClamp` | [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md) |
| `YawScaleBiasClamp` | [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md) |
| `MeshToComponent` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Overrides

UE.AnimNode\_Base.constructor

## Properties

### BasePose

• **BasePose**: [`PoseLink`](ue_ue.PoseLink.md)

___

### MeshToComponent

• **MeshToComponent**: [`Rotator`](ue_ue_s.Rotator.md)

___

### Pitch

• **Pitch**: `number`

___

### PitchScaleBiasClamp

• **PitchScaleBiasClamp**: [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md)

___

### Yaw

• **Yaw**: `number`

___

### YawScaleBiasClamp

• **YawScaleBiasClamp**: [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md)

___

### \_\_tid\_AnimNode\_RotateRootBone\_\_

• `Private` **\_\_tid\_AnimNode\_RotateRootBone\_\_**: `boolean`

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
