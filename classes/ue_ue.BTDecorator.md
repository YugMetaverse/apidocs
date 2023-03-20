[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTDecorator

# Class: BTDecorator

[ue/ue](../modules/ue_ue.md).BTDecorator

## Hierarchy

- [`BTAuxiliaryNode`](ue_ue.BTAuxiliaryNode.md)

  ↳ **`BTDecorator`**

  ↳↳ [`BTDecorator_BlackboardBase`](ue_ue.BTDecorator_BlackboardBase.md)

  ↳↳ [`BTDecorator_BlueprintBase`](ue_ue.BTDecorator_BlueprintBase.md)

  ↳↳ [`BTDecorator_CheckGameplayTagsOnActor`](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md)

  ↳↳ [`BTDecorator_CompareBBEntries`](ue_ue.BTDecorator_CompareBBEntries.md)

  ↳↳ [`BTDecorator_ConeCheck`](ue_ue.BTDecorator_ConeCheck.md)

  ↳↳ [`BTDecorator_Cooldown`](ue_ue.BTDecorator_Cooldown.md)

  ↳↳ [`BTDecorator_DoesPathExist`](ue_ue.BTDecorator_DoesPathExist.md)

  ↳↳ [`BTDecorator_ForceSuccess`](ue_ue.BTDecorator_ForceSuccess.md)

  ↳↳ [`BTDecorator_KeepInCone`](ue_ue.BTDecorator_KeepInCone.md)

  ↳↳ [`BTDecorator_Loop`](ue_ue.BTDecorator_Loop.md)

  ↳↳ [`BTDecorator_ReachedMoveGoal`](ue_ue.BTDecorator_ReachedMoveGoal.md)

  ↳↳ [`BTDecorator_SetTagCooldown`](ue_ue.BTDecorator_SetTagCooldown.md)

  ↳↳ [`BTDecorator_TagCooldown`](ue_ue.BTDecorator_TagCooldown.md)

  ↳↳ [`BTDecorator_TimeLimit`](ue_ue.BTDecorator_TimeLimit.md)

  ↳↳ [`TestBTDecorator_CantExecute`](ue_ue.TestBTDecorator_CantExecute.md)

  ↳↳ [`TestBTDecorator_DelayedAbort`](ue_ue.TestBTDecorator_DelayedAbort.md)

## Table of contents

### Constructors

- [constructor](ue_ue.BTDecorator.md#constructor)

### Properties

- [FlowAbortMode](ue_ue.BTDecorator.md#flowabortmode)
- [NodeName](ue_ue.BTDecorator.md#nodename)
- [ParentNode](ue_ue.BTDecorator.md#parentnode)
- [TreeAsset](ue_ue.BTDecorator.md#treeasset)
- [\_\_tid\_BTAuxiliaryNode\_\_](ue_ue.BTDecorator.md#__tid_btauxiliarynode__)
- [\_\_tid\_BTDecorator\_\_](ue_ue.BTDecorator.md#__tid_btdecorator__)
- [\_\_tid\_BTNode\_\_](ue_ue.BTDecorator.md#__tid_btnode__)
- [\_\_tid\_Object\_\_](ue_ue.BTDecorator.md#__tid_object__)
- [bInverseCondition](ue_ue.BTDecorator.md#binversecondition)

### Methods

- [CreateDefaultSubobject](ue_ue.BTDecorator.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTDecorator.md#executeubergraph)
- [GetClass](ue_ue.BTDecorator.md#getclass)
- [GetName](ue_ue.BTDecorator.md#getname)
- [GetOuter](ue_ue.BTDecorator.md#getouter)
- [GetWorld](ue_ue.BTDecorator.md#getworld)
- [Find](ue_ue.BTDecorator.md#find)
- [Load](ue_ue.BTDecorator.md#load)
- [StaticClass](ue_ue.BTDecorator.md#staticclass)

## Constructors

### constructor

• **new BTDecorator**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[constructor](ue_ue.BTAuxiliaryNode.md#constructor)

## Properties

### FlowAbortMode

• **FlowAbortMode**: [`EBTFlowAbortMode`](../enums/ue_ue.EBTFlowAbortMode.md)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[NodeName](ue_ue.BTAuxiliaryNode.md#nodename)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[ParentNode](ue_ue.BTAuxiliaryNode.md#parentnode)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[TreeAsset](ue_ue.BTAuxiliaryNode.md#treeasset)

___

### \_\_tid\_BTAuxiliaryNode\_\_

• **\_\_tid\_BTAuxiliaryNode\_\_**: `boolean`

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[__tid_BTAuxiliaryNode__](ue_ue.BTAuxiliaryNode.md#__tid_btauxiliarynode__)

___

### \_\_tid\_BTDecorator\_\_

• **\_\_tid\_BTDecorator\_\_**: `boolean`

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[__tid_BTNode__](ue_ue.BTAuxiliaryNode.md#__tid_btnode__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[__tid_Object__](ue_ue.BTAuxiliaryNode.md#__tid_object__)

___

### bInverseCondition

• **bInverseCondition**: `boolean`

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

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[CreateDefaultSubobject](ue_ue.BTAuxiliaryNode.md#createdefaultsubobject)

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

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[ExecuteUbergraph](ue_ue.BTAuxiliaryNode.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[GetClass](ue_ue.BTAuxiliaryNode.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[GetName](ue_ue.BTAuxiliaryNode.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[GetOuter](ue_ue.BTAuxiliaryNode.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[GetWorld](ue_ue.BTAuxiliaryNode.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTDecorator`](ue_ue.BTDecorator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTDecorator`](ue_ue.BTDecorator.md)

#### Overrides

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[Find](ue_ue.BTAuxiliaryNode.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BTDecorator`](ue_ue.BTDecorator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTDecorator`](ue_ue.BTDecorator.md)

#### Overrides

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[Load](ue_ue.BTAuxiliaryNode.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[StaticClass](ue_ue.BTAuxiliaryNode.md#staticclass)
