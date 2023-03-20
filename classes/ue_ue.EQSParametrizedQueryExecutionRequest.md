[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EQSParametrizedQueryExecutionRequest

# Class: EQSParametrizedQueryExecutionRequest

[ue/ue](../modules/ue_ue.md).EQSParametrizedQueryExecutionRequest

## Table of contents

### Constructors

- [constructor](ue_ue.EQSParametrizedQueryExecutionRequest.md#constructor)

### Properties

- [EQSQueryBlackboardKey](ue_ue.EQSParametrizedQueryExecutionRequest.md#eqsqueryblackboardkey)
- [QueryConfig](ue_ue.EQSParametrizedQueryExecutionRequest.md#queryconfig)
- [QueryTemplate](ue_ue.EQSParametrizedQueryExecutionRequest.md#querytemplate)
- [RunMode](ue_ue.EQSParametrizedQueryExecutionRequest.md#runmode)
- [\_\_tid\_EQSParametrizedQueryExecutionRequest\_\_](ue_ue.EQSParametrizedQueryExecutionRequest.md#__tid_eqsparametrizedqueryexecutionrequest__)
- [bUseBBKeyForQueryTemplate](ue_ue.EQSParametrizedQueryExecutionRequest.md#busebbkeyforquerytemplate)

### Methods

- [StaticClass](ue_ue.EQSParametrizedQueryExecutionRequest.md#staticclass)
- [StaticStruct](ue_ue.EQSParametrizedQueryExecutionRequest.md#staticstruct)

## Constructors

### constructor

• **new EQSParametrizedQueryExecutionRequest**()

#### Defined in

[ue/ue.d.ts:25195](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25195)

• **new EQSParametrizedQueryExecutionRequest**(`QueryTemplate`, `QueryConfig`, `EQSQueryBlackboardKey`, `RunMode`, `bUseBBKeyForQueryTemplate`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `QueryTemplate` | [`EnvQuery`](ue_ue.EnvQuery.md) |
| `QueryConfig` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AIDynamicParam`](ue_ue.AIDynamicParam.md)\> |
| `EQSQueryBlackboardKey` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |
| `RunMode` | [`EEnvQueryRunMode`](../enums/ue_ue.EEnvQueryRunMode.md) |
| `bUseBBKeyForQueryTemplate` | `boolean` |

#### Defined in

[ue/ue.d.ts:25196](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25196)

## Properties

### EQSQueryBlackboardKey

• **EQSQueryBlackboardKey**: [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md)

#### Defined in

[ue/ue.d.ts:25199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25199)

___

### QueryConfig

• **QueryConfig**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AIDynamicParam`](ue_ue.AIDynamicParam.md)\>

#### Defined in

[ue/ue.d.ts:25198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25198)

___

### QueryTemplate

• **QueryTemplate**: [`EnvQuery`](ue_ue.EnvQuery.md)

#### Defined in

[ue/ue.d.ts:25197](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25197)

___

### RunMode

• **RunMode**: [`EEnvQueryRunMode`](../enums/ue_ue.EEnvQueryRunMode.md)

#### Defined in

[ue/ue.d.ts:25200](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25200)

___

### \_\_tid\_EQSParametrizedQueryExecutionRequest\_\_

• `Private` **\_\_tid\_EQSParametrizedQueryExecutionRequest\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:25207](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25207)

___

### bUseBBKeyForQueryTemplate

• **bUseBBKeyForQueryTemplate**: `boolean`

#### Defined in

[ue/ue.d.ts:25201](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25201)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:25205](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25205)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:25206](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25206)
