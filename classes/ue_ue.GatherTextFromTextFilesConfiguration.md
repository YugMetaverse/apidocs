[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GatherTextFromTextFilesConfiguration

# Class: GatherTextFromTextFilesConfiguration

[ue/ue](../modules/ue_ue.md).GatherTextFromTextFilesConfiguration

## Table of contents

### Constructors

- [constructor](ue_ue.GatherTextFromTextFilesConfiguration.md#constructor)

### Properties

- [ExcludePathWildcards](ue_ue.GatherTextFromTextFilesConfiguration.md#excludepathwildcards)
- [FileExtensions](ue_ue.GatherTextFromTextFilesConfiguration.md#fileextensions)
- [IsEnabled](ue_ue.GatherTextFromTextFilesConfiguration.md#isenabled)
- [SearchDirectories](ue_ue.GatherTextFromTextFilesConfiguration.md#searchdirectories)
- [ShouldGatherFromEditorOnlyData](ue_ue.GatherTextFromTextFilesConfiguration.md#shouldgatherfromeditoronlydata)
- [\_\_tid\_GatherTextFromTextFilesConfiguration\_\_](ue_ue.GatherTextFromTextFilesConfiguration.md#__tid_gathertextfromtextfilesconfiguration__)

### Methods

- [StaticClass](ue_ue.GatherTextFromTextFilesConfiguration.md#staticclass)
- [StaticStruct](ue_ue.GatherTextFromTextFilesConfiguration.md#staticstruct)

## Constructors

### constructor

• **new GatherTextFromTextFilesConfiguration**()

• **new GatherTextFromTextFilesConfiguration**(`IsEnabled`, `SearchDirectories`, `ExcludePathWildcards`, `FileExtensions`, `ShouldGatherFromEditorOnlyData`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `IsEnabled` | `boolean` |
| `SearchDirectories` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GatherTextSearchDirectory`](ue_ue.GatherTextSearchDirectory.md)\> |
| `ExcludePathWildcards` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GatherTextExcludePath`](ue_ue.GatherTextExcludePath.md)\> |
| `FileExtensions` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GatherTextFileExtension`](ue_ue.GatherTextFileExtension.md)\> |
| `ShouldGatherFromEditorOnlyData` | `boolean` |

## Properties

### ExcludePathWildcards

• **ExcludePathWildcards**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GatherTextExcludePath`](ue_ue.GatherTextExcludePath.md)\>

___

### FileExtensions

• **FileExtensions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GatherTextFileExtension`](ue_ue.GatherTextFileExtension.md)\>

___

### IsEnabled

• **IsEnabled**: `boolean`

___

### SearchDirectories

• **SearchDirectories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GatherTextSearchDirectory`](ue_ue.GatherTextSearchDirectory.md)\>

___

### ShouldGatherFromEditorOnlyData

• **ShouldGatherFromEditorOnlyData**: `boolean`

___

### \_\_tid\_GatherTextFromTextFilesConfiguration\_\_

• `Private` **\_\_tid\_GatherTextFromTextFilesConfiguration\_\_**: `boolean`

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
