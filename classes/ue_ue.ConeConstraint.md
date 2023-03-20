[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ConeConstraint

# Class: ConeConstraint

[ue/ue](../modules/ue_ue.md).ConeConstraint

## Hierarchy

- [`ConstraintBaseParams`](ue_ue.ConstraintBaseParams.md)

  ↳ **`ConeConstraint`**

## Table of contents

### Constructors

- [constructor](ue_ue.ConeConstraint.md#constructor)

### Properties

- [ContactDistance](ue_ue.ConeConstraint.md#contactdistance)
- [Damping](ue_ue.ConeConstraint.md#damping)
- [Restitution](ue_ue.ConeConstraint.md#restitution)
- [Stiffness](ue_ue.ConeConstraint.md#stiffness)
- [Swing1LimitDegrees](ue_ue.ConeConstraint.md#swing1limitdegrees)
- [Swing1Motion](ue_ue.ConeConstraint.md#swing1motion)
- [Swing2LimitDegrees](ue_ue.ConeConstraint.md#swing2limitdegrees)
- [Swing2Motion](ue_ue.ConeConstraint.md#swing2motion)
- [\_\_tid\_ConeConstraint\_\_](ue_ue.ConeConstraint.md#__tid_coneconstraint__)
- [bSoftConstraint](ue_ue.ConeConstraint.md#bsoftconstraint)

### Methods

- [StaticClass](ue_ue.ConeConstraint.md#staticclass)
- [StaticStruct](ue_ue.ConeConstraint.md#staticstruct)

## Constructors

### constructor

• **new ConeConstraint**()

#### Overrides

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[constructor](ue_ue.ConstraintBaseParams.md#constructor)

#### Defined in

[ue/ue.d.ts:3612](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3612)

• **new ConeConstraint**(`Swing1LimitDegrees`, `Swing2LimitDegrees`, `Swing1Motion`, `Swing2Motion`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Swing1LimitDegrees` | `number` |
| `Swing2LimitDegrees` | `number` |
| `Swing1Motion` | [`EAngularConstraintMotion`](../enums/ue_ue.EAngularConstraintMotion.md) |
| `Swing2Motion` | [`EAngularConstraintMotion`](../enums/ue_ue.EAngularConstraintMotion.md) |

#### Overrides

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[constructor](ue_ue.ConstraintBaseParams.md#constructor)

#### Defined in

[ue/ue.d.ts:3613](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3613)

## Properties

### ContactDistance

• **ContactDistance**: `number`

#### Inherited from

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[ContactDistance](ue_ue.ConstraintBaseParams.md#contactdistance)

#### Defined in

[ue/ue.d.ts:3584](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3584)

___

### Damping

• **Damping**: `number`

#### Inherited from

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[Damping](ue_ue.ConstraintBaseParams.md#damping)

#### Defined in

[ue/ue.d.ts:3582](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3582)

___

### Restitution

• **Restitution**: `number`

#### Inherited from

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[Restitution](ue_ue.ConstraintBaseParams.md#restitution)

#### Defined in

[ue/ue.d.ts:3583](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3583)

___

### Stiffness

• **Stiffness**: `number`

#### Inherited from

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[Stiffness](ue_ue.ConstraintBaseParams.md#stiffness)

#### Defined in

[ue/ue.d.ts:3581](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3581)

___

### Swing1LimitDegrees

• **Swing1LimitDegrees**: `number`

#### Defined in

[ue/ue.d.ts:3614](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3614)

___

### Swing1Motion

• **Swing1Motion**: [`EAngularConstraintMotion`](../enums/ue_ue.EAngularConstraintMotion.md)

#### Defined in

[ue/ue.d.ts:3616](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3616)

___

### Swing2LimitDegrees

• **Swing2LimitDegrees**: `number`

#### Defined in

[ue/ue.d.ts:3615](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3615)

___

### Swing2Motion

• **Swing2Motion**: [`EAngularConstraintMotion`](../enums/ue_ue.EAngularConstraintMotion.md)

#### Defined in

[ue/ue.d.ts:3617](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3617)

___

### \_\_tid\_ConeConstraint\_\_

• `Private` **\_\_tid\_ConeConstraint\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:3623](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3623)

___

### bSoftConstraint

• **bSoftConstraint**: `boolean`

#### Inherited from

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[bSoftConstraint](ue_ue.ConstraintBaseParams.md#bsoftconstraint)

#### Defined in

[ue/ue.d.ts:3585](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3585)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[StaticClass](ue_ue.ConstraintBaseParams.md#staticclass)

#### Defined in

[ue/ue.d.ts:3621](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3621)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[StaticStruct](ue_ue.ConstraintBaseParams.md#staticstruct)

#### Defined in

[ue/ue.d.ts:3622](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3622)
