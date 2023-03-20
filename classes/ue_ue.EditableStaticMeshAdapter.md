[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditableStaticMeshAdapter

# Class: EditableStaticMeshAdapter

[ue/ue](../modules/ue_ue.md).EditableStaticMeshAdapter

## Hierarchy

- [`EditableMeshAdapter`](ue_ue.EditableMeshAdapter.md)

  ↳ **`EditableStaticMeshAdapter`**

## Table of contents

### Constructors

- [constructor](ue_ue.EditableStaticMeshAdapter.md#constructor)

### Properties

- [OriginalStaticMesh](ue_ue.EditableStaticMeshAdapter.md#originalstaticmesh)
- [StaticMesh](ue_ue.EditableStaticMeshAdapter.md#staticmesh)
- [StaticMeshLODIndex](ue_ue.EditableStaticMeshAdapter.md#staticmeshlodindex)
- [\_\_tid\_EditableMeshAdapter\_\_](ue_ue.EditableStaticMeshAdapter.md#__tid_editablemeshadapter__)
- [\_\_tid\_EditableStaticMeshAdapter\_\_](ue_ue.EditableStaticMeshAdapter.md#__tid_editablestaticmeshadapter__)
- [\_\_tid\_Object\_\_](ue_ue.EditableStaticMeshAdapter.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.EditableStaticMeshAdapter.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditableStaticMeshAdapter.md#executeubergraph)
- [GetClass](ue_ue.EditableStaticMeshAdapter.md#getclass)
- [GetName](ue_ue.EditableStaticMeshAdapter.md#getname)
- [GetOuter](ue_ue.EditableStaticMeshAdapter.md#getouter)
- [GetWorld](ue_ue.EditableStaticMeshAdapter.md#getworld)
- [Find](ue_ue.EditableStaticMeshAdapter.md#find)
- [Load](ue_ue.EditableStaticMeshAdapter.md#load)
- [StaticClass](ue_ue.EditableStaticMeshAdapter.md#staticclass)

## Constructors

### constructor

• **new EditableStaticMeshAdapter**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EditableMeshAdapter](ue_ue.EditableMeshAdapter.md).[constructor](ue_ue.EditableMeshAdapter.md#constructor)

## Properties

### OriginalStaticMesh

• **OriginalStaticMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### StaticMesh

• **StaticMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### StaticMeshLODIndex

• **StaticMeshLODIndex**: `number`

___

### \_\_tid\_EditableMeshAdapter\_\_

• **\_\_tid\_EditableMeshAdapter\_\_**: `boolean`

#### Inherited from

[EditableMeshAdapter](ue_ue.EditableMeshAdapter.md).[__tid_EditableMeshAdapter__](ue_ue.EditableMeshAdapter.md#__tid_editablemeshadapter__)

___

### \_\_tid\_EditableStaticMeshAdapter\_\_

• **\_\_tid\_EditableStaticMeshAdapter\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EditableMeshAdapter](ue_ue.EditableMeshAdapter.md).[__tid_Object__](ue_ue.EditableMeshAdapter.md#__tid_object__)

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

[EditableMeshAdapter](ue_ue.EditableMeshAdapter.md).[CreateDefaultSubobject](ue_ue.EditableMeshAdapter.md#createdefaultsubobject)

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

[EditableMeshAdapter](ue_ue.EditableMeshAdapter.md).[ExecuteUbergraph](ue_ue.EditableMeshAdapter.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EditableMeshAdapter](ue_ue.EditableMeshAdapter.md).[GetClass](ue_ue.EditableMeshAdapter.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EditableMeshAdapter](ue_ue.EditableMeshAdapter.md).[GetName](ue_ue.EditableMeshAdapter.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EditableMeshAdapter](ue_ue.EditableMeshAdapter.md).[GetOuter](ue_ue.EditableMeshAdapter.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EditableMeshAdapter](ue_ue.EditableMeshAdapter.md).[GetWorld](ue_ue.EditableMeshAdapter.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditableStaticMeshAdapter`](ue_ue.EditableStaticMeshAdapter.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditableStaticMeshAdapter`](ue_ue.EditableStaticMeshAdapter.md)

#### Overrides

[EditableMeshAdapter](ue_ue.EditableMeshAdapter.md).[Find](ue_ue.EditableMeshAdapter.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EditableStaticMeshAdapter`](ue_ue.EditableStaticMeshAdapter.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditableStaticMeshAdapter`](ue_ue.EditableStaticMeshAdapter.md)

#### Overrides

[EditableMeshAdapter](ue_ue.EditableMeshAdapter.md).[Load](ue_ue.EditableMeshAdapter.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EditableMeshAdapter](ue_ue.EditableMeshAdapter.md).[StaticClass](ue_ue.EditableMeshAdapter.md#staticclass)
