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

#### Defined in

[ue/ue.d.ts:10386](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10386)

## Properties

### ActorChannelPool

• **ActorChannelPool**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Channel`](ue_ue.Channel.md)\>

#### Defined in

[ue/ue.d.ts:10416](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10416)

___

### ChannelDefinitionMap

• **ChannelDefinitionMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`ChannelDefinition`](ue_ue.ChannelDefinition.md)\>

#### Defined in

[ue/ue.d.ts:10415](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10415)

___

### ChannelDefinitions

• **ChannelDefinitions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ChannelDefinition`](ue_ue.ChannelDefinition.md)\>

#### Defined in

[ue/ue.d.ts:10414](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10414)

___

### ClientConnections

• **ClientConnections**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NetConnection`](ue_ue.NetConnection.md)\>

#### Defined in

[ue/ue.d.ts:10405](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10405)

___

### ConnectionTimeout

• **ConnectionTimeout**: `number`

#### Defined in

[ue/ue.d.ts:10400](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10400)

___

### InitialConnectTimeout

• **InitialConnectTimeout**: `number`

#### Defined in

[ue/ue.d.ts:10399](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10399)

___

### KeepAliveTime

• **KeepAliveTime**: `number`

#### Defined in

[ue/ue.d.ts:10398](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10398)

___

### MaxClientRate

• **MaxClientRate**: `number`

#### Defined in

[ue/ue.d.ts:10394](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10394)

___

### MaxDownloadSize

• **MaxDownloadSize**: `number`

#### Defined in

[ue/ue.d.ts:10389](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10389)

___

### MaxInternetClientRate

• **MaxInternetClientRate**: `number`

#### Defined in

[ue/ue.d.ts:10393](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10393)

___

### MaxNetTickRate

• **MaxNetTickRate**: `number`

#### Defined in

[ue/ue.d.ts:10392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10392)

___

### NetConnectionClass

• **NetConnectionClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:10409](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10409)

___

### NetConnectionClassName

• **NetConnectionClassName**: `string`

#### Defined in

[ue/ue.d.ts:10387](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10387)

___

### NetDriverName

• **NetDriverName**: `string`

#### Defined in

[ue/ue.d.ts:10413](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10413)

___

### NetServerMaxTickRate

• **NetServerMaxTickRate**: `number`

#### Defined in

[ue/ue.d.ts:10391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10391)

___

### RecentlyDisconnectedTrackingTime

• **RecentlyDisconnectedTrackingTime**: `number`

#### Defined in

[ue/ue.d.ts:10406](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10406)

___

### RelevantTimeout

• **RelevantTimeout**: `number`

#### Defined in

[ue/ue.d.ts:10397](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10397)

___

### RemoteRoleProperty

• **RemoteRoleProperty**: [`Property`](ue_ue.Property.md)

#### Defined in

[ue/ue.d.ts:10412](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10412)

___

### ReplicationDriver

• **ReplicationDriver**: [`ReplicationDriver`](ue_ue.ReplicationDriver.md)

#### Defined in

[ue/ue.d.ts:10418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10418)

___

### ReplicationDriverClass

• **ReplicationDriverClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:10410](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10410)

___

### ReplicationDriverClassName

• **ReplicationDriverClassName**: `string`

#### Defined in

[ue/ue.d.ts:10388](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10388)

___

### RoleProperty

• **RoleProperty**: [`Property`](ue_ue.Property.md)

#### Defined in

[ue/ue.d.ts:10411](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10411)

___

### ServerConnection

• **ServerConnection**: [`NetConnection`](ue_ue.NetConnection.md)

#### Defined in

[ue/ue.d.ts:10404](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10404)

___

### ServerTravelPause

• **ServerTravelPause**: `number`

#### Defined in

[ue/ue.d.ts:10395](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10395)

___

### SpawnPrioritySeconds

• **SpawnPrioritySeconds**: `number`

#### Defined in

[ue/ue.d.ts:10396](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10396)

___

### Time

• **Time**: `number`

#### Defined in

[ue/ue.d.ts:10417](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10417)

___

### TimeoutMultiplierForUnoptimizedBuilds

• **TimeoutMultiplierForUnoptimizedBuilds**: `number`

#### Defined in

[ue/ue.d.ts:10401](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10401)

___

### World

• **World**: [`World`](ue_ue.World.md)

#### Defined in

[ue/ue.d.ts:10407](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10407)

___

### WorldPackage

• **WorldPackage**: [`Package`](ue_ue.Package.md)

#### Defined in

[ue/ue.d.ts:10408](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10408)

___

### \_\_tid\_NetDriver\_\_

• **\_\_tid\_NetDriver\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:10423](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10423)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bClampListenServerTickRate

• **bClampListenServerTickRate**: `boolean`

#### Defined in

[ue/ue.d.ts:10390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10390)

___

### bNeverApplyNetworkEmulationSettings

• **bNeverApplyNetworkEmulationSettings**: `boolean`

#### Defined in

[ue/ue.d.ts:10403](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10403)

___

### bNoTimeouts

• **bNoTimeouts**: `boolean`

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:10420](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10420)

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

#### Defined in

[ue/ue.d.ts:10421](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10421)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:10419](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10419)
