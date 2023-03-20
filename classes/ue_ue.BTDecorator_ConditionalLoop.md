[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTDecorator\_ConditionalLoop

# Class: BTDecorator\_ConditionalLoop

[ue/ue](../modules/ue_ue.md).BTDecorator_ConditionalLoop

## Hierarchy

- [`BTDecorator_Blackboard`](ue_ue.BTDecorator_Blackboard.md)

  ↳ **`BTDecorator_ConditionalLoop`**

## Table of contents

### Constructors

- [constructor](ue_ue.BTDecorator_ConditionalLoop.md#constructor)

### Properties

- [ArithmeticOperation](ue_ue.BTDecorator_ConditionalLoop.md#arithmeticoperation)
- [BasicOperation](ue_ue.BTDecorator_ConditionalLoop.md#basicoperation)
- [BlackboardKey](ue_ue.BTDecorator_ConditionalLoop.md#blackboardkey)
- [CachedDescription](ue_ue.BTDecorator_ConditionalLoop.md#cacheddescription)
- [FloatValue](ue_ue.BTDecorator_ConditionalLoop.md#floatvalue)
- [FlowAbortMode](ue_ue.BTDecorator_ConditionalLoop.md#flowabortmode)
- [IntValue](ue_ue.BTDecorator_ConditionalLoop.md#intvalue)
- [NodeName](ue_ue.BTDecorator_ConditionalLoop.md#nodename)
- [NotifyObserver](ue_ue.BTDecorator_ConditionalLoop.md#notifyobserver)
- [OperationType](ue_ue.BTDecorator_ConditionalLoop.md#operationtype)
- [ParentNode](ue_ue.BTDecorator_ConditionalLoop.md#parentnode)
- [StringValue](ue_ue.BTDecorator_ConditionalLoop.md#stringvalue)
- [TextOperation](ue_ue.BTDecorator_ConditionalLoop.md#textoperation)
- [TreeAsset](ue_ue.BTDecorator_ConditionalLoop.md#treeasset)
- [\_\_tid\_BTAuxiliaryNode\_\_](ue_ue.BTDecorator_ConditionalLoop.md#__tid_btauxiliarynode__)
- [\_\_tid\_BTDecorator\_BlackboardBase\_\_](ue_ue.BTDecorator_ConditionalLoop.md#__tid_btdecorator_blackboardbase__)
- [\_\_tid\_BTDecorator\_Blackboard\_\_](ue_ue.BTDecorator_ConditionalLoop.md#__tid_btdecorator_blackboard__)
- [\_\_tid\_BTDecorator\_ConditionalLoop\_\_](ue_ue.BTDecorator_ConditionalLoop.md#__tid_btdecorator_conditionalloop__)
- [\_\_tid\_BTDecorator\_\_](ue_ue.BTDecorator_ConditionalLoop.md#__tid_btdecorator__)
- [\_\_tid\_BTNode\_\_](ue_ue.BTDecorator_ConditionalLoop.md#__tid_btnode__)
- [\_\_tid\_Object\_\_](ue_ue.BTDecorator_ConditionalLoop.md#__tid_object__)
- [bInverseCondition](ue_ue.BTDecorator_ConditionalLoop.md#binversecondition)

### Methods

- [CreateDefaultSubobject](ue_ue.BTDecorator_ConditionalLoop.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTDecorator_ConditionalLoop.md#executeubergraph)
- [GetClass](ue_ue.BTDecorator_ConditionalLoop.md#getclass)
- [GetName](ue_ue.BTDecorator_ConditionalLoop.md#getname)
- [GetOuter](ue_ue.BTDecorator_ConditionalLoop.md#getouter)
- [GetWorld](ue_ue.BTDecorator_ConditionalLoop.md#getworld)
- [Find](ue_ue.BTDecorator_ConditionalLoop.md#find)
- [Load](ue_ue.BTDecorator_ConditionalLoop.md#load)
- [StaticClass](ue_ue.BTDecorator_ConditionalLoop.md#staticclass)

## Constructors

### constructor

• **new BTDecorator_ConditionalLoop**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[constructor](ue_ue.BTDecorator_Blackboard.md#constructor)

## Properties

### ArithmeticOperation

• **ArithmeticOperation**: [`EArithmeticKeyOperation`](../enums/ue_ue.EArithmeticKeyOperation.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[ArithmeticOperation](ue_ue.BTDecorator_Blackboard.md#arithmeticoperation)

___

### BasicOperation

• **BasicOperation**: [`EBasicKeyOperation`](../enums/ue_ue.EBasicKeyOperation.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[BasicOperation](ue_ue.BTDecorator_Blackboard.md#basicoperation)

___

### BlackboardKey

• **BlackboardKey**: [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[BlackboardKey](ue_ue.BTDecorator_Blackboard.md#blackboardkey)

___

### CachedDescription

• **CachedDescription**: `string`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[CachedDescription](ue_ue.BTDecorator_Blackboard.md#cacheddescription)

___

### FloatValue

• **FloatValue**: `number`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[FloatValue](ue_ue.BTDecorator_Blackboard.md#floatvalue)

___

### FlowAbortMode

• **FlowAbortMode**: [`EBTFlowAbortMode`](../enums/ue_ue.EBTFlowAbortMode.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[FlowAbortMode](ue_ue.BTDecorator_Blackboard.md#flowabortmode)

___

### IntValue

• **IntValue**: `number`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[IntValue](ue_ue.BTDecorator_Blackboard.md#intvalue)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[NodeName](ue_ue.BTDecorator_Blackboard.md#nodename)

___

### NotifyObserver

• **NotifyObserver**: [`EBTBlackboardRestart`](../enums/ue_ue.EBTBlackboardRestart.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[NotifyObserver](ue_ue.BTDecorator_Blackboard.md#notifyobserver)

___

### OperationType

• **OperationType**: `number`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[OperationType](ue_ue.BTDecorator_Blackboard.md#operationtype)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[ParentNode](ue_ue.BTDecorator_Blackboard.md#parentnode)

___

### StringValue

• **StringValue**: `string`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[StringValue](ue_ue.BTDecorator_Blackboard.md#stringvalue)

___

### TextOperation

• **TextOperation**: [`ETextKeyOperation`](../enums/ue_ue.ETextKeyOperation.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[TextOperation](ue_ue.BTDecorator_Blackboard.md#textoperation)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[TreeAsset](ue_ue.BTDecorator_Blackboard.md#treeasset)

___

### \_\_tid\_BTAuxiliaryNode\_\_

• **\_\_tid\_BTAuxiliaryNode\_\_**: `boolean`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[__tid_BTAuxiliaryNode__](ue_ue.BTDecorator_Blackboard.md#__tid_btauxiliarynode__)

___

### \_\_tid\_BTDecorator\_BlackboardBase\_\_

• **\_\_tid\_BTDecorator\_BlackboardBase\_\_**: `boolean`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[__tid_BTDecorator_BlackboardBase__](ue_ue.BTDecorator_Blackboard.md#__tid_btdecorator_blackboardbase__)

___

### \_\_tid\_BTDecorator\_Blackboard\_\_

• **\_\_tid\_BTDecorator\_Blackboard\_\_**: `boolean`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[__tid_BTDecorator_Blackboard__](ue_ue.BTDecorator_Blackboard.md#__tid_btdecorator_blackboard__)

___

### \_\_tid\_BTDecorator\_ConditionalLoop\_\_

• **\_\_tid\_BTDecorator\_ConditionalLoop\_\_**: `boolean`

___

### \_\_tid\_BTDecorator\_\_

• **\_\_tid\_BTDecorator\_\_**: `boolean`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[__tid_BTDecorator__](ue_ue.BTDecorator_Blackboard.md#__tid_btdecorator__)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[__tid_BTNode__](ue_ue.BTDecorator_Blackboard.md#__tid_btnode__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[__tid_Object__](ue_ue.BTDecorator_Blackboard.md#__tid_object__)

___

### bInverseCondition

• **bInverseCondition**: `boolean`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[bInverseCondition](ue_ue.BTDecorator_Blackboard.md#binversecondition)

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

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[CreateDefaultSubobject](ue_ue.BTDecorator_Blackboard.md#createdefaultsubobject)

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

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[ExecuteUbergraph](ue_ue.BTDecorator_Blackboard.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[GetClass](ue_ue.BTDecorator_Blackboard.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[GetName](ue_ue.BTDecorator_Blackboard.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[GetOuter](ue_ue.BTDecorator_Blackboard.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[GetWorld](ue_ue.BTDecorator_Blackboard.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTDecorator_ConditionalLoop`](ue_ue.BTDecorator_ConditionalLoop.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTDecorator_ConditionalLoop`](ue_ue.BTDecorator_ConditionalLoop.md)

#### Overrides

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[Find](ue_ue.BTDecorator_Blackboard.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BTDecorator_ConditionalLoop`](ue_ue.BTDecorator_ConditionalLoop.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTDecorator_ConditionalLoop`](ue_ue.BTDecorator_ConditionalLoop.md)

#### Overrides

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[Load](ue_ue.BTDecorator_Blackboard.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[StaticClass](ue_ue.BTDecorator_Blackboard.md#staticclass)
