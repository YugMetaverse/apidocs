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

#### Defined in

[ue/ue.d.ts:27811](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27811)

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

#### Defined in

[ue/ue.d.ts:27812](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27812)

## Properties

### AngularDrag

• **AngularDrag**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:27826](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27826)

___

### AngularInertiaScale

• **AngularInertiaScale**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:27828](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27828)

___

### AnimDriveDamperStiffness

• **AnimDriveDamperStiffness**: `number`

#### Defined in

[ue/ue.d.ts:27839](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27839)

___

### AnimDriveSpringStiffness

• **AnimDriveSpringStiffness**: `number`

#### Defined in

[ue/ue.d.ts:27838](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27838)

___

### BendConstraintConfig

• **BendConstraintConfig**: [`ClothConstraintSetup`](ue_ue.ClothConstraintSetup.md)

#### Defined in

[ue/ue.d.ts:27816](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27816)

___

### CentrifugalInertiaScale

• **CentrifugalInertiaScale**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:27829](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27829)

___

### CollisionThickness

• **CollisionThickness**: `number`

#### Defined in

[ue/ue.d.ts:27837](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27837)

___

### Damping

• **Damping**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:27821](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27821)

___

### Friction

• **Friction**: `number`

#### Defined in

[ue/ue.d.ts:27822](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27822)

___

### GravityOverride

• **GravityOverride**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:27833](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27833)

___

### GravityScale

• **GravityScale**: `number`

#### Defined in

[ue/ue.d.ts:27832](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27832)

___

### HorizontalConstraintConfig

• **HorizontalConstraintConfig**: [`ClothConstraintSetup`](ue_ue.ClothConstraintSetup.md)

#### Defined in

[ue/ue.d.ts:27815](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27815)

___

### LinearDrag

• **LinearDrag**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:27825](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27825)

___

### LinearInertiaScale

• **LinearInertiaScale**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:27827](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27827)

___

### SelfCollisionCullScale

• **SelfCollisionCullScale**: `number`

#### Defined in

[ue/ue.d.ts:27820](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27820)

___

### SelfCollisionRadius

• **SelfCollisionRadius**: `number`

#### Defined in

[ue/ue.d.ts:27818](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27818)

___

### SelfCollisionStiffness

• **SelfCollisionStiffness**: `number`

#### Defined in

[ue/ue.d.ts:27819](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27819)

___

### ShearConstraintConfig

• **ShearConstraintConfig**: [`ClothConstraintSetup`](ue_ue.ClothConstraintSetup.md)

#### Defined in

[ue/ue.d.ts:27817](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27817)

___

### SolverFrequency

• **SolverFrequency**: `number`

#### Defined in

[ue/ue.d.ts:27830](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27830)

___

### StiffnessFrequency

• **StiffnessFrequency**: `number`

#### Defined in

[ue/ue.d.ts:27831](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27831)

___

### TetherLimit

• **TetherLimit**: `number`

#### Defined in

[ue/ue.d.ts:27836](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27836)

___

### TetherStiffness

• **TetherStiffness**: `number`

#### Defined in

[ue/ue.d.ts:27835](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27835)

___

### VerticalConstraintConfig

• **VerticalConstraintConfig**: [`ClothConstraintSetup`](ue_ue.ClothConstraintSetup.md)

#### Defined in

[ue/ue.d.ts:27814](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27814)

___

### WindDragCoefficient

• **WindDragCoefficient**: `number`

#### Defined in

[ue/ue.d.ts:27823](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27823)

___

### WindLiftCoefficient

• **WindLiftCoefficient**: `number`

#### Defined in

[ue/ue.d.ts:27824](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27824)

___

### WindMethod

• **WindMethod**: [`EClothingWindMethod`](../enums/ue_ue.EClothingWindMethod.md)

#### Defined in

[ue/ue.d.ts:27813](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27813)

___

### \_\_tid\_ClothConfig\_\_

• `Private` **\_\_tid\_ClothConfig\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:27845](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27845)

___

### bUseGravityOverride

• **bUseGravityOverride**: `boolean`

#### Defined in

[ue/ue.d.ts:27834](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27834)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:27843](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27843)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:27844](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27844)
