[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DemoNetDriver

# Class: DemoNetDriver

[ue/ue](../modules/ue_ue.md).DemoNetDriver

## Hierarchy

- [`NetDriver`](ue_ue.NetDriver.md)

  ↳ **`DemoNetDriver`**

## Table of contents

### Constructors

- [constructor](ue_ue.DemoNetDriver.md#constructor)

### Properties

- [ActorChannelPool](ue_ue.DemoNetDriver.md#actorchannelpool)
- [ChannelDefinitionMap](ue_ue.DemoNetDriver.md#channeldefinitionmap)
- [ChannelDefinitions](ue_ue.DemoNetDriver.md#channeldefinitions)
- [CheckpointSaveMaxMSPerFrame](ue_ue.DemoNetDriver.md#checkpointsavemaxmsperframe)
- [ClientConnections](ue_ue.DemoNetDriver.md#clientconnections)
- [ConnectionTimeout](ue_ue.DemoNetDriver.md#connectiontimeout)
- [InitialConnectTimeout](ue_ue.DemoNetDriver.md#initialconnecttimeout)
- [KeepAliveTime](ue_ue.DemoNetDriver.md#keepalivetime)
- [MaxClientRate](ue_ue.DemoNetDriver.md#maxclientrate)
- [MaxDownloadSize](ue_ue.DemoNetDriver.md#maxdownloadsize)
- [MaxInternetClientRate](ue_ue.DemoNetDriver.md#maxinternetclientrate)
- [MaxNetTickRate](ue_ue.DemoNetDriver.md#maxnettickrate)
- [MulticastRecordOptions](ue_ue.DemoNetDriver.md#multicastrecordoptions)
- [NetConnectionClass](ue_ue.DemoNetDriver.md#netconnectionclass)
- [NetConnectionClassName](ue_ue.DemoNetDriver.md#netconnectionclassname)
- [NetDriverName](ue_ue.DemoNetDriver.md#netdrivername)
- [NetServerMaxTickRate](ue_ue.DemoNetDriver.md#netservermaxtickrate)
- [RecentlyDisconnectedTrackingTime](ue_ue.DemoNetDriver.md#recentlydisconnectedtrackingtime)
- [RelevantTimeout](ue_ue.DemoNetDriver.md#relevanttimeout)
- [RemoteRoleProperty](ue_ue.DemoNetDriver.md#remoteroleproperty)
- [ReplicationDriver](ue_ue.DemoNetDriver.md#replicationdriver)
- [ReplicationDriverClass](ue_ue.DemoNetDriver.md#replicationdriverclass)
- [ReplicationDriverClassName](ue_ue.DemoNetDriver.md#replicationdriverclassname)
- [RoleProperty](ue_ue.DemoNetDriver.md#roleproperty)
- [RollbackNetStartupActors](ue_ue.DemoNetDriver.md#rollbacknetstartupactors)
- [ServerConnection](ue_ue.DemoNetDriver.md#serverconnection)
- [ServerTravelPause](ue_ue.DemoNetDriver.md#servertravelpause)
- [SpawnPrioritySeconds](ue_ue.DemoNetDriver.md#spawnpriorityseconds)
- [SpectatorControllers](ue_ue.DemoNetDriver.md#spectatorcontrollers)
- [Time](ue_ue.DemoNetDriver.md#time)
- [TimeoutMultiplierForUnoptimizedBuilds](ue_ue.DemoNetDriver.md#timeoutmultiplierforunoptimizedbuilds)
- [World](ue_ue.DemoNetDriver.md#world)
- [WorldPackage](ue_ue.DemoNetDriver.md#worldpackage)
- [\_\_tid\_DemoNetDriver\_\_](ue_ue.DemoNetDriver.md#__tid_demonetdriver__)
- [\_\_tid\_NetDriver\_\_](ue_ue.DemoNetDriver.md#__tid_netdriver__)
- [\_\_tid\_Object\_\_](ue_ue.DemoNetDriver.md#__tid_object__)
- [bClampListenServerTickRate](ue_ue.DemoNetDriver.md#bclamplistenservertickrate)
- [bIsLocalReplay](ue_ue.DemoNetDriver.md#bislocalreplay)
- [bNeverApplyNetworkEmulationSettings](ue_ue.DemoNetDriver.md#bneverapplynetworkemulationsettings)
- [bNoTimeouts](ue_ue.DemoNetDriver.md#bnotimeouts)

### Methods

- [CreateDefaultSubobject](ue_ue.DemoNetDriver.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DemoNetDriver.md#executeubergraph)
- [GetClass](ue_ue.DemoNetDriver.md#getclass)
- [GetName](ue_ue.DemoNetDriver.md#getname)
- [GetOuter](ue_ue.DemoNetDriver.md#getouter)
- [GetWorld](ue_ue.DemoNetDriver.md#getworld)
- [Find](ue_ue.DemoNetDriver.md#find)
- [Load](ue_ue.DemoNetDriver.md#load)
- [StaticClass](ue_ue.DemoNetDriver.md#staticclass)

## Constructors

### constructor

• **new DemoNetDriver**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### CheckpointSaveMaxMSPerFrame

• **CheckpointSaveMaxMSPerFrame**: `number`

___

### ClientConnections

• **ClientConnections**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NetConnection`](ue_ue.NetConnection.md)\>

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ClientConnections](ue_ue.NetDriver.md#clientconnections)

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

### MulticastRecordOptions

• **MulticastRecordOptions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MulticastRecordOptions`](ue_ue.MulticastRecordOptions.md)\>

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

### RollbackNetStartupActors

• **RollbackNetStartupActors**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`RollbackNetStartupActorInfo`](ue_ue.RollbackNetStartupActorInfo.md)\>

___

### ServerConnection

• **ServerConnection**: [`NetConnection`](ue_ue.NetConnection.md)

#### Inherited from

[NetDriver](ue_ue.NetDriver.md).[ServerConnection](ue_ue.NetDriver.md#serverconnection)

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

### SpectatorControllers

• **SpectatorControllers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PlayerController`](ue_ue.PlayerController.md)\>

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

### \_\_tid\_DemoNetDriver\_\_

• **\_\_tid\_DemoNetDriver\_\_**: `boolean`

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

### bIsLocalReplay

• **bIsLocalReplay**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DemoNetDriver`](ue_ue.DemoNetDriver.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DemoNetDriver`](ue_ue.DemoNetDriver.md)

#### Overrides

[NetDriver](ue_ue.NetDriver.md).[Find](ue_ue.NetDriver.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DemoNetDriver`](ue_ue.DemoNetDriver.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DemoNetDriver`](ue_ue.DemoNetDriver.md)

#### Overrides

[NetDriver](ue_ue.NetDriver.md).[Load](ue_ue.NetDriver.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[NetDriver](ue_ue.NetDriver.md).[StaticClass](ue_ue.NetDriver.md#staticclass)
