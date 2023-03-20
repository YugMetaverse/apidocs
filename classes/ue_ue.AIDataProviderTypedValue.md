[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AIDataProviderTypedValue

# Class: AIDataProviderTypedValue

[ue/ue](../modules/ue_ue.md).AIDataProviderTypedValue

## Hierarchy

- [`AIDataProviderValue`](ue_ue.AIDataProviderValue.md)

  ↳ **`AIDataProviderTypedValue`**

  ↳↳ [`AIDataProviderBoolValue`](ue_ue.AIDataProviderBoolValue.md)

  ↳↳ [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

  ↳↳ [`AIDataProviderIntValue`](ue_ue.AIDataProviderIntValue.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AIDataProviderTypedValue.md#constructor)

### Properties

- [CachedProperty](ue_ue.AIDataProviderTypedValue.md#cachedproperty)
- [DataBinding](ue_ue.AIDataProviderTypedValue.md#databinding)
- [DataField](ue_ue.AIDataProviderTypedValue.md#datafield)
- [PropertyType](ue_ue.AIDataProviderTypedValue.md#propertytype)
- [\_\_tid\_AIDataProviderTypedValue\_\_](ue_ue.AIDataProviderTypedValue.md#__tid_aidataprovidertypedvalue__)

### Methods

- [StaticClass](ue_ue.AIDataProviderTypedValue.md#staticclass)
- [StaticStruct](ue_ue.AIDataProviderTypedValue.md#staticstruct)

## Constructors

### constructor

• **new AIDataProviderTypedValue**()

#### Overrides

[AIDataProviderValue](ue_ue.AIDataProviderValue.md).[constructor](ue_ue.AIDataProviderValue.md#constructor)

• **new AIDataProviderTypedValue**(`PropertyType`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PropertyType` | [`Class`](ue_ue.Class.md) |

#### Overrides

[AIDataProviderValue](ue_ue.AIDataProviderValue.md).[constructor](ue_ue.AIDataProviderValue.md#constructor)

## Properties

### CachedProperty

• **CachedProperty**: [`Property`](ue_ue.Property.md)

#### Inherited from

[AIDataProviderValue](ue_ue.AIDataProviderValue.md).[CachedProperty](ue_ue.AIDataProviderValue.md#cachedproperty)

___

### DataBinding

• **DataBinding**: [`AIDataProvider`](ue_ue.AIDataProvider.md)

#### Inherited from

[AIDataProviderValue](ue_ue.AIDataProviderValue.md).[DataBinding](ue_ue.AIDataProviderValue.md#databinding)

___

### DataField

• **DataField**: `string`

#### Inherited from

[AIDataProviderValue](ue_ue.AIDataProviderValue.md).[DataField](ue_ue.AIDataProviderValue.md#datafield)

___

### PropertyType

• **PropertyType**: [`Class`](ue_ue.Class.md)

___

### \_\_tid\_AIDataProviderTypedValue\_\_

• `Private` **\_\_tid\_AIDataProviderTypedValue\_\_**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AIDataProviderValue](ue_ue.AIDataProviderValue.md).[StaticClass](ue_ue.AIDataProviderValue.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AIDataProviderValue](ue_ue.AIDataProviderValue.md).[StaticStruct](ue_ue.AIDataProviderValue.md#staticstruct)
