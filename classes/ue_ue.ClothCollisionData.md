[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ClothCollisionData

# Class: ClothCollisionData

[ue/ue](../modules/ue_ue.md).ClothCollisionData

## Table of contents

### Constructors

- [constructor](ue_ue.ClothCollisionData.md#constructor)

### Properties

- [Boxes](ue_ue.ClothCollisionData.md#boxes)
- [Convexes](ue_ue.ClothCollisionData.md#convexes)
- [SphereConnections](ue_ue.ClothCollisionData.md#sphereconnections)
- [Spheres](ue_ue.ClothCollisionData.md#spheres)
- [\_\_tid\_ClothCollisionData\_\_](ue_ue.ClothCollisionData.md#__tid_clothcollisiondata__)

### Methods

- [StaticClass](ue_ue.ClothCollisionData.md#staticclass)
- [StaticStruct](ue_ue.ClothCollisionData.md#staticstruct)

## Constructors

### constructor

• **new ClothCollisionData**()

• **new ClothCollisionData**(`Spheres`, `SphereConnections`, `Convexes`, `Boxes`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Spheres` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClothCollisionPrim_Sphere`](ue_ue.ClothCollisionPrim_Sphere.md)\> |
| `SphereConnections` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClothCollisionPrim_SphereConnection`](ue_ue.ClothCollisionPrim_SphereConnection.md)\> |
| `Convexes` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClothCollisionPrim_Convex`](ue_ue.ClothCollisionPrim_Convex.md)\> |
| `Boxes` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClothCollisionPrim_Box`](ue_ue.ClothCollisionPrim_Box.md)\> |

## Properties

### Boxes

• **Boxes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClothCollisionPrim_Box`](ue_ue.ClothCollisionPrim_Box.md)\>

___

### Convexes

• **Convexes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClothCollisionPrim_Convex`](ue_ue.ClothCollisionPrim_Convex.md)\>

___

### SphereConnections

• **SphereConnections**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClothCollisionPrim_SphereConnection`](ue_ue.ClothCollisionPrim_SphereConnection.md)\>

___

### Spheres

• **Spheres**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClothCollisionPrim_Sphere`](ue_ue.ClothCollisionPrim_Sphere.md)\>

___

### \_\_tid\_ClothCollisionData\_\_

• `Private` **\_\_tid\_ClothCollisionData\_\_**: `boolean`

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
