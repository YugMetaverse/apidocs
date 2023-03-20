[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CachedPropertyPath

# Class: CachedPropertyPath

[ue/ue](../modules/ue_ue.md).CachedPropertyPath

## Hierarchy

- **`CachedPropertyPath`**

  ↳ [`DynamicPropertyPath`](ue_ue.DynamicPropertyPath.md)

## Table of contents

### Constructors

- [constructor](ue_ue.CachedPropertyPath.md#constructor)

### Properties

- [CachedFunction](ue_ue.CachedPropertyPath.md#cachedfunction)
- [Segments](ue_ue.CachedPropertyPath.md#segments)
- [\_\_tid\_CachedPropertyPath\_\_](ue_ue.CachedPropertyPath.md#__tid_cachedpropertypath__)

### Methods

- [StaticClass](ue_ue.CachedPropertyPath.md#staticclass)
- [StaticStruct](ue_ue.CachedPropertyPath.md#staticstruct)

## Constructors

### constructor

• **new CachedPropertyPath**()

• **new CachedPropertyPath**(`Segments`, `CachedFunction`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Segments` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyPathSegment`](ue_ue.PropertyPathSegment.md)\> |
| `CachedFunction` | [`Function`](ue_ue.Function.md) |

## Properties

### CachedFunction

• **CachedFunction**: [`Function`](ue_ue.Function.md)

___

### Segments

• **Segments**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyPathSegment`](ue_ue.PropertyPathSegment.md)\>

___

### \_\_tid\_CachedPropertyPath\_\_

• `Private` **\_\_tid\_CachedPropertyPath\_\_**: `boolean`

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
