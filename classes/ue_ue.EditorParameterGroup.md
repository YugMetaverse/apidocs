[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorParameterGroup

# Class: EditorParameterGroup

[ue/ue](../modules/ue_ue.md).EditorParameterGroup

## Table of contents

### Constructors

- [constructor](ue_ue.EditorParameterGroup.md#constructor)

### Properties

- [GroupAssociation](ue_ue.EditorParameterGroup.md#groupassociation)
- [GroupName](ue_ue.EditorParameterGroup.md#groupname)
- [GroupSortPriority](ue_ue.EditorParameterGroup.md#groupsortpriority)
- [Parameters](ue_ue.EditorParameterGroup.md#parameters)
- [\_\_tid\_EditorParameterGroup\_\_](ue_ue.EditorParameterGroup.md#__tid_editorparametergroup__)

### Methods

- [StaticClass](ue_ue.EditorParameterGroup.md#staticclass)
- [StaticStruct](ue_ue.EditorParameterGroup.md#staticstruct)

## Constructors

### constructor

• **new EditorParameterGroup**()

• **new EditorParameterGroup**(`GroupName`, `GroupAssociation`, `Parameters`, `GroupSortPriority`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `GroupName` | `string` |
| `GroupAssociation` | [`EMaterialParameterAssociation`](../enums/ue_ue.EMaterialParameterAssociation.md) |
| `Parameters` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DEditorParameterValue`](ue_ue.DEditorParameterValue.md)\> |
| `GroupSortPriority` | `number` |

## Properties

### GroupAssociation

• **GroupAssociation**: [`EMaterialParameterAssociation`](../enums/ue_ue.EMaterialParameterAssociation.md)

___

### GroupName

• **GroupName**: `string`

___

### GroupSortPriority

• **GroupSortPriority**: `number`

___

### Parameters

• **Parameters**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DEditorParameterValue`](ue_ue.DEditorParameterValue.md)\>

___

### \_\_tid\_EditorParameterGroup\_\_

• `Private` **\_\_tid\_EditorParameterGroup\_\_**: `boolean`

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
