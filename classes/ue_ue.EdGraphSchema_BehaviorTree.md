[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EdGraphSchema\_BehaviorTree

# Class: EdGraphSchema\_BehaviorTree

[ue/ue](../modules/ue_ue.md).EdGraphSchema_BehaviorTree

## Hierarchy

- [`AIGraphSchema`](ue_ue.AIGraphSchema.md)

  ↳ **`EdGraphSchema_BehaviorTree`**

## Table of contents

### Constructors

- [constructor](ue_ue.EdGraphSchema_BehaviorTree.md#constructor)

### Properties

- [\_\_tid\_AIGraphSchema\_\_](ue_ue.EdGraphSchema_BehaviorTree.md#__tid_aigraphschema__)
- [\_\_tid\_EdGraphSchema\_BehaviorTree\_\_](ue_ue.EdGraphSchema_BehaviorTree.md#__tid_edgraphschema_behaviortree__)
- [\_\_tid\_EdGraphSchema\_\_](ue_ue.EdGraphSchema_BehaviorTree.md#__tid_edgraphschema__)
- [\_\_tid\_Object\_\_](ue_ue.EdGraphSchema_BehaviorTree.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.EdGraphSchema_BehaviorTree.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EdGraphSchema_BehaviorTree.md#executeubergraph)
- [GetClass](ue_ue.EdGraphSchema_BehaviorTree.md#getclass)
- [GetName](ue_ue.EdGraphSchema_BehaviorTree.md#getname)
- [GetOuter](ue_ue.EdGraphSchema_BehaviorTree.md#getouter)
- [GetWorld](ue_ue.EdGraphSchema_BehaviorTree.md#getworld)
- [Find](ue_ue.EdGraphSchema_BehaviorTree.md#find)
- [Load](ue_ue.EdGraphSchema_BehaviorTree.md#load)
- [StaticClass](ue_ue.EdGraphSchema_BehaviorTree.md#staticclass)

## Constructors

### constructor

• **new EdGraphSchema_BehaviorTree**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AIGraphSchema](ue_ue.AIGraphSchema.md).[constructor](ue_ue.AIGraphSchema.md#constructor)

## Properties

### \_\_tid\_AIGraphSchema\_\_

• **\_\_tid\_AIGraphSchema\_\_**: `boolean`

#### Inherited from

[AIGraphSchema](ue_ue.AIGraphSchema.md).[__tid_AIGraphSchema__](ue_ue.AIGraphSchema.md#__tid_aigraphschema__)

___

### \_\_tid\_EdGraphSchema\_BehaviorTree\_\_

• **\_\_tid\_EdGraphSchema\_BehaviorTree\_\_**: `boolean`

___

### \_\_tid\_EdGraphSchema\_\_

• **\_\_tid\_EdGraphSchema\_\_**: `boolean`

#### Inherited from

[AIGraphSchema](ue_ue.AIGraphSchema.md).[__tid_EdGraphSchema__](ue_ue.AIGraphSchema.md#__tid_edgraphschema__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AIGraphSchema](ue_ue.AIGraphSchema.md).[__tid_Object__](ue_ue.AIGraphSchema.md#__tid_object__)

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

[AIGraphSchema](ue_ue.AIGraphSchema.md).[CreateDefaultSubobject](ue_ue.AIGraphSchema.md#createdefaultsubobject)

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

[AIGraphSchema](ue_ue.AIGraphSchema.md).[ExecuteUbergraph](ue_ue.AIGraphSchema.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AIGraphSchema](ue_ue.AIGraphSchema.md).[GetClass](ue_ue.AIGraphSchema.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AIGraphSchema](ue_ue.AIGraphSchema.md).[GetName](ue_ue.AIGraphSchema.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AIGraphSchema](ue_ue.AIGraphSchema.md).[GetOuter](ue_ue.AIGraphSchema.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AIGraphSchema](ue_ue.AIGraphSchema.md).[GetWorld](ue_ue.AIGraphSchema.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EdGraphSchema_BehaviorTree`](ue_ue.EdGraphSchema_BehaviorTree.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EdGraphSchema_BehaviorTree`](ue_ue.EdGraphSchema_BehaviorTree.md)

#### Overrides

[AIGraphSchema](ue_ue.AIGraphSchema.md).[Find](ue_ue.AIGraphSchema.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EdGraphSchema_BehaviorTree`](ue_ue.EdGraphSchema_BehaviorTree.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EdGraphSchema_BehaviorTree`](ue_ue.EdGraphSchema_BehaviorTree.md)

#### Overrides

[AIGraphSchema](ue_ue.AIGraphSchema.md).[Load](ue_ue.AIGraphSchema.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AIGraphSchema](ue_ue.AIGraphSchema.md).[StaticClass](ue_ue.AIGraphSchema.md#staticclass)
