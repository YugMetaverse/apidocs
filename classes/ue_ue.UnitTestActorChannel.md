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

## Properties

### Actor

• **Actor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[ActorChannel](ue_ue.ActorChannel.md).[Actor](ue_ue.ActorChannel.md#actor)

___

### Connection

• **Connection**: [`NetConnection`](ue_ue.NetConnection.md)

#### Inherited from

[ActorChannel](ue_ue.ActorChannel.md).[Connection](ue_ue.ActorChannel.md#connection)

___

### CreateSubObjects

• **CreateSubObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[ActorChannel](ue_ue.ActorChannel.md).[CreateSubObjects](ue_ue.ActorChannel.md#createsubobjects)

___

### \_\_tid\_ActorChannel\_\_

• **\_\_tid\_ActorChannel\_\_**: `boolean`

#### Inherited from

[ActorChannel](ue_ue.ActorChannel.md).[__tid_ActorChannel__](ue_ue.ActorChannel.md#__tid_actorchannel__)

___

### \_\_tid\_Channel\_\_

• **\_\_tid\_Channel\_\_**: `boolean`

#### Inherited from

[ActorChannel](ue_ue.ActorChannel.md).[__tid_Channel__](ue_ue.ActorChannel.md#__tid_channel__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ActorChannel](ue_ue.ActorChannel.md).[__tid_Object__](ue_ue.ActorChannel.md#__tid_object__)

___

### \_\_tid\_UnitTestActorChannel\_\_

• **\_\_tid\_UnitTestActorChannel\_\_**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ActorChannel](ue_ue.ActorChannel.md).[GetClass](ue_ue.ActorChannel.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ActorChannel](ue_ue.ActorChannel.md).[GetName](ue_ue.ActorChannel.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ActorChannel](ue_ue.ActorChannel.md).[GetOuter](ue_ue.ActorChannel.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ActorChannel](ue_ue.ActorChannel.md).[GetWorld](ue_ue.ActorChannel.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ActorChannel](ue_ue.ActorChannel.md).[StaticClass](ue_ue.ActorChannel.md#staticclass)
