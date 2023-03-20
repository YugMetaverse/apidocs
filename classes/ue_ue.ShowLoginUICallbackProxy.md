[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ShowLoginUICallbackProxy

# Class: ShowLoginUICallbackProxy

[ue/ue](../modules/ue_ue.md).ShowLoginUICallbackProxy

## Hierarchy

- [`BlueprintAsyncActionBase`](ue_ue.BlueprintAsyncActionBase.md)

  ↳ **`ShowLoginUICallbackProxy`**

## Table of contents

### Constructors

- [constructor](ue_ue.ShowLoginUICallbackProxy.md#constructor)

### Properties

- [OnFailure](ue_ue.ShowLoginUICallbackProxy.md#onfailure)
- [OnSuccess](ue_ue.ShowLoginUICallbackProxy.md#onsuccess)
- [\_\_tid\_BlueprintAsyncActionBase\_\_](ue_ue.ShowLoginUICallbackProxy.md#__tid_blueprintasyncactionbase__)
- [\_\_tid\_Object\_\_](ue_ue.ShowLoginUICallbackProxy.md#__tid_object__)
- [\_\_tid\_ShowLoginUICallbackProxy\_\_](ue_ue.ShowLoginUICallbackProxy.md#__tid_showloginuicallbackproxy__)

### Methods

- [Activate](ue_ue.ShowLoginUICallbackProxy.md#activate)
- [CreateDefaultSubobject](ue_ue.ShowLoginUICallbackProxy.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ShowLoginUICallbackProxy.md#executeubergraph)
- [GetClass](ue_ue.ShowLoginUICallbackProxy.md#getclass)
- [GetName](ue_ue.ShowLoginUICallbackProxy.md#getname)
- [GetOuter](ue_ue.ShowLoginUICallbackProxy.md#getouter)
- [GetWorld](ue_ue.ShowLoginUICallbackProxy.md#getworld)
- [Find](ue_ue.ShowLoginUICallbackProxy.md#find)
- [Load](ue_ue.ShowLoginUICallbackProxy.md#load)
- [ShowExternalLoginUI](ue_ue.ShowLoginUICallbackProxy.md#showexternalloginui)
- [StaticClass](ue_ue.ShowLoginUICallbackProxy.md#staticclass)

## Constructors

### constructor

• **new ShowLoginUICallbackProxy**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[constructor](ue_ue.BlueprintAsyncActionBase.md#constructor)

#### Defined in

[ue/ue.d.ts:60372](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60372)

## Properties

### OnFailure

• **OnFailure**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`PlayerController`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:60374](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60374)

___

### OnSuccess

• **OnSuccess**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`PlayerController`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:60373](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60373)

___

### \_\_tid\_BlueprintAsyncActionBase\_\_

• **\_\_tid\_BlueprintAsyncActionBase\_\_**: `boolean`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[__tid_BlueprintAsyncActionBase__](ue_ue.BlueprintAsyncActionBase.md#__tid_blueprintasyncactionbase__)

#### Defined in

[ue/ue.d.ts:20672](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20672)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[__tid_Object__](ue_ue.BlueprintAsyncActionBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_ShowLoginUICallbackProxy\_\_

• **\_\_tid\_ShowLoginUICallbackProxy\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:60380](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60380)

## Methods

### Activate

▸ **Activate**(): `void`

#### Returns

`void`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Activate](ue_ue.BlueprintAsyncActionBase.md#activate)

#### Defined in

[ue/ue.d.ts:20667](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20667)

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

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[CreateDefaultSubobject](ue_ue.BlueprintAsyncActionBase.md#createdefaultsubobject)

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

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[ExecuteUbergraph](ue_ue.BlueprintAsyncActionBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetClass](ue_ue.BlueprintAsyncActionBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetName](ue_ue.BlueprintAsyncActionBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetOuter](ue_ue.BlueprintAsyncActionBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetWorld](ue_ue.BlueprintAsyncActionBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ShowLoginUICallbackProxy`](ue_ue.ShowLoginUICallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ShowLoginUICallbackProxy`](ue_ue.ShowLoginUICallbackProxy.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Find](ue_ue.BlueprintAsyncActionBase.md#find)

#### Defined in

[ue/ue.d.ts:60377](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60377)

___

### Load

▸ `Static` **Load**(`InName`): [`ShowLoginUICallbackProxy`](ue_ue.ShowLoginUICallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ShowLoginUICallbackProxy`](ue_ue.ShowLoginUICallbackProxy.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Load](ue_ue.BlueprintAsyncActionBase.md#load)

#### Defined in

[ue/ue.d.ts:60378](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60378)

___

### ShowExternalLoginUI

▸ `Static` **ShowExternalLoginUI**(`WorldContextObject`, `InPlayerController`): [`ShowLoginUICallbackProxy`](ue_ue.ShowLoginUICallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `InPlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

[`ShowLoginUICallbackProxy`](ue_ue.ShowLoginUICallbackProxy.md)

#### Defined in

[ue/ue.d.ts:60375](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60375)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[StaticClass](ue_ue.BlueprintAsyncActionBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:60376](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60376)
