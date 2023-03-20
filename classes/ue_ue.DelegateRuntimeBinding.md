[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DelegateRuntimeBinding

# Class: DelegateRuntimeBinding

[ue/ue](../modules/ue_ue.md).DelegateRuntimeBinding

## Table of contents

### Constructors

- [constructor](ue_ue.DelegateRuntimeBinding.md#constructor)

### Properties

- [FunctionName](ue_ue.DelegateRuntimeBinding.md#functionname)
- [Kind](ue_ue.DelegateRuntimeBinding.md#kind)
- [ObjectName](ue_ue.DelegateRuntimeBinding.md#objectname)
- [PropertyName](ue_ue.DelegateRuntimeBinding.md#propertyname)
- [SourcePath](ue_ue.DelegateRuntimeBinding.md#sourcepath)
- [\_\_tid\_DelegateRuntimeBinding\_\_](ue_ue.DelegateRuntimeBinding.md#__tid_delegateruntimebinding__)

### Methods

- [StaticClass](ue_ue.DelegateRuntimeBinding.md#staticclass)
- [StaticStruct](ue_ue.DelegateRuntimeBinding.md#staticstruct)

## Constructors

### constructor

• **new DelegateRuntimeBinding**()

• **new DelegateRuntimeBinding**(`ObjectName`, `PropertyName`, `FunctionName`, `SourcePath`, `Kind`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ObjectName` | `string` |
| `PropertyName` | `string` |
| `FunctionName` | `string` |
| `SourcePath` | [`DynamicPropertyPath`](ue_ue.DynamicPropertyPath.md) |
| `Kind` | [`EBindingKind`](../enums/ue_ue.EBindingKind.md) |

## Properties

### FunctionName

• **FunctionName**: `string`

___

### Kind

• **Kind**: [`EBindingKind`](../enums/ue_ue.EBindingKind.md)

___

### ObjectName

• **ObjectName**: `string`

___

### PropertyName

• **PropertyName**: `string`

___

### SourcePath

• **SourcePath**: [`DynamicPropertyPath`](ue_ue.DynamicPropertyPath.md)

___

### \_\_tid\_DelegateRuntimeBinding\_\_

• `Private` **\_\_tid\_DelegateRuntimeBinding\_\_**: `boolean`

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
