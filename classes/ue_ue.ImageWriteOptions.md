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

#### Defined in

[ue/ue.d.ts:38772](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38772)

• **new ImageWriteOptions**(`Format`, `OnComplete`, `CompressionQuality`, `bOverwriteFile`, `bAsync`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Format` | [`EDesiredImageFormat`](../enums/ue_ue.EDesiredImageFormat.md) |
| `OnComplete` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`bSuccess`: `boolean`) => `void`\> |
| `CompressionQuality` | `number` |
| `bOverwriteFile` | `boolean` |
| `bAsync` | `boolean` |

#### Defined in

[ue/ue.d.ts:38773](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38773)

## Properties

### CompressionQuality

• **CompressionQuality**: `number`

#### Defined in

[ue/ue.d.ts:38776](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38776)

___

### Format

• **Format**: [`EDesiredImageFormat`](../enums/ue_ue.EDesiredImageFormat.md)

#### Defined in

[ue/ue.d.ts:38774](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38774)

___

### OnComplete

• **OnComplete**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`bSuccess`: `boolean`) => `void`\>

#### Defined in

[ue/ue.d.ts:38775](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38775)

___

### \_\_tid\_ImageWriteOptions\_\_

• `Private` **\_\_tid\_ImageWriteOptions\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:38784](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38784)

___

### bAsync

• **bAsync**: `boolean`

#### Defined in

[ue/ue.d.ts:38778](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38778)

___

### bOverwriteFile

• **bOverwriteFile**: `boolean`

#### Defined in

[ue/ue.d.ts:38777](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38777)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:38782](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38782)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:38783](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38783)
