[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTComposite\_Selector

# Class: BTComposite\_Selector

[ue/ue](../modules/ue_ue.md).BTComposite_Selector

## Hierarchy

- [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

  ↳ **`BTComposite_Selector`**

## Table of contents

### Constructors

- [constructor](ue_ue.BTComposite_Selector.md#constructor)

### Properties

- [Children](ue_ue.BTComposite_Selector.md#children)
- [NodeName](ue_ue.BTComposite_Selector.md#nodename)
- [ParentNode](ue_ue.BTComposite_Selector.md#parentnode)
- [Services](ue_ue.BTComposite_Selector.md#services)
- [TreeAsset](ue_ue.BTComposite_Selector.md#treeasset)
- [\_\_tid\_BTCompositeNode\_\_](ue_ue.BTComposite_Selector.md#__tid_btcompositenode__)
- [\_\_tid\_BTComposite\_Selector\_\_](ue_ue.BTComposite_Selector.md#__tid_btcomposite_selector__)
- [\_\_tid\_BTNode\_\_](ue_ue.BTComposite_Selector.md#__tid_btnode__)
- [\_\_tid\_Object\_\_](ue_ue.BTComposite_Selector.md#__tid_object__)
- [bApplyDecoratorScope](ue_ue.BTComposite_Selector.md#bapplydecoratorscope)

### Methods

- [CreateDefaultSubobject](ue_ue.BTComposite_Selector.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTComposite_Selector.md#executeubergraph)
- [GetClass](ue_ue.BTComposite_Selector.md#getclass)
- [GetName](ue_ue.BTComposite_Selector.md#getname)
- [GetOuter](ue_ue.BTComposite_Selector.md#getouter)
- [GetWorld](ue_ue.BTComposite_Selector.md#getworld)
- [Find](ue_ue.BTComposite_Selector.md#find)
- [Load](ue_ue.BTComposite_Selector.md#load)
- [StaticClass](ue_ue.BTComposite_Selector.md#staticclass)

## Constructors

### constructor

• **new BTComposite_Selector**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTCompositeNode](ue_ue.BTCompositeNode.md).[constructor](ue_ue.BTCompositeNode.md#constructor)

#### Defined in

[ue/ue.d.ts:24815](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24815)

## Properties

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BTCompositeChild`](ue_ue.BTCompositeChild.md)\>

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[Children](ue_ue.BTCompositeNode.md#children)

#### Defined in

[ue/ue.d.ts:14653](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14653)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[NodeName](ue_ue.BTCompositeNode.md#nodename)

#### Defined in

[ue/ue.d.ts:14567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14567)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[ParentNode](ue_ue.BTCompositeNode.md#parentnode)

#### Defined in

[ue/ue.d.ts:14569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14569)

___

### Services

• **Services**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BTService`](ue_ue.BTService.md)\>

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[Services](ue_ue.BTCompositeNode.md#services)

#### Defined in

[ue/ue.d.ts:14654](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14654)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[TreeAsset](ue_ue.BTCompositeNode.md#treeasset)

#### Defined in

[ue/ue.d.ts:14568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14568)

___

### \_\_tid\_BTCompositeNode\_\_

• **\_\_tid\_BTCompositeNode\_\_**: `boolean`

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[__tid_BTCompositeNode__](ue_ue.BTCompositeNode.md#__tid_btcompositenode__)

#### Defined in

[ue/ue.d.ts:14660](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14660)

___

### \_\_tid\_BTComposite\_Selector\_\_

• **\_\_tid\_BTComposite\_Selector\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:24820](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24820)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[__tid_BTNode__](ue_ue.BTCompositeNode.md#__tid_btnode__)

#### Defined in

[ue/ue.d.ts:14574](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14574)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[__tid_Object__](ue_ue.BTCompositeNode.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bApplyDecoratorScope

• **bApplyDecoratorScope**: `boolean`

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[bApplyDecoratorScope](ue_ue.BTCompositeNode.md#bapplydecoratorscope)

#### Defined in

[ue/ue.d.ts:14655](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14655)

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

[BTCompositeNode](ue_ue.BTCompositeNode.md).[CreateDefaultSubobject](ue_ue.BTCompositeNode.md#createdefaultsubobject)

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

[BTCompositeNode](ue_ue.BTCompositeNode.md).[ExecuteUbergraph](ue_ue.BTCompositeNode.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[GetClass](ue_ue.BTCompositeNode.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[GetName](ue_ue.BTCompositeNode.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[GetOuter](ue_ue.BTCompositeNode.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[GetWorld](ue_ue.BTCompositeNode.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTComposite_Selector`](ue_ue.BTComposite_Selector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTComposite_Selector`](ue_ue.BTComposite_Selector.md)

#### Overrides

[BTCompositeNode](ue_ue.BTCompositeNode.md).[Find](ue_ue.BTCompositeNode.md#find)

#### Defined in

[ue/ue.d.ts:24817](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24817)

___

### Load

▸ `Static` **Load**(`InName`): [`BTComposite_Selector`](ue_ue.BTComposite_Selector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTComposite_Selector`](ue_ue.BTComposite_Selector.md)

#### Overrides

[BTCompositeNode](ue_ue.BTCompositeNode.md).[Load](ue_ue.BTCompositeNode.md#load)

#### Defined in

[ue/ue.d.ts:24818](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24818)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTCompositeNode](ue_ue.BTCompositeNode.md).[StaticClass](ue_ue.BTCompositeNode.md#staticclass)

#### Defined in

[ue/ue.d.ts:24816](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24816)
