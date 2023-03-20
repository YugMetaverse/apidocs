[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTTask\_RunEQSQuery

# Class: BTTask\_RunEQSQuery

[ue/ue](../modules/ue_ue.md).BTTask_RunEQSQuery

## Hierarchy

- [`BTTask_BlackboardBase`](ue_ue.BTTask_BlackboardBase.md)

  ↳ **`BTTask_RunEQSQuery`**

## Table of contents

### Constructors

- [constructor](ue_ue.BTTask_RunEQSQuery.md#constructor)

### Properties

- [BlackboardKey](ue_ue.BTTask_RunEQSQuery.md#blackboardkey)
- [EQSQueryBlackboardKey](ue_ue.BTTask_RunEQSQuery.md#eqsqueryblackboardkey)
- [EQSRequest](ue_ue.BTTask_RunEQSQuery.md#eqsrequest)
- [NodeName](ue_ue.BTTask_RunEQSQuery.md#nodename)
- [ParentNode](ue_ue.BTTask_RunEQSQuery.md#parentnode)
- [QueryConfig](ue_ue.BTTask_RunEQSQuery.md#queryconfig)
- [QueryParams](ue_ue.BTTask_RunEQSQuery.md#queryparams)
- [QueryTemplate](ue_ue.BTTask_RunEQSQuery.md#querytemplate)
- [RunMode](ue_ue.BTTask_RunEQSQuery.md#runmode)
- [Services](ue_ue.BTTask_RunEQSQuery.md#services)
- [TreeAsset](ue_ue.BTTask_RunEQSQuery.md#treeasset)
- [\_\_tid\_BTNode\_\_](ue_ue.BTTask_RunEQSQuery.md#__tid_btnode__)
- [\_\_tid\_BTTaskNode\_\_](ue_ue.BTTask_RunEQSQuery.md#__tid_bttasknode__)
- [\_\_tid\_BTTask\_BlackboardBase\_\_](ue_ue.BTTask_RunEQSQuery.md#__tid_bttask_blackboardbase__)
- [\_\_tid\_BTTask\_RunEQSQuery\_\_](ue_ue.BTTask_RunEQSQuery.md#__tid_bttask_runeqsquery__)
- [\_\_tid\_Object\_\_](ue_ue.BTTask_RunEQSQuery.md#__tid_object__)
- [bIgnoreRestartSelf](ue_ue.BTTask_RunEQSQuery.md#bignorerestartself)
- [bUseBBKey](ue_ue.BTTask_RunEQSQuery.md#busebbkey)

### Methods

- [CreateDefaultSubobject](ue_ue.BTTask_RunEQSQuery.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTTask_RunEQSQuery.md#executeubergraph)
- [GetClass](ue_ue.BTTask_RunEQSQuery.md#getclass)
- [GetName](ue_ue.BTTask_RunEQSQuery.md#getname)
- [GetOuter](ue_ue.BTTask_RunEQSQuery.md#getouter)
- [GetWorld](ue_ue.BTTask_RunEQSQuery.md#getworld)
- [Find](ue_ue.BTTask_RunEQSQuery.md#find)
- [Load](ue_ue.BTTask_RunEQSQuery.md#load)
- [StaticClass](ue_ue.BTTask_RunEQSQuery.md#staticclass)

## Constructors

### constructor

• **new BTTask_RunEQSQuery**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[constructor](ue_ue.BTTask_BlackboardBase.md#constructor)

## Properties

### BlackboardKey

• **BlackboardKey**: [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md)

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[BlackboardKey](ue_ue.BTTask_BlackboardBase.md#blackboardkey)

___

### EQSQueryBlackboardKey

• **EQSQueryBlackboardKey**: [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md)

___

### EQSRequest

• **EQSRequest**: [`EQSParametrizedQueryExecutionRequest`](ue_ue.EQSParametrizedQueryExecutionRequest.md)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[NodeName](ue_ue.BTTask_BlackboardBase.md#nodename)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[ParentNode](ue_ue.BTTask_BlackboardBase.md#parentnode)

___

### QueryConfig

• **QueryConfig**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AIDynamicParam`](ue_ue.AIDynamicParam.md)\>

___

### QueryParams

• **QueryParams**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EnvNamedValue`](ue_ue.EnvNamedValue.md)\>

___

### QueryTemplate

• **QueryTemplate**: [`EnvQuery`](ue_ue.EnvQuery.md)

___

### RunMode

• **RunMode**: [`EEnvQueryRunMode`](../enums/ue_ue.EEnvQueryRunMode.md)

___

### Services

• **Services**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BTService`](ue_ue.BTService.md)\>

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[Services](ue_ue.BTTask_BlackboardBase.md#services)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[TreeAsset](ue_ue.BTTask_BlackboardBase.md#treeasset)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[__tid_BTNode__](ue_ue.BTTask_BlackboardBase.md#__tid_btnode__)

___

### \_\_tid\_BTTaskNode\_\_

• **\_\_tid\_BTTaskNode\_\_**: `boolean`

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[__tid_BTTaskNode__](ue_ue.BTTask_BlackboardBase.md#__tid_bttasknode__)

___

### \_\_tid\_BTTask\_BlackboardBase\_\_

• **\_\_tid\_BTTask\_BlackboardBase\_\_**: `boolean`

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[__tid_BTTask_BlackboardBase__](ue_ue.BTTask_BlackboardBase.md#__tid_bttask_blackboardbase__)

___

### \_\_tid\_BTTask\_RunEQSQuery\_\_

• **\_\_tid\_BTTask\_RunEQSQuery\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[__tid_Object__](ue_ue.BTTask_BlackboardBase.md#__tid_object__)

___

### bIgnoreRestartSelf

• **bIgnoreRestartSelf**: `boolean`

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[bIgnoreRestartSelf](ue_ue.BTTask_BlackboardBase.md#bignorerestartself)

___

### bUseBBKey

• **bUseBBKey**: `boolean`

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

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[CreateDefaultSubobject](ue_ue.BTTask_BlackboardBase.md#createdefaultsubobject)

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

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[ExecuteUbergraph](ue_ue.BTTask_BlackboardBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[GetClass](ue_ue.BTTask_BlackboardBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[GetName](ue_ue.BTTask_BlackboardBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[GetOuter](ue_ue.BTTask_BlackboardBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[GetWorld](ue_ue.BTTask_BlackboardBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTTask_RunEQSQuery`](ue_ue.BTTask_RunEQSQuery.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTTask_RunEQSQuery`](ue_ue.BTTask_RunEQSQuery.md)

#### Overrides

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[Find](ue_ue.BTTask_BlackboardBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BTTask_RunEQSQuery`](ue_ue.BTTask_RunEQSQuery.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTTask_RunEQSQuery`](ue_ue.BTTask_RunEQSQuery.md)

#### Overrides

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[Load](ue_ue.BTTask_BlackboardBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[StaticClass](ue_ue.BTTask_BlackboardBase.md#staticclass)
