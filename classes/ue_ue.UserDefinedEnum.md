[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UserDefinedEnum

# Class: UserDefinedEnum

[ue/ue](../modules/ue_ue.md).UserDefinedEnum

## Hierarchy

- [`Enum`](ue_ue.Enum.md)

  ↳ **`UserDefinedEnum`**

## Table of contents

### Constructors

- [constructor](ue_ue.UserDefinedEnum.md#constructor)

### Properties

- [DisplayNameMap](ue_ue.UserDefinedEnum.md#displaynamemap)
- [EnumDescription](ue_ue.UserDefinedEnum.md#enumdescription)
- [UniqueNameIndex](ue_ue.UserDefinedEnum.md#uniquenameindex)
- [\_\_tid\_Enum\_\_](ue_ue.UserDefinedEnum.md#__tid_enum__)
- [\_\_tid\_Field\_\_](ue_ue.UserDefinedEnum.md#__tid_field__)
- [\_\_tid\_Object\_\_](ue_ue.UserDefinedEnum.md#__tid_object__)
- [\_\_tid\_UserDefinedEnum\_\_](ue_ue.UserDefinedEnum.md#__tid_userdefinedenum__)

### Methods

- [CreateDefaultSubobject](ue_ue.UserDefinedEnum.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UserDefinedEnum.md#executeubergraph)
- [GetClass](ue_ue.UserDefinedEnum.md#getclass)
- [GetName](ue_ue.UserDefinedEnum.md#getname)
- [GetOuter](ue_ue.UserDefinedEnum.md#getouter)
- [GetWorld](ue_ue.UserDefinedEnum.md#getworld)
- [Find](ue_ue.UserDefinedEnum.md#find)
- [Load](ue_ue.UserDefinedEnum.md#load)
- [StaticClass](ue_ue.UserDefinedEnum.md#staticclass)

## Constructors

### constructor

• **new UserDefinedEnum**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Enum](ue_ue.Enum.md).[constructor](ue_ue.Enum.md#constructor)

## Properties

### DisplayNameMap

• **DisplayNameMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\>

___

### EnumDescription

• **EnumDescription**: `string`

___

### UniqueNameIndex

• **UniqueNameIndex**: `number`

___

### \_\_tid\_Enum\_\_

• **\_\_tid\_Enum\_\_**: `boolean`

#### Inherited from

[Enum](ue_ue.Enum.md).[__tid_Enum__](ue_ue.Enum.md#__tid_enum__)

___

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[Enum](ue_ue.Enum.md).[__tid_Field__](ue_ue.Enum.md#__tid_field__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Enum](ue_ue.Enum.md).[__tid_Object__](ue_ue.Enum.md#__tid_object__)

___

### \_\_tid\_UserDefinedEnum\_\_

• **\_\_tid\_UserDefinedEnum\_\_**: `boolean`

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

[Enum](ue_ue.Enum.md).[CreateDefaultSubobject](ue_ue.Enum.md#createdefaultsubobject)

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

[Enum](ue_ue.Enum.md).[ExecuteUbergraph](ue_ue.Enum.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Enum](ue_ue.Enum.md).[GetClass](ue_ue.Enum.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Enum](ue_ue.Enum.md).[GetName](ue_ue.Enum.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Enum](ue_ue.Enum.md).[GetOuter](ue_ue.Enum.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Enum](ue_ue.Enum.md).[GetWorld](ue_ue.Enum.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UserDefinedEnum`](ue_ue.UserDefinedEnum.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UserDefinedEnum`](ue_ue.UserDefinedEnum.md)

#### Overrides

[Enum](ue_ue.Enum.md).[Find](ue_ue.Enum.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`UserDefinedEnum`](ue_ue.UserDefinedEnum.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UserDefinedEnum`](ue_ue.UserDefinedEnum.md)

#### Overrides

[Enum](ue_ue.Enum.md).[Load](ue_ue.Enum.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Enum](ue_ue.Enum.md).[StaticClass](ue_ue.Enum.md#staticclass)
