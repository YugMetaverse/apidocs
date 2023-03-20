[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / StaticParameterSet

# Class: StaticParameterSet

[ue/ue](../modules/ue_ue.md).StaticParameterSet

## Table of contents

### Constructors

- [constructor](ue_ue.StaticParameterSet.md#constructor)

### Properties

- [MaterialLayersParameters](ue_ue.StaticParameterSet.md#materiallayersparameters)
- [StaticComponentMaskParameters](ue_ue.StaticParameterSet.md#staticcomponentmaskparameters)
- [StaticSwitchParameters](ue_ue.StaticParameterSet.md#staticswitchparameters)
- [TerrainLayerWeightParameters](ue_ue.StaticParameterSet.md#terrainlayerweightparameters)
- [\_\_tid\_StaticParameterSet\_\_](ue_ue.StaticParameterSet.md#__tid_staticparameterset__)

### Methods

- [StaticClass](ue_ue.StaticParameterSet.md#staticclass)
- [StaticStruct](ue_ue.StaticParameterSet.md#staticstruct)

## Constructors

### constructor

• **new StaticParameterSet**()

• **new StaticParameterSet**(`StaticSwitchParameters`, `StaticComponentMaskParameters`, `TerrainLayerWeightParameters`, `MaterialLayersParameters`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `StaticSwitchParameters` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticSwitchParameter`](ue_ue.StaticSwitchParameter.md)\> |
| `StaticComponentMaskParameters` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticComponentMaskParameter`](ue_ue.StaticComponentMaskParameter.md)\> |
| `TerrainLayerWeightParameters` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticTerrainLayerWeightParameter`](ue_ue.StaticTerrainLayerWeightParameter.md)\> |
| `MaterialLayersParameters` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticMaterialLayersParameter`](ue_ue.StaticMaterialLayersParameter.md)\> |

## Properties

### MaterialLayersParameters

• **MaterialLayersParameters**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticMaterialLayersParameter`](ue_ue.StaticMaterialLayersParameter.md)\>

___

### StaticComponentMaskParameters

• **StaticComponentMaskParameters**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticComponentMaskParameter`](ue_ue.StaticComponentMaskParameter.md)\>

___

### StaticSwitchParameters

• **StaticSwitchParameters**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticSwitchParameter`](ue_ue.StaticSwitchParameter.md)\>

___

### TerrainLayerWeightParameters

• **TerrainLayerWeightParameters**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticTerrainLayerWeightParameter`](ue_ue.StaticTerrainLayerWeightParameter.md)\>

___

### \_\_tid\_StaticParameterSet\_\_

• `Private` **\_\_tid\_StaticParameterSet\_\_**: `boolean`

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
