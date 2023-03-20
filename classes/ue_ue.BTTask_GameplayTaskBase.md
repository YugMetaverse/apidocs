[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTTask\_GameplayTaskBase

# Class: BTTask\_GameplayTaskBase

[ue/ue](../modules/ue_ue.md).BTTask_GameplayTaskBase

## Hierarchy

- [`BTTaskNode`](ue_ue.BTTaskNode.md)

  ↳ **`BTTask_GameplayTaskBase`**

## Table of contents

### Constructors

- [constructor](ue_ue.BTTask_GameplayTaskBase.md#constructor)

### Properties

- [NodeName](ue_ue.BTTask_GameplayTaskBase.md#nodename)
- [ParentNode](ue_ue.BTTask_GameplayTaskBase.md#parentnode)
- [Services](ue_ue.BTTask_GameplayTaskBase.md#services)
- [TreeAsset](ue_ue.BTTask_GameplayTaskBase.md#treeasset)
- [\_\_tid\_BTNode\_\_](ue_ue.BTTask_GameplayTaskBase.md#__tid_btnode__)
- [\_\_tid\_BTTaskNode\_\_](ue_ue.BTTask_GameplayTaskBase.md#__tid_bttasknode__)
- [\_\_tid\_BTTask\_GameplayTaskBase\_\_](ue_ue.BTTask_GameplayTaskBase.md#__tid_bttask_gameplaytaskbase__)
- [\_\_tid\_Object\_\_](ue_ue.BTTask_GameplayTaskBase.md#__tid_object__)
- [bIgnoreRestartSelf](ue_ue.BTTask_GameplayTaskBase.md#bignorerestartself)
- [bWaitForGameplayTask](ue_ue.BTTask_GameplayTaskBase.md#bwaitforgameplaytask)

### Methods

- [CreateDefaultSubobject](ue_ue.BTTask_GameplayTaskBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTTask_GameplayTaskBase.md#executeubergraph)
- [GetClass](ue_ue.BTTask_GameplayTaskBase.md#getclass)
- [GetName](ue_ue.BTTask_GameplayTaskBase.md#getname)
- [GetOuter](ue_ue.BTTask_GameplayTaskBase.md#getouter)
- [GetWorld](ue_ue.BTTask_GameplayTaskBase.md#getworld)
- [Find](ue_ue.BTTask_GameplayTaskBase.md#find)
- [Load](ue_ue.BTTask_GameplayTaskBase.md#load)
- [StaticClass](ue_ue.BTTask_GameplayTaskBase.md#staticclass)

## Constructors

### constructor

• **new BTTask_GameplayTaskBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[constructor](ue_ue.BTTaskNode.md#constructor)

#### Defined in

[ue/ue.d.ts:25278](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25278)

## Properties

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

### \_\_tid\_BTTask\_GameplayTaskBase\_\_

• **\_\_tid\_BTTask\_GameplayTaskBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:25284](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25284)

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

### bWaitForGameplayTask

• **bWaitForGameplayTask**: `boolean`

#### Defined in

[ue/ue.d.ts:25279](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25279)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTTask_GameplayTaskBase`](ue_ue.BTTask_GameplayTaskBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTTask_GameplayTaskBase`](ue_ue.BTTask_GameplayTaskBase.md)

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[Find](ue_ue.BTTaskNode.md#find)

#### Defined in

[ue/ue.d.ts:25281](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25281)

___

### Load

▸ `Static` **Load**(`InName`): [`BTTask_GameplayTaskBase`](ue_ue.BTTask_GameplayTaskBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTTask_GameplayTaskBase`](ue_ue.BTTask_GameplayTaskBase.md)

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[Load](ue_ue.BTTaskNode.md#load)

#### Defined in

[ue/ue.d.ts:25282](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25282)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[StaticClass](ue_ue.BTTaskNode.md#staticclass)

#### Defined in

[ue/ue.d.ts:25280](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25280)
