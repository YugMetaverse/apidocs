[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / OnlineSessionClient

# Class: OnlineSessionClient

[ue/ue](../modules/ue_ue.md).OnlineSessionClient

## Hierarchy

- [`OnlineSession`](ue_ue.OnlineSession.md)

  ↳ **`OnlineSessionClient`**

## Table of contents

### Constructors

- [constructor](ue_ue.OnlineSessionClient.md#constructor)

### Properties

- [\_\_tid\_Object\_\_](ue_ue.OnlineSessionClient.md#__tid_object__)
- [\_\_tid\_OnlineSessionClient\_\_](ue_ue.OnlineSessionClient.md#__tid_onlinesessionclient__)
- [\_\_tid\_OnlineSession\_\_](ue_ue.OnlineSessionClient.md#__tid_onlinesession__)
- [bHandlingDisconnect](ue_ue.OnlineSessionClient.md#bhandlingdisconnect)
- [bIsFromInvite](ue_ue.OnlineSessionClient.md#bisfrominvite)

### Methods

- [CreateDefaultSubobject](ue_ue.OnlineSessionClient.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.OnlineSessionClient.md#executeubergraph)
- [GetClass](ue_ue.OnlineSessionClient.md#getclass)
- [GetName](ue_ue.OnlineSessionClient.md#getname)
- [GetOuter](ue_ue.OnlineSessionClient.md#getouter)
- [GetWorld](ue_ue.OnlineSessionClient.md#getworld)
- [Find](ue_ue.OnlineSessionClient.md#find)
- [Load](ue_ue.OnlineSessionClient.md#load)
- [StaticClass](ue_ue.OnlineSessionClient.md#staticclass)

## Constructors

### constructor

• **new OnlineSessionClient**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[OnlineSession](ue_ue.OnlineSession.md).[constructor](ue_ue.OnlineSession.md#constructor)

## Properties

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[OnlineSession](ue_ue.OnlineSession.md).[__tid_Object__](ue_ue.OnlineSession.md#__tid_object__)

___

### \_\_tid\_OnlineSessionClient\_\_

• **\_\_tid\_OnlineSessionClient\_\_**: `boolean`

___

### \_\_tid\_OnlineSession\_\_

• **\_\_tid\_OnlineSession\_\_**: `boolean`

#### Inherited from

[OnlineSession](ue_ue.OnlineSession.md).[__tid_OnlineSession__](ue_ue.OnlineSession.md#__tid_onlinesession__)

___

### bHandlingDisconnect

• **bHandlingDisconnect**: `boolean`

___

### bIsFromInvite

• **bIsFromInvite**: `boolean`

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

[OnlineSession](ue_ue.OnlineSession.md).[CreateDefaultSubobject](ue_ue.OnlineSession.md#createdefaultsubobject)

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

[OnlineSession](ue_ue.OnlineSession.md).[ExecuteUbergraph](ue_ue.OnlineSession.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[OnlineSession](ue_ue.OnlineSession.md).[GetClass](ue_ue.OnlineSession.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[OnlineSession](ue_ue.OnlineSession.md).[GetName](ue_ue.OnlineSession.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[OnlineSession](ue_ue.OnlineSession.md).[GetOuter](ue_ue.OnlineSession.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[OnlineSession](ue_ue.OnlineSession.md).[GetWorld](ue_ue.OnlineSession.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`OnlineSessionClient`](ue_ue.OnlineSessionClient.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`OnlineSessionClient`](ue_ue.OnlineSessionClient.md)

#### Overrides

[OnlineSession](ue_ue.OnlineSession.md).[Find](ue_ue.OnlineSession.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`OnlineSessionClient`](ue_ue.OnlineSessionClient.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`OnlineSessionClient`](ue_ue.OnlineSessionClient.md)

#### Overrides

[OnlineSession](ue_ue.OnlineSession.md).[Load](ue_ue.OnlineSession.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[OnlineSession](ue_ue.OnlineSession.md).[StaticClass](ue_ue.OnlineSession.md#staticclass)
