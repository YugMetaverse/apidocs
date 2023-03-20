[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTTask\_BlackboardBase

# Class: BTTask\_BlackboardBase

[ue/ue](../modules/ue_ue.md).BTTask_BlackboardBase

## Hierarchy

- [`BTTaskNode`](ue_ue.BTTaskNode.md)

  ↳ **`BTTask_BlackboardBase`**

  ↳↳ [`BTTask_MoveTo`](ue_ue.BTTask_MoveTo.md)

  ↳↳ [`BTTask_RotateToFaceBBEntry`](ue_ue.BTTask_RotateToFaceBBEntry.md)

  ↳↳ [`BTTask_RunEQSQuery`](ue_ue.BTTask_RunEQSQuery.md)

## Table of contents

### Constructors

- [constructor](ue_ue.BTTask_BlackboardBase.md#constructor)

### Properties

- [BlackboardKey](ue_ue.BTTask_BlackboardBase.md#blackboardkey)
- [NodeName](ue_ue.BTTask_BlackboardBase.md#nodename)
- [ParentNode](ue_ue.BTTask_BlackboardBase.md#parentnode)
- [Services](ue_ue.BTTask_BlackboardBase.md#services)
- [TreeAsset](ue_ue.BTTask_BlackboardBase.md#treeasset)
- [\_\_tid\_BTNode\_\_](ue_ue.BTTask_BlackboardBase.md#__tid_btnode__)
- [\_\_tid\_BTTaskNode\_\_](ue_ue.BTTask_BlackboardBase.md#__tid_bttasknode__)
- [\_\_tid\_BTTask\_BlackboardBase\_\_](ue_ue.BTTask_BlackboardBase.md#__tid_bttask_blackboardbase__)
- [\_\_tid\_Object\_\_](ue_ue.BTTask_BlackboardBase.md#__tid_object__)
- [bIgnoreRestartSelf](ue_ue.BTTask_BlackboardBase.md#bignorerestartself)

### Methods

- [CreateDefaultSubobject](ue_ue.BTTask_BlackboardBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTTask_BlackboardBase.md#executeubergraph)
- [GetClass](ue_ue.BTTask_BlackboardBase.md#getclass)
- [GetName](ue_ue.BTTask_BlackboardBase.md#getname)
- [GetOuter](ue_ue.BTTask_BlackboardBase.md#getouter)
- [GetWorld](ue_ue.BTTask_BlackboardBase.md#getworld)
- [Find](ue_ue.BTTask_BlackboardBase.md#find)
- [Load](ue_ue.BTTask_BlackboardBase.md#load)
- [StaticClass](ue_ue.BTTask_BlackboardBase.md#staticclass)

## Constructors

### constructor

• **new BTTask_BlackboardBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[constructor](ue_ue.BTTaskNode.md#constructor)

## Properties

### BlackboardKey

• **BlackboardKey**: [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md)

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

### \_\_tid\_BTTask\_BlackboardBase\_\_

• **\_\_tid\_BTTask\_BlackboardBase\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTTask_BlackboardBase`](ue_ue.BTTask_BlackboardBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTTask_BlackboardBase`](ue_ue.BTTask_BlackboardBase.md)

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[Find](ue_ue.BTTaskNode.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BTTask_BlackboardBase`](ue_ue.BTTask_BlackboardBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTTask_BlackboardBase`](ue_ue.BTTask_BlackboardBase.md)

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[Load](ue_ue.BTTaskNode.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[StaticClass](ue_ue.BTTaskNode.md#staticclass)
