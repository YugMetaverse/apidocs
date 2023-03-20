[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTAuxiliaryNode

# Class: BTAuxiliaryNode

[ue/ue](../modules/ue_ue.md).BTAuxiliaryNode

## Hierarchy

- [`BTNode`](ue_ue.BTNode.md)

  ↳ **`BTAuxiliaryNode`**

  ↳↳ [`BTService`](ue_ue.BTService.md)

  ↳↳ [`BTDecorator`](ue_ue.BTDecorator.md)

## Table of contents

### Constructors

- [constructor](ue_ue.BTAuxiliaryNode.md#constructor)

### Properties

- [NodeName](ue_ue.BTAuxiliaryNode.md#nodename)
- [ParentNode](ue_ue.BTAuxiliaryNode.md#parentnode)
- [TreeAsset](ue_ue.BTAuxiliaryNode.md#treeasset)
- [\_\_tid\_BTAuxiliaryNode\_\_](ue_ue.BTAuxiliaryNode.md#__tid_btauxiliarynode__)
- [\_\_tid\_BTNode\_\_](ue_ue.BTAuxiliaryNode.md#__tid_btnode__)
- [\_\_tid\_Object\_\_](ue_ue.BTAuxiliaryNode.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.BTAuxiliaryNode.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTAuxiliaryNode.md#executeubergraph)
- [GetClass](ue_ue.BTAuxiliaryNode.md#getclass)
- [GetName](ue_ue.BTAuxiliaryNode.md#getname)
- [GetOuter](ue_ue.BTAuxiliaryNode.md#getouter)
- [GetWorld](ue_ue.BTAuxiliaryNode.md#getworld)
- [Find](ue_ue.BTAuxiliaryNode.md#find)
- [Load](ue_ue.BTAuxiliaryNode.md#load)
- [StaticClass](ue_ue.BTAuxiliaryNode.md#staticclass)

## Constructors

### constructor

• **new BTAuxiliaryNode**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTNode](ue_ue.BTNode.md).[constructor](ue_ue.BTNode.md#constructor)

## Properties

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTNode](ue_ue.BTNode.md).[NodeName](ue_ue.BTNode.md#nodename)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTNode](ue_ue.BTNode.md).[ParentNode](ue_ue.BTNode.md#parentnode)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTNode](ue_ue.BTNode.md).[TreeAsset](ue_ue.BTNode.md#treeasset)

___

### \_\_tid\_BTAuxiliaryNode\_\_

• **\_\_tid\_BTAuxiliaryNode\_\_**: `boolean`

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTNode](ue_ue.BTNode.md).[__tid_BTNode__](ue_ue.BTNode.md#__tid_btnode__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTNode](ue_ue.BTNode.md).[__tid_Object__](ue_ue.BTNode.md#__tid_object__)

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

[BTNode](ue_ue.BTNode.md).[CreateDefaultSubobject](ue_ue.BTNode.md#createdefaultsubobject)

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

[BTNode](ue_ue.BTNode.md).[ExecuteUbergraph](ue_ue.BTNode.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTNode](ue_ue.BTNode.md).[GetClass](ue_ue.BTNode.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTNode](ue_ue.BTNode.md).[GetName](ue_ue.BTNode.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTNode](ue_ue.BTNode.md).[GetOuter](ue_ue.BTNode.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTNode](ue_ue.BTNode.md).[GetWorld](ue_ue.BTNode.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTAuxiliaryNode`](ue_ue.BTAuxiliaryNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTAuxiliaryNode`](ue_ue.BTAuxiliaryNode.md)

#### Overrides

[BTNode](ue_ue.BTNode.md).[Find](ue_ue.BTNode.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BTAuxiliaryNode`](ue_ue.BTAuxiliaryNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTAuxiliaryNode`](ue_ue.BTAuxiliaryNode.md)

#### Overrides

[BTNode](ue_ue.BTNode.md).[Load](ue_ue.BTNode.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTNode](ue_ue.BTNode.md).[StaticClass](ue_ue.BTNode.md#staticclass)
