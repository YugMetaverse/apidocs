[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VoiceChannel

# Class: VoiceChannel

[ue/ue](../modules/ue_ue.md).VoiceChannel

## Hierarchy

- [`Channel`](ue_ue.Channel.md)

  ↳ **`VoiceChannel`**

## Table of contents

### Constructors

- [constructor](ue_ue.VoiceChannel.md#constructor)

### Properties

- [Connection](ue_ue.VoiceChannel.md#connection)
- [\_\_tid\_Channel\_\_](ue_ue.VoiceChannel.md#__tid_channel__)
- [\_\_tid\_Object\_\_](ue_ue.VoiceChannel.md#__tid_object__)
- [\_\_tid\_VoiceChannel\_\_](ue_ue.VoiceChannel.md#__tid_voicechannel__)

### Methods

- [CreateDefaultSubobject](ue_ue.VoiceChannel.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.VoiceChannel.md#executeubergraph)
- [GetClass](ue_ue.VoiceChannel.md#getclass)
- [GetName](ue_ue.VoiceChannel.md#getname)
- [GetOuter](ue_ue.VoiceChannel.md#getouter)
- [GetWorld](ue_ue.VoiceChannel.md#getworld)
- [Find](ue_ue.VoiceChannel.md#find)
- [Load](ue_ue.VoiceChannel.md#load)
- [StaticClass](ue_ue.VoiceChannel.md#staticclass)

## Constructors

### constructor

• **new VoiceChannel**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Channel](ue_ue.Channel.md).[constructor](ue_ue.Channel.md#constructor)

#### Defined in

[ue/ue.d.ts:65431](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65431)

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

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Channel](ue_ue.Channel.md).[__tid_Object__](ue_ue.Channel.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_VoiceChannel\_\_

• **\_\_tid\_VoiceChannel\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:65436](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65436)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`VoiceChannel`](ue_ue.VoiceChannel.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`VoiceChannel`](ue_ue.VoiceChannel.md)

#### Overrides

[Channel](ue_ue.Channel.md).[Find](ue_ue.Channel.md#find)

#### Defined in

[ue/ue.d.ts:65433](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65433)

___

### Load

▸ `Static` **Load**(`InName`): [`VoiceChannel`](ue_ue.VoiceChannel.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`VoiceChannel`](ue_ue.VoiceChannel.md)

#### Overrides

[Channel](ue_ue.Channel.md).[Load](ue_ue.Channel.md#load)

#### Defined in

[ue/ue.d.ts:65434](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65434)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Channel](ue_ue.Channel.md).[StaticClass](ue_ue.Channel.md#staticclass)

#### Defined in

[ue/ue.d.ts:65432](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65432)