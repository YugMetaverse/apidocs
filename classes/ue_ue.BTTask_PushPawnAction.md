[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTTask\_PushPawnAction

# Class: BTTask\_PushPawnAction

[ue/ue](../modules/ue_ue.md).BTTask_PushPawnAction

## Hierarchy

- [`BTTask_PawnActionBase`](ue_ue.BTTask_PawnActionBase.md)

  ↳ **`BTTask_PushPawnAction`**

## Table of contents

### Constructors

- [constructor](ue_ue.BTTask_PushPawnAction.md#constructor)

### Properties

- [Action](ue_ue.BTTask_PushPawnAction.md#action)
- [NodeName](ue_ue.BTTask_PushPawnAction.md#nodename)
- [ParentNode](ue_ue.BTTask_PushPawnAction.md#parentnode)
- [Services](ue_ue.BTTask_PushPawnAction.md#services)
- [TreeAsset](ue_ue.BTTask_PushPawnAction.md#treeasset)
- [\_\_tid\_BTNode\_\_](ue_ue.BTTask_PushPawnAction.md#__tid_btnode__)
- [\_\_tid\_BTTaskNode\_\_](ue_ue.BTTask_PushPawnAction.md#__tid_bttasknode__)
- [\_\_tid\_BTTask\_PawnActionBase\_\_](ue_ue.BTTask_PushPawnAction.md#__tid_bttask_pawnactionbase__)
- [\_\_tid\_BTTask\_PushPawnAction\_\_](ue_ue.BTTask_PushPawnAction.md#__tid_bttask_pushpawnaction__)
- [\_\_tid\_Object\_\_](ue_ue.BTTask_PushPawnAction.md#__tid_object__)
- [bIgnoreRestartSelf](ue_ue.BTTask_PushPawnAction.md#bignorerestartself)

### Methods

- [CreateDefaultSubobject](ue_ue.BTTask_PushPawnAction.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTTask_PushPawnAction.md#executeubergraph)
- [GetClass](ue_ue.BTTask_PushPawnAction.md#getclass)
- [GetName](ue_ue.BTTask_PushPawnAction.md#getname)
- [GetOuter](ue_ue.BTTask_PushPawnAction.md#getouter)
- [GetWorld](ue_ue.BTTask_PushPawnAction.md#getworld)
- [Find](ue_ue.BTTask_PushPawnAction.md#find)
- [Load](ue_ue.BTTask_PushPawnAction.md#load)
- [StaticClass](ue_ue.BTTask_PushPawnAction.md#staticclass)

## Constructors

### constructor

• **new BTTask_PushPawnAction**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTTask_PawnActionBase](ue_ue.BTTask_PawnActionBase.md).[constructor](ue_ue.BTTask_PawnActionBase.md#constructor)

## Properties

### Action

• **Action**: [`PawnAction`](ue_ue.PawnAction.md)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTTask_PawnActionBase](ue_ue.BTTask_PawnActionBase.md).[NodeName](ue_ue.BTTask_PawnActionBase.md#nodename)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTTask_PawnActionBase](ue_ue.BTTask_PawnActionBase.md).[ParentNode](ue_ue.BTTask_PawnActionBase.md#parentnode)

___

### Services

• **Services**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BTService`](ue_ue.BTService.md)\>

#### Inherited from

[BTTask_PawnActionBase](ue_ue.BTTask_PawnActionBase.md).[Services](ue_ue.BTTask_PawnActionBase.md#services)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTTask_PawnActionBase](ue_ue.BTTask_PawnActionBase.md).[TreeAsset](ue_ue.BTTask_PawnActionBase.md#treeasset)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTTask_PawnActionBase](ue_ue.BTTask_PawnActionBase.md).[__tid_BTNode__](ue_ue.BTTask_PawnActionBase.md#__tid_btnode__)

___

### \_\_tid\_BTTaskNode\_\_

• **\_\_tid\_BTTaskNode\_\_**: `boolean`

#### Inherited from

[BTTask_PawnActionBase](ue_ue.BTTask_PawnActionBase.md).[__tid_BTTaskNode__](ue_ue.BTTask_PawnActionBase.md#__tid_bttasknode__)

___

### \_\_tid\_BTTask\_PawnActionBase\_\_

• **\_\_tid\_BTTask\_PawnActionBase\_\_**: `boolean`

#### Inherited from

[BTTask_PawnActionBase](ue_ue.BTTask_PawnActionBase.md).[__tid_BTTask_PawnActionBase__](ue_ue.BTTask_PawnActionBase.md#__tid_bttask_pawnactionbase__)

___

### \_\_tid\_BTTask\_PushPawnAction\_\_

• **\_\_tid\_BTTask\_PushPawnAction\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTTask_PawnActionBase](ue_ue.BTTask_PawnActionBase.md).[__tid_Object__](ue_ue.BTTask_PawnActionBase.md#__tid_object__)

___

### bIgnoreRestartSelf

• **bIgnoreRestartSelf**: `boolean`

#### Inherited from

[BTTask_PawnActionBase](ue_ue.BTTask_PawnActionBase.md).[bIgnoreRestartSelf](ue_ue.BTTask_PawnActionBase.md#bignorerestartself)

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

[BTTask_PawnActionBase](ue_ue.BTTask_PawnActionBase.md).[CreateDefaultSubobject](ue_ue.BTTask_PawnActionBase.md#createdefaultsubobject)

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

[BTTask_PawnActionBase](ue_ue.BTTask_PawnActionBase.md).[ExecuteUbergraph](ue_ue.BTTask_PawnActionBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTTask_PawnActionBase](ue_ue.BTTask_PawnActionBase.md).[GetClass](ue_ue.BTTask_PawnActionBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTTask_PawnActionBase](ue_ue.BTTask_PawnActionBase.md).[GetName](ue_ue.BTTask_PawnActionBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTTask_PawnActionBase](ue_ue.BTTask_PawnActionBase.md).[GetOuter](ue_ue.BTTask_PawnActionBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTTask_PawnActionBase](ue_ue.BTTask_PawnActionBase.md).[GetWorld](ue_ue.BTTask_PawnActionBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTTask_PushPawnAction`](ue_ue.BTTask_PushPawnAction.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTTask_PushPawnAction`](ue_ue.BTTask_PushPawnAction.md)

#### Overrides

[BTTask_PawnActionBase](ue_ue.BTTask_PawnActionBase.md).[Find](ue_ue.BTTask_PawnActionBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BTTask_PushPawnAction`](ue_ue.BTTask_PushPawnAction.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTTask_PushPawnAction`](ue_ue.BTTask_PushPawnAction.md)

#### Overrides

[BTTask_PawnActionBase](ue_ue.BTTask_PawnActionBase.md).[Load](ue_ue.BTTask_PawnActionBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTTask_PawnActionBase](ue_ue.BTTask_PawnActionBase.md).[StaticClass](ue_ue.BTTask_PawnActionBase.md#staticclass)
