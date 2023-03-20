[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ExposedValueHandler

# Class: ExposedValueHandler

[ue/ue](../modules/ue_ue.md).ExposedValueHandler

## Table of contents

### Constructors

- [constructor](ue_ue.ExposedValueHandler.md#constructor)

### Properties

- [BoundFunction](ue_ue.ExposedValueHandler.md#boundfunction)
- [CopyRecords](ue_ue.ExposedValueHandler.md#copyrecords)
- [Function](ue_ue.ExposedValueHandler.md#function)
- [ValueHandlerNodeProperty](ue_ue.ExposedValueHandler.md#valuehandlernodeproperty)
- [\_\_tid\_ExposedValueHandler\_\_](ue_ue.ExposedValueHandler.md#__tid_exposedvaluehandler__)

### Methods

- [StaticClass](ue_ue.ExposedValueHandler.md#staticclass)
- [StaticStruct](ue_ue.ExposedValueHandler.md#staticstruct)

## Constructors

### constructor

• **new ExposedValueHandler**()

• **new ExposedValueHandler**(`BoundFunction`, `CopyRecords`, `Function`, `ValueHandlerNodeProperty`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoundFunction` | `string` |
| `CopyRecords` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ExposedValueCopyRecord`](ue_ue.ExposedValueCopyRecord.md)\> |
| `Function` | [`Function`](ue_ue.Function.md) |
| `ValueHandlerNodeProperty` | [`StructProperty`](ue_ue.StructProperty.md) |

## Properties

### BoundFunction

• **BoundFunction**: `string`

___

### CopyRecords

• **CopyRecords**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ExposedValueCopyRecord`](ue_ue.ExposedValueCopyRecord.md)\>

___

### Function

• **Function**: [`Function`](ue_ue.Function.md)

___

### ValueHandlerNodeProperty

• **ValueHandlerNodeProperty**: [`StructProperty`](ue_ue.StructProperty.md)

___

### \_\_tid\_ExposedValueHandler\_\_

• `Private` **\_\_tid\_ExposedValueHandler\_\_**: `boolean`

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
