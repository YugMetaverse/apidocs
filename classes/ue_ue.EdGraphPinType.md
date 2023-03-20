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

#### Defined in

[ue/ue.d.ts:1008](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1008)

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

#### Defined in

[ue/ue.d.ts:1009](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1009)

## Properties

### ContainerType

• **ContainerType**: [`EPinContainerType`](../enums/ue_ue.EPinContainerType.md)

#### Defined in

[ue/ue.d.ts:1015](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1015)

___

### PinCategory

• **PinCategory**: `string`

#### Defined in

[ue/ue.d.ts:1010](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1010)

___

### PinSubCategory

• **PinSubCategory**: `string`

#### Defined in

[ue/ue.d.ts:1011](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1011)

___

### PinSubCategoryMemberReference

• **PinSubCategoryMemberReference**: [`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)

#### Defined in

[ue/ue.d.ts:1013](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1013)

___

### PinSubCategoryObject

• **PinSubCategoryObject**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:1012](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1012)

___

### PinValueType

• **PinValueType**: [`EdGraphTerminalType`](ue_ue.EdGraphTerminalType.md)

#### Defined in

[ue/ue.d.ts:1014](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1014)

___

### \_\_tid\_EdGraphPinType\_\_

• `Private` **\_\_tid\_EdGraphPinType\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:1025](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1025)

___

### bIsArray

• **bIsArray**: `boolean`

#### Defined in

[ue/ue.d.ts:1016](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1016)

___

### bIsConst

• **bIsConst**: `boolean`

#### Defined in

[ue/ue.d.ts:1018](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1018)

___

### bIsReference

• **bIsReference**: `boolean`

#### Defined in

[ue/ue.d.ts:1017](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1017)

___

### bIsWeakPointer

• **bIsWeakPointer**: `boolean`

#### Defined in

[ue/ue.d.ts:1019](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1019)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:1023](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1023)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:1024](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1024)
