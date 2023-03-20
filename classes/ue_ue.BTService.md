[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTService

# Class: BTService

[ue/ue](../modules/ue_ue.md).BTService

## Hierarchy

- [`BTAuxiliaryNode`](ue_ue.BTAuxiliaryNode.md)

  ↳ **`BTService`**

  ↳↳ [`BTService_BlackboardBase`](ue_ue.BTService_BlackboardBase.md)

  ↳↳ [`BTService_BlueprintBase`](ue_ue.BTService_BlueprintBase.md)

  ↳↳ [`TestBTService_Log`](ue_ue.TestBTService_Log.md)

## Table of contents

### Constructors

- [constructor](ue_ue.BTService.md#constructor)

### Properties

- [Interval](ue_ue.BTService.md#interval)
- [NodeName](ue_ue.BTService.md#nodename)
- [ParentNode](ue_ue.BTService.md#parentnode)
- [RandomDeviation](ue_ue.BTService.md#randomdeviation)
- [TreeAsset](ue_ue.BTService.md#treeasset)
- [\_\_tid\_BTAuxiliaryNode\_\_](ue_ue.BTService.md#__tid_btauxiliarynode__)
- [\_\_tid\_BTNode\_\_](ue_ue.BTService.md#__tid_btnode__)
- [\_\_tid\_BTService\_\_](ue_ue.BTService.md#__tid_btservice__)
- [\_\_tid\_Object\_\_](ue_ue.BTService.md#__tid_object__)
- [bCallTickOnSearchStart](ue_ue.BTService.md#bcalltickonsearchstart)
- [bRestartTimerOnEachActivation](ue_ue.BTService.md#brestarttimeroneachactivation)

### Methods

- [CreateDefaultSubobject](ue_ue.BTService.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTService.md#executeubergraph)
- [GetClass](ue_ue.BTService.md#getclass)
- [GetName](ue_ue.BTService.md#getname)
- [GetOuter](ue_ue.BTService.md#getouter)
- [GetWorld](ue_ue.BTService.md#getworld)
- [Find](ue_ue.BTService.md#find)
- [Load](ue_ue.BTService.md#load)
- [StaticClass](ue_ue.BTService.md#staticclass)

## Constructors

### constructor

• **new BTService**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[constructor](ue_ue.BTAuxiliaryNode.md#constructor)

#### Defined in

[ue/ue.d.ts:14587](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14587)

## Properties

### Interval

• **Interval**: `number`

#### Defined in

[ue/ue.d.ts:14588](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14588)

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

### RandomDeviation

• **RandomDeviation**: `number`

#### Defined in

[ue/ue.d.ts:14589](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14589)

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

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[__tid_BTNode__](ue_ue.BTAuxiliaryNode.md#__tid_btnode__)

#### Defined in

[ue/ue.d.ts:14574](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14574)

___

### \_\_tid\_BTService\_\_

• **\_\_tid\_BTService\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:14596](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14596)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[__tid_Object__](ue_ue.BTAuxiliaryNode.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bCallTickOnSearchStart

• **bCallTickOnSearchStart**: `boolean`

#### Defined in

[ue/ue.d.ts:14590](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14590)

___

### bRestartTimerOnEachActivation

• **bRestartTimerOnEachActivation**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTService`](ue_ue.BTService.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTService`](ue_ue.BTService.md)

#### Overrides

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[Find](ue_ue.BTAuxiliaryNode.md#find)

#### Defined in

[ue/ue.d.ts:14593](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14593)

___

### Load

▸ `Static` **Load**(`InName`): [`BTService`](ue_ue.BTService.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTService`](ue_ue.BTService.md)

#### Overrides

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[Load](ue_ue.BTAuxiliaryNode.md#load)

#### Defined in

[ue/ue.d.ts:14594](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14594)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[StaticClass](ue_ue.BTAuxiliaryNode.md#staticclass)

#### Defined in

[ue/ue.d.ts:14592](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14592)
