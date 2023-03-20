[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTComposite\_Sequence

# Class: BTComposite\_Sequence

[ue/ue](../modules/ue_ue.md).BTComposite_Sequence

## Hierarchy

- [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

  ↳ **`BTComposite_Sequence`**

## Table of contents

### Constructors

- [constructor](ue_ue.BTComposite_Sequence.md#constructor)

### Properties

- [Children](ue_ue.BTComposite_Sequence.md#children)
- [NodeName](ue_ue.BTComposite_Sequence.md#nodename)
- [ParentNode](ue_ue.BTComposite_Sequence.md#parentnode)
- [Services](ue_ue.BTComposite_Sequence.md#services)
- [TreeAsset](ue_ue.BTComposite_Sequence.md#treeasset)
- [\_\_tid\_BTCompositeNode\_\_](ue_ue.BTComposite_Sequence.md#__tid_btcompositenode__)
- [\_\_tid\_BTComposite\_Sequence\_\_](ue_ue.BTComposite_Sequence.md#__tid_btcomposite_sequence__)
- [\_\_tid\_BTNode\_\_](ue_ue.BTComposite_Sequence.md#__tid_btnode__)
- [\_\_tid\_Object\_\_](ue_ue.BTComposite_Sequence.md#__tid_object__)
- [bApplyDecoratorScope](ue_ue.BTComposite_Sequence.md#bapplydecoratorscope)

### Methods

- [CreateDefaultSubobject](ue_ue.BTComposite_Sequence.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTComposite_Sequence.md#executeubergraph)
- [GetClass](ue_ue.BTComposite_Sequence.md#getclass)
- [GetName](ue_ue.BTComposite_Sequence.md#getname)
- [GetOuter](ue_ue.BTComposite_Sequence.md#getouter)
- [GetWorld](ue_ue.BTComposite_Sequence.md#getworld)
- [Find](ue_ue.BTComposite_Sequence.md#find)
- [Load](ue_ue.BTComposite_Sequence.md#load)
- [StaticClass](ue_ue.BTComposite_Sequence.md#staticclass)

## Constructors

### constructor

• **new BTComposite_Sequence**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTCompositeNode](ue_ue.BTCompositeNode.md).[constructor](ue_ue.BTCompositeNode.md#constructor)

## Properties

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BTCompositeChild`](ue_ue.BTCompositeChild.md)\>

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[Children](ue_ue.BTCompositeNode.md#children)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[NodeName](ue_ue.BTCompositeNode.md#nodename)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[ParentNode](ue_ue.BTCompositeNode.md#parentnode)

___

### Services

• **Services**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BTService`](ue_ue.BTService.md)\>

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[Services](ue_ue.BTCompositeNode.md#services)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[TreeAsset](ue_ue.BTCompositeNode.md#treeasset)

___

### \_\_tid\_BTCompositeNode\_\_

• **\_\_tid\_BTCompositeNode\_\_**: `boolean`

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[__tid_BTCompositeNode__](ue_ue.BTCompositeNode.md#__tid_btcompositenode__)

___

### \_\_tid\_BTComposite\_Sequence\_\_

• **\_\_tid\_BTComposite\_Sequence\_\_**: `boolean`

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[__tid_BTNode__](ue_ue.BTCompositeNode.md#__tid_btnode__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[__tid_Object__](ue_ue.BTCompositeNode.md#__tid_object__)

___

### bApplyDecoratorScope

• **bApplyDecoratorScope**: `boolean`

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[bApplyDecoratorScope](ue_ue.BTCompositeNode.md#bapplydecoratorscope)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[GetClass](ue_ue.BTCompositeNode.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[GetName](ue_ue.BTCompositeNode.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[GetOuter](ue_ue.BTCompositeNode.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTCompositeNode](ue_ue.BTCompositeNode.md).[GetWorld](ue_ue.BTCompositeNode.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTComposite_Sequence`](ue_ue.BTComposite_Sequence.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTComposite_Sequence`](ue_ue.BTComposite_Sequence.md)

#### Overrides

[BTCompositeNode](ue_ue.BTCompositeNode.md).[Find](ue_ue.BTCompositeNode.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BTComposite_Sequence`](ue_ue.BTComposite_Sequence.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTComposite_Sequence`](ue_ue.BTComposite_Sequence.md)

#### Overrides

[BTCompositeNode](ue_ue.BTCompositeNode.md).[Load](ue_ue.BTCompositeNode.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTCompositeNode](ue_ue.BTCompositeNode.md).[StaticClass](ue_ue.BTCompositeNode.md#staticclass)
