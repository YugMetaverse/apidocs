[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Class

# Class: Class

[ue/ue](../modules/ue_ue.md).Class

## Hierarchy

- [`Struct`](ue_ue.Struct.md)

  ↳ **`Class`**

  ↳↳ [`BlueprintGeneratedClass`](ue_ue.BlueprintGeneratedClass.md)

  ↳↳ [`DynamicClass`](ue_ue.DynamicClass.md)

  ↳↳ [`LinkerPlaceholderClass`](ue_ue.LinkerPlaceholderClass.md)

## Table of contents

### Constructors

- [constructor](ue_ue.Class.md#constructor)

### Properties

- [\_\_tid\_Class\_\_](ue_ue.Class.md#__tid_class__)
- [\_\_tid\_Field\_\_](ue_ue.Class.md#__tid_field__)
- [\_\_tid\_Object\_\_](ue_ue.Class.md#__tid_object__)
- [\_\_tid\_Struct\_\_](ue_ue.Class.md#__tid_struct__)

### Methods

- [CreateDefaultSubobject](ue_ue.Class.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Class.md#executeubergraph)
- [GetClass](ue_ue.Class.md#getclass)
- [GetName](ue_ue.Class.md#getname)
- [GetOuter](ue_ue.Class.md#getouter)
- [GetWorld](ue_ue.Class.md#getworld)
- [IsChildOf](ue_ue.Class.md#ischildof)
- [Find](ue_ue.Class.md#find)
- [Load](ue_ue.Class.md#load)
- [StaticClass](ue_ue.Class.md#staticclass)

## Constructors

### constructor

• **new Class**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Struct](ue_ue.Struct.md).[constructor](ue_ue.Struct.md#constructor)

## Properties

### \_\_tid\_Class\_\_

• **\_\_tid\_Class\_\_**: `boolean`

___

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[Struct](ue_ue.Struct.md).[__tid_Field__](ue_ue.Struct.md#__tid_field__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Struct](ue_ue.Struct.md).[__tid_Object__](ue_ue.Struct.md#__tid_object__)

___

### \_\_tid\_Struct\_\_

• **\_\_tid\_Struct\_\_**: `boolean`

#### Inherited from

[Struct](ue_ue.Struct.md).[__tid_Struct__](ue_ue.Struct.md#__tid_struct__)

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

[Struct](ue_ue.Struct.md).[CreateDefaultSubobject](ue_ue.Struct.md#createdefaultsubobject)

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

[Struct](ue_ue.Struct.md).[ExecuteUbergraph](ue_ue.Struct.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Struct](ue_ue.Struct.md).[GetClass](ue_ue.Struct.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Struct](ue_ue.Struct.md).[GetName](ue_ue.Struct.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Struct](ue_ue.Struct.md).[GetOuter](ue_ue.Struct.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Struct](ue_ue.Struct.md).[GetWorld](ue_ue.Struct.md#getworld)

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

[Struct](ue_ue.Struct.md).[IsChildOf](ue_ue.Struct.md#ischildof)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Class`](ue_ue.Class.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Struct](ue_ue.Struct.md).[Find](ue_ue.Struct.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`Class`](ue_ue.Class.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Struct](ue_ue.Struct.md).[Load](ue_ue.Struct.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Struct](ue_ue.Struct.md).[StaticClass](ue_ue.Struct.md#staticclass)
