[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MapProperty

# Class: MapProperty

[ue/ue](../modules/ue_ue.md).MapProperty

## Hierarchy

- [`Property`](ue_ue.Property.md)

  ↳ **`MapProperty`**

## Table of contents

### Constructors

- [constructor](ue_ue.MapProperty.md#constructor)

### Properties

- [\_\_tid\_Field\_\_](ue_ue.MapProperty.md#__tid_field__)
- [\_\_tid\_MapProperty\_\_](ue_ue.MapProperty.md#__tid_mapproperty__)
- [\_\_tid\_Object\_\_](ue_ue.MapProperty.md#__tid_object__)
- [\_\_tid\_Property\_\_](ue_ue.MapProperty.md#__tid_property__)

### Methods

- [CreateDefaultSubobject](ue_ue.MapProperty.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MapProperty.md#executeubergraph)
- [GetClass](ue_ue.MapProperty.md#getclass)
- [GetName](ue_ue.MapProperty.md#getname)
- [GetOuter](ue_ue.MapProperty.md#getouter)
- [GetWorld](ue_ue.MapProperty.md#getworld)
- [Find](ue_ue.MapProperty.md#find)
- [Load](ue_ue.MapProperty.md#load)
- [StaticClass](ue_ue.MapProperty.md#staticclass)

## Constructors

### constructor

• **new MapProperty**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Property](ue_ue.Property.md).[constructor](ue_ue.Property.md#constructor)

#### Defined in

[ue/ue.d.ts:47249](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47249)

## Properties

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[Property](ue_ue.Property.md).[__tid_Field__](ue_ue.Property.md#__tid_field__)

#### Defined in

[ue/ue.d.ts:700](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L700)

___

### \_\_tid\_MapProperty\_\_

• **\_\_tid\_MapProperty\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:47254](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47254)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Property](ue_ue.Property.md).[__tid_Object__](ue_ue.Property.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_Property\_\_

• **\_\_tid\_Property\_\_**: `boolean`

#### Inherited from

[Property](ue_ue.Property.md).[__tid_Property__](ue_ue.Property.md#__tid_property__)

#### Defined in

[ue/ue.d.ts:4766](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4766)

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

[Property](ue_ue.Property.md).[ExecuteUbergraph](ue_ue.Property.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Property](ue_ue.Property.md).[GetClass](ue_ue.Property.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Property](ue_ue.Property.md).[GetName](ue_ue.Property.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Property](ue_ue.Property.md).[GetOuter](ue_ue.Property.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Property](ue_ue.Property.md).[GetWorld](ue_ue.Property.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MapProperty`](ue_ue.MapProperty.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MapProperty`](ue_ue.MapProperty.md)

#### Overrides

[Property](ue_ue.Property.md).[Find](ue_ue.Property.md#find)

#### Defined in

[ue/ue.d.ts:47251](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47251)

___

### Load

▸ `Static` **Load**(`InName`): [`MapProperty`](ue_ue.MapProperty.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MapProperty`](ue_ue.MapProperty.md)

#### Overrides

[Property](ue_ue.Property.md).[Load](ue_ue.Property.md#load)

#### Defined in

[ue/ue.d.ts:47252](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47252)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Property](ue_ue.Property.md).[StaticClass](ue_ue.Property.md#staticclass)

#### Defined in

[ue/ue.d.ts:47250](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47250)
