[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ReferenceViewerSchema

# Class: ReferenceViewerSchema

[ue/ue](../modules/ue_ue.md).ReferenceViewerSchema

## Hierarchy

- [`EdGraphSchema`](ue_ue.EdGraphSchema.md)

  ↳ **`ReferenceViewerSchema`**

## Table of contents

### Constructors

- [constructor](ue_ue.ReferenceViewerSchema.md#constructor)

### Properties

- [\_\_tid\_EdGraphSchema\_\_](ue_ue.ReferenceViewerSchema.md#__tid_edgraphschema__)
- [\_\_tid\_Object\_\_](ue_ue.ReferenceViewerSchema.md#__tid_object__)
- [\_\_tid\_ReferenceViewerSchema\_\_](ue_ue.ReferenceViewerSchema.md#__tid_referenceviewerschema__)

### Methods

- [CreateDefaultSubobject](ue_ue.ReferenceViewerSchema.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ReferenceViewerSchema.md#executeubergraph)
- [GetClass](ue_ue.ReferenceViewerSchema.md#getclass)
- [GetName](ue_ue.ReferenceViewerSchema.md#getname)
- [GetOuter](ue_ue.ReferenceViewerSchema.md#getouter)
- [GetWorld](ue_ue.ReferenceViewerSchema.md#getworld)
- [Find](ue_ue.ReferenceViewerSchema.md#find)
- [Load](ue_ue.ReferenceViewerSchema.md#load)
- [StaticClass](ue_ue.ReferenceViewerSchema.md#staticclass)

## Constructors

### constructor

• **new ReferenceViewerSchema**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EdGraphSchema](ue_ue.EdGraphSchema.md).[constructor](ue_ue.EdGraphSchema.md#constructor)

## Properties

### \_\_tid\_EdGraphSchema\_\_

• **\_\_tid\_EdGraphSchema\_\_**: `boolean`

#### Inherited from

[EdGraphSchema](ue_ue.EdGraphSchema.md).[__tid_EdGraphSchema__](ue_ue.EdGraphSchema.md#__tid_edgraphschema__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EdGraphSchema](ue_ue.EdGraphSchema.md).[__tid_Object__](ue_ue.EdGraphSchema.md#__tid_object__)

___

### \_\_tid\_ReferenceViewerSchema\_\_

• **\_\_tid\_ReferenceViewerSchema\_\_**: `boolean`

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

[EdGraphSchema](ue_ue.EdGraphSchema.md).[CreateDefaultSubobject](ue_ue.EdGraphSchema.md#createdefaultsubobject)

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

[EdGraphSchema](ue_ue.EdGraphSchema.md).[ExecuteUbergraph](ue_ue.EdGraphSchema.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EdGraphSchema](ue_ue.EdGraphSchema.md).[GetClass](ue_ue.EdGraphSchema.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EdGraphSchema](ue_ue.EdGraphSchema.md).[GetName](ue_ue.EdGraphSchema.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EdGraphSchema](ue_ue.EdGraphSchema.md).[GetOuter](ue_ue.EdGraphSchema.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EdGraphSchema](ue_ue.EdGraphSchema.md).[GetWorld](ue_ue.EdGraphSchema.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ReferenceViewerSchema`](ue_ue.ReferenceViewerSchema.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ReferenceViewerSchema`](ue_ue.ReferenceViewerSchema.md)

#### Overrides

[EdGraphSchema](ue_ue.EdGraphSchema.md).[Find](ue_ue.EdGraphSchema.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ReferenceViewerSchema`](ue_ue.ReferenceViewerSchema.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ReferenceViewerSchema`](ue_ue.ReferenceViewerSchema.md)

#### Overrides

[EdGraphSchema](ue_ue.EdGraphSchema.md).[Load](ue_ue.EdGraphSchema.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EdGraphSchema](ue_ue.EdGraphSchema.md).[StaticClass](ue_ue.EdGraphSchema.md#staticclass)
