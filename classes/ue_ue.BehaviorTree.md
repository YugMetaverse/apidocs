[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BehaviorTree

# Class: BehaviorTree

[ue/ue](../modules/ue_ue.md).BehaviorTree

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`BehaviorTree`**

## Table of contents

### Constructors

- [constructor](ue_ue.BehaviorTree.md#constructor)

### Properties

- [BTGraph](ue_ue.BehaviorTree.md#btgraph)
- [BlackboardAsset](ue_ue.BehaviorTree.md#blackboardasset)
- [LastEditedDocuments](ue_ue.BehaviorTree.md#lastediteddocuments)
- [RootDecoratorOps](ue_ue.BehaviorTree.md#rootdecoratorops)
- [RootDecorators](ue_ue.BehaviorTree.md#rootdecorators)
- [RootNode](ue_ue.BehaviorTree.md#rootnode)
- [\_\_tid\_BehaviorTree\_\_](ue_ue.BehaviorTree.md#__tid_behaviortree__)
- [\_\_tid\_Object\_\_](ue_ue.BehaviorTree.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.BehaviorTree.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BehaviorTree.md#executeubergraph)
- [GetClass](ue_ue.BehaviorTree.md#getclass)
- [GetName](ue_ue.BehaviorTree.md#getname)
- [GetOuter](ue_ue.BehaviorTree.md#getouter)
- [GetWorld](ue_ue.BehaviorTree.md#getworld)
- [Find](ue_ue.BehaviorTree.md#find)
- [Load](ue_ue.BehaviorTree.md#load)
- [StaticClass](ue_ue.BehaviorTree.md#staticclass)

## Constructors

### constructor

• **new BehaviorTree**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:14701](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14701)

## Properties

### BTGraph

• **BTGraph**: [`EdGraph`](ue_ue.EdGraph.md)

#### Defined in

[ue/ue.d.ts:14703](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14703)

___

### BlackboardAsset

• **BlackboardAsset**: [`BlackboardData`](ue_ue.BlackboardData.md)

#### Defined in

[ue/ue.d.ts:14705](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14705)

___

### LastEditedDocuments

• **LastEditedDocuments**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EditedDocumentInfo`](ue_ue.EditedDocumentInfo.md)\>

#### Defined in

[ue/ue.d.ts:14704](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14704)

___

### RootDecoratorOps

• **RootDecoratorOps**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BTDecoratorLogic`](ue_ue.BTDecoratorLogic.md)\>

#### Defined in

[ue/ue.d.ts:14707](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14707)

___

### RootDecorators

• **RootDecorators**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BTDecorator`](ue_ue.BTDecorator.md)\>

#### Defined in

[ue/ue.d.ts:14706](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14706)

___

### RootNode

• **RootNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Defined in

[ue/ue.d.ts:14702](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14702)

___

### \_\_tid\_BehaviorTree\_\_

• **\_\_tid\_BehaviorTree\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:14712](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14712)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:14709](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14709)

___

### Load

▸ `Static` **Load**(`InName`): [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:14710](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14710)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:14708](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14708)
