[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ClothConfig

# Class: ClothConfig

[ue/ue](../modules/ue_ue.md).ClothConfig

## Table of contents

### Constructors

- [constructor](ue_ue.ClothConfig.md#constructor)

### Properties

- [AngularDrag](ue_ue.ClothConfig.md#angulardrag)
- [AngularInertiaScale](ue_ue.ClothConfig.md#angularinertiascale)
- [AnimDriveDamperStiffness](ue_ue.ClothConfig.md#animdrivedamperstiffness)
- [AnimDriveSpringStiffness](ue_ue.ClothConfig.md#animdrivespringstiffness)
- [BendConstraintConfig](ue_ue.ClothConfig.md#bendconstraintconfig)
- [CentrifugalInertiaScale](ue_ue.ClothConfig.md#centrifugalinertiascale)
- [CollisionThickness](ue_ue.ClothConfig.md#collisionthickness)
- [Damping](ue_ue.ClothConfig.md#damping)
- [Friction](ue_ue.ClothConfig.md#friction)
- [GravityOverride](ue_ue.ClothConfig.md#gravityoverride)
- [GravityScale](ue_ue.ClothConfig.md#gravityscale)
- [HorizontalConstraintConfig](ue_ue.ClothConfig.md#horizontalconstraintconfig)
- [LinearDrag](ue_ue.ClothConfig.md#lineardrag)
- [LinearInertiaScale](ue_ue.ClothConfig.md#linearinertiascale)
- [SelfCollisionCullScale](ue_ue.ClothConfig.md#selfcollisioncullscale)
- [SelfCollisionRadius](ue_ue.ClothConfig.md#selfcollisionradius)
- [SelfCollisionStiffness](ue_ue.ClothConfig.md#selfcollisionstiffness)
- [ShearConstraintConfig](ue_ue.ClothConfig.md#shearconstraintconfig)
- [SolverFrequency](ue_ue.ClothConfig.md#solverfrequency)
- [StiffnessFrequency](ue_ue.ClothConfig.md#stiffnessfrequency)
- [TetherLimit](ue_ue.ClothConfig.md#tetherlimit)
- [TetherStiffness](ue_ue.ClothConfig.md#tetherstiffness)
- [VerticalConstraintConfig](ue_ue.ClothConfig.md#verticalconstraintconfig)
- [WindDragCoefficient](ue_ue.ClothConfig.md#winddragcoefficient)
- [WindLiftCoefficient](ue_ue.ClothConfig.md#windliftcoefficient)
- [WindMethod](ue_ue.ClothConfig.md#windmethod)
- [\_\_tid\_ClothConfig\_\_](ue_ue.ClothConfig.md#__tid_clothconfig__)
- [bUseGravityOverride](ue_ue.ClothConfig.md#busegravityoverride)

### Methods

- [StaticClass](ue_ue.ClothConfig.md#staticclass)
- [StaticStruct](ue_ue.ClothConfig.md#staticstruct)

## Constructors

### constructor

• **new ClothConfig**()

• **new ClothConfig**(`WindMethod`, `VerticalConstraintConfig`, `HorizontalConstraintConfig`, `BendConstraintConfig`, `ShearConstraintConfig`, `SelfCollisionRadius`, `SelfCollisionStiffness`, `SelfCollisionCullScale`, `Damping`, `Friction`, `WindDragCoefficient`, `WindLiftCoefficient`, `LinearDrag`, `AngularDrag`, `LinearInertiaScale`, `AngularInertiaScale`, `CentrifugalInertiaScale`, `SolverFrequency`, `StiffnessFrequency`, `GravityScale`, `GravityOverride`, `bUseGravityOverride`, `TetherStiffness`, `TetherLimit`, `CollisionThickness`, `AnimDriveSpringStiffness`, `AnimDriveDamperStiffness`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WindMethod` | [`EClothingWindMethod`](../enums/ue_ue.EClothingWindMethod.md) |
| `VerticalConstraintConfig` | [`ClothConstraintSetup`](ue_ue.ClothConstraintSetup.md) |
| `HorizontalConstraintConfig` | [`ClothConstraintSetup`](ue_ue.ClothConstraintSetup.md) |
| `BendConstraintConfig` | [`ClothConstraintSetup`](ue_ue.ClothConstraintSetup.md) |
| `ShearConstraintConfig` | [`ClothConstraintSetup`](ue_ue.ClothConstraintSetup.md) |
| `SelfCollisionRadius` | `number` |
| `SelfCollisionStiffness` | `number` |
| `SelfCollisionCullScale` | `number` |
| `Damping` | [`Vector`](ue_ue_s.Vector.md) |
| `Friction` | `number` |
| `WindDragCoefficient` | `number` |
| `WindLiftCoefficient` | `number` |
| `LinearDrag` | [`Vector`](ue_ue_s.Vector.md) |
| `AngularDrag` | [`Vector`](ue_ue_s.Vector.md) |
| `LinearInertiaScale` | [`Vector`](ue_ue_s.Vector.md) |
| `AngularInertiaScale` | [`Vector`](ue_ue_s.Vector.md) |
| `CentrifugalInertiaScale` | [`Vector`](ue_ue_s.Vector.md) |
| `SolverFrequency` | `number` |
| `StiffnessFrequency` | `number` |
| `GravityScale` | `number` |
| `GravityOverride` | [`Vector`](ue_ue_s.Vector.md) |
| `bUseGravityOverride` | `boolean` |
| `TetherStiffness` | `number` |
| `TetherLimit` | `number` |
| `CollisionThickness` | `number` |
| `AnimDriveSpringStiffness` | `number` |
| `AnimDriveDamperStiffness` | `number` |

## Properties

### AngularDrag

• **AngularDrag**: [`Vector`](ue_ue_s.Vector.md)

___

### AngularInertiaScale

• **AngularInertiaScale**: [`Vector`](ue_ue_s.Vector.md)

___

### AnimDriveDamperStiffness

• **AnimDriveDamperStiffness**: `number`

___

### AnimDriveSpringStiffness

• **AnimDriveSpringStiffness**: `number`

___

### BendConstraintConfig

• **BendConstraintConfig**: [`ClothConstraintSetup`](ue_ue.ClothConstraintSetup.md)

___

### CentrifugalInertiaScale

• **CentrifugalInertiaScale**: [`Vector`](ue_ue_s.Vector.md)

___

### CollisionThickness

• **CollisionThickness**: `number`

___

### Damping

• **Damping**: [`Vector`](ue_ue_s.Vector.md)

___

### Friction

• **Friction**: `number`

___

### GravityOverride

• **GravityOverride**: [`Vector`](ue_ue_s.Vector.md)

___

### GravityScale

• **GravityScale**: `number`

___

### HorizontalConstraintConfig

• **HorizontalConstraintConfig**: [`ClothConstraintSetup`](ue_ue.ClothConstraintSetup.md)

___

### LinearDrag

• **LinearDrag**: [`Vector`](ue_ue_s.Vector.md)

___

### LinearInertiaScale

• **LinearInertiaScale**: [`Vector`](ue_ue_s.Vector.md)

___

### SelfCollisionCullScale

• **SelfCollisionCullScale**: `number`

___

### SelfCollisionRadius

• **SelfCollisionRadius**: `number`

___

### SelfCollisionStiffness

• **SelfCollisionStiffness**: `number`

___

### ShearConstraintConfig

• **ShearConstraintConfig**: [`ClothConstraintSetup`](ue_ue.ClothConstraintSetup.md)

___

### SolverFrequency

• **SolverFrequency**: `number`

___

### StiffnessFrequency

• **StiffnessFrequency**: `number`

___

### TetherLimit

• **TetherLimit**: `number`

___

### TetherStiffness

• **TetherStiffness**: `number`

___

### VerticalConstraintConfig

• **VerticalConstraintConfig**: [`ClothConstraintSetup`](ue_ue.ClothConstraintSetup.md)

___

### WindDragCoefficient

• **WindDragCoefficient**: `number`

___

### WindLiftCoefficient

• **WindLiftCoefficient**: `number`

___

### WindMethod

• **WindMethod**: [`EClothingWindMethod`](../enums/ue_ue.EClothingWindMethod.md)

___

### \_\_tid\_ClothConfig\_\_

• `Private` **\_\_tid\_ClothConfig\_\_**: `boolean`

___

### bUseGravityOverride

• **bUseGravityOverride**: `boolean`

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
