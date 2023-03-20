[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ClothLODDataNv

# Class: ClothLODDataNv

[ue/ue](../modules/ue_ue.md).ClothLODDataNv

## Hierarchy

- [`ClothLODDataBase`](ue_ue.ClothLODDataBase.md)

  ↳ **`ClothLODDataNv`**

## Table of contents

### Constructors

- [constructor](ue_ue.ClothLODDataNv.md#constructor)

### Properties

- [CollisionData](ue_ue.ClothLODDataNv.md#collisiondata)
- [ParameterMasks](ue_ue.ClothLODDataNv.md#parametermasks)
- [PhysicalMeshData](ue_ue.ClothLODDataNv.md#physicalmeshdata)
- [\_\_tid\_ClothLODDataBase\_\_](ue_ue.ClothLODDataNv.md#__tid_clothloddatabase__)
- [\_\_tid\_ClothLODDataNv\_\_](ue_ue.ClothLODDataNv.md#__tid_clothloddatanv__)
- [\_\_tid\_Object\_\_](ue_ue.ClothLODDataNv.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ClothLODDataNv.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ClothLODDataNv.md#executeubergraph)
- [GetClass](ue_ue.ClothLODDataNv.md#getclass)
- [GetName](ue_ue.ClothLODDataNv.md#getname)
- [GetOuter](ue_ue.ClothLODDataNv.md#getouter)
- [GetWorld](ue_ue.ClothLODDataNv.md#getworld)
- [Find](ue_ue.ClothLODDataNv.md#find)
- [Load](ue_ue.ClothLODDataNv.md#load)
- [StaticClass](ue_ue.ClothLODDataNv.md#staticclass)

## Constructors

### constructor

• **new ClothLODDataNv**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ClothLODDataBase](ue_ue.ClothLODDataBase.md).[constructor](ue_ue.ClothLODDataBase.md#constructor)

## Properties

### CollisionData

• **CollisionData**: [`ClothCollisionData`](ue_ue.ClothCollisionData.md)

#### Inherited from

[ClothLODDataBase](ue_ue.ClothLODDataBase.md).[CollisionData](ue_ue.ClothLODDataBase.md#collisiondata)

___

### ParameterMasks

• **ParameterMasks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PointWeightMap`](ue_ue.PointWeightMap.md)\>

#### Inherited from

[ClothLODDataBase](ue_ue.ClothLODDataBase.md).[ParameterMasks](ue_ue.ClothLODDataBase.md#parametermasks)

___

### PhysicalMeshData

• **PhysicalMeshData**: [`ClothPhysicalMeshDataBase`](ue_ue.ClothPhysicalMeshDataBase.md)

#### Inherited from

[ClothLODDataBase](ue_ue.ClothLODDataBase.md).[PhysicalMeshData](ue_ue.ClothLODDataBase.md#physicalmeshdata)

___

### \_\_tid\_ClothLODDataBase\_\_

• **\_\_tid\_ClothLODDataBase\_\_**: `boolean`

#### Inherited from

[ClothLODDataBase](ue_ue.ClothLODDataBase.md).[__tid_ClothLODDataBase__](ue_ue.ClothLODDataBase.md#__tid_clothloddatabase__)

___

### \_\_tid\_ClothLODDataNv\_\_

• **\_\_tid\_ClothLODDataNv\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ClothLODDataBase](ue_ue.ClothLODDataBase.md).[__tid_Object__](ue_ue.ClothLODDataBase.md#__tid_object__)

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

[ClothLODDataBase](ue_ue.ClothLODDataBase.md).[CreateDefaultSubobject](ue_ue.ClothLODDataBase.md#createdefaultsubobject)

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

[ClothLODDataBase](ue_ue.ClothLODDataBase.md).[ExecuteUbergraph](ue_ue.ClothLODDataBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ClothLODDataBase](ue_ue.ClothLODDataBase.md).[GetClass](ue_ue.ClothLODDataBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ClothLODDataBase](ue_ue.ClothLODDataBase.md).[GetName](ue_ue.ClothLODDataBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ClothLODDataBase](ue_ue.ClothLODDataBase.md).[GetOuter](ue_ue.ClothLODDataBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ClothLODDataBase](ue_ue.ClothLODDataBase.md).[GetWorld](ue_ue.ClothLODDataBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ClothLODDataNv`](ue_ue.ClothLODDataNv.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ClothLODDataNv`](ue_ue.ClothLODDataNv.md)

#### Overrides

[ClothLODDataBase](ue_ue.ClothLODDataBase.md).[Find](ue_ue.ClothLODDataBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ClothLODDataNv`](ue_ue.ClothLODDataNv.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ClothLODDataNv`](ue_ue.ClothLODDataNv.md)

#### Overrides

[ClothLODDataBase](ue_ue.ClothLODDataBase.md).[Load](ue_ue.ClothLODDataBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ClothLODDataBase](ue_ue.ClothLODDataBase.md).[StaticClass](ue_ue.ClothLODDataBase.md#staticclass)
