[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AssetManager

# Class: AssetManager

[ue/ue](../modules/ue_ue.md).AssetManager

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AssetManager`**

## Table of contents

### Constructors

- [constructor](ue_ue.AssetManager.md#constructor)

### Properties

- [NumberOfSpawnedNotifications](ue_ue.AssetManager.md#numberofspawnednotifications)
- [ObjectReferenceList](ue_ue.AssetManager.md#objectreferencelist)
- [\_\_tid\_AssetManager\_\_](ue_ue.AssetManager.md#__tid_assetmanager__)
- [\_\_tid\_Object\_\_](ue_ue.AssetManager.md#__tid_object__)
- [bIncludeOnlyOnDiskAssets](ue_ue.AssetManager.md#bincludeonlyondiskassets)
- [bIsBulkScanning](ue_ue.AssetManager.md#bisbulkscanning)
- [bIsGlobalAsyncScanEnvironment](ue_ue.AssetManager.md#bisglobalasyncscanenvironment)
- [bIsLoadingFromPakFiles](ue_ue.AssetManager.md#bisloadingfrompakfiles)
- [bIsManagementDatabaseCurrent](ue_ue.AssetManager.md#bismanagementdatabasecurrent)
- [bIsPrimaryAssetDirectoryCurrent](ue_ue.AssetManager.md#bisprimaryassetdirectorycurrent)
- [bOnlyCookProductionAssets](ue_ue.AssetManager.md#bonlycookproductionassets)
- [bShouldAcquireMissingChunksOnLoad](ue_ue.AssetManager.md#bshouldacquiremissingchunksonload)
- [bShouldGuessTypeAndName](ue_ue.AssetManager.md#bshouldguesstypeandname)
- [bShouldUseSynchronousLoad](ue_ue.AssetManager.md#bshouldusesynchronousload)
- [bUpdateManagementDatabaseAfterScan](ue_ue.AssetManager.md#bupdatemanagementdatabaseafterscan)

### Methods

- [CreateDefaultSubobject](ue_ue.AssetManager.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AssetManager.md#executeubergraph)
- [GetClass](ue_ue.AssetManager.md#getclass)
- [GetName](ue_ue.AssetManager.md#getname)
- [GetOuter](ue_ue.AssetManager.md#getouter)
- [GetWorld](ue_ue.AssetManager.md#getworld)
- [Find](ue_ue.AssetManager.md#find)
- [Load](ue_ue.AssetManager.md#load)
- [StaticClass](ue_ue.AssetManager.md#staticclass)

## Constructors

### constructor

• **new AssetManager**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:21606](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21606)

## Properties

### NumberOfSpawnedNotifications

• **NumberOfSpawnedNotifications**: `number`

#### Defined in

[ue/ue.d.ts:21619](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21619)

___

### ObjectReferenceList

• **ObjectReferenceList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:21607](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21607)

___

### \_\_tid\_AssetManager\_\_

• **\_\_tid\_AssetManager\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:21624](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21624)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bIncludeOnlyOnDiskAssets

• **bIncludeOnlyOnDiskAssets**: `boolean`

#### Defined in

[ue/ue.d.ts:21618](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21618)

___

### bIsBulkScanning

• **bIsBulkScanning**: `boolean`

#### Defined in

[ue/ue.d.ts:21614](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21614)

___

### bIsGlobalAsyncScanEnvironment

• **bIsGlobalAsyncScanEnvironment**: `boolean`

#### Defined in

[ue/ue.d.ts:21608](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21608)

___

### bIsLoadingFromPakFiles

• **bIsLoadingFromPakFiles**: `boolean`

#### Defined in

[ue/ue.d.ts:21611](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21611)

___

### bIsManagementDatabaseCurrent

• **bIsManagementDatabaseCurrent**: `boolean`

#### Defined in

[ue/ue.d.ts:21616](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21616)

___

### bIsPrimaryAssetDirectoryCurrent

• **bIsPrimaryAssetDirectoryCurrent**: `boolean`

#### Defined in

[ue/ue.d.ts:21615](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21615)

___

### bOnlyCookProductionAssets

• **bOnlyCookProductionAssets**: `boolean`

#### Defined in

[ue/ue.d.ts:21613](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21613)

___

### bShouldAcquireMissingChunksOnLoad

• **bShouldAcquireMissingChunksOnLoad**: `boolean`

#### Defined in

[ue/ue.d.ts:21612](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21612)

___

### bShouldGuessTypeAndName

• **bShouldGuessTypeAndName**: `boolean`

#### Defined in

[ue/ue.d.ts:21609](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21609)

___

### bShouldUseSynchronousLoad

• **bShouldUseSynchronousLoad**: `boolean`

#### Defined in

[ue/ue.d.ts:21610](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21610)

___

### bUpdateManagementDatabaseAfterScan

• **bUpdateManagementDatabaseAfterScan**: `boolean`

#### Defined in

[ue/ue.d.ts:21617](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21617)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AssetManager`](ue_ue.AssetManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AssetManager`](ue_ue.AssetManager.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:21621](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21621)

___

### Load

▸ `Static` **Load**(`InName`): [`AssetManager`](ue_ue.AssetManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AssetManager`](ue_ue.AssetManager.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:21622](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21622)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:21620](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21620)
