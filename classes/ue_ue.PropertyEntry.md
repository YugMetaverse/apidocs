[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PropertyEntry

# Class: PropertyEntry

[ue/ue](../modules/ue_ue.md).PropertyEntry

## Table of contents

### Constructors

- [constructor](ue_ue.PropertyEntry.md#constructor)

### Properties

- [ConstantValue](ue_ue.PropertyEntry.md#constantvalue)
- [CustomSize](ue_ue.PropertyEntry.md#customsize)
- [Property](ue_ue.PropertyEntry.md#property)
- [\_\_tid\_PropertyEntry\_\_](ue_ue.PropertyEntry.md#__tid_propertyentry__)
- [bUseConstantValue](ue_ue.PropertyEntry.md#buseconstantvalue)
- [bUseCustomSize](ue_ue.PropertyEntry.md#busecustomsize)

### Methods

- [StaticClass](ue_ue.PropertyEntry.md#staticclass)
- [StaticStruct](ue_ue.PropertyEntry.md#staticstruct)

## Constructors

### constructor

• **new PropertyEntry**()

• **new PropertyEntry**(`Property`, `bUseCustomSize`, `CustomSize`, `bUseConstantValue`, `ConstantValue`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Property` | [`EMaterialProperty`](../enums/ue_ue.EMaterialProperty.md) |
| `bUseCustomSize` | `boolean` |
| `CustomSize` | [`IntPoint`](ue_ue_s.IntPoint.md) |
| `bUseConstantValue` | `boolean` |
| `ConstantValue` | `number` |

## Properties

### ConstantValue

• **ConstantValue**: `number`

___

### CustomSize

• **CustomSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### Property

• **Property**: [`EMaterialProperty`](../enums/ue_ue.EMaterialProperty.md)

___

### \_\_tid\_PropertyEntry\_\_

• `Private` **\_\_tid\_PropertyEntry\_\_**: `boolean`

___

### bUseConstantValue

• **bUseConstantValue**: `boolean`

___

### bUseCustomSize

• **bUseCustomSize**: `boolean`

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
