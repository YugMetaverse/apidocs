[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NetDriver

# Class: NetDriver

[ue/ue](../modules/ue_ue.md).NetDriver

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`NetDriver`**

  ↳↳ [`DemoNetDriver`](ue_ue.DemoNetDriver.md)

  ↳↳ [`IpNetDriver`](ue_ue.IpNetDriver.md)

## Table of contents

### Constructors

- [constructor](ue_ue.NetDriver.md#constructor)

### Properties

- [ActorChannelPool](ue_ue.NetDriver.md#actorchannelpool)
- [ChannelDefinitionMap](ue_ue.NetDriver.md#channeldefinitionmap)
- [ChannelDefinitions](ue_ue.NetDriver.md#channeldefinitions)
- [ClientConnections](ue_ue.NetDriver.md#clientconnections)
- [ConnectionTimeout](ue_ue.NetDriver.md#connectiontimeout)
- [InitialConnectTimeout](ue_ue.NetDriver.md#initialconnecttimeout)
- [KeepAliveTime](ue_ue.NetDriver.md#keepalivetime)
- [MaxClientRate](ue_ue.NetDriver.md#maxclientrate)
- [MaxDownloadSize](ue_ue.NetDriver.md#maxdownloadsize)
- [MaxInternetClientRate](ue_ue.NetDriver.md#maxinternetclientrate)
- [MaxNetTickRate](ue_ue.NetDriver.md#maxnettickrate)
- [NetConnectionClass](ue_ue.NetDriver.md#netconnectionclass)
- [NetConnectionClassName](ue_ue.NetDriver.md#netconnectionclassname)
- [NetDriverName](ue_ue.NetDriver.md#netdrivername)
- [NetServerMaxTickRate](ue_ue.NetDriver.md#netservermaxtickrate)
- [RecentlyDisconnectedTrackingTime](ue_ue.NetDriver.md#recentlydisconnectedtrackingtime)
- [RelevantTimeout](ue_ue.NetDriver.md#relevanttimeout)
- [RemoteRoleProperty](ue_ue.NetDriver.md#remoteroleproperty)
- [ReplicationDriver](ue_ue.NetDriver.md#replicationdriver)
- [ReplicationDriverClass](ue_ue.NetDriver.md#replicationdriverclass)
- [ReplicationDriverClassName](ue_ue.NetDriver.md#replicationdriverclassname)
- [RoleProperty](ue_ue.NetDriver.md#roleproperty)
- [ServerConnection](ue_ue.NetDriver.md#serverconnection)
- [ServerTravelPause](ue_ue.NetDriver.md#servertravelpause)
- [SpawnPrioritySeconds](ue_ue.NetDriver.md#spawnpriorityseconds)
- [Time](ue_ue.NetDriver.md#time)
- [TimeoutMultiplierForUnoptimizedBuilds](ue_ue.NetDriver.md#timeoutmultiplierforunoptimizedbuilds)
- [World](ue_ue.NetDriver.md#world)
- [WorldPackage](ue_ue.NetDriver.md#worldpackage)
- [\_\_tid\_NetDriver\_\_](ue_ue.NetDriver.md#__tid_netdriver__)
- [\_\_tid\_Object\_\_](ue_ue.NetDriver.md#__tid_object__)
- [bClampListenServerTickRate](ue_ue.NetDriver.md#bclamplistenservertickrate)
- [bNeverApplyNetworkEmulationSettings](ue_ue.NetDriver.md#bneverapplynetworkemulationsettings)
- [bNoTimeouts](ue_ue.NetDriver.md#bnotimeouts)

### Methods

- [CreateDefaultSubobject](ue_ue.NetDriver.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.NetDriver.md#executeubergraph)
- [GetClass](ue_ue.NetDriver.md#getclass)
- [GetName](ue_ue.NetDriver.md#getname)
- [GetOuter](ue_ue.NetDriver.md#getouter)
- [GetWorld](ue_ue.NetDriver.md#getworld)
- [Find](ue_ue.NetDriver.md#find)
- [Load](ue_ue.NetDriver.md#load)
- [StaticClass](ue_ue.NetDriver.md#staticclass)

## Constructors

### constructor

• **new NetDriver**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ActorChannelPool

• **ActorChannelPool**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Channel`](ue_ue.Channel.md)\>

___

### ChannelDefinitionMap

• **ChannelDefinitionMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`ChannelDefinition`](ue_ue.ChannelDefinition.md)\>

___

### ChannelDefinitions

• **ChannelDefinitions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ChannelDefinition`](ue_ue.ChannelDefinition.md)\>

___

### ClientConnections

• **ClientConnections**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NetConnection`](ue_ue.NetConnection.md)\>

___

### ConnectionTimeout

• **ConnectionTimeout**: `number`

___

### InitialConnectTimeout

• **InitialConnectTimeout**: `number`

___

### KeepAliveTime

• **KeepAliveTime**: `number`

___

### MaxClientRate

• **MaxClientRate**: `number`

___

### MaxDownloadSize

• **MaxDownloadSize**: `number`

___

### MaxInternetClientRate

• **MaxInternetClientRate**: `number`

___

### MaxNetTickRate

• **MaxNetTickRate**: `number`

___

### NetConnectionClass

• **NetConnectionClass**: [`Class`](ue_ue.Class.md)

___

### NetConnectionClassName

• **NetConnectionClassName**: `string`

___

### NetDriverName

• **NetDriverName**: `string`

___

### NetServerMaxTickRate

• **NetServerMaxTickRate**: `number`

___

### RecentlyDisconnectedTrackingTime

• **RecentlyDisconnectedTrackingTime**: `number`

___

### RelevantTimeout

• **RelevantTimeout**: `number`

___

### RemoteRoleProperty

• **RemoteRoleProperty**: [`Property`](ue_ue.Property.md)

___

### ReplicationDriver

• **ReplicationDriver**: [`ReplicationDriver`](ue_ue.ReplicationDriver.md)

___

### ReplicationDriverClass

• **ReplicationDriverClass**: [`Class`](ue_ue.Class.md)

___

### ReplicationDriverClassName

• **ReplicationDriverClassName**: `string`

___

### RoleProperty

• **RoleProperty**: [`Property`](ue_ue.Property.md)

___

### ServerConnection

• **ServerConnection**: [`NetConnection`](ue_ue.NetConnection.md)

___

### ServerTravelPause

• **ServerTravelPause**: `number`

___

### SpawnPrioritySeconds

• **SpawnPrioritySeconds**: `number`

___

### Time

• **Time**: `number`

___

### TimeoutMultiplierForUnoptimizedBuilds

• **TimeoutMultiplierForUnoptimizedBuilds**: `number`

___

### World

• **World**: [`World`](ue_ue.World.md)

___

### WorldPackage

• **WorldPackage**: [`Package`](ue_ue.Package.md)

___

### \_\_tid\_NetDriver\_\_

• **\_\_tid\_NetDriver\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bClampListenServerTickRate

• **bClampListenServerTickRate**: `boolean`

___

### bNeverApplyNetworkEmulationSettings

• **bNeverApplyNetworkEmulationSettings**: `boolean`

___

### bNoTimeouts

• **bNoTimeouts**: `boolean`

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`NetDriver`](ue_ue.NetDriver.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`NetDriver`](ue_ue.NetDriver.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`NetDriver`](ue_ue.NetDriver.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`NetDriver`](ue_ue.NetDriver.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
