[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PrimaryAssetTypeInfo

# Class: PrimaryAssetTypeInfo

[ue/ue](../modules/ue_ue.md).PrimaryAssetTypeInfo

## Table of contents

### Constructors

- [constructor](ue_ue.PrimaryAssetTypeInfo.md#constructor)

### Properties

- [AssetBaseClass](ue_ue.PrimaryAssetTypeInfo.md#assetbaseclass)
- [AssetBaseClassLoaded](ue_ue.PrimaryAssetTypeInfo.md#assetbaseclassloaded)
- [AssetScanPaths](ue_ue.PrimaryAssetTypeInfo.md#assetscanpaths)
- [Directories](ue_ue.PrimaryAssetTypeInfo.md#directories)
- [NumberOfAssets](ue_ue.PrimaryAssetTypeInfo.md#numberofassets)
- [PrimaryAssetType](ue_ue.PrimaryAssetTypeInfo.md#primaryassettype)
- [Rules](ue_ue.PrimaryAssetTypeInfo.md#rules)
- [SpecificAssets](ue_ue.PrimaryAssetTypeInfo.md#specificassets)
- [\_\_tid\_PrimaryAssetTypeInfo\_\_](ue_ue.PrimaryAssetTypeInfo.md#__tid_primaryassettypeinfo__)
- [bHasBlueprintClasses](ue_ue.PrimaryAssetTypeInfo.md#bhasblueprintclasses)
- [bIsDynamicAsset](ue_ue.PrimaryAssetTypeInfo.md#bisdynamicasset)
- [bIsEditorOnly](ue_ue.PrimaryAssetTypeInfo.md#biseditoronly)

### Methods

- [StaticClass](ue_ue.PrimaryAssetTypeInfo.md#staticclass)
- [StaticStruct](ue_ue.PrimaryAssetTypeInfo.md#staticstruct)

## Constructors

### constructor

• **new PrimaryAssetTypeInfo**()

• **new PrimaryAssetTypeInfo**(`PrimaryAssetType`, `AssetBaseClass`, `AssetBaseClassLoaded`, `bHasBlueprintClasses`, `bIsEditorOnly`, `Directories`, `SpecificAssets`, `Rules`, `AssetScanPaths`, `bIsDynamicAsset`, `NumberOfAssets`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrimaryAssetType` | `string` |
| `AssetBaseClass` | [`TSoftClassPtr`](../modules/ue_puerts.md#tsoftclassptr)<[`Object`](ue_ue.Object.md)\> |
| `AssetBaseClassLoaded` | [`Class`](ue_ue.Class.md) |
| `bHasBlueprintClasses` | `boolean` |
| `bIsEditorOnly` | `boolean` |
| `Directories` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryPath`](ue_ue.DirectoryPath.md)\> |
| `SpecificAssets` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoftObjectPath`](ue_ue.SoftObjectPath.md)\> |
| `Rules` | [`PrimaryAssetRules`](ue_ue.PrimaryAssetRules.md) |
| `AssetScanPaths` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `bIsDynamicAsset` | `boolean` |
| `NumberOfAssets` | `number` |

## Properties

### AssetBaseClass

• **AssetBaseClass**: [`TSoftClassPtr`](../modules/ue_puerts.md#tsoftclassptr)<[`Object`](ue_ue.Object.md)\>

___

### AssetBaseClassLoaded

• **AssetBaseClassLoaded**: [`Class`](ue_ue.Class.md)

___

### AssetScanPaths

• **AssetScanPaths**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### Directories

• **Directories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryPath`](ue_ue.DirectoryPath.md)\>

___

### NumberOfAssets

• **NumberOfAssets**: `number`

___

### PrimaryAssetType

• **PrimaryAssetType**: `string`

___

### Rules

• **Rules**: [`PrimaryAssetRules`](ue_ue.PrimaryAssetRules.md)

___

### SpecificAssets

• **SpecificAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoftObjectPath`](ue_ue.SoftObjectPath.md)\>

___

### \_\_tid\_PrimaryAssetTypeInfo\_\_

• `Private` **\_\_tid\_PrimaryAssetTypeInfo\_\_**: `boolean`

___

### bHasBlueprintClasses

• **bHasBlueprintClasses**: `boolean`

___

### bIsDynamicAsset

• **bIsDynamicAsset**: `boolean`

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

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
