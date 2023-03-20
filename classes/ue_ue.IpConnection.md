[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / IpConnection

# Class: IpConnection

[ue/ue](../modules/ue_ue.md).IpConnection

## Hierarchy

- [`NetConnection`](ue_ue.NetConnection.md)

  ↳ **`IpConnection`**

## Table of contents

### Constructors

- [constructor](ue_ue.IpConnection.md#constructor)

### Properties

- [ChannelsToTick](ue_ue.IpConnection.md#channelstotick)
- [Children](ue_ue.IpConnection.md#children)
- [ConfiguredInternetSpeed](ue_ue.IpConnection.md#configuredinternetspeed)
- [ConfiguredLanSpeed](ue_ue.IpConnection.md#configuredlanspeed)
- [CurrentNetSpeed](ue_ue.IpConnection.md#currentnetspeed)
- [Driver](ue_ue.IpConnection.md#driver)
- [InternalAck](ue_ue.IpConnection.md#internalack)
- [LastReceiveTime](ue_ue.IpConnection.md#lastreceivetime)
- [MaxPacket](ue_ue.IpConnection.md#maxpacket)
- [OpenChannels](ue_ue.IpConnection.md#openchannels)
- [OwningActor](ue_ue.IpConnection.md#owningactor)
- [PackageMap](ue_ue.IpConnection.md#packagemap)
- [PackageMapClass](ue_ue.IpConnection.md#packagemapclass)
- [PlayerController](ue_ue.IpConnection.md#playercontroller)
- [PlayerId](ue_ue.IpConnection.md#playerid)
- [SentTemporaries](ue_ue.IpConnection.md#senttemporaries)
- [SocketErrorDisconnectDelay](ue_ue.IpConnection.md#socketerrordisconnectdelay)
- [ViewTarget](ue_ue.IpConnection.md#viewtarget)
- [\_\_tid\_IpConnection\_\_](ue_ue.IpConnection.md#__tid_ipconnection__)
- [\_\_tid\_NetConnection\_\_](ue_ue.IpConnection.md#__tid_netconnection__)
- [\_\_tid\_Object\_\_](ue_ue.IpConnection.md#__tid_object__)
- [\_\_tid\_Player\_\_](ue_ue.IpConnection.md#__tid_player__)

### Methods

- [CreateDefaultSubobject](ue_ue.IpConnection.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.IpConnection.md#executeubergraph)
- [GetClass](ue_ue.IpConnection.md#getclass)
- [GetName](ue_ue.IpConnection.md#getname)
- [GetOuter](ue_ue.IpConnection.md#getouter)
- [GetWorld](ue_ue.IpConnection.md#getworld)
- [Find](ue_ue.IpConnection.md#find)
- [Load](ue_ue.IpConnection.md#load)
- [StaticClass](ue_ue.IpConnection.md#staticclass)

## Constructors

### constructor

• **new IpConnection**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[NetConnection](ue_ue.NetConnection.md).[constructor](ue_ue.NetConnection.md#constructor)

## Properties

### ChannelsToTick

• **ChannelsToTick**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Channel`](ue_ue.Channel.md)\>

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[ChannelsToTick](ue_ue.NetConnection.md#channelstotick)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ChildConnection`](ue_ue.ChildConnection.md)\>

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[Children](ue_ue.NetConnection.md#children)

___

### ConfiguredInternetSpeed

• **ConfiguredInternetSpeed**: `number`

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[ConfiguredInternetSpeed](ue_ue.NetConnection.md#configuredinternetspeed)

___

### ConfiguredLanSpeed

• **ConfiguredLanSpeed**: `number`

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[ConfiguredLanSpeed](ue_ue.NetConnection.md#configuredlanspeed)

___

### CurrentNetSpeed

• **CurrentNetSpeed**: `number`

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[CurrentNetSpeed](ue_ue.NetConnection.md#currentnetspeed)

___

### Driver

• **Driver**: [`NetDriver`](ue_ue.NetDriver.md)

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[Driver](ue_ue.NetConnection.md#driver)

___

### InternalAck

• **InternalAck**: `boolean`

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[InternalAck](ue_ue.NetConnection.md#internalack)

___

### LastReceiveTime

• **LastReceiveTime**: `number`

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[LastReceiveTime](ue_ue.NetConnection.md#lastreceivetime)

___

### MaxPacket

• **MaxPacket**: `number`

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[MaxPacket](ue_ue.NetConnection.md#maxpacket)

___

### OpenChannels

• **OpenChannels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Channel`](ue_ue.Channel.md)\>

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[OpenChannels](ue_ue.NetConnection.md#openchannels)

___

### OwningActor

• **OwningActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[OwningActor](ue_ue.NetConnection.md#owningactor)

___

### PackageMap

• **PackageMap**: [`PackageMap`](ue_ue.PackageMap.md)

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[PackageMap](ue_ue.NetConnection.md#packagemap)

___

### PackageMapClass

• **PackageMapClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[PackageMapClass](ue_ue.NetConnection.md#packagemapclass)

___

### PlayerController

• **PlayerController**: [`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[PlayerController](ue_ue.NetConnection.md#playercontroller)

___

### PlayerId

• **PlayerId**: [`UniqueNetIdRepl`](ue_ue.UniqueNetIdRepl.md)

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[PlayerId](ue_ue.NetConnection.md#playerid)

___

### SentTemporaries

• **SentTemporaries**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[SentTemporaries](ue_ue.NetConnection.md#senttemporaries)

___

### SocketErrorDisconnectDelay

• **SocketErrorDisconnectDelay**: `number`

___

### ViewTarget

• **ViewTarget**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[ViewTarget](ue_ue.NetConnection.md#viewtarget)

___

### \_\_tid\_IpConnection\_\_

• **\_\_tid\_IpConnection\_\_**: `boolean`

___

### \_\_tid\_NetConnection\_\_

• **\_\_tid\_NetConnection\_\_**: `boolean`

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[__tid_NetConnection__](ue_ue.NetConnection.md#__tid_netconnection__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[__tid_Object__](ue_ue.NetConnection.md#__tid_object__)

___

### \_\_tid\_Player\_\_

• **\_\_tid\_Player\_\_**: `boolean`

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[__tid_Player__](ue_ue.NetConnection.md#__tid_player__)

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

[NetConnection](ue_ue.NetConnection.md).[CreateDefaultSubobject](ue_ue.NetConnection.md#createdefaultsubobject)

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

[NetConnection](ue_ue.NetConnection.md).[ExecuteUbergraph](ue_ue.NetConnection.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[GetClass](ue_ue.NetConnection.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[GetName](ue_ue.NetConnection.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[GetOuter](ue_ue.NetConnection.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[GetWorld](ue_ue.NetConnection.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`IpConnection`](ue_ue.IpConnection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`IpConnection`](ue_ue.IpConnection.md)

#### Overrides

[NetConnection](ue_ue.NetConnection.md).[Find](ue_ue.NetConnection.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`IpConnection`](ue_ue.IpConnection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`IpConnection`](ue_ue.IpConnection.md)

#### Overrides

[NetConnection](ue_ue.NetConnection.md).[Load](ue_ue.NetConnection.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[NetConnection](ue_ue.NetConnection.md).[StaticClass](ue_ue.NetConnection.md#staticclass)
