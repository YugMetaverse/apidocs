[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ImageWriteOptions

# Class: ImageWriteOptions

[ue/ue](../modules/ue_ue.md).ImageWriteOptions

## Table of contents

### Constructors

- [constructor](ue_ue.ImageWriteOptions.md#constructor)

### Properties

- [CompressionQuality](ue_ue.ImageWriteOptions.md#compressionquality)
- [Format](ue_ue.ImageWriteOptions.md#format)
- [OnComplete](ue_ue.ImageWriteOptions.md#oncomplete)
- [\_\_tid\_ImageWriteOptions\_\_](ue_ue.ImageWriteOptions.md#__tid_imagewriteoptions__)
- [bAsync](ue_ue.ImageWriteOptions.md#basync)
- [bOverwriteFile](ue_ue.ImageWriteOptions.md#boverwritefile)

### Methods

- [StaticClass](ue_ue.ImageWriteOptions.md#staticclass)
- [StaticStruct](ue_ue.ImageWriteOptions.md#staticstruct)

## Constructors

### constructor

• **new ImageWriteOptions**()

• **new ImageWriteOptions**(`Format`, `OnComplete`, `CompressionQuality`, `bOverwriteFile`, `bAsync`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Format` | [`EDesiredImageFormat`](../enums/ue_ue.EDesiredImageFormat.md) |
| `OnComplete` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`bSuccess`: `boolean`) => `void`\> |
| `CompressionQuality` | `number` |
| `bOverwriteFile` | `boolean` |
| `bAsync` | `boolean` |

## Properties

### CompressionQuality

• **CompressionQuality**: `number`

___

### Format

• **Format**: [`EDesiredImageFormat`](../enums/ue_ue.EDesiredImageFormat.md)

___

### OnComplete

• **OnComplete**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`bSuccess`: `boolean`) => `void`\>

___

### \_\_tid\_ImageWriteOptions\_\_

• `Private` **\_\_tid\_ImageWriteOptions\_\_**: `boolean`

___

### bAsync

• **bAsync**: `boolean`

___

### bOverwriteFile

• **bOverwriteFile**: `boolean`

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
