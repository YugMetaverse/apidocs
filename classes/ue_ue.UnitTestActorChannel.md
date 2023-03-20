[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UnitTestActorChannel

# Class: UnitTestActorChannel

[ue/ue](../modules/ue_ue.md).UnitTestActorChannel

## Hierarchy

- [`ActorChannel`](ue_ue.ActorChannel.md)

  ↳ **`UnitTestActorChannel`**

## Table of contents

### Constructors

- [constructor](ue_ue.UnitTestActorChannel.md#constructor)

### Properties

- [Actor](ue_ue.UnitTestActorChannel.md#actor)
- [Connection](ue_ue.UnitTestActorChannel.md#connection)
- [CreateSubObjects](ue_ue.UnitTestActorChannel.md#createsubobjects)
- [\_\_tid\_ActorChannel\_\_](ue_ue.UnitTestActorChannel.md#__tid_actorchannel__)
- [\_\_tid\_Channel\_\_](ue_ue.UnitTestActorChannel.md#__tid_channel__)
- [\_\_tid\_Object\_\_](ue_ue.UnitTestActorChannel.md#__tid_object__)
- [\_\_tid\_UnitTestActorChannel\_\_](ue_ue.UnitTestActorChannel.md#__tid_unittestactorchannel__)

### Methods

- [CreateDefaultSubobject](ue_ue.UnitTestActorChannel.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UnitTestActorChannel.md#executeubergraph)
- [GetClass](ue_ue.UnitTestActorChannel.md#getclass)
- [GetName](ue_ue.UnitTestActorChannel.md#getname)
- [GetOuter](ue_ue.UnitTestActorChannel.md#getouter)
- [GetWorld](ue_ue.UnitTestActorChannel.md#getworld)
- [Find](ue_ue.UnitTestActorChannel.md#find)
- [Load](ue_ue.UnitTestActorChannel.md#load)
- [StaticClass](ue_ue.UnitTestActorChannel.md#staticclass)

## Constructors

### constructor

• **new UnitTestActorChannel**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ActorChannel](ue_ue.ActorChannel.md).[constructor](ue_ue.ActorChannel.md#constructor)

#### Defined in

[ue/ue.d.ts:64595](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64595)

## Properties

### Actor

• **Actor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[ActorChannel](ue_ue.ActorChannel.md).[Actor](ue_ue.ActorChannel.md#actor)

#### Defined in

[ue/ue.d.ts:13489](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13489)

___

### Connection

• **Connection**: [`NetConnection`](ue_ue.NetConnection.md)

#### Inherited from

[ActorChannel](ue_ue.ActorChannel.md).[Connection](ue_ue.ActorChannel.md#connection)

#### Defined in

[ue/ue.d.ts:10368](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10368)

___

### CreateSubObjects

• **CreateSubObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[ActorChannel](ue_ue.ActorChannel.md).[CreateSubObjects](ue_ue.ActorChannel.md#createsubobjects)

#### Defined in

[ue/ue.d.ts:13490](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13490)

___

### \_\_tid\_ActorChannel\_\_

• **\_\_tid\_ActorChannel\_\_**: `boolean`

#### Inherited from

[ActorChannel](ue_ue.ActorChannel.md).[__tid_ActorChannel__](ue_ue.ActorChannel.md#__tid_actorchannel__)

#### Defined in

[ue/ue.d.ts:13495](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13495)

___

### \_\_tid\_Channel\_\_

• **\_\_tid\_Channel\_\_**: `boolean`

#### Inherited from

[ActorChannel](ue_ue.ActorChannel.md).[__tid_Channel__](ue_ue.ActorChannel.md#__tid_channel__)

#### Defined in

[ue/ue.d.ts:10373](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10373)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ActorChannel](ue_ue.ActorChannel.md).[__tid_Object__](ue_ue.ActorChannel.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_UnitTestActorChannel\_\_

• **\_\_tid\_UnitTestActorChannel\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:64600](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64600)

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

[ActorChannel](ue_ue.ActorChannel.md).[CreateDefaultSubobject](ue_ue.ActorChannel.md#createdefaultsubobject)

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

[ActorChannel](ue_ue.ActorChannel.md).[ExecuteUbergraph](ue_ue.ActorChannel.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ActorChannel](ue_ue.ActorChannel.md).[GetClass](ue_ue.ActorChannel.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ActorChannel](ue_ue.ActorChannel.md).[GetName](ue_ue.ActorChannel.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ActorChannel](ue_ue.ActorChannel.md).[GetOuter](ue_ue.ActorChannel.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ActorChannel](ue_ue.ActorChannel.md).[GetWorld](ue_ue.ActorChannel.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UnitTestActorChannel`](ue_ue.UnitTestActorChannel.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UnitTestActorChannel`](ue_ue.UnitTestActorChannel.md)

#### Overrides

[ActorChannel](ue_ue.ActorChannel.md).[Find](ue_ue.ActorChannel.md#find)

#### Defined in

[ue/ue.d.ts:64597](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64597)

___

### Load

▸ `Static` **Load**(`InName`): [`UnitTestActorChannel`](ue_ue.UnitTestActorChannel.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UnitTestActorChannel`](ue_ue.UnitTestActorChannel.md)

#### Overrides

[ActorChannel](ue_ue.ActorChannel.md).[Load](ue_ue.ActorChannel.md#load)

#### Defined in

[ue/ue.d.ts:64598](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64598)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ActorChannel](ue_ue.ActorChannel.md).[StaticClass](ue_ue.ActorChannel.md#staticclass)

#### Defined in

[ue/ue.d.ts:64596](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64596)
