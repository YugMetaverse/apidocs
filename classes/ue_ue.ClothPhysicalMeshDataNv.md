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

#### Defined in

[ue/ue.d.ts:28027](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28027)

## Properties

### AnimDriveMultipliers

• **AnimDriveMultipliers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:28031](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28031)

___

### BackstopDistances

• **BackstopDistances**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:28029](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28029)

___

### BackstopRadiuses

• **BackstopRadiuses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:28030](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28030)

___

### BoneData

• **BoneData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClothVertBoneData`](ue_ue.ClothVertBoneData.md)\>

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[BoneData](ue_ue.ClothPhysicalMeshDataBase.md#bonedata)

#### Defined in

[ue/ue.d.ts:27660](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27660)

___

### Indices

• **Indices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[Indices](ue_ue.ClothPhysicalMeshDataBase.md#indices)

#### Defined in

[ue/ue.d.ts:27658](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27658)

___

### InverseMasses

• **InverseMasses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[InverseMasses](ue_ue.ClothPhysicalMeshDataBase.md#inversemasses)

#### Defined in

[ue/ue.d.ts:27659](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27659)

___

### MaxBoneWeights

• **MaxBoneWeights**: `number`

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[MaxBoneWeights](ue_ue.ClothPhysicalMeshDataBase.md#maxboneweights)

#### Defined in

[ue/ue.d.ts:27662](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27662)

___

### MaxDistances

• **MaxDistances**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:28028](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28028)

___

### Normals

• **Normals**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[Normals](ue_ue.ClothPhysicalMeshDataBase.md#normals)

#### Defined in

[ue/ue.d.ts:27656](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27656)

___

### NumFixedVerts

• **NumFixedVerts**: `number`

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[NumFixedVerts](ue_ue.ClothPhysicalMeshDataBase.md#numfixedverts)

#### Defined in

[ue/ue.d.ts:27661](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27661)

___

### SelfCollisionIndices

• **SelfCollisionIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[SelfCollisionIndices](ue_ue.ClothPhysicalMeshDataBase.md#selfcollisionindices)

#### Defined in

[ue/ue.d.ts:27663](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27663)

___

### VertexColors

• **VertexColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Color`](ue_ue_s.Color.md)\>

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[VertexColors](ue_ue.ClothPhysicalMeshDataBase.md#vertexcolors)

#### Defined in

[ue/ue.d.ts:27657](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27657)

___

### Vertices

• **Vertices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[Vertices](ue_ue.ClothPhysicalMeshDataBase.md#vertices)

#### Defined in

[ue/ue.d.ts:27655](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27655)

___

### \_\_tid\_ClothPhysicalMeshDataBase\_\_

• **\_\_tid\_ClothPhysicalMeshDataBase\_\_**: `boolean`

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[__tid_ClothPhysicalMeshDataBase__](ue_ue.ClothPhysicalMeshDataBase.md#__tid_clothphysicalmeshdatabase__)

#### Defined in

[ue/ue.d.ts:27668](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27668)

___

### \_\_tid\_ClothPhysicalMeshDataNv\_\_

• **\_\_tid\_ClothPhysicalMeshDataNv\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:28036](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28036)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[__tid_Object__](ue_ue.ClothPhysicalMeshDataBase.md#__tid_object__)

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

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[CreateDefaultSubobject](ue_ue.ClothPhysicalMeshDataBase.md#createdefaultsubobject)

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

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[ExecuteUbergraph](ue_ue.ClothPhysicalMeshDataBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[GetClass](ue_ue.ClothPhysicalMeshDataBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[GetName](ue_ue.ClothPhysicalMeshDataBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[GetOuter](ue_ue.ClothPhysicalMeshDataBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[GetWorld](ue_ue.ClothPhysicalMeshDataBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:28033](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28033)

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

#### Defined in

[ue/ue.d.ts:28034](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28034)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ClothPhysicalMeshDataBase](ue_ue.ClothPhysicalMeshDataBase.md).[StaticClass](ue_ue.ClothPhysicalMeshDataBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:28032](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28032)
