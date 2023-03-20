[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FindSessionsCallbackProxy

# Class: FindSessionsCallbackProxy

[ue/ue](../modules/ue_ue.md).FindSessionsCallbackProxy

## Hierarchy

- [`OnlineBlueprintCallProxyBase`](ue_ue.OnlineBlueprintCallProxyBase.md)

  ↳ **`FindSessionsCallbackProxy`**

## Table of contents

### Constructors

- [constructor](ue_ue.FindSessionsCallbackProxy.md#constructor)

### Properties

- [OnFailure](ue_ue.FindSessionsCallbackProxy.md#onfailure)
- [OnSuccess](ue_ue.FindSessionsCallbackProxy.md#onsuccess)
- [\_\_tid\_FindSessionsCallbackProxy\_\_](ue_ue.FindSessionsCallbackProxy.md#__tid_findsessionscallbackproxy__)
- [\_\_tid\_Object\_\_](ue_ue.FindSessionsCallbackProxy.md#__tid_object__)
- [\_\_tid\_OnlineBlueprintCallProxyBase\_\_](ue_ue.FindSessionsCallbackProxy.md#__tid_onlineblueprintcallproxybase__)

### Methods

- [Activate](ue_ue.FindSessionsCallbackProxy.md#activate)
- [CreateDefaultSubobject](ue_ue.FindSessionsCallbackProxy.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.FindSessionsCallbackProxy.md#executeubergraph)
- [GetClass](ue_ue.FindSessionsCallbackProxy.md#getclass)
- [GetName](ue_ue.FindSessionsCallbackProxy.md#getname)
- [GetOuter](ue_ue.FindSessionsCallbackProxy.md#getouter)
- [GetWorld](ue_ue.FindSessionsCallbackProxy.md#getworld)
- [Find](ue_ue.FindSessionsCallbackProxy.md#find)
- [FindSessions](ue_ue.FindSessionsCallbackProxy.md#findsessions)
- [GetCurrentPlayers](ue_ue.FindSessionsCallbackProxy.md#getcurrentplayers)
- [GetMaxPlayers](ue_ue.FindSessionsCallbackProxy.md#getmaxplayers)
- [GetPingInMs](ue_ue.FindSessionsCallbackProxy.md#getpinginms)
- [GetServerName](ue_ue.FindSessionsCallbackProxy.md#getservername)
- [Load](ue_ue.FindSessionsCallbackProxy.md#load)
- [StaticClass](ue_ue.FindSessionsCallbackProxy.md#staticclass)

## Constructors

### constructor

• **new FindSessionsCallbackProxy**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[constructor](ue_ue.OnlineBlueprintCallProxyBase.md#constructor)

#### Defined in

[ue/ue.d.ts:35577](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35577)

## Properties

### OnFailure

• **OnFailure**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Results`: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlueprintSessionResult`](ue_ue.BlueprintSessionResult.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:35579](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35579)

___

### OnSuccess

• **OnSuccess**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Results`: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlueprintSessionResult`](ue_ue.BlueprintSessionResult.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:35578](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35578)

___

### \_\_tid\_FindSessionsCallbackProxy\_\_

• **\_\_tid\_FindSessionsCallbackProxy\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:35589](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35589)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[__tid_Object__](ue_ue.OnlineBlueprintCallProxyBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_OnlineBlueprintCallProxyBase\_\_

• **\_\_tid\_OnlineBlueprintCallProxyBase\_\_**: `boolean`

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[__tid_OnlineBlueprintCallProxyBase__](ue_ue.OnlineBlueprintCallProxyBase.md#__tid_onlineblueprintcallproxybase__)

#### Defined in

[ue/ue.d.ts:13439](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13439)

## Methods

### Activate

▸ **Activate**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[Activate](ue_ue.OnlineBlueprintCallProxyBase.md#activate)

#### Defined in

[ue/ue.d.ts:13434](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13434)

___

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

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[CreateDefaultSubobject](ue_ue.OnlineBlueprintCallProxyBase.md#createdefaultsubobject)

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

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[ExecuteUbergraph](ue_ue.OnlineBlueprintCallProxyBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[GetClass](ue_ue.OnlineBlueprintCallProxyBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[GetName](ue_ue.OnlineBlueprintCallProxyBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[GetOuter](ue_ue.OnlineBlueprintCallProxyBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[GetWorld](ue_ue.OnlineBlueprintCallProxyBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FindSessionsCallbackProxy`](ue_ue.FindSessionsCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FindSessionsCallbackProxy`](ue_ue.FindSessionsCallbackProxy.md)

#### Overrides

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[Find](ue_ue.OnlineBlueprintCallProxyBase.md#find)

#### Defined in

[ue/ue.d.ts:35586](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35586)

___

### FindSessions

▸ `Static` **FindSessions**(`WorldContextObject`, `PlayerController`, `MaxResults`, `bUseLAN`): [`FindSessionsCallbackProxy`](ue_ue.FindSessionsCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |
| `MaxResults` | `number` |
| `bUseLAN` | `boolean` |

#### Returns

[`FindSessionsCallbackProxy`](ue_ue.FindSessionsCallbackProxy.md)

#### Defined in

[ue/ue.d.ts:35580](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35580)

___

### GetCurrentPlayers

▸ `Static` **GetCurrentPlayers**(`Result`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Result` | [`BlueprintSessionResult`](ue_ue.BlueprintSessionResult.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:35581](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35581)

___

### GetMaxPlayers

▸ `Static` **GetMaxPlayers**(`Result`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Result` | [`BlueprintSessionResult`](ue_ue.BlueprintSessionResult.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:35582](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35582)

___

### GetPingInMs

▸ `Static` **GetPingInMs**(`Result`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Result` | [`BlueprintSessionResult`](ue_ue.BlueprintSessionResult.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:35583](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35583)

___

### GetServerName

▸ `Static` **GetServerName**(`Result`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Result` | [`BlueprintSessionResult`](ue_ue.BlueprintSessionResult.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:35584](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35584)

___

### Load

▸ `Static` **Load**(`InName`): [`FindSessionsCallbackProxy`](ue_ue.FindSessionsCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FindSessionsCallbackProxy`](ue_ue.FindSessionsCallbackProxy.md)

#### Overrides

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[Load](ue_ue.OnlineBlueprintCallProxyBase.md#load)

#### Defined in

[ue/ue.d.ts:35587](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35587)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[StaticClass](ue_ue.OnlineBlueprintCallProxyBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:35585](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35585)
