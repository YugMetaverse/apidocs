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

## Properties

### Actor

• **Actor**: [`Actor`](ue_ue.Actor.md)

___

### Connection

• **Connection**: [`NetConnection`](ue_ue.NetConnection.md)

#### Inherited from

[Channel](ue_ue.Channel.md).[Connection](ue_ue.Channel.md#connection)

___

### CreateSubObjects

• **CreateSubObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

___

### \_\_tid\_ActorChannel\_\_

• **\_\_tid\_ActorChannel\_\_**: `boolean`

___

### \_\_tid\_Channel\_\_

• **\_\_tid\_Channel\_\_**: `boolean`

#### Inherited from

[Channel](ue_ue.Channel.md).[__tid_Channel__](ue_ue.Channel.md#__tid_channel__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Channel](ue_ue.Channel.md).[__tid_Object__](ue_ue.Channel.md#__tid_object__)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Channel](ue_ue.Channel.md).[GetClass](ue_ue.Channel.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Channel](ue_ue.Channel.md).[GetName](ue_ue.Channel.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Channel](ue_ue.Channel.md).[GetOuter](ue_ue.Channel.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Channel](ue_ue.Channel.md).[GetWorld](ue_ue.Channel.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Channel](ue_ue.Channel.md).[StaticClass](ue_ue.Channel.md#staticclass)
