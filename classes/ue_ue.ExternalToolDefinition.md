[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ExternalToolDefinition

# Class: ExternalToolDefinition

[ue/ue](../modules/ue_ue.md).ExternalToolDefinition

## Table of contents

### Constructors

- [constructor](ue_ue.ExternalToolDefinition.md#constructor)

### Properties

- [CommandLineOptions](ue_ue.ExternalToolDefinition.md#commandlineoptions)
- [ExecutablePath](ue_ue.ExternalToolDefinition.md#executablepath)
- [ScriptDirectory](ue_ue.ExternalToolDefinition.md#scriptdirectory)
- [ScriptExtension](ue_ue.ExternalToolDefinition.md#scriptextension)
- [ToolName](ue_ue.ExternalToolDefinition.md#toolname)
- [WorkingDirectory](ue_ue.ExternalToolDefinition.md#workingdirectory)
- [\_\_tid\_ExternalToolDefinition\_\_](ue_ue.ExternalToolDefinition.md#__tid_externaltooldefinition__)

### Methods

- [StaticClass](ue_ue.ExternalToolDefinition.md#staticclass)
- [StaticStruct](ue_ue.ExternalToolDefinition.md#staticstruct)

## Constructors

### constructor

• **new ExternalToolDefinition**()

• **new ExternalToolDefinition**(`ToolName`, `ExecutablePath`, `CommandLineOptions`, `WorkingDirectory`, `ScriptExtension`, `ScriptDirectory`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ToolName` | `string` |
| `ExecutablePath` | [`FilePath`](ue_ue.FilePath.md) |
| `CommandLineOptions` | `string` |
| `WorkingDirectory` | [`DirectoryPath`](ue_ue.DirectoryPath.md) |
| `ScriptExtension` | `string` |
| `ScriptDirectory` | [`DirectoryPath`](ue_ue.DirectoryPath.md) |

## Properties

### CommandLineOptions

• **CommandLineOptions**: `string`

___

### ExecutablePath

• **ExecutablePath**: [`FilePath`](ue_ue.FilePath.md)

___

### ScriptDirectory

• **ScriptDirectory**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

___

### ScriptExtension

• **ScriptExtension**: `string`

___

### ToolName

• **ToolName**: `string`

___

### WorkingDirectory

• **WorkingDirectory**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

___

### \_\_tid\_ExternalToolDefinition\_\_

• `Private` **\_\_tid\_ExternalToolDefinition\_\_**: `boolean`

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
