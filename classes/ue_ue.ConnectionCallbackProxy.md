[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ConnectionCallbackProxy

# Class: ConnectionCallbackProxy

[ue/ue](../modules/ue_ue.md).ConnectionCallbackProxy

## Hierarchy

- [`OnlineBlueprintCallProxyBase`](ue_ue.OnlineBlueprintCallProxyBase.md)

  ↳ **`ConnectionCallbackProxy`**

## Table of contents

### Constructors

- [constructor](ue_ue.ConnectionCallbackProxy.md#constructor)

### Properties

- [OnFailure](ue_ue.ConnectionCallbackProxy.md#onfailure)
- [OnSuccess](ue_ue.ConnectionCallbackProxy.md#onsuccess)
- [\_\_tid\_ConnectionCallbackProxy\_\_](ue_ue.ConnectionCallbackProxy.md#__tid_connectioncallbackproxy__)
- [\_\_tid\_Object\_\_](ue_ue.ConnectionCallbackProxy.md#__tid_object__)
- [\_\_tid\_OnlineBlueprintCallProxyBase\_\_](ue_ue.ConnectionCallbackProxy.md#__tid_onlineblueprintcallproxybase__)

### Methods

- [Activate](ue_ue.ConnectionCallbackProxy.md#activate)
- [CreateDefaultSubobject](ue_ue.ConnectionCallbackProxy.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ConnectionCallbackProxy.md#executeubergraph)
- [GetClass](ue_ue.ConnectionCallbackProxy.md#getclass)
- [GetName](ue_ue.ConnectionCallbackProxy.md#getname)
- [GetOuter](ue_ue.ConnectionCallbackProxy.md#getouter)
- [GetWorld](ue_ue.ConnectionCallbackProxy.md#getworld)
- [ConnectToService](ue_ue.ConnectionCallbackProxy.md#connecttoservice)
- [Find](ue_ue.ConnectionCallbackProxy.md#find)
- [Load](ue_ue.ConnectionCallbackProxy.md#load)
- [StaticClass](ue_ue.ConnectionCallbackProxy.md#staticclass)

## Constructors

### constructor

• **new ConnectionCallbackProxy**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[constructor](ue_ue.OnlineBlueprintCallProxyBase.md#constructor)

#### Defined in

[ue/ue.d.ts:28589](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28589)

## Properties

### OnFailure

• **OnFailure**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`ErrorCode`: `number`) => `void`\>

#### Defined in

[ue/ue.d.ts:28591](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28591)

___

### OnSuccess

• **OnSuccess**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`ErrorCode`: `number`) => `void`\>

#### Defined in

[ue/ue.d.ts:28590](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28590)

___

### \_\_tid\_ConnectionCallbackProxy\_\_

• **\_\_tid\_ConnectionCallbackProxy\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:28597](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28597)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[__tid_Object__](ue_ue.OnlineBlueprintCallProxyBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_OnlineBlueprintCallProxyBase\_\_

• **\_\_tid\_OnlineBlueprintCallProxyBase\_\_**: `boolean`

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[__tid_OnlineBlueprintCallProxyBase__](ue_ue.OnlineBlueprintCallProxyBase.md#__tid_onlineblueprintcallproxybase__)

#### Defined in

[ue/ue.d.ts:13439](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13439)

## Methods

### Activate

▸ **Activate**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[Activate](ue_ue.OnlineBlueprintCallProxyBase.md#activate)

#### Defined in

[ue/ue.d.ts:13434](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13434)

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

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[ExecuteUbergraph](ue_ue.OnlineBlueprintCallProxyBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[GetClass](ue_ue.OnlineBlueprintCallProxyBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[GetName](ue_ue.OnlineBlueprintCallProxyBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[GetOuter](ue_ue.OnlineBlueprintCallProxyBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[GetWorld](ue_ue.OnlineBlueprintCallProxyBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### ConnectToService

▸ `Static` **ConnectToService**(`WorldContextObject`, `PlayerController`): [`ConnectionCallbackProxy`](ue_ue.ConnectionCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

[`ConnectionCallbackProxy`](ue_ue.ConnectionCallbackProxy.md)

#### Defined in

[ue/ue.d.ts:28592](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28592)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ConnectionCallbackProxy`](ue_ue.ConnectionCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ConnectionCallbackProxy`](ue_ue.ConnectionCallbackProxy.md)

#### Overrides

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[Find](ue_ue.OnlineBlueprintCallProxyBase.md#find)

#### Defined in

[ue/ue.d.ts:28594](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28594)

___

### Load

▸ `Static` **Load**(`InName`): [`ConnectionCallbackProxy`](ue_ue.ConnectionCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ConnectionCallbackProxy`](ue_ue.ConnectionCallbackProxy.md)

#### Overrides

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[Load](ue_ue.OnlineBlueprintCallProxyBase.md#load)

#### Defined in

[ue/ue.d.ts:28595](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28595)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[StaticClass](ue_ue.OnlineBlueprintCallProxyBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:28593](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28593)
