[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ActorChannel

# Class: ActorChannel

[ue/ue](../modules/ue_ue.md).ActorChannel

## Hierarchy

- [`Channel`](ue_ue.Channel.md)

  ↳ **`ActorChannel`**

  ↳↳ [`UnitTestActorChannel`](ue_ue.UnitTestActorChannel.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ActorChannel.md#constructor)

### Properties

- [Actor](ue_ue.ActorChannel.md#actor)
- [Connection](ue_ue.ActorChannel.md#connection)
- [CreateSubObjects](ue_ue.ActorChannel.md#createsubobjects)
- [\_\_tid\_ActorChannel\_\_](ue_ue.ActorChannel.md#__tid_actorchannel__)
- [\_\_tid\_Channel\_\_](ue_ue.ActorChannel.md#__tid_channel__)
- [\_\_tid\_Object\_\_](ue_ue.ActorChannel.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ActorChannel.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ActorChannel.md#executeubergraph)
- [GetClass](ue_ue.ActorChannel.md#getclass)
- [GetName](ue_ue.ActorChannel.md#getname)
- [GetOuter](ue_ue.ActorChannel.md#getouter)
- [GetWorld](ue_ue.ActorChannel.md#getworld)
- [Find](ue_ue.ActorChannel.md#find)
- [Load](ue_ue.ActorChannel.md#load)
- [StaticClass](ue_ue.ActorChannel.md#staticclass)

## Constructors

### constructor

• **new ActorChannel**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Channel](ue_ue.Channel.md).[constructor](ue_ue.Channel.md#constructor)

#### Defined in

[ue/ue.d.ts:13488](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13488)

## Properties

### Actor

• **Actor**: [`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:13489](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13489)

___

### Connection

• **Connection**: [`NetConnection`](ue_ue.NetConnection.md)

#### Inherited from

[Channel](ue_ue.Channel.md).[Connection](ue_ue.Channel.md#connection)

#### Defined in

[ue/ue.d.ts:10368](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10368)

___

### CreateSubObjects

• **CreateSubObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:13490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13490)

___

### \_\_tid\_ActorChannel\_\_

• **\_\_tid\_ActorChannel\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:13495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13495)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ActorChannel`](ue_ue.ActorChannel.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ActorChannel`](ue_ue.ActorChannel.md)

#### Overrides

[Channel](ue_ue.Channel.md).[Find](ue_ue.Channel.md#find)

#### Defined in

[ue/ue.d.ts:13492](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13492)

___

### Load

▸ `Static` **Load**(`InName`): [`ActorChannel`](ue_ue.ActorChannel.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ActorChannel`](ue_ue.ActorChannel.md)

#### Overrides

[Channel](ue_ue.Channel.md).[Load](ue_ue.Channel.md#load)

#### Defined in

[ue/ue.d.ts:13493](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13493)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Channel](ue_ue.Channel.md).[StaticClass](ue_ue.Channel.md#staticclass)

#### Defined in

[ue/ue.d.ts:13491](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13491)
