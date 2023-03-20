[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TestBTTask\_Log

# Class: TestBTTask\_Log

[ue/ue](../modules/ue_ue.md).TestBTTask_Log

## Hierarchy

- [`BTTaskNode`](ue_ue.BTTaskNode.md)

  ↳ **`TestBTTask_Log`**

## Table of contents

### Constructors

- [constructor](ue_ue.TestBTTask_Log.md#constructor)

### Properties

- [ExecutionTicks](ue_ue.TestBTTask_Log.md#executionticks)
- [LogFinished](ue_ue.TestBTTask_Log.md#logfinished)
- [LogIndex](ue_ue.TestBTTask_Log.md#logindex)
- [LogResult](ue_ue.TestBTTask_Log.md#logresult)
- [NodeName](ue_ue.TestBTTask_Log.md#nodename)
- [ParentNode](ue_ue.TestBTTask_Log.md#parentnode)
- [Services](ue_ue.TestBTTask_Log.md#services)
- [TreeAsset](ue_ue.TestBTTask_Log.md#treeasset)
- [\_\_tid\_BTNode\_\_](ue_ue.TestBTTask_Log.md#__tid_btnode__)
- [\_\_tid\_BTTaskNode\_\_](ue_ue.TestBTTask_Log.md#__tid_bttasknode__)
- [\_\_tid\_Object\_\_](ue_ue.TestBTTask_Log.md#__tid_object__)
- [\_\_tid\_TestBTTask\_Log\_\_](ue_ue.TestBTTask_Log.md#__tid_testbttask_log__)
- [bIgnoreRestartSelf](ue_ue.TestBTTask_Log.md#bignorerestartself)

### Methods

- [CreateDefaultSubobject](ue_ue.TestBTTask_Log.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TestBTTask_Log.md#executeubergraph)
- [GetClass](ue_ue.TestBTTask_Log.md#getclass)
- [GetName](ue_ue.TestBTTask_Log.md#getname)
- [GetOuter](ue_ue.TestBTTask_Log.md#getouter)
- [GetWorld](ue_ue.TestBTTask_Log.md#getworld)
- [Find](ue_ue.TestBTTask_Log.md#find)
- [Load](ue_ue.TestBTTask_Log.md#load)
- [StaticClass](ue_ue.TestBTTask_Log.md#staticclass)

## Constructors

### constructor

• **new TestBTTask_Log**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[constructor](ue_ue.BTTaskNode.md#constructor)

#### Defined in

[ue/ue.d.ts:62906](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L62906)

## Properties

### ExecutionTicks

• **ExecutionTicks**: `number`

#### Defined in

[ue/ue.d.ts:62909](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L62909)

___

### LogFinished

• **LogFinished**: `number`

#### Defined in

[ue/ue.d.ts:62908](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L62908)

___

### LogIndex

• **LogIndex**: `number`

#### Defined in

[ue/ue.d.ts:62907](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L62907)

___

### LogResult

• **LogResult**: [`EBTNodeResult`](../enums/ue_ue.EBTNodeResult.md)

#### Defined in

[ue/ue.d.ts:62910](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L62910)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[NodeName](ue_ue.BTTaskNode.md#nodename)

#### Defined in

[ue/ue.d.ts:14567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14567)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[ParentNode](ue_ue.BTTaskNode.md#parentnode)

#### Defined in

[ue/ue.d.ts:14569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14569)

___

### Services

• **Services**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BTService`](ue_ue.BTService.md)\>

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[Services](ue_ue.BTTaskNode.md#services)

#### Defined in

[ue/ue.d.ts:14601](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14601)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[TreeAsset](ue_ue.BTTaskNode.md#treeasset)

#### Defined in

[ue/ue.d.ts:14568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14568)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[__tid_BTNode__](ue_ue.BTTaskNode.md#__tid_btnode__)

#### Defined in

[ue/ue.d.ts:14574](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14574)

___

### \_\_tid\_BTTaskNode\_\_

• **\_\_tid\_BTTaskNode\_\_**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[__tid_BTTaskNode__](ue_ue.BTTaskNode.md#__tid_bttasknode__)

#### Defined in

[ue/ue.d.ts:14607](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14607)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[__tid_Object__](ue_ue.BTTaskNode.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_TestBTTask\_Log\_\_

• **\_\_tid\_TestBTTask\_Log\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:62915](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L62915)

___

### bIgnoreRestartSelf

• **bIgnoreRestartSelf**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[bIgnoreRestartSelf](ue_ue.BTTaskNode.md#bignorerestartself)

#### Defined in

[ue/ue.d.ts:14602](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14602)

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

[BTTaskNode](ue_ue.BTTaskNode.md).[ExecuteUbergraph](ue_ue.BTTaskNode.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetClass](ue_ue.BTTaskNode.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetName](ue_ue.BTTaskNode.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetOuter](ue_ue.BTTaskNode.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetWorld](ue_ue.BTTaskNode.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TestBTTask_Log`](ue_ue.TestBTTask_Log.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TestBTTask_Log`](ue_ue.TestBTTask_Log.md)

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[Find](ue_ue.BTTaskNode.md#find)

#### Defined in

[ue/ue.d.ts:62912](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L62912)

___

### Load

▸ `Static` **Load**(`InName`): [`TestBTTask_Log`](ue_ue.TestBTTask_Log.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TestBTTask_Log`](ue_ue.TestBTTask_Log.md)

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[Load](ue_ue.BTTaskNode.md#load)

#### Defined in

[ue/ue.d.ts:62913](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L62913)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[StaticClass](ue_ue.BTTaskNode.md#staticclass)

#### Defined in

[ue/ue.d.ts:62911](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L62911)