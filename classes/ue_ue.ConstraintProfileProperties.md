[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ConstraintProfileProperties

# Class: ConstraintProfileProperties

[ue/ue](../modules/ue_ue.md).ConstraintProfileProperties

## Table of contents

### Constructors

- [constructor](ue_ue.ConstraintProfileProperties.md#constructor)

### Properties

- [AngularBreakThreshold](ue_ue.ConstraintProfileProperties.md#angularbreakthreshold)
- [AngularDrive](ue_ue.ConstraintProfileProperties.md#angulardrive)
- [ConeLimit](ue_ue.ConstraintProfileProperties.md#conelimit)
- [LinearBreakThreshold](ue_ue.ConstraintProfileProperties.md#linearbreakthreshold)
- [LinearDrive](ue_ue.ConstraintProfileProperties.md#lineardrive)
- [LinearLimit](ue_ue.ConstraintProfileProperties.md#linearlimit)
- [ProjectionAngularTolerance](ue_ue.ConstraintProfileProperties.md#projectionangulartolerance)
- [ProjectionLinearTolerance](ue_ue.ConstraintProfileProperties.md#projectionlineartolerance)
- [TwistLimit](ue_ue.ConstraintProfileProperties.md#twistlimit)
- [\_\_tid\_ConstraintProfileProperties\_\_](ue_ue.ConstraintProfileProperties.md#__tid_constraintprofileproperties__)
- [bAngularBreakable](ue_ue.ConstraintProfileProperties.md#bangularbreakable)
- [bDisableCollision](ue_ue.ConstraintProfileProperties.md#bdisablecollision)
- [bEnableProjection](ue_ue.ConstraintProfileProperties.md#benableprojection)
- [bLinearBreakable](ue_ue.ConstraintProfileProperties.md#blinearbreakable)
- [bParentDominates](ue_ue.ConstraintProfileProperties.md#bparentdominates)

### Methods

- [StaticClass](ue_ue.ConstraintProfileProperties.md#staticclass)
- [StaticStruct](ue_ue.ConstraintProfileProperties.md#staticstruct)

## Constructors

### constructor

• **new ConstraintProfileProperties**()

• **new ConstraintProfileProperties**(`ProjectionLinearTolerance`, `ProjectionAngularTolerance`, `LinearBreakThreshold`, `AngularBreakThreshold`, `LinearLimit`, `ConeLimit`, `TwistLimit`, `LinearDrive`, `AngularDrive`, `bDisableCollision`, `bParentDominates`, `bEnableProjection`, `bAngularBreakable`, `bLinearBreakable`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ProjectionLinearTolerance` | `number` |
| `ProjectionAngularTolerance` | `number` |
| `LinearBreakThreshold` | `number` |
| `AngularBreakThreshold` | `number` |
| `LinearLimit` | [`LinearConstraint`](ue_ue.LinearConstraint.md) |
| `ConeLimit` | [`ConeConstraint`](ue_ue.ConeConstraint.md) |
| `TwistLimit` | [`TwistConstraint`](ue_ue.TwistConstraint.md) |
| `LinearDrive` | [`LinearDriveConstraint`](ue_ue.LinearDriveConstraint.md) |
| `AngularDrive` | [`AngularDriveConstraint`](ue_ue.AngularDriveConstraint.md) |
| `bDisableCollision` | `boolean` |
| `bParentDominates` | `boolean` |
| `bEnableProjection` | `boolean` |
| `bAngularBreakable` | `boolean` |
| `bLinearBreakable` | `boolean` |

## Properties

### AngularBreakThreshold

• **AngularBreakThreshold**: `number`

___

### AngularDrive

• **AngularDrive**: [`AngularDriveConstraint`](ue_ue.AngularDriveConstraint.md)

___

### ConeLimit

• **ConeLimit**: [`ConeConstraint`](ue_ue.ConeConstraint.md)

___

### LinearBreakThreshold

• **LinearBreakThreshold**: `number`

___

### LinearDrive

• **LinearDrive**: [`LinearDriveConstraint`](ue_ue.LinearDriveConstraint.md)

___

### LinearLimit

• **LinearLimit**: [`LinearConstraint`](ue_ue.LinearConstraint.md)

___

### ProjectionAngularTolerance

• **ProjectionAngularTolerance**: `number`

___

### ProjectionLinearTolerance

• **ProjectionLinearTolerance**: `number`

___

### TwistLimit

• **TwistLimit**: [`TwistConstraint`](ue_ue.TwistConstraint.md)

___

### \_\_tid\_ConstraintProfileProperties\_\_

• `Private` **\_\_tid\_ConstraintProfileProperties\_\_**: `boolean`

___

### bAngularBreakable

• **bAngularBreakable**: `boolean`

___

### bDisableCollision

• **bDisableCollision**: `boolean`

___

### bEnableProjection

• **bEnableProjection**: `boolean`

___

### bLinearBreakable

• **bLinearBreakable**: `boolean`

___

### bParentDominates

• **bParentDominates**: `boolean`

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
