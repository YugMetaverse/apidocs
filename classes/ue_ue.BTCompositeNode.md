[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTCompositeNode

# Class: BTCompositeNode

[ue/ue](../modules/ue_ue.md).BTCompositeNode

## Hierarchy

- [`BTNode`](ue_ue.BTNode.md)

  ↳ **`BTCompositeNode`**

  ↳↳ [`BTComposite_Selector`](ue_ue.BTComposite_Selector.md)

  ↳↳ [`BTComposite_Sequence`](ue_ue.BTComposite_Sequence.md)

  ↳↳ [`BTComposite_SimpleParallel`](ue_ue.BTComposite_SimpleParallel.md)

## Table of contents

### Constructors

- [constructor](ue_ue.BTCompositeNode.md#constructor)

### Properties

- [Children](ue_ue.BTCompositeNode.md#children)
- [NodeName](ue_ue.BTCompositeNode.md#nodename)
- [ParentNode](ue_ue.BTCompositeNode.md#parentnode)
- [Services](ue_ue.BTCompositeNode.md#services)
- [TreeAsset](ue_ue.BTCompositeNode.md#treeasset)
- [\_\_tid\_BTCompositeNode\_\_](ue_ue.BTCompositeNode.md#__tid_btcompositenode__)
- [\_\_tid\_BTNode\_\_](ue_ue.BTCompositeNode.md#__tid_btnode__)
- [\_\_tid\_Object\_\_](ue_ue.BTCompositeNode.md#__tid_object__)
- [bApplyDecoratorScope](ue_ue.BTCompositeNode.md#bapplydecoratorscope)

### Methods

- [CreateDefaultSubobject](ue_ue.BTCompositeNode.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTCompositeNode.md#executeubergraph)
- [GetClass](ue_ue.BTCompositeNode.md#getclass)
- [GetName](ue_ue.BTCompositeNode.md#getname)
- [GetOuter](ue_ue.BTCompositeNode.md#getouter)
- [GetWorld](ue_ue.BTCompositeNode.md#getworld)
- [Find](ue_ue.BTCompositeNode.md#find)
- [Load](ue_ue.BTCompositeNode.md#load)
- [StaticClass](ue_ue.BTCompositeNode.md#staticclass)

## Constructors

### constructor

• **new BTCompositeNode**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTNode](ue_ue.BTNode.md).[constructor](ue_ue.BTNode.md#constructor)

#### Defined in

[ue/ue.d.ts:14652](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14652)

## Properties

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BTCompositeChild`](ue_ue.BTCompositeChild.md)\>

#### Defined in

[ue/ue.d.ts:14653](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14653)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTNode](ue_ue.BTNode.md).[NodeName](ue_ue.BTNode.md#nodename)

#### Defined in

[ue/ue.d.ts:14567](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14567)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTNode](ue_ue.BTNode.md).[ParentNode](ue_ue.BTNode.md#parentnode)

#### Defined in

[ue/ue.d.ts:14569](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14569)

___

### Services

• **Services**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BTService`](ue_ue.BTService.md)\>

#### Defined in

[ue/ue.d.ts:14654](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14654)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTNode](ue_ue.BTNode.md).[TreeAsset](ue_ue.BTNode.md#treeasset)

#### Defined in

[ue/ue.d.ts:14568](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14568)

___

### \_\_tid\_BTCompositeNode\_\_

• **\_\_tid\_BTCompositeNode\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:14660](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14660)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTNode](ue_ue.BTNode.md).[__tid_BTNode__](ue_ue.BTNode.md#__tid_btnode__)

#### Defined in

[ue/ue.d.ts:14574](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14574)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTNode](ue_ue.BTNode.md).[__tid_Object__](ue_ue.BTNode.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bApplyDecoratorScope

• **bApplyDecoratorScope**: `boolean`

#### Defined in

[ue/ue.d.ts:14655](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14655)

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

[BTNode](ue_ue.BTNode.md).[CreateDefaultSubobject](ue_ue.BTNode.md#createdefaultsubobject)

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

[BTNode](ue_ue.BTNode.md).[ExecuteUbergraph](ue_ue.BTNode.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTNode](ue_ue.BTNode.md).[GetClass](ue_ue.BTNode.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTNode](ue_ue.BTNode.md).[GetName](ue_ue.BTNode.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTNode](ue_ue.BTNode.md).[GetOuter](ue_ue.BTNode.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTNode](ue_ue.BTNode.md).[GetWorld](ue_ue.BTNode.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Overrides

[BTNode](ue_ue.BTNode.md).[Find](ue_ue.BTNode.md#find)

#### Defined in

[ue/ue.d.ts:14657](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14657)

___

### Load

▸ `Static` **Load**(`InName`): [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Overrides

[BTNode](ue_ue.BTNode.md).[Load](ue_ue.BTNode.md#load)

#### Defined in

[ue/ue.d.ts:14658](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14658)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTNode](ue_ue.BTNode.md).[StaticClass](ue_ue.BTNode.md#staticclass)

#### Defined in

[ue/ue.d.ts:14656](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14656)
