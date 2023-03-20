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

## Properties

### OnFail

• **OnFail**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Texture`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture2DDynamic`](ue_ue.Texture2DDynamic.md)\>) => `void`\>

___

### OnSuccess

• **OnSuccess**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Texture`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture2DDynamic`](ue_ue.Texture2DDynamic.md)\>) => `void`\>

___

### \_\_tid\_AsyncTaskDownloadImage\_\_

• **\_\_tid\_AsyncTaskDownloadImage\_\_**: `boolean`

___

### \_\_tid\_BlueprintAsyncActionBase\_\_

• **\_\_tid\_BlueprintAsyncActionBase\_\_**: `boolean`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[__tid_BlueprintAsyncActionBase__](ue_ue.BlueprintAsyncActionBase.md#__tid_blueprintasyncactionbase__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[__tid_Object__](ue_ue.BlueprintAsyncActionBase.md#__tid_object__)

## Methods

### Activate

▸ **Activate**(): `void`

#### Returns

`void`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Activate](ue_ue.BlueprintAsyncActionBase.md#activate)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetClass](ue_ue.BlueprintAsyncActionBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetName](ue_ue.BlueprintAsyncActionBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetOuter](ue_ue.BlueprintAsyncActionBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetWorld](ue_ue.BlueprintAsyncActionBase.md#getworld)

___

### DownloadImage

▸ `Static` **DownloadImage**(`URL`): [`AsyncTaskDownloadImage`](ue_ue.AsyncTaskDownloadImage.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `URL` | `string` |

#### Returns

[`AsyncTaskDownloadImage`](ue_ue.AsyncTaskDownloadImage.md)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[StaticClass](ue_ue.BlueprintAsyncActionBase.md#staticclass)
