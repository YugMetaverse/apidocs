[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / IpNetDriver

# Class: IpNetDriver

[ue/ue](../modules/ue_ue.md).IpNetDriver

## Hierarchy

- [`NetDriver`](ue_ue.NetDriver.md)

  ↳ **`IpNetDriver`**

## Table of contents

### Constructors

- [constructor](ue_ue.IpNetDriver.md#constructor)

### Properties

- [ActorChannelPool](ue_ue.IpNetDriver.md#actorchannelpool)
- [AllowPlayerPortUnreach](ue_ue.IpNetDriver.md#allowplayerportunreach)
- [ChannelDefinitionMap](ue_ue.IpNetDriver.md#channeldefinitionmap)
- [ChannelDefinitions](ue_ue.IpNetDriver.md#channeldefinitions)
- [ClientConnections](ue_ue.IpNetDriver.md#clientconnections)
- [ClientDesiredSocketReceiveBufferBytes](ue_ue.IpNetDriver.md#clientdesiredsocketreceivebufferbytes)
- [ClientDesiredSocketSendBufferBytes](ue_ue.IpNetDriver.md#clientdesiredsocketsendbufferbytes)
- [ConnectionTimeout](ue_ue.IpNetDriver.md#connectiontimeout)
- [InitialConnectTimeout](ue_ue.IpNetDriver.md#initialconnecttimeout)
- [KeepAliveTime](ue_ue.IpNetDriver.md#keepalivetime)
- [LogPortUnreach](ue_ue.IpNetDriver.md#logportunreach)
- [MaxClientRate](ue_ue.IpNetDriver.md#maxclientrate)
- [MaxDownloadSize](ue_ue.IpNetDriver.md#maxdownloadsize)
- [MaxInternetClientRate](ue_ue.IpNetDriver.md#maxinternetclientrate)
- [MaxNetTickRate](ue_ue.IpNetDriver.md#maxnettickrate)
- [MaxPortCountToTry](ue_ue.IpNetDriver.md#maxportcounttotry)
- [MaxSecondsInReceive](ue_ue.IpNetDriver.md#maxsecondsinreceive)
- [NbPacketsBetweenReceiveTimeTest](ue_ue.IpNetDriver.md#nbpacketsbetweenreceivetimetest)
- [NetConnectionClass](ue_ue.IpNetDriver.md#netconnectionclass)
- [NetConnectionClassName](ue_ue.IpNetDriver.md#netconnectionclassname)
- [NetDriverName](ue_ue.IpNetDriver.md#netdrivername)
- [NetServerMaxTickRate](ue_ue.IpNetDriver.md#netservermaxtickrate)
- [RecentlyDisconnectedTrackingTime](ue_ue.IpNetDriver.md#recentlydisconnectedtrackingtime)
- [RelevantTimeout](ue_ue.IpNetDriver.md#relevanttimeout)
- [RemoteRoleProperty](ue_ue.IpNetDriver.md#remoteroleproperty)
- [ReplicationDriver](ue_ue.IpNetDriver.md#replicationdriver)
- [ReplicationDriverClass](ue_ue.IpNetDriver.md#replicationdriverclass)
- [ReplicationDriverClassName](ue_ue.IpNetDriver.md#replicationdriverclassname)
- [RoleProperty](ue_ue.IpNetDriver.md#roleproperty)
- [ServerConnection](ue_ue.IpNetDriver.md#serverconnection)
- [ServerDesiredSocketReceiveBufferBytes](ue_ue.IpNetDriver.md#serverdesiredsocketreceivebufferbytes)
- [ServerDesiredSocketSendBufferBytes](ue_ue.IpNetDriver.md#serverdesiredsocketsendbufferbytes)
- [ServerTravelPause](ue_ue.IpNetDriver.md#servertravelpause)
- [SpawnPrioritySeconds](ue_ue.IpNetDriver.md#spawnpriorityseconds)
- [Time](ue_ue.IpNetDriver.md#time)
- [TimeoutMultiplierForUnoptimizedBuilds](ue_ue.IpNetDriver.md#timeoutmultiplierforunoptimizedbuilds)
- [World](ue_ue.IpNetDriver.md#world)
- [WorldPackage](ue_ue.IpNetDriver.md#worldpackage)
- [\_\_tid\_IpNetDriver\_\_](ue_ue.IpNetDriver.md#__tid_ipnetdriver__)
- [\_\_tid\_NetDriver\_\_](ue_ue.IpNetDriver.md#__tid_netdriver__)
- [\_\_tid\_Object\_\_](ue_ue.IpNetDriver.md#__tid_object__)
- [bClampListenServerTickRate](ue_ue.IpNetDriver.md#bclamplistenservertickrate)
- [bNeverApplyNetworkEmulationSettings](ue_ue.IpNetDriver.md#bneverapplynetworkemulationsettings)
- [bNoTimeouts](ue_ue.IpNetDriver.md#bnotimeouts)

### Methods

- [CreateDefaultSubobject](ue_ue.IpNetDriver.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.IpNetDriver.md#executeubergraph)
- [GetClass](ue_ue.IpNetDriver.md#getclass)
- [GetName](ue_ue.IpNetDriver.md#getname)
- [GetOuter](ue_ue.IpNetDriver.md#getouter)
- [GetWorld](ue_ue.IpNetDriver.md#getworld)
- [Find](ue_ue.IpNetDriver.md#find)
- [Load](ue_ue.IpNetDriver.md#load)
- [StaticClass](ue_ue.IpNetDriver.md#staticclass)

## Constructors

### constructor

• **new IpNetDriver**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[NetDriver](ue_ue.NetDriver.md).[constructor](ue_ue.NetDriver.md#constructor)

## Properties

### ActorChannelPool

• **ActorChannelPool**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Channel`](ue_ue.Channel.md)\>

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ActorChannelPool](ue_ue.NetDriver.md#actorchannelpool)

___

### AllowPlayerPortUnreach

• **AllowPlayerPortUnreach**: `boolean`

___

### ChannelDefinitionMap

• **ChannelDefinitionMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`ChannelDefinition`](ue_ue.ChannelDefinition.md)\>

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ChannelDefinitionMap](ue_ue.NetDriver.md#channeldefinitionmap)

___

### ChannelDefinitions

• **ChannelDefinitions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ChannelDefinition`](ue_ue.ChannelDefinition.md)\>

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ChannelDefinitions](ue_ue.NetDriver.md#channeldefinitions)

___

### ClientConnections

• **ClientConnections**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NetConnection`](ue_ue.NetConnection.md)\>

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ClientConnections](ue_ue.NetDriver.md#clientconnections)

___

### ClientDesiredSocketReceiveBufferBytes

• **ClientDesiredSocketReceiveBufferBytes**: `number`

___

### ClientDesiredSocketSendBufferBytes

• **ClientDesiredSocketSendBufferBytes**: `number`

___

### ConnectionTimeout

• **ConnectionTimeout**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ConnectionTimeout](ue_ue.NetDriver.md#connectiontimeout)

___

### InitialConnectTimeout

• **InitialConnectTimeout**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[InitialConnectTimeout](ue_ue.NetDriver.md#initialconnecttimeout)

___

### KeepAliveTime

• **KeepAliveTime**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[KeepAliveTime](ue_ue.NetDriver.md#keepalivetime)

___

### LogPortUnreach

• **LogPortUnreach**: `boolean`

___

### MaxClientRate

• **MaxClientRate**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[MaxClientRate](ue_ue.NetDriver.md#maxclientrate)

___

### MaxDownloadSize

• **MaxDownloadSize**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[MaxDownloadSize](ue_ue.NetDriver.md#maxdownloadsize)

___

### MaxInternetClientRate

• **MaxInternetClientRate**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[MaxInternetClientRate](ue_ue.NetDriver.md#maxinternetclientrate)

___

### MaxNetTickRate

• **MaxNetTickRate**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[MaxNetTickRate](ue_ue.NetDriver.md#maxnettickrate)

___

### MaxPortCountToTry

• **MaxPortCountToTry**: `number`

___

### MaxSecondsInReceive

• **MaxSecondsInReceive**: `number`

___

### NbPacketsBetweenReceiveTimeTest

• **NbPacketsBetweenReceiveTimeTest**: `number`

___

### NetConnectionClass

• **NetConnectionClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[NetConnectionClass](ue_ue.NetDriver.md#netconnectionclass)

___

### NetConnectionClassName

• **NetConnectionClassName**: `string`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[NetConnectionClassName](ue_ue.NetDriver.md#netconnectionclassname)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[NetDriverName](ue_ue.NetDriver.md#netdrivername)

___

### NetServerMaxTickRate

• **NetServerMaxTickRate**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[NetServerMaxTickRate](ue_ue.NetDriver.md#netservermaxtickrate)

___

### RecentlyDisconnectedTrackingTime

• **RecentlyDisconnectedTrackingTime**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[RecentlyDisconnectedTrackingTime](ue_ue.NetDriver.md#recentlydisconnectedtrackingtime)

___

### RelevantTimeout

• **RelevantTimeout**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[RelevantTimeout](ue_ue.NetDriver.md#relevanttimeout)

___

### RemoteRoleProperty

• **RemoteRoleProperty**: [`Property`](ue_ue.Property.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[RemoteRoleProperty](ue_ue.NetDriver.md#remoteroleproperty)

___

### ReplicationDriver

• **ReplicationDriver**: [`ReplicationDriver`](ue_ue.ReplicationDriver.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ReplicationDriver](ue_ue.NetDriver.md#replicationdriver)

___

### ReplicationDriverClass

• **ReplicationDriverClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ReplicationDriverClass](ue_ue.NetDriver.md#replicationdriverclass)

___

### ReplicationDriverClassName

• **ReplicationDriverClassName**: `string`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ReplicationDriverClassName](ue_ue.NetDriver.md#replicationdriverclassname)

___

### RoleProperty

• **RoleProperty**: [`Property`](ue_ue.Property.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[RoleProperty](ue_ue.NetDriver.md#roleproperty)

___

### ServerConnection

• **ServerConnection**: [`NetConnection`](ue_ue.NetConnection.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ServerConnection](ue_ue.NetDriver.md#serverconnection)

___

### ServerDesiredSocketReceiveBufferBytes

• **ServerDesiredSocketReceiveBufferBytes**: `number`

___

### ServerDesiredSocketSendBufferBytes

• **ServerDesiredSocketSendBufferBytes**: `number`

___

### ServerTravelPause

• **ServerTravelPause**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ServerTravelPause](ue_ue.NetDriver.md#servertravelpause)

___

### SpawnPrioritySeconds

• **SpawnPrioritySeconds**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[SpawnPrioritySeconds](ue_ue.NetDriver.md#spawnpriorityseconds)

___

### Time

• **Time**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[Time](ue_ue.NetDriver.md#time)

___

### TimeoutMultiplierForUnoptimizedBuilds

• **TimeoutMultiplierForUnoptimizedBuilds**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[TimeoutMultiplierForUnoptimizedBuilds](ue_ue.NetDriver.md#timeoutmultiplierforunoptimizedbuilds)

___

### World

• **World**: [`World`](ue_ue.World.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[World](ue_ue.NetDriver.md#world)

___

### WorldPackage

• **WorldPackage**: [`Package`](ue_ue.Package.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[WorldPackage](ue_ue.NetDriver.md#worldpackage)

___

### \_\_tid\_IpNetDriver\_\_

• **\_\_tid\_IpNetDriver\_\_**: `boolean`

___

### \_\_tid\_NetDriver\_\_

• **\_\_tid\_NetDriver\_\_**: `boolean`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[__tid_NetDriver__](ue_ue.NetDriver.md#__tid_netdriver__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[__tid_Object__](ue_ue.NetDriver.md#__tid_object__)

___

### bClampListenServerTickRate

• **bClampListenServerTickRate**: `boolean`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[bClampListenServerTickRate](ue_ue.NetDriver.md#bclamplistenservertickrate)

___

### bNeverApplyNetworkEmulationSettings

• **bNeverApplyNetworkEmulationSettings**: `boolean`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[bNeverApplyNetworkEmulationSettings](ue_ue.NetDriver.md#bneverapplynetworkemulationsettings)

___

### bNoTimeouts

• **bNoTimeouts**: `boolean`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[bNoTimeouts](ue_ue.NetDriver.md#bnotimeouts)

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

[NetDriver](ue_ue.NetDriver.md).[CreateDefaultSubobject](ue_ue.NetDriver.md#createdefaultsubobject)

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

[NetDriver](ue_ue.NetDriver.md).[ExecuteUbergraph](ue_ue.NetDriver.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[GetClass](ue_ue.NetDriver.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[GetName](ue_ue.NetDriver.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[GetOuter](ue_ue.NetDriver.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[GetWorld](ue_ue.NetDriver.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`IpNetDriver`](ue_ue.IpNetDriver.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`IpNetDriver`](ue_ue.IpNetDriver.md)

#### Overrides

[NetDriver](ue_ue.NetDriver.md).[Find](ue_ue.NetDriver.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`IpNetDriver`](ue_ue.IpNetDriver.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`IpNetDriver`](ue_ue.IpNetDriver.md)

#### Overrides

[NetDriver](ue_ue.NetDriver.md).[Load](ue_ue.NetDriver.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[NetDriver](ue_ue.NetDriver.md).[StaticClass](ue_ue.NetDriver.md#staticclass)
