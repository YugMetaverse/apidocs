[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoftClassProperty

# Class: SoftClassProperty

[ue/ue](../modules/ue_ue.md).SoftClassProperty

## Hierarchy

- [`SoftObjectProperty`](ue_ue.SoftObjectProperty.md)

  ↳ **`SoftClassProperty`**

## Table of contents

### Constructors

- [constructor](ue_ue.SoftClassProperty.md#constructor)

### Properties

- [\_\_tid\_Field\_\_](ue_ue.SoftClassProperty.md#__tid_field__)
- [\_\_tid\_ObjectPropertyBase\_\_](ue_ue.SoftClassProperty.md#__tid_objectpropertybase__)
- [\_\_tid\_Object\_\_](ue_ue.SoftClassProperty.md#__tid_object__)
- [\_\_tid\_Property\_\_](ue_ue.SoftClassProperty.md#__tid_property__)
- [\_\_tid\_SoftClassProperty\_\_](ue_ue.SoftClassProperty.md#__tid_softclassproperty__)
- [\_\_tid\_SoftObjectProperty\_\_](ue_ue.SoftClassProperty.md#__tid_softobjectproperty__)

### Methods

- [CreateDefaultSubobject](ue_ue.SoftClassProperty.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoftClassProperty.md#executeubergraph)
- [GetClass](ue_ue.SoftClassProperty.md#getclass)
- [GetName](ue_ue.SoftClassProperty.md#getname)
- [GetOuter](ue_ue.SoftClassProperty.md#getouter)
- [GetWorld](ue_ue.SoftClassProperty.md#getworld)
- [Find](ue_ue.SoftClassProperty.md#find)
- [Load](ue_ue.SoftClassProperty.md#load)
- [StaticClass](ue_ue.SoftClassProperty.md#staticclass)

## Constructors

### constructor

• **new SoftClassProperty**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[constructor](ue_ue.SoftObjectProperty.md#constructor)

## Properties

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[__tid_Field__](ue_ue.SoftObjectProperty.md#__tid_field__)

___

### \_\_tid\_ObjectPropertyBase\_\_

• **\_\_tid\_ObjectPropertyBase\_\_**: `boolean`

#### Inherited from

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[__tid_ObjectPropertyBase__](ue_ue.SoftObjectProperty.md#__tid_objectpropertybase__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[__tid_Object__](ue_ue.SoftObjectProperty.md#__tid_object__)

___

### \_\_tid\_Property\_\_

• **\_\_tid\_Property\_\_**: `boolean`

#### Inherited from

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[__tid_Property__](ue_ue.SoftObjectProperty.md#__tid_property__)

___

### \_\_tid\_SoftClassProperty\_\_

• **\_\_tid\_SoftClassProperty\_\_**: `boolean`

___

### \_\_tid\_SoftObjectProperty\_\_

• **\_\_tid\_SoftObjectProperty\_\_**: `boolean`

#### Inherited from

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[__tid_SoftObjectProperty__](ue_ue.SoftObjectProperty.md#__tid_softobjectproperty__)

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

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[CreateDefaultSubobject](ue_ue.SoftObjectProperty.md#createdefaultsubobject)

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

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[ExecuteUbergraph](ue_ue.SoftObjectProperty.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[GetClass](ue_ue.SoftObjectProperty.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[GetName](ue_ue.SoftObjectProperty.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[GetOuter](ue_ue.SoftObjectProperty.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[GetWorld](ue_ue.SoftObjectProperty.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoftClassProperty`](ue_ue.SoftClassProperty.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoftClassProperty`](ue_ue.SoftClassProperty.md)

#### Overrides

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[Find](ue_ue.SoftObjectProperty.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SoftClassProperty`](ue_ue.SoftClassProperty.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoftClassProperty`](ue_ue.SoftClassProperty.md)

#### Overrides

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[Load](ue_ue.SoftObjectProperty.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[StaticClass](ue_ue.SoftObjectProperty.md#staticclass)
