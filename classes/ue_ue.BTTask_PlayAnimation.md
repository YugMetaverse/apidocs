[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTTask\_PlayAnimation

# Class: BTTask\_PlayAnimation

[ue/ue](../modules/ue_ue.md).BTTask_PlayAnimation

## Hierarchy

- [`BTTaskNode`](ue_ue.BTTaskNode.md)

  ↳ **`BTTask_PlayAnimation`**

## Table of contents

### Constructors

- [constructor](ue_ue.BTTask_PlayAnimation.md#constructor)

### Properties

- [AnimationToPlay](ue_ue.BTTask_PlayAnimation.md#animationtoplay)
- [CachedSkelMesh](ue_ue.BTTask_PlayAnimation.md#cachedskelmesh)
- [MyOwnerComp](ue_ue.BTTask_PlayAnimation.md#myownercomp)
- [NodeName](ue_ue.BTTask_PlayAnimation.md#nodename)
- [ParentNode](ue_ue.BTTask_PlayAnimation.md#parentnode)
- [Services](ue_ue.BTTask_PlayAnimation.md#services)
- [TreeAsset](ue_ue.BTTask_PlayAnimation.md#treeasset)
- [\_\_tid\_BTNode\_\_](ue_ue.BTTask_PlayAnimation.md#__tid_btnode__)
- [\_\_tid\_BTTaskNode\_\_](ue_ue.BTTask_PlayAnimation.md#__tid_bttasknode__)
- [\_\_tid\_BTTask\_PlayAnimation\_\_](ue_ue.BTTask_PlayAnimation.md#__tid_bttask_playanimation__)
- [\_\_tid\_Object\_\_](ue_ue.BTTask_PlayAnimation.md#__tid_object__)
- [bIgnoreRestartSelf](ue_ue.BTTask_PlayAnimation.md#bignorerestartself)
- [bLooping](ue_ue.BTTask_PlayAnimation.md#blooping)
- [bNonBlocking](ue_ue.BTTask_PlayAnimation.md#bnonblocking)

### Methods

- [CreateDefaultSubobject](ue_ue.BTTask_PlayAnimation.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTTask_PlayAnimation.md#executeubergraph)
- [GetClass](ue_ue.BTTask_PlayAnimation.md#getclass)
- [GetName](ue_ue.BTTask_PlayAnimation.md#getname)
- [GetOuter](ue_ue.BTTask_PlayAnimation.md#getouter)
- [GetWorld](ue_ue.BTTask_PlayAnimation.md#getworld)
- [Find](ue_ue.BTTask_PlayAnimation.md#find)
- [Load](ue_ue.BTTask_PlayAnimation.md#load)
- [StaticClass](ue_ue.BTTask_PlayAnimation.md#staticclass)

## Constructors

### constructor

• **new BTTask_PlayAnimation**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[constructor](ue_ue.BTTaskNode.md#constructor)

## Properties

### AnimationToPlay

• **AnimationToPlay**: [`AnimationAsset`](ue_ue.AnimationAsset.md)

___

### CachedSkelMesh

• **CachedSkelMesh**: [`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)

___

### MyOwnerComp

• **MyOwnerComp**: [`BehaviorTreeComponent`](ue_ue.BehaviorTreeComponent.md)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[NodeName](ue_ue.BTTaskNode.md#nodename)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[ParentNode](ue_ue.BTTaskNode.md#parentnode)

___

### Services

• **Services**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BTService`](ue_ue.BTService.md)\>

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[Services](ue_ue.BTTaskNode.md#services)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[TreeAsset](ue_ue.BTTaskNode.md#treeasset)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[__tid_BTNode__](ue_ue.BTTaskNode.md#__tid_btnode__)

___

### \_\_tid\_BTTaskNode\_\_

• **\_\_tid\_BTTaskNode\_\_**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[__tid_BTTaskNode__](ue_ue.BTTaskNode.md#__tid_bttasknode__)

___

### \_\_tid\_BTTask\_PlayAnimation\_\_

• **\_\_tid\_BTTask\_PlayAnimation\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[__tid_Object__](ue_ue.BTTaskNode.md#__tid_object__)

___

### bIgnoreRestartSelf

• **bIgnoreRestartSelf**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[bIgnoreRestartSelf](ue_ue.BTTaskNode.md#bignorerestartself)

___

### bLooping

• **bLooping**: `boolean`

___

### bNonBlocking

• **bNonBlocking**: `boolean`

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

[BTTaskNode](ue_ue.BTTaskNode.md).[CreateDefaultSubobject](ue_ue.BTTaskNode.md#createdefaultsubobject)

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

[BTTaskNode](ue_ue.BTTaskNode.md).[ExecuteUbergraph](ue_ue.BTTaskNode.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetClass](ue_ue.BTTaskNode.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetName](ue_ue.BTTaskNode.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetOuter](ue_ue.BTTaskNode.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetWorld](ue_ue.BTTaskNode.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTTask_PlayAnimation`](ue_ue.BTTask_PlayAnimation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTTask_PlayAnimation`](ue_ue.BTTask_PlayAnimation.md)

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[Find](ue_ue.BTTaskNode.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BTTask_PlayAnimation`](ue_ue.BTTask_PlayAnimation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTTask_PlayAnimation`](ue_ue.BTTask_PlayAnimation.md)

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[Load](ue_ue.BTTaskNode.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[StaticClass](ue_ue.BTTaskNode.md#staticclass)
