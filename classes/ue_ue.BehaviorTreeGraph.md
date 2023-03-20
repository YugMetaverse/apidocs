[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BehaviorTreeGraph

# Class: BehaviorTreeGraph

[ue/ue](../modules/ue_ue.md).BehaviorTreeGraph

## Hierarchy

- [`AIGraph`](ue_ue.AIGraph.md)

  ↳ **`BehaviorTreeGraph`**

## Table of contents

### Constructors

- [constructor](ue_ue.BehaviorTreeGraph.md#constructor)

### Properties

- [GraphGuid](ue_ue.BehaviorTreeGraph.md#graphguid)
- [GraphVersion](ue_ue.BehaviorTreeGraph.md#graphversion)
- [InterfaceGuid](ue_ue.BehaviorTreeGraph.md#interfaceguid)
- [ModCounter](ue_ue.BehaviorTreeGraph.md#modcounter)
- [Nodes](ue_ue.BehaviorTreeGraph.md#nodes)
- [Schema](ue_ue.BehaviorTreeGraph.md#schema)
- [SubGraphs](ue_ue.BehaviorTreeGraph.md#subgraphs)
- [\_\_tid\_AIGraph\_\_](ue_ue.BehaviorTreeGraph.md#__tid_aigraph__)
- [\_\_tid\_BehaviorTreeGraph\_\_](ue_ue.BehaviorTreeGraph.md#__tid_behaviortreegraph__)
- [\_\_tid\_EdGraph\_\_](ue_ue.BehaviorTreeGraph.md#__tid_edgraph__)
- [\_\_tid\_Object\_\_](ue_ue.BehaviorTreeGraph.md#__tid_object__)
- [bAllowDeletion](ue_ue.BehaviorTreeGraph.md#ballowdeletion)
- [bAllowRenaming](ue_ue.BehaviorTreeGraph.md#ballowrenaming)
- [bEditable](ue_ue.BehaviorTreeGraph.md#beditable)
- [bIsUsingModCounter](ue_ue.BehaviorTreeGraph.md#bisusingmodcounter)

### Methods

- [CreateDefaultSubobject](ue_ue.BehaviorTreeGraph.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BehaviorTreeGraph.md#executeubergraph)
- [GetClass](ue_ue.BehaviorTreeGraph.md#getclass)
- [GetName](ue_ue.BehaviorTreeGraph.md#getname)
- [GetOuter](ue_ue.BehaviorTreeGraph.md#getouter)
- [GetWorld](ue_ue.BehaviorTreeGraph.md#getworld)
- [Find](ue_ue.BehaviorTreeGraph.md#find)
- [Load](ue_ue.BehaviorTreeGraph.md#load)
- [StaticClass](ue_ue.BehaviorTreeGraph.md#staticclass)

## Constructors

### constructor

• **new BehaviorTreeGraph**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AIGraph](ue_ue.AIGraph.md).[constructor](ue_ue.AIGraph.md#constructor)

## Properties

### GraphGuid

• **GraphGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[AIGraph](ue_ue.AIGraph.md).[GraphGuid](ue_ue.AIGraph.md#graphguid)

___

### GraphVersion

• **GraphVersion**: `number`

#### Inherited from

[AIGraph](ue_ue.AIGraph.md).[GraphVersion](ue_ue.AIGraph.md#graphversion)

___

### InterfaceGuid

• **InterfaceGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[AIGraph](ue_ue.AIGraph.md).[InterfaceGuid](ue_ue.AIGraph.md#interfaceguid)

___

### ModCounter

• **ModCounter**: `number`

___

### Nodes

• **Nodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphNode`](ue_ue.EdGraphNode.md)\>

#### Inherited from

[AIGraph](ue_ue.AIGraph.md).[Nodes](ue_ue.AIGraph.md#nodes)

___

### Schema

• **Schema**: [`Class`](ue_ue.Class.md)

#### Inherited from

[AIGraph](ue_ue.AIGraph.md).[Schema](ue_ue.AIGraph.md#schema)

___

### SubGraphs

• **SubGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[AIGraph](ue_ue.AIGraph.md).[SubGraphs](ue_ue.AIGraph.md#subgraphs)

___

### \_\_tid\_AIGraph\_\_

• **\_\_tid\_AIGraph\_\_**: `boolean`

#### Inherited from

[AIGraph](ue_ue.AIGraph.md).[__tid_AIGraph__](ue_ue.AIGraph.md#__tid_aigraph__)

___

### \_\_tid\_BehaviorTreeGraph\_\_

• **\_\_tid\_BehaviorTreeGraph\_\_**: `boolean`

___

### \_\_tid\_EdGraph\_\_

• **\_\_tid\_EdGraph\_\_**: `boolean`

#### Inherited from

[AIGraph](ue_ue.AIGraph.md).[__tid_EdGraph__](ue_ue.AIGraph.md#__tid_edgraph__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AIGraph](ue_ue.AIGraph.md).[__tid_Object__](ue_ue.AIGraph.md#__tid_object__)

___

### bAllowDeletion

• **bAllowDeletion**: `boolean`

#### Inherited from

[AIGraph](ue_ue.AIGraph.md).[bAllowDeletion](ue_ue.AIGraph.md#ballowdeletion)

___

### bAllowRenaming

• **bAllowRenaming**: `boolean`

#### Inherited from

[AIGraph](ue_ue.AIGraph.md).[bAllowRenaming](ue_ue.AIGraph.md#ballowrenaming)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[AIGraph](ue_ue.AIGraph.md).[bEditable](ue_ue.AIGraph.md#beditable)

___

### bIsUsingModCounter

• **bIsUsingModCounter**: `boolean`

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

[AIGraph](ue_ue.AIGraph.md).[CreateDefaultSubobject](ue_ue.AIGraph.md#createdefaultsubobject)

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

[AIGraph](ue_ue.AIGraph.md).[ExecuteUbergraph](ue_ue.AIGraph.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AIGraph](ue_ue.AIGraph.md).[GetClass](ue_ue.AIGraph.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AIGraph](ue_ue.AIGraph.md).[GetName](ue_ue.AIGraph.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AIGraph](ue_ue.AIGraph.md).[GetOuter](ue_ue.AIGraph.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AIGraph](ue_ue.AIGraph.md).[GetWorld](ue_ue.AIGraph.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BehaviorTreeGraph`](ue_ue.BehaviorTreeGraph.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BehaviorTreeGraph`](ue_ue.BehaviorTreeGraph.md)

#### Overrides

[AIGraph](ue_ue.AIGraph.md).[Find](ue_ue.AIGraph.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BehaviorTreeGraph`](ue_ue.BehaviorTreeGraph.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BehaviorTreeGraph`](ue_ue.BehaviorTreeGraph.md)

#### Overrides

[AIGraph](ue_ue.AIGraph.md).[Load](ue_ue.AIGraph.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AIGraph](ue_ue.AIGraph.md).[StaticClass](ue_ue.AIGraph.md#staticclass)
