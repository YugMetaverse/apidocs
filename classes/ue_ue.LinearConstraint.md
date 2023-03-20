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

#### Defined in

[ue/ue.d.ts:3596](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3596)

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

#### Defined in

[ue/ue.d.ts:3597](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3597)

## Properties

### ContactDistance

• **ContactDistance**: `number`

#### Inherited from

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[ContactDistance](ue_ue.ConstraintBaseParams.md#contactdistance)

#### Defined in

[ue/ue.d.ts:3584](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3584)

___

### Damping

• **Damping**: `number`

#### Inherited from

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[Damping](ue_ue.ConstraintBaseParams.md#damping)

#### Defined in

[ue/ue.d.ts:3582](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3582)

___

### Limit

• **Limit**: `number`

#### Defined in

[ue/ue.d.ts:3598](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3598)

___

### Restitution

• **Restitution**: `number`

#### Inherited from

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[Restitution](ue_ue.ConstraintBaseParams.md#restitution)

#### Defined in

[ue/ue.d.ts:3583](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3583)

___

### Stiffness

• **Stiffness**: `number`

#### Inherited from

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[Stiffness](ue_ue.ConstraintBaseParams.md#stiffness)

#### Defined in

[ue/ue.d.ts:3581](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3581)

___

### XMotion

• **XMotion**: [`ELinearConstraintMotion`](../enums/ue_ue.ELinearConstraintMotion.md)

#### Defined in

[ue/ue.d.ts:3599](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3599)

___

### YMotion

• **YMotion**: [`ELinearConstraintMotion`](../enums/ue_ue.ELinearConstraintMotion.md)

#### Defined in

[ue/ue.d.ts:3600](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3600)

___

### ZMotion

• **ZMotion**: [`ELinearConstraintMotion`](../enums/ue_ue.ELinearConstraintMotion.md)

#### Defined in

[ue/ue.d.ts:3601](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3601)

___

### \_\_tid\_LinearConstraint\_\_

• `Private` **\_\_tid\_LinearConstraint\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:3607](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3607)

___

### bSoftConstraint

• **bSoftConstraint**: `boolean`

#### Inherited from

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[bSoftConstraint](ue_ue.ConstraintBaseParams.md#bsoftconstraint)

#### Defined in

[ue/ue.d.ts:3585](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3585)

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

[ue/ue.d.ts:3605](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3605)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[StaticStruct](ue_ue.ConstraintBaseParams.md#staticstruct)

#### Defined in

[ue/ue.d.ts:3606](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3606)
