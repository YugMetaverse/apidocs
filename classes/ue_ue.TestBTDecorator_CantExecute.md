[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TestBTDecorator\_CantExecute

# Class: TestBTDecorator\_CantExecute

[ue/ue](../modules/ue_ue.md).TestBTDecorator_CantExecute

## Hierarchy

- [`BTDecorator`](ue_ue.BTDecorator.md)

  ↳ **`TestBTDecorator_CantExecute`**

## Table of contents

### Constructors

- [constructor](ue_ue.TestBTDecorator_CantExecute.md#constructor)

### Properties

- [FlowAbortMode](ue_ue.TestBTDecorator_CantExecute.md#flowabortmode)
- [NodeName](ue_ue.TestBTDecorator_CantExecute.md#nodename)
- [ParentNode](ue_ue.TestBTDecorator_CantExecute.md#parentnode)
- [TreeAsset](ue_ue.TestBTDecorator_CantExecute.md#treeasset)
- [\_\_tid\_BTAuxiliaryNode\_\_](ue_ue.TestBTDecorator_CantExecute.md#__tid_btauxiliarynode__)
- [\_\_tid\_BTDecorator\_\_](ue_ue.TestBTDecorator_CantExecute.md#__tid_btdecorator__)
- [\_\_tid\_BTNode\_\_](ue_ue.TestBTDecorator_CantExecute.md#__tid_btnode__)
- [\_\_tid\_Object\_\_](ue_ue.TestBTDecorator_CantExecute.md#__tid_object__)
- [\_\_tid\_TestBTDecorator\_CantExecute\_\_](ue_ue.TestBTDecorator_CantExecute.md#__tid_testbtdecorator_cantexecute__)
- [bInverseCondition](ue_ue.TestBTDecorator_CantExecute.md#binversecondition)

### Methods

- [CreateDefaultSubobject](ue_ue.TestBTDecorator_CantExecute.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TestBTDecorator_CantExecute.md#executeubergraph)
- [GetClass](ue_ue.TestBTDecorator_CantExecute.md#getclass)
- [GetName](ue_ue.TestBTDecorator_CantExecute.md#getname)
- [GetOuter](ue_ue.TestBTDecorator_CantExecute.md#getouter)
- [GetWorld](ue_ue.TestBTDecorator_CantExecute.md#getworld)
- [Find](ue_ue.TestBTDecorator_CantExecute.md#find)
- [Load](ue_ue.TestBTDecorator_CantExecute.md#load)
- [StaticClass](ue_ue.TestBTDecorator_CantExecute.md#staticclass)

## Constructors

### constructor

• **new TestBTDecorator_CantExecute**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTDecorator](ue_ue.BTDecorator.md).[constructor](ue_ue.BTDecorator.md#constructor)

## Properties

### FlowAbortMode

• **FlowAbortMode**: [`EBTFlowAbortMode`](../enums/ue_ue.EBTFlowAbortMode.md)

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[FlowAbortMode](ue_ue.BTDecorator.md#flowabortmode)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[NodeName](ue_ue.BTDecorator.md#nodename)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[ParentNode](ue_ue.BTDecorator.md#parentnode)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[TreeAsset](ue_ue.BTDecorator.md#treeasset)

___

### \_\_tid\_BTAuxiliaryNode\_\_

• **\_\_tid\_BTAuxiliaryNode\_\_**: `boolean`

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[__tid_BTAuxiliaryNode__](ue_ue.BTDecorator.md#__tid_btauxiliarynode__)

___

### \_\_tid\_BTDecorator\_\_

• **\_\_tid\_BTDecorator\_\_**: `boolean`

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[__tid_BTDecorator__](ue_ue.BTDecorator.md#__tid_btdecorator__)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[__tid_BTNode__](ue_ue.BTDecorator.md#__tid_btnode__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[__tid_Object__](ue_ue.BTDecorator.md#__tid_object__)

___

### \_\_tid\_TestBTDecorator\_CantExecute\_\_

• **\_\_tid\_TestBTDecorator\_CantExecute\_\_**: `boolean`

___

### bInverseCondition

• **bInverseCondition**: `boolean`

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[bInverseCondition](ue_ue.BTDecorator.md#binversecondition)

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

[BTDecorator](ue_ue.BTDecorator.md).[CreateDefaultSubobject](ue_ue.BTDecorator.md#createdefaultsubobject)

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

[BTDecorator](ue_ue.BTDecorator.md).[ExecuteUbergraph](ue_ue.BTDecorator.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[GetClass](ue_ue.BTDecorator.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[GetName](ue_ue.BTDecorator.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[GetOuter](ue_ue.BTDecorator.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[GetWorld](ue_ue.BTDecorator.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TestBTDecorator_CantExecute`](ue_ue.TestBTDecorator_CantExecute.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TestBTDecorator_CantExecute`](ue_ue.TestBTDecorator_CantExecute.md)

#### Overrides

[BTDecorator](ue_ue.BTDecorator.md).[Find](ue_ue.BTDecorator.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TestBTDecorator_CantExecute`](ue_ue.TestBTDecorator_CantExecute.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TestBTDecorator_CantExecute`](ue_ue.TestBTDecorator_CantExecute.md)

#### Overrides

[BTDecorator](ue_ue.BTDecorator.md).[Load](ue_ue.BTDecorator.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTDecorator](ue_ue.BTDecorator.md).[StaticClass](ue_ue.BTDecorator.md#staticclass)
