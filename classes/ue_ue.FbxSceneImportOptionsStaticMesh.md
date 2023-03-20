[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FbxSceneImportOptionsStaticMesh

# Class: FbxSceneImportOptionsStaticMesh

[ue/ue](../modules/ue_ue.md).FbxSceneImportOptionsStaticMesh

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`FbxSceneImportOptionsStaticMesh`**

## Table of contents

### Constructors

- [constructor](ue_ue.FbxSceneImportOptionsStaticMesh.md#constructor)

### Properties

- [NormalGenerationMethod](ue_ue.FbxSceneImportOptionsStaticMesh.md#normalgenerationmethod)
- [NormalImportMethod](ue_ue.FbxSceneImportOptionsStaticMesh.md#normalimportmethod)
- [StaticMeshLODGroup](ue_ue.FbxSceneImportOptionsStaticMesh.md#staticmeshlodgroup)
- [VertexColorImportOption](ue_ue.FbxSceneImportOptionsStaticMesh.md#vertexcolorimportoption)
- [VertexOverrideColor](ue_ue.FbxSceneImportOptionsStaticMesh.md#vertexoverridecolor)
- [\_\_tid\_FbxSceneImportOptionsStaticMesh\_\_](ue_ue.FbxSceneImportOptionsStaticMesh.md#__tid_fbxsceneimportoptionsstaticmesh__)
- [\_\_tid\_Object\_\_](ue_ue.FbxSceneImportOptionsStaticMesh.md#__tid_object__)
- [bAutoGenerateCollision](ue_ue.FbxSceneImportOptionsStaticMesh.md#bautogeneratecollision)
- [bBuildAdjacencyBuffer](ue_ue.FbxSceneImportOptionsStaticMesh.md#bbuildadjacencybuffer)
- [bBuildReversedIndexBuffer](ue_ue.FbxSceneImportOptionsStaticMesh.md#bbuildreversedindexbuffer)
- [bGenerateLightmapUVs](ue_ue.FbxSceneImportOptionsStaticMesh.md#bgeneratelightmapuvs)
- [bOneConvexHullPerUCX](ue_ue.FbxSceneImportOptionsStaticMesh.md#boneconvexhullperucx)
- [bRemoveDegenerates](ue_ue.FbxSceneImportOptionsStaticMesh.md#bremovedegenerates)

### Methods

- [CreateDefaultSubobject](ue_ue.FbxSceneImportOptionsStaticMesh.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.FbxSceneImportOptionsStaticMesh.md#executeubergraph)
- [GetClass](ue_ue.FbxSceneImportOptionsStaticMesh.md#getclass)
- [GetName](ue_ue.FbxSceneImportOptionsStaticMesh.md#getname)
- [GetOuter](ue_ue.FbxSceneImportOptionsStaticMesh.md#getouter)
- [GetWorld](ue_ue.FbxSceneImportOptionsStaticMesh.md#getworld)
- [Find](ue_ue.FbxSceneImportOptionsStaticMesh.md#find)
- [Load](ue_ue.FbxSceneImportOptionsStaticMesh.md#load)
- [StaticClass](ue_ue.FbxSceneImportOptionsStaticMesh.md#staticclass)

## Constructors

### constructor

• **new FbxSceneImportOptionsStaticMesh**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### NormalGenerationMethod

• **NormalGenerationMethod**: [`EFBXSceneNormalGenerationMethod`](../enums/ue_ue.EFBXSceneNormalGenerationMethod.md)

___

### NormalImportMethod

• **NormalImportMethod**: [`EFBXSceneNormalImportMethod`](../enums/ue_ue.EFBXSceneNormalImportMethod.md)

___

### StaticMeshLODGroup

• **StaticMeshLODGroup**: `string`

___

### VertexColorImportOption

• **VertexColorImportOption**: [`EFbxSceneVertexColorImportOption`](../enums/ue_ue.EFbxSceneVertexColorImportOption.md)

___

### VertexOverrideColor

• **VertexOverrideColor**: [`Color`](ue_ue_s.Color.md)

___

### \_\_tid\_FbxSceneImportOptionsStaticMesh\_\_

• **\_\_tid\_FbxSceneImportOptionsStaticMesh\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bAutoGenerateCollision

• **bAutoGenerateCollision**: `boolean`

___

### bBuildAdjacencyBuffer

• **bBuildAdjacencyBuffer**: `boolean`

___

### bBuildReversedIndexBuffer

• **bBuildReversedIndexBuffer**: `boolean`

___

### bGenerateLightmapUVs

• **bGenerateLightmapUVs**: `boolean`

___

### bOneConvexHullPerUCX

• **bOneConvexHullPerUCX**: `boolean`

___

### bRemoveDegenerates

• **bRemoveDegenerates**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FbxSceneImportOptionsStaticMesh`](ue_ue.FbxSceneImportOptionsStaticMesh.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FbxSceneImportOptionsStaticMesh`](ue_ue.FbxSceneImportOptionsStaticMesh.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`FbxSceneImportOptionsStaticMesh`](ue_ue.FbxSceneImportOptionsStaticMesh.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FbxSceneImportOptionsStaticMesh`](ue_ue.FbxSceneImportOptionsStaticMesh.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
