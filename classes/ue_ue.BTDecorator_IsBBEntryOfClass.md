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

#### Defined in

[ue/ue.d.ts:25021](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25021)

## Properties

### BlackboardKey

• **BlackboardKey**: [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md)

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[BlackboardKey](ue_ue.BTDecorator_BlackboardBase.md#blackboardkey)

#### Defined in

[ue/ue.d.ts:24861](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24861)

___

### FlowAbortMode

• **FlowAbortMode**: [`EBTFlowAbortMode`](../enums/ue_ue.EBTFlowAbortMode.md)

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[FlowAbortMode](ue_ue.BTDecorator_BlackboardBase.md#flowabortmode)

#### Defined in

[ue/ue.d.ts:14614](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14614)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[NodeName](ue_ue.BTDecorator_BlackboardBase.md#nodename)

#### Defined in

[ue/ue.d.ts:14567](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14567)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[ParentNode](ue_ue.BTDecorator_BlackboardBase.md#parentnode)

#### Defined in

[ue/ue.d.ts:14569](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14569)

___

### TestClass

• **TestClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:25022](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25022)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[TreeAsset](ue_ue.BTDecorator_BlackboardBase.md#treeasset)

#### Defined in

[ue/ue.d.ts:14568](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14568)

___

### \_\_tid\_BTAuxiliaryNode\_\_

• **\_\_tid\_BTAuxiliaryNode\_\_**: `boolean`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[__tid_BTAuxiliaryNode__](ue_ue.BTDecorator_BlackboardBase.md#__tid_btauxiliarynode__)

#### Defined in

[ue/ue.d.ts:14583](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14583)

___

### \_\_tid\_BTDecorator\_BlackboardBase\_\_

• **\_\_tid\_BTDecorator\_BlackboardBase\_\_**: `boolean`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[__tid_BTDecorator_BlackboardBase__](ue_ue.BTDecorator_BlackboardBase.md#__tid_btdecorator_blackboardbase__)

#### Defined in

[ue/ue.d.ts:24866](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24866)

___

### \_\_tid\_BTDecorator\_IsBBEntryOfClass\_\_

• **\_\_tid\_BTDecorator\_IsBBEntryOfClass\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:25027](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25027)

___

### \_\_tid\_BTDecorator\_\_

• **\_\_tid\_BTDecorator\_\_**: `boolean`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[__tid_BTDecorator__](ue_ue.BTDecorator_BlackboardBase.md#__tid_btdecorator__)

#### Defined in

[ue/ue.d.ts:14619](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14619)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[__tid_BTNode__](ue_ue.BTDecorator_BlackboardBase.md#__tid_btnode__)

#### Defined in

[ue/ue.d.ts:14574](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14574)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[__tid_Object__](ue_ue.BTDecorator_BlackboardBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bInverseCondition

• **bInverseCondition**: `boolean`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[bInverseCondition](ue_ue.BTDecorator_BlackboardBase.md#binversecondition)

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

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[CreateDefaultSubobject](ue_ue.BTDecorator_BlackboardBase.md#createdefaultsubobject)

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

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[ExecuteUbergraph](ue_ue.BTDecorator_BlackboardBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[GetClass](ue_ue.BTDecorator_BlackboardBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[GetName](ue_ue.BTDecorator_BlackboardBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[GetOuter](ue_ue.BTDecorator_BlackboardBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[GetWorld](ue_ue.BTDecorator_BlackboardBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:25024](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25024)

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

#### Defined in

[ue/ue.d.ts:25025](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25025)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[StaticClass](ue_ue.BTDecorator_BlackboardBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:25023](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25023)
