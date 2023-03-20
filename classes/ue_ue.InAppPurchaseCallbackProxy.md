[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InAppPurchaseCallbackProxy

# Class: InAppPurchaseCallbackProxy

[ue/ue](../modules/ue_ue.md).InAppPurchaseCallbackProxy

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`InAppPurchaseCallbackProxy`**

## Table of contents

### Constructors

- [constructor](ue_ue.InAppPurchaseCallbackProxy.md#constructor)

### Properties

- [OnFailure](ue_ue.InAppPurchaseCallbackProxy.md#onfailure)
- [OnSuccess](ue_ue.InAppPurchaseCallbackProxy.md#onsuccess)
- [\_\_tid\_InAppPurchaseCallbackProxy\_\_](ue_ue.InAppPurchaseCallbackProxy.md#__tid_inapppurchasecallbackproxy__)
- [\_\_tid\_Object\_\_](ue_ue.InAppPurchaseCallbackProxy.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.InAppPurchaseCallbackProxy.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InAppPurchaseCallbackProxy.md#executeubergraph)
- [GetClass](ue_ue.InAppPurchaseCallbackProxy.md#getclass)
- [GetName](ue_ue.InAppPurchaseCallbackProxy.md#getname)
- [GetOuter](ue_ue.InAppPurchaseCallbackProxy.md#getouter)
- [GetWorld](ue_ue.InAppPurchaseCallbackProxy.md#getworld)
- [CreateProxyObjectForInAppPurchase](ue_ue.InAppPurchaseCallbackProxy.md#createproxyobjectforinapppurchase)
- [Find](ue_ue.InAppPurchaseCallbackProxy.md#find)
- [Load](ue_ue.InAppPurchaseCallbackProxy.md#load)
- [StaticClass](ue_ue.InAppPurchaseCallbackProxy.md#staticclass)

## Constructors

### constructor

• **new InAppPurchaseCallbackProxy**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:38976](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38976)

## Properties

### OnFailure

• **OnFailure**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`CompletionStatus`: [`EInAppPurchaseState`](../enums/ue_ue.EInAppPurchaseState.md), `InAppPurchaseInformation`: [`InAppPurchaseProductInfo`](ue_ue.InAppPurchaseProductInfo.md)) => `void`\>

#### Defined in

[ue/ue.d.ts:38978](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38978)

___

### OnSuccess

• **OnSuccess**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`CompletionStatus`: [`EInAppPurchaseState`](../enums/ue_ue.EInAppPurchaseState.md), `InAppPurchaseInformation`: [`InAppPurchaseProductInfo`](ue_ue.InAppPurchaseProductInfo.md)) => `void`\>

#### Defined in

[ue/ue.d.ts:38977](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38977)

___

### \_\_tid\_InAppPurchaseCallbackProxy\_\_

• **\_\_tid\_InAppPurchaseCallbackProxy\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:38984](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38984)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

### CreateProxyObjectForInAppPurchase

▸ `Static` **CreateProxyObjectForInAppPurchase**(`PlayerController`, `ProductRequest`): [`InAppPurchaseCallbackProxy`](ue_ue.InAppPurchaseCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |
| `ProductRequest` | [`InAppPurchaseProductRequest`](ue_ue.InAppPurchaseProductRequest.md) |

#### Returns

[`InAppPurchaseCallbackProxy`](ue_ue.InAppPurchaseCallbackProxy.md)

#### Defined in

[ue/ue.d.ts:38979](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38979)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InAppPurchaseCallbackProxy`](ue_ue.InAppPurchaseCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InAppPurchaseCallbackProxy`](ue_ue.InAppPurchaseCallbackProxy.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:38981](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38981)

___

### Load

▸ `Static` **Load**(`InName`): [`InAppPurchaseCallbackProxy`](ue_ue.InAppPurchaseCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InAppPurchaseCallbackProxy`](ue_ue.InAppPurchaseCallbackProxy.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:38982](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38982)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:38980](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38980)
