[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AngularDriveConstraint

# Class: AngularDriveConstraint

[ue/ue](../modules/ue_ue.md).AngularDriveConstraint

## Table of contents

### Constructors

- [constructor](ue_ue.AngularDriveConstraint.md#constructor)

### Properties

- [AngularDriveMode](ue_ue.AngularDriveConstraint.md#angulardrivemode)
- [AngularVelocityTarget](ue_ue.AngularDriveConstraint.md#angularvelocitytarget)
- [OrientationTarget](ue_ue.AngularDriveConstraint.md#orientationtarget)
- [SlerpDrive](ue_ue.AngularDriveConstraint.md#slerpdrive)
- [SwingDrive](ue_ue.AngularDriveConstraint.md#swingdrive)
- [TwistDrive](ue_ue.AngularDriveConstraint.md#twistdrive)
- [\_\_tid\_AngularDriveConstraint\_\_](ue_ue.AngularDriveConstraint.md#__tid_angulardriveconstraint__)

### Methods

- [StaticClass](ue_ue.AngularDriveConstraint.md#staticclass)
- [StaticStruct](ue_ue.AngularDriveConstraint.md#staticstruct)

## Constructors

### constructor

• **new AngularDriveConstraint**()

• **new AngularDriveConstraint**(`TwistDrive`, `SwingDrive`, `SlerpDrive`, `OrientationTarget`, `AngularVelocityTarget`, `AngularDriveMode`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TwistDrive` | [`ConstraintDrive`](ue_ue.ConstraintDrive.md) |
| `SwingDrive` | [`ConstraintDrive`](ue_ue.ConstraintDrive.md) |
| `SlerpDrive` | [`ConstraintDrive`](ue_ue.ConstraintDrive.md) |
| `OrientationTarget` | [`Rotator`](ue_ue_s.Rotator.md) |
| `AngularVelocityTarget` | [`Vector`](ue_ue_s.Vector.md) |
| `AngularDriveMode` | [`EAngularDriveMode`](../enums/ue_ue.EAngularDriveMode.md) |

## Properties

### AngularDriveMode

• **AngularDriveMode**: [`EAngularDriveMode`](../enums/ue_ue.EAngularDriveMode.md)

___

### AngularVelocityTarget

• **AngularVelocityTarget**: [`Vector`](ue_ue_s.Vector.md)

___

### OrientationTarget

• **OrientationTarget**: [`Rotator`](ue_ue_s.Rotator.md)

___

### SlerpDrive

• **SlerpDrive**: [`ConstraintDrive`](ue_ue.ConstraintDrive.md)

___

### SwingDrive

• **SwingDrive**: [`ConstraintDrive`](ue_ue.ConstraintDrive.md)

___

### TwistDrive

• **TwistDrive**: [`ConstraintDrive`](ue_ue.ConstraintDrive.md)

___

### \_\_tid\_AngularDriveConstraint\_\_

• `Private` **\_\_tid\_AngularDriveConstraint\_\_**: `boolean`

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
