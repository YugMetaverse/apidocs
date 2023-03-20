[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ConstraintBaseParams

# Class: ConstraintBaseParams

[ue/ue](../modules/ue_ue.md).ConstraintBaseParams

## Hierarchy

- **`ConstraintBaseParams`**

  ↳ [`LinearConstraint`](ue_ue.LinearConstraint.md)

  ↳ [`ConeConstraint`](ue_ue.ConeConstraint.md)

  ↳ [`TwistConstraint`](ue_ue.TwistConstraint.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ConstraintBaseParams.md#constructor)

### Properties

- [ContactDistance](ue_ue.ConstraintBaseParams.md#contactdistance)
- [Damping](ue_ue.ConstraintBaseParams.md#damping)
- [Restitution](ue_ue.ConstraintBaseParams.md#restitution)
- [Stiffness](ue_ue.ConstraintBaseParams.md#stiffness)
- [\_\_tid\_ConstraintBaseParams\_\_](ue_ue.ConstraintBaseParams.md#__tid_constraintbaseparams__)
- [bSoftConstraint](ue_ue.ConstraintBaseParams.md#bsoftconstraint)

### Methods

- [StaticClass](ue_ue.ConstraintBaseParams.md#staticclass)
- [StaticStruct](ue_ue.ConstraintBaseParams.md#staticstruct)

## Constructors

### constructor

• **new ConstraintBaseParams**()

• **new ConstraintBaseParams**(`Stiffness`, `Damping`, `Restitution`, `ContactDistance`, `bSoftConstraint`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Stiffness` | `number` |
| `Damping` | `number` |
| `Restitution` | `number` |
| `ContactDistance` | `number` |
| `bSoftConstraint` | `boolean` |

## Properties

### ContactDistance

• **ContactDistance**: `number`

___

### Damping

• **Damping**: `number`

___

### Restitution

• **Restitution**: `number`

___

### Stiffness

• **Stiffness**: `number`

___

### \_\_tid\_ConstraintBaseParams\_\_

• `Private` **\_\_tid\_ConstraintBaseParams\_\_**: `boolean`

___

### bSoftConstraint

• **bSoftConstraint**: `boolean`

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
