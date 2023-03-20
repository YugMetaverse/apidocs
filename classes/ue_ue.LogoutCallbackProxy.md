[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LogoutCallbackProxy

# Class: LogoutCallbackProxy

[ue/ue](../modules/ue_ue.md).LogoutCallbackProxy

## Hierarchy

- [`BlueprintAsyncActionBase`](ue_ue.BlueprintAsyncActionBase.md)

  ↳ **`LogoutCallbackProxy`**

## Table of contents

### Constructors

- [constructor](ue_ue.LogoutCallbackProxy.md#constructor)

### Properties

- [OnFailure](ue_ue.LogoutCallbackProxy.md#onfailure)
- [OnSuccess](ue_ue.LogoutCallbackProxy.md#onsuccess)
- [\_\_tid\_BlueprintAsyncActionBase\_\_](ue_ue.LogoutCallbackProxy.md#__tid_blueprintasyncactionbase__)
- [\_\_tid\_LogoutCallbackProxy\_\_](ue_ue.LogoutCallbackProxy.md#__tid_logoutcallbackproxy__)
- [\_\_tid\_Object\_\_](ue_ue.LogoutCallbackProxy.md#__tid_object__)

### Methods

- [Activate](ue_ue.LogoutCallbackProxy.md#activate)
- [CreateDefaultSubobject](ue_ue.LogoutCallbackProxy.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LogoutCallbackProxy.md#executeubergraph)
- [GetClass](ue_ue.LogoutCallbackProxy.md#getclass)
- [GetName](ue_ue.LogoutCallbackProxy.md#getname)
- [GetOuter](ue_ue.LogoutCallbackProxy.md#getouter)
- [GetWorld](ue_ue.LogoutCallbackProxy.md#getworld)
- [Find](ue_ue.LogoutCallbackProxy.md#find)
- [Load](ue_ue.LogoutCallbackProxy.md#load)
- [Logout](ue_ue.LogoutCallbackProxy.md#logout)
- [StaticClass](ue_ue.LogoutCallbackProxy.md#staticclass)

## Constructors

### constructor

• **new LogoutCallbackProxy**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[constructor](ue_ue.BlueprintAsyncActionBase.md#constructor)

#### Defined in

[ue/ue.d.ts:46324](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46324)

## Properties

### OnFailure

• **OnFailure**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`PlayerController`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:46326](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46326)

___

### OnSuccess

• **OnSuccess**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`PlayerController`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:46325](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46325)

___

### \_\_tid\_BlueprintAsyncActionBase\_\_

• **\_\_tid\_BlueprintAsyncActionBase\_\_**: `boolean`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[__tid_BlueprintAsyncActionBase__](ue_ue.BlueprintAsyncActionBase.md#__tid_blueprintasyncactionbase__)

#### Defined in

[ue/ue.d.ts:20672](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20672)

___

### \_\_tid\_LogoutCallbackProxy\_\_

• **\_\_tid\_LogoutCallbackProxy\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:46332](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46332)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[__tid_Object__](ue_ue.BlueprintAsyncActionBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LogoutCallbackProxy`](ue_ue.LogoutCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LogoutCallbackProxy`](ue_ue.LogoutCallbackProxy.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Find](ue_ue.BlueprintAsyncActionBase.md#find)

#### Defined in

[ue/ue.d.ts:46329](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46329)

___

### Load

▸ `Static` **Load**(`InName`): [`LogoutCallbackProxy`](ue_ue.LogoutCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LogoutCallbackProxy`](ue_ue.LogoutCallbackProxy.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Load](ue_ue.BlueprintAsyncActionBase.md#load)

#### Defined in

[ue/ue.d.ts:46330](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46330)

___

### Logout

▸ `Static` **Logout**(`WorldContextObject`, `PlayerController`): [`LogoutCallbackProxy`](ue_ue.LogoutCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

[`LogoutCallbackProxy`](ue_ue.LogoutCallbackProxy.md)

#### Defined in

[ue/ue.d.ts:46327](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46327)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[StaticClass](ue_ue.BlueprintAsyncActionBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:46328](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46328)
