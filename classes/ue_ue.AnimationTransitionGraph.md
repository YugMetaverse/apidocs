[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimationTransitionGraph

# Class: AnimationTransitionGraph

[ue/ue](../modules/ue_ue.md).AnimationTransitionGraph

## Hierarchy

- [`AnimationGraph`](ue_ue.AnimationGraph.md)

  ↳ **`AnimationTransitionGraph`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimationTransitionGraph.md#constructor)

### Properties

- [BlendOptions](ue_ue.AnimationTransitionGraph.md#blendoptions)
- [GraphGuid](ue_ue.AnimationTransitionGraph.md#graphguid)
- [InterfaceGuid](ue_ue.AnimationTransitionGraph.md#interfaceguid)
- [MyResultNode](ue_ue.AnimationTransitionGraph.md#myresultnode)
- [Nodes](ue_ue.AnimationTransitionGraph.md#nodes)
- [Schema](ue_ue.AnimationTransitionGraph.md#schema)
- [SubGraphs](ue_ue.AnimationTransitionGraph.md#subgraphs)
- [\_\_tid\_AnimationGraph\_\_](ue_ue.AnimationTransitionGraph.md#__tid_animationgraph__)
- [\_\_tid\_AnimationTransitionGraph\_\_](ue_ue.AnimationTransitionGraph.md#__tid_animationtransitiongraph__)
- [\_\_tid\_EdGraph\_\_](ue_ue.AnimationTransitionGraph.md#__tid_edgraph__)
- [\_\_tid\_Object\_\_](ue_ue.AnimationTransitionGraph.md#__tid_object__)
- [bAllowDeletion](ue_ue.AnimationTransitionGraph.md#ballowdeletion)
- [bAllowRenaming](ue_ue.AnimationTransitionGraph.md#ballowrenaming)
- [bEditable](ue_ue.AnimationTransitionGraph.md#beditable)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimationTransitionGraph.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimationTransitionGraph.md#executeubergraph)
- [GetClass](ue_ue.AnimationTransitionGraph.md#getclass)
- [GetName](ue_ue.AnimationTransitionGraph.md#getname)
- [GetOuter](ue_ue.AnimationTransitionGraph.md#getouter)
- [GetWorld](ue_ue.AnimationTransitionGraph.md#getworld)
- [Find](ue_ue.AnimationTransitionGraph.md#find)
- [Load](ue_ue.AnimationTransitionGraph.md#load)
- [StaticClass](ue_ue.AnimationTransitionGraph.md#staticclass)

## Constructors

### constructor

• **new AnimationTransitionGraph**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimationGraph](ue_ue.AnimationGraph.md).[constructor](ue_ue.AnimationGraph.md#constructor)

#### Defined in

[ue/ue.d.ts:17228](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17228)

## Properties

### BlendOptions

• **BlendOptions**: [`AnimGraphBlendOptions`](ue_ue.AnimGraphBlendOptions.md)

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[BlendOptions](ue_ue.AnimationGraph.md#blendoptions)

#### Defined in

[ue/ue.d.ts:16735](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16735)

___

### GraphGuid

• **GraphGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[GraphGuid](ue_ue.AnimationGraph.md#graphguid)

#### Defined in

[ue/ue.d.ts:4175](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4175)

___

### InterfaceGuid

• **InterfaceGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[InterfaceGuid](ue_ue.AnimationGraph.md#interfaceguid)

#### Defined in

[ue/ue.d.ts:4176](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4176)

___

### MyResultNode

• **MyResultNode**: [`AnimGraphNode_TransitionResult`](ue_ue.AnimGraphNode_TransitionResult.md)

#### Defined in

[ue/ue.d.ts:17229](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17229)

___

### Nodes

• **Nodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphNode`](ue_ue.EdGraphNode.md)\>

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[Nodes](ue_ue.AnimationGraph.md#nodes)

#### Defined in

[ue/ue.d.ts:4170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4170)

___

### Schema

• **Schema**: [`Class`](ue_ue.Class.md)

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[Schema](ue_ue.AnimationGraph.md#schema)

#### Defined in

[ue/ue.d.ts:4169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4169)

___

### SubGraphs

• **SubGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[SubGraphs](ue_ue.AnimationGraph.md#subgraphs)

#### Defined in

[ue/ue.d.ts:4174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4174)

___

### \_\_tid\_AnimationGraph\_\_

• **\_\_tid\_AnimationGraph\_\_**: `boolean`

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[__tid_AnimationGraph__](ue_ue.AnimationGraph.md#__tid_animationgraph__)

#### Defined in

[ue/ue.d.ts:16740](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16740)

___

### \_\_tid\_AnimationTransitionGraph\_\_

• **\_\_tid\_AnimationTransitionGraph\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:17234](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17234)

___

### \_\_tid\_EdGraph\_\_

• **\_\_tid\_EdGraph\_\_**: `boolean`

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[__tid_EdGraph__](ue_ue.AnimationGraph.md#__tid_edgraph__)

#### Defined in

[ue/ue.d.ts:4181](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4181)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[__tid_Object__](ue_ue.AnimationGraph.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bAllowDeletion

• **bAllowDeletion**: `boolean`

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[bAllowDeletion](ue_ue.AnimationGraph.md#ballowdeletion)

#### Defined in

[ue/ue.d.ts:4172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4172)

___

### bAllowRenaming

• **bAllowRenaming**: `boolean`

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[bAllowRenaming](ue_ue.AnimationGraph.md#ballowrenaming)

#### Defined in

[ue/ue.d.ts:4173](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4173)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[bEditable](ue_ue.AnimationGraph.md#beditable)

#### Defined in

[ue/ue.d.ts:4171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4171)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[GetClass](ue_ue.AnimationGraph.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[GetName](ue_ue.AnimationGraph.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[GetOuter](ue_ue.AnimationGraph.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimationGraph](ue_ue.AnimationGraph.md).[GetWorld](ue_ue.AnimationGraph.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimationTransitionGraph`](ue_ue.AnimationTransitionGraph.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimationTransitionGraph`](ue_ue.AnimationTransitionGraph.md)

#### Overrides

[AnimationGraph](ue_ue.AnimationGraph.md).[Find](ue_ue.AnimationGraph.md#find)

#### Defined in

[ue/ue.d.ts:17231](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17231)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimationTransitionGraph`](ue_ue.AnimationTransitionGraph.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimationTransitionGraph`](ue_ue.AnimationTransitionGraph.md)

#### Overrides

[AnimationGraph](ue_ue.AnimationGraph.md).[Load](ue_ue.AnimationGraph.md#load)

#### Defined in

[ue/ue.d.ts:17232](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17232)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimationGraph](ue_ue.AnimationGraph.md).[StaticClass](ue_ue.AnimationGraph.md#staticclass)

#### Defined in

[ue/ue.d.ts:17230](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17230)
