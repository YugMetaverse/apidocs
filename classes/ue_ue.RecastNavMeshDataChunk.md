[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / RecastNavMeshDataChunk

# Class: RecastNavMeshDataChunk

[ue/ue](../modules/ue_ue.md).RecastNavMeshDataChunk

## Hierarchy

- [`NavigationDataChunk`](ue_ue.NavigationDataChunk.md)

  ↳ **`RecastNavMeshDataChunk`**

## Table of contents

### Constructors

- [constructor](ue_ue.RecastNavMeshDataChunk.md#constructor)

### Properties

- [NavigationDataName](ue_ue.RecastNavMeshDataChunk.md#navigationdataname)
- [\_\_tid\_NavigationDataChunk\_\_](ue_ue.RecastNavMeshDataChunk.md#__tid_navigationdatachunk__)
- [\_\_tid\_Object\_\_](ue_ue.RecastNavMeshDataChunk.md#__tid_object__)
- [\_\_tid\_RecastNavMeshDataChunk\_\_](ue_ue.RecastNavMeshDataChunk.md#__tid_recastnavmeshdatachunk__)

### Methods

- [CreateDefaultSubobject](ue_ue.RecastNavMeshDataChunk.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.RecastNavMeshDataChunk.md#executeubergraph)
- [GetClass](ue_ue.RecastNavMeshDataChunk.md#getclass)
- [GetName](ue_ue.RecastNavMeshDataChunk.md#getname)
- [GetOuter](ue_ue.RecastNavMeshDataChunk.md#getouter)
- [GetWorld](ue_ue.RecastNavMeshDataChunk.md#getworld)
- [Find](ue_ue.RecastNavMeshDataChunk.md#find)
- [Load](ue_ue.RecastNavMeshDataChunk.md#load)
- [StaticClass](ue_ue.RecastNavMeshDataChunk.md#staticclass)

## Constructors

### constructor

• **new RecastNavMeshDataChunk**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[NavigationDataChunk](ue_ue.NavigationDataChunk.md).[constructor](ue_ue.NavigationDataChunk.md#constructor)

## Properties

### NavigationDataName

• **NavigationDataName**: `string`

#### Inherited from

[NavigationDataChunk](ue_ue.NavigationDataChunk.md).[NavigationDataName](ue_ue.NavigationDataChunk.md#navigationdataname)

___

### \_\_tid\_NavigationDataChunk\_\_

• **\_\_tid\_NavigationDataChunk\_\_**: `boolean`

#### Inherited from

[NavigationDataChunk](ue_ue.NavigationDataChunk.md).[__tid_NavigationDataChunk__](ue_ue.NavigationDataChunk.md#__tid_navigationdatachunk__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[NavigationDataChunk](ue_ue.NavigationDataChunk.md).[__tid_Object__](ue_ue.NavigationDataChunk.md#__tid_object__)

___

### \_\_tid\_RecastNavMeshDataChunk\_\_

• **\_\_tid\_RecastNavMeshDataChunk\_\_**: `boolean`

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

[NavigationDataChunk](ue_ue.NavigationDataChunk.md).[CreateDefaultSubobject](ue_ue.NavigationDataChunk.md#createdefaultsubobject)

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

[NavigationDataChunk](ue_ue.NavigationDataChunk.md).[ExecuteUbergraph](ue_ue.NavigationDataChunk.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[NavigationDataChunk](ue_ue.NavigationDataChunk.md).[GetClass](ue_ue.NavigationDataChunk.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[NavigationDataChunk](ue_ue.NavigationDataChunk.md).[GetName](ue_ue.NavigationDataChunk.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[NavigationDataChunk](ue_ue.NavigationDataChunk.md).[GetOuter](ue_ue.NavigationDataChunk.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[NavigationDataChunk](ue_ue.NavigationDataChunk.md).[GetWorld](ue_ue.NavigationDataChunk.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`RecastNavMeshDataChunk`](ue_ue.RecastNavMeshDataChunk.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`RecastNavMeshDataChunk`](ue_ue.RecastNavMeshDataChunk.md)

#### Overrides

[NavigationDataChunk](ue_ue.NavigationDataChunk.md).[Find](ue_ue.NavigationDataChunk.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`RecastNavMeshDataChunk`](ue_ue.RecastNavMeshDataChunk.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`RecastNavMeshDataChunk`](ue_ue.RecastNavMeshDataChunk.md)

#### Overrides

[NavigationDataChunk](ue_ue.NavigationDataChunk.md).[Load](ue_ue.NavigationDataChunk.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[NavigationDataChunk](ue_ue.NavigationDataChunk.md).[StaticClass](ue_ue.NavigationDataChunk.md#staticclass)
