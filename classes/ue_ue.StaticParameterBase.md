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

#### Defined in

[ue/ue.d.ts:2035](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2035)

• **new StaticParameterBase**(`ParameterInfo`, `bOverride`, `ExpressionGUID`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterInfo` | [`MaterialParameterInfo`](ue_ue.MaterialParameterInfo.md) |
| `bOverride` | `boolean` |
| `ExpressionGUID` | [`Guid`](ue_ue_s.Guid.md) |

#### Defined in

[ue/ue.d.ts:2036](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2036)

## Properties

### ExpressionGUID

• **ExpressionGUID**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:2039](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2039)

___

### ParameterInfo

• **ParameterInfo**: [`MaterialParameterInfo`](ue_ue.MaterialParameterInfo.md)

#### Defined in

[ue/ue.d.ts:2037](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2037)

___

### \_\_tid\_StaticParameterBase\_\_

• `Private` **\_\_tid\_StaticParameterBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:2045](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2045)

___

### bOverride

• **bOverride**: `boolean`

#### Defined in

[ue/ue.d.ts:2038](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2038)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:2043](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2043)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:2044](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2044)
