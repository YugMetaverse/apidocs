[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AssetBundleEntry

# Class: AssetBundleEntry

[ue/ue](../modules/ue_ue.md).AssetBundleEntry

## Table of contents

### Constructors

- [constructor](ue_ue.AssetBundleEntry.md#constructor)

### Properties

- [BundleAssets](ue_ue.AssetBundleEntry.md#bundleassets)
- [BundleName](ue_ue.AssetBundleEntry.md#bundlename)
- [BundleScope](ue_ue.AssetBundleEntry.md#bundlescope)
- [\_\_tid\_AssetBundleEntry\_\_](ue_ue.AssetBundleEntry.md#__tid_assetbundleentry__)

### Methods

- [StaticClass](ue_ue.AssetBundleEntry.md#staticclass)
- [StaticStruct](ue_ue.AssetBundleEntry.md#staticstruct)

## Constructors

### constructor

• **new AssetBundleEntry**()

• **new AssetBundleEntry**(`BundleScope`, `BundleName`, `BundleAssets`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BundleScope` | [`PrimaryAssetId`](ue_ue.PrimaryAssetId.md) |
| `BundleName` | `string` |
| `BundleAssets` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoftObjectPath`](ue_ue.SoftObjectPath.md)\> |

## Properties

### BundleAssets

• **BundleAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoftObjectPath`](ue_ue.SoftObjectPath.md)\>

___

### BundleName

• **BundleName**: `string`

___

### BundleScope

• **BundleScope**: [`PrimaryAssetId`](ue_ue.PrimaryAssetId.md)

___

### \_\_tid\_AssetBundleEntry\_\_

• `Private` **\_\_tid\_AssetBundleEntry\_\_**: `boolean`

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
