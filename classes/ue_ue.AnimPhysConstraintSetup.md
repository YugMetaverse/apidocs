[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimPhysConstraintSetup

# Class: AnimPhysConstraintSetup

[ue/ue](../modules/ue_ue.md).AnimPhysConstraintSetup

## Table of contents

### Constructors

- [constructor](ue_ue.AnimPhysConstraintSetup.md#constructor)

### Properties

- [AngularConstraintType](ue_ue.AnimPhysConstraintSetup.md#angularconstrainttype)
- [AngularLimitsMax](ue_ue.AnimPhysConstraintSetup.md#angularlimitsmax)
- [AngularLimitsMin](ue_ue.AnimPhysConstraintSetup.md#angularlimitsmin)
- [AngularTarget](ue_ue.AnimPhysConstraintSetup.md#angulartarget)
- [AngularTargetAxis](ue_ue.AnimPhysConstraintSetup.md#angulartargetaxis)
- [AngularXAngle](ue_ue.AnimPhysConstraintSetup.md#angularxangle)
- [AngularYAngle](ue_ue.AnimPhysConstraintSetup.md#angularyangle)
- [AngularZAngle](ue_ue.AnimPhysConstraintSetup.md#angularzangle)
- [ConeAngle](ue_ue.AnimPhysConstraintSetup.md#coneangle)
- [LinearAxesMax](ue_ue.AnimPhysConstraintSetup.md#linearaxesmax)
- [LinearAxesMin](ue_ue.AnimPhysConstraintSetup.md#linearaxesmin)
- [LinearXLimitType](ue_ue.AnimPhysConstraintSetup.md#linearxlimittype)
- [LinearYLimitType](ue_ue.AnimPhysConstraintSetup.md#linearylimittype)
- [LinearZLimitType](ue_ue.AnimPhysConstraintSetup.md#linearzlimittype)
- [TwistAxis](ue_ue.AnimPhysConstraintSetup.md#twistaxis)
- [\_\_tid\_AnimPhysConstraintSetup\_\_](ue_ue.AnimPhysConstraintSetup.md#__tid_animphysconstraintsetup__)

### Methods

- [StaticClass](ue_ue.AnimPhysConstraintSetup.md#staticclass)
- [StaticStruct](ue_ue.AnimPhysConstraintSetup.md#staticstruct)

## Constructors

### constructor

• **new AnimPhysConstraintSetup**()

• **new AnimPhysConstraintSetup**(`LinearXLimitType`, `LinearYLimitType`, `LinearZLimitType`, `LinearAxesMin`, `LinearAxesMax`, `AngularConstraintType`, `TwistAxis`, `AngularTargetAxis`, `ConeAngle`, `AngularXAngle`, `AngularYAngle`, `AngularZAngle`, `AngularLimitsMin`, `AngularLimitsMax`, `AngularTarget`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `LinearXLimitType` | [`AnimPhysLinearConstraintType`](../enums/ue_ue.AnimPhysLinearConstraintType.md) |
| `LinearYLimitType` | [`AnimPhysLinearConstraintType`](../enums/ue_ue.AnimPhysLinearConstraintType.md) |
| `LinearZLimitType` | [`AnimPhysLinearConstraintType`](../enums/ue_ue.AnimPhysLinearConstraintType.md) |
| `LinearAxesMin` | [`Vector`](ue_ue_s.Vector.md) |
| `LinearAxesMax` | [`Vector`](ue_ue_s.Vector.md) |
| `AngularConstraintType` | [`AnimPhysAngularConstraintType`](../enums/ue_ue.AnimPhysAngularConstraintType.md) |
| `TwistAxis` | [`AnimPhysTwistAxis`](../enums/ue_ue.AnimPhysTwistAxis.md) |
| `AngularTargetAxis` | [`AnimPhysTwistAxis`](../enums/ue_ue.AnimPhysTwistAxis.md) |
| `ConeAngle` | `number` |
| `AngularXAngle` | `number` |
| `AngularYAngle` | `number` |
| `AngularZAngle` | `number` |
| `AngularLimitsMin` | [`Vector`](ue_ue_s.Vector.md) |
| `AngularLimitsMax` | [`Vector`](ue_ue_s.Vector.md) |
| `AngularTarget` | [`Vector`](ue_ue_s.Vector.md) |

## Properties

### AngularConstraintType

• **AngularConstraintType**: [`AnimPhysAngularConstraintType`](../enums/ue_ue.AnimPhysAngularConstraintType.md)

___

### AngularLimitsMax

• **AngularLimitsMax**: [`Vector`](ue_ue_s.Vector.md)

___

### AngularLimitsMin

• **AngularLimitsMin**: [`Vector`](ue_ue_s.Vector.md)

___

### AngularTarget

• **AngularTarget**: [`Vector`](ue_ue_s.Vector.md)

___

### AngularTargetAxis

• **AngularTargetAxis**: [`AnimPhysTwistAxis`](../enums/ue_ue.AnimPhysTwistAxis.md)

___

### AngularXAngle

• **AngularXAngle**: `number`

___

### AngularYAngle

• **AngularYAngle**: `number`

___

### AngularZAngle

• **AngularZAngle**: `number`

___

### ConeAngle

• **ConeAngle**: `number`

___

### LinearAxesMax

• **LinearAxesMax**: [`Vector`](ue_ue_s.Vector.md)

___

### LinearAxesMin

• **LinearAxesMin**: [`Vector`](ue_ue_s.Vector.md)

___

### LinearXLimitType

• **LinearXLimitType**: [`AnimPhysLinearConstraintType`](../enums/ue_ue.AnimPhysLinearConstraintType.md)

___

### LinearYLimitType

• **LinearYLimitType**: [`AnimPhysLinearConstraintType`](../enums/ue_ue.AnimPhysLinearConstraintType.md)

___

### LinearZLimitType

• **LinearZLimitType**: [`AnimPhysLinearConstraintType`](../enums/ue_ue.AnimPhysLinearConstraintType.md)

___

### TwistAxis

• **TwistAxis**: [`AnimPhysTwistAxis`](../enums/ue_ue.AnimPhysTwistAxis.md)

___

### \_\_tid\_AnimPhysConstraintSetup\_\_

• `Private` **\_\_tid\_AnimPhysConstraintSetup\_\_**: `boolean`

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
