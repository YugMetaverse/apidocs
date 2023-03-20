[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GatherTextFromMetaDataConfiguration

# Class: GatherTextFromMetaDataConfiguration

[ue/ue](../modules/ue_ue.md).GatherTextFromMetaDataConfiguration

## Table of contents

### Constructors

- [constructor](ue_ue.GatherTextFromMetaDataConfiguration.md#constructor)

### Properties

- [ExcludePathWildcards](ue_ue.GatherTextFromMetaDataConfiguration.md#excludepathwildcards)
- [IncludePathWildcards](ue_ue.GatherTextFromMetaDataConfiguration.md#includepathwildcards)
- [IsEnabled](ue_ue.GatherTextFromMetaDataConfiguration.md#isenabled)
- [KeySpecifications](ue_ue.GatherTextFromMetaDataConfiguration.md#keyspecifications)
- [ShouldGatherFromEditorOnlyData](ue_ue.GatherTextFromMetaDataConfiguration.md#shouldgatherfromeditoronlydata)
- [\_\_tid\_GatherTextFromMetaDataConfiguration\_\_](ue_ue.GatherTextFromMetaDataConfiguration.md#__tid_gathertextfrommetadataconfiguration__)

### Methods

- [StaticClass](ue_ue.GatherTextFromMetaDataConfiguration.md#staticclass)
- [StaticStruct](ue_ue.GatherTextFromMetaDataConfiguration.md#staticstruct)

## Constructors

### constructor

• **new GatherTextFromMetaDataConfiguration**()

• **new GatherTextFromMetaDataConfiguration**(`IsEnabled`, `IncludePathWildcards`, `ExcludePathWildcards`, `KeySpecifications`, `ShouldGatherFromEditorOnlyData`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `IsEnabled` | `boolean` |
| `IncludePathWildcards` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GatherTextIncludePath`](ue_ue.GatherTextIncludePath.md)\> |
| `ExcludePathWildcards` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GatherTextExcludePath`](ue_ue.GatherTextExcludePath.md)\> |
| `KeySpecifications` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MetaDataKeyGatherSpecification`](ue_ue.MetaDataKeyGatherSpecification.md)\> |
| `ShouldGatherFromEditorOnlyData` | `boolean` |

## Properties

### ExcludePathWildcards

• **ExcludePathWildcards**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GatherTextExcludePath`](ue_ue.GatherTextExcludePath.md)\>

___

### IncludePathWildcards

• **IncludePathWildcards**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GatherTextIncludePath`](ue_ue.GatherTextIncludePath.md)\>

___

### IsEnabled

• **IsEnabled**: `boolean`

___

### KeySpecifications

• **KeySpecifications**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MetaDataKeyGatherSpecification`](ue_ue.MetaDataKeyGatherSpecification.md)\>

___

### ShouldGatherFromEditorOnlyData

• **ShouldGatherFromEditorOnlyData**: `boolean`

___

### \_\_tid\_GatherTextFromMetaDataConfiguration\_\_

• `Private` **\_\_tid\_GatherTextFromMetaDataConfiguration\_\_**: `boolean`

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
