[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BlueprintInputActionDelegateBinding

# Class: BlueprintInputActionDelegateBinding

[ue/ue](../modules/ue_ue.md).BlueprintInputActionDelegateBinding

## Hierarchy

- [`BlueprintInputDelegateBinding`](ue_ue.BlueprintInputDelegateBinding.md)

  ↳ **`BlueprintInputActionDelegateBinding`**

## Table of contents

### Constructors

- [constructor](ue_ue.BlueprintInputActionDelegateBinding.md#constructor)

### Properties

- [FunctionNameToBind](ue_ue.BlueprintInputActionDelegateBinding.md#functionnametobind)
- [InputActionName](ue_ue.BlueprintInputActionDelegateBinding.md#inputactionname)
- [InputKeyEvent](ue_ue.BlueprintInputActionDelegateBinding.md#inputkeyevent)
- [\_\_tid\_BlueprintInputActionDelegateBinding\_\_](ue_ue.BlueprintInputActionDelegateBinding.md#__tid_blueprintinputactiondelegatebinding__)
- [bConsumeInput](ue_ue.BlueprintInputActionDelegateBinding.md#bconsumeinput)
- [bExecuteWhenPaused](ue_ue.BlueprintInputActionDelegateBinding.md#bexecutewhenpaused)
- [bOverrideParentBinding](ue_ue.BlueprintInputActionDelegateBinding.md#boverrideparentbinding)

### Methods

- [StaticClass](ue_ue.BlueprintInputActionDelegateBinding.md#staticclass)
- [StaticStruct](ue_ue.BlueprintInputActionDelegateBinding.md#staticstruct)

## Constructors

### constructor

• **new BlueprintInputActionDelegateBinding**()

#### Overrides

[BlueprintInputDelegateBinding](ue_ue.BlueprintInputDelegateBinding.md).[constructor](ue_ue.BlueprintInputDelegateBinding.md#constructor)

• **new BlueprintInputActionDelegateBinding**(`InputActionName`, `InputKeyEvent`, `FunctionNameToBind`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InputActionName` | `string` |
| `InputKeyEvent` | [`EInputEvent`](../enums/ue_ue.EInputEvent.md) |
| `FunctionNameToBind` | `string` |

#### Overrides

[BlueprintInputDelegateBinding](ue_ue.BlueprintInputDelegateBinding.md).[constructor](ue_ue.BlueprintInputDelegateBinding.md#constructor)

## Properties

### FunctionNameToBind

• **FunctionNameToBind**: `string`

___

### InputActionName

• **InputActionName**: `string`

___

### InputKeyEvent

• **InputKeyEvent**: [`EInputEvent`](../enums/ue_ue.EInputEvent.md)

___

### \_\_tid\_BlueprintInputActionDelegateBinding\_\_

• `Private` **\_\_tid\_BlueprintInputActionDelegateBinding\_\_**: `boolean`

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
