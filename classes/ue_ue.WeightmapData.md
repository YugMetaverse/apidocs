[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / WeightmapData

# Class: WeightmapData

[ue/ue](../modules/ue_ue.md).WeightmapData

## Table of contents

### Constructors

- [constructor](ue_ue.WeightmapData.md#constructor)

### Properties

- [LayerAllocations](ue_ue.WeightmapData.md#layerallocations)
- [TextureUsages](ue_ue.WeightmapData.md#textureusages)
- [Textures](ue_ue.WeightmapData.md#textures)
- [\_\_tid\_WeightmapData\_\_](ue_ue.WeightmapData.md#__tid_weightmapdata__)

### Methods

- [StaticClass](ue_ue.WeightmapData.md#staticclass)
- [StaticStruct](ue_ue.WeightmapData.md#staticstruct)

## Constructors

### constructor

• **new WeightmapData**()

• **new WeightmapData**(`Textures`, `LayerAllocations`, `TextureUsages`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Textures` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Texture2D`](ue_ue.Texture2D.md)\> |
| `LayerAllocations` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`WeightmapLayerAllocationInfo`](ue_ue.WeightmapLayerAllocationInfo.md)\> |
| `TextureUsages` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeWeightmapUsage`](ue_ue.LandscapeWeightmapUsage.md)\> |

## Properties

### LayerAllocations

• **LayerAllocations**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`WeightmapLayerAllocationInfo`](ue_ue.WeightmapLayerAllocationInfo.md)\>

___

### TextureUsages

• **TextureUsages**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeWeightmapUsage`](ue_ue.LandscapeWeightmapUsage.md)\>

___

### Textures

• **Textures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Texture2D`](ue_ue.Texture2D.md)\>

___

### \_\_tid\_WeightmapData\_\_

• `Private` **\_\_tid\_WeightmapData\_\_**: `boolean`

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
