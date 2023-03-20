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

#### Defined in

[ue/ue.d.ts:27849](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27849)

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

#### Defined in

[ue/ue.d.ts:27850](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27850)

## Properties

### AnimDriveMultipliers

• **AnimDriveMultipliers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:27858](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27858)

___

### BackstopDistances

• **BackstopDistances**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:27856](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27856)

___

### BackstopRadiuses

• **BackstopRadiuses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:27857](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27857)

___

### BoneData

• **BoneData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClothVertBoneData`](ue_ue.ClothVertBoneData.md)\>

#### Defined in

[ue/ue.d.ts:27860](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27860)

___

### Indices

• **Indices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:27854](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27854)

___

### InverseMasses

• **InverseMasses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:27859](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27859)

___

### MaxBoneWeights

• **MaxBoneWeights**: `number`

#### Defined in

[ue/ue.d.ts:27861](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27861)

___

### MaxDistances

• **MaxDistances**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:27855](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27855)

___

### Normals

• **Normals**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Defined in

[ue/ue.d.ts:27852](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27852)

___

### NumFixedVerts

• **NumFixedVerts**: `number`

#### Defined in

[ue/ue.d.ts:27862](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27862)

___

### SelfCollisionIndices

• **SelfCollisionIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:27863](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27863)

___

### VertexColors

• **VertexColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Color`](ue_ue_s.Color.md)\>

#### Defined in

[ue/ue.d.ts:27853](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27853)

___

### Vertices

• **Vertices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Defined in

[ue/ue.d.ts:27851](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27851)

___

### \_\_tid\_ClothPhysicalMeshData\_\_

• `Private` **\_\_tid\_ClothPhysicalMeshData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:27869](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27869)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:27867](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27867)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:27868](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27868)
