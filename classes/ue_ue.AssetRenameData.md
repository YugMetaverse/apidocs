[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AssetRenameData

# Class: AssetRenameData

[ue/ue](../modules/ue_ue.md).AssetRenameData

## Table of contents

### Constructors

- [constructor](ue_ue.AssetRenameData.md#constructor)

### Properties

- [Asset](ue_ue.AssetRenameData.md#asset)
- [NewName](ue_ue.AssetRenameData.md#newname)
- [NewObjectPath](ue_ue.AssetRenameData.md#newobjectpath)
- [NewPackagePath](ue_ue.AssetRenameData.md#newpackagepath)
- [OldObjectPath](ue_ue.AssetRenameData.md#oldobjectpath)
- [\_\_tid\_AssetRenameData\_\_](ue_ue.AssetRenameData.md#__tid_assetrenamedata__)
- [bOnlyFixSoftReferences](ue_ue.AssetRenameData.md#bonlyfixsoftreferences)

### Methods

- [StaticClass](ue_ue.AssetRenameData.md#staticclass)
- [StaticStruct](ue_ue.AssetRenameData.md#staticstruct)

## Constructors

### constructor

• **new AssetRenameData**()

• **new AssetRenameData**(`Asset`, `NewPackagePath`, `NewName`, `OldObjectPath`, `NewObjectPath`, `bOnlyFixSoftReferences`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Asset` | [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\> |
| `NewPackagePath` | `string` |
| `NewName` | `string` |
| `OldObjectPath` | [`SoftObjectPath`](ue_ue.SoftObjectPath.md) |
| `NewObjectPath` | [`SoftObjectPath`](ue_ue.SoftObjectPath.md) |
| `bOnlyFixSoftReferences` | `boolean` |

## Properties

### Asset

• **Asset**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\>

___

### NewName

• **NewName**: `string`

___

### NewObjectPath

• **NewObjectPath**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### NewPackagePath

• **NewPackagePath**: `string`

___

### OldObjectPath

• **OldObjectPath**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### \_\_tid\_AssetRenameData\_\_

• `Private` **\_\_tid\_AssetRenameData\_\_**: `boolean`

___

### bOnlyFixSoftReferences

• **bOnlyFixSoftReferences**: `boolean`

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
