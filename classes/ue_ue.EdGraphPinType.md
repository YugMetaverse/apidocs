[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EdGraphPinType

# Class: EdGraphPinType

[ue/ue](../modules/ue_ue.md).EdGraphPinType

## Table of contents

### Constructors

- [constructor](ue_ue.EdGraphPinType.md#constructor)

### Properties

- [ContainerType](ue_ue.EdGraphPinType.md#containertype)
- [PinCategory](ue_ue.EdGraphPinType.md#pincategory)
- [PinSubCategory](ue_ue.EdGraphPinType.md#pinsubcategory)
- [PinSubCategoryMemberReference](ue_ue.EdGraphPinType.md#pinsubcategorymemberreference)
- [PinSubCategoryObject](ue_ue.EdGraphPinType.md#pinsubcategoryobject)
- [PinValueType](ue_ue.EdGraphPinType.md#pinvaluetype)
- [\_\_tid\_EdGraphPinType\_\_](ue_ue.EdGraphPinType.md#__tid_edgraphpintype__)
- [bIsArray](ue_ue.EdGraphPinType.md#bisarray)
- [bIsConst](ue_ue.EdGraphPinType.md#bisconst)
- [bIsReference](ue_ue.EdGraphPinType.md#bisreference)
- [bIsWeakPointer](ue_ue.EdGraphPinType.md#bisweakpointer)

### Methods

- [StaticClass](ue_ue.EdGraphPinType.md#staticclass)
- [StaticStruct](ue_ue.EdGraphPinType.md#staticstruct)

## Constructors

### constructor

• **new EdGraphPinType**()

• **new EdGraphPinType**(`PinCategory`, `PinSubCategory`, `PinSubCategoryObject`, `PinSubCategoryMemberReference`, `PinValueType`, `ContainerType`, `bIsArray`, `bIsReference`, `bIsConst`, `bIsWeakPointer`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PinCategory` | `string` |
| `PinSubCategory` | `string` |
| `PinSubCategoryObject` | [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\> |
| `PinSubCategoryMemberReference` | [`SimpleMemberReference`](ue_ue.SimpleMemberReference.md) |
| `PinValueType` | [`EdGraphTerminalType`](ue_ue.EdGraphTerminalType.md) |
| `ContainerType` | [`EPinContainerType`](../enums/ue_ue.EPinContainerType.md) |
| `bIsArray` | `boolean` |
| `bIsReference` | `boolean` |
| `bIsConst` | `boolean` |
| `bIsWeakPointer` | `boolean` |

## Properties

### ContainerType

• **ContainerType**: [`EPinContainerType`](../enums/ue_ue.EPinContainerType.md)

___

### PinCategory

• **PinCategory**: `string`

___

### PinSubCategory

• **PinSubCategory**: `string`

___

### PinSubCategoryMemberReference

• **PinSubCategoryMemberReference**: [`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)

___

### PinSubCategoryObject

• **PinSubCategoryObject**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\>

___

### PinValueType

• **PinValueType**: [`EdGraphTerminalType`](ue_ue.EdGraphTerminalType.md)

___

### \_\_tid\_EdGraphPinType\_\_

• `Private` **\_\_tid\_EdGraphPinType\_\_**: `boolean`

___

### bIsArray

• **bIsArray**: `boolean`

___

### bIsConst

• **bIsConst**: `boolean`

___

### bIsReference

• **bIsReference**: `boolean`

___

### bIsWeakPointer

• **bIsWeakPointer**: `boolean`

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
