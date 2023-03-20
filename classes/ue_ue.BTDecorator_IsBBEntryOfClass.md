[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTDecorator\_IsBBEntryOfClass

# Class: BTDecorator\_IsBBEntryOfClass

[ue/ue](../modules/ue_ue.md).BTDecorator_IsBBEntryOfClass

## Hierarchy

- [`BTDecorator_BlackboardBase`](ue_ue.BTDecorator_BlackboardBase.md)

  ↳ **`BTDecorator_IsBBEntryOfClass`**

## Table of contents

### Constructors

- [constructor](ue_ue.BTDecorator_IsBBEntryOfClass.md#constructor)

### Properties

- [BlackboardKey](ue_ue.BTDecorator_IsBBEntryOfClass.md#blackboardkey)
- [FlowAbortMode](ue_ue.BTDecorator_IsBBEntryOfClass.md#flowabortmode)
- [NodeName](ue_ue.BTDecorator_IsBBEntryOfClass.md#nodename)
- [ParentNode](ue_ue.BTDecorator_IsBBEntryOfClass.md#parentnode)
- [TestClass](ue_ue.BTDecorator_IsBBEntryOfClass.md#testclass)
- [TreeAsset](ue_ue.BTDecorator_IsBBEntryOfClass.md#treeasset)
- [\_\_tid\_BTAuxiliaryNode\_\_](ue_ue.BTDecorator_IsBBEntryOfClass.md#__tid_btauxiliarynode__)
- [\_\_tid\_BTDecorator\_BlackboardBase\_\_](ue_ue.BTDecorator_IsBBEntryOfClass.md#__tid_btdecorator_blackboardbase__)
- [\_\_tid\_BTDecorator\_IsBBEntryOfClass\_\_](ue_ue.BTDecorator_IsBBEntryOfClass.md#__tid_btdecorator_isbbentryofclass__)
- [\_\_tid\_BTDecorator\_\_](ue_ue.BTDecorator_IsBBEntryOfClass.md#__tid_btdecorator__)
- [\_\_tid\_BTNode\_\_](ue_ue.BTDecorator_IsBBEntryOfClass.md#__tid_btnode__)
- [\_\_tid\_Object\_\_](ue_ue.BTDecorator_IsBBEntryOfClass.md#__tid_object__)
- [bInverseCondition](ue_ue.BTDecorator_IsBBEntryOfClass.md#binversecondition)

### Methods

- [CreateDefaultSubobject](ue_ue.BTDecorator_IsBBEntryOfClass.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTDecorator_IsBBEntryOfClass.md#executeubergraph)
- [GetClass](ue_ue.BTDecorator_IsBBEntryOfClass.md#getclass)
- [GetName](ue_ue.BTDecorator_IsBBEntryOfClass.md#getname)
- [GetOuter](ue_ue.BTDecorator_IsBBEntryOfClass.md#getouter)
- [GetWorld](ue_ue.BTDecorator_IsBBEntryOfClass.md#getworld)
- [Find](ue_ue.BTDecorator_IsBBEntryOfClass.md#find)
- [Load](ue_ue.BTDecorator_IsBBEntryOfClass.md#load)
- [StaticClass](ue_ue.BTDecorator_IsBBEntryOfClass.md#staticclass)

## Constructors

### constructor

• **new BTDecorator_IsBBEntryOfClass**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[constructor](ue_ue.BTDecorator_BlackboardBase.md#constructor)

## Properties

### BlackboardKey

• **BlackboardKey**: [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md)

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[BlackboardKey](ue_ue.BTDecorator_BlackboardBase.md#blackboardkey)

___

### FlowAbortMode

• **FlowAbortMode**: [`EBTFlowAbortMode`](../enums/ue_ue.EBTFlowAbortMode.md)

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[FlowAbortMode](ue_ue.BTDecorator_BlackboardBase.md#flowabortmode)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[NodeName](ue_ue.BTDecorator_BlackboardBase.md#nodename)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[ParentNode](ue_ue.BTDecorator_BlackboardBase.md#parentnode)

___

### TestClass

• **TestClass**: [`Class`](ue_ue.Class.md)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[TreeAsset](ue_ue.BTDecorator_BlackboardBase.md#treeasset)

___

### \_\_tid\_BTAuxiliaryNode\_\_

• **\_\_tid\_BTAuxiliaryNode\_\_**: `boolean`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[__tid_BTAuxiliaryNode__](ue_ue.BTDecorator_BlackboardBase.md#__tid_btauxiliarynode__)

___

### \_\_tid\_BTDecorator\_BlackboardBase\_\_

• **\_\_tid\_BTDecorator\_BlackboardBase\_\_**: `boolean`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[__tid_BTDecorator_BlackboardBase__](ue_ue.BTDecorator_BlackboardBase.md#__tid_btdecorator_blackboardbase__)

___

### \_\_tid\_BTDecorator\_IsBBEntryOfClass\_\_

• **\_\_tid\_BTDecorator\_IsBBEntryOfClass\_\_**: `boolean`

___

### \_\_tid\_BTDecorator\_\_

• **\_\_tid\_BTDecorator\_\_**: `boolean`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[__tid_BTDecorator__](ue_ue.BTDecorator_BlackboardBase.md#__tid_btdecorator__)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[__tid_BTNode__](ue_ue.BTDecorator_BlackboardBase.md#__tid_btnode__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[__tid_Object__](ue_ue.BTDecorator_BlackboardBase.md#__tid_object__)

___

### bInverseCondition

• **bInverseCondition**: `boolean`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[bInverseCondition](ue_ue.BTDecorator_BlackboardBase.md#binversecondition)

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

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[CreateDefaultSubobject](ue_ue.BTDecorator_BlackboardBase.md#createdefaultsubobject)

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

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[ExecuteUbergraph](ue_ue.BTDecorator_BlackboardBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[GetClass](ue_ue.BTDecorator_BlackboardBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[GetName](ue_ue.BTDecorator_BlackboardBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[GetOuter](ue_ue.BTDecorator_BlackboardBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[GetWorld](ue_ue.BTDecorator_BlackboardBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTDecorator_IsBBEntryOfClass`](ue_ue.BTDecorator_IsBBEntryOfClass.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTDecorator_IsBBEntryOfClass`](ue_ue.BTDecorator_IsBBEntryOfClass.md)

#### Overrides

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[Find](ue_ue.BTDecorator_BlackboardBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BTDecorator_IsBBEntryOfClass`](ue_ue.BTDecorator_IsBBEntryOfClass.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTDecorator_IsBBEntryOfClass`](ue_ue.BTDecorator_IsBBEntryOfClass.md)

#### Overrides

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[Load](ue_ue.BTDecorator_BlackboardBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[StaticClass](ue_ue.BTDecorator_BlackboardBase.md#staticclass)
