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

## Properties

### BlackboardKey

• **BlackboardKey**: [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md)

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[BlackboardKey](ue_ue.BTService_BlackboardBase.md#blackboardkey)

___

### FocusPriority

• **FocusPriority**: `number`

___

### Interval

• **Interval**: `number`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[Interval](ue_ue.BTService_BlackboardBase.md#interval)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[NodeName](ue_ue.BTService_BlackboardBase.md#nodename)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[ParentNode](ue_ue.BTService_BlackboardBase.md#parentnode)

___

### RandomDeviation

• **RandomDeviation**: `number`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[RandomDeviation](ue_ue.BTService_BlackboardBase.md#randomdeviation)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[TreeAsset](ue_ue.BTService_BlackboardBase.md#treeasset)

___

### \_\_tid\_BTAuxiliaryNode\_\_

• **\_\_tid\_BTAuxiliaryNode\_\_**: `boolean`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[__tid_BTAuxiliaryNode__](ue_ue.BTService_BlackboardBase.md#__tid_btauxiliarynode__)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[__tid_BTNode__](ue_ue.BTService_BlackboardBase.md#__tid_btnode__)

___

### \_\_tid\_BTService\_BlackboardBase\_\_

• **\_\_tid\_BTService\_BlackboardBase\_\_**: `boolean`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[__tid_BTService_BlackboardBase__](ue_ue.BTService_BlackboardBase.md#__tid_btservice_blackboardbase__)

___

### \_\_tid\_BTService\_DefaultFocus\_\_

• **\_\_tid\_BTService\_DefaultFocus\_\_**: `boolean`

___

### \_\_tid\_BTService\_\_

• **\_\_tid\_BTService\_\_**: `boolean`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[__tid_BTService__](ue_ue.BTService_BlackboardBase.md#__tid_btservice__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[__tid_Object__](ue_ue.BTService_BlackboardBase.md#__tid_object__)

___

### bCallTickOnSearchStart

• **bCallTickOnSearchStart**: `boolean`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[bCallTickOnSearchStart](ue_ue.BTService_BlackboardBase.md#bcalltickonsearchstart)

___

### bRestartTimerOnEachActivation

• **bRestartTimerOnEachActivation**: `boolean`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[bRestartTimerOnEachActivation](ue_ue.BTService_BlackboardBase.md#brestarttimeroneachactivation)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[GetClass](ue_ue.BTService_BlackboardBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[GetName](ue_ue.BTService_BlackboardBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[GetOuter](ue_ue.BTService_BlackboardBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[GetWorld](ue_ue.BTService_BlackboardBase.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTService_BlackboardBase](ue_ue.BTService_BlackboardBase.md).[StaticClass](ue_ue.BTService_BlackboardBase.md#staticclass)
