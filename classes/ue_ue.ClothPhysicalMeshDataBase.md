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

## Properties

### BoneData

• **BoneData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClothVertBoneData`](ue_ue.ClothVertBoneData.md)\>

___

### Indices

• **Indices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### InverseMasses

• **InverseMasses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### MaxBoneWeights

• **MaxBoneWeights**: `number`

___

### Normals

• **Normals**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

___

### NumFixedVerts

• **NumFixedVerts**: `number`

___

### SelfCollisionIndices

• **SelfCollisionIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### VertexColors

• **VertexColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Color`](ue_ue_s.Color.md)\>

___

### Vertices

• **Vertices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

___

### \_\_tid\_ClothPhysicalMeshDataBase\_\_

• **\_\_tid\_ClothPhysicalMeshDataBase\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
