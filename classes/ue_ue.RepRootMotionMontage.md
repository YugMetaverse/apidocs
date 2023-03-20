[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / RepRootMotionMontage

# Class: RepRootMotionMontage

[ue/ue](../modules/ue_ue.md).RepRootMotionMontage

## Table of contents

### Constructors

- [constructor](ue_ue.RepRootMotionMontage.md#constructor)

### Properties

- [Acceleration](ue_ue.RepRootMotionMontage.md#acceleration)
- [AnimMontage](ue_ue.RepRootMotionMontage.md#animmontage)
- [AuthoritativeRootMotion](ue_ue.RepRootMotionMontage.md#authoritativerootmotion)
- [LinearVelocity](ue_ue.RepRootMotionMontage.md#linearvelocity)
- [Location](ue_ue.RepRootMotionMontage.md#location)
- [MovementBase](ue_ue.RepRootMotionMontage.md#movementbase)
- [MovementBaseBoneName](ue_ue.RepRootMotionMontage.md#movementbasebonename)
- [Position](ue_ue.RepRootMotionMontage.md#position)
- [Rotation](ue_ue.RepRootMotionMontage.md#rotation)
- [\_\_tid\_RepRootMotionMontage\_\_](ue_ue.RepRootMotionMontage.md#__tid_reprootmotionmontage__)
- [bIsActive](ue_ue.RepRootMotionMontage.md#bisactive)
- [bRelativePosition](ue_ue.RepRootMotionMontage.md#brelativeposition)
- [bRelativeRotation](ue_ue.RepRootMotionMontage.md#brelativerotation)

### Methods

- [StaticClass](ue_ue.RepRootMotionMontage.md#staticclass)
- [StaticStruct](ue_ue.RepRootMotionMontage.md#staticstruct)

## Constructors

### constructor

• **new RepRootMotionMontage**()

• **new RepRootMotionMontage**(`bIsActive`, `AnimMontage`, `Position`, `Location`, `Rotation`, `MovementBase`, `MovementBaseBoneName`, `bRelativePosition`, `bRelativeRotation`, `AuthoritativeRootMotion`, `Acceleration`, `LinearVelocity`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIsActive` | `boolean` |
| `AnimMontage` | [`AnimMontage`](ue_ue.AnimMontage.md) |
| `Position` | `number` |
| `Location` | [`Vector_NetQuantize100`](ue_ue.Vector_NetQuantize100.md) |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `MovementBase` | [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md) |
| `MovementBaseBoneName` | `string` |
| `bRelativePosition` | `boolean` |
| `bRelativeRotation` | `boolean` |
| `AuthoritativeRootMotion` | [`RootMotionSourceGroup`](ue_ue.RootMotionSourceGroup.md) |
| `Acceleration` | [`Vector_NetQuantize10`](ue_ue.Vector_NetQuantize10.md) |
| `LinearVelocity` | [`Vector_NetQuantize10`](ue_ue.Vector_NetQuantize10.md) |

## Properties

### Acceleration

• **Acceleration**: [`Vector_NetQuantize10`](ue_ue.Vector_NetQuantize10.md)

___

### AnimMontage

• **AnimMontage**: [`AnimMontage`](ue_ue.AnimMontage.md)

___

### AuthoritativeRootMotion

• **AuthoritativeRootMotion**: [`RootMotionSourceGroup`](ue_ue.RootMotionSourceGroup.md)

___

### LinearVelocity

• **LinearVelocity**: [`Vector_NetQuantize10`](ue_ue.Vector_NetQuantize10.md)

___

### Location

• **Location**: [`Vector_NetQuantize100`](ue_ue.Vector_NetQuantize100.md)

___

### MovementBase

• **MovementBase**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

___

### MovementBaseBoneName

• **MovementBaseBoneName**: `string`

___

### Position

• **Position**: `number`

___

### Rotation

• **Rotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### \_\_tid\_RepRootMotionMontage\_\_

• `Private` **\_\_tid\_RepRootMotionMontage\_\_**: `boolean`

___

### bIsActive

• **bIsActive**: `boolean`

___

### bRelativePosition

• **bRelativePosition**: `boolean`

___

### bRelativeRotation

• **bRelativeRotation**: `boolean`

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
