[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTTask\_WaitBlackboardTime

# Class: BTTask\_WaitBlackboardTime

[ue/ue](../modules/ue_ue.md).BTTask_WaitBlackboardTime

## Hierarchy

- [`BTTask_Wait`](ue_ue.BTTask_Wait.md)

  ↳ **`BTTask_WaitBlackboardTime`**

## Table of contents

### Constructors

- [constructor](ue_ue.BTTask_WaitBlackboardTime.md#constructor)

### Properties

- [BlackboardKey](ue_ue.BTTask_WaitBlackboardTime.md#blackboardkey)
- [NodeName](ue_ue.BTTask_WaitBlackboardTime.md#nodename)
- [ParentNode](ue_ue.BTTask_WaitBlackboardTime.md#parentnode)
- [RandomDeviation](ue_ue.BTTask_WaitBlackboardTime.md#randomdeviation)
- [Services](ue_ue.BTTask_WaitBlackboardTime.md#services)
- [TreeAsset](ue_ue.BTTask_WaitBlackboardTime.md#treeasset)
- [WaitTime](ue_ue.BTTask_WaitBlackboardTime.md#waittime)
- [\_\_tid\_BTNode\_\_](ue_ue.BTTask_WaitBlackboardTime.md#__tid_btnode__)
- [\_\_tid\_BTTaskNode\_\_](ue_ue.BTTask_WaitBlackboardTime.md#__tid_bttasknode__)
- [\_\_tid\_BTTask\_WaitBlackboardTime\_\_](ue_ue.BTTask_WaitBlackboardTime.md#__tid_bttask_waitblackboardtime__)
- [\_\_tid\_BTTask\_Wait\_\_](ue_ue.BTTask_WaitBlackboardTime.md#__tid_bttask_wait__)
- [\_\_tid\_Object\_\_](ue_ue.BTTask_WaitBlackboardTime.md#__tid_object__)
- [bIgnoreRestartSelf](ue_ue.BTTask_WaitBlackboardTime.md#bignorerestartself)

### Methods

- [CreateDefaultSubobject](ue_ue.BTTask_WaitBlackboardTime.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTTask_WaitBlackboardTime.md#executeubergraph)
- [GetClass](ue_ue.BTTask_WaitBlackboardTime.md#getclass)
- [GetName](ue_ue.BTTask_WaitBlackboardTime.md#getname)
- [GetOuter](ue_ue.BTTask_WaitBlackboardTime.md#getouter)
- [GetWorld](ue_ue.BTTask_WaitBlackboardTime.md#getworld)
- [Find](ue_ue.BTTask_WaitBlackboardTime.md#find)
- [Load](ue_ue.BTTask_WaitBlackboardTime.md#load)
- [StaticClass](ue_ue.BTTask_WaitBlackboardTime.md#staticclass)

## Constructors

### constructor

• **new BTTask_WaitBlackboardTime**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTTask_Wait](ue_ue.BTTask_Wait.md).[constructor](ue_ue.BTTask_Wait.md#constructor)

#### Defined in

[ue/ue.d.ts:25459](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25459)

## Properties

### BlackboardKey

• **BlackboardKey**: [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md)

#### Defined in

[ue/ue.d.ts:25460](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25460)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTTask_Wait](ue_ue.BTTask_Wait.md).[NodeName](ue_ue.BTTask_Wait.md#nodename)

#### Defined in

[ue/ue.d.ts:14567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14567)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTTask_Wait](ue_ue.BTTask_Wait.md).[ParentNode](ue_ue.BTTask_Wait.md#parentnode)

#### Defined in

[ue/ue.d.ts:14569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14569)

___

### RandomDeviation

• **RandomDeviation**: `number`

#### Inherited from

[BTTask_Wait](ue_ue.BTTask_Wait.md).[RandomDeviation](ue_ue.BTTask_Wait.md#randomdeviation)

#### Defined in

[ue/ue.d.ts:25450](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25450)

___

### Services

• **Services**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BTService`](ue_ue.BTService.md)\>

#### Inherited from

[BTTask_Wait](ue_ue.BTTask_Wait.md).[Services](ue_ue.BTTask_Wait.md#services)

#### Defined in

[ue/ue.d.ts:14601](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14601)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTTask_Wait](ue_ue.BTTask_Wait.md).[TreeAsset](ue_ue.BTTask_Wait.md#treeasset)

#### Defined in

[ue/ue.d.ts:14568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14568)

___

### WaitTime

• **WaitTime**: `number`

#### Inherited from

[BTTask_Wait](ue_ue.BTTask_Wait.md).[WaitTime](ue_ue.BTTask_Wait.md#waittime)

#### Defined in

[ue/ue.d.ts:25449](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25449)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTTask_Wait](ue_ue.BTTask_Wait.md).[__tid_BTNode__](ue_ue.BTTask_Wait.md#__tid_btnode__)

#### Defined in

[ue/ue.d.ts:14574](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14574)

___

### \_\_tid\_BTTaskNode\_\_

• **\_\_tid\_BTTaskNode\_\_**: `boolean`

#### Inherited from

[BTTask_Wait](ue_ue.BTTask_Wait.md).[__tid_BTTaskNode__](ue_ue.BTTask_Wait.md#__tid_bttasknode__)

#### Defined in

[ue/ue.d.ts:14607](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14607)

___

### \_\_tid\_BTTask\_WaitBlackboardTime\_\_

• **\_\_tid\_BTTask\_WaitBlackboardTime\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:25465](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25465)

___

### \_\_tid\_BTTask\_Wait\_\_

• **\_\_tid\_BTTask\_Wait\_\_**: `boolean`

#### Inherited from

[BTTask_Wait](ue_ue.BTTask_Wait.md).[__tid_BTTask_Wait__](ue_ue.BTTask_Wait.md#__tid_bttask_wait__)

#### Defined in

[ue/ue.d.ts:25455](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25455)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTTask_Wait](ue_ue.BTTask_Wait.md).[__tid_Object__](ue_ue.BTTask_Wait.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bIgnoreRestartSelf

• **bIgnoreRestartSelf**: `boolean`

#### Inherited from

[BTTask_Wait](ue_ue.BTTask_Wait.md).[bIgnoreRestartSelf](ue_ue.BTTask_Wait.md#bignorerestartself)

#### Defined in

[ue/ue.d.ts:14602](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14602)

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

[BTTask_Wait](ue_ue.BTTask_Wait.md).[CreateDefaultSubobject](ue_ue.BTTask_Wait.md#createdefaultsubobject)

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

[BTTask_Wait](ue_ue.BTTask_Wait.md).[ExecuteUbergraph](ue_ue.BTTask_Wait.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTTask_Wait](ue_ue.BTTask_Wait.md).[GetClass](ue_ue.BTTask_Wait.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTTask_Wait](ue_ue.BTTask_Wait.md).[GetName](ue_ue.BTTask_Wait.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTTask_Wait](ue_ue.BTTask_Wait.md).[GetOuter](ue_ue.BTTask_Wait.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTTask_Wait](ue_ue.BTTask_Wait.md).[GetWorld](ue_ue.BTTask_Wait.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTTask_WaitBlackboardTime`](ue_ue.BTTask_WaitBlackboardTime.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTTask_WaitBlackboardTime`](ue_ue.BTTask_WaitBlackboardTime.md)

#### Overrides

[BTTask_Wait](ue_ue.BTTask_Wait.md).[Find](ue_ue.BTTask_Wait.md#find)

#### Defined in

[ue/ue.d.ts:25462](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25462)

___

### Load

▸ `Static` **Load**(`InName`): [`BTTask_WaitBlackboardTime`](ue_ue.BTTask_WaitBlackboardTime.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTTask_WaitBlackboardTime`](ue_ue.BTTask_WaitBlackboardTime.md)

#### Overrides

[BTTask_Wait](ue_ue.BTTask_Wait.md).[Load](ue_ue.BTTask_Wait.md#load)

#### Defined in

[ue/ue.d.ts:25463](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25463)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTTask_Wait](ue_ue.BTTask_Wait.md).[StaticClass](ue_ue.BTTask_Wait.md#staticclass)

#### Defined in

[ue/ue.d.ts:25461](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25461)
