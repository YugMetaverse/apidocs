[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ComponentKey

# Class: ComponentKey

[ue/ue](../modules/ue_ue.md).ComponentKey

## Table of contents

### Constructors

- [constructor](ue_ue.ComponentKey.md#constructor)

### Properties

- [AssociatedGuid](ue_ue.ComponentKey.md#associatedguid)
- [OwnerClass](ue_ue.ComponentKey.md#ownerclass)
- [SCSVariableName](ue_ue.ComponentKey.md#scsvariablename)
- [\_\_tid\_ComponentKey\_\_](ue_ue.ComponentKey.md#__tid_componentkey__)

### Methods

- [StaticClass](ue_ue.ComponentKey.md#staticclass)
- [StaticStruct](ue_ue.ComponentKey.md#staticstruct)

## Constructors

### constructor

• **new ComponentKey**()

• **new ComponentKey**(`OwnerClass`, `SCSVariableName`, `AssociatedGuid`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerClass` | [`Class`](ue_ue.Class.md) |
| `SCSVariableName` | `string` |
| `AssociatedGuid` | [`Guid`](ue_ue_s.Guid.md) |

## Properties

### AssociatedGuid

• **AssociatedGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### OwnerClass

• **OwnerClass**: [`Class`](ue_ue.Class.md)

___

### SCSVariableName

• **SCSVariableName**: `string`

___

### \_\_tid\_ComponentKey\_\_

• `Private` **\_\_tid\_ComponentKey\_\_**: `boolean`

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
