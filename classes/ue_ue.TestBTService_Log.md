[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TestBTService\_Log

# Class: TestBTService\_Log

[ue/ue](../modules/ue_ue.md).TestBTService_Log

## Hierarchy

- [`BTService`](ue_ue.BTService.md)

  ↳ **`TestBTService_Log`**

## Table of contents

### Constructors

- [constructor](ue_ue.TestBTService_Log.md#constructor)

### Properties

- [Interval](ue_ue.TestBTService_Log.md#interval)
- [LogActivation](ue_ue.TestBTService_Log.md#logactivation)
- [LogDeactivation](ue_ue.TestBTService_Log.md#logdeactivation)
- [NodeName](ue_ue.TestBTService_Log.md#nodename)
- [ParentNode](ue_ue.TestBTService_Log.md#parentnode)
- [RandomDeviation](ue_ue.TestBTService_Log.md#randomdeviation)
- [TreeAsset](ue_ue.TestBTService_Log.md#treeasset)
- [\_\_tid\_BTAuxiliaryNode\_\_](ue_ue.TestBTService_Log.md#__tid_btauxiliarynode__)
- [\_\_tid\_BTNode\_\_](ue_ue.TestBTService_Log.md#__tid_btnode__)
- [\_\_tid\_BTService\_\_](ue_ue.TestBTService_Log.md#__tid_btservice__)
- [\_\_tid\_Object\_\_](ue_ue.TestBTService_Log.md#__tid_object__)
- [\_\_tid\_TestBTService\_Log\_\_](ue_ue.TestBTService_Log.md#__tid_testbtservice_log__)
- [bCallTickOnSearchStart](ue_ue.TestBTService_Log.md#bcalltickonsearchstart)
- [bRestartTimerOnEachActivation](ue_ue.TestBTService_Log.md#brestarttimeroneachactivation)

### Methods

- [CreateDefaultSubobject](ue_ue.TestBTService_Log.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TestBTService_Log.md#executeubergraph)
- [GetClass](ue_ue.TestBTService_Log.md#getclass)
- [GetName](ue_ue.TestBTService_Log.md#getname)
- [GetOuter](ue_ue.TestBTService_Log.md#getouter)
- [GetWorld](ue_ue.TestBTService_Log.md#getworld)
- [Find](ue_ue.TestBTService_Log.md#find)
- [Load](ue_ue.TestBTService_Log.md#load)
- [StaticClass](ue_ue.TestBTService_Log.md#staticclass)

## Constructors

### constructor

• **new TestBTService_Log**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTService](ue_ue.BTService.md).[constructor](ue_ue.BTService.md#constructor)

## Properties

### Interval

• **Interval**: `number`

#### Inherited from

[BTService](ue_ue.BTService.md).[Interval](ue_ue.BTService.md#interval)

___

### LogActivation

• **LogActivation**: `number`

___

### LogDeactivation

• **LogDeactivation**: `number`

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTService](ue_ue.BTService.md).[NodeName](ue_ue.BTService.md#nodename)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTService](ue_ue.BTService.md).[ParentNode](ue_ue.BTService.md#parentnode)

___

### RandomDeviation

• **RandomDeviation**: `number`

#### Inherited from

[BTService](ue_ue.BTService.md).[RandomDeviation](ue_ue.BTService.md#randomdeviation)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTService](ue_ue.BTService.md).[TreeAsset](ue_ue.BTService.md#treeasset)

___

### \_\_tid\_BTAuxiliaryNode\_\_

• **\_\_tid\_BTAuxiliaryNode\_\_**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[__tid_BTAuxiliaryNode__](ue_ue.BTService.md#__tid_btauxiliarynode__)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[__tid_BTNode__](ue_ue.BTService.md#__tid_btnode__)

___

### \_\_tid\_BTService\_\_

• **\_\_tid\_BTService\_\_**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[__tid_BTService__](ue_ue.BTService.md#__tid_btservice__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[__tid_Object__](ue_ue.BTService.md#__tid_object__)

___

### \_\_tid\_TestBTService\_Log\_\_

• **\_\_tid\_TestBTService\_Log\_\_**: `boolean`

___

### bCallTickOnSearchStart

• **bCallTickOnSearchStart**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[bCallTickOnSearchStart](ue_ue.BTService.md#bcalltickonsearchstart)

___

### bRestartTimerOnEachActivation

• **bRestartTimerOnEachActivation**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[bRestartTimerOnEachActivation](ue_ue.BTService.md#brestarttimeroneachactivation)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTService](ue_ue.BTService.md).[GetClass](ue_ue.BTService.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTService](ue_ue.BTService.md).[GetName](ue_ue.BTService.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTService](ue_ue.BTService.md).[GetOuter](ue_ue.BTService.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTService](ue_ue.BTService.md).[GetWorld](ue_ue.BTService.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TestBTService_Log`](ue_ue.TestBTService_Log.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TestBTService_Log`](ue_ue.TestBTService_Log.md)

#### Overrides

[BTService](ue_ue.BTService.md).[Find](ue_ue.BTService.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TestBTService_Log`](ue_ue.TestBTService_Log.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TestBTService_Log`](ue_ue.TestBTService_Log.md)

#### Overrides

[BTService](ue_ue.BTService.md).[Load](ue_ue.BTService.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTService](ue_ue.BTService.md).[StaticClass](ue_ue.BTService.md#staticclass)
