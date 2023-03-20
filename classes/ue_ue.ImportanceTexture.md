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

#### Defined in

[ue/ue.d.ts:38850](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38850)

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

#### Defined in

[ue/ue.d.ts:38851](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38851)

## Properties

### ConditionalCDF

• **ConditionalCDF**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:38855](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38855)

___

### MarginalCDF

• **MarginalCDF**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:38854](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38854)

___

### NumMips

• **NumMips**: `number`

#### Defined in

[ue/ue.d.ts:38853](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38853)

___

### Size

• **Size**: [`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:38852](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38852)

___

### Texture

• **Texture**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Texture2D`](ue_ue.Texture2D.md)\>

#### Defined in

[ue/ue.d.ts:38857](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38857)

___

### TextureData

• **TextureData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Color`](ue_ue_s.Color.md)\>

#### Defined in

[ue/ue.d.ts:38856](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38856)

___

### Weighting

• **Weighting**: [`EImportanceWeight`](../enums/ue_ue.EImportanceWeight.md)

#### Defined in

[ue/ue.d.ts:38858](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38858)

___

### \_\_tid\_ImportanceTexture\_\_

• `Private` **\_\_tid\_ImportanceTexture\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:38864](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38864)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:38862](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38862)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:38863](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38863)
