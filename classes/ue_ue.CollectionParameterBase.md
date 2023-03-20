[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CollectionParameterBase

# Class: CollectionParameterBase

[ue/ue](../modules/ue_ue.md).CollectionParameterBase

## Hierarchy

- **`CollectionParameterBase`**

  ↳ [`CollectionScalarParameter`](ue_ue.CollectionScalarParameter.md)

  ↳ [`CollectionVectorParameter`](ue_ue.CollectionVectorParameter.md)

## Table of contents

### Constructors

- [constructor](ue_ue.CollectionParameterBase.md#constructor)

### Properties

- [Id](ue_ue.CollectionParameterBase.md#id)
- [ParameterName](ue_ue.CollectionParameterBase.md#parametername)
- [\_\_tid\_CollectionParameterBase\_\_](ue_ue.CollectionParameterBase.md#__tid_collectionparameterbase__)

### Methods

- [StaticClass](ue_ue.CollectionParameterBase.md#staticclass)
- [StaticStruct](ue_ue.CollectionParameterBase.md#staticstruct)

## Constructors

### constructor

• **new CollectionParameterBase**()

• **new CollectionParameterBase**(`ParameterName`, `Id`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |
| `Id` | [`Guid`](ue_ue_s.Guid.md) |

## Properties

### Id

• **Id**: [`Guid`](ue_ue_s.Guid.md)

___

### ParameterName

• **ParameterName**: `string`

___

### \_\_tid\_CollectionParameterBase\_\_

• `Private` **\_\_tid\_CollectionParameterBase\_\_**: `boolean`

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
