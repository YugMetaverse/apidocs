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

#### Defined in

[ue/ue.d.ts:704](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L704)

## Properties

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[Field](ue_ue.Field.md).[__tid_Field__](ue_ue.Field.md#__tid_field__)

#### Defined in

[ue/ue.d.ts:700](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L700)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Field](ue_ue.Field.md).[__tid_Object__](ue_ue.Field.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_Struct\_\_

• **\_\_tid\_Struct\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:710](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L710)

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

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Field](ue_ue.Field.md).[GetClass](ue_ue.Field.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Field](ue_ue.Field.md).[GetName](ue_ue.Field.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Field](ue_ue.Field.md).[GetOuter](ue_ue.Field.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Field](ue_ue.Field.md).[GetWorld](ue_ue.Field.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### IsChildOf

▸ **IsChildOf**(`p0`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`Struct`](ue_ue.Struct.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:705](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L705)

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

#### Defined in

[ue/ue.d.ts:707](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L707)

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

#### Defined in

[ue/ue.d.ts:708](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L708)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Field](ue_ue.Field.md).[StaticClass](ue_ue.Field.md#staticclass)

#### Defined in

[ue/ue.d.ts:706](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L706)
