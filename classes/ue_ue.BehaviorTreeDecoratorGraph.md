[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BehaviorTreeDecoratorGraph

# Class: BehaviorTreeDecoratorGraph

[ue/ue](../modules/ue_ue.md).BehaviorTreeDecoratorGraph

## Hierarchy

- [`EdGraph`](ue_ue.EdGraph.md)

  ↳ **`BehaviorTreeDecoratorGraph`**

## Table of contents

### Constructors

- [constructor](ue_ue.BehaviorTreeDecoratorGraph.md#constructor)

### Properties

- [GraphGuid](ue_ue.BehaviorTreeDecoratorGraph.md#graphguid)
- [InterfaceGuid](ue_ue.BehaviorTreeDecoratorGraph.md#interfaceguid)
- [Nodes](ue_ue.BehaviorTreeDecoratorGraph.md#nodes)
- [Schema](ue_ue.BehaviorTreeDecoratorGraph.md#schema)
- [SubGraphs](ue_ue.BehaviorTreeDecoratorGraph.md#subgraphs)
- [\_\_tid\_BehaviorTreeDecoratorGraph\_\_](ue_ue.BehaviorTreeDecoratorGraph.md#__tid_behaviortreedecoratorgraph__)
- [\_\_tid\_EdGraph\_\_](ue_ue.BehaviorTreeDecoratorGraph.md#__tid_edgraph__)
- [\_\_tid\_Object\_\_](ue_ue.BehaviorTreeDecoratorGraph.md#__tid_object__)
- [bAllowDeletion](ue_ue.BehaviorTreeDecoratorGraph.md#ballowdeletion)
- [bAllowRenaming](ue_ue.BehaviorTreeDecoratorGraph.md#ballowrenaming)
- [bEditable](ue_ue.BehaviorTreeDecoratorGraph.md#beditable)

### Methods

- [CreateDefaultSubobject](ue_ue.BehaviorTreeDecoratorGraph.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BehaviorTreeDecoratorGraph.md#executeubergraph)
- [GetClass](ue_ue.BehaviorTreeDecoratorGraph.md#getclass)
- [GetName](ue_ue.BehaviorTreeDecoratorGraph.md#getname)
- [GetOuter](ue_ue.BehaviorTreeDecoratorGraph.md#getouter)
- [GetWorld](ue_ue.BehaviorTreeDecoratorGraph.md#getworld)
- [Find](ue_ue.BehaviorTreeDecoratorGraph.md#find)
- [Load](ue_ue.BehaviorTreeDecoratorGraph.md#load)
- [StaticClass](ue_ue.BehaviorTreeDecoratorGraph.md#staticclass)

## Constructors

### constructor

• **new BehaviorTreeDecoratorGraph**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EdGraph](ue_ue.EdGraph.md).[constructor](ue_ue.EdGraph.md#constructor)

## Properties

### GraphGuid

• **GraphGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[GraphGuid](ue_ue.EdGraph.md#graphguid)

___

### InterfaceGuid

• **InterfaceGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[InterfaceGuid](ue_ue.EdGraph.md#interfaceguid)

___

### Nodes

• **Nodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphNode`](ue_ue.EdGraphNode.md)\>

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[Nodes](ue_ue.EdGraph.md#nodes)

___

### Schema

• **Schema**: [`Class`](ue_ue.Class.md)

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[Schema](ue_ue.EdGraph.md#schema)

___

### SubGraphs

• **SubGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[SubGraphs](ue_ue.EdGraph.md#subgraphs)

___

### \_\_tid\_BehaviorTreeDecoratorGraph\_\_

• **\_\_tid\_BehaviorTreeDecoratorGraph\_\_**: `boolean`

___

### \_\_tid\_EdGraph\_\_

• **\_\_tid\_EdGraph\_\_**: `boolean`

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[__tid_EdGraph__](ue_ue.EdGraph.md#__tid_edgraph__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[__tid_Object__](ue_ue.EdGraph.md#__tid_object__)

___

### bAllowDeletion

• **bAllowDeletion**: `boolean`

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[bAllowDeletion](ue_ue.EdGraph.md#ballowdeletion)

___

### bAllowRenaming

• **bAllowRenaming**: `boolean`

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[bAllowRenaming](ue_ue.EdGraph.md#ballowrenaming)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[bEditable](ue_ue.EdGraph.md#beditable)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[GetClass](ue_ue.EdGraph.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[GetName](ue_ue.EdGraph.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[GetOuter](ue_ue.EdGraph.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[GetWorld](ue_ue.EdGraph.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BehaviorTreeDecoratorGraph`](ue_ue.BehaviorTreeDecoratorGraph.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BehaviorTreeDecoratorGraph`](ue_ue.BehaviorTreeDecoratorGraph.md)

#### Overrides

[EdGraph](ue_ue.EdGraph.md).[Find](ue_ue.EdGraph.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BehaviorTreeDecoratorGraph`](ue_ue.BehaviorTreeDecoratorGraph.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BehaviorTreeDecoratorGraph`](ue_ue.BehaviorTreeDecoratorGraph.md)

#### Overrides

[EdGraph](ue_ue.EdGraph.md).[Load](ue_ue.EdGraph.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EdGraph](ue_ue.EdGraph.md).[StaticClass](ue_ue.EdGraph.md#staticclass)
