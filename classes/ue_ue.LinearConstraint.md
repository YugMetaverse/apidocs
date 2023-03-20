[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LinearConstraint

# Class: LinearConstraint

[ue/ue](../modules/ue_ue.md).LinearConstraint

## Hierarchy

- [`ConstraintBaseParams`](ue_ue.ConstraintBaseParams.md)

  ↳ **`LinearConstraint`**

## Table of contents

### Constructors

- [constructor](ue_ue.LinearConstraint.md#constructor)

### Properties

- [ContactDistance](ue_ue.LinearConstraint.md#contactdistance)
- [Damping](ue_ue.LinearConstraint.md#damping)
- [Limit](ue_ue.LinearConstraint.md#limit)
- [Restitution](ue_ue.LinearConstraint.md#restitution)
- [Stiffness](ue_ue.LinearConstraint.md#stiffness)
- [XMotion](ue_ue.LinearConstraint.md#xmotion)
- [YMotion](ue_ue.LinearConstraint.md#ymotion)
- [ZMotion](ue_ue.LinearConstraint.md#zmotion)
- [\_\_tid\_LinearConstraint\_\_](ue_ue.LinearConstraint.md#__tid_linearconstraint__)
- [bSoftConstraint](ue_ue.LinearConstraint.md#bsoftconstraint)

### Methods

- [StaticClass](ue_ue.LinearConstraint.md#staticclass)
- [StaticStruct](ue_ue.LinearConstraint.md#staticstruct)

## Constructors

### constructor

• **new LinearConstraint**()

#### Overrides

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[constructor](ue_ue.ConstraintBaseParams.md#constructor)

• **new LinearConstraint**(`Limit`, `XMotion`, `YMotion`, `ZMotion`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Limit` | `number` |
| `XMotion` | [`ELinearConstraintMotion`](../enums/ue_ue.ELinearConstraintMotion.md) |
| `YMotion` | [`ELinearConstraintMotion`](../enums/ue_ue.ELinearConstraintMotion.md) |
| `ZMotion` | [`ELinearConstraintMotion`](../enums/ue_ue.ELinearConstraintMotion.md) |

#### Overrides

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[constructor](ue_ue.ConstraintBaseParams.md#constructor)

## Properties

### ContactDistance

• **ContactDistance**: `number`

#### Inherited from

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[ContactDistance](ue_ue.ConstraintBaseParams.md#contactdistance)

___

### Damping

• **Damping**: `number`

#### Inherited from

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[Damping](ue_ue.ConstraintBaseParams.md#damping)

___

### Limit

• **Limit**: `number`

___

### Restitution

• **Restitution**: `number`

#### Inherited from

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[Restitution](ue_ue.ConstraintBaseParams.md#restitution)

___

### Stiffness

• **Stiffness**: `number`

#### Inherited from

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[Stiffness](ue_ue.ConstraintBaseParams.md#stiffness)

___

### XMotion

• **XMotion**: [`ELinearConstraintMotion`](../enums/ue_ue.ELinearConstraintMotion.md)

___

### YMotion

• **YMotion**: [`ELinearConstraintMotion`](../enums/ue_ue.ELinearConstraintMotion.md)

___

### ZMotion

• **ZMotion**: [`ELinearConstraintMotion`](../enums/ue_ue.ELinearConstraintMotion.md)

___

### \_\_tid\_LinearConstraint\_\_

• `Private` **\_\_tid\_LinearConstraint\_\_**: `boolean`

___

### bSoftConstraint

• **bSoftConstraint**: `boolean`

#### Inherited from

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[bSoftConstraint](ue_ue.ConstraintBaseParams.md#bsoftconstraint)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[StaticClass](ue_ue.ConstraintBaseParams.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[StaticStruct](ue_ue.ConstraintBaseParams.md#staticstruct)
