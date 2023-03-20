[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SimulatedClientNetConnection

# Class: SimulatedClientNetConnection

[ue/ue](../modules/ue_ue.md).SimulatedClientNetConnection

## Hierarchy

- [`NetConnection`](ue_ue.NetConnection.md)

  ↳ **`SimulatedClientNetConnection`**

## Table of contents

### Constructors

- [constructor](ue_ue.SimulatedClientNetConnection.md#constructor)

### Properties

- [ChannelsToTick](ue_ue.SimulatedClientNetConnection.md#channelstotick)
- [Children](ue_ue.SimulatedClientNetConnection.md#children)
- [ConfiguredInternetSpeed](ue_ue.SimulatedClientNetConnection.md#configuredinternetspeed)
- [ConfiguredLanSpeed](ue_ue.SimulatedClientNetConnection.md#configuredlanspeed)
- [CurrentNetSpeed](ue_ue.SimulatedClientNetConnection.md#currentnetspeed)
- [Driver](ue_ue.SimulatedClientNetConnection.md#driver)
- [InternalAck](ue_ue.SimulatedClientNetConnection.md#internalack)
- [LastReceiveTime](ue_ue.SimulatedClientNetConnection.md#lastreceivetime)
- [MaxPacket](ue_ue.SimulatedClientNetConnection.md#maxpacket)
- [OpenChannels](ue_ue.SimulatedClientNetConnection.md#openchannels)
- [OwningActor](ue_ue.SimulatedClientNetConnection.md#owningactor)
- [PackageMap](ue_ue.SimulatedClientNetConnection.md#packagemap)
- [PackageMapClass](ue_ue.SimulatedClientNetConnection.md#packagemapclass)
- [PlayerController](ue_ue.SimulatedClientNetConnection.md#playercontroller)
- [PlayerId](ue_ue.SimulatedClientNetConnection.md#playerid)
- [SentTemporaries](ue_ue.SimulatedClientNetConnection.md#senttemporaries)
- [ViewTarget](ue_ue.SimulatedClientNetConnection.md#viewtarget)
- [\_\_tid\_NetConnection\_\_](ue_ue.SimulatedClientNetConnection.md#__tid_netconnection__)
- [\_\_tid\_Object\_\_](ue_ue.SimulatedClientNetConnection.md#__tid_object__)
- [\_\_tid\_Player\_\_](ue_ue.SimulatedClientNetConnection.md#__tid_player__)
- [\_\_tid\_SimulatedClientNetConnection\_\_](ue_ue.SimulatedClientNetConnection.md#__tid_simulatedclientnetconnection__)

### Methods

- [CreateDefaultSubobject](ue_ue.SimulatedClientNetConnection.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SimulatedClientNetConnection.md#executeubergraph)
- [GetClass](ue_ue.SimulatedClientNetConnection.md#getclass)
- [GetName](ue_ue.SimulatedClientNetConnection.md#getname)
- [GetOuter](ue_ue.SimulatedClientNetConnection.md#getouter)
- [GetWorld](ue_ue.SimulatedClientNetConnection.md#getworld)
- [Find](ue_ue.SimulatedClientNetConnection.md#find)
- [Load](ue_ue.SimulatedClientNetConnection.md#load)
- [StaticClass](ue_ue.SimulatedClientNetConnection.md#staticclass)

## Constructors

### constructor

• **new SimulatedClientNetConnection**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[NetConnection](ue_ue.NetConnection.md).[constructor](ue_ue.NetConnection.md#constructor)

#### Defined in

[ue/ue.d.ts:60604](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60604)

## Properties

### ChannelsToTick

• **ChannelsToTick**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Channel`](ue_ue.Channel.md)\>

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[ChannelsToTick](ue_ue.NetConnection.md#channelstotick)

#### Defined in

[ue/ue.d.ts:10449](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10449)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ChildConnection`](ue_ue.ChildConnection.md)\>

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[Children](ue_ue.NetConnection.md#children)

#### Defined in

[ue/ue.d.ts:10437](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10437)

___

### ConfiguredInternetSpeed

• **ConfiguredInternetSpeed**: `number`

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[ConfiguredInternetSpeed](ue_ue.NetConnection.md#configuredinternetspeed)

#### Defined in

[ue/ue.d.ts:6041](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6041)

___

### ConfiguredLanSpeed

• **ConfiguredLanSpeed**: `number`

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[ConfiguredLanSpeed](ue_ue.NetConnection.md#configuredlanspeed)

#### Defined in

[ue/ue.d.ts:6042](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6042)

___

### CurrentNetSpeed

• **CurrentNetSpeed**: `number`

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[CurrentNetSpeed](ue_ue.NetConnection.md#currentnetspeed)

#### Defined in

[ue/ue.d.ts:6040](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6040)

___

### Driver

• **Driver**: [`NetDriver`](ue_ue.NetDriver.md)

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[Driver](ue_ue.NetConnection.md#driver)

#### Defined in

[ue/ue.d.ts:10438](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10438)

___

### InternalAck

• **InternalAck**: `boolean`

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[InternalAck](ue_ue.NetConnection.md#internalack)

#### Defined in

[ue/ue.d.ts:10446](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10446)

___

### LastReceiveTime

• **LastReceiveTime**: `number`

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[LastReceiveTime](ue_ue.NetConnection.md#lastreceivetime)

#### Defined in

[ue/ue.d.ts:10448](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10448)

___

### MaxPacket

• **MaxPacket**: `number`

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[MaxPacket](ue_ue.NetConnection.md#maxpacket)

#### Defined in

[ue/ue.d.ts:10445](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10445)

___

### OpenChannels

• **OpenChannels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Channel`](ue_ue.Channel.md)\>

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[OpenChannels](ue_ue.NetConnection.md#openchannels)

#### Defined in

[ue/ue.d.ts:10441](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10441)

___

### OwningActor

• **OwningActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[OwningActor](ue_ue.NetConnection.md#owningactor)

#### Defined in

[ue/ue.d.ts:10444](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10444)

___

### PackageMap

• **PackageMap**: [`PackageMap`](ue_ue.PackageMap.md)

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[PackageMap](ue_ue.NetConnection.md#packagemap)

#### Defined in

[ue/ue.d.ts:10440](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10440)

___

### PackageMapClass

• **PackageMapClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[PackageMapClass](ue_ue.NetConnection.md#packagemapclass)

#### Defined in

[ue/ue.d.ts:10439](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10439)

___

### PlayerController

• **PlayerController**: [`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[PlayerController](ue_ue.NetConnection.md#playercontroller)

#### Defined in

[ue/ue.d.ts:6039](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6039)

___

### PlayerId

• **PlayerId**: [`UniqueNetIdRepl`](ue_ue.UniqueNetIdRepl.md)

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[PlayerId](ue_ue.NetConnection.md#playerid)

#### Defined in

[ue/ue.d.ts:10447](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10447)

___

### SentTemporaries

• **SentTemporaries**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[SentTemporaries](ue_ue.NetConnection.md#senttemporaries)

#### Defined in

[ue/ue.d.ts:10442](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10442)

___

### ViewTarget

• **ViewTarget**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[ViewTarget](ue_ue.NetConnection.md#viewtarget)

#### Defined in

[ue/ue.d.ts:10443](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10443)

___

### \_\_tid\_NetConnection\_\_

• **\_\_tid\_NetConnection\_\_**: `boolean`

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[__tid_NetConnection__](ue_ue.NetConnection.md#__tid_netconnection__)

#### Defined in

[ue/ue.d.ts:10454](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10454)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[__tid_Object__](ue_ue.NetConnection.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_Player\_\_

• **\_\_tid\_Player\_\_**: `boolean`

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[__tid_Player__](ue_ue.NetConnection.md#__tid_player__)

#### Defined in

[ue/ue.d.ts:6047](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6047)

___

### \_\_tid\_SimulatedClientNetConnection\_\_

• **\_\_tid\_SimulatedClientNetConnection\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:60609](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60609)

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

[NetConnection](ue_ue.NetConnection.md).[ExecuteUbergraph](ue_ue.NetConnection.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[GetClass](ue_ue.NetConnection.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[GetName](ue_ue.NetConnection.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[GetOuter](ue_ue.NetConnection.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[NetConnection](ue_ue.NetConnection.md).[GetWorld](ue_ue.NetConnection.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SimulatedClientNetConnection`](ue_ue.SimulatedClientNetConnection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SimulatedClientNetConnection`](ue_ue.SimulatedClientNetConnection.md)

#### Overrides

[NetConnection](ue_ue.NetConnection.md).[Find](ue_ue.NetConnection.md#find)

#### Defined in

[ue/ue.d.ts:60606](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60606)

___

### Load

▸ `Static` **Load**(`InName`): [`SimulatedClientNetConnection`](ue_ue.SimulatedClientNetConnection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SimulatedClientNetConnection`](ue_ue.SimulatedClientNetConnection.md)

#### Overrides

[NetConnection](ue_ue.NetConnection.md).[Load](ue_ue.NetConnection.md#load)

#### Defined in

[ue/ue.d.ts:60607](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60607)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[NetConnection](ue_ue.NetConnection.md).[StaticClass](ue_ue.NetConnection.md#staticclass)

#### Defined in

[ue/ue.d.ts:60605](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60605)
