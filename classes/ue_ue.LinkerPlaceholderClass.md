[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LinkerPlaceholderClass

# Class: LinkerPlaceholderClass

[ue/ue](../modules/ue_ue.md).LinkerPlaceholderClass

## Hierarchy

- [`Class`](ue_ue.Class.md)

  ↳ **`LinkerPlaceholderClass`**

## Table of contents

### Constructors

- [constructor](ue_ue.LinkerPlaceholderClass.md#constructor)

### Properties

- [\_\_tid\_Class\_\_](ue_ue.LinkerPlaceholderClass.md#__tid_class__)
- [\_\_tid\_Field\_\_](ue_ue.LinkerPlaceholderClass.md#__tid_field__)
- [\_\_tid\_LinkerPlaceholderClass\_\_](ue_ue.LinkerPlaceholderClass.md#__tid_linkerplaceholderclass__)
- [\_\_tid\_Object\_\_](ue_ue.LinkerPlaceholderClass.md#__tid_object__)
- [\_\_tid\_Struct\_\_](ue_ue.LinkerPlaceholderClass.md#__tid_struct__)

### Methods

- [CreateDefaultSubobject](ue_ue.LinkerPlaceholderClass.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LinkerPlaceholderClass.md#executeubergraph)
- [GetClass](ue_ue.LinkerPlaceholderClass.md#getclass)
- [GetName](ue_ue.LinkerPlaceholderClass.md#getname)
- [GetOuter](ue_ue.LinkerPlaceholderClass.md#getouter)
- [GetWorld](ue_ue.LinkerPlaceholderClass.md#getworld)
- [IsChildOf](ue_ue.LinkerPlaceholderClass.md#ischildof)
- [Find](ue_ue.LinkerPlaceholderClass.md#find)
- [Load](ue_ue.LinkerPlaceholderClass.md#load)
- [StaticClass](ue_ue.LinkerPlaceholderClass.md#staticclass)

## Constructors

### constructor

• **new LinkerPlaceholderClass**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Class](ue_ue.Class.md).[constructor](ue_ue.Class.md#constructor)

## Properties

### \_\_tid\_Class\_\_

• **\_\_tid\_Class\_\_**: `boolean`

#### Inherited from

[Class](ue_ue.Class.md).[__tid_Class__](ue_ue.Class.md#__tid_class__)

___

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[Class](ue_ue.Class.md).[__tid_Field__](ue_ue.Class.md#__tid_field__)

___

### \_\_tid\_LinkerPlaceholderClass\_\_

• **\_\_tid\_LinkerPlaceholderClass\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Class](ue_ue.Class.md).[__tid_Object__](ue_ue.Class.md#__tid_object__)

___

### \_\_tid\_Struct\_\_

• **\_\_tid\_Struct\_\_**: `boolean`

#### Inherited from

[Class](ue_ue.Class.md).[__tid_Struct__](ue_ue.Class.md#__tid_struct__)

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

[Class](ue_ue.Class.md).[CreateDefaultSubobject](ue_ue.Class.md#createdefaultsubobject)

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

[Class](ue_ue.Class.md).[ExecuteUbergraph](ue_ue.Class.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Class](ue_ue.Class.md).[GetClass](ue_ue.Class.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Class](ue_ue.Class.md).[GetName](ue_ue.Class.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Class](ue_ue.Class.md).[GetOuter](ue_ue.Class.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Class](ue_ue.Class.md).[GetWorld](ue_ue.Class.md#getworld)

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

[Class](ue_ue.Class.md).[IsChildOf](ue_ue.Class.md#ischildof)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LinkerPlaceholderClass`](ue_ue.LinkerPlaceholderClass.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LinkerPlaceholderClass`](ue_ue.LinkerPlaceholderClass.md)

#### Overrides

[Class](ue_ue.Class.md).[Find](ue_ue.Class.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LinkerPlaceholderClass`](ue_ue.LinkerPlaceholderClass.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LinkerPlaceholderClass`](ue_ue.LinkerPlaceholderClass.md)

#### Overrides

[Class](ue_ue.Class.md).[Load](ue_ue.Class.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Class](ue_ue.Class.md).[StaticClass](ue_ue.Class.md#staticclass)
