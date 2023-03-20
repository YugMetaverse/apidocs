[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTService\_BlackboardBase

# Class: BTService\_BlackboardBase

[ue/ue](../modules/ue_ue.md).BTService_BlackboardBase

## Hierarchy

- [`BTService`](ue_ue.BTService.md)

  ↳ **`BTService_BlackboardBase`**

  ↳↳ [`BTService_DefaultFocus`](ue_ue.BTService_DefaultFocus.md)

  ↳↳ [`BTService_RunEQS`](ue_ue.BTService_RunEQS.md)

## Table of contents

### Constructors

- [constructor](ue_ue.BTService_BlackboardBase.md#constructor)

### Properties

- [BlackboardKey](ue_ue.BTService_BlackboardBase.md#blackboardkey)
- [Interval](ue_ue.BTService_BlackboardBase.md#interval)
- [NodeName](ue_ue.BTService_BlackboardBase.md#nodename)
- [ParentNode](ue_ue.BTService_BlackboardBase.md#parentnode)
- [RandomDeviation](ue_ue.BTService_BlackboardBase.md#randomdeviation)
- [TreeAsset](ue_ue.BTService_BlackboardBase.md#treeasset)
- [\_\_tid\_BTAuxiliaryNode\_\_](ue_ue.BTService_BlackboardBase.md#__tid_btauxiliarynode__)
- [\_\_tid\_BTNode\_\_](ue_ue.BTService_BlackboardBase.md#__tid_btnode__)
- [\_\_tid\_BTService\_BlackboardBase\_\_](ue_ue.BTService_BlackboardBase.md#__tid_btservice_blackboardbase__)
- [\_\_tid\_BTService\_\_](ue_ue.BTService_BlackboardBase.md#__tid_btservice__)
- [\_\_tid\_Object\_\_](ue_ue.BTService_BlackboardBase.md#__tid_object__)
- [bCallTickOnSearchStart](ue_ue.BTService_BlackboardBase.md#bcalltickonsearchstart)
- [bRestartTimerOnEachActivation](ue_ue.BTService_BlackboardBase.md#brestarttimeroneachactivation)

### Methods

- [CreateDefaultSubobject](ue_ue.BTService_BlackboardBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTService_BlackboardBase.md#executeubergraph)
- [GetClass](ue_ue.BTService_BlackboardBase.md#getclass)
- [GetName](ue_ue.BTService_BlackboardBase.md#getname)
- [GetOuter](ue_ue.BTService_BlackboardBase.md#getouter)
- [GetWorld](ue_ue.BTService_BlackboardBase.md#getworld)
- [Find](ue_ue.BTService_BlackboardBase.md#find)
- [Load](ue_ue.BTService_BlackboardBase.md#load)
- [StaticClass](ue_ue.BTService_BlackboardBase.md#staticclass)

## Constructors

### constructor

• **new BTService_BlackboardBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTService](ue_ue.BTService.md).[constructor](ue_ue.BTService.md#constructor)

#### Defined in

[ue/ue.d.ts:25137](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25137)

## Properties

### BlackboardKey

• **BlackboardKey**: [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md)

#### Defined in

[ue/ue.d.ts:25138](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25138)

___

### Interval

• **Interval**: `number`

#### Inherited from

[BTService](ue_ue.BTService.md).[Interval](ue_ue.BTService.md#interval)

#### Defined in

[ue/ue.d.ts:14588](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14588)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTService](ue_ue.BTService.md).[NodeName](ue_ue.BTService.md#nodename)

#### Defined in

[ue/ue.d.ts:14567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14567)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTService](ue_ue.BTService.md).[ParentNode](ue_ue.BTService.md#parentnode)

#### Defined in

[ue/ue.d.ts:14569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14569)

___

### RandomDeviation

• **RandomDeviation**: `number`

#### Inherited from

[BTService](ue_ue.BTService.md).[RandomDeviation](ue_ue.BTService.md#randomdeviation)

#### Defined in

[ue/ue.d.ts:14589](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14589)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTService](ue_ue.BTService.md).[TreeAsset](ue_ue.BTService.md#treeasset)

#### Defined in

[ue/ue.d.ts:14568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14568)

___

### \_\_tid\_BTAuxiliaryNode\_\_

• **\_\_tid\_BTAuxiliaryNode\_\_**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[__tid_BTAuxiliaryNode__](ue_ue.BTService.md#__tid_btauxiliarynode__)

#### Defined in

[ue/ue.d.ts:14583](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14583)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[__tid_BTNode__](ue_ue.BTService.md#__tid_btnode__)

#### Defined in

[ue/ue.d.ts:14574](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14574)

___

### \_\_tid\_BTService\_BlackboardBase\_\_

• **\_\_tid\_BTService\_BlackboardBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:25143](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25143)

___

### \_\_tid\_BTService\_\_

• **\_\_tid\_BTService\_\_**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[__tid_BTService__](ue_ue.BTService.md#__tid_btservice__)

#### Defined in

[ue/ue.d.ts:14596](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14596)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[__tid_Object__](ue_ue.BTService.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bCallTickOnSearchStart

• **bCallTickOnSearchStart**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[bCallTickOnSearchStart](ue_ue.BTService.md#bcalltickonsearchstart)

#### Defined in

[ue/ue.d.ts:14590](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14590)

___

### bRestartTimerOnEachActivation

• **bRestartTimerOnEachActivation**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[bRestartTimerOnEachActivation](ue_ue.BTService.md#brestarttimeroneachactivation)

#### Defined in

[ue/ue.d.ts:14591](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14591)

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

[BTService](ue_ue.BTService.md).[CreateDefaultSubobject](ue_ue.BTService.md#createdefaultsubobject)

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

[BTService](ue_ue.BTService.md).[ExecuteUbergraph](ue_ue.BTService.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTService](ue_ue.BTService.md).[GetClass](ue_ue.BTService.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTService](ue_ue.BTService.md).[GetName](ue_ue.BTService.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTService](ue_ue.BTService.md).[GetOuter](ue_ue.BTService.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTService](ue_ue.BTService.md).[GetWorld](ue_ue.BTService.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTService_BlackboardBase`](ue_ue.BTService_BlackboardBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTService_BlackboardBase`](ue_ue.BTService_BlackboardBase.md)

#### Overrides

[BTService](ue_ue.BTService.md).[Find](ue_ue.BTService.md#find)

#### Defined in

[ue/ue.d.ts:25140](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25140)

___

### Load

▸ `Static` **Load**(`InName`): [`BTService_BlackboardBase`](ue_ue.BTService_BlackboardBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTService_BlackboardBase`](ue_ue.BTService_BlackboardBase.md)

#### Overrides

[BTService](ue_ue.BTService.md).[Load](ue_ue.BTService.md#load)

#### Defined in

[ue/ue.d.ts:25141](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25141)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTService](ue_ue.BTService.md).[StaticClass](ue_ue.BTService.md#staticclass)

#### Defined in

[ue/ue.d.ts:25139](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25139)
