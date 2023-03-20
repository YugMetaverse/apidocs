[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LeaderboardQueryCallbackProxy

# Class: LeaderboardQueryCallbackProxy

[ue/ue](../modules/ue_ue.md).LeaderboardQueryCallbackProxy

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`LeaderboardQueryCallbackProxy`**

## Table of contents

### Constructors

- [constructor](ue_ue.LeaderboardQueryCallbackProxy.md#constructor)

### Properties

- [OnFailure](ue_ue.LeaderboardQueryCallbackProxy.md#onfailure)
- [OnSuccess](ue_ue.LeaderboardQueryCallbackProxy.md#onsuccess)
- [\_\_tid\_LeaderboardQueryCallbackProxy\_\_](ue_ue.LeaderboardQueryCallbackProxy.md#__tid_leaderboardquerycallbackproxy__)
- [\_\_tid\_Object\_\_](ue_ue.LeaderboardQueryCallbackProxy.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.LeaderboardQueryCallbackProxy.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LeaderboardQueryCallbackProxy.md#executeubergraph)
- [GetClass](ue_ue.LeaderboardQueryCallbackProxy.md#getclass)
- [GetName](ue_ue.LeaderboardQueryCallbackProxy.md#getname)
- [GetOuter](ue_ue.LeaderboardQueryCallbackProxy.md#getouter)
- [GetWorld](ue_ue.LeaderboardQueryCallbackProxy.md#getworld)
- [CreateProxyObjectForIntQuery](ue_ue.LeaderboardQueryCallbackProxy.md#createproxyobjectforintquery)
- [Find](ue_ue.LeaderboardQueryCallbackProxy.md#find)
- [Load](ue_ue.LeaderboardQueryCallbackProxy.md#load)
- [StaticClass](ue_ue.LeaderboardQueryCallbackProxy.md#staticclass)

## Constructors

### constructor

• **new LeaderboardQueryCallbackProxy**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### OnFailure

• **OnFailure**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`LeaderboardValue`: `number`) => `void`\>

___

### OnSuccess

• **OnSuccess**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`LeaderboardValue`: `number`) => `void`\>

___

### \_\_tid\_LeaderboardQueryCallbackProxy\_\_

• **\_\_tid\_LeaderboardQueryCallbackProxy\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

### CreateProxyObjectForIntQuery

▸ `Static` **CreateProxyObjectForIntQuery**(`PlayerController`, `StatName`): [`LeaderboardQueryCallbackProxy`](ue_ue.LeaderboardQueryCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |
| `StatName` | `string` |

#### Returns

[`LeaderboardQueryCallbackProxy`](ue_ue.LeaderboardQueryCallbackProxy.md)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LeaderboardQueryCallbackProxy`](ue_ue.LeaderboardQueryCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LeaderboardQueryCallbackProxy`](ue_ue.LeaderboardQueryCallbackProxy.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LeaderboardQueryCallbackProxy`](ue_ue.LeaderboardQueryCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LeaderboardQueryCallbackProxy`](ue_ue.LeaderboardQueryCallbackProxy.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
