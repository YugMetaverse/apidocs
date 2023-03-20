[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MeshReconstructorBase

# Class: MeshReconstructorBase

[ue/ue](../modules/ue_ue.md).MeshReconstructorBase

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MeshReconstructorBase`**

## Table of contents

### Constructors

- [constructor](ue_ue.MeshReconstructorBase.md#constructor)

### Properties

- [\_\_tid\_MeshReconstructorBase\_\_](ue_ue.MeshReconstructorBase.md#__tid_meshreconstructorbase__)
- [\_\_tid\_Object\_\_](ue_ue.MeshReconstructorBase.md#__tid_object__)

### Methods

- [ConnectMRMesh](ue_ue.MeshReconstructorBase.md#connectmrmesh)
- [CreateDefaultSubobject](ue_ue.MeshReconstructorBase.md#createdefaultsubobject)
- [DisconnectMRMesh](ue_ue.MeshReconstructorBase.md#disconnectmrmesh)
- [ExecuteUbergraph](ue_ue.MeshReconstructorBase.md#executeubergraph)
- [GetClass](ue_ue.MeshReconstructorBase.md#getclass)
- [GetName](ue_ue.MeshReconstructorBase.md#getname)
- [GetOuter](ue_ue.MeshReconstructorBase.md#getouter)
- [GetWorld](ue_ue.MeshReconstructorBase.md#getworld)
- [IsReconstructionPaused](ue_ue.MeshReconstructorBase.md#isreconstructionpaused)
- [IsReconstructionStarted](ue_ue.MeshReconstructorBase.md#isreconstructionstarted)
- [PauseReconstruction](ue_ue.MeshReconstructorBase.md#pausereconstruction)
- [StartReconstruction](ue_ue.MeshReconstructorBase.md#startreconstruction)
- [StopReconstruction](ue_ue.MeshReconstructorBase.md#stopreconstruction)
- [Find](ue_ue.MeshReconstructorBase.md#find)
- [Load](ue_ue.MeshReconstructorBase.md#load)
- [StaticClass](ue_ue.MeshReconstructorBase.md#staticclass)

## Constructors

### constructor

• **new MeshReconstructorBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_MeshReconstructorBase\_\_

• **\_\_tid\_MeshReconstructorBase\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

## Methods

### ConnectMRMesh

▸ **ConnectMRMesh**(`Mesh`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Mesh` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MRMeshComponent`](ue_ue.MRMeshComponent.md)\> |

#### Returns

`void`

___

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

### DisconnectMRMesh

▸ **DisconnectMRMesh**(): `void`

#### Returns

`void`

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

### IsReconstructionPaused

▸ **IsReconstructionPaused**(): `boolean`

#### Returns

`boolean`

___

### IsReconstructionStarted

▸ **IsReconstructionStarted**(): `boolean`

#### Returns

`boolean`

___

### PauseReconstruction

▸ **PauseReconstruction**(): `void`

#### Returns

`void`

___

### StartReconstruction

▸ **StartReconstruction**(): `void`

#### Returns

`void`

___

### StopReconstruction

▸ **StopReconstruction**(): `void`

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MeshReconstructorBase`](ue_ue.MeshReconstructorBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MeshReconstructorBase`](ue_ue.MeshReconstructorBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MeshReconstructorBase`](ue_ue.MeshReconstructorBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MeshReconstructorBase`](ue_ue.MeshReconstructorBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
