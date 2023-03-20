[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NavCollision

# Class: NavCollision

[ue/ue](../modules/ue_ue.md).NavCollision

## Hierarchy

- [`NavCollisionBase`](ue_ue.NavCollisionBase.md)

  ↳ **`NavCollision`**

## Table of contents

### Constructors

- [constructor](ue_ue.NavCollision.md#constructor)

### Properties

- [AreaClass](ue_ue.NavCollision.md#areaclass)
- [BoxCollision](ue_ue.NavCollision.md#boxcollision)
- [CylinderCollision](ue_ue.NavCollision.md#cylindercollision)
- [\_\_tid\_NavCollisionBase\_\_](ue_ue.NavCollision.md#__tid_navcollisionbase__)
- [\_\_tid\_NavCollision\_\_](ue_ue.NavCollision.md#__tid_navcollision__)
- [\_\_tid\_Object\_\_](ue_ue.NavCollision.md#__tid_object__)
- [bCreateOnClient](ue_ue.NavCollision.md#bcreateonclient)
- [bGatherConvexGeometry](ue_ue.NavCollision.md#bgatherconvexgeometry)
- [bIsDynamicObstacle](ue_ue.NavCollision.md#bisdynamicobstacle)

### Methods

- [CreateDefaultSubobject](ue_ue.NavCollision.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.NavCollision.md#executeubergraph)
- [GetClass](ue_ue.NavCollision.md#getclass)
- [GetName](ue_ue.NavCollision.md#getname)
- [GetOuter](ue_ue.NavCollision.md#getouter)
- [GetWorld](ue_ue.NavCollision.md#getworld)
- [Find](ue_ue.NavCollision.md#find)
- [Load](ue_ue.NavCollision.md#load)
- [StaticClass](ue_ue.NavCollision.md#staticclass)

## Constructors

### constructor

• **new NavCollision**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[NavCollisionBase](ue_ue.NavCollisionBase.md).[constructor](ue_ue.NavCollisionBase.md#constructor)

## Properties

### AreaClass

• **AreaClass**: [`Class`](ue_ue.Class.md)

___

### BoxCollision

• **BoxCollision**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NavCollisionBox`](ue_ue.NavCollisionBox.md)\>

___

### CylinderCollision

• **CylinderCollision**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NavCollisionCylinder`](ue_ue.NavCollisionCylinder.md)\>

___

### \_\_tid\_NavCollisionBase\_\_

• **\_\_tid\_NavCollisionBase\_\_**: `boolean`

#### Inherited from

[NavCollisionBase](ue_ue.NavCollisionBase.md).[__tid_NavCollisionBase__](ue_ue.NavCollisionBase.md#__tid_navcollisionbase__)

___

### \_\_tid\_NavCollision\_\_

• **\_\_tid\_NavCollision\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[NavCollisionBase](ue_ue.NavCollisionBase.md).[__tid_Object__](ue_ue.NavCollisionBase.md#__tid_object__)

___

### bCreateOnClient

• **bCreateOnClient**: `boolean`

___

### bGatherConvexGeometry

• **bGatherConvexGeometry**: `boolean`

___

### bIsDynamicObstacle

• **bIsDynamicObstacle**: `boolean`

#### Inherited from

[NavCollisionBase](ue_ue.NavCollisionBase.md).[bIsDynamicObstacle](ue_ue.NavCollisionBase.md#bisdynamicobstacle)

## Methods

### CreateDefaultSubobject

▸ **CreateDefaultSubobject**(`p0`, `p1`, `p2`, `p3`, `p4`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `string` |
| `p1` | [`Class`](ue_ue.Class.md) |
| `p2` | [`Class`](ue_ue.Class.md) |
| `p3` | `boolean` |
| `p4` | `boolean` |

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[NavCollisionBase](ue_ue.NavCollisionBase.md).[CreateDefaultSubobject](ue_ue.NavCollisionBase.md#createdefaultsubobject)

___

### ExecuteUbergraph

▸ **ExecuteUbergraph**(`EntryPoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EntryPoint` | `number` |

#### Returns

`void`

#### Inherited from

[NavCollisionBase](ue_ue.NavCollisionBase.md).[ExecuteUbergraph](ue_ue.NavCollisionBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[NavCollisionBase](ue_ue.NavCollisionBase.md).[GetClass](ue_ue.NavCollisionBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[NavCollisionBase](ue_ue.NavCollisionBase.md).[GetName](ue_ue.NavCollisionBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[NavCollisionBase](ue_ue.NavCollisionBase.md).[GetOuter](ue_ue.NavCollisionBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[NavCollisionBase](ue_ue.NavCollisionBase.md).[GetWorld](ue_ue.NavCollisionBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`NavCollision`](ue_ue.NavCollision.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`NavCollision`](ue_ue.NavCollision.md)

#### Overrides

[NavCollisionBase](ue_ue.NavCollisionBase.md).[Find](ue_ue.NavCollisionBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`NavCollision`](ue_ue.NavCollision.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`NavCollision`](ue_ue.NavCollision.md)

#### Overrides

[NavCollisionBase](ue_ue.NavCollisionBase.md).[Load](ue_ue.NavCollisionBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[NavCollisionBase](ue_ue.NavCollisionBase.md).[StaticClass](ue_ue.NavCollisionBase.md#staticclass)
