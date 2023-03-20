[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EdGraph

# Class: EdGraph

[ue/ue](../modules/ue_ue.md).EdGraph

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`EdGraph`**

  ↳↳ [`AIGraph`](ue_ue.AIGraph.md)

  ↳↳ [`AnimationGraph`](ue_ue.AnimationGraph.md)

  ↳↳ [`AnimationStateMachineGraph`](ue_ue.AnimationStateMachineGraph.md)

  ↳↳ [`BehaviorTreeDecoratorGraph`](ue_ue.BehaviorTreeDecoratorGraph.md)

  ↳↳ [`EdGraph_ReferenceViewer`](ue_ue.EdGraph_ReferenceViewer.md)

  ↳↳ [`MaterialGraph`](ue_ue.MaterialGraph.md)

  ↳↳ [`SoundClassGraph`](ue_ue.SoundClassGraph.md)

  ↳↳ [`SoundCueGraph`](ue_ue.SoundCueGraph.md)

  ↳↳ [`SoundSubmixGraph`](ue_ue.SoundSubmixGraph.md)

## Table of contents

### Constructors

- [constructor](ue_ue.EdGraph.md#constructor)

### Properties

- [GraphGuid](ue_ue.EdGraph.md#graphguid)
- [InterfaceGuid](ue_ue.EdGraph.md#interfaceguid)
- [Nodes](ue_ue.EdGraph.md#nodes)
- [Schema](ue_ue.EdGraph.md#schema)
- [SubGraphs](ue_ue.EdGraph.md#subgraphs)
- [\_\_tid\_EdGraph\_\_](ue_ue.EdGraph.md#__tid_edgraph__)
- [\_\_tid\_Object\_\_](ue_ue.EdGraph.md#__tid_object__)
- [bAllowDeletion](ue_ue.EdGraph.md#ballowdeletion)
- [bAllowRenaming](ue_ue.EdGraph.md#ballowrenaming)
- [bEditable](ue_ue.EdGraph.md#beditable)

### Methods

- [CreateDefaultSubobject](ue_ue.EdGraph.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EdGraph.md#executeubergraph)
- [GetClass](ue_ue.EdGraph.md#getclass)
- [GetName](ue_ue.EdGraph.md#getname)
- [GetOuter](ue_ue.EdGraph.md#getouter)
- [GetWorld](ue_ue.EdGraph.md#getworld)
- [Find](ue_ue.EdGraph.md#find)
- [Load](ue_ue.EdGraph.md#load)
- [StaticClass](ue_ue.EdGraph.md#staticclass)

## Constructors

### constructor

• **new EdGraph**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:4168](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4168)

## Properties

### GraphGuid

• **GraphGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:4175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4175)

___

### InterfaceGuid

• **InterfaceGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:4176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4176)

___

### Nodes

• **Nodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphNode`](ue_ue.EdGraphNode.md)\>

#### Defined in

[ue/ue.d.ts:4170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4170)

___

### Schema

• **Schema**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:4169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4169)

___

### SubGraphs

• **SubGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Defined in

[ue/ue.d.ts:4174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4174)

___

### \_\_tid\_EdGraph\_\_

• **\_\_tid\_EdGraph\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:4181](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4181)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bAllowDeletion

• **bAllowDeletion**: `boolean`

#### Defined in

[ue/ue.d.ts:4172](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4172)

___

### bAllowRenaming

• **bAllowRenaming**: `boolean`

#### Defined in

[ue/ue.d.ts:4173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4173)

___

### bEditable

• **bEditable**: `boolean`

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EdGraph`](ue_ue.EdGraph.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EdGraph`](ue_ue.EdGraph.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:4178](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4178)

___

### Load

▸ `Static` **Load**(`InName`): [`EdGraph`](ue_ue.EdGraph.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EdGraph`](ue_ue.EdGraph.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:4179](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4179)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:4177](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4177)
