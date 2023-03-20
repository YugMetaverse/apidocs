[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BasedMovementInfo

# Class: BasedMovementInfo

[ue/ue](../modules/ue_ue.md).BasedMovementInfo

## Table of contents

### Constructors

- [constructor](ue_ue.BasedMovementInfo.md#constructor)

### Properties

- [BoneName](ue_ue.BasedMovementInfo.md#bonename)
- [Location](ue_ue.BasedMovementInfo.md#location)
- [MovementBase](ue_ue.BasedMovementInfo.md#movementbase)
- [Rotation](ue_ue.BasedMovementInfo.md#rotation)
- [\_\_tid\_BasedMovementInfo\_\_](ue_ue.BasedMovementInfo.md#__tid_basedmovementinfo__)
- [bRelativeRotation](ue_ue.BasedMovementInfo.md#brelativerotation)
- [bServerHasBaseComponent](ue_ue.BasedMovementInfo.md#bserverhasbasecomponent)
- [bServerHasVelocity](ue_ue.BasedMovementInfo.md#bserverhasvelocity)

### Methods

- [StaticClass](ue_ue.BasedMovementInfo.md#staticclass)
- [StaticStruct](ue_ue.BasedMovementInfo.md#staticstruct)

## Constructors

### constructor

• **new BasedMovementInfo**()

• **new BasedMovementInfo**(`MovementBase`, `BoneName`, `Location`, `Rotation`, `bServerHasBaseComponent`, `bRelativeRotation`, `bServerHasVelocity`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MovementBase` | [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md) |
| `BoneName` | `string` |
| `Location` | [`Vector_NetQuantize100`](ue_ue.Vector_NetQuantize100.md) |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bServerHasBaseComponent` | `boolean` |
| `bRelativeRotation` | `boolean` |
| `bServerHasVelocity` | `boolean` |

## Properties

### BoneName

• **BoneName**: `string`

___

### Location

• **Location**: [`Vector_NetQuantize100`](ue_ue.Vector_NetQuantize100.md)

___

### MovementBase

• **MovementBase**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

___

### Rotation

• **Rotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### \_\_tid\_BasedMovementInfo\_\_

• `Private` **\_\_tid\_BasedMovementInfo\_\_**: `boolean`

___

### bRelativeRotation

• **bRelativeRotation**: `boolean`

___

### bServerHasBaseComponent

• **bServerHasBaseComponent**: `boolean`

___

### bServerHasVelocity

• **bServerHasVelocity**: `boolean`

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
