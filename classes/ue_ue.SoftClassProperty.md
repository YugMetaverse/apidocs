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

#### Defined in

[ue/ue.d.ts:61084](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61084)

## Properties

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[__tid_Field__](ue_ue.SoftObjectProperty.md#__tid_field__)

#### Defined in

[ue/ue.d.ts:700](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L700)

___

### \_\_tid\_ObjectPropertyBase\_\_

• **\_\_tid\_ObjectPropertyBase\_\_**: `boolean`

#### Inherited from

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[__tid_ObjectPropertyBase__](ue_ue.SoftObjectProperty.md#__tid_objectpropertybase__)

#### Defined in

[ue/ue.d.ts:27417](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27417)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[__tid_Object__](ue_ue.SoftObjectProperty.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_Property\_\_

• **\_\_tid\_Property\_\_**: `boolean`

#### Inherited from

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[__tid_Property__](ue_ue.SoftObjectProperty.md#__tid_property__)

#### Defined in

[ue/ue.d.ts:4766](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4766)

___

### \_\_tid\_SoftClassProperty\_\_

• **\_\_tid\_SoftClassProperty\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:61089](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61089)

___

### \_\_tid\_SoftObjectProperty\_\_

• **\_\_tid\_SoftObjectProperty\_\_**: `boolean`

#### Inherited from

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[__tid_SoftObjectProperty__](ue_ue.SoftObjectProperty.md#__tid_softobjectproperty__)

#### Defined in

[ue/ue.d.ts:61080](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61080)

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

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[ExecuteUbergraph](ue_ue.SoftObjectProperty.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[GetClass](ue_ue.SoftObjectProperty.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[GetName](ue_ue.SoftObjectProperty.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[GetOuter](ue_ue.SoftObjectProperty.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[GetWorld](ue_ue.SoftObjectProperty.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:61086](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61086)

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

#### Defined in

[ue/ue.d.ts:61087](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61087)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoftObjectProperty](ue_ue.SoftObjectProperty.md).[StaticClass](ue_ue.SoftObjectProperty.md#staticclass)

#### Defined in

[ue/ue.d.ts:61085](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61085)
