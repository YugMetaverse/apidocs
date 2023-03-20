[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UnitTestChannel

# Class: UnitTestChannel

[ue/ue](../modules/ue_ue.md).UnitTestChannel

## Hierarchy

- [`Channel`](ue_ue.Channel.md)

  ↳ **`UnitTestChannel`**

## Table of contents

### Constructors

- [constructor](ue_ue.UnitTestChannel.md#constructor)

### Properties

- [Connection](ue_ue.UnitTestChannel.md#connection)
- [\_\_tid\_Channel\_\_](ue_ue.UnitTestChannel.md#__tid_channel__)
- [\_\_tid\_Object\_\_](ue_ue.UnitTestChannel.md#__tid_object__)
- [\_\_tid\_UnitTestChannel\_\_](ue_ue.UnitTestChannel.md#__tid_unittestchannel__)

### Methods

- [CreateDefaultSubobject](ue_ue.UnitTestChannel.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UnitTestChannel.md#executeubergraph)
- [GetClass](ue_ue.UnitTestChannel.md#getclass)
- [GetName](ue_ue.UnitTestChannel.md#getname)
- [GetOuter](ue_ue.UnitTestChannel.md#getouter)
- [GetWorld](ue_ue.UnitTestChannel.md#getworld)
- [Find](ue_ue.UnitTestChannel.md#find)
- [Load](ue_ue.UnitTestChannel.md#load)
- [StaticClass](ue_ue.UnitTestChannel.md#staticclass)

## Constructors

### constructor

• **new UnitTestChannel**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Channel](ue_ue.Channel.md).[constructor](ue_ue.Channel.md#constructor)

#### Defined in

[ue/ue.d.ts:64604](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64604)

## Properties

### Connection

• **Connection**: [`NetConnection`](ue_ue.NetConnection.md)

#### Inherited from

[Channel](ue_ue.Channel.md).[Connection](ue_ue.Channel.md#connection)

#### Defined in

[ue/ue.d.ts:10368](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10368)

___

### \_\_tid\_Channel\_\_

• **\_\_tid\_Channel\_\_**: `boolean`

#### Inherited from

[Channel](ue_ue.Channel.md).[__tid_Channel__](ue_ue.Channel.md#__tid_channel__)

#### Defined in

[ue/ue.d.ts:10373](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10373)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Channel](ue_ue.Channel.md).[__tid_Object__](ue_ue.Channel.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_UnitTestChannel\_\_

• **\_\_tid\_UnitTestChannel\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:64609](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64609)

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

[Channel](ue_ue.Channel.md).[CreateDefaultSubobject](ue_ue.Channel.md#createdefaultsubobject)

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

[Channel](ue_ue.Channel.md).[ExecuteUbergraph](ue_ue.Channel.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Channel](ue_ue.Channel.md).[GetClass](ue_ue.Channel.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Channel](ue_ue.Channel.md).[GetName](ue_ue.Channel.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Channel](ue_ue.Channel.md).[GetOuter](ue_ue.Channel.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Channel](ue_ue.Channel.md).[GetWorld](ue_ue.Channel.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UnitTestChannel`](ue_ue.UnitTestChannel.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UnitTestChannel`](ue_ue.UnitTestChannel.md)

#### Overrides

[Channel](ue_ue.Channel.md).[Find](ue_ue.Channel.md#find)

#### Defined in

[ue/ue.d.ts:64606](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64606)

___

### Load

▸ `Static` **Load**(`InName`): [`UnitTestChannel`](ue_ue.UnitTestChannel.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UnitTestChannel`](ue_ue.UnitTestChannel.md)

#### Overrides

[Channel](ue_ue.Channel.md).[Load](ue_ue.Channel.md#load)

#### Defined in

[ue/ue.d.ts:64607](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64607)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Channel](ue_ue.Channel.md).[StaticClass](ue_ue.Channel.md#staticclass)

#### Defined in

[ue/ue.d.ts:64605](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64605)
