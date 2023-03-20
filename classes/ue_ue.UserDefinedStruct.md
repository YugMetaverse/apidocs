[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UserDefinedStruct

# Class: UserDefinedStruct

[ue/ue](../modules/ue_ue.md).UserDefinedStruct

## Hierarchy

- [`ScriptStruct`](ue_ue.ScriptStruct.md)

  ↳ **`UserDefinedStruct`**

  ↳↳ [`AISenseBlueprintListener`](ue_ue.AISenseBlueprintListener.md)

## Table of contents

### Constructors

- [constructor](ue_ue.UserDefinedStruct.md#constructor)

### Properties

- [EditorData](ue_ue.UserDefinedStruct.md#editordata)
- [ErrorMessage](ue_ue.UserDefinedStruct.md#errormessage)
- [Guid](ue_ue.UserDefinedStruct.md#guid)
- [PrimaryStruct](ue_ue.UserDefinedStruct.md#primarystruct)
- [Status](ue_ue.UserDefinedStruct.md#status)
- [\_\_tid\_Field\_\_](ue_ue.UserDefinedStruct.md#__tid_field__)
- [\_\_tid\_Object\_\_](ue_ue.UserDefinedStruct.md#__tid_object__)
- [\_\_tid\_ScriptStruct\_\_](ue_ue.UserDefinedStruct.md#__tid_scriptstruct__)
- [\_\_tid\_Struct\_\_](ue_ue.UserDefinedStruct.md#__tid_struct__)
- [\_\_tid\_UserDefinedStruct\_\_](ue_ue.UserDefinedStruct.md#__tid_userdefinedstruct__)

### Methods

- [CreateDefaultSubobject](ue_ue.UserDefinedStruct.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UserDefinedStruct.md#executeubergraph)
- [GetClass](ue_ue.UserDefinedStruct.md#getclass)
- [GetName](ue_ue.UserDefinedStruct.md#getname)
- [GetOuter](ue_ue.UserDefinedStruct.md#getouter)
- [GetWorld](ue_ue.UserDefinedStruct.md#getworld)
- [IsChildOf](ue_ue.UserDefinedStruct.md#ischildof)
- [Find](ue_ue.UserDefinedStruct.md#find)
- [Load](ue_ue.UserDefinedStruct.md#load)
- [StaticClass](ue_ue.UserDefinedStruct.md#staticclass)

## Constructors

### constructor

• **new UserDefinedStruct**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ScriptStruct](ue_ue.ScriptStruct.md).[constructor](ue_ue.ScriptStruct.md#constructor)

## Properties

### EditorData

• **EditorData**: [`Object`](ue_ue.Object.md)

___

### ErrorMessage

• **ErrorMessage**: `string`

___

### Guid

• **Guid**: [`Guid`](ue_ue_s.Guid.md)

___

### PrimaryStruct

• **PrimaryStruct**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`UserDefinedStruct`](ue_ue.UserDefinedStruct.md)\>

___

### Status

• **Status**: [`EUserDefinedStructureStatus`](../enums/ue_ue.EUserDefinedStructureStatus.md)

___

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[ScriptStruct](ue_ue.ScriptStruct.md).[__tid_Field__](ue_ue.ScriptStruct.md#__tid_field__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ScriptStruct](ue_ue.ScriptStruct.md).[__tid_Object__](ue_ue.ScriptStruct.md#__tid_object__)

___

### \_\_tid\_ScriptStruct\_\_

• **\_\_tid\_ScriptStruct\_\_**: `boolean`

#### Inherited from

[ScriptStruct](ue_ue.ScriptStruct.md).[__tid_ScriptStruct__](ue_ue.ScriptStruct.md#__tid_scriptstruct__)

___

### \_\_tid\_Struct\_\_

• **\_\_tid\_Struct\_\_**: `boolean`

#### Inherited from

[ScriptStruct](ue_ue.ScriptStruct.md).[__tid_Struct__](ue_ue.ScriptStruct.md#__tid_struct__)

___

### \_\_tid\_UserDefinedStruct\_\_

• **\_\_tid\_UserDefinedStruct\_\_**: `boolean`

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

[ScriptStruct](ue_ue.ScriptStruct.md).[CreateDefaultSubobject](ue_ue.ScriptStruct.md#createdefaultsubobject)

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

[ScriptStruct](ue_ue.ScriptStruct.md).[ExecuteUbergraph](ue_ue.ScriptStruct.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ScriptStruct](ue_ue.ScriptStruct.md).[GetClass](ue_ue.ScriptStruct.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ScriptStruct](ue_ue.ScriptStruct.md).[GetName](ue_ue.ScriptStruct.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ScriptStruct](ue_ue.ScriptStruct.md).[GetOuter](ue_ue.ScriptStruct.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ScriptStruct](ue_ue.ScriptStruct.md).[GetWorld](ue_ue.ScriptStruct.md#getworld)

___

### IsChildOf

▸ **IsChildOf**(`p0`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`Struct`](ue_ue.Struct.md) |

#### Returns

`boolean`

#### Inherited from

[ScriptStruct](ue_ue.ScriptStruct.md).[IsChildOf](ue_ue.ScriptStruct.md#ischildof)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UserDefinedStruct`](ue_ue.UserDefinedStruct.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UserDefinedStruct`](ue_ue.UserDefinedStruct.md)

#### Overrides

[ScriptStruct](ue_ue.ScriptStruct.md).[Find](ue_ue.ScriptStruct.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`UserDefinedStruct`](ue_ue.UserDefinedStruct.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UserDefinedStruct`](ue_ue.UserDefinedStruct.md)

#### Overrides

[ScriptStruct](ue_ue.ScriptStruct.md).[Load](ue_ue.ScriptStruct.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ScriptStruct](ue_ue.ScriptStruct.md).[StaticClass](ue_ue.ScriptStruct.md#staticclass)
