[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EdGraph\_ReferenceViewer

# Class: EdGraph\_ReferenceViewer

[ue/ue](../modules/ue_ue.md).EdGraph_ReferenceViewer

## Hierarchy

- [`EdGraph`](ue_ue.EdGraph.md)

  ↳ **`EdGraph_ReferenceViewer`**

## Table of contents

### Constructors

- [constructor](ue_ue.EdGraph_ReferenceViewer.md#constructor)

### Properties

- [GraphGuid](ue_ue.EdGraph_ReferenceViewer.md#graphguid)
- [InterfaceGuid](ue_ue.EdGraph_ReferenceViewer.md#interfaceguid)
- [Nodes](ue_ue.EdGraph_ReferenceViewer.md#nodes)
- [Schema](ue_ue.EdGraph_ReferenceViewer.md#schema)
- [SubGraphs](ue_ue.EdGraph_ReferenceViewer.md#subgraphs)
- [\_\_tid\_EdGraph\_ReferenceViewer\_\_](ue_ue.EdGraph_ReferenceViewer.md#__tid_edgraph_referenceviewer__)
- [\_\_tid\_EdGraph\_\_](ue_ue.EdGraph_ReferenceViewer.md#__tid_edgraph__)
- [\_\_tid\_Object\_\_](ue_ue.EdGraph_ReferenceViewer.md#__tid_object__)
- [bAllowDeletion](ue_ue.EdGraph_ReferenceViewer.md#ballowdeletion)
- [bAllowRenaming](ue_ue.EdGraph_ReferenceViewer.md#ballowrenaming)
- [bEditable](ue_ue.EdGraph_ReferenceViewer.md#beditable)

### Methods

- [CreateDefaultSubobject](ue_ue.EdGraph_ReferenceViewer.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EdGraph_ReferenceViewer.md#executeubergraph)
- [GetClass](ue_ue.EdGraph_ReferenceViewer.md#getclass)
- [GetName](ue_ue.EdGraph_ReferenceViewer.md#getname)
- [GetOuter](ue_ue.EdGraph_ReferenceViewer.md#getouter)
- [GetWorld](ue_ue.EdGraph_ReferenceViewer.md#getworld)
- [Find](ue_ue.EdGraph_ReferenceViewer.md#find)
- [Load](ue_ue.EdGraph_ReferenceViewer.md#load)
- [StaticClass](ue_ue.EdGraph_ReferenceViewer.md#staticclass)

## Constructors

### constructor

• **new EdGraph_ReferenceViewer**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EdGraph](ue_ue.EdGraph.md).[constructor](ue_ue.EdGraph.md#constructor)

#### Defined in

[ue/ue.d.ts:31440](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31440)

## Properties

### GraphGuid

• **GraphGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[GraphGuid](ue_ue.EdGraph.md#graphguid)

#### Defined in

[ue/ue.d.ts:4175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4175)

___

### InterfaceGuid

• **InterfaceGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[InterfaceGuid](ue_ue.EdGraph.md#interfaceguid)

#### Defined in

[ue/ue.d.ts:4176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4176)

___

### Nodes

• **Nodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphNode`](ue_ue.EdGraphNode.md)\>

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[Nodes](ue_ue.EdGraph.md#nodes)

#### Defined in

[ue/ue.d.ts:4170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4170)

___

### Schema

• **Schema**: [`Class`](ue_ue.Class.md)

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[Schema](ue_ue.EdGraph.md#schema)

#### Defined in

[ue/ue.d.ts:4169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4169)

___

### SubGraphs

• **SubGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[SubGraphs](ue_ue.EdGraph.md#subgraphs)

#### Defined in

[ue/ue.d.ts:4174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4174)

___

### \_\_tid\_EdGraph\_ReferenceViewer\_\_

• **\_\_tid\_EdGraph\_ReferenceViewer\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:31445](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31445)

___

### \_\_tid\_EdGraph\_\_

• **\_\_tid\_EdGraph\_\_**: `boolean`

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[__tid_EdGraph__](ue_ue.EdGraph.md#__tid_edgraph__)

#### Defined in

[ue/ue.d.ts:4181](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4181)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[__tid_Object__](ue_ue.EdGraph.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bAllowDeletion

• **bAllowDeletion**: `boolean`

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[bAllowDeletion](ue_ue.EdGraph.md#ballowdeletion)

#### Defined in

[ue/ue.d.ts:4172](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4172)

___

### bAllowRenaming

• **bAllowRenaming**: `boolean`

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[bAllowRenaming](ue_ue.EdGraph.md#ballowrenaming)

#### Defined in

[ue/ue.d.ts:4173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4173)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[bEditable](ue_ue.EdGraph.md#beditable)

#### Defined in

[ue/ue.d.ts:4171](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4171)

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

[EdGraph](ue_ue.EdGraph.md).[CreateDefaultSubobject](ue_ue.EdGraph.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[EdGraph](ue_ue.EdGraph.md).[ExecuteUbergraph](ue_ue.EdGraph.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[GetClass](ue_ue.EdGraph.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[GetName](ue_ue.EdGraph.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[GetOuter](ue_ue.EdGraph.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[GetWorld](ue_ue.EdGraph.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EdGraph_ReferenceViewer`](ue_ue.EdGraph_ReferenceViewer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EdGraph_ReferenceViewer`](ue_ue.EdGraph_ReferenceViewer.md)

#### Overrides

[EdGraph](ue_ue.EdGraph.md).[Find](ue_ue.EdGraph.md#find)

#### Defined in

[ue/ue.d.ts:31442](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31442)

___

### Load

▸ `Static` **Load**(`InName`): [`EdGraph_ReferenceViewer`](ue_ue.EdGraph_ReferenceViewer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EdGraph_ReferenceViewer`](ue_ue.EdGraph_ReferenceViewer.md)

#### Overrides

[EdGraph](ue_ue.EdGraph.md).[Load](ue_ue.EdGraph.md#load)

#### Defined in

[ue/ue.d.ts:31443](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31443)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EdGraph](ue_ue.EdGraph.md).[StaticClass](ue_ue.EdGraph.md#staticclass)

#### Defined in

[ue/ue.d.ts:31441](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31441)
