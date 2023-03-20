[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTDecorator\_ConeCheck

# Class: BTDecorator\_ConeCheck

[ue/ue](../modules/ue_ue.md).BTDecorator_ConeCheck

## Hierarchy

- [`BTDecorator`](ue_ue.BTDecorator.md)

  ↳ **`BTDecorator_ConeCheck`**

## Table of contents

### Constructors

- [constructor](ue_ue.BTDecorator_ConeCheck.md#constructor)

### Properties

- [ConeDirection](ue_ue.BTDecorator_ConeCheck.md#conedirection)
- [ConeHalfAngle](ue_ue.BTDecorator_ConeCheck.md#conehalfangle)
- [ConeOrigin](ue_ue.BTDecorator_ConeCheck.md#coneorigin)
- [FlowAbortMode](ue_ue.BTDecorator_ConeCheck.md#flowabortmode)
- [NodeName](ue_ue.BTDecorator_ConeCheck.md#nodename)
- [Observed](ue_ue.BTDecorator_ConeCheck.md#observed)
- [ParentNode](ue_ue.BTDecorator_ConeCheck.md#parentnode)
- [TreeAsset](ue_ue.BTDecorator_ConeCheck.md#treeasset)
- [\_\_tid\_BTAuxiliaryNode\_\_](ue_ue.BTDecorator_ConeCheck.md#__tid_btauxiliarynode__)
- [\_\_tid\_BTDecorator\_ConeCheck\_\_](ue_ue.BTDecorator_ConeCheck.md#__tid_btdecorator_conecheck__)
- [\_\_tid\_BTDecorator\_\_](ue_ue.BTDecorator_ConeCheck.md#__tid_btdecorator__)
- [\_\_tid\_BTNode\_\_](ue_ue.BTDecorator_ConeCheck.md#__tid_btnode__)
- [\_\_tid\_Object\_\_](ue_ue.BTDecorator_ConeCheck.md#__tid_object__)
- [bInverseCondition](ue_ue.BTDecorator_ConeCheck.md#binversecondition)

### Methods

- [CreateDefaultSubobject](ue_ue.BTDecorator_ConeCheck.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTDecorator_ConeCheck.md#executeubergraph)
- [GetClass](ue_ue.BTDecorator_ConeCheck.md#getclass)
- [GetName](ue_ue.BTDecorator_ConeCheck.md#getname)
- [GetOuter](ue_ue.BTDecorator_ConeCheck.md#getouter)
- [GetWorld](ue_ue.BTDecorator_ConeCheck.md#getworld)
- [Find](ue_ue.BTDecorator_ConeCheck.md#find)
- [Load](ue_ue.BTDecorator_ConeCheck.md#load)
- [StaticClass](ue_ue.BTDecorator_ConeCheck.md#staticclass)

## Constructors

### constructor

• **new BTDecorator_ConeCheck**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTDecorator](ue_ue.BTDecorator.md).[constructor](ue_ue.BTDecorator.md#constructor)

## Properties

### ConeDirection

• **ConeDirection**: [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md)

___

### ConeHalfAngle

• **ConeHalfAngle**: `number`

___

### ConeOrigin

• **ConeOrigin**: [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md)

___

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

### Observed

• **Observed**: [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md)

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

### \_\_tid\_BTDecorator\_ConeCheck\_\_

• **\_\_tid\_BTDecorator\_ConeCheck\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTDecorator_ConeCheck`](ue_ue.BTDecorator_ConeCheck.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTDecorator_ConeCheck`](ue_ue.BTDecorator_ConeCheck.md)

#### Overrides

[BTDecorator](ue_ue.BTDecorator.md).[Find](ue_ue.BTDecorator.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BTDecorator_ConeCheck`](ue_ue.BTDecorator_ConeCheck.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTDecorator_ConeCheck`](ue_ue.BTDecorator_ConeCheck.md)

#### Overrides

[BTDecorator](ue_ue.BTDecorator.md).[Load](ue_ue.BTDecorator.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTDecorator](ue_ue.BTDecorator.md).[StaticClass](ue_ue.BTDecorator.md#staticclass)
