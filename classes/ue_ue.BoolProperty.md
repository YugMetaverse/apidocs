[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BoolProperty

# Class: BoolProperty

[ue/ue](../modules/ue_ue.md).BoolProperty

## Hierarchy

- [`Property`](ue_ue.Property.md)

  ↳ **`BoolProperty`**

## Table of contents

### Constructors

- [constructor](ue_ue.BoolProperty.md#constructor)

### Properties

- [\_\_tid\_BoolProperty\_\_](ue_ue.BoolProperty.md#__tid_boolproperty__)
- [\_\_tid\_Field\_\_](ue_ue.BoolProperty.md#__tid_field__)
- [\_\_tid\_Object\_\_](ue_ue.BoolProperty.md#__tid_object__)
- [\_\_tid\_Property\_\_](ue_ue.BoolProperty.md#__tid_property__)

### Methods

- [CreateDefaultSubobject](ue_ue.BoolProperty.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BoolProperty.md#executeubergraph)
- [GetClass](ue_ue.BoolProperty.md#getclass)
- [GetName](ue_ue.BoolProperty.md#getname)
- [GetOuter](ue_ue.BoolProperty.md#getouter)
- [GetWorld](ue_ue.BoolProperty.md#getworld)
- [Find](ue_ue.BoolProperty.md#find)
- [Load](ue_ue.BoolProperty.md#load)
- [StaticClass](ue_ue.BoolProperty.md#staticclass)

## Constructors

### constructor

• **new BoolProperty**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Property](ue_ue.Property.md).[constructor](ue_ue.Property.md#constructor)

## Properties

### \_\_tid\_BoolProperty\_\_

• **\_\_tid\_BoolProperty\_\_**: `boolean`

___

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[Property](ue_ue.Property.md).[__tid_Field__](ue_ue.Property.md#__tid_field__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Property](ue_ue.Property.md).[__tid_Object__](ue_ue.Property.md#__tid_object__)

___

### \_\_tid\_Property\_\_

• **\_\_tid\_Property\_\_**: `boolean`

#### Inherited from

[Property](ue_ue.Property.md).[__tid_Property__](ue_ue.Property.md#__tid_property__)

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

[Property](ue_ue.Property.md).[CreateDefaultSubobject](ue_ue.Property.md#createdefaultsubobject)

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

[Property](ue_ue.Property.md).[ExecuteUbergraph](ue_ue.Property.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Property](ue_ue.Property.md).[GetClass](ue_ue.Property.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Property](ue_ue.Property.md).[GetName](ue_ue.Property.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Property](ue_ue.Property.md).[GetOuter](ue_ue.Property.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Property](ue_ue.Property.md).[GetWorld](ue_ue.Property.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BoolProperty`](ue_ue.BoolProperty.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BoolProperty`](ue_ue.BoolProperty.md)

#### Overrides

[Property](ue_ue.Property.md).[Find](ue_ue.Property.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BoolProperty`](ue_ue.BoolProperty.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BoolProperty`](ue_ue.BoolProperty.md)

#### Overrides

[Property](ue_ue.Property.md).[Load](ue_ue.Property.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Property](ue_ue.Property.md).[StaticClass](ue_ue.Property.md#staticclass)
