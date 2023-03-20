[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTDecorator\_CheckGameplayTagsOnActor

# Class: BTDecorator\_CheckGameplayTagsOnActor

[ue/ue](../modules/ue_ue.md).BTDecorator_CheckGameplayTagsOnActor

## Hierarchy

- [`BTDecorator`](ue_ue.BTDecorator.md)

  ↳ **`BTDecorator_CheckGameplayTagsOnActor`**

## Table of contents

### Constructors

- [constructor](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#constructor)

### Properties

- [ActorToCheck](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#actortocheck)
- [CachedDescription](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#cacheddescription)
- [FlowAbortMode](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#flowabortmode)
- [GameplayTags](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#gameplaytags)
- [NodeName](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#nodename)
- [ParentNode](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#parentnode)
- [TagsToMatch](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#tagstomatch)
- [TreeAsset](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#treeasset)
- [\_\_tid\_BTAuxiliaryNode\_\_](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#__tid_btauxiliarynode__)
- [\_\_tid\_BTDecorator\_CheckGameplayTagsOnActor\_\_](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#__tid_btdecorator_checkgameplaytagsonactor__)
- [\_\_tid\_BTDecorator\_\_](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#__tid_btdecorator__)
- [\_\_tid\_BTNode\_\_](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#__tid_btnode__)
- [\_\_tid\_Object\_\_](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#__tid_object__)
- [bInverseCondition](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#binversecondition)

### Methods

- [CreateDefaultSubobject](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#executeubergraph)
- [GetClass](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#getclass)
- [GetName](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#getname)
- [GetOuter](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#getouter)
- [GetWorld](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#getworld)
- [Find](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#find)
- [Load](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#load)
- [StaticClass](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md#staticclass)

## Constructors

### constructor

• **new BTDecorator_CheckGameplayTagsOnActor**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTDecorator](ue_ue.BTDecorator.md).[constructor](ue_ue.BTDecorator.md#constructor)

## Properties

### ActorToCheck

• **ActorToCheck**: [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md)

___

### CachedDescription

• **CachedDescription**: `string`

___

### FlowAbortMode

• **FlowAbortMode**: [`EBTFlowAbortMode`](../enums/ue_ue.EBTFlowAbortMode.md)

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[FlowAbortMode](ue_ue.BTDecorator.md#flowabortmode)

___

### GameplayTags

• **GameplayTags**: [`GameplayTagContainer`](ue_ue.GameplayTagContainer.md)

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

### TagsToMatch

• **TagsToMatch**: [`EGameplayContainerMatchType`](../enums/ue_ue.EGameplayContainerMatchType.md)

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

### \_\_tid\_BTDecorator\_CheckGameplayTagsOnActor\_\_

• **\_\_tid\_BTDecorator\_CheckGameplayTagsOnActor\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTDecorator_CheckGameplayTagsOnActor`](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTDecorator_CheckGameplayTagsOnActor`](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md)

#### Overrides

[BTDecorator](ue_ue.BTDecorator.md).[Find](ue_ue.BTDecorator.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BTDecorator_CheckGameplayTagsOnActor`](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTDecorator_CheckGameplayTagsOnActor`](ue_ue.BTDecorator_CheckGameplayTagsOnActor.md)

#### Overrides

[BTDecorator](ue_ue.BTDecorator.md).[Load](ue_ue.BTDecorator.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTDecorator](ue_ue.BTDecorator.md).[StaticClass](ue_ue.BTDecorator.md#staticclass)
