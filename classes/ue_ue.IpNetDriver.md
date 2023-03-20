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

#### Defined in

[ue/ue.d.ts:40579](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40579)

## Properties

### ActorChannelPool

• **ActorChannelPool**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Channel`](ue_ue.Channel.md)\>

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ActorChannelPool](ue_ue.NetDriver.md#actorchannelpool)

#### Defined in

[ue/ue.d.ts:10416](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10416)

___

### AllowPlayerPortUnreach

• **AllowPlayerPortUnreach**: `boolean`

#### Defined in

[ue/ue.d.ts:40581](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40581)

___

### ChannelDefinitionMap

• **ChannelDefinitionMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`ChannelDefinition`](ue_ue.ChannelDefinition.md)\>

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ChannelDefinitionMap](ue_ue.NetDriver.md#channeldefinitionmap)

#### Defined in

[ue/ue.d.ts:10415](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10415)

___

### ChannelDefinitions

• **ChannelDefinitions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ChannelDefinition`](ue_ue.ChannelDefinition.md)\>

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ChannelDefinitions](ue_ue.NetDriver.md#channeldefinitions)

#### Defined in

[ue/ue.d.ts:10414](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10414)

___

### ClientConnections

• **ClientConnections**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NetConnection`](ue_ue.NetConnection.md)\>

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ClientConnections](ue_ue.NetDriver.md#clientconnections)

#### Defined in

[ue/ue.d.ts:10405](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10405)

___

### ClientDesiredSocketReceiveBufferBytes

• **ClientDesiredSocketReceiveBufferBytes**: `number`

#### Defined in

[ue/ue.d.ts:40585](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40585)

___

### ClientDesiredSocketSendBufferBytes

• **ClientDesiredSocketSendBufferBytes**: `number`

#### Defined in

[ue/ue.d.ts:40586](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40586)

___

### ConnectionTimeout

• **ConnectionTimeout**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ConnectionTimeout](ue_ue.NetDriver.md#connectiontimeout)

#### Defined in

[ue/ue.d.ts:10400](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10400)

___

### InitialConnectTimeout

• **InitialConnectTimeout**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[InitialConnectTimeout](ue_ue.NetDriver.md#initialconnecttimeout)

#### Defined in

[ue/ue.d.ts:10399](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10399)

___

### KeepAliveTime

• **KeepAliveTime**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[KeepAliveTime](ue_ue.NetDriver.md#keepalivetime)

#### Defined in

[ue/ue.d.ts:10398](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10398)

___

### LogPortUnreach

• **LogPortUnreach**: `boolean`

#### Defined in

[ue/ue.d.ts:40580](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40580)

___

### MaxClientRate

• **MaxClientRate**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[MaxClientRate](ue_ue.NetDriver.md#maxclientrate)

#### Defined in

[ue/ue.d.ts:10394](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10394)

___

### MaxDownloadSize

• **MaxDownloadSize**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[MaxDownloadSize](ue_ue.NetDriver.md#maxdownloadsize)

#### Defined in

[ue/ue.d.ts:10389](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10389)

___

### MaxInternetClientRate

• **MaxInternetClientRate**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[MaxInternetClientRate](ue_ue.NetDriver.md#maxinternetclientrate)

#### Defined in

[ue/ue.d.ts:10393](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10393)

___

### MaxNetTickRate

• **MaxNetTickRate**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[MaxNetTickRate](ue_ue.NetDriver.md#maxnettickrate)

#### Defined in

[ue/ue.d.ts:10392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10392)

___

### MaxPortCountToTry

• **MaxPortCountToTry**: `number`

#### Defined in

[ue/ue.d.ts:40582](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40582)

___

### MaxSecondsInReceive

• **MaxSecondsInReceive**: `number`

#### Defined in

[ue/ue.d.ts:40587](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40587)

___

### NbPacketsBetweenReceiveTimeTest

• **NbPacketsBetweenReceiveTimeTest**: `number`

#### Defined in

[ue/ue.d.ts:40588](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40588)

___

### NetConnectionClass

• **NetConnectionClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[NetConnectionClass](ue_ue.NetDriver.md#netconnectionclass)

#### Defined in

[ue/ue.d.ts:10409](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10409)

___

### NetConnectionClassName

• **NetConnectionClassName**: `string`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[NetConnectionClassName](ue_ue.NetDriver.md#netconnectionclassname)

#### Defined in

[ue/ue.d.ts:10387](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10387)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[NetDriverName](ue_ue.NetDriver.md#netdrivername)

#### Defined in

[ue/ue.d.ts:10413](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10413)

___

### NetServerMaxTickRate

• **NetServerMaxTickRate**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[NetServerMaxTickRate](ue_ue.NetDriver.md#netservermaxtickrate)

#### Defined in

[ue/ue.d.ts:10391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10391)

___

### RecentlyDisconnectedTrackingTime

• **RecentlyDisconnectedTrackingTime**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[RecentlyDisconnectedTrackingTime](ue_ue.NetDriver.md#recentlydisconnectedtrackingtime)

#### Defined in

[ue/ue.d.ts:10406](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10406)

___

### RelevantTimeout

• **RelevantTimeout**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[RelevantTimeout](ue_ue.NetDriver.md#relevanttimeout)

#### Defined in

[ue/ue.d.ts:10397](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10397)

___

### RemoteRoleProperty

• **RemoteRoleProperty**: [`Property`](ue_ue.Property.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[RemoteRoleProperty](ue_ue.NetDriver.md#remoteroleproperty)

#### Defined in

[ue/ue.d.ts:10412](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10412)

___

### ReplicationDriver

• **ReplicationDriver**: [`ReplicationDriver`](ue_ue.ReplicationDriver.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ReplicationDriver](ue_ue.NetDriver.md#replicationdriver)

#### Defined in

[ue/ue.d.ts:10418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10418)

___

### ReplicationDriverClass

• **ReplicationDriverClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ReplicationDriverClass](ue_ue.NetDriver.md#replicationdriverclass)

#### Defined in

[ue/ue.d.ts:10410](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10410)

___

### ReplicationDriverClassName

• **ReplicationDriverClassName**: `string`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ReplicationDriverClassName](ue_ue.NetDriver.md#replicationdriverclassname)

#### Defined in

[ue/ue.d.ts:10388](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10388)

___

### RoleProperty

• **RoleProperty**: [`Property`](ue_ue.Property.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[RoleProperty](ue_ue.NetDriver.md#roleproperty)

#### Defined in

[ue/ue.d.ts:10411](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10411)

___

### ServerConnection

• **ServerConnection**: [`NetConnection`](ue_ue.NetConnection.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ServerConnection](ue_ue.NetDriver.md#serverconnection)

#### Defined in

[ue/ue.d.ts:10404](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10404)

___

### ServerDesiredSocketReceiveBufferBytes

• **ServerDesiredSocketReceiveBufferBytes**: `number`

#### Defined in

[ue/ue.d.ts:40583](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40583)

___

### ServerDesiredSocketSendBufferBytes

• **ServerDesiredSocketSendBufferBytes**: `number`

#### Defined in

[ue/ue.d.ts:40584](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40584)

___

### ServerTravelPause

• **ServerTravelPause**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ServerTravelPause](ue_ue.NetDriver.md#servertravelpause)

#### Defined in

[ue/ue.d.ts:10395](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10395)

___

### SpawnPrioritySeconds

• **SpawnPrioritySeconds**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[SpawnPrioritySeconds](ue_ue.NetDriver.md#spawnpriorityseconds)

#### Defined in

[ue/ue.d.ts:10396](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10396)

___

### Time

• **Time**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[Time](ue_ue.NetDriver.md#time)

#### Defined in

[ue/ue.d.ts:10417](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10417)

___

### TimeoutMultiplierForUnoptimizedBuilds

• **TimeoutMultiplierForUnoptimizedBuilds**: `number`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[TimeoutMultiplierForUnoptimizedBuilds](ue_ue.NetDriver.md#timeoutmultiplierforunoptimizedbuilds)

#### Defined in

[ue/ue.d.ts:10401](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10401)

___

### World

• **World**: [`World`](ue_ue.World.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[World](ue_ue.NetDriver.md#world)

#### Defined in

[ue/ue.d.ts:10407](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10407)

___

### WorldPackage

• **WorldPackage**: [`Package`](ue_ue.Package.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[WorldPackage](ue_ue.NetDriver.md#worldpackage)

#### Defined in

[ue/ue.d.ts:10408](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10408)

___

### \_\_tid\_IpNetDriver\_\_

• **\_\_tid\_IpNetDriver\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:40593](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40593)

___

### \_\_tid\_NetDriver\_\_

• **\_\_tid\_NetDriver\_\_**: `boolean`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[__tid_NetDriver__](ue_ue.NetDriver.md#__tid_netdriver__)

#### Defined in

[ue/ue.d.ts:10423](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10423)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[__tid_Object__](ue_ue.NetDriver.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bClampListenServerTickRate

• **bClampListenServerTickRate**: `boolean`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[bClampListenServerTickRate](ue_ue.NetDriver.md#bclamplistenservertickrate)

#### Defined in

[ue/ue.d.ts:10390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10390)

___

### bNeverApplyNetworkEmulationSettings

• **bNeverApplyNetworkEmulationSettings**: `boolean`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[bNeverApplyNetworkEmulationSettings](ue_ue.NetDriver.md#bneverapplynetworkemulationsettings)

#### Defined in

[ue/ue.d.ts:10403](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10403)

___

### bNoTimeouts

• **bNoTimeouts**: `boolean`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[bNoTimeouts](ue_ue.NetDriver.md#bnotimeouts)

#### Defined in

[ue/ue.d.ts:10402](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10402)

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

[NetDriver](ue_ue.NetDriver.md).[ExecuteUbergraph](ue_ue.NetDriver.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[GetClass](ue_ue.NetDriver.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[GetName](ue_ue.NetDriver.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[GetOuter](ue_ue.NetDriver.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[GetWorld](ue_ue.NetDriver.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:40590](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40590)

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

#### Defined in

[ue/ue.d.ts:40591](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40591)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[NetDriver](ue_ue.NetDriver.md).[StaticClass](ue_ue.NetDriver.md#staticclass)

#### Defined in

[ue/ue.d.ts:40589](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40589)
