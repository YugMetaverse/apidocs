[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Struct

# Class: Struct

[ue/ue](../modules/ue_ue.md).Struct

## Hierarchy

- [`Field`](ue_ue.Field.md)

  ↳ **`Struct`**

  ↳↳ [`Class`](ue_ue.Class.md)

  ↳↳ [`Function`](ue_ue.Function.md)

  ↳↳ [`ScriptStruct`](ue_ue.ScriptStruct.md)

## Table of contents

### Constructors

- [constructor](ue_ue.Struct.md#constructor)

### Properties

- [\_\_tid\_Field\_\_](ue_ue.Struct.md#__tid_field__)
- [\_\_tid\_Object\_\_](ue_ue.Struct.md#__tid_object__)
- [\_\_tid\_Struct\_\_](ue_ue.Struct.md#__tid_struct__)

### Methods

- [CreateDefaultSubobject](ue_ue.Struct.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Struct.md#executeubergraph)
- [GetClass](ue_ue.Struct.md#getclass)
- [GetName](ue_ue.Struct.md#getname)
- [GetOuter](ue_ue.Struct.md#getouter)
- [GetWorld](ue_ue.Struct.md#getworld)
- [IsChildOf](ue_ue.Struct.md#ischildof)
- [Find](ue_ue.Struct.md#find)
- [Load](ue_ue.Struct.md#load)
- [StaticClass](ue_ue.Struct.md#staticclass)

## Constructors

### constructor

• **new Struct**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Field](ue_ue.Field.md).[constructor](ue_ue.Field.md#constructor)

## Properties

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[Field](ue_ue.Field.md).[__tid_Field__](ue_ue.Field.md#__tid_field__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Field](ue_ue.Field.md).[__tid_Object__](ue_ue.Field.md#__tid_object__)

___

### \_\_tid\_Struct\_\_

• **\_\_tid\_Struct\_\_**: `boolean`

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

[Field](ue_ue.Field.md).[CreateDefaultSubobject](ue_ue.Field.md#createdefaultsubobject)

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

[Field](ue_ue.Field.md).[ExecuteUbergraph](ue_ue.Field.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Field](ue_ue.Field.md).[GetClass](ue_ue.Field.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Field](ue_ue.Field.md).[GetName](ue_ue.Field.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Field](ue_ue.Field.md).[GetOuter](ue_ue.Field.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Field](ue_ue.Field.md).[GetWorld](ue_ue.Field.md#getworld)

___

### IsChildOf

▸ **IsChildOf**(`p0`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`Struct`](ue_ue.Struct.md) |

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Struct`](ue_ue.Struct.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Struct`](ue_ue.Struct.md)

#### Overrides

[Field](ue_ue.Field.md).[Find](ue_ue.Field.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`Struct`](ue_ue.Struct.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Struct`](ue_ue.Struct.md)

#### Overrides

[Field](ue_ue.Field.md).[Load](ue_ue.Field.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Field](ue_ue.Field.md).[StaticClass](ue_ue.Field.md#staticclass)
