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

## Properties

### Interval

• **Interval**: `number`

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[NodeName](ue_ue.BTAuxiliaryNode.md#nodename)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[ParentNode](ue_ue.BTAuxiliaryNode.md#parentnode)

___

### RandomDeviation

• **RandomDeviation**: `number`

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[TreeAsset](ue_ue.BTAuxiliaryNode.md#treeasset)

___

### \_\_tid\_BTAuxiliaryNode\_\_

• **\_\_tid\_BTAuxiliaryNode\_\_**: `boolean`

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[__tid_BTAuxiliaryNode__](ue_ue.BTAuxiliaryNode.md#__tid_btauxiliarynode__)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[__tid_BTNode__](ue_ue.BTAuxiliaryNode.md#__tid_btnode__)

___

### \_\_tid\_BTService\_\_

• **\_\_tid\_BTService\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[__tid_Object__](ue_ue.BTAuxiliaryNode.md#__tid_object__)

___

### bCallTickOnSearchStart

• **bCallTickOnSearchStart**: `boolean`

___

### bRestartTimerOnEachActivation

• **bRestartTimerOnEachActivation**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[GetClass](ue_ue.BTAuxiliaryNode.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[GetName](ue_ue.BTAuxiliaryNode.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[GetOuter](ue_ue.BTAuxiliaryNode.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[GetWorld](ue_ue.BTAuxiliaryNode.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTAuxiliaryNode](ue_ue.BTAuxiliaryNode.md).[StaticClass](ue_ue.BTAuxiliaryNode.md#staticclass)
