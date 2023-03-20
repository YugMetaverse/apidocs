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

#### Defined in

[ue/ue.d.ts:10436](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10436)

## Properties

### ChannelsToTick

• **ChannelsToTick**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Channel`](ue_ue.Channel.md)\>

#### Defined in

[ue/ue.d.ts:10449](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10449)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ChildConnection`](ue_ue.ChildConnection.md)\>

#### Defined in

[ue/ue.d.ts:10437](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10437)

___

### ConfiguredInternetSpeed

• **ConfiguredInternetSpeed**: `number`

#### Inherited from

[Player](ue_ue.Player.md).[ConfiguredInternetSpeed](ue_ue.Player.md#configuredinternetspeed)

#### Defined in

[ue/ue.d.ts:6041](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6041)

___

### ConfiguredLanSpeed

• **ConfiguredLanSpeed**: `number`

#### Inherited from

[Player](ue_ue.Player.md).[ConfiguredLanSpeed](ue_ue.Player.md#configuredlanspeed)

#### Defined in

[ue/ue.d.ts:6042](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6042)

___

### CurrentNetSpeed

• **CurrentNetSpeed**: `number`

#### Inherited from

[Player](ue_ue.Player.md).[CurrentNetSpeed](ue_ue.Player.md#currentnetspeed)

#### Defined in

[ue/ue.d.ts:6040](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6040)

___

### Driver

• **Driver**: [`NetDriver`](ue_ue.NetDriver.md)

#### Defined in

[ue/ue.d.ts:10438](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10438)

___

### InternalAck

• **InternalAck**: `boolean`

#### Defined in

[ue/ue.d.ts:10446](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10446)

___

### LastReceiveTime

• **LastReceiveTime**: `number`

#### Defined in

[ue/ue.d.ts:10448](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10448)

___

### MaxPacket

• **MaxPacket**: `number`

#### Defined in

[ue/ue.d.ts:10445](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10445)

___

### OpenChannels

• **OpenChannels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Channel`](ue_ue.Channel.md)\>

#### Defined in

[ue/ue.d.ts:10441](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10441)

___

### OwningActor

• **OwningActor**: [`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:10444](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10444)

___

### PackageMap

• **PackageMap**: [`PackageMap`](ue_ue.PackageMap.md)

#### Defined in

[ue/ue.d.ts:10440](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10440)

___

### PackageMapClass

• **PackageMapClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:10439](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10439)

___

### PlayerController

• **PlayerController**: [`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[Player](ue_ue.Player.md).[PlayerController](ue_ue.Player.md#playercontroller)

#### Defined in

[ue/ue.d.ts:6039](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6039)

___

### PlayerId

• **PlayerId**: [`UniqueNetIdRepl`](ue_ue.UniqueNetIdRepl.md)

#### Defined in

[ue/ue.d.ts:10447](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10447)

___

### SentTemporaries

• **SentTemporaries**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Defined in

[ue/ue.d.ts:10442](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10442)

___

### ViewTarget

• **ViewTarget**: [`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:10443](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10443)

___

### \_\_tid\_NetConnection\_\_

• **\_\_tid\_NetConnection\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:10454](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10454)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Player](ue_ue.Player.md).[__tid_Object__](ue_ue.Player.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_Player\_\_

• **\_\_tid\_Player\_\_**: `boolean`

#### Inherited from

[Player](ue_ue.Player.md).[__tid_Player__](ue_ue.Player.md#__tid_player__)

#### Defined in

[ue/ue.d.ts:6047](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6047)

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

[Player](ue_ue.Player.md).[ExecuteUbergraph](ue_ue.Player.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Player](ue_ue.Player.md).[GetClass](ue_ue.Player.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Player](ue_ue.Player.md).[GetName](ue_ue.Player.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Player](ue_ue.Player.md).[GetOuter](ue_ue.Player.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Player](ue_ue.Player.md).[GetWorld](ue_ue.Player.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:10451](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10451)

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

#### Defined in

[ue/ue.d.ts:10452](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10452)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Player](ue_ue.Player.md).[StaticClass](ue_ue.Player.md#staticclass)

#### Defined in

[ue/ue.d.ts:10450](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10450)
