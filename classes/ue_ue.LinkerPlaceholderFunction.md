[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LinkerPlaceholderFunction

# Class: LinkerPlaceholderFunction

[ue/ue](../modules/ue_ue.md).LinkerPlaceholderFunction

## Hierarchy

- [`Function`](ue_ue.Function.md)

  ↳ **`LinkerPlaceholderFunction`**

## Table of contents

### Constructors

- [constructor](ue_ue.LinkerPlaceholderFunction.md#constructor)

### Properties

- [\_\_tid\_Field\_\_](ue_ue.LinkerPlaceholderFunction.md#__tid_field__)
- [\_\_tid\_Function\_\_](ue_ue.LinkerPlaceholderFunction.md#__tid_function__)
- [\_\_tid\_LinkerPlaceholderFunction\_\_](ue_ue.LinkerPlaceholderFunction.md#__tid_linkerplaceholderfunction__)
- [\_\_tid\_Object\_\_](ue_ue.LinkerPlaceholderFunction.md#__tid_object__)
- [\_\_tid\_Struct\_\_](ue_ue.LinkerPlaceholderFunction.md#__tid_struct__)

### Methods

- [CreateDefaultSubobject](ue_ue.LinkerPlaceholderFunction.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LinkerPlaceholderFunction.md#executeubergraph)
- [GetClass](ue_ue.LinkerPlaceholderFunction.md#getclass)
- [GetName](ue_ue.LinkerPlaceholderFunction.md#getname)
- [GetOuter](ue_ue.LinkerPlaceholderFunction.md#getouter)
- [GetWorld](ue_ue.LinkerPlaceholderFunction.md#getworld)
- [IsChildOf](ue_ue.LinkerPlaceholderFunction.md#ischildof)
- [Find](ue_ue.LinkerPlaceholderFunction.md#find)
- [Load](ue_ue.LinkerPlaceholderFunction.md#load)
- [StaticClass](ue_ue.LinkerPlaceholderFunction.md#staticclass)

## Constructors

### constructor

• **new LinkerPlaceholderFunction**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Function](ue_ue.Function.md).[constructor](ue_ue.Function.md#constructor)

## Properties

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[Function](ue_ue.Function.md).[__tid_Field__](ue_ue.Function.md#__tid_field__)

___

### \_\_tid\_Function\_\_

• **\_\_tid\_Function\_\_**: `boolean`

#### Inherited from

[Function](ue_ue.Function.md).[__tid_Function__](ue_ue.Function.md#__tid_function__)

___

### \_\_tid\_LinkerPlaceholderFunction\_\_

• **\_\_tid\_LinkerPlaceholderFunction\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Function](ue_ue.Function.md).[__tid_Object__](ue_ue.Function.md#__tid_object__)

___

### \_\_tid\_Struct\_\_

• **\_\_tid\_Struct\_\_**: `boolean`

#### Inherited from

[Function](ue_ue.Function.md).[__tid_Struct__](ue_ue.Function.md#__tid_struct__)

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

[Function](ue_ue.Function.md).[CreateDefaultSubobject](ue_ue.Function.md#createdefaultsubobject)

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

[Function](ue_ue.Function.md).[ExecuteUbergraph](ue_ue.Function.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Function](ue_ue.Function.md).[GetClass](ue_ue.Function.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Function](ue_ue.Function.md).[GetName](ue_ue.Function.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Function](ue_ue.Function.md).[GetOuter](ue_ue.Function.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Function](ue_ue.Function.md).[GetWorld](ue_ue.Function.md#getworld)

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

[Function](ue_ue.Function.md).[IsChildOf](ue_ue.Function.md#ischildof)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LinkerPlaceholderFunction`](ue_ue.LinkerPlaceholderFunction.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LinkerPlaceholderFunction`](ue_ue.LinkerPlaceholderFunction.md)

#### Overrides

[Function](ue_ue.Function.md).[Find](ue_ue.Function.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LinkerPlaceholderFunction`](ue_ue.LinkerPlaceholderFunction.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LinkerPlaceholderFunction`](ue_ue.LinkerPlaceholderFunction.md)

#### Overrides

[Function](ue_ue.Function.md).[Load](ue_ue.Function.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Function](ue_ue.Function.md).[StaticClass](ue_ue.Function.md#staticclass)
