[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / RepMovement

# Class: RepMovement

[ue/ue](../modules/ue_ue.md).RepMovement

## Table of contents

### Constructors

- [constructor](ue_ue.RepMovement.md#constructor)

### Properties

- [AngularVelocity](ue_ue.RepMovement.md#angularvelocity)
- [LinearVelocity](ue_ue.RepMovement.md#linearvelocity)
- [Location](ue_ue.RepMovement.md#location)
- [LocationQuantizationLevel](ue_ue.RepMovement.md#locationquantizationlevel)
- [Rotation](ue_ue.RepMovement.md#rotation)
- [RotationQuantizationLevel](ue_ue.RepMovement.md#rotationquantizationlevel)
- [VelocityQuantizationLevel](ue_ue.RepMovement.md#velocityquantizationlevel)
- [\_\_tid\_RepMovement\_\_](ue_ue.RepMovement.md#__tid_repmovement__)
- [bRepPhysics](ue_ue.RepMovement.md#brepphysics)
- [bSimulatedPhysicSleep](ue_ue.RepMovement.md#bsimulatedphysicsleep)

### Methods

- [StaticClass](ue_ue.RepMovement.md#staticclass)
- [StaticStruct](ue_ue.RepMovement.md#staticstruct)

## Constructors

### constructor

• **new RepMovement**()

• **new RepMovement**(`LinearVelocity`, `AngularVelocity`, `Location`, `Rotation`, `bSimulatedPhysicSleep`, `bRepPhysics`, `LocationQuantizationLevel`, `VelocityQuantizationLevel`, `RotationQuantizationLevel`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `LinearVelocity` | [`Vector`](ue_ue_s.Vector.md) |
| `AngularVelocity` | [`Vector`](ue_ue_s.Vector.md) |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bSimulatedPhysicSleep` | `boolean` |
| `bRepPhysics` | `boolean` |
| `LocationQuantizationLevel` | [`EVectorQuantization`](../enums/ue_ue.EVectorQuantization.md) |
| `VelocityQuantizationLevel` | [`EVectorQuantization`](../enums/ue_ue.EVectorQuantization.md) |
| `RotationQuantizationLevel` | [`ERotatorQuantization`](../enums/ue_ue.ERotatorQuantization.md) |

## Properties

### AngularVelocity

• **AngularVelocity**: [`Vector`](ue_ue_s.Vector.md)

___

### LinearVelocity

• **LinearVelocity**: [`Vector`](ue_ue_s.Vector.md)

___

### Location

• **Location**: [`Vector`](ue_ue_s.Vector.md)

___

### LocationQuantizationLevel

• **LocationQuantizationLevel**: [`EVectorQuantization`](../enums/ue_ue.EVectorQuantization.md)

___

### Rotation

• **Rotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### RotationQuantizationLevel

• **RotationQuantizationLevel**: [`ERotatorQuantization`](../enums/ue_ue.ERotatorQuantization.md)

___

### VelocityQuantizationLevel

• **VelocityQuantizationLevel**: [`EVectorQuantization`](../enums/ue_ue.EVectorQuantization.md)

___

### \_\_tid\_RepMovement\_\_

• `Private` **\_\_tid\_RepMovement\_\_**: `boolean`

___

### bRepPhysics

• **bRepPhysics**: `boolean`

___

### bSimulatedPhysicSleep

• **bSimulatedPhysicSleep**: `boolean`

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
