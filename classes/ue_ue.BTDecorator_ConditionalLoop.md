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

#### Defined in

[ue/ue.d.ts:24949](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24949)

## Properties

### ArithmeticOperation

• **ArithmeticOperation**: [`EArithmeticKeyOperation`](../enums/ue_ue.EArithmeticKeyOperation.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[ArithmeticOperation](ue_ue.BTDecorator_Blackboard.md#arithmeticoperation)

#### Defined in

[ue/ue.d.ts:24882](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24882)

___

### BasicOperation

• **BasicOperation**: [`EBasicKeyOperation`](../enums/ue_ue.EBasicKeyOperation.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[BasicOperation](ue_ue.BTDecorator_Blackboard.md#basicoperation)

#### Defined in

[ue/ue.d.ts:24881](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24881)

___

### BlackboardKey

• **BlackboardKey**: [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[BlackboardKey](ue_ue.BTDecorator_Blackboard.md#blackboardkey)

#### Defined in

[ue/ue.d.ts:24861](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24861)

___

### CachedDescription

• **CachedDescription**: `string`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[CachedDescription](ue_ue.BTDecorator_Blackboard.md#cacheddescription)

#### Defined in

[ue/ue.d.ts:24878](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24878)

___

### FloatValue

• **FloatValue**: `number`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[FloatValue](ue_ue.BTDecorator_Blackboard.md#floatvalue)

#### Defined in

[ue/ue.d.ts:24876](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24876)

___

### FlowAbortMode

• **FlowAbortMode**: [`EBTFlowAbortMode`](../enums/ue_ue.EBTFlowAbortMode.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[FlowAbortMode](ue_ue.BTDecorator_Blackboard.md#flowabortmode)

#### Defined in

[ue/ue.d.ts:14614](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14614)

___

### IntValue

• **IntValue**: `number`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[IntValue](ue_ue.BTDecorator_Blackboard.md#intvalue)

#### Defined in

[ue/ue.d.ts:24875](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24875)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[NodeName](ue_ue.BTDecorator_Blackboard.md#nodename)

#### Defined in

[ue/ue.d.ts:14567](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14567)

___

### NotifyObserver

• **NotifyObserver**: [`EBTBlackboardRestart`](../enums/ue_ue.EBTBlackboardRestart.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[NotifyObserver](ue_ue.BTDecorator_Blackboard.md#notifyobserver)

#### Defined in

[ue/ue.d.ts:24880](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24880)

___

### OperationType

• **OperationType**: `number`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[OperationType](ue_ue.BTDecorator_Blackboard.md#operationtype)

#### Defined in

[ue/ue.d.ts:24879](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24879)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[ParentNode](ue_ue.BTDecorator_Blackboard.md#parentnode)

#### Defined in

[ue/ue.d.ts:14569](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14569)

___

### StringValue

• **StringValue**: `string`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[StringValue](ue_ue.BTDecorator_Blackboard.md#stringvalue)

#### Defined in

[ue/ue.d.ts:24877](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24877)

___

### TextOperation

• **TextOperation**: [`ETextKeyOperation`](../enums/ue_ue.ETextKeyOperation.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[TextOperation](ue_ue.BTDecorator_Blackboard.md#textoperation)

#### Defined in

[ue/ue.d.ts:24883](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24883)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[TreeAsset](ue_ue.BTDecorator_Blackboard.md#treeasset)

#### Defined in

[ue/ue.d.ts:14568](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14568)

___

### \_\_tid\_BTAuxiliaryNode\_\_

• **\_\_tid\_BTAuxiliaryNode\_\_**: `boolean`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[__tid_BTAuxiliaryNode__](ue_ue.BTDecorator_Blackboard.md#__tid_btauxiliarynode__)

#### Defined in

[ue/ue.d.ts:14583](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14583)

___

### \_\_tid\_BTDecorator\_BlackboardBase\_\_

• **\_\_tid\_BTDecorator\_BlackboardBase\_\_**: `boolean`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[__tid_BTDecorator_BlackboardBase__](ue_ue.BTDecorator_Blackboard.md#__tid_btdecorator_blackboardbase__)

#### Defined in

[ue/ue.d.ts:24866](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24866)

___

### \_\_tid\_BTDecorator\_Blackboard\_\_

• **\_\_tid\_BTDecorator\_Blackboard\_\_**: `boolean`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[__tid_BTDecorator_Blackboard__](ue_ue.BTDecorator_Blackboard.md#__tid_btdecorator_blackboard__)

#### Defined in

[ue/ue.d.ts:24888](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24888)

___

### \_\_tid\_BTDecorator\_ConditionalLoop\_\_

• **\_\_tid\_BTDecorator\_ConditionalLoop\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:24954](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24954)

___

### \_\_tid\_BTDecorator\_\_

• **\_\_tid\_BTDecorator\_\_**: `boolean`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[__tid_BTDecorator__](ue_ue.BTDecorator_Blackboard.md#__tid_btdecorator__)

#### Defined in

[ue/ue.d.ts:14619](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14619)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[__tid_BTNode__](ue_ue.BTDecorator_Blackboard.md#__tid_btnode__)

#### Defined in

[ue/ue.d.ts:14574](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14574)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[__tid_Object__](ue_ue.BTDecorator_Blackboard.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bInverseCondition

• **bInverseCondition**: `boolean`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[bInverseCondition](ue_ue.BTDecorator_Blackboard.md#binversecondition)

#### Defined in

[ue/ue.d.ts:14613](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14613)

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

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[ExecuteUbergraph](ue_ue.BTDecorator_Blackboard.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[GetClass](ue_ue.BTDecorator_Blackboard.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[GetName](ue_ue.BTDecorator_Blackboard.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[GetOuter](ue_ue.BTDecorator_Blackboard.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[GetWorld](ue_ue.BTDecorator_Blackboard.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:24951](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24951)

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

#### Defined in

[ue/ue.d.ts:24952](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24952)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTDecorator_Blackboard](ue_ue.BTDecorator_Blackboard.md).[StaticClass](ue_ue.BTDecorator_Blackboard.md#staticclass)

#### Defined in

[ue/ue.d.ts:24950](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24950)
