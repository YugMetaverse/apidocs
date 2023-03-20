[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AIDynamicParam

# Class: AIDynamicParam

[ue/ue](../modules/ue_ue.md).AIDynamicParam

## Table of contents

### Constructors

- [constructor](ue_ue.AIDynamicParam.md#constructor)

### Properties

- [BBKey](ue_ue.AIDynamicParam.md#bbkey)
- [ParamName](ue_ue.AIDynamicParam.md#paramname)
- [ParamType](ue_ue.AIDynamicParam.md#paramtype)
- [Value](ue_ue.AIDynamicParam.md#value)
- [\_\_tid\_AIDynamicParam\_\_](ue_ue.AIDynamicParam.md#__tid_aidynamicparam__)

### Methods

- [StaticClass](ue_ue.AIDynamicParam.md#staticclass)
- [StaticStruct](ue_ue.AIDynamicParam.md#staticstruct)

## Constructors

### constructor

• **new AIDynamicParam**()

• **new AIDynamicParam**(`ParamName`, `ParamType`, `Value`, `BBKey`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParamName` | `string` |
| `ParamType` | [`EAIParamType`](../enums/ue_ue.EAIParamType.md) |
| `Value` | `number` |
| `BBKey` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |

## Properties

### BBKey

• **BBKey**: [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md)

___

### ParamName

• **ParamName**: `string`

___

### ParamType

• **ParamType**: [`EAIParamType`](../enums/ue_ue.EAIParamType.md)

___

### Value

• **Value**: `number`

___

### \_\_tid\_AIDynamicParam\_\_

• `Private` **\_\_tid\_AIDynamicParam\_\_**: `boolean`

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
