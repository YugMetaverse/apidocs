[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TwistConstraint

# Class: TwistConstraint

[ue/ue](../modules/ue_ue.md).TwistConstraint

## Hierarchy

- [`ConstraintBaseParams`](ue_ue.ConstraintBaseParams.md)

  ↳ **`TwistConstraint`**

## Table of contents

### Constructors

- [constructor](ue_ue.TwistConstraint.md#constructor)

### Properties

- [ContactDistance](ue_ue.TwistConstraint.md#contactdistance)
- [Damping](ue_ue.TwistConstraint.md#damping)
- [Restitution](ue_ue.TwistConstraint.md#restitution)
- [Stiffness](ue_ue.TwistConstraint.md#stiffness)
- [TwistLimitDegrees](ue_ue.TwistConstraint.md#twistlimitdegrees)
- [TwistMotion](ue_ue.TwistConstraint.md#twistmotion)
- [\_\_tid\_TwistConstraint\_\_](ue_ue.TwistConstraint.md#__tid_twistconstraint__)
- [bSoftConstraint](ue_ue.TwistConstraint.md#bsoftconstraint)

### Methods

- [StaticClass](ue_ue.TwistConstraint.md#staticclass)
- [StaticStruct](ue_ue.TwistConstraint.md#staticstruct)

## Constructors

### constructor

• **new TwistConstraint**()

#### Overrides

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[constructor](ue_ue.ConstraintBaseParams.md#constructor)

#### Defined in

[ue/ue.d.ts:3627](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3627)

• **new TwistConstraint**(`TwistLimitDegrees`, `TwistMotion`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TwistLimitDegrees` | `number` |
| `TwistMotion` | [`EAngularConstraintMotion`](../enums/ue_ue.EAngularConstraintMotion.md) |

#### Overrides

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[constructor](ue_ue.ConstraintBaseParams.md#constructor)

#### Defined in

[ue/ue.d.ts:3628](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3628)

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

### TwistLimitDegrees

• **TwistLimitDegrees**: `number`

#### Defined in

[ue/ue.d.ts:3629](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3629)

___

### TwistMotion

• **TwistMotion**: [`EAngularConstraintMotion`](../enums/ue_ue.EAngularConstraintMotion.md)

#### Defined in

[ue/ue.d.ts:3630](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3630)

___

### \_\_tid\_TwistConstraint\_\_

• `Private` **\_\_tid\_TwistConstraint\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:3636](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3636)

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

[ue/ue.d.ts:3634](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3634)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[ConstraintBaseParams](ue_ue.ConstraintBaseParams.md).[StaticStruct](ue_ue.ConstraintBaseParams.md#staticstruct)

#### Defined in

[ue/ue.d.ts:3635](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3635)
