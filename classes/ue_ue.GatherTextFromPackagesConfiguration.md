[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GatherTextFromPackagesConfiguration

# Class: GatherTextFromPackagesConfiguration

[ue/ue](../modules/ue_ue.md).GatherTextFromPackagesConfiguration

## Table of contents

### Constructors

- [constructor](ue_ue.GatherTextFromPackagesConfiguration.md#constructor)

### Properties

- [Collections](ue_ue.GatherTextFromPackagesConfiguration.md#collections)
- [ExcludePathWildcards](ue_ue.GatherTextFromPackagesConfiguration.md#excludepathwildcards)
- [FileExtensions](ue_ue.GatherTextFromPackagesConfiguration.md#fileextensions)
- [IncludePathWildcards](ue_ue.GatherTextFromPackagesConfiguration.md#includepathwildcards)
- [IsEnabled](ue_ue.GatherTextFromPackagesConfiguration.md#isenabled)
- [ShouldGatherFromEditorOnlyData](ue_ue.GatherTextFromPackagesConfiguration.md#shouldgatherfromeditoronlydata)
- [SkipGatherCache](ue_ue.GatherTextFromPackagesConfiguration.md#skipgathercache)
- [\_\_tid\_GatherTextFromPackagesConfiguration\_\_](ue_ue.GatherTextFromPackagesConfiguration.md#__tid_gathertextfrompackagesconfiguration__)

### Methods

- [StaticClass](ue_ue.GatherTextFromPackagesConfiguration.md#staticclass)
- [StaticStruct](ue_ue.GatherTextFromPackagesConfiguration.md#staticstruct)

## Constructors

### constructor

• **new GatherTextFromPackagesConfiguration**()

• **new GatherTextFromPackagesConfiguration**(`IsEnabled`, `IncludePathWildcards`, `ExcludePathWildcards`, `FileExtensions`, `Collections`, `ShouldGatherFromEditorOnlyData`, `SkipGatherCache`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `IsEnabled` | `boolean` |
| `IncludePathWildcards` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GatherTextIncludePath`](ue_ue.GatherTextIncludePath.md)\> |
| `ExcludePathWildcards` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GatherTextExcludePath`](ue_ue.GatherTextExcludePath.md)\> |
| `FileExtensions` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GatherTextFileExtension`](ue_ue.GatherTextFileExtension.md)\> |
| `Collections` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `ShouldGatherFromEditorOnlyData` | `boolean` |
| `SkipGatherCache` | `boolean` |

## Properties

### Collections

• **Collections**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ExcludePathWildcards

• **ExcludePathWildcards**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GatherTextExcludePath`](ue_ue.GatherTextExcludePath.md)\>

___

### FileExtensions

• **FileExtensions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GatherTextFileExtension`](ue_ue.GatherTextFileExtension.md)\>

___

### IncludePathWildcards

• **IncludePathWildcards**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GatherTextIncludePath`](ue_ue.GatherTextIncludePath.md)\>

___

### IsEnabled

• **IsEnabled**: `boolean`

___

### ShouldGatherFromEditorOnlyData

• **ShouldGatherFromEditorOnlyData**: `boolean`

___

### SkipGatherCache

• **SkipGatherCache**: `boolean`

___

### \_\_tid\_GatherTextFromPackagesConfiguration\_\_

• `Private` **\_\_tid\_GatherTextFromPackagesConfiguration\_\_**: `boolean`

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
