[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARFilter

# Class: ARFilter

[ue/ue](../modules/ue_ue.md).ARFilter

## Table of contents

### Constructors

- [constructor](ue_ue.ARFilter.md#constructor)

### Properties

- [ClassNames](ue_ue.ARFilter.md#classnames)
- [ObjectPaths](ue_ue.ARFilter.md#objectpaths)
- [PackageNames](ue_ue.ARFilter.md#packagenames)
- [PackagePaths](ue_ue.ARFilter.md#packagepaths)
- [RecursiveClassesExclusionSet](ue_ue.ARFilter.md#recursiveclassesexclusionset)
- [\_\_tid\_ARFilter\_\_](ue_ue.ARFilter.md#__tid_arfilter__)
- [bIncludeOnlyOnDiskAssets](ue_ue.ARFilter.md#bincludeonlyondiskassets)
- [bRecursiveClasses](ue_ue.ARFilter.md#brecursiveclasses)
- [bRecursivePaths](ue_ue.ARFilter.md#brecursivepaths)

### Methods

- [StaticClass](ue_ue.ARFilter.md#staticclass)
- [StaticStruct](ue_ue.ARFilter.md#staticstruct)

## Constructors

### constructor

• **new ARFilter**()

• **new ARFilter**(`PackageNames`, `PackagePaths`, `ObjectPaths`, `ClassNames`, `RecursiveClassesExclusionSet`, `bRecursivePaths`, `bRecursiveClasses`, `bIncludeOnlyOnDiskAssets`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PackageNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `PackagePaths` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `ObjectPaths` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `ClassNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `RecursiveClassesExclusionSet` | [`TSet`](../interfaces/ue_puerts.TSet.md)<`string`\> |
| `bRecursivePaths` | `boolean` |
| `bRecursiveClasses` | `boolean` |
| `bIncludeOnlyOnDiskAssets` | `boolean` |

## Properties

### ClassNames

• **ClassNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ObjectPaths

• **ObjectPaths**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### PackageNames

• **PackageNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### PackagePaths

• **PackagePaths**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### RecursiveClassesExclusionSet

• **RecursiveClassesExclusionSet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<`string`\>

___

### \_\_tid\_ARFilter\_\_

• `Private` **\_\_tid\_ARFilter\_\_**: `boolean`

___

### bIncludeOnlyOnDiskAssets

• **bIncludeOnlyOnDiskAssets**: `boolean`

___

### bRecursiveClasses

• **bRecursiveClasses**: `boolean`

___

### bRecursivePaths

• **bRecursivePaths**: `boolean`

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
