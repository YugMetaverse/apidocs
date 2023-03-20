[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DynamicClass

# Class: DynamicClass

[ue/ue](../modules/ue_ue.md).DynamicClass

## Hierarchy

- [`Class`](ue_ue.Class.md)

  ↳ **`DynamicClass`**

## Table of contents

### Constructors

- [constructor](ue_ue.DynamicClass.md#constructor)

### Properties

- [\_\_tid\_Class\_\_](ue_ue.DynamicClass.md#__tid_class__)
- [\_\_tid\_DynamicClass\_\_](ue_ue.DynamicClass.md#__tid_dynamicclass__)
- [\_\_tid\_Field\_\_](ue_ue.DynamicClass.md#__tid_field__)
- [\_\_tid\_Object\_\_](ue_ue.DynamicClass.md#__tid_object__)
- [\_\_tid\_Struct\_\_](ue_ue.DynamicClass.md#__tid_struct__)

### Methods

- [CreateDefaultSubobject](ue_ue.DynamicClass.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DynamicClass.md#executeubergraph)
- [GetClass](ue_ue.DynamicClass.md#getclass)
- [GetName](ue_ue.DynamicClass.md#getname)
- [GetOuter](ue_ue.DynamicClass.md#getouter)
- [GetWorld](ue_ue.DynamicClass.md#getworld)
- [IsChildOf](ue_ue.DynamicClass.md#ischildof)
- [Find](ue_ue.DynamicClass.md#find)
- [Load](ue_ue.DynamicClass.md#load)
- [StaticClass](ue_ue.DynamicClass.md#staticclass)

## Constructors

### constructor

• **new DynamicClass**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Class](ue_ue.Class.md).[constructor](ue_ue.Class.md#constructor)

#### Defined in

[ue/ue.d.ts:31279](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31279)

## Properties

### \_\_tid\_Class\_\_

• **\_\_tid\_Class\_\_**: `boolean`

#### Inherited from

[Class](ue_ue.Class.md).[__tid_Class__](ue_ue.Class.md#__tid_class__)

#### Defined in

[ue/ue.d.ts:719](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L719)

___

### \_\_tid\_DynamicClass\_\_

• **\_\_tid\_DynamicClass\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:31284](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31284)

___

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[Class](ue_ue.Class.md).[__tid_Field__](ue_ue.Class.md#__tid_field__)

#### Defined in

[ue/ue.d.ts:700](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L700)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Class](ue_ue.Class.md).[__tid_Object__](ue_ue.Class.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_Struct\_\_

• **\_\_tid\_Struct\_\_**: `boolean`

#### Inherited from

[Class](ue_ue.Class.md).[__tid_Struct__](ue_ue.Class.md#__tid_struct__)

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

[Class](ue_ue.Class.md).[CreateDefaultSubobject](ue_ue.Class.md#createdefaultsubobject)

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

[Class](ue_ue.Class.md).[ExecuteUbergraph](ue_ue.Class.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Class](ue_ue.Class.md).[GetClass](ue_ue.Class.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Class](ue_ue.Class.md).[GetName](ue_ue.Class.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Class](ue_ue.Class.md).[GetOuter](ue_ue.Class.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Class](ue_ue.Class.md).[GetWorld](ue_ue.Class.md#getworld)

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

#### Inherited from

[Class](ue_ue.Class.md).[IsChildOf](ue_ue.Class.md#ischildof)

#### Defined in

[ue/ue.d.ts:705](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L705)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DynamicClass`](ue_ue.DynamicClass.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DynamicClass`](ue_ue.DynamicClass.md)

#### Overrides

[Class](ue_ue.Class.md).[Find](ue_ue.Class.md#find)

#### Defined in

[ue/ue.d.ts:31281](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31281)

___

### Load

▸ `Static` **Load**(`InName`): [`DynamicClass`](ue_ue.DynamicClass.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DynamicClass`](ue_ue.DynamicClass.md)

#### Overrides

[Class](ue_ue.Class.md).[Load](ue_ue.Class.md#load)

#### Defined in

[ue/ue.d.ts:31282](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31282)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Class](ue_ue.Class.md).[StaticClass](ue_ue.Class.md#staticclass)

#### Defined in

[ue/ue.d.ts:31280](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31280)
