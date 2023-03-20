[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InAppPurchaseRestoreCallbackProxy

# Class: InAppPurchaseRestoreCallbackProxy

[ue/ue](../modules/ue_ue.md).InAppPurchaseRestoreCallbackProxy

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`InAppPurchaseRestoreCallbackProxy`**

## Table of contents

### Constructors

- [constructor](ue_ue.InAppPurchaseRestoreCallbackProxy.md#constructor)

### Properties

- [OnFailure](ue_ue.InAppPurchaseRestoreCallbackProxy.md#onfailure)
- [OnSuccess](ue_ue.InAppPurchaseRestoreCallbackProxy.md#onsuccess)
- [\_\_tid\_InAppPurchaseRestoreCallbackProxy\_\_](ue_ue.InAppPurchaseRestoreCallbackProxy.md#__tid_inapppurchaserestorecallbackproxy__)
- [\_\_tid\_Object\_\_](ue_ue.InAppPurchaseRestoreCallbackProxy.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.InAppPurchaseRestoreCallbackProxy.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InAppPurchaseRestoreCallbackProxy.md#executeubergraph)
- [GetClass](ue_ue.InAppPurchaseRestoreCallbackProxy.md#getclass)
- [GetName](ue_ue.InAppPurchaseRestoreCallbackProxy.md#getname)
- [GetOuter](ue_ue.InAppPurchaseRestoreCallbackProxy.md#getouter)
- [GetWorld](ue_ue.InAppPurchaseRestoreCallbackProxy.md#getworld)
- [CreateProxyObjectForInAppPurchaseRestore](ue_ue.InAppPurchaseRestoreCallbackProxy.md#createproxyobjectforinapppurchaserestore)
- [Find](ue_ue.InAppPurchaseRestoreCallbackProxy.md#find)
- [Load](ue_ue.InAppPurchaseRestoreCallbackProxy.md#load)
- [StaticClass](ue_ue.InAppPurchaseRestoreCallbackProxy.md#staticclass)

## Constructors

### constructor

• **new InAppPurchaseRestoreCallbackProxy**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:39068](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39068)

## Properties

### OnFailure

• **OnFailure**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`CompletionStatus`: [`EInAppPurchaseState`](../enums/ue_ue.EInAppPurchaseState.md), `InAppRestorePurchaseInformation`: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InAppPurchaseRestoreInfo`](ue_ue.InAppPurchaseRestoreInfo.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:39070](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39070)

___

### OnSuccess

• **OnSuccess**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`CompletionStatus`: [`EInAppPurchaseState`](../enums/ue_ue.EInAppPurchaseState.md), `InAppRestorePurchaseInformation`: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InAppPurchaseRestoreInfo`](ue_ue.InAppPurchaseRestoreInfo.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:39069](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39069)

___

### \_\_tid\_InAppPurchaseRestoreCallbackProxy\_\_

• **\_\_tid\_InAppPurchaseRestoreCallbackProxy\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:39076](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39076)

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

### CreateProxyObjectForInAppPurchaseRestore

▸ `Static` **CreateProxyObjectForInAppPurchaseRestore**(`ConsumableProductFlags`, `PlayerController`): [`InAppPurchaseRestoreCallbackProxy`](ue_ue.InAppPurchaseRestoreCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ConsumableProductFlags` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InAppPurchaseProductRequest`](ue_ue.InAppPurchaseProductRequest.md)\> |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

[`InAppPurchaseRestoreCallbackProxy`](ue_ue.InAppPurchaseRestoreCallbackProxy.md)

#### Defined in

[ue/ue.d.ts:39071](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39071)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InAppPurchaseRestoreCallbackProxy`](ue_ue.InAppPurchaseRestoreCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InAppPurchaseRestoreCallbackProxy`](ue_ue.InAppPurchaseRestoreCallbackProxy.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:39073](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39073)

___

### Load

▸ `Static` **Load**(`InName`): [`InAppPurchaseRestoreCallbackProxy`](ue_ue.InAppPurchaseRestoreCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InAppPurchaseRestoreCallbackProxy`](ue_ue.InAppPurchaseRestoreCallbackProxy.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:39074](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39074)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:39072](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39072)
