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

#### Defined in

[ue/ue.d.ts:14612](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14612)

## Properties

### FlowAbortMode

• **FlowAbortMode**: [`EBTFlowAbortMode`](../enums/ue_ue.EBTFlowAbortMode.md)

#### Defined in

[ue/ue.d.ts:14614](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14614)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[NodeName](ue_ue.BTAuxiliaryNode.md#nodename)

#### Defined in

[ue/ue.d.ts:14567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14567)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[ParentNode](ue_ue.BTAuxiliaryNode.md#parentnode)

#### Defined in

[ue/ue.d.ts:14569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14569)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[TreeAsset](ue_ue.BTAuxiliaryNode.md#treeasset)

#### Defined in

[ue/ue.d.ts:14568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14568)

___

### \_\_tid\_BTAuxiliaryNode\_\_

• **\_\_tid\_BTAuxiliaryNode\_\_**: `boolean`

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[__tid_BTAuxiliaryNode__](ue_ue.BTAuxiliaryNode.md#__tid_btauxiliarynode__)

#### Defined in

[ue/ue.d.ts:14583](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14583)

___

### \_\_tid\_BTDecorator\_\_

• **\_\_tid\_BTDecorator\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:14619](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14619)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[__tid_BTNode__](ue_ue.BTAuxiliaryNode.md#__tid_btnode__)

#### Defined in

[ue/ue.d.ts:14574](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14574)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[__tid_Object__](ue_ue.BTAuxiliaryNode.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bInverseCondition

• **bInverseCondition**: `boolean`

#### Defined in

[ue/ue.d.ts:14613](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14613)

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

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[ExecuteUbergraph](ue_ue.BTAuxiliaryNode.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[GetClass](ue_ue.BTAuxiliaryNode.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[GetName](ue_ue.BTAuxiliaryNode.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[GetOuter](ue_ue.BTAuxiliaryNode.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[GetWorld](ue_ue.BTAuxiliaryNode.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:14616](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14616)

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

#### Defined in

[ue/ue.d.ts:14617](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14617)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[StaticClass](ue_ue.BTAuxiliaryNode.md#staticclass)

#### Defined in

[ue/ue.d.ts:14615](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14615)
