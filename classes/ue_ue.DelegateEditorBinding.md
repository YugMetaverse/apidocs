[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DelegateEditorBinding

# Class: DelegateEditorBinding

[ue/ue](../modules/ue_ue.md).DelegateEditorBinding

## Table of contents

### Constructors

- [constructor](ue_ue.DelegateEditorBinding.md#constructor)

### Properties

- [FunctionName](ue_ue.DelegateEditorBinding.md#functionname)
- [Kind](ue_ue.DelegateEditorBinding.md#kind)
- [MemberGuid](ue_ue.DelegateEditorBinding.md#memberguid)
- [ObjectName](ue_ue.DelegateEditorBinding.md#objectname)
- [PropertyName](ue_ue.DelegateEditorBinding.md#propertyname)
- [SourcePath](ue_ue.DelegateEditorBinding.md#sourcepath)
- [SourceProperty](ue_ue.DelegateEditorBinding.md#sourceproperty)
- [\_\_tid\_DelegateEditorBinding\_\_](ue_ue.DelegateEditorBinding.md#__tid_delegateeditorbinding__)

### Methods

- [StaticClass](ue_ue.DelegateEditorBinding.md#staticclass)
- [StaticStruct](ue_ue.DelegateEditorBinding.md#staticstruct)

## Constructors

### constructor

• **new DelegateEditorBinding**()

• **new DelegateEditorBinding**(`ObjectName`, `PropertyName`, `FunctionName`, `SourceProperty`, `SourcePath`, `MemberGuid`, `Kind`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ObjectName` | `string` |
| `PropertyName` | `string` |
| `FunctionName` | `string` |
| `SourceProperty` | `string` |
| `SourcePath` | [`EditorPropertyPath`](ue_ue.EditorPropertyPath.md) |
| `MemberGuid` | [`Guid`](ue_ue_s.Guid.md) |
| `Kind` | [`EBindingKind`](../enums/ue_ue.EBindingKind.md) |

## Properties

### FunctionName

• **FunctionName**: `string`

___

### Kind

• **Kind**: [`EBindingKind`](../enums/ue_ue.EBindingKind.md)

___

### MemberGuid

• **MemberGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### ObjectName

• **ObjectName**: `string`

___

### PropertyName

• **PropertyName**: `string`

___

### SourcePath

• **SourcePath**: [`EditorPropertyPath`](ue_ue.EditorPropertyPath.md)

___

### SourceProperty

• **SourceProperty**: `string`

___

### \_\_tid\_DelegateEditorBinding\_\_

• `Private` **\_\_tid\_DelegateEditorBinding\_\_**: `boolean`

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
