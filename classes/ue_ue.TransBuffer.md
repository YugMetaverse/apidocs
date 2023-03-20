[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TransBuffer

# Class: TransBuffer

[ue/ue](../modules/ue_ue.md).TransBuffer

## Hierarchy

- [`Transactor`](ue_ue.Transactor.md)

  ↳ **`TransBuffer`**

## Table of contents

### Constructors

- [constructor](ue_ue.TransBuffer.md#constructor)

### Properties

- [\_\_tid\_Object\_\_](ue_ue.TransBuffer.md#__tid_object__)
- [\_\_tid\_TransBuffer\_\_](ue_ue.TransBuffer.md#__tid_transbuffer__)
- [\_\_tid\_Transactor\_\_](ue_ue.TransBuffer.md#__tid_transactor__)

### Methods

- [CreateDefaultSubobject](ue_ue.TransBuffer.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TransBuffer.md#executeubergraph)
- [GetClass](ue_ue.TransBuffer.md#getclass)
- [GetName](ue_ue.TransBuffer.md#getname)
- [GetOuter](ue_ue.TransBuffer.md#getouter)
- [GetWorld](ue_ue.TransBuffer.md#getworld)
- [Find](ue_ue.TransBuffer.md#find)
- [Load](ue_ue.TransBuffer.md#load)
- [StaticClass](ue_ue.TransBuffer.md#staticclass)

## Constructors

### constructor

• **new TransBuffer**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Transactor](ue_ue.Transactor.md).[constructor](ue_ue.Transactor.md#constructor)

#### Defined in

[ue/ue.d.ts:64080](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64080)

## Properties

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Transactor](ue_ue.Transactor.md).[__tid_Object__](ue_ue.Transactor.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_TransBuffer\_\_

• **\_\_tid\_TransBuffer\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:64085](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64085)

___

### \_\_tid\_Transactor\_\_

• **\_\_tid\_Transactor\_\_**: `boolean`

#### Inherited from

[Transactor](ue_ue.Transactor.md).[__tid_Transactor__](ue_ue.Transactor.md#__tid_transactor__)

#### Defined in

[ue/ue.d.ts:32897](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32897)

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

[Transactor](ue_ue.Transactor.md).[CreateDefaultSubobject](ue_ue.Transactor.md#createdefaultsubobject)

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

[Transactor](ue_ue.Transactor.md).[ExecuteUbergraph](ue_ue.Transactor.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Transactor](ue_ue.Transactor.md).[GetClass](ue_ue.Transactor.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Transactor](ue_ue.Transactor.md).[GetName](ue_ue.Transactor.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Transactor](ue_ue.Transactor.md).[GetOuter](ue_ue.Transactor.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Transactor](ue_ue.Transactor.md).[GetWorld](ue_ue.Transactor.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TransBuffer`](ue_ue.TransBuffer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TransBuffer`](ue_ue.TransBuffer.md)

#### Overrides

[Transactor](ue_ue.Transactor.md).[Find](ue_ue.Transactor.md#find)

#### Defined in

[ue/ue.d.ts:64082](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64082)

___

### Load

▸ `Static` **Load**(`InName`): [`TransBuffer`](ue_ue.TransBuffer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TransBuffer`](ue_ue.TransBuffer.md)

#### Overrides

[Transactor](ue_ue.Transactor.md).[Load](ue_ue.Transactor.md#load)

#### Defined in

[ue/ue.d.ts:64083](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64083)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Transactor](ue_ue.Transactor.md).[StaticClass](ue_ue.Transactor.md#staticclass)

#### Defined in

[ue/ue.d.ts:64081](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64081)
