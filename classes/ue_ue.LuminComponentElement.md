[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LuminComponentElement

# Class: LuminComponentElement

[ue/ue](../modules/ue_ue.md).LuminComponentElement

## Table of contents

### Constructors

- [constructor](ue_ue.LuminComponentElement.md#constructor)

### Properties

- [ComponentType](ue_ue.LuminComponentElement.md#componenttype)
- [ExecutableName](ue_ue.LuminComponentElement.md#executablename)
- [ExtraComponentSubElements](ue_ue.LuminComponentElement.md#extracomponentsubelements)
- [Name](ue_ue.LuminComponentElement.md#name)
- [VisibleName](ue_ue.LuminComponentElement.md#visiblename)
- [\_\_tid\_LuminComponentElement\_\_](ue_ue.LuminComponentElement.md#__tid_lumincomponentelement__)

### Methods

- [StaticClass](ue_ue.LuminComponentElement.md#staticclass)
- [StaticStruct](ue_ue.LuminComponentElement.md#staticstruct)

## Constructors

### constructor

• **new LuminComponentElement**()

• **new LuminComponentElement**(`Name`, `VisibleName`, `ExecutableName`, `ComponentType`, `ExtraComponentSubElements`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `VisibleName` | `string` |
| `ExecutableName` | `string` |
| `ComponentType` | [`ELuminComponentType`](../enums/ue_ue.ELuminComponentType.md) |
| `ExtraComponentSubElements` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LuminComponentSubElement`](ue_ue.LuminComponentSubElement.md)\> |

## Properties

### ComponentType

• **ComponentType**: [`ELuminComponentType`](../enums/ue_ue.ELuminComponentType.md)

___

### ExecutableName

• **ExecutableName**: `string`

___

### ExtraComponentSubElements

• **ExtraComponentSubElements**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LuminComponentSubElement`](ue_ue.LuminComponentSubElement.md)\>

___

### Name

• **Name**: `string`

___

### VisibleName

• **VisibleName**: `string`

___

### \_\_tid\_LuminComponentElement\_\_

• `Private` **\_\_tid\_LuminComponentElement\_\_**: `boolean`

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
