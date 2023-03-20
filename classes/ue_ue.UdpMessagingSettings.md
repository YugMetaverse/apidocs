[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UdpMessagingSettings

# Class: UdpMessagingSettings

[ue/ue](../modules/ue_ue.md).UdpMessagingSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`UdpMessagingSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.UdpMessagingSettings.md#constructor)

### Properties

- [EnableTransport](ue_ue.UdpMessagingSettings.md#enabletransport)
- [EnableTunnel](ue_ue.UdpMessagingSettings.md#enabletunnel)
- [MulticastEndpoint](ue_ue.UdpMessagingSettings.md#multicastendpoint)
- [MulticastTimeToLive](ue_ue.UdpMessagingSettings.md#multicasttimetolive)
- [RemoteTunnelEndpoints](ue_ue.UdpMessagingSettings.md#remotetunnelendpoints)
- [StaticEndpoints](ue_ue.UdpMessagingSettings.md#staticendpoints)
- [TunnelMulticastEndpoint](ue_ue.UdpMessagingSettings.md#tunnelmulticastendpoint)
- [TunnelUnicastEndpoint](ue_ue.UdpMessagingSettings.md#tunnelunicastendpoint)
- [UnicastEndpoint](ue_ue.UdpMessagingSettings.md#unicastendpoint)
- [\_\_tid\_Object\_\_](ue_ue.UdpMessagingSettings.md#__tid_object__)
- [\_\_tid\_UdpMessagingSettings\_\_](ue_ue.UdpMessagingSettings.md#__tid_udpmessagingsettings__)
- [bAutoRepair](ue_ue.UdpMessagingSettings.md#bautorepair)

### Methods

- [CreateDefaultSubobject](ue_ue.UdpMessagingSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UdpMessagingSettings.md#executeubergraph)
- [GetClass](ue_ue.UdpMessagingSettings.md#getclass)
- [GetName](ue_ue.UdpMessagingSettings.md#getname)
- [GetOuter](ue_ue.UdpMessagingSettings.md#getouter)
- [GetWorld](ue_ue.UdpMessagingSettings.md#getworld)
- [Find](ue_ue.UdpMessagingSettings.md#find)
- [Load](ue_ue.UdpMessagingSettings.md#load)
- [StaticClass](ue_ue.UdpMessagingSettings.md#staticclass)

## Constructors

### constructor

• **new UdpMessagingSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### EnableTransport

• **EnableTransport**: `boolean`

___

### EnableTunnel

• **EnableTunnel**: `boolean`

___

### MulticastEndpoint

• **MulticastEndpoint**: `string`

___

### MulticastTimeToLive

• **MulticastTimeToLive**: `number`

___

### RemoteTunnelEndpoints

• **RemoteTunnelEndpoints**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### StaticEndpoints

• **StaticEndpoints**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### TunnelMulticastEndpoint

• **TunnelMulticastEndpoint**: `string`

___

### TunnelUnicastEndpoint

• **TunnelUnicastEndpoint**: `string`

___

### UnicastEndpoint

• **UnicastEndpoint**: `string`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_UdpMessagingSettings\_\_

• **\_\_tid\_UdpMessagingSettings\_\_**: `boolean`

___

### bAutoRepair

• **bAutoRepair**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UdpMessagingSettings`](ue_ue.UdpMessagingSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UdpMessagingSettings`](ue_ue.UdpMessagingSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`UdpMessagingSettings`](ue_ue.UdpMessagingSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UdpMessagingSettings`](ue_ue.UdpMessagingSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
