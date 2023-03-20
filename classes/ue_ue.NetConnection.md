[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NetConnection

# Class: NetConnection

[ue/ue](../modules/ue_ue.md).NetConnection

## Hierarchy

- [`Player`](ue_ue.Player.md)

  ↳ **`NetConnection`**

  ↳↳ [`ChildConnection`](ue_ue.ChildConnection.md)

  ↳↳ [`DemoNetConnection`](ue_ue.DemoNetConnection.md)

  ↳↳ [`IpConnection`](ue_ue.IpConnection.md)

  ↳↳ [`SimulatedClientNetConnection`](ue_ue.SimulatedClientNetConnection.md)

## Table of contents

### Constructors

- [constructor](ue_ue.NetConnection.md#constructor)

### Properties

- [ChannelsToTick](ue_ue.NetConnection.md#channelstotick)
- [Children](ue_ue.NetConnection.md#children)
- [ConfiguredInternetSpeed](ue_ue.NetConnection.md#configuredinternetspeed)
- [ConfiguredLanSpeed](ue_ue.NetConnection.md#configuredlanspeed)
- [CurrentNetSpeed](ue_ue.NetConnection.md#currentnetspeed)
- [Driver](ue_ue.NetConnection.md#driver)
- [InternalAck](ue_ue.NetConnection.md#internalack)
- [LastReceiveTime](ue_ue.NetConnection.md#lastreceivetime)
- [MaxPacket](ue_ue.NetConnection.md#maxpacket)
- [OpenChannels](ue_ue.NetConnection.md#openchannels)
- [OwningActor](ue_ue.NetConnection.md#owningactor)
- [PackageMap](ue_ue.NetConnection.md#packagemap)
- [PackageMapClass](ue_ue.NetConnection.md#packagemapclass)
- [PlayerController](ue_ue.NetConnection.md#playercontroller)
- [PlayerId](ue_ue.NetConnection.md#playerid)
- [SentTemporaries](ue_ue.NetConnection.md#senttemporaries)
- [ViewTarget](ue_ue.NetConnection.md#viewtarget)
- [\_\_tid\_NetConnection\_\_](ue_ue.NetConnection.md#__tid_netconnection__)
- [\_\_tid\_Object\_\_](ue_ue.NetConnection.md#__tid_object__)
- [\_\_tid\_Player\_\_](ue_ue.NetConnection.md#__tid_player__)

### Methods

- [CreateDefaultSubobject](ue_ue.NetConnection.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.NetConnection.md#executeubergraph)
- [GetClass](ue_ue.NetConnection.md#getclass)
- [GetName](ue_ue.NetConnection.md#getname)
- [GetOuter](ue_ue.NetConnection.md#getouter)
- [GetWorld](ue_ue.NetConnection.md#getworld)
- [Find](ue_ue.NetConnection.md#find)
- [Load](ue_ue.NetConnection.md#load)
- [StaticClass](ue_ue.NetConnection.md#staticclass)

## Constructors

### constructor

• **new NetConnection**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Player](ue_ue.Player.md).[constructor](ue_ue.Player.md#constructor)

## Properties

### ChannelsToTick

• **ChannelsToTick**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Channel`](ue_ue.Channel.md)\>

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ChildConnection`](ue_ue.ChildConnection.md)\>

___

### ConfiguredInternetSpeed

• **ConfiguredInternetSpeed**: `number`

#### Inherited from

[Player](ue_ue.Player.md).[ConfiguredInternetSpeed](ue_ue.Player.md#configuredinternetspeed)

___

### ConfiguredLanSpeed

• **ConfiguredLanSpeed**: `number`

#### Inherited from

[Player](ue_ue.Player.md).[ConfiguredLanSpeed](ue_ue.Player.md#configuredlanspeed)

___

### CurrentNetSpeed

• **CurrentNetSpeed**: `number`

#### Inherited from

[Player](ue_ue.Player.md).[CurrentNetSpeed](ue_ue.Player.md#currentnetspeed)

___

### Driver

• **Driver**: [`NetDriver`](ue_ue.NetDriver.md)

___

### InternalAck

• **InternalAck**: `boolean`

___

### LastReceiveTime

• **LastReceiveTime**: `number`

___

### MaxPacket

• **MaxPacket**: `number`

___

### OpenChannels

• **OpenChannels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Channel`](ue_ue.Channel.md)\>

___

### OwningActor

• **OwningActor**: [`Actor`](ue_ue.Actor.md)

___

### PackageMap

• **PackageMap**: [`PackageMap`](ue_ue.PackageMap.md)

___

### PackageMapClass

• **PackageMapClass**: [`Class`](ue_ue.Class.md)

___

### PlayerController

• **PlayerController**: [`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[Player](ue_ue.Player.md).[PlayerController](ue_ue.Player.md#playercontroller)

___

### PlayerId

• **PlayerId**: [`UniqueNetIdRepl`](ue_ue.UniqueNetIdRepl.md)

___

### SentTemporaries

• **SentTemporaries**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

___

### ViewTarget

• **ViewTarget**: [`Actor`](ue_ue.Actor.md)

___

### \_\_tid\_NetConnection\_\_

• **\_\_tid\_NetConnection\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Player](ue_ue.Player.md).[__tid_Object__](ue_ue.Player.md#__tid_object__)

___

### \_\_tid\_Player\_\_

• **\_\_tid\_Player\_\_**: `boolean`

#### Inherited from

[Player](ue_ue.Player.md).[__tid_Player__](ue_ue.Player.md#__tid_player__)

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

[Player](ue_ue.Player.md).[CreateDefaultSubobject](ue_ue.Player.md#createdefaultsubobject)

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

[Player](ue_ue.Player.md).[ExecuteUbergraph](ue_ue.Player.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Player](ue_ue.Player.md).[GetClass](ue_ue.Player.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Player](ue_ue.Player.md).[GetName](ue_ue.Player.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Player](ue_ue.Player.md).[GetOuter](ue_ue.Player.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Player](ue_ue.Player.md).[GetWorld](ue_ue.Player.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`NetConnection`](ue_ue.NetConnection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`NetConnection`](ue_ue.NetConnection.md)

#### Overrides

[Player](ue_ue.Player.md).[Find](ue_ue.Player.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`NetConnection`](ue_ue.NetConnection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`NetConnection`](ue_ue.NetConnection.md)

#### Overrides

[Player](ue_ue.Player.md).[Load](ue_ue.Player.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Player](ue_ue.Player.md).[StaticClass](ue_ue.Player.md#staticclass)
