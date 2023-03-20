[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTNode

# Class: BTNode

[ue/ue](../modules/ue_ue.md).BTNode

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`BTNode`**

  ↳↳ [`BTAuxiliaryNode`](ue_ue.BTAuxiliaryNode.md)

  ↳↳ [`BTTaskNode`](ue_ue.BTTaskNode.md)

  ↳↳ [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

## Table of contents

### Constructors

- [constructor](ue_ue.BTNode.md#constructor)

### Properties

- [NodeName](ue_ue.BTNode.md#nodename)
- [ParentNode](ue_ue.BTNode.md#parentnode)
- [TreeAsset](ue_ue.BTNode.md#treeasset)
- [\_\_tid\_BTNode\_\_](ue_ue.BTNode.md#__tid_btnode__)
- [\_\_tid\_Object\_\_](ue_ue.BTNode.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.BTNode.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTNode.md#executeubergraph)
- [GetClass](ue_ue.BTNode.md#getclass)
- [GetName](ue_ue.BTNode.md#getname)
- [GetOuter](ue_ue.BTNode.md#getouter)
- [GetWorld](ue_ue.BTNode.md#getworld)
- [Find](ue_ue.BTNode.md#find)
- [Load](ue_ue.BTNode.md#load)
- [StaticClass](ue_ue.BTNode.md#staticclass)

## Constructors

### constructor

• **new BTNode**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### NodeName

• **NodeName**: `string`

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTNode`](ue_ue.BTNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTNode`](ue_ue.BTNode.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BTNode`](ue_ue.BTNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTNode`](ue_ue.BTNode.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
