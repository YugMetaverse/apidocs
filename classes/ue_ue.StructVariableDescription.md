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

#### Defined in

[ue/ue.d.ts:64883](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64883)

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

#### Defined in

[ue/ue.d.ts:64884](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64884)

## Properties

### Category

• **Category**: `string`

#### Defined in

[ue/ue.d.ts:64889](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64889)

___

### ContainerType

• **ContainerType**: [`EPinContainerType`](../enums/ue_ue.EPinContainerType.md)

#### Defined in

[ue/ue.d.ts:64893](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64893)

___

### CurrentDefaultValue

• **CurrentDefaultValue**: `string`

#### Defined in

[ue/ue.d.ts:64902](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64902)

___

### DefaultValue

• **DefaultValue**: `string`

#### Defined in

[ue/ue.d.ts:64888](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64888)

___

### FriendlyName

• **FriendlyName**: `string`

#### Defined in

[ue/ue.d.ts:64887](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64887)

___

### PinValueType

• **PinValueType**: [`EdGraphTerminalType`](ue_ue.EdGraphTerminalType.md)

#### Defined in

[ue/ue.d.ts:64892](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64892)

___

### SubCategory

• **SubCategory**: `string`

#### Defined in

[ue/ue.d.ts:64890](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64890)

___

### SubCategoryObject

• **SubCategoryObject**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:64891](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64891)

___

### ToolTip

• **ToolTip**: `string`

#### Defined in

[ue/ue.d.ts:64903](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64903)

___

### VarGuid

• **VarGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:64886](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64886)

___

### VarName

• **VarName**: `string`

#### Defined in

[ue/ue.d.ts:64885](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64885)

___

### \_\_tid\_StructVariableDescription\_\_

• `Private` **\_\_tid\_StructVariableDescription\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:64909](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64909)

___

### bDontEditOnInstance

• **bDontEditOnInstance**: `boolean`

#### Defined in

[ue/ue.d.ts:64898](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64898)

___

### bEnable3dWidget

• **bEnable3dWidget**: `boolean`

#### Defined in

[ue/ue.d.ts:64901](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64901)

___

### bEnableMultiLineText

• **bEnableMultiLineText**: `boolean`

#### Defined in

[ue/ue.d.ts:64900](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64900)

___

### bEnableSaveGame

• **bEnableSaveGame**: `boolean`

#### Defined in

[ue/ue.d.ts:64899](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64899)

___

### bInvalidMember

• **bInvalidMember**: `boolean`

#### Defined in

[ue/ue.d.ts:64897](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64897)

___

### bIsArray

• **bIsArray**: `boolean`

#### Defined in

[ue/ue.d.ts:64894](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64894)

___

### bIsMap

• **bIsMap**: `boolean`

#### Defined in

[ue/ue.d.ts:64896](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64896)

___

### bIsSet

• **bIsSet**: `boolean`

#### Defined in

[ue/ue.d.ts:64895](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64895)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:64907](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64907)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:64908](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64908)
