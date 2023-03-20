[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTService\_DefaultFocus

# Class: BTService\_DefaultFocus

[ue/ue](../modules/ue_ue.md).BTService_DefaultFocus

## Hierarchy

- [`BTService_BlackboardBase`](ue_ue.BTService_BlackboardBase.md)

  ↳ **`BTService_DefaultFocus`**

## Table of contents

### Constructors

- [constructor](ue_ue.BTService_DefaultFocus.md#constructor)

### Properties

- [BlackboardKey](ue_ue.BTService_DefaultFocus.md#blackboardkey)
- [FocusPriority](ue_ue.BTService_DefaultFocus.md#focuspriority)
- [Interval](ue_ue.BTService_DefaultFocus.md#interval)
- [NodeName](ue_ue.BTService_DefaultFocus.md#nodename)
- [ParentNode](ue_ue.BTService_DefaultFocus.md#parentnode)
- [RandomDeviation](ue_ue.BTService_DefaultFocus.md#randomdeviation)
- [TreeAsset](ue_ue.BTService_DefaultFocus.md#treeasset)
- [\_\_tid\_BTAuxiliaryNode\_\_](ue_ue.BTService_DefaultFocus.md#__tid_btauxiliarynode__)
- [\_\_tid\_BTNode\_\_](ue_ue.BTService_DefaultFocus.md#__tid_btnode__)
- [\_\_tid\_BTService\_BlackboardBase\_\_](ue_ue.BTService_DefaultFocus.md#__tid_btservice_blackboardbase__)
- [\_\_tid\_BTService\_DefaultFocus\_\_](ue_ue.BTService_DefaultFocus.md#__tid_btservice_defaultfocus__)
- [\_\_tid\_BTService\_\_](ue_ue.BTService_DefaultFocus.md#__tid_btservice__)
- [\_\_tid\_Object\_\_](ue_ue.BTService_DefaultFocus.md#__tid_object__)
- [bCallTickOnSearchStart](ue_ue.BTService_DefaultFocus.md#bcalltickonsearchstart)
- [bRestartTimerOnEachActivation](ue_ue.BTService_DefaultFocus.md#brestarttimeroneachactivation)

### Methods

- [CreateDefaultSubobject](ue_ue.BTService_DefaultFocus.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTService_DefaultFocus.md#executeubergraph)
- [GetClass](ue_ue.BTService_DefaultFocus.md#getclass)
- [GetName](ue_ue.BTService_DefaultFocus.md#getname)
- [GetOuter](ue_ue.BTService_DefaultFocus.md#getouter)
- [GetWorld](ue_ue.BTService_DefaultFocus.md#getworld)
- [Find](ue_ue.BTService_DefaultFocus.md#find)
- [Load](ue_ue.BTService_DefaultFocus.md#load)
- [StaticClass](ue_ue.BTService_DefaultFocus.md#staticclass)

## Constructors

### constructor

• **new BTService_DefaultFocus**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[constructor](ue_ue.BTService_BlackboardBase.md#constructor)

#### Defined in

[ue/ue.d.ts:25169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25169)

## Properties

### BlackboardKey

• **BlackboardKey**: [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md)

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[BlackboardKey](ue_ue.BTService_BlackboardBase.md#blackboardkey)

#### Defined in

[ue/ue.d.ts:25138](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25138)

___

### FocusPriority

• **FocusPriority**: `number`

#### Defined in

[ue/ue.d.ts:25170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25170)

___

### Interval

• **Interval**: `number`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[Interval](ue_ue.BTService_BlackboardBase.md#interval)

#### Defined in

[ue/ue.d.ts:14588](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14588)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[NodeName](ue_ue.BTService_BlackboardBase.md#nodename)

#### Defined in

[ue/ue.d.ts:14567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14567)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[ParentNode](ue_ue.BTService_BlackboardBase.md#parentnode)

#### Defined in

[ue/ue.d.ts:14569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14569)

___

### RandomDeviation

• **RandomDeviation**: `number`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[RandomDeviation](ue_ue.BTService_BlackboardBase.md#randomdeviation)

#### Defined in

[ue/ue.d.ts:14589](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14589)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[TreeAsset](ue_ue.BTService_BlackboardBase.md#treeasset)

#### Defined in

[ue/ue.d.ts:14568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14568)

___

### \_\_tid\_BTAuxiliaryNode\_\_

• **\_\_tid\_BTAuxiliaryNode\_\_**: `boolean`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[__tid_BTAuxiliaryNode__](ue_ue.BTService_BlackboardBase.md#__tid_btauxiliarynode__)

#### Defined in

[ue/ue.d.ts:14583](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14583)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[__tid_BTNode__](ue_ue.BTService_BlackboardBase.md#__tid_btnode__)

#### Defined in

[ue/ue.d.ts:14574](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14574)

___

### \_\_tid\_BTService\_BlackboardBase\_\_

• **\_\_tid\_BTService\_BlackboardBase\_\_**: `boolean`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[__tid_BTService_BlackboardBase__](ue_ue.BTService_BlackboardBase.md#__tid_btservice_blackboardbase__)

#### Defined in

[ue/ue.d.ts:25143](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25143)

___

### \_\_tid\_BTService\_DefaultFocus\_\_

• **\_\_tid\_BTService\_DefaultFocus\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:25175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25175)

___

### \_\_tid\_BTService\_\_

• **\_\_tid\_BTService\_\_**: `boolean`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[__tid_BTService__](ue_ue.BTService_BlackboardBase.md#__tid_btservice__)

#### Defined in

[ue/ue.d.ts:14596](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14596)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[__tid_Object__](ue_ue.BTService_BlackboardBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bCallTickOnSearchStart

• **bCallTickOnSearchStart**: `boolean`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[bCallTickOnSearchStart](ue_ue.BTService_BlackboardBase.md#bcalltickonsearchstart)

#### Defined in

[ue/ue.d.ts:14590](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14590)

___

### bRestartTimerOnEachActivation

• **bRestartTimerOnEachActivation**: `boolean`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[bRestartTimerOnEachActivation](ue_ue.BTService_BlackboardBase.md#brestarttimeroneachactivation)

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

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[CreateDefaultSubobject](ue_ue.BTService_BlackboardBase.md#createdefaultsubobject)

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

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[ExecuteUbergraph](ue_ue.BTService_BlackboardBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[GetClass](ue_ue.BTService_BlackboardBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[GetName](ue_ue.BTService_BlackboardBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[GetOuter](ue_ue.BTService_BlackboardBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[GetWorld](ue_ue.BTService_BlackboardBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTService_DefaultFocus`](ue_ue.BTService_DefaultFocus.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTService_DefaultFocus`](ue_ue.BTService_DefaultFocus.md)

#### Overrides

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[Find](ue_ue.BTService_BlackboardBase.md#find)

#### Defined in

[ue/ue.d.ts:25172](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25172)

___

### Load

▸ `Static` **Load**(`InName`): [`BTService_DefaultFocus`](ue_ue.BTService_DefaultFocus.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTService_DefaultFocus`](ue_ue.BTService_DefaultFocus.md)

#### Overrides

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[Load](ue_ue.BTService_BlackboardBase.md#load)

#### Defined in

[ue/ue.d.ts:25173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25173)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[StaticClass](ue_ue.BTService_BlackboardBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:25171](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25171)