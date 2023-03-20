[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoftObjectProperty

# Class: SoftObjectProperty

[ue/ue](../modules/ue_ue.md).SoftObjectProperty

## Hierarchy

- [`ObjectPropertyBase`](ue_ue.ObjectPropertyBase.md)

  ↳ **`SoftObjectProperty`**

  ↳↳ [`SoftClassProperty`](ue_ue.SoftClassProperty.md)

## Table of contents

### Constructors

- [constructor](ue_ue.SoftObjectProperty.md#constructor)

### Properties

- [\_\_tid\_Field\_\_](ue_ue.SoftObjectProperty.md#__tid_field__)
- [\_\_tid\_ObjectPropertyBase\_\_](ue_ue.SoftObjectProperty.md#__tid_objectpropertybase__)
- [\_\_tid\_Object\_\_](ue_ue.SoftObjectProperty.md#__tid_object__)
- [\_\_tid\_Property\_\_](ue_ue.SoftObjectProperty.md#__tid_property__)
- [\_\_tid\_SoftObjectProperty\_\_](ue_ue.SoftObjectProperty.md#__tid_softobjectproperty__)

### Methods

- [CreateDefaultSubobject](ue_ue.SoftObjectProperty.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoftObjectProperty.md#executeubergraph)
- [GetClass](ue_ue.SoftObjectProperty.md#getclass)
- [GetName](ue_ue.SoftObjectProperty.md#getname)
- [GetOuter](ue_ue.SoftObjectProperty.md#getouter)
- [GetWorld](ue_ue.SoftObjectProperty.md#getworld)
- [Find](ue_ue.SoftObjectProperty.md#find)
- [Load](ue_ue.SoftObjectProperty.md#load)
- [StaticClass](ue_ue.SoftObjectProperty.md#staticclass)

## Constructors

### constructor

• **new SoftObjectProperty**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[constructor](ue_ue.ObjectPropertyBase.md#constructor)

#### Defined in

[ue/ue.d.ts:61075](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61075)

## Properties

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[__tid_Field__](ue_ue.ObjectPropertyBase.md#__tid_field__)

#### Defined in

[ue/ue.d.ts:700](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L700)

___

### \_\_tid\_ObjectPropertyBase\_\_

• **\_\_tid\_ObjectPropertyBase\_\_**: `boolean`

#### Inherited from

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[__tid_ObjectPropertyBase__](ue_ue.ObjectPropertyBase.md#__tid_objectpropertybase__)

#### Defined in

[ue/ue.d.ts:27417](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27417)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[__tid_Object__](ue_ue.ObjectPropertyBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_Property\_\_

• **\_\_tid\_Property\_\_**: `boolean`

#### Inherited from

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[__tid_Property__](ue_ue.ObjectPropertyBase.md#__tid_property__)

#### Defined in

[ue/ue.d.ts:4766](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4766)

___

### \_\_tid\_SoftObjectProperty\_\_

• **\_\_tid\_SoftObjectProperty\_\_**: `boolean`

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

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[CreateDefaultSubobject](ue_ue.ObjectPropertyBase.md#createdefaultsubobject)

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

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[ExecuteUbergraph](ue_ue.ObjectPropertyBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[GetClass](ue_ue.ObjectPropertyBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[GetName](ue_ue.ObjectPropertyBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[GetOuter](ue_ue.ObjectPropertyBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[GetWorld](ue_ue.ObjectPropertyBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoftObjectProperty`](ue_ue.SoftObjectProperty.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoftObjectProperty`](ue_ue.SoftObjectProperty.md)

#### Overrides

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[Find](ue_ue.ObjectPropertyBase.md#find)

#### Defined in

[ue/ue.d.ts:61077](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61077)

___

### Load

▸ `Static` **Load**(`InName`): [`SoftObjectProperty`](ue_ue.SoftObjectProperty.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoftObjectProperty`](ue_ue.SoftObjectProperty.md)

#### Overrides

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[Load](ue_ue.ObjectPropertyBase.md#load)

#### Defined in

[ue/ue.d.ts:61078](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61078)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ObjectPropertyBase](ue_ue.ObjectPropertyBase.md).[StaticClass](ue_ue.ObjectPropertyBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:61076](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61076)
