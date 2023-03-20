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

#### Defined in

[ue/ue.d.ts:21644](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21644)

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

#### Defined in

[ue/ue.d.ts:21645](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21645)

## Properties

### AssetBaseClass

• **AssetBaseClass**: [`TSoftClassPtr`](../modules/ue_puerts.md#tsoftclassptr)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:21647](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21647)

___

### AssetBaseClassLoaded

• **AssetBaseClassLoaded**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:21648](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21648)

___

### AssetScanPaths

• **AssetScanPaths**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:21654](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21654)

___

### Directories

• **Directories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryPath`](ue_ue.DirectoryPath.md)\>

#### Defined in

[ue/ue.d.ts:21651](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21651)

___

### NumberOfAssets

• **NumberOfAssets**: `number`

#### Defined in

[ue/ue.d.ts:21656](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21656)

___

### PrimaryAssetType

• **PrimaryAssetType**: `string`

#### Defined in

[ue/ue.d.ts:21646](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21646)

___

### Rules

• **Rules**: [`PrimaryAssetRules`](ue_ue.PrimaryAssetRules.md)

#### Defined in

[ue/ue.d.ts:21653](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21653)

___

### SpecificAssets

• **SpecificAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoftObjectPath`](ue_ue.SoftObjectPath.md)\>

#### Defined in

[ue/ue.d.ts:21652](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21652)

___

### \_\_tid\_PrimaryAssetTypeInfo\_\_

• `Private` **\_\_tid\_PrimaryAssetTypeInfo\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:21662](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21662)

___

### bHasBlueprintClasses

• **bHasBlueprintClasses**: `boolean`

#### Defined in

[ue/ue.d.ts:21649](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21649)

___

### bIsDynamicAsset

• **bIsDynamicAsset**: `boolean`

#### Defined in

[ue/ue.d.ts:21655](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21655)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Defined in

[ue/ue.d.ts:21650](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21650)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:21660](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21660)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:21661](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21661)
