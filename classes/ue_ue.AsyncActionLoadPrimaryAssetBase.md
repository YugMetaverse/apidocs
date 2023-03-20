[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AsyncActionLoadPrimaryAssetBase

# Class: AsyncActionLoadPrimaryAssetBase

[ue/ue](../modules/ue_ue.md).AsyncActionLoadPrimaryAssetBase

## Hierarchy

- [`BlueprintAsyncActionBase`](ue_ue.BlueprintAsyncActionBase.md)

  ↳ **`AsyncActionLoadPrimaryAssetBase`**

  ↳↳ [`AsyncActionChangePrimaryAssetBundles`](ue_ue.AsyncActionChangePrimaryAssetBundles.md)

  ↳↳ [`AsyncActionLoadPrimaryAsset`](ue_ue.AsyncActionLoadPrimaryAsset.md)

  ↳↳ [`AsyncActionLoadPrimaryAssetClass`](ue_ue.AsyncActionLoadPrimaryAssetClass.md)

  ↳↳ [`AsyncActionLoadPrimaryAssetClassList`](ue_ue.AsyncActionLoadPrimaryAssetClassList.md)

  ↳↳ [`AsyncActionLoadPrimaryAssetList`](ue_ue.AsyncActionLoadPrimaryAssetList.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AsyncActionLoadPrimaryAssetBase.md#constructor)

### Properties

- [\_\_tid\_AsyncActionLoadPrimaryAssetBase\_\_](ue_ue.AsyncActionLoadPrimaryAssetBase.md#__tid_asyncactionloadprimaryassetbase__)
- [\_\_tid\_BlueprintAsyncActionBase\_\_](ue_ue.AsyncActionLoadPrimaryAssetBase.md#__tid_blueprintasyncactionbase__)
- [\_\_tid\_Object\_\_](ue_ue.AsyncActionLoadPrimaryAssetBase.md#__tid_object__)

### Methods

- [Activate](ue_ue.AsyncActionLoadPrimaryAssetBase.md#activate)
- [CreateDefaultSubobject](ue_ue.AsyncActionLoadPrimaryAssetBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AsyncActionLoadPrimaryAssetBase.md#executeubergraph)
- [GetClass](ue_ue.AsyncActionLoadPrimaryAssetBase.md#getclass)
- [GetName](ue_ue.AsyncActionLoadPrimaryAssetBase.md#getname)
- [GetOuter](ue_ue.AsyncActionLoadPrimaryAssetBase.md#getouter)
- [GetWorld](ue_ue.AsyncActionLoadPrimaryAssetBase.md#getworld)
- [Find](ue_ue.AsyncActionLoadPrimaryAssetBase.md#find)
- [Load](ue_ue.AsyncActionLoadPrimaryAssetBase.md#load)
- [StaticClass](ue_ue.AsyncActionLoadPrimaryAssetBase.md#staticclass)

## Constructors

### constructor

• **new AsyncActionLoadPrimaryAssetBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[constructor](ue_ue.BlueprintAsyncActionBase.md#constructor)

#### Defined in

[ue/ue.d.ts:22049](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22049)

## Properties

### \_\_tid\_AsyncActionLoadPrimaryAssetBase\_\_

• **\_\_tid\_AsyncActionLoadPrimaryAssetBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:22054](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22054)

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AsyncActionLoadPrimaryAssetBase`](ue_ue.AsyncActionLoadPrimaryAssetBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AsyncActionLoadPrimaryAssetBase`](ue_ue.AsyncActionLoadPrimaryAssetBase.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Find](ue_ue.BlueprintAsyncActionBase.md#find)

#### Defined in

[ue/ue.d.ts:22051](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22051)

___

### Load

▸ `Static` **Load**(`InName`): [`AsyncActionLoadPrimaryAssetBase`](ue_ue.AsyncActionLoadPrimaryAssetBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AsyncActionLoadPrimaryAssetBase`](ue_ue.AsyncActionLoadPrimaryAssetBase.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Load](ue_ue.BlueprintAsyncActionBase.md#load)

#### Defined in

[ue/ue.d.ts:22052](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22052)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[StaticClass](ue_ue.BlueprintAsyncActionBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:22050](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22050)
