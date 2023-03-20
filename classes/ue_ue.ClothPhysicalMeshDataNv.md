[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ClothPhysicalMeshDataNv

# Class: ClothPhysicalMeshDataNv

[ue/ue](../modules/ue_ue.md).ClothPhysicalMeshDataNv

## Hierarchy

- [`ClothPhysicalMeshDataBase`](ue_ue.ClothPhysicalMeshDataBase.md)

  ↳ **`ClothPhysicalMeshDataNv`**

## Table of contents

### Constructors

- [constructor](ue_ue.ClothPhysicalMeshDataNv.md#constructor)

### Properties

- [AnimDriveMultipliers](ue_ue.ClothPhysicalMeshDataNv.md#animdrivemultipliers)
- [BackstopDistances](ue_ue.ClothPhysicalMeshDataNv.md#backstopdistances)
- [BackstopRadiuses](ue_ue.ClothPhysicalMeshDataNv.md#backstopradiuses)
- [BoneData](ue_ue.ClothPhysicalMeshDataNv.md#bonedata)
- [Indices](ue_ue.ClothPhysicalMeshDataNv.md#indices)
- [InverseMasses](ue_ue.ClothPhysicalMeshDataNv.md#inversemasses)
- [MaxBoneWeights](ue_ue.ClothPhysicalMeshDataNv.md#maxboneweights)
- [MaxDistances](ue_ue.ClothPhysicalMeshDataNv.md#maxdistances)
- [Normals](ue_ue.ClothPhysicalMeshDataNv.md#normals)
- [NumFixedVerts](ue_ue.ClothPhysicalMeshDataNv.md#numfixedverts)
- [SelfCollisionIndices](ue_ue.ClothPhysicalMeshDataNv.md#selfcollisionindices)
- [VertexColors](ue_ue.ClothPhysicalMeshDataNv.md#vertexcolors)
- [Vertices](ue_ue.ClothPhysicalMeshDataNv.md#vertices)
- [\_\_tid\_ClothPhysicalMeshDataBase\_\_](ue_ue.ClothPhysicalMeshDataNv.md#__tid_clothphysicalmeshdatabase__)
- [\_\_tid\_ClothPhysicalMeshDataNv\_\_](ue_ue.ClothPhysicalMeshDataNv.md#__tid_clothphysicalmeshdatanv__)
- [\_\_tid\_Object\_\_](ue_ue.ClothPhysicalMeshDataNv.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ClothPhysicalMeshDataNv.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ClothPhysicalMeshDataNv.md#executeubergraph)
- [GetClass](ue_ue.ClothPhysicalMeshDataNv.md#getclass)
- [GetName](ue_ue.ClothPhysicalMeshDataNv.md#getname)
- [GetOuter](ue_ue.ClothPhysicalMeshDataNv.md#getouter)
- [GetWorld](ue_ue.ClothPhysicalMeshDataNv.md#getworld)
- [Find](ue_ue.ClothPhysicalMeshDataNv.md#find)
- [Load](ue_ue.ClothPhysicalMeshDataNv.md#load)
- [StaticClass](ue_ue.ClothPhysicalMeshDataNv.md#staticclass)

## Constructors

### constructor

• **new ClothPhysicalMeshDataNv**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[constructor](ue_ue.ClothPhysicalMeshDataBase.md#constructor)

## Properties

### AnimDriveMultipliers

• **AnimDriveMultipliers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### BackstopDistances

• **BackstopDistances**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### BackstopRadiuses

• **BackstopRadiuses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### BoneData

• **BoneData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClothVertBoneData`](ue_ue.ClothVertBoneData.md)\>

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[BoneData](ue_ue.ClothPhysicalMeshDataBase.md#bonedata)

___

### Indices

• **Indices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[Indices](ue_ue.ClothPhysicalMeshDataBase.md#indices)

___

### InverseMasses

• **InverseMasses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[InverseMasses](ue_ue.ClothPhysicalMeshDataBase.md#inversemasses)

___

### MaxBoneWeights

• **MaxBoneWeights**: `number`

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[MaxBoneWeights](ue_ue.ClothPhysicalMeshDataBase.md#maxboneweights)

___

### MaxDistances

• **MaxDistances**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### Normals

• **Normals**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[Normals](ue_ue.ClothPhysicalMeshDataBase.md#normals)

___

### NumFixedVerts

• **NumFixedVerts**: `number`

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[NumFixedVerts](ue_ue.ClothPhysicalMeshDataBase.md#numfixedverts)

___

### SelfCollisionIndices

• **SelfCollisionIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[SelfCollisionIndices](ue_ue.ClothPhysicalMeshDataBase.md#selfcollisionindices)

___

### VertexColors

• **VertexColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Color`](ue_ue_s.Color.md)\>

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[VertexColors](ue_ue.ClothPhysicalMeshDataBase.md#vertexcolors)

___

### Vertices

• **Vertices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[Vertices](ue_ue.ClothPhysicalMeshDataBase.md#vertices)

___

### \_\_tid\_ClothPhysicalMeshDataBase\_\_

• **\_\_tid\_ClothPhysicalMeshDataBase\_\_**: `boolean`

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[__tid_ClothPhysicalMeshDataBase__](ue_ue.ClothPhysicalMeshDataBase.md#__tid_clothphysicalmeshdatabase__)

___

### \_\_tid\_ClothPhysicalMeshDataNv\_\_

• **\_\_tid\_ClothPhysicalMeshDataNv\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[__tid_Object__](ue_ue.ClothPhysicalMeshDataBase.md#__tid_object__)

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

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[CreateDefaultSubobject](ue_ue.ClothPhysicalMeshDataBase.md#createdefaultsubobject)

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

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[ExecuteUbergraph](ue_ue.ClothPhysicalMeshDataBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[GetClass](ue_ue.ClothPhysicalMeshDataBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[GetName](ue_ue.ClothPhysicalMeshDataBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[GetOuter](ue_ue.ClothPhysicalMeshDataBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[GetWorld](ue_ue.ClothPhysicalMeshDataBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ClothPhysicalMeshDataNv`](ue_ue.ClothPhysicalMeshDataNv.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ClothPhysicalMeshDataNv`](ue_ue.ClothPhysicalMeshDataNv.md)

#### Overrides

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[Find](ue_ue.ClothPhysicalMeshDataBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ClothPhysicalMeshDataNv`](ue_ue.ClothPhysicalMeshDataNv.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ClothPhysicalMeshDataNv`](ue_ue.ClothPhysicalMeshDataNv.md)

#### Overrides

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[Load](ue_ue.ClothPhysicalMeshDataBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[StaticClass](ue_ue.ClothPhysicalMeshDataBase.md#staticclass)
