[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ControlChannel

# Class: ControlChannel

[ue/ue](../modules/ue_ue.md).ControlChannel

## Hierarchy

- [`Channel`](ue_ue.Channel.md)

  ↳ **`ControlChannel`**

## Table of contents

### Constructors

- [constructor](ue_ue.ControlChannel.md#constructor)

### Properties

- [Connection](ue_ue.ControlChannel.md#connection)
- [\_\_tid\_Channel\_\_](ue_ue.ControlChannel.md#__tid_channel__)
- [\_\_tid\_ControlChannel\_\_](ue_ue.ControlChannel.md#__tid_controlchannel__)
- [\_\_tid\_Object\_\_](ue_ue.ControlChannel.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ControlChannel.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ControlChannel.md#executeubergraph)
- [GetClass](ue_ue.ControlChannel.md#getclass)
- [GetName](ue_ue.ControlChannel.md#getname)
- [GetOuter](ue_ue.ControlChannel.md#getouter)
- [GetWorld](ue_ue.ControlChannel.md#getworld)
- [Find](ue_ue.ControlChannel.md#find)
- [Load](ue_ue.ControlChannel.md#load)
- [StaticClass](ue_ue.ControlChannel.md#staticclass)

## Constructors

### constructor

• **new ControlChannel**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Channel](ue_ue.Channel.md).[constructor](ue_ue.Channel.md#constructor)

#### Defined in

[ue/ue.d.ts:28712](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28712)

## Properties

### Connection

• **Connection**: [`NetConnection`](ue_ue.NetConnection.md)

#### Inherited from

[Channel](ue_ue.Channel.md).[Connection](ue_ue.Channel.md#connection)

#### Defined in

[ue/ue.d.ts:10368](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10368)

___

### \_\_tid\_Channel\_\_

• **\_\_tid\_Channel\_\_**: `boolean`

#### Inherited from

[Channel](ue_ue.Channel.md).[__tid_Channel__](ue_ue.Channel.md#__tid_channel__)

#### Defined in

[ue/ue.d.ts:10373](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10373)

___

### \_\_tid\_ControlChannel\_\_

• **\_\_tid\_ControlChannel\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:28717](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28717)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Channel](ue_ue.Channel.md).[__tid_Object__](ue_ue.Channel.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[Channel](ue_ue.Channel.md).[ExecuteUbergraph](ue_ue.Channel.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Channel](ue_ue.Channel.md).[GetClass](ue_ue.Channel.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Channel](ue_ue.Channel.md).[GetName](ue_ue.Channel.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Channel](ue_ue.Channel.md).[GetOuter](ue_ue.Channel.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Channel](ue_ue.Channel.md).[GetWorld](ue_ue.Channel.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ControlChannel`](ue_ue.ControlChannel.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ControlChannel`](ue_ue.ControlChannel.md)

#### Overrides

[Channel](ue_ue.Channel.md).[Find](ue_ue.Channel.md#find)

#### Defined in

[ue/ue.d.ts:28714](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28714)

___

### Load

▸ `Static` **Load**(`InName`): [`ControlChannel`](ue_ue.ControlChannel.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ControlChannel`](ue_ue.ControlChannel.md)

#### Overrides

[Channel](ue_ue.Channel.md).[Load](ue_ue.Channel.md#load)

#### Defined in

[ue/ue.d.ts:28715](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28715)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Channel](ue_ue.Channel.md).[StaticClass](ue_ue.Channel.md#staticclass)

#### Defined in

[ue/ue.d.ts:28713](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28713)
