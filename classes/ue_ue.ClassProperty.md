[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ClassProperty

# Class: ClassProperty

[ue/ue](../modules/ue_ue.md).ClassProperty

## Hierarchy

- [`ObjectProperty`](ue_ue.ObjectProperty.md)

  ↳ **`ClassProperty`**

## Table of contents

### Constructors

- [constructor](ue_ue.ClassProperty.md#constructor)

### Properties

- [\_\_tid\_ClassProperty\_\_](ue_ue.ClassProperty.md#__tid_classproperty__)
- [\_\_tid\_Field\_\_](ue_ue.ClassProperty.md#__tid_field__)
- [\_\_tid\_ObjectPropertyBase\_\_](ue_ue.ClassProperty.md#__tid_objectpropertybase__)
- [\_\_tid\_ObjectProperty\_\_](ue_ue.ClassProperty.md#__tid_objectproperty__)
- [\_\_tid\_Object\_\_](ue_ue.ClassProperty.md#__tid_object__)
- [\_\_tid\_Property\_\_](ue_ue.ClassProperty.md#__tid_property__)

### Methods

- [CreateDefaultSubobject](ue_ue.ClassProperty.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ClassProperty.md#executeubergraph)
- [GetClass](ue_ue.ClassProperty.md#getclass)
- [GetName](ue_ue.ClassProperty.md#getname)
- [GetOuter](ue_ue.ClassProperty.md#getouter)
- [GetWorld](ue_ue.ClassProperty.md#getworld)
- [Find](ue_ue.ClassProperty.md#find)
- [Load](ue_ue.ClassProperty.md#load)
- [StaticClass](ue_ue.ClassProperty.md#staticclass)

## Constructors

### constructor

• **new ClassProperty**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ObjectProperty](ue_ue.ObjectProperty.md).[constructor](ue_ue.ObjectProperty.md#constructor)

## Properties

### \_\_tid\_ClassProperty\_\_

• **\_\_tid\_ClassProperty\_\_**: `boolean`

___

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[ObjectProperty](ue_ue.ObjectProperty.md).[__tid_Field__](ue_ue.ObjectProperty.md#__tid_field__)

___

### \_\_tid\_ObjectPropertyBase\_\_

• **\_\_tid\_ObjectPropertyBase\_\_**: `boolean`

#### Inherited from

[ObjectProperty](ue_ue.ObjectProperty.md).[__tid_ObjectPropertyBase__](ue_ue.ObjectProperty.md#__tid_objectpropertybase__)

___

### \_\_tid\_ObjectProperty\_\_

• **\_\_tid\_ObjectProperty\_\_**: `boolean`

#### Inherited from

[ObjectProperty](ue_ue.ObjectProperty.md).[__tid_ObjectProperty__](ue_ue.ObjectProperty.md#__tid_objectproperty__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ObjectProperty](ue_ue.ObjectProperty.md).[__tid_Object__](ue_ue.ObjectProperty.md#__tid_object__)

___

### \_\_tid\_Property\_\_

• **\_\_tid\_Property\_\_**: `boolean`

#### Inherited from

[ObjectProperty](ue_ue.ObjectProperty.md).[__tid_Property__](ue_ue.ObjectProperty.md#__tid_property__)

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

[ObjectProperty](ue_ue.ObjectProperty.md).[CreateDefaultSubobject](ue_ue.ObjectProperty.md#createdefaultsubobject)

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

[ObjectProperty](ue_ue.ObjectProperty.md).[ExecuteUbergraph](ue_ue.ObjectProperty.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ObjectProperty](ue_ue.ObjectProperty.md).[GetClass](ue_ue.ObjectProperty.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ObjectProperty](ue_ue.ObjectProperty.md).[GetName](ue_ue.ObjectProperty.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ObjectProperty](ue_ue.ObjectProperty.md).[GetOuter](ue_ue.ObjectProperty.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ObjectProperty](ue_ue.ObjectProperty.md).[GetWorld](ue_ue.ObjectProperty.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ClassProperty`](ue_ue.ClassProperty.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ClassProperty`](ue_ue.ClassProperty.md)

#### Overrides

[ObjectProperty](ue_ue.ObjectProperty.md).[Find](ue_ue.ObjectProperty.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ClassProperty`](ue_ue.ClassProperty.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ClassProperty`](ue_ue.ClassProperty.md)

#### Overrides

[ObjectProperty](ue_ue.ObjectProperty.md).[Load](ue_ue.ObjectProperty.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ObjectProperty](ue_ue.ObjectProperty.md).[StaticClass](ue_ue.ObjectProperty.md#staticclass)
