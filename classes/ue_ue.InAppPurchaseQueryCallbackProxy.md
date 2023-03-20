[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InAppPurchaseQueryCallbackProxy

# Class: InAppPurchaseQueryCallbackProxy

[ue/ue](../modules/ue_ue.md).InAppPurchaseQueryCallbackProxy

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`InAppPurchaseQueryCallbackProxy`**

## Table of contents

### Constructors

- [constructor](ue_ue.InAppPurchaseQueryCallbackProxy.md#constructor)

### Properties

- [OnFailure](ue_ue.InAppPurchaseQueryCallbackProxy.md#onfailure)
- [OnSuccess](ue_ue.InAppPurchaseQueryCallbackProxy.md#onsuccess)
- [\_\_tid\_InAppPurchaseQueryCallbackProxy\_\_](ue_ue.InAppPurchaseQueryCallbackProxy.md#__tid_inapppurchasequerycallbackproxy__)
- [\_\_tid\_Object\_\_](ue_ue.InAppPurchaseQueryCallbackProxy.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.InAppPurchaseQueryCallbackProxy.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InAppPurchaseQueryCallbackProxy.md#executeubergraph)
- [GetClass](ue_ue.InAppPurchaseQueryCallbackProxy.md#getclass)
- [GetName](ue_ue.InAppPurchaseQueryCallbackProxy.md#getname)
- [GetOuter](ue_ue.InAppPurchaseQueryCallbackProxy.md#getouter)
- [GetWorld](ue_ue.InAppPurchaseQueryCallbackProxy.md#getworld)
- [CreateProxyObjectForInAppPurchaseQuery](ue_ue.InAppPurchaseQueryCallbackProxy.md#createproxyobjectforinapppurchasequery)
- [Find](ue_ue.InAppPurchaseQueryCallbackProxy.md#find)
- [Load](ue_ue.InAppPurchaseQueryCallbackProxy.md#load)
- [StaticClass](ue_ue.InAppPurchaseQueryCallbackProxy.md#staticclass)

## Constructors

### constructor

• **new InAppPurchaseQueryCallbackProxy**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:39042](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39042)

## Properties

### OnFailure

• **OnFailure**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`InAppPurchaseInformation`: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InAppPurchaseProductInfo`](ue_ue.InAppPurchaseProductInfo.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:39044](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39044)

___

### OnSuccess

• **OnSuccess**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`InAppPurchaseInformation`: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InAppPurchaseProductInfo`](ue_ue.InAppPurchaseProductInfo.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:39043](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39043)

___

### \_\_tid\_InAppPurchaseQueryCallbackProxy\_\_

• **\_\_tid\_InAppPurchaseQueryCallbackProxy\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:39050](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39050)

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

### CreateProxyObjectForInAppPurchaseQuery

▸ `Static` **CreateProxyObjectForInAppPurchaseQuery**(`PlayerController`, `ProductIdentifiers`): [`InAppPurchaseQueryCallbackProxy`](ue_ue.InAppPurchaseQueryCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |
| `ProductIdentifiers` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

[`InAppPurchaseQueryCallbackProxy`](ue_ue.InAppPurchaseQueryCallbackProxy.md)

#### Defined in

[ue/ue.d.ts:39045](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39045)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InAppPurchaseQueryCallbackProxy`](ue_ue.InAppPurchaseQueryCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InAppPurchaseQueryCallbackProxy`](ue_ue.InAppPurchaseQueryCallbackProxy.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:39047](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39047)

___

### Load

▸ `Static` **Load**(`InName`): [`InAppPurchaseQueryCallbackProxy`](ue_ue.InAppPurchaseQueryCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InAppPurchaseQueryCallbackProxy`](ue_ue.InAppPurchaseQueryCallbackProxy.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:39048](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39048)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:39046](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39046)
