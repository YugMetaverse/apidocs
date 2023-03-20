[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UserDefinedStructEditorData

# Class: UserDefinedStructEditorData

[ue/ue](../modules/ue_ue.md).UserDefinedStructEditorData

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`UserDefinedStructEditorData`**

## Table of contents

### Constructors

- [constructor](ue_ue.UserDefinedStructEditorData.md#constructor)

### Properties

- [ToolTip](ue_ue.UserDefinedStructEditorData.md#tooltip)
- [UniqueNameId](ue_ue.UserDefinedStructEditorData.md#uniquenameid)
- [VariablesDescriptions](ue_ue.UserDefinedStructEditorData.md#variablesdescriptions)
- [\_\_tid\_Object\_\_](ue_ue.UserDefinedStructEditorData.md#__tid_object__)
- [\_\_tid\_UserDefinedStructEditorData\_\_](ue_ue.UserDefinedStructEditorData.md#__tid_userdefinedstructeditordata__)

### Methods

- [CreateDefaultSubobject](ue_ue.UserDefinedStructEditorData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UserDefinedStructEditorData.md#executeubergraph)
- [GetClass](ue_ue.UserDefinedStructEditorData.md#getclass)
- [GetName](ue_ue.UserDefinedStructEditorData.md#getname)
- [GetOuter](ue_ue.UserDefinedStructEditorData.md#getouter)
- [GetWorld](ue_ue.UserDefinedStructEditorData.md#getworld)
- [Find](ue_ue.UserDefinedStructEditorData.md#find)
- [Load](ue_ue.UserDefinedStructEditorData.md#load)
- [StaticClass](ue_ue.UserDefinedStructEditorData.md#staticclass)

## Constructors

### constructor

• **new UserDefinedStructEditorData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ToolTip

• **ToolTip**: `string`

___

### UniqueNameId

• **UniqueNameId**: `number`

___

### VariablesDescriptions

• **VariablesDescriptions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StructVariableDescription`](ue_ue.StructVariableDescription.md)\>

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_UserDefinedStructEditorData\_\_

• **\_\_tid\_UserDefinedStructEditorData\_\_**: `boolean`

## Methods

### CreateDefaultSubobject

▸ **CreateDefaultSubobject**(`p0`, `p1`, `p2`, `p3`, `p4`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `string` |
| `p1` | [`Class`](ue_ue.Class.md) |
| `p2` | [`Class`](ue_ue.Class.md) |
| `p3` | `boolean` |
| `p4` | `boolean` |

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

___

### ExecuteUbergraph

▸ **ExecuteUbergraph**(`EntryPoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EntryPoint` | `number` |

#### Returns

`void`

#### Inherited from

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UserDefinedStructEditorData`](ue_ue.UserDefinedStructEditorData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UserDefinedStructEditorData`](ue_ue.UserDefinedStructEditorData.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`UserDefinedStructEditorData`](ue_ue.UserDefinedStructEditorData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UserDefinedStructEditorData`](ue_ue.UserDefinedStructEditorData.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
