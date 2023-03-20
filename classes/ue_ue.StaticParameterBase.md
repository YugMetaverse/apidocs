[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / StaticParameterBase

# Class: StaticParameterBase

[ue/ue](../modules/ue_ue.md).StaticParameterBase

## Hierarchy

- **`StaticParameterBase`**

  ↳ [`StaticSwitchParameter`](ue_ue.StaticSwitchParameter.md)

  ↳ [`StaticComponentMaskParameter`](ue_ue.StaticComponentMaskParameter.md)

  ↳ [`StaticTerrainLayerWeightParameter`](ue_ue.StaticTerrainLayerWeightParameter.md)

  ↳ [`StaticMaterialLayersParameter`](ue_ue.StaticMaterialLayersParameter.md)

## Table of contents

### Constructors

- [constructor](ue_ue.StaticParameterBase.md#constructor)

### Properties

- [ExpressionGUID](ue_ue.StaticParameterBase.md#expressionguid)
- [ParameterInfo](ue_ue.StaticParameterBase.md#parameterinfo)
- [\_\_tid\_StaticParameterBase\_\_](ue_ue.StaticParameterBase.md#__tid_staticparameterbase__)
- [bOverride](ue_ue.StaticParameterBase.md#boverride)

### Methods

- [StaticClass](ue_ue.StaticParameterBase.md#staticclass)
- [StaticStruct](ue_ue.StaticParameterBase.md#staticstruct)

## Constructors

### constructor

• **new StaticParameterBase**()

• **new StaticParameterBase**(`ParameterInfo`, `bOverride`, `ExpressionGUID`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterInfo` | [`MaterialParameterInfo`](ue_ue.MaterialParameterInfo.md) |
| `bOverride` | `boolean` |
| `ExpressionGUID` | [`Guid`](ue_ue_s.Guid.md) |

## Properties

### ExpressionGUID

• **ExpressionGUID**: [`Guid`](ue_ue_s.Guid.md)

___

### ParameterInfo

• **ParameterInfo**: [`MaterialParameterInfo`](ue_ue.MaterialParameterInfo.md)

___

### \_\_tid\_StaticParameterBase\_\_

• `Private` **\_\_tid\_StaticParameterBase\_\_**: `boolean`

___

### bOverride

• **bOverride**: `boolean`

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
