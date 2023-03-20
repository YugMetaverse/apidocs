[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / WeakObjectProperty

# Class: WeakObjectProperty

[ue/ue](../modules/ue_ue.md).WeakObjectProperty

## Hierarchy

- [`ObjectPropertyBase`](ue_ue.ObjectPropertyBase.md)

  ↳ **`WeakObjectProperty`**

## Table of contents

### Constructors

- [constructor](ue_ue.WeakObjectProperty.md#constructor)

### Properties

- [\_\_tid\_Field\_\_](ue_ue.WeakObjectProperty.md#__tid_field__)
- [\_\_tid\_ObjectPropertyBase\_\_](ue_ue.WeakObjectProperty.md#__tid_objectpropertybase__)
- [\_\_tid\_Object\_\_](ue_ue.WeakObjectProperty.md#__tid_object__)
- [\_\_tid\_Property\_\_](ue_ue.WeakObjectProperty.md#__tid_property__)
- [\_\_tid\_WeakObjectProperty\_\_](ue_ue.WeakObjectProperty.md#__tid_weakobjectproperty__)

### Methods

- [CreateDefaultSubobject](ue_ue.WeakObjectProperty.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.WeakObjectProperty.md#executeubergraph)
- [GetClass](ue_ue.WeakObjectProperty.md#getclass)
- [GetName](ue_ue.WeakObjectProperty.md#getname)
- [GetOuter](ue_ue.WeakObjectProperty.md#getouter)
- [GetWorld](ue_ue.WeakObjectProperty.md#getworld)
- [Find](ue_ue.WeakObjectProperty.md#find)
- [Load](ue_ue.WeakObjectProperty.md#load)
- [StaticClass](ue_ue.WeakObjectProperty.md#staticclass)

## Constructors

### constructor

• **new WeakObjectProperty**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[constructor](ue_ue.ObjectPropertyBase.md#constructor)

## Properties

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[__tid_Field__](ue_ue.ObjectPropertyBase.md#__tid_field__)

___

### \_\_tid\_ObjectPropertyBase\_\_

• **\_\_tid\_ObjectPropertyBase\_\_**: `boolean`

#### Inherited from

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[__tid_ObjectPropertyBase__](ue_ue.ObjectPropertyBase.md#__tid_objectpropertybase__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[__tid_Object__](ue_ue.ObjectPropertyBase.md#__tid_object__)

___

### \_\_tid\_Property\_\_

• **\_\_tid\_Property\_\_**: `boolean`

#### Inherited from

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[__tid_Property__](ue_ue.ObjectPropertyBase.md#__tid_property__)

___

### \_\_tid\_WeakObjectProperty\_\_

• **\_\_tid\_WeakObjectProperty\_\_**: `boolean`

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

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[CreateDefaultSubobject](ue_ue.ObjectPropertyBase.md#createdefaultsubobject)

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

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[ExecuteUbergraph](ue_ue.ObjectPropertyBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[GetClass](ue_ue.ObjectPropertyBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[GetName](ue_ue.ObjectPropertyBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[GetOuter](ue_ue.ObjectPropertyBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[GetWorld](ue_ue.ObjectPropertyBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`WeakObjectProperty`](ue_ue.WeakObjectProperty.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`WeakObjectProperty`](ue_ue.WeakObjectProperty.md)

#### Overrides

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[Find](ue_ue.ObjectPropertyBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`WeakObjectProperty`](ue_ue.WeakObjectProperty.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`WeakObjectProperty`](ue_ue.WeakObjectProperty.md)

#### Overrides

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[Load](ue_ue.ObjectPropertyBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[StaticClass](ue_ue.ObjectPropertyBase.md#staticclass)
