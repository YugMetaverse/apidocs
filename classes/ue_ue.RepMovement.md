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

#### Defined in

[ue/ue.d.ts:223](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L223)

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

#### Defined in

[ue/ue.d.ts:224](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L224)

## Properties

### AngularVelocity

• **AngularVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:226](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L226)

___

### LinearVelocity

• **LinearVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:225](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L225)

___

### Location

• **Location**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:227](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L227)

___

### LocationQuantizationLevel

• **LocationQuantizationLevel**: [`EVectorQuantization`](../enums/ue_ue.EVectorQuantization.md)

#### Defined in

[ue/ue.d.ts:231](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L231)

___

### Rotation

• **Rotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:228](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L228)

___

### RotationQuantizationLevel

• **RotationQuantizationLevel**: [`ERotatorQuantization`](../enums/ue_ue.ERotatorQuantization.md)

#### Defined in

[ue/ue.d.ts:233](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L233)

___

### VelocityQuantizationLevel

• **VelocityQuantizationLevel**: [`EVectorQuantization`](../enums/ue_ue.EVectorQuantization.md)

#### Defined in

[ue/ue.d.ts:232](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L232)

___

### \_\_tid\_RepMovement\_\_

• `Private` **\_\_tid\_RepMovement\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:239](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L239)

___

### bRepPhysics

• **bRepPhysics**: `boolean`

#### Defined in

[ue/ue.d.ts:230](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L230)

___

### bSimulatedPhysicSleep

• **bSimulatedPhysicSleep**: `boolean`

#### Defined in

[ue/ue.d.ts:229](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L229)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:237](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L237)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:238](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L238)
