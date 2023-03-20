[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LeaderboardFlushCallbackProxy

# Class: LeaderboardFlushCallbackProxy

[ue/ue](../modules/ue_ue.md).LeaderboardFlushCallbackProxy

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`LeaderboardFlushCallbackProxy`**

## Table of contents

### Constructors

- [constructor](ue_ue.LeaderboardFlushCallbackProxy.md#constructor)

### Properties

- [OnFailure](ue_ue.LeaderboardFlushCallbackProxy.md#onfailure)
- [OnSuccess](ue_ue.LeaderboardFlushCallbackProxy.md#onsuccess)
- [\_\_tid\_LeaderboardFlushCallbackProxy\_\_](ue_ue.LeaderboardFlushCallbackProxy.md#__tid_leaderboardflushcallbackproxy__)
- [\_\_tid\_Object\_\_](ue_ue.LeaderboardFlushCallbackProxy.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.LeaderboardFlushCallbackProxy.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LeaderboardFlushCallbackProxy.md#executeubergraph)
- [GetClass](ue_ue.LeaderboardFlushCallbackProxy.md#getclass)
- [GetName](ue_ue.LeaderboardFlushCallbackProxy.md#getname)
- [GetOuter](ue_ue.LeaderboardFlushCallbackProxy.md#getouter)
- [GetWorld](ue_ue.LeaderboardFlushCallbackProxy.md#getworld)
- [CreateProxyObjectForFlush](ue_ue.LeaderboardFlushCallbackProxy.md#createproxyobjectforflush)
- [Find](ue_ue.LeaderboardFlushCallbackProxy.md#find)
- [Load](ue_ue.LeaderboardFlushCallbackProxy.md#load)
- [StaticClass](ue_ue.LeaderboardFlushCallbackProxy.md#staticclass)

## Constructors

### constructor

• **new LeaderboardFlushCallbackProxy**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:44717](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44717)

## Properties

### OnFailure

• **OnFailure**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SessionName`: `string`) => `void`\>

#### Defined in

[ue/ue.d.ts:44719](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44719)

___

### OnSuccess

• **OnSuccess**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SessionName`: `string`) => `void`\>

#### Defined in

[ue/ue.d.ts:44718](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44718)

___

### \_\_tid\_LeaderboardFlushCallbackProxy\_\_

• **\_\_tid\_LeaderboardFlushCallbackProxy\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:44725](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44725)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### CreateProxyObjectForFlush

▸ `Static` **CreateProxyObjectForFlush**(`PlayerController`, `SessionName`): [`LeaderboardFlushCallbackProxy`](ue_ue.LeaderboardFlushCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |
| `SessionName` | `string` |

#### Returns

[`LeaderboardFlushCallbackProxy`](ue_ue.LeaderboardFlushCallbackProxy.md)

#### Defined in

[ue/ue.d.ts:44720](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44720)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LeaderboardFlushCallbackProxy`](ue_ue.LeaderboardFlushCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LeaderboardFlushCallbackProxy`](ue_ue.LeaderboardFlushCallbackProxy.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:44722](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44722)

___

### Load

▸ `Static` **Load**(`InName`): [`LeaderboardFlushCallbackProxy`](ue_ue.LeaderboardFlushCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LeaderboardFlushCallbackProxy`](ue_ue.LeaderboardFlushCallbackProxy.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:44723](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44723)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:44721](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44721)
