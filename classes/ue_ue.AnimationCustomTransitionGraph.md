[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimationCustomTransitionGraph

# Class: AnimationCustomTransitionGraph

[ue/ue](../modules/ue_ue.md).AnimationCustomTransitionGraph

## Hierarchy

- [`AnimationGraph`](ue_ue.AnimationGraph.md)

  ↳ **`AnimationCustomTransitionGraph`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimationCustomTransitionGraph.md#constructor)

### Properties

- [BlendOptions](ue_ue.AnimationCustomTransitionGraph.md#blendoptions)
- [GraphGuid](ue_ue.AnimationCustomTransitionGraph.md#graphguid)
- [InterfaceGuid](ue_ue.AnimationCustomTransitionGraph.md#interfaceguid)
- [MyResultNode](ue_ue.AnimationCustomTransitionGraph.md#myresultnode)
- [Nodes](ue_ue.AnimationCustomTransitionGraph.md#nodes)
- [Schema](ue_ue.AnimationCustomTransitionGraph.md#schema)
- [SubGraphs](ue_ue.AnimationCustomTransitionGraph.md#subgraphs)
- [\_\_tid\_AnimationCustomTransitionGraph\_\_](ue_ue.AnimationCustomTransitionGraph.md#__tid_animationcustomtransitiongraph__)
- [\_\_tid\_AnimationGraph\_\_](ue_ue.AnimationCustomTransitionGraph.md#__tid_animationgraph__)
- [\_\_tid\_EdGraph\_\_](ue_ue.AnimationCustomTransitionGraph.md#__tid_edgraph__)
- [\_\_tid\_Object\_\_](ue_ue.AnimationCustomTransitionGraph.md#__tid_object__)
- [bAllowDeletion](ue_ue.AnimationCustomTransitionGraph.md#ballowdeletion)
- [bAllowRenaming](ue_ue.AnimationCustomTransitionGraph.md#ballowrenaming)
- [bEditable](ue_ue.AnimationCustomTransitionGraph.md#beditable)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimationCustomTransitionGraph.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimationCustomTransitionGraph.md#executeubergraph)
- [GetClass](ue_ue.AnimationCustomTransitionGraph.md#getclass)
- [GetName](ue_ue.AnimationCustomTransitionGraph.md#getname)
- [GetOuter](ue_ue.AnimationCustomTransitionGraph.md#getouter)
- [GetWorld](ue_ue.AnimationCustomTransitionGraph.md#getworld)
- [Find](ue_ue.AnimationCustomTransitionGraph.md#find)
- [Load](ue_ue.AnimationCustomTransitionGraph.md#load)
- [StaticClass](ue_ue.AnimationCustomTransitionGraph.md#staticclass)

## Constructors

### constructor

• **new AnimationCustomTransitionGraph**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimationGraph](ue_ue.AnimationGraph.md).[constructor](ue_ue.AnimationGraph.md#constructor)

## Properties

### BlendOptions

• **BlendOptions**: [`AnimGraphBlendOptions`](ue_ue.AnimGraphBlendOptions.md)

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[BlendOptions](ue_ue.AnimationGraph.md#blendoptions)

___

### GraphGuid

• **GraphGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[GraphGuid](ue_ue.AnimationGraph.md#graphguid)

___

### InterfaceGuid

• **InterfaceGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[InterfaceGuid](ue_ue.AnimationGraph.md#interfaceguid)

___

### MyResultNode

• **MyResultNode**: [`AnimGraphNode_CustomTransitionResult`](ue_ue.AnimGraphNode_CustomTransitionResult.md)

___

### Nodes

• **Nodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphNode`](ue_ue.EdGraphNode.md)\>

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[Nodes](ue_ue.AnimationGraph.md#nodes)

___

### Schema

• **Schema**: [`Class`](ue_ue.Class.md)

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[Schema](ue_ue.AnimationGraph.md#schema)

___

### SubGraphs

• **SubGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[SubGraphs](ue_ue.AnimationGraph.md#subgraphs)

___

### \_\_tid\_AnimationCustomTransitionGraph\_\_

• **\_\_tid\_AnimationCustomTransitionGraph\_\_**: `boolean`

___

### \_\_tid\_AnimationGraph\_\_

• **\_\_tid\_AnimationGraph\_\_**: `boolean`

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[__tid_AnimationGraph__](ue_ue.AnimationGraph.md#__tid_animationgraph__)

___

### \_\_tid\_EdGraph\_\_

• **\_\_tid\_EdGraph\_\_**: `boolean`

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[__tid_EdGraph__](ue_ue.AnimationGraph.md#__tid_edgraph__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[__tid_Object__](ue_ue.AnimationGraph.md#__tid_object__)

___

### bAllowDeletion

• **bAllowDeletion**: `boolean`

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[bAllowDeletion](ue_ue.AnimationGraph.md#ballowdeletion)

___

### bAllowRenaming

• **bAllowRenaming**: `boolean`

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[bAllowRenaming](ue_ue.AnimationGraph.md#ballowrenaming)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[bEditable](ue_ue.AnimationGraph.md#beditable)

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

[AnimationGraph](ue_ue.AnimationGraph.md).[CreateDefaultSubobject](ue_ue.AnimationGraph.md#createdefaultsubobject)

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

[AnimationGraph](ue_ue.AnimationGraph.md).[ExecuteUbergraph](ue_ue.AnimationGraph.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[GetClass](ue_ue.AnimationGraph.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[GetName](ue_ue.AnimationGraph.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[GetOuter](ue_ue.AnimationGraph.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[GetWorld](ue_ue.AnimationGraph.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimationCustomTransitionGraph`](ue_ue.AnimationCustomTransitionGraph.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimationCustomTransitionGraph`](ue_ue.AnimationCustomTransitionGraph.md)

#### Overrides

[AnimationGraph](ue_ue.AnimationGraph.md).[Find](ue_ue.AnimationGraph.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimationCustomTransitionGraph`](ue_ue.AnimationCustomTransitionGraph.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimationCustomTransitionGraph`](ue_ue.AnimationCustomTransitionGraph.md)

#### Overrides

[AnimationGraph](ue_ue.AnimationGraph.md).[Load](ue_ue.AnimationGraph.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimationGraph](ue_ue.AnimationGraph.md).[StaticClass](ue_ue.AnimationGraph.md#staticclass)
