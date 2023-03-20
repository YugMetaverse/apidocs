[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ClothPhysicalMeshDataBase

# Class: ClothPhysicalMeshDataBase

[ue/ue](../modules/ue_ue.md).ClothPhysicalMeshDataBase

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ClothPhysicalMeshDataBase`**

  ↳↳ [`ClothPhysicalMeshDataNv`](ue_ue.ClothPhysicalMeshDataNv.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ClothPhysicalMeshDataBase.md#constructor)

### Properties

- [BoneData](ue_ue.ClothPhysicalMeshDataBase.md#bonedata)
- [Indices](ue_ue.ClothPhysicalMeshDataBase.md#indices)
- [InverseMasses](ue_ue.ClothPhysicalMeshDataBase.md#inversemasses)
- [MaxBoneWeights](ue_ue.ClothPhysicalMeshDataBase.md#maxboneweights)
- [Normals](ue_ue.ClothPhysicalMeshDataBase.md#normals)
- [NumFixedVerts](ue_ue.ClothPhysicalMeshDataBase.md#numfixedverts)
- [SelfCollisionIndices](ue_ue.ClothPhysicalMeshDataBase.md#selfcollisionindices)
- [VertexColors](ue_ue.ClothPhysicalMeshDataBase.md#vertexcolors)
- [Vertices](ue_ue.ClothPhysicalMeshDataBase.md#vertices)
- [\_\_tid\_ClothPhysicalMeshDataBase\_\_](ue_ue.ClothPhysicalMeshDataBase.md#__tid_clothphysicalmeshdatabase__)
- [\_\_tid\_Object\_\_](ue_ue.ClothPhysicalMeshDataBase.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ClothPhysicalMeshDataBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ClothPhysicalMeshDataBase.md#executeubergraph)
- [GetClass](ue_ue.ClothPhysicalMeshDataBase.md#getclass)
- [GetName](ue_ue.ClothPhysicalMeshDataBase.md#getname)
- [GetOuter](ue_ue.ClothPhysicalMeshDataBase.md#getouter)
- [GetWorld](ue_ue.ClothPhysicalMeshDataBase.md#getworld)
- [Find](ue_ue.ClothPhysicalMeshDataBase.md#find)
- [Load](ue_ue.ClothPhysicalMeshDataBase.md#load)
- [StaticClass](ue_ue.ClothPhysicalMeshDataBase.md#staticclass)

## Constructors

### constructor

• **new ClothPhysicalMeshDataBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:27654](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27654)

## Properties

### BoneData

• **BoneData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClothVertBoneData`](ue_ue.ClothVertBoneData.md)\>

#### Defined in

[ue/ue.d.ts:27660](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27660)

___

### Indices

• **Indices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:27658](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27658)

___

### InverseMasses

• **InverseMasses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:27659](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27659)

___

### MaxBoneWeights

• **MaxBoneWeights**: `number`

#### Defined in

[ue/ue.d.ts:27662](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27662)

___

### Normals

• **Normals**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Defined in

[ue/ue.d.ts:27656](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27656)

___

### NumFixedVerts

• **NumFixedVerts**: `number`

#### Defined in

[ue/ue.d.ts:27661](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27661)

___

### SelfCollisionIndices

• **SelfCollisionIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:27663](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27663)

___

### VertexColors

• **VertexColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Color`](ue_ue_s.Color.md)\>

#### Defined in

[ue/ue.d.ts:27657](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27657)

___

### Vertices

• **Vertices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Defined in

[ue/ue.d.ts:27655](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27655)

___

### \_\_tid\_ClothPhysicalMeshDataBase\_\_

• **\_\_tid\_ClothPhysicalMeshDataBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:27668](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27668)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ClothPhysicalMeshDataBase`](ue_ue.ClothPhysicalMeshDataBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ClothPhysicalMeshDataBase`](ue_ue.ClothPhysicalMeshDataBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:27665](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27665)

___

### Load

▸ `Static` **Load**(`InName`): [`ClothPhysicalMeshDataBase`](ue_ue.ClothPhysicalMeshDataBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ClothPhysicalMeshDataBase`](ue_ue.ClothPhysicalMeshDataBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:27666](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27666)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:27664](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27664)
