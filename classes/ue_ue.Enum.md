[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Enum

# Class: Enum

[ue/ue](../modules/ue_ue.md).Enum

## Hierarchy

- [`Field`](ue_ue.Field.md)

  ↳ **`Enum`**

  ↳↳ [`UserDefinedEnum`](ue_ue.UserDefinedEnum.md)

## Table of contents

### Constructors

- [constructor](ue_ue.Enum.md#constructor)

### Properties

- [\_\_tid\_Enum\_\_](ue_ue.Enum.md#__tid_enum__)
- [\_\_tid\_Field\_\_](ue_ue.Enum.md#__tid_field__)
- [\_\_tid\_Object\_\_](ue_ue.Enum.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.Enum.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Enum.md#executeubergraph)
- [GetClass](ue_ue.Enum.md#getclass)
- [GetName](ue_ue.Enum.md#getname)
- [GetOuter](ue_ue.Enum.md#getouter)
- [GetWorld](ue_ue.Enum.md#getworld)
- [Find](ue_ue.Enum.md#find)
- [Load](ue_ue.Enum.md#load)
- [StaticClass](ue_ue.Enum.md#staticclass)

## Constructors

### constructor

• **new Enum**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Field](ue_ue.Field.md).[constructor](ue_ue.Field.md#constructor)

#### Defined in

[ue/ue.d.ts:16980](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16980)

## Properties

### \_\_tid\_Enum\_\_

• **\_\_tid\_Enum\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:16985](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16985)

___

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[Field](ue_ue.Field.md).[__tid_Field__](ue_ue.Field.md#__tid_field__)

#### Defined in

[ue/ue.d.ts:700](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L700)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Field](ue_ue.Field.md).[__tid_Object__](ue_ue.Field.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Field](ue_ue.Field.md).[GetClass](ue_ue.Field.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Field](ue_ue.Field.md).[GetName](ue_ue.Field.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Field](ue_ue.Field.md).[GetOuter](ue_ue.Field.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Field](ue_ue.Field.md).[GetWorld](ue_ue.Field.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Enum`](ue_ue.Enum.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Enum`](ue_ue.Enum.md)

#### Overrides

[Field](ue_ue.Field.md).[Find](ue_ue.Field.md#find)

#### Defined in

[ue/ue.d.ts:16982](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16982)

___

### Load

▸ `Static` **Load**(`InName`): [`Enum`](ue_ue.Enum.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Enum`](ue_ue.Enum.md)

#### Overrides

[Field](ue_ue.Field.md).[Load](ue_ue.Field.md#load)

#### Defined in

[ue/ue.d.ts:16983](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16983)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Field](ue_ue.Field.md).[StaticClass](ue_ue.Field.md#staticclass)

#### Defined in

[ue/ue.d.ts:16981](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16981)
