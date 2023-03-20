[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorPropertyPathSegment

# Class: EditorPropertyPathSegment

[ue/ue](../modules/ue_ue.md).EditorPropertyPathSegment

## Table of contents

### Constructors

- [constructor](ue_ue.EditorPropertyPathSegment.md#constructor)

### Properties

- [IsProperty](ue_ue.EditorPropertyPathSegment.md#isproperty)
- [MemberGuid](ue_ue.EditorPropertyPathSegment.md#memberguid)
- [MemberName](ue_ue.EditorPropertyPathSegment.md#membername)
- [Struct](ue_ue.EditorPropertyPathSegment.md#struct)
- [\_\_tid\_EditorPropertyPathSegment\_\_](ue_ue.EditorPropertyPathSegment.md#__tid_editorpropertypathsegment__)

### Methods

- [StaticClass](ue_ue.EditorPropertyPathSegment.md#staticclass)
- [StaticStruct](ue_ue.EditorPropertyPathSegment.md#staticstruct)

## Constructors

### constructor

• **new EditorPropertyPathSegment**()

• **new EditorPropertyPathSegment**(`Struct`, `MemberName`, `MemberGuid`, `IsProperty`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Struct` | [`Struct`](ue_ue.Struct.md) |
| `MemberName` | `string` |
| `MemberGuid` | [`Guid`](ue_ue_s.Guid.md) |
| `IsProperty` | `boolean` |

## Properties

### IsProperty

• **IsProperty**: `boolean`

___

### MemberGuid

• **MemberGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### MemberName

• **MemberName**: `string`

___

### Struct

• **Struct**: [`Struct`](ue_ue.Struct.md)

___

### \_\_tid\_EditorPropertyPathSegment\_\_

• `Private` **\_\_tid\_EditorPropertyPathSegment\_\_**: `boolean`

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
