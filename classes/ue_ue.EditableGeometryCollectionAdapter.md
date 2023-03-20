[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditableGeometryCollectionAdapter

# Class: EditableGeometryCollectionAdapter

[ue/ue](../modules/ue_ue.md).EditableGeometryCollectionAdapter

## Hierarchy

- [`EditableMeshAdapter`](ue_ue.EditableMeshAdapter.md)

  ↳ **`EditableGeometryCollectionAdapter`**

## Table of contents

### Constructors

- [constructor](ue_ue.EditableGeometryCollectionAdapter.md#constructor)

### Properties

- [GeometryCollection](ue_ue.EditableGeometryCollectionAdapter.md#geometrycollection)
- [GeometryCollectionLODIndex](ue_ue.EditableGeometryCollectionAdapter.md#geometrycollectionlodindex)
- [OriginalGeometryCollection](ue_ue.EditableGeometryCollectionAdapter.md#originalgeometrycollection)
- [\_\_tid\_EditableGeometryCollectionAdapter\_\_](ue_ue.EditableGeometryCollectionAdapter.md#__tid_editablegeometrycollectionadapter__)
- [\_\_tid\_EditableMeshAdapter\_\_](ue_ue.EditableGeometryCollectionAdapter.md#__tid_editablemeshadapter__)
- [\_\_tid\_Object\_\_](ue_ue.EditableGeometryCollectionAdapter.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.EditableGeometryCollectionAdapter.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditableGeometryCollectionAdapter.md#executeubergraph)
- [GetClass](ue_ue.EditableGeometryCollectionAdapter.md#getclass)
- [GetName](ue_ue.EditableGeometryCollectionAdapter.md#getname)
- [GetOuter](ue_ue.EditableGeometryCollectionAdapter.md#getouter)
- [GetWorld](ue_ue.EditableGeometryCollectionAdapter.md#getworld)
- [Find](ue_ue.EditableGeometryCollectionAdapter.md#find)
- [Load](ue_ue.EditableGeometryCollectionAdapter.md#load)
- [StaticClass](ue_ue.EditableGeometryCollectionAdapter.md#staticclass)

## Constructors

### constructor

• **new EditableGeometryCollectionAdapter**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EditableMeshAdapter](ue_ue.EditableMeshAdapter.md).[constructor](ue_ue.EditableMeshAdapter.md#constructor)

## Properties

### GeometryCollection

• **GeometryCollection**: [`GeometryCollection`](ue_ue.GeometryCollection.md)

___

### GeometryCollectionLODIndex

• **GeometryCollectionLODIndex**: `number`

___

### OriginalGeometryCollection

• **OriginalGeometryCollection**: [`GeometryCollection`](ue_ue.GeometryCollection.md)

___

### \_\_tid\_EditableGeometryCollectionAdapter\_\_

• **\_\_tid\_EditableGeometryCollectionAdapter\_\_**: `boolean`

___

### \_\_tid\_EditableMeshAdapter\_\_

• **\_\_tid\_EditableMeshAdapter\_\_**: `boolean`

#### Inherited from

[EditableMeshAdapter](ue_ue.EditableMeshAdapter.md).[__tid_EditableMeshAdapter__](ue_ue.EditableMeshAdapter.md#__tid_editablemeshadapter__)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditableGeometryCollectionAdapter`](ue_ue.EditableGeometryCollectionAdapter.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditableGeometryCollectionAdapter`](ue_ue.EditableGeometryCollectionAdapter.md)

#### Overrides

[EditableMeshAdapter](ue_ue.EditableMeshAdapter.md).[Find](ue_ue.EditableMeshAdapter.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EditableGeometryCollectionAdapter`](ue_ue.EditableGeometryCollectionAdapter.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditableGeometryCollectionAdapter`](ue_ue.EditableGeometryCollectionAdapter.md)

#### Overrides

[EditableMeshAdapter](ue_ue.EditableMeshAdapter.md).[Load](ue_ue.EditableMeshAdapter.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EditableMeshAdapter](ue_ue.EditableMeshAdapter.md).[StaticClass](ue_ue.EditableMeshAdapter.md#staticclass)
