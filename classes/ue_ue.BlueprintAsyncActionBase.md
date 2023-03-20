[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BlueprintAsyncActionBase

# Class: BlueprintAsyncActionBase

[ue/ue](../modules/ue_ue.md).BlueprintAsyncActionBase

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`BlueprintAsyncActionBase`**

  ↳↳ [`ARBaseAsyncTaskBlueprintProxy`](ue_ue.ARBaseAsyncTaskBlueprintProxy.md)

  ↳↳ [`AsyncActionLoadPrimaryAssetBase`](ue_ue.AsyncActionLoadPrimaryAssetBase.md)

  ↳↳ [`AsyncActionHandleSaveGame`](ue_ue.AsyncActionHandleSaveGame.md)

  ↳↳ [`AsyncTask_LoadXRDeviceVisComponent`](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md)

  ↳↳ [`AsyncTaskDownloadImage`](ue_ue.AsyncTaskDownloadImage.md)

  ↳↳ [`LogoutCallbackProxy`](ue_ue.LogoutCallbackProxy.md)

  ↳↳ [`ShowLoginUICallbackProxy`](ue_ue.ShowLoginUICallbackProxy.md)

## Table of contents

### Constructors

- [constructor](ue_ue.BlueprintAsyncActionBase.md#constructor)

### Properties

- [\_\_tid\_BlueprintAsyncActionBase\_\_](ue_ue.BlueprintAsyncActionBase.md#__tid_blueprintasyncactionbase__)
- [\_\_tid\_Object\_\_](ue_ue.BlueprintAsyncActionBase.md#__tid_object__)

### Methods

- [Activate](ue_ue.BlueprintAsyncActionBase.md#activate)
- [CreateDefaultSubobject](ue_ue.BlueprintAsyncActionBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BlueprintAsyncActionBase.md#executeubergraph)
- [GetClass](ue_ue.BlueprintAsyncActionBase.md#getclass)
- [GetName](ue_ue.BlueprintAsyncActionBase.md#getname)
- [GetOuter](ue_ue.BlueprintAsyncActionBase.md#getouter)
- [GetWorld](ue_ue.BlueprintAsyncActionBase.md#getworld)
- [Find](ue_ue.BlueprintAsyncActionBase.md#find)
- [Load](ue_ue.BlueprintAsyncActionBase.md#load)
- [StaticClass](ue_ue.BlueprintAsyncActionBase.md#staticclass)

## Constructors

### constructor

• **new BlueprintAsyncActionBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:20666](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20666)

## Properties

### \_\_tid\_BlueprintAsyncActionBase\_\_

• **\_\_tid\_BlueprintAsyncActionBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:20672](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20672)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

## Methods

### Activate

▸ **Activate**(): `void`

#### Returns

`void`

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BlueprintAsyncActionBase`](ue_ue.BlueprintAsyncActionBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BlueprintAsyncActionBase`](ue_ue.BlueprintAsyncActionBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:20669](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20669)

___

### Load

▸ `Static` **Load**(`InName`): [`BlueprintAsyncActionBase`](ue_ue.BlueprintAsyncActionBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BlueprintAsyncActionBase`](ue_ue.BlueprintAsyncActionBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:20670](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20670)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:20668](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20668)
