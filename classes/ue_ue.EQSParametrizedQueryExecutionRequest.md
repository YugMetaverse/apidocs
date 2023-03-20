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

• **new EQSParametrizedQueryExecutionRequest**(`QueryTemplate`, `QueryConfig`, `EQSQueryBlackboardKey`, `RunMode`, `bUseBBKeyForQueryTemplate`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `QueryTemplate` | [`EnvQuery`](ue_ue.EnvQuery.md) |
| `QueryConfig` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AIDynamicParam`](ue_ue.AIDynamicParam.md)\> |
| `EQSQueryBlackboardKey` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |
| `RunMode` | [`EEnvQueryRunMode`](../enums/ue_ue.EEnvQueryRunMode.md) |
| `bUseBBKeyForQueryTemplate` | `boolean` |

## Properties

### EQSQueryBlackboardKey

• **EQSQueryBlackboardKey**: [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md)

___

### QueryConfig

• **QueryConfig**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AIDynamicParam`](ue_ue.AIDynamicParam.md)\>

___

### QueryTemplate

• **QueryTemplate**: [`EnvQuery`](ue_ue.EnvQuery.md)

___

### RunMode

• **RunMode**: [`EEnvQueryRunMode`](../enums/ue_ue.EEnvQueryRunMode.md)

___

### \_\_tid\_EQSParametrizedQueryExecutionRequest\_\_

• `Private` **\_\_tid\_EQSParametrizedQueryExecutionRequest\_\_**: `boolean`

___

### bUseBBKeyForQueryTemplate

• **bUseBBKeyForQueryTemplate**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
