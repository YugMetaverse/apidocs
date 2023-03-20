[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FontData

# Class: FontData

[ue/ue](../modules/ue_ue.md).FontData

## Table of contents

### Constructors

- [constructor](ue_ue.FontData.md#constructor)

### Properties

- [BulkDataPtr](ue_ue.FontData.md#bulkdataptr)
- [FontData](ue_ue.FontData.md#fontdata)
- [FontFaceAsset](ue_ue.FontData.md#fontfaceasset)
- [FontFilename](ue_ue.FontData.md#fontfilename)
- [Hinting](ue_ue.FontData.md#hinting)
- [LoadingPolicy](ue_ue.FontData.md#loadingpolicy)
- [SubFaceIndex](ue_ue.FontData.md#subfaceindex)
- [\_\_tid\_FontData\_\_](ue_ue.FontData.md#__tid_fontdata__)

### Methods

- [StaticClass](ue_ue.FontData.md#staticclass)
- [StaticStruct](ue_ue.FontData.md#staticstruct)

## Constructors

### constructor

• **new FontData**()

• **new FontData**(`FontFilename`, `Hinting`, `LoadingPolicy`, `SubFaceIndex`, `FontFaceAsset`, `BulkDataPtr`, `FontData`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `FontFilename` | `string` |
| `Hinting` | [`EFontHinting`](../enums/ue_ue.EFontHinting.md) |
| `LoadingPolicy` | [`EFontLoadingPolicy`](../enums/ue_ue.EFontLoadingPolicy.md) |
| `SubFaceIndex` | `number` |
| `FontFaceAsset` | [`Object`](ue_ue.Object.md) |
| `BulkDataPtr` | [`FontBulkData`](ue_ue.FontBulkData.md) |
| `FontData` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

## Properties

### BulkDataPtr

• **BulkDataPtr**: [`FontBulkData`](ue_ue.FontBulkData.md)

___

### FontData

• **FontData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### FontFaceAsset

• **FontFaceAsset**: [`Object`](ue_ue.Object.md)

___

### FontFilename

• **FontFilename**: `string`

___

### Hinting

• **Hinting**: [`EFontHinting`](../enums/ue_ue.EFontHinting.md)

___

### LoadingPolicy

• **LoadingPolicy**: [`EFontLoadingPolicy`](../enums/ue_ue.EFontLoadingPolicy.md)

___

### SubFaceIndex

• **SubFaceIndex**: `number`

___

### \_\_tid\_FontData\_\_

• `Private` **\_\_tid\_FontData\_\_**: `boolean`

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
