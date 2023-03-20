[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PropertyPathSegment

# Class: PropertyPathSegment

[ue/ue](../modules/ue_ue.md).PropertyPathSegment

## Table of contents

### Constructors

- [constructor](ue_ue.PropertyPathSegment.md#constructor)

### Properties

- [ArrayIndex](ue_ue.PropertyPathSegment.md#arrayindex)
- [Field](ue_ue.PropertyPathSegment.md#field)
- [Name](ue_ue.PropertyPathSegment.md#name)
- [Struct](ue_ue.PropertyPathSegment.md#struct)
- [\_\_tid\_PropertyPathSegment\_\_](ue_ue.PropertyPathSegment.md#__tid_propertypathsegment__)

### Methods

- [StaticClass](ue_ue.PropertyPathSegment.md#staticclass)
- [StaticStruct](ue_ue.PropertyPathSegment.md#staticstruct)

## Constructors

### constructor

• **new PropertyPathSegment**()

• **new PropertyPathSegment**(`Name`, `ArrayIndex`, `Struct`, `Field`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `ArrayIndex` | `number` |
| `Struct` | [`Struct`](ue_ue.Struct.md) |
| `Field` | [`Field`](ue_ue.Field.md) |

## Properties

### ArrayIndex

• **ArrayIndex**: `number`

___

### Field

• **Field**: [`Field`](ue_ue.Field.md)

___

### Name

• **Name**: `string`

___

### Struct

• **Struct**: [`Struct`](ue_ue.Struct.md)

___

### \_\_tid\_PropertyPathSegment\_\_

• `Private` **\_\_tid\_PropertyPathSegment\_\_**: `boolean`

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
