[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimationGraph

# Class: AnimationGraph

[ue/ue](../modules/ue_ue.md).AnimationGraph

## Hierarchy

- [`EdGraph`](ue_ue.EdGraph.md)

  ↳ **`AnimationGraph`**

  ↳↳ [`AnimationCustomTransitionGraph`](ue_ue.AnimationCustomTransitionGraph.md)

  ↳↳ [`AnimationStateGraph`](ue_ue.AnimationStateGraph.md)

  ↳↳ [`AnimationTransitionGraph`](ue_ue.AnimationTransitionGraph.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimationGraph.md#constructor)

### Properties

- [BlendOptions](ue_ue.AnimationGraph.md#blendoptions)
- [GraphGuid](ue_ue.AnimationGraph.md#graphguid)
- [InterfaceGuid](ue_ue.AnimationGraph.md#interfaceguid)
- [Nodes](ue_ue.AnimationGraph.md#nodes)
- [Schema](ue_ue.AnimationGraph.md#schema)
- [SubGraphs](ue_ue.AnimationGraph.md#subgraphs)
- [\_\_tid\_AnimationGraph\_\_](ue_ue.AnimationGraph.md#__tid_animationgraph__)
- [\_\_tid\_EdGraph\_\_](ue_ue.AnimationGraph.md#__tid_edgraph__)
- [\_\_tid\_Object\_\_](ue_ue.AnimationGraph.md#__tid_object__)
- [bAllowDeletion](ue_ue.AnimationGraph.md#ballowdeletion)
- [bAllowRenaming](ue_ue.AnimationGraph.md#ballowrenaming)
- [bEditable](ue_ue.AnimationGraph.md#beditable)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimationGraph.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimationGraph.md#executeubergraph)
- [GetClass](ue_ue.AnimationGraph.md#getclass)
- [GetName](ue_ue.AnimationGraph.md#getname)
- [GetOuter](ue_ue.AnimationGraph.md#getouter)
- [GetWorld](ue_ue.AnimationGraph.md#getworld)
- [Find](ue_ue.AnimationGraph.md#find)
- [Load](ue_ue.AnimationGraph.md#load)
- [StaticClass](ue_ue.AnimationGraph.md#staticclass)

## Constructors

### constructor

• **new AnimationGraph**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EdGraph](ue_ue.EdGraph.md).[constructor](ue_ue.EdGraph.md#constructor)

#### Defined in

[ue/ue.d.ts:16734](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16734)

## Properties

### BlendOptions

• **BlendOptions**: [`AnimGraphBlendOptions`](ue_ue.AnimGraphBlendOptions.md)

#### Defined in

[ue/ue.d.ts:16735](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16735)

___

### GraphGuid

• **GraphGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[GraphGuid](ue_ue.EdGraph.md#graphguid)

#### Defined in

[ue/ue.d.ts:4175](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4175)

___

### InterfaceGuid

• **InterfaceGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[InterfaceGuid](ue_ue.EdGraph.md#interfaceguid)

#### Defined in

[ue/ue.d.ts:4176](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4176)

___

### Nodes

• **Nodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphNode`](ue_ue.EdGraphNode.md)\>

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[Nodes](ue_ue.EdGraph.md#nodes)

#### Defined in

[ue/ue.d.ts:4170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4170)

___

### Schema

• **Schema**: [`Class`](ue_ue.Class.md)

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[Schema](ue_ue.EdGraph.md#schema)

#### Defined in

[ue/ue.d.ts:4169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4169)

___

### SubGraphs

• **SubGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[SubGraphs](ue_ue.EdGraph.md#subgraphs)

#### Defined in

[ue/ue.d.ts:4174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4174)

___

### \_\_tid\_AnimationGraph\_\_

• **\_\_tid\_AnimationGraph\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:16740](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16740)

___

### \_\_tid\_EdGraph\_\_

• **\_\_tid\_EdGraph\_\_**: `boolean`

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[__tid_EdGraph__](ue_ue.EdGraph.md#__tid_edgraph__)

#### Defined in

[ue/ue.d.ts:4181](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4181)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[__tid_Object__](ue_ue.EdGraph.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bAllowDeletion

• **bAllowDeletion**: `boolean`

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[bAllowDeletion](ue_ue.EdGraph.md#ballowdeletion)

#### Defined in

[ue/ue.d.ts:4172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4172)

___

### bAllowRenaming

• **bAllowRenaming**: `boolean`

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[bAllowRenaming](ue_ue.EdGraph.md#ballowrenaming)

#### Defined in

[ue/ue.d.ts:4173](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4173)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[bEditable](ue_ue.EdGraph.md#beditable)

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

[EdGraph](ue_ue.EdGraph.md).[CreateDefaultSubobject](ue_ue.EdGraph.md#createdefaultsubobject)

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

[EdGraph](ue_ue.EdGraph.md).[ExecuteUbergraph](ue_ue.EdGraph.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[GetClass](ue_ue.EdGraph.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[GetName](ue_ue.EdGraph.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[GetOuter](ue_ue.EdGraph.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EdGraph](ue_ue.EdGraph.md).[GetWorld](ue_ue.EdGraph.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimationGraph`](ue_ue.AnimationGraph.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimationGraph`](ue_ue.AnimationGraph.md)

#### Overrides

[EdGraph](ue_ue.EdGraph.md).[Find](ue_ue.EdGraph.md#find)

#### Defined in

[ue/ue.d.ts:16737](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16737)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimationGraph`](ue_ue.AnimationGraph.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimationGraph`](ue_ue.AnimationGraph.md)

#### Overrides

[EdGraph](ue_ue.EdGraph.md).[Load](ue_ue.EdGraph.md#load)

#### Defined in

[ue/ue.d.ts:16738](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16738)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EdGraph](ue_ue.EdGraph.md).[StaticClass](ue_ue.EdGraph.md#staticclass)

#### Defined in

[ue/ue.d.ts:16736](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16736)
