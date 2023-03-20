[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ClothLODDataBase

# Class: ClothLODDataBase

[ue/ue](../modules/ue_ue.md).ClothLODDataBase

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ClothLODDataBase`**

  ↳↳ [`ClothLODDataNv`](ue_ue.ClothLODDataNv.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ClothLODDataBase.md#constructor)

### Properties

- [CollisionData](ue_ue.ClothLODDataBase.md#collisiondata)
- [ParameterMasks](ue_ue.ClothLODDataBase.md#parametermasks)
- [PhysicalMeshData](ue_ue.ClothLODDataBase.md#physicalmeshdata)
- [\_\_tid\_ClothLODDataBase\_\_](ue_ue.ClothLODDataBase.md#__tid_clothloddatabase__)
- [\_\_tid\_Object\_\_](ue_ue.ClothLODDataBase.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ClothLODDataBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ClothLODDataBase.md#executeubergraph)
- [GetClass](ue_ue.ClothLODDataBase.md#getclass)
- [GetName](ue_ue.ClothLODDataBase.md#getname)
- [GetOuter](ue_ue.ClothLODDataBase.md#getouter)
- [GetWorld](ue_ue.ClothLODDataBase.md#getworld)
- [Find](ue_ue.ClothLODDataBase.md#find)
- [Load](ue_ue.ClothLODDataBase.md#load)
- [StaticClass](ue_ue.ClothLODDataBase.md#staticclass)

## Constructors

### constructor

• **new ClothLODDataBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:27755](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27755)

## Properties

### CollisionData

• **CollisionData**: [`ClothCollisionData`](ue_ue.ClothCollisionData.md)

#### Defined in

[ue/ue.d.ts:27757](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27757)

___

### ParameterMasks

• **ParameterMasks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PointWeightMap`](ue_ue.PointWeightMap.md)\>

#### Defined in

[ue/ue.d.ts:27758](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27758)

___

### PhysicalMeshData

• **PhysicalMeshData**: [`ClothPhysicalMeshDataBase`](ue_ue.ClothPhysicalMeshDataBase.md)

#### Defined in

[ue/ue.d.ts:27756](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27756)

___

### \_\_tid\_ClothLODDataBase\_\_

• **\_\_tid\_ClothLODDataBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:27763](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27763)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ClothLODDataBase`](ue_ue.ClothLODDataBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ClothLODDataBase`](ue_ue.ClothLODDataBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:27760](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27760)

___

### Load

▸ `Static` **Load**(`InName`): [`ClothLODDataBase`](ue_ue.ClothLODDataBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ClothLODDataBase`](ue_ue.ClothLODDataBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:27761](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27761)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:27759](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27759)
