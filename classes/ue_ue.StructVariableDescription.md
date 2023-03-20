[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / StructVariableDescription

# Class: StructVariableDescription

[ue/ue](../modules/ue_ue.md).StructVariableDescription

## Table of contents

### Constructors

- [constructor](ue_ue.StructVariableDescription.md#constructor)

### Properties

- [Category](ue_ue.StructVariableDescription.md#category)
- [ContainerType](ue_ue.StructVariableDescription.md#containertype)
- [CurrentDefaultValue](ue_ue.StructVariableDescription.md#currentdefaultvalue)
- [DefaultValue](ue_ue.StructVariableDescription.md#defaultvalue)
- [FriendlyName](ue_ue.StructVariableDescription.md#friendlyname)
- [PinValueType](ue_ue.StructVariableDescription.md#pinvaluetype)
- [SubCategory](ue_ue.StructVariableDescription.md#subcategory)
- [SubCategoryObject](ue_ue.StructVariableDescription.md#subcategoryobject)
- [ToolTip](ue_ue.StructVariableDescription.md#tooltip)
- [VarGuid](ue_ue.StructVariableDescription.md#varguid)
- [VarName](ue_ue.StructVariableDescription.md#varname)
- [\_\_tid\_StructVariableDescription\_\_](ue_ue.StructVariableDescription.md#__tid_structvariabledescription__)
- [bDontEditOnInstance](ue_ue.StructVariableDescription.md#bdonteditoninstance)
- [bEnable3dWidget](ue_ue.StructVariableDescription.md#benable3dwidget)
- [bEnableMultiLineText](ue_ue.StructVariableDescription.md#benablemultilinetext)
- [bEnableSaveGame](ue_ue.StructVariableDescription.md#benablesavegame)
- [bInvalidMember](ue_ue.StructVariableDescription.md#binvalidmember)
- [bIsArray](ue_ue.StructVariableDescription.md#bisarray)
- [bIsMap](ue_ue.StructVariableDescription.md#bismap)
- [bIsSet](ue_ue.StructVariableDescription.md#bisset)

### Methods

- [StaticClass](ue_ue.StructVariableDescription.md#staticclass)
- [StaticStruct](ue_ue.StructVariableDescription.md#staticstruct)

## Constructors

### constructor

• **new StructVariableDescription**()

• **new StructVariableDescription**(`VarName`, `VarGuid`, `FriendlyName`, `DefaultValue`, `Category`, `SubCategory`, `SubCategoryObject`, `PinValueType`, `ContainerType`, `bIsArray`, `bIsSet`, `bIsMap`, `bInvalidMember`, `bDontEditOnInstance`, `bEnableSaveGame`, `bEnableMultiLineText`, `bEnable3dWidget`, `CurrentDefaultValue`, `ToolTip`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VarName` | `string` |
| `VarGuid` | [`Guid`](ue_ue_s.Guid.md) |
| `FriendlyName` | `string` |
| `DefaultValue` | `string` |
| `Category` | `string` |
| `SubCategory` | `string` |
| `SubCategoryObject` | [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`Object`](ue_ue.Object.md)\> |
| `PinValueType` | [`EdGraphTerminalType`](ue_ue.EdGraphTerminalType.md) |
| `ContainerType` | [`EPinContainerType`](../enums/ue_ue.EPinContainerType.md) |
| `bIsArray` | `boolean` |
| `bIsSet` | `boolean` |
| `bIsMap` | `boolean` |
| `bInvalidMember` | `boolean` |
| `bDontEditOnInstance` | `boolean` |
| `bEnableSaveGame` | `boolean` |
| `bEnableMultiLineText` | `boolean` |
| `bEnable3dWidget` | `boolean` |
| `CurrentDefaultValue` | `string` |
| `ToolTip` | `string` |

## Properties

### Category

• **Category**: `string`

___

### ContainerType

• **ContainerType**: [`EPinContainerType`](../enums/ue_ue.EPinContainerType.md)

___

### CurrentDefaultValue

• **CurrentDefaultValue**: `string`

___

### DefaultValue

• **DefaultValue**: `string`

___

### FriendlyName

• **FriendlyName**: `string`

___

### PinValueType

• **PinValueType**: [`EdGraphTerminalType`](ue_ue.EdGraphTerminalType.md)

___

### SubCategory

• **SubCategory**: `string`

___

### SubCategoryObject

• **SubCategoryObject**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`Object`](ue_ue.Object.md)\>

___

### ToolTip

• **ToolTip**: `string`

___

### VarGuid

• **VarGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### VarName

• **VarName**: `string`

___

### \_\_tid\_StructVariableDescription\_\_

• `Private` **\_\_tid\_StructVariableDescription\_\_**: `boolean`

___

### bDontEditOnInstance

• **bDontEditOnInstance**: `boolean`

___

### bEnable3dWidget

• **bEnable3dWidget**: `boolean`

___

### bEnableMultiLineText

• **bEnableMultiLineText**: `boolean`

___

### bEnableSaveGame

• **bEnableSaveGame**: `boolean`

___

### bInvalidMember

• **bInvalidMember**: `boolean`

___

### bIsArray

• **bIsArray**: `boolean`

___

### bIsMap

• **bIsMap**: `boolean`

___

### bIsSet

• **bIsSet**: `boolean`

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
