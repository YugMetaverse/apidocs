[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AsyncTaskDownloadImage

# Class: AsyncTaskDownloadImage

[ue/ue](../modules/ue_ue.md).AsyncTaskDownloadImage

## Hierarchy

- [`BlueprintAsyncActionBase`](ue_ue.BlueprintAsyncActionBase.md)

  ↳ **`AsyncTaskDownloadImage`**

## Table of contents

### Constructors

- [constructor](ue_ue.AsyncTaskDownloadImage.md#constructor)

### Properties

- [OnFail](ue_ue.AsyncTaskDownloadImage.md#onfail)
- [OnSuccess](ue_ue.AsyncTaskDownloadImage.md#onsuccess)
- [\_\_tid\_AsyncTaskDownloadImage\_\_](ue_ue.AsyncTaskDownloadImage.md#__tid_asynctaskdownloadimage__)
- [\_\_tid\_BlueprintAsyncActionBase\_\_](ue_ue.AsyncTaskDownloadImage.md#__tid_blueprintasyncactionbase__)
- [\_\_tid\_Object\_\_](ue_ue.AsyncTaskDownloadImage.md#__tid_object__)

### Methods

- [Activate](ue_ue.AsyncTaskDownloadImage.md#activate)
- [CreateDefaultSubobject](ue_ue.AsyncTaskDownloadImage.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AsyncTaskDownloadImage.md#executeubergraph)
- [GetClass](ue_ue.AsyncTaskDownloadImage.md#getclass)
- [GetName](ue_ue.AsyncTaskDownloadImage.md#getname)
- [GetOuter](ue_ue.AsyncTaskDownloadImage.md#getouter)
- [GetWorld](ue_ue.AsyncTaskDownloadImage.md#getworld)
- [DownloadImage](ue_ue.AsyncTaskDownloadImage.md#downloadimage)
- [Find](ue_ue.AsyncTaskDownloadImage.md#find)
- [Load](ue_ue.AsyncTaskDownloadImage.md#load)
- [StaticClass](ue_ue.AsyncTaskDownloadImage.md#staticclass)

## Constructors

### constructor

• **new AsyncTaskDownloadImage**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[constructor](ue_ue.BlueprintAsyncActionBase.md#constructor)

#### Defined in

[ue/ue.d.ts:22185](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22185)

## Properties

### OnFail

• **OnFail**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Texture`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture2DDynamic`](ue_ue.Texture2DDynamic.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:22187](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22187)

___

### OnSuccess

• **OnSuccess**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Texture`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture2DDynamic`](ue_ue.Texture2DDynamic.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:22186](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22186)

___

### \_\_tid\_AsyncTaskDownloadImage\_\_

• **\_\_tid\_AsyncTaskDownloadImage\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:22193](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22193)

___

### \_\_tid\_BlueprintAsyncActionBase\_\_

• **\_\_tid\_BlueprintAsyncActionBase\_\_**: `boolean`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[__tid_BlueprintAsyncActionBase__](ue_ue.BlueprintAsyncActionBase.md#__tid_blueprintasyncactionbase__)

#### Defined in

[ue/ue.d.ts:20672](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20672)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[__tid_Object__](ue_ue.BlueprintAsyncActionBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

## Methods

### Activate

▸ **Activate**(): `void`

#### Returns

`void`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Activate](ue_ue.BlueprintAsyncActionBase.md#activate)

#### Defined in

[ue/ue.d.ts:20667](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20667)

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

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[ExecuteUbergraph](ue_ue.BlueprintAsyncActionBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetClass](ue_ue.BlueprintAsyncActionBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetName](ue_ue.BlueprintAsyncActionBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetOuter](ue_ue.BlueprintAsyncActionBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetWorld](ue_ue.BlueprintAsyncActionBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### DownloadImage

▸ `Static` **DownloadImage**(`URL`): [`AsyncTaskDownloadImage`](ue_ue.AsyncTaskDownloadImage.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `URL` | `string` |

#### Returns

[`AsyncTaskDownloadImage`](ue_ue.AsyncTaskDownloadImage.md)

#### Defined in

[ue/ue.d.ts:22188](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22188)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AsyncTaskDownloadImage`](ue_ue.AsyncTaskDownloadImage.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AsyncTaskDownloadImage`](ue_ue.AsyncTaskDownloadImage.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Find](ue_ue.BlueprintAsyncActionBase.md#find)

#### Defined in

[ue/ue.d.ts:22190](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22190)

___

### Load

▸ `Static` **Load**(`InName`): [`AsyncTaskDownloadImage`](ue_ue.AsyncTaskDownloadImage.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AsyncTaskDownloadImage`](ue_ue.AsyncTaskDownloadImage.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Load](ue_ue.BlueprintAsyncActionBase.md#load)

#### Defined in

[ue/ue.d.ts:22191](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22191)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[StaticClass](ue_ue.BlueprintAsyncActionBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:22189](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22189)
