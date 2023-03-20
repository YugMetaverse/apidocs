[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AIGraphSchema

# Class: AIGraphSchema

[ue/ue](../modules/ue_ue.md).AIGraphSchema

## Hierarchy

- [`EdGraphSchema`](ue_ue.EdGraphSchema.md)

  ↳ **`AIGraphSchema`**

  ↳↳ [`EdGraphSchema_BehaviorTree`](ue_ue.EdGraphSchema_BehaviorTree.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AIGraphSchema.md#constructor)

### Properties

- [\_\_tid\_AIGraphSchema\_\_](ue_ue.AIGraphSchema.md#__tid_aigraphschema__)
- [\_\_tid\_EdGraphSchema\_\_](ue_ue.AIGraphSchema.md#__tid_edgraphschema__)
- [\_\_tid\_Object\_\_](ue_ue.AIGraphSchema.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AIGraphSchema.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AIGraphSchema.md#executeubergraph)
- [GetClass](ue_ue.AIGraphSchema.md#getclass)
- [GetName](ue_ue.AIGraphSchema.md#getname)
- [GetOuter](ue_ue.AIGraphSchema.md#getouter)
- [GetWorld](ue_ue.AIGraphSchema.md#getworld)
- [Find](ue_ue.AIGraphSchema.md#find)
- [Load](ue_ue.AIGraphSchema.md#load)
- [StaticClass](ue_ue.AIGraphSchema.md#staticclass)

## Constructors

### constructor

• **new AIGraphSchema**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EdGraphSchema](ue_ue.EdGraphSchema.md).[constructor](ue_ue.EdGraphSchema.md#constructor)

#### Defined in

[ue/ue.d.ts:15142](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15142)

## Properties

### \_\_tid\_AIGraphSchema\_\_

• **\_\_tid\_AIGraphSchema\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:15147](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15147)

___

### \_\_tid\_EdGraphSchema\_\_

• **\_\_tid\_EdGraphSchema\_\_**: `boolean`

#### Inherited from

[EdGraphSchema](ue_ue.EdGraphSchema.md).[__tid_EdGraphSchema__](ue_ue.EdGraphSchema.md#__tid_edgraphschema__)

#### Defined in

[ue/ue.d.ts:15138](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15138)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EdGraphSchema](ue_ue.EdGraphSchema.md).[__tid_Object__](ue_ue.EdGraphSchema.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[EdGraphSchema](ue_ue.EdGraphSchema.md).[CreateDefaultSubobject](ue_ue.EdGraphSchema.md#createdefaultsubobject)

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

[EdGraphSchema](ue_ue.EdGraphSchema.md).[ExecuteUbergraph](ue_ue.EdGraphSchema.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EdGraphSchema](ue_ue.EdGraphSchema.md).[GetClass](ue_ue.EdGraphSchema.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EdGraphSchema](ue_ue.EdGraphSchema.md).[GetName](ue_ue.EdGraphSchema.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EdGraphSchema](ue_ue.EdGraphSchema.md).[GetOuter](ue_ue.EdGraphSchema.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EdGraphSchema](ue_ue.EdGraphSchema.md).[GetWorld](ue_ue.EdGraphSchema.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AIGraphSchema`](ue_ue.AIGraphSchema.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AIGraphSchema`](ue_ue.AIGraphSchema.md)

#### Overrides

[EdGraphSchema](ue_ue.EdGraphSchema.md).[Find](ue_ue.EdGraphSchema.md#find)

#### Defined in

[ue/ue.d.ts:15144](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15144)

___

### Load

▸ `Static` **Load**(`InName`): [`AIGraphSchema`](ue_ue.AIGraphSchema.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AIGraphSchema`](ue_ue.AIGraphSchema.md)

#### Overrides

[EdGraphSchema](ue_ue.EdGraphSchema.md).[Load](ue_ue.EdGraphSchema.md#load)

#### Defined in

[ue/ue.d.ts:15145](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15145)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EdGraphSchema](ue_ue.EdGraphSchema.md).[StaticClass](ue_ue.EdGraphSchema.md#staticclass)

#### Defined in

[ue/ue.d.ts:15143](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15143)
