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

## Properties

### NumberOfSpawnedNotifications

• **NumberOfSpawnedNotifications**: `number`

___

### ObjectReferenceList

• **ObjectReferenceList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

___

### \_\_tid\_AssetManager\_\_

• **\_\_tid\_AssetManager\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bIncludeOnlyOnDiskAssets

• **bIncludeOnlyOnDiskAssets**: `boolean`

___

### bIsBulkScanning

• **bIsBulkScanning**: `boolean`

___

### bIsGlobalAsyncScanEnvironment

• **bIsGlobalAsyncScanEnvironment**: `boolean`

___

### bIsLoadingFromPakFiles

• **bIsLoadingFromPakFiles**: `boolean`

___

### bIsManagementDatabaseCurrent

• **bIsManagementDatabaseCurrent**: `boolean`

___

### bIsPrimaryAssetDirectoryCurrent

• **bIsPrimaryAssetDirectoryCurrent**: `boolean`

___

### bOnlyCookProductionAssets

• **bOnlyCookProductionAssets**: `boolean`

___

### bShouldAcquireMissingChunksOnLoad

• **bShouldAcquireMissingChunksOnLoad**: `boolean`

___

### bShouldGuessTypeAndName

• **bShouldGuessTypeAndName**: `boolean`

___

### bShouldUseSynchronousLoad

• **bShouldUseSynchronousLoad**: `boolean`

___

### bUpdateManagementDatabaseAfterScan

• **bUpdateManagementDatabaseAfterScan**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
