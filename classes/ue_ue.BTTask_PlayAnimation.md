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

#### Defined in

[ue/ue.d.ts:25340](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25340)

## Properties

### AnimationToPlay

• **AnimationToPlay**: [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Defined in

[ue/ue.d.ts:25341](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25341)

___

### CachedSkelMesh

• **CachedSkelMesh**: [`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)

#### Defined in

[ue/ue.d.ts:25345](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25345)

___

### MyOwnerComp

• **MyOwnerComp**: [`BehaviorTreeComponent`](ue_ue.BehaviorTreeComponent.md)

#### Defined in

[ue/ue.d.ts:25344](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25344)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[NodeName](ue_ue.BTTaskNode.md#nodename)

#### Defined in

[ue/ue.d.ts:14567](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14567)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[ParentNode](ue_ue.BTTaskNode.md#parentnode)

#### Defined in

[ue/ue.d.ts:14569](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14569)

___

### Services

• **Services**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BTService`](ue_ue.BTService.md)\>

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[Services](ue_ue.BTTaskNode.md#services)

#### Defined in

[ue/ue.d.ts:14601](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14601)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[TreeAsset](ue_ue.BTTaskNode.md#treeasset)

#### Defined in

[ue/ue.d.ts:14568](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14568)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[__tid_BTNode__](ue_ue.BTTaskNode.md#__tid_btnode__)

#### Defined in

[ue/ue.d.ts:14574](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14574)

___

### \_\_tid\_BTTaskNode\_\_

• **\_\_tid\_BTTaskNode\_\_**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[__tid_BTTaskNode__](ue_ue.BTTaskNode.md#__tid_bttasknode__)

#### Defined in

[ue/ue.d.ts:14607](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14607)

___

### \_\_tid\_BTTask\_PlayAnimation\_\_

• **\_\_tid\_BTTask\_PlayAnimation\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:25350](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25350)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[__tid_Object__](ue_ue.BTTaskNode.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bIgnoreRestartSelf

• **bIgnoreRestartSelf**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[bIgnoreRestartSelf](ue_ue.BTTaskNode.md#bignorerestartself)

#### Defined in

[ue/ue.d.ts:14602](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14602)

___

### bLooping

• **bLooping**: `boolean`

#### Defined in

[ue/ue.d.ts:25342](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25342)

___

### bNonBlocking

• **bNonBlocking**: `boolean`

#### Defined in

[ue/ue.d.ts:25343](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25343)

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

[BTTaskNode](ue_ue.BTTaskNode.md).[ExecuteUbergraph](ue_ue.BTTaskNode.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetClass](ue_ue.BTTaskNode.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetName](ue_ue.BTTaskNode.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetOuter](ue_ue.BTTaskNode.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetWorld](ue_ue.BTTaskNode.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:25347](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25347)

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

#### Defined in

[ue/ue.d.ts:25348](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25348)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[StaticClass](ue_ue.BTTaskNode.md#staticclass)

#### Defined in

[ue/ue.d.ts:25346](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25346)
