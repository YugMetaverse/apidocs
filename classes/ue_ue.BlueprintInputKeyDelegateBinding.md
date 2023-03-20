[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BlueprintInputKeyDelegateBinding

# Class: BlueprintInputKeyDelegateBinding

[ue/ue](../modules/ue_ue.md).BlueprintInputKeyDelegateBinding

## Hierarchy

- [`BlueprintInputDelegateBinding`](ue_ue.BlueprintInputDelegateBinding.md)

  ↳ **`BlueprintInputKeyDelegateBinding`**

## Table of contents

### Constructors

- [constructor](ue_ue.BlueprintInputKeyDelegateBinding.md#constructor)

### Properties

- [FunctionNameToBind](ue_ue.BlueprintInputKeyDelegateBinding.md#functionnametobind)
- [InputChord](ue_ue.BlueprintInputKeyDelegateBinding.md#inputchord)
- [InputKeyEvent](ue_ue.BlueprintInputKeyDelegateBinding.md#inputkeyevent)
- [\_\_tid\_BlueprintInputKeyDelegateBinding\_\_](ue_ue.BlueprintInputKeyDelegateBinding.md#__tid_blueprintinputkeydelegatebinding__)
- [bConsumeInput](ue_ue.BlueprintInputKeyDelegateBinding.md#bconsumeinput)
- [bExecuteWhenPaused](ue_ue.BlueprintInputKeyDelegateBinding.md#bexecutewhenpaused)
- [bOverrideParentBinding](ue_ue.BlueprintInputKeyDelegateBinding.md#boverrideparentbinding)

### Methods

- [StaticClass](ue_ue.BlueprintInputKeyDelegateBinding.md#staticclass)
- [StaticStruct](ue_ue.BlueprintInputKeyDelegateBinding.md#staticstruct)

## Constructors

### constructor

• **new BlueprintInputKeyDelegateBinding**()

#### Overrides

[BlueprintInputDelegateBinding](ue_ue.BlueprintInputDelegateBinding.md).[constructor](ue_ue.BlueprintInputDelegateBinding.md#constructor)

• **new BlueprintInputKeyDelegateBinding**(`InputChord`, `InputKeyEvent`, `FunctionNameToBind`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InputChord` | [`InputChord`](ue_ue.InputChord.md) |
| `InputKeyEvent` | [`EInputEvent`](../enums/ue_ue.EInputEvent.md) |
| `FunctionNameToBind` | `string` |

#### Overrides

[BlueprintInputDelegateBinding](ue_ue.BlueprintInputDelegateBinding.md).[constructor](ue_ue.BlueprintInputDelegateBinding.md#constructor)

## Properties

### FunctionNameToBind

• **FunctionNameToBind**: `string`

___

### InputChord

• **InputChord**: [`InputChord`](ue_ue.InputChord.md)

___

### InputKeyEvent

• **InputKeyEvent**: [`EInputEvent`](../enums/ue_ue.EInputEvent.md)

___

### \_\_tid\_BlueprintInputKeyDelegateBinding\_\_

• `Private` **\_\_tid\_BlueprintInputKeyDelegateBinding\_\_**: `boolean`

___

### bConsumeInput

• **bConsumeInput**: `boolean`

#### Inherited from

[BlueprintInputDelegateBinding](ue_ue.BlueprintInputDelegateBinding.md).[bConsumeInput](ue_ue.BlueprintInputDelegateBinding.md#bconsumeinput)

___

### bExecuteWhenPaused

• **bExecuteWhenPaused**: `boolean`

#### Inherited from

[BlueprintInputDelegateBinding](ue_ue.BlueprintInputDelegateBinding.md).[bExecuteWhenPaused](ue_ue.BlueprintInputDelegateBinding.md#bexecutewhenpaused)

___

### bOverrideParentBinding

• **bOverrideParentBinding**: `boolean`

#### Inherited from

[BlueprintInputDelegateBinding](ue_ue.BlueprintInputDelegateBinding.md).[bOverrideParentBinding](ue_ue.BlueprintInputDelegateBinding.md#boverrideparentbinding)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[BlueprintInputDelegateBinding](ue_ue.BlueprintInputDelegateBinding.md).[StaticClass](ue_ue.BlueprintInputDelegateBinding.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[BlueprintInputDelegateBinding](ue_ue.BlueprintInputDelegateBinding.md).[StaticStruct](ue_ue.BlueprintInputDelegateBinding.md#staticstruct)
