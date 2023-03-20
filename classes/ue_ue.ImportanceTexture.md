[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ImportanceTexture

# Class: ImportanceTexture

[ue/ue](../modules/ue_ue.md).ImportanceTexture

## Table of contents

### Constructors

- [constructor](ue_ue.ImportanceTexture.md#constructor)

### Properties

- [ConditionalCDF](ue_ue.ImportanceTexture.md#conditionalcdf)
- [MarginalCDF](ue_ue.ImportanceTexture.md#marginalcdf)
- [NumMips](ue_ue.ImportanceTexture.md#nummips)
- [Size](ue_ue.ImportanceTexture.md#size)
- [Texture](ue_ue.ImportanceTexture.md#texture)
- [TextureData](ue_ue.ImportanceTexture.md#texturedata)
- [Weighting](ue_ue.ImportanceTexture.md#weighting)
- [\_\_tid\_ImportanceTexture\_\_](ue_ue.ImportanceTexture.md#__tid_importancetexture__)

### Methods

- [StaticClass](ue_ue.ImportanceTexture.md#staticclass)
- [StaticStruct](ue_ue.ImportanceTexture.md#staticstruct)

## Constructors

### constructor

• **new ImportanceTexture**()

• **new ImportanceTexture**(`Size`, `NumMips`, `MarginalCDF`, `ConditionalCDF`, `TextureData`, `Texture`, `Weighting`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Size` | [`IntPoint`](ue_ue_s.IntPoint.md) |
| `NumMips` | `number` |
| `MarginalCDF` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `ConditionalCDF` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `TextureData` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Color`](ue_ue_s.Color.md)\> |
| `Texture` | [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Texture2D`](ue_ue.Texture2D.md)\> |
| `Weighting` | [`EImportanceWeight`](../enums/ue_ue.EImportanceWeight.md) |

## Properties

### ConditionalCDF

• **ConditionalCDF**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### MarginalCDF

• **MarginalCDF**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### NumMips

• **NumMips**: `number`

___

### Size

• **Size**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### Texture

• **Texture**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Texture2D`](ue_ue.Texture2D.md)\>

___

### TextureData

• **TextureData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Color`](ue_ue_s.Color.md)\>

___

### Weighting

• **Weighting**: [`EImportanceWeight`](../enums/ue_ue.EImportanceWeight.md)

___

### \_\_tid\_ImportanceTexture\_\_

• `Private` **\_\_tid\_ImportanceTexture\_\_**: `boolean`

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
