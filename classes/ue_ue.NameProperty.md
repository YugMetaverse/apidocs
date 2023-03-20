[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NameProperty

# Class: NameProperty

[ue/ue](../modules/ue_ue.md).NameProperty

## Hierarchy

- [`Property`](ue_ue.Property.md)

  ↳ **`NameProperty`**

## Table of contents

### Constructors

- [constructor](ue_ue.NameProperty.md#constructor)

### Properties

- [\_\_tid\_Field\_\_](ue_ue.NameProperty.md#__tid_field__)
- [\_\_tid\_NameProperty\_\_](ue_ue.NameProperty.md#__tid_nameproperty__)
- [\_\_tid\_Object\_\_](ue_ue.NameProperty.md#__tid_object__)
- [\_\_tid\_Property\_\_](ue_ue.NameProperty.md#__tid_property__)

### Methods

- [CreateDefaultSubobject](ue_ue.NameProperty.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.NameProperty.md#executeubergraph)
- [GetClass](ue_ue.NameProperty.md#getclass)
- [GetName](ue_ue.NameProperty.md#getname)
- [GetOuter](ue_ue.NameProperty.md#getouter)
- [GetWorld](ue_ue.NameProperty.md#getworld)
- [Find](ue_ue.NameProperty.md#find)
- [Load](ue_ue.NameProperty.md#load)
- [StaticClass](ue_ue.NameProperty.md#staticclass)

## Constructors

### constructor

• **new NameProperty**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Property](ue_ue.Property.md).[constructor](ue_ue.Property.md#constructor)

#### Defined in

[ue/ue.d.ts:52716](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L52716)

## Properties

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[Property](ue_ue.Property.md).[__tid_Field__](ue_ue.Property.md#__tid_field__)

#### Defined in

[ue/ue.d.ts:700](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L700)

___

### \_\_tid\_NameProperty\_\_

• **\_\_tid\_NameProperty\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:52721](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L52721)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Property](ue_ue.Property.md).[__tid_Object__](ue_ue.Property.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_Property\_\_

• **\_\_tid\_Property\_\_**: `boolean`

#### Inherited from

[Property](ue_ue.Property.md).[__tid_Property__](ue_ue.Property.md#__tid_property__)

#### Defined in

[ue/ue.d.ts:4766](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4766)

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

[Property](ue_ue.Property.md).[ExecuteUbergraph](ue_ue.Property.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Property](ue_ue.Property.md).[GetClass](ue_ue.Property.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Property](ue_ue.Property.md).[GetName](ue_ue.Property.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Property](ue_ue.Property.md).[GetOuter](ue_ue.Property.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Property](ue_ue.Property.md).[GetWorld](ue_ue.Property.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`NameProperty`](ue_ue.NameProperty.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`NameProperty`](ue_ue.NameProperty.md)

#### Overrides

[Property](ue_ue.Property.md).[Find](ue_ue.Property.md#find)

#### Defined in

[ue/ue.d.ts:52718](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L52718)

___

### Load

▸ `Static` **Load**(`InName`): [`NameProperty`](ue_ue.NameProperty.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`NameProperty`](ue_ue.NameProperty.md)

#### Overrides

[Property](ue_ue.Property.md).[Load](ue_ue.Property.md#load)

#### Defined in

[ue/ue.d.ts:52719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L52719)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Property](ue_ue.Property.md).[StaticClass](ue_ue.Property.md#staticclass)

#### Defined in

[ue/ue.d.ts:52717](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L52717)
