[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / StaticTerrainLayerWeightParameter

# Class: StaticTerrainLayerWeightParameter

[ue/ue](../modules/ue_ue.md).StaticTerrainLayerWeightParameter

## Hierarchy

- [`StaticParameterBase`](ue_ue.StaticParameterBase.md)

  ↳ **`StaticTerrainLayerWeightParameter`**

## Table of contents

### Constructors

- [constructor](ue_ue.StaticTerrainLayerWeightParameter.md#constructor)

### Properties

- [ExpressionGUID](ue_ue.StaticTerrainLayerWeightParameter.md#expressionguid)
- [ParameterInfo](ue_ue.StaticTerrainLayerWeightParameter.md#parameterinfo)
- [WeightmapIndex](ue_ue.StaticTerrainLayerWeightParameter.md#weightmapindex)
- [\_\_tid\_StaticTerrainLayerWeightParameter\_\_](ue_ue.StaticTerrainLayerWeightParameter.md#__tid_staticterrainlayerweightparameter__)
- [bOverride](ue_ue.StaticTerrainLayerWeightParameter.md#boverride)
- [bWeightBasedBlend](ue_ue.StaticTerrainLayerWeightParameter.md#bweightbasedblend)

### Methods

- [StaticClass](ue_ue.StaticTerrainLayerWeightParameter.md#staticclass)
- [StaticStruct](ue_ue.StaticTerrainLayerWeightParameter.md#staticstruct)

## Constructors

### constructor

• **new StaticTerrainLayerWeightParameter**()

#### Overrides

[StaticParameterBase](ue_ue.StaticParameterBase.md).[constructor](ue_ue.StaticParameterBase.md#constructor)

• **new StaticTerrainLayerWeightParameter**(`WeightmapIndex`, `bWeightBasedBlend`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WeightmapIndex` | `number` |
| `bWeightBasedBlend` | `boolean` |

#### Overrides

[StaticParameterBase](ue_ue.StaticParameterBase.md).[constructor](ue_ue.StaticParameterBase.md#constructor)

## Properties

### ExpressionGUID

• **ExpressionGUID**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[StaticParameterBase](ue_ue.StaticParameterBase.md).[ExpressionGUID](ue_ue.StaticParameterBase.md#expressionguid)

___

### ParameterInfo

• **ParameterInfo**: [`MaterialParameterInfo`](ue_ue.MaterialParameterInfo.md)

#### Inherited from

[StaticParameterBase](ue_ue.StaticParameterBase.md).[ParameterInfo](ue_ue.StaticParameterBase.md#parameterinfo)

___

### WeightmapIndex

• **WeightmapIndex**: `number`

___

### \_\_tid\_StaticTerrainLayerWeightParameter\_\_

• `Private` **\_\_tid\_StaticTerrainLayerWeightParameter\_\_**: `boolean`

___

### bOverride

• **bOverride**: `boolean`

#### Inherited from

[StaticParameterBase](ue_ue.StaticParameterBase.md).[bOverride](ue_ue.StaticParameterBase.md#boverride)

___

### bWeightBasedBlend

• **bWeightBasedBlend**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[StaticParameterBase](ue_ue.StaticParameterBase.md).[StaticClass](ue_ue.StaticParameterBase.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[StaticParameterBase](ue_ue.StaticParameterBase.md).[StaticStruct](ue_ue.StaticParameterBase.md#staticstruct)
