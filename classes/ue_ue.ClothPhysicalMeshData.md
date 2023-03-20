[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ClothPhysicalMeshData

# Class: ClothPhysicalMeshData

[ue/ue](../modules/ue_ue.md).ClothPhysicalMeshData

## Table of contents

### Constructors

- [constructor](ue_ue.ClothPhysicalMeshData.md#constructor)

### Properties

- [AnimDriveMultipliers](ue_ue.ClothPhysicalMeshData.md#animdrivemultipliers)
- [BackstopDistances](ue_ue.ClothPhysicalMeshData.md#backstopdistances)
- [BackstopRadiuses](ue_ue.ClothPhysicalMeshData.md#backstopradiuses)
- [BoneData](ue_ue.ClothPhysicalMeshData.md#bonedata)
- [Indices](ue_ue.ClothPhysicalMeshData.md#indices)
- [InverseMasses](ue_ue.ClothPhysicalMeshData.md#inversemasses)
- [MaxBoneWeights](ue_ue.ClothPhysicalMeshData.md#maxboneweights)
- [MaxDistances](ue_ue.ClothPhysicalMeshData.md#maxdistances)
- [Normals](ue_ue.ClothPhysicalMeshData.md#normals)
- [NumFixedVerts](ue_ue.ClothPhysicalMeshData.md#numfixedverts)
- [SelfCollisionIndices](ue_ue.ClothPhysicalMeshData.md#selfcollisionindices)
- [VertexColors](ue_ue.ClothPhysicalMeshData.md#vertexcolors)
- [Vertices](ue_ue.ClothPhysicalMeshData.md#vertices)
- [\_\_tid\_ClothPhysicalMeshData\_\_](ue_ue.ClothPhysicalMeshData.md#__tid_clothphysicalmeshdata__)

### Methods

- [StaticClass](ue_ue.ClothPhysicalMeshData.md#staticclass)
- [StaticStruct](ue_ue.ClothPhysicalMeshData.md#staticstruct)

## Constructors

### constructor

• **new ClothPhysicalMeshData**()

• **new ClothPhysicalMeshData**(`Vertices`, `Normals`, `VertexColors`, `Indices`, `MaxDistances`, `BackstopDistances`, `BackstopRadiuses`, `AnimDriveMultipliers`, `InverseMasses`, `BoneData`, `MaxBoneWeights`, `NumFixedVerts`, `SelfCollisionIndices`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Vertices` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `Normals` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `VertexColors` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Color`](ue_ue_s.Color.md)\> |
| `Indices` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `MaxDistances` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `BackstopDistances` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `BackstopRadiuses` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `AnimDriveMultipliers` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `InverseMasses` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `BoneData` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClothVertBoneData`](ue_ue.ClothVertBoneData.md)\> |
| `MaxBoneWeights` | `number` |
| `NumFixedVerts` | `number` |
| `SelfCollisionIndices` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

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

### MaxDistances

• **MaxDistances**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

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

### \_\_tid\_ClothPhysicalMeshData\_\_

• `Private` **\_\_tid\_ClothPhysicalMeshData\_\_**: `boolean`

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
